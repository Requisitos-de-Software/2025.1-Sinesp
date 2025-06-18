# Casos de Uso – Matheus de Alcântara

## UC27 – Visualizar Histórico de Consultas Realizadas

<p align="center">Tabela 1 - Caso de Uso 27 </p>

| Campo              | Descrição                                                                                                                                       |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC27"></a>UC27                 | Visualizar histórico de consultas realizadas                                                                                   |
| Descrição          | Permitir ao usuário visualizar a lista de todas as consultas realizadas, com data, profissional e especialidade.                               |
| Ator               | Usuário cadastrado no plano de saúde GDF Saúde                                                           |
| Pré-condições      | O usuário deve estar autenticado no sistema.                                                             |
| Ação               | O usuário acessa a seção "Histórico de Consultas".                                                      |
| Fluxo principal    | 1. Usuário faz login no sistema.<br>2. Usuário navega até a seção "Histórico de Consultas".<br>3. Sistema recupera e exibe a lista de consultas realizadas, ordenadas da mais recente para a mais antiga.<br>4. Cada item exibe data, profissional e especialidade.<br>5. Usuário pode buscar ou filtrar consultas por período, profissional ou especialidade.<br>6. Usuário seleciona uma consulta para ver detalhes.<br>7. Sistema exibe detalhes completos da consulta selecionada.<br>8. Usuário retorna à lista ou encerra a navegação. |
| Fluxo alternativo  | A1. Se não houver consultas registradas:<br>&nbsp;&nbsp;- Sistema exibe mensagem "Nenhuma consulta encontrada".<br>&nbsp;&nbsp;- Usuário pode retornar ao menu principal. |
| Fluxo de exceção   | E1. Falha na recuperação dos dados:<br>&nbsp;&nbsp;- Sistema exibe mensagem "Erro ao carregar histórico de consultas".<br>&nbsp;&nbsp;- Usuário pode tentar novamente ou contatar o suporte.<br>E2. Sessão expirada:<br>&nbsp;&nbsp;- Sistema solicita novo login. |
| Pós-condições      | O usuário visualizou seu histórico de consultas.                                                         |
| Rastreabilidade    | [RF09.1](../../elicitacao/requisitos_finais.md#RF09.1)                                                  |
| Data de criação    | 15/05/2025                                                                                               |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## UC28 – Visualizar Histórico de Exames Realizados

<p align="center">Tabela 2 - Caso de Uso 28 </p>

| Campo              | Descrição                                                                                                  |
|--------------------|----------------------------------------------------------------------------------------------------------|
| <a id="UC28"></a>UC28                 | Visualizar histórico de exames realizados                                                |
| Descrição          | Permitir ao usuário visualizar a lista de todos os exames realizados, com nome do exame e data.           |
| Ator               | Usuário cadastrado no plano de saúde GDF Saúde                                                           |
| Pré-condições      | O usuário deve estar autenticado no sistema.                                                             |
| Ação               | O usuário acessa a seção "Histórico de Exames".                                                          |
| Fluxo principal    | 1. Usuário faz login.<br>2. Acessa "Histórico de Exames".<br>3. Sistema exibe lista de exames realizados.<br>4. Cada item mostra nome do exame e data.<br>5. Usuário pode buscar ou filtrar exames.<br>6. Usuário seleciona exame para ver detalhes.<br>7. Sistema exibe detalhes do exame.<br>8. Usuário retorna à lista ou encerra. |
| Fluxo alternativo  | A1. Se não houver exames:<br>&nbsp;&nbsp;- Sistema exibe "Nenhum exame encontrado".<br>&nbsp;&nbsp;- Usuário pode retornar ao menu principal. |
| Fluxo de exceção   | E1. Falha ao carregar exames:<br>&nbsp;&nbsp;- Sistema exibe "Erro ao carregar exames".<br>&nbsp;&nbsp;- Usuário pode tentar novamente ou contatar suporte.<br>E2. Sessão expirada:<br>&nbsp;&nbsp;- Sistema solicita novo login. |
| Pós-condições      | O usuário visualizou seu histórico de exames.                                                            |
| Rastreabilidade    | [RF09.2](../../elicitacao/requisitos_finais.md#RF09.2)                                                  |
| Data de criação    | 15/05/2025                                                                                               |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## UC29 – Visualizar Resultados de Exames Laboratoriais

<p align="center">Tabela 3 - Caso de Uso 29 </p>

| Campo              | Descrição                                                                                                  |
|--------------------|----------------------------------------------------------------------------------------------------------|
| <a id="UC29"></a>UC29                 | Visualizar resultados de exames laboratoriais                                            |
| Descrição          | Permitir ao usuário acessar e visualizar os resultados de exames laboratoriais realizados.                |
| Ator               | Usuário cadastrado no plano de saúde GDF Saúde                                                           |
| Pré-condições      | O usuário deve estar autenticado e ter exames laboratoriais com resultado disponível.                     |
| Ação               | O usuário acessa a seção "Histórico de Exames" e seleciona um exame com resultado.                       |
| Fluxo principal    | 1. Usuário faz login.<br>2. Acessa "Histórico de Exames".<br>3. Sistema exibe lista de exames laboratoriais.<br>4. Exames com resultado disponível exibem botão "Ver Resultado".<br>5. Usuário clica para visualizar ou baixar o resultado.<br>6. Sistema exibe ou permite download do resultado.<br>7. Usuário retorna à lista ou encerra. |
| Fluxo alternativo  | A1. Se não houver resultados disponíveis:<br>&nbsp;&nbsp;- Sistema exibe "Nenhum resultado disponível".<br>&nbsp;&nbsp;- Usuário pode retornar ao menu principal. |
| Fluxo de exceção   | E1. Falha ao carregar resultados:<br>&nbsp;&nbsp;- Sistema exibe "Erro ao carregar resultados".<br>&nbsp;&nbsp;- Usuário pode tentar novamente ou contatar suporte.<br>E2. Arquivo corrompido:<br>&nbsp;&nbsp;- Sistema exibe mensagem de erro e orienta novo download.<br>E3. Sessão expirada:<br>&nbsp;&nbsp;- Sistema solicita novo login. |
| Pós-condições      | O usuário visualizou o resultado do exame laboratorial.                                                  |
| Rastreabilidade    | [RF09.3](../../elicitacao/requisitos_finais.md#RF09.3)                                                  |
| Data de criação    | 15/05/2025                                                                                               |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## UC30 – Visualizar Histórico de Coparticipações

<p align="center">Tabela 4 - Caso de Uso 30 </p>

| Campo              | Descrição                                                                                                  |
|--------------------|----------------------------------------------------------------------------------------------------------|
| <a id="UC30"></a>UC30                 | Visualizar histórico de coparticipações                                                  |
| Descrição          | Permitir ao usuário acessar o histórico detalhado de cobranças de coparticipação.                         |
| Ator               | Usuário cadastrado no plano de saúde GDF Saúde                                                           |
| Pré-condições      | O usuário deve estar autenticado no sistema.                                                             |
| Ação               | O usuário acessa a seção "Histórico de Coparticipações" ou "Financeiro".                                 |
| Fluxo principal    | 1. Usuário faz login.<br>2. Acessa "Histórico de Coparticipações".<br>3. Sistema exibe lista de cobranças de coparticipação.<br>4. Cada item mostra serviço, data e valor cobrado.<br>5. Usuário pode buscar ou filtrar cobranças.<br>6. Usuário seleciona uma cobrança para ver detalhes.<br>7. Sistema exibe detalhes completos.<br>8. Usuário retorna à lista ou encerra. |
| Fluxo alternativo  | A1. Se não houver cobranças:<br>&nbsp;&nbsp;- Sistema exibe "Nenhuma coparticipação encontrada".<br>&nbsp;&nbsp;- Usuário pode retornar ao menu principal. |
| Fluxo de exceção   | E1. Falha ao carregar histórico:<br>&nbsp;&nbsp;- Sistema exibe "Erro ao carregar histórico de coparticipações".<br>&nbsp;&nbsp;- Usuário pode tentar novamente ou contatar suporte.<br>E2. Sessão expirada:<br>&nbsp;&nbsp;- Sistema solicita novo login. |
| Pós-condições      | O usuário visualizou seu histórico de coparticipações.                                                   |
| Rastreabilidade    | [RF09.4](../../elicitacao/requisitos_finais.md#RF09.4)                                                  |
| Data de criação    | 15/05/2025                                                                                               |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## UC31 – Favoritar Horários de Consulta

<p align="center">Tabela 5 - Caso de Uso 31 </p>

| Campo              | Descrição                                                                                                  |
|--------------------|----------------------------------------------------------------------------------------------------------|
| <a id="UC31"></a>UC31                 | Favoritar horários de consulta                                                          |
| Descrição          | Permitir ao usuário marcar horários preferidos para agendamentos futuros.                                |
| Ator               | Usuário cadastrado no plano de saúde GDF Saúde                                                           |
| Pré-condições      | O sistema deve exibir horários disponíveis para consulta.                                                |
| Ação               | O usuário acessa a seção de agendamento, seleciona horários para favoritar e confirma a ação.            |
| Fluxo principal    | 1. Usuário faz login.<br>2. Acessa a seção de agendamento.<br>3. Sistema exibe horários disponíveis.<br>4. Usuário seleciona um ou mais horários para favoritar.<br>5. Usuário confirma a ação.<br>6. Sistema salva horários favoritos no perfil do usuário.<br>7. Sistema exibe confirmação de sucesso.<br>8. Usuário pode visualizar ou editar favoritos. |
| Fluxo alternativo  | A1. Horário indisponível:<br>&nbsp;&nbsp;- Sistema notifica "Horário não disponível" e remove da seleção.<br>&nbsp;&nbsp;- Usuário pode escolher outro horário.<br>A2. Limite de favoritos atingido:<br>&nbsp;&nbsp;- Sistema informa o limite e impede seleção adicional. |
| Fluxo de exceção   | E1. Erro ao salvar favoritos:<br>&nbsp;&nbsp;- Sistema exibe "Erro ao salvar horário favorito" e oferece tentar novamente.<br>E2. Sessão expirada:<br>&nbsp;&nbsp;- Sistema solicita novo login. |
| Pós-condições      | Horários favoritados salvos no perfil do usuário.                                                        |
| Rastreabilidade    | [RF10](../../elicitacao/requisitos_finais.md#RF10)                                                      |
| Data de criação    | 15/05/2025                                                                                               |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## UC32 – Solicitar Reembolso de Cobrança Indevida

<p align="center">Tabela 6 - Caso de Uso 32 </p>

| Campo              | Descrição                                                                                                  |
|--------------------|----------------------------------------------------------------------------------------------------------|
| <a id="UC32"></a>UC32                 | Solicitar reembolso de cobrança indevida                                                |
| Descrição          | Permitir ao usuário solicitar reembolso de valores cobrados indevidamente, fornecendo justificativa e documentos. |
| Ator               | Usuário cadastrado no plano de saúde GDF Saúde                                                           |
| Pré-condições      | 1. O usuário deve ter uma cobrança registrada.<br>2. Solicitação feita em até 30 dias da cobrança.        |
| Ação               | O usuário acessa a seção de reembolso, seleciona a cobrança, preenche justificativa, anexa documentos e envia. |
| Fluxo principal    | 1. Usuário faz login.<br>2. Acessa a seção de reembolso.<br>3. Sistema exibe lista de cobranças.<br>4. Usuário seleciona cobrança indevida.<br>5. Sistema apresenta formulário para justificativa e anexos.<br>6. Usuário preenche justificativa e anexa documentos.<br>7. Usuário envia solicitação.<br>8. Sistema valida dados e envia solicitação.<br>9. Sistema notifica usuário sobre o recebimento.<br>10. Usuário pode acompanhar o status da solicitação. |
| Fluxo alternativo  | A1. Documentação incompleta:<br>&nbsp;&nbsp;- Sistema solicita arquivos faltantes.<br>&nbsp;&nbsp;- Usuário anexa documentos adicionais.<br>&nbsp;&nbsp;- Sistema retoma validação. |
| Fluxo de exceção   | E1. Erro técnico ao enviar solicitação:<br>&nbsp;&nbsp;- Sistema exibe "Erro ao enviar solicitação" e oferece tentar novamente.<br>E2. Prazo excedido:<br>&nbsp;&nbsp;- Sistema informa que o prazo para solicitação expirou e impede envio.<br>E3. Sessão expirada:<br>&nbsp;&nbsp;- Sistema solicita novo login. |
| Pós-condições      | Solicitação registrada e enviada para análise.                                                           |
| Rastreabilidade    | [RF20](../../elicitacao/requisitos_finais.md#RF20)                                                      |
| Data de criação    | 15/05/2025                                                                                               |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---
