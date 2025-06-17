## Cenário 9: Visualizar Histórico de Consultas Realizadas

**Requisito Associado:** [RF09.1](../../elicitacao/requisitos_finais.md#RF09.1)

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | CE09      |
| **Título**      | Visualizar Histórico de Consultas Realizadas |
| **Metas/Objetivos** | Permitir ao usuário acessar e consultar todas as consultas realizadas, com detalhes de data, profissional e especialidade. |
| **Contexto**    | Usuário autenticado deseja revisar seu histórico de consultas para controle pessoal ou agendamento de retornos. |
| **Ator(es)**    | - Usuário cadastrado no GDF Saúde |
| **Recursos**    | - App GDF Saúde<br>- Banco de dados de consultas<br>- Conexão à internet<br>- Interface de histórico com filtros e busca<br>- Sistema de autenticação<br>- Sistema de exportação/visualização de detalhes |
| **Exceções**    | - Usuário sem consultas registradas: sistema exibe mensagem "Nenhuma consulta encontrada".<br>- Erro técnico ao carregar histórico: sistema exibe mensagem de erro e opção de tentar novamente.<br>- Falha de autenticação: usuário é redirecionado para tela de login.<br>- Conexão instável: sistema exibe aviso e tenta recarregar.<br>- Dados corrompidos: sistema orienta a contatar suporte. |
| **Restrições**  | - Apenas usuários autenticados podem acessar.<br>- Dados protegidos por LGPD.<br>- Histórico disponível apenas para titulares e dependentes autorizados.<br>- Acesso permitido somente em dispositivos compatíveis.<br>- Tempo de carregamento deve ser inferior a 2 segundos.<br>- Histórico limitado aos últimos 5 anos. |
| **Episódios**   | 1. Usuário faz login.<br>2. Acessa "Histórico de Consultas".<br>3. Sistema exibe lista de consultas.<br>4. Usuário pode filtrar por período, profissional ou especialidade.<br>5. Usuário busca por palavra-chave.<br>6. Seleciona consulta para ver detalhes (data, profissional, local, status, observações).<br>7. Usuário pode exportar ou compartilhar o histórico.<br>8. Se não houver consultas, sistema exibe mensagem adequada.<br>9. Se erro, sistema oferece opção de tentar novamente ou contatar suporte. |

---

## Cenário X: Visualizar Histórico de Exames Realizados

**Requisito Associado:** [RF09.2](../../elicitacao/requisitos_finais.md#RF09.2)

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | CEXX      |
| **Título**      | Visualizar Histórico de Exames Realizados |
| **Metas/Objetivos** | Permitir ao usuário consultar todos os exames realizados, com nome, data e status. |
| **Contexto**    | Usuário autenticado deseja acompanhar exames feitos para controle de saúde e acompanhamento médico. |
| **Ator(es)**    | - Usuário cadastrado no GDF Saúde |
| **Recursos**    | - App GDF Saúde<br>- Banco de dados de exames<br>- Conexão à internet<br>- Interface de histórico de exames com filtros e busca<br>- Sistema de autenticação<br>- Sistema de exportação/visualização de detalhes |
| **Exceções**    | - Usuário sem exames registrados: sistema exibe "Nenhum exame encontrado".<br>- Erro técnico ao carregar histórico: sistema exibe mensagem de erro e opção de tentar novamente.<br>- Falha de autenticação: usuário é redirecionado para tela de login.<br>- Conexão instável: sistema exibe aviso e tenta recarregar.<br>- Dados corrompidos: sistema orienta a contatar suporte. |
| **Restrições**  | - Apenas usuários autenticados podem acessar.<br>- Dados protegidos por LGPD.<br>- Histórico disponível apenas para titulares e dependentes autorizados.<br>- Acesso permitido somente em dispositivos compatíveis.<br>- Tempo de carregamento deve ser inferior a 2 segundos.<br>- Histórico limitado aos últimos 5 anos. |
| **Episódios**   | 1. Usuário faz login.<br>2. Acessa "Histórico de Exames".<br>3. Sistema exibe lista de exames realizados.<br>4. Usuário pode filtrar por período, tipo de exame ou status.<br>5. Usuário busca por palavra-chave.<br>6. Seleciona exame para ver detalhes (nome, data, local, status, observações).<br>7. Usuário pode exportar ou compartilhar o histórico.<br>8. Se não houver exames, sistema exibe mensagem adequada.<br>9. Se erro, sistema oferece opção de tentar novamente ou contatar suporte. |

---

## Cenário X: Visualizar Resultados de Exames Laboratoriais

**Requisito Associado:** [RF09.3](../../elicitacao/requisitos_finais.md#RF09.3)

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | CEXX      |
| **Título**      | Visualizar Resultados de Exames Laboratoriais |
| **Metas/Objetivos** | Permitir ao usuário acessar resultados de exames laboratoriais realizados, visualizar e baixar arquivos de resultados. |
| **Contexto**    | Usuário autenticado deseja consultar resultados de exames para acompanhamento médico ou compartilhamento com profissionais de saúde. |
| **Ator(es)**    | - Usuário cadastrado no GDF Saúde |
| **Recursos**    | - App GDF Saúde<br>- Banco de dados de exames/resultados<br>- Conexão à internet<br>- Interface de histórico de exames com acesso a resultados<br>- Sistema de autenticação<br>- Visualizador de PDF/imagens<br>- Sistema de exportação/download de resultados |
| **Exceções**    | - Resultado não disponível: sistema exibe "Resultado ainda não disponível".<br>- Erro técnico ao carregar resultado: sistema exibe mensagem de erro e opção de tentar novamente.<br>- Falha de autenticação: usuário é redirecionado para tela de login.<br>- Conexão instável: sistema exibe aviso e tenta recarregar.<br>- Arquivo corrompido: sistema orienta a contatar suporte.<br>- Resultado restrito por política de privacidade: sistema exibe mensagem de acesso negado. |
| **Restrições**  | - Apenas usuários autenticados podem acessar.<br>- Dados protegidos por LGPD.<br>- Resultados disponíveis apenas para exames realizados pelo plano.<br>- Download permitido apenas em dispositivos compatíveis.<br>- Tempo de carregamento deve ser inferior a 2 segundos.<br>- Resultados disponíveis por até 5 anos após realização do exame. |
| **Episódios**   | 1. Usuário faz login.<br>2. Acessa "Histórico de Exames".<br>3. Seleciona exame com resultado disponível.<br>4. Sistema exibe botão/link para visualizar ou baixar resultado.<br>5. Usuário visualiza resultado em tela ou faz download (PDF, imagem).<br>6. Usuário pode compartilhar resultado com profissional de saúde.<br>7. Se resultado não disponível, sistema exibe mensagem adequada.<br>8. Se erro, sistema oferece opção de tentar novamente ou contatar suporte. |

---

## Cenário X: Visualizar Histórico de Coparticipações

**Requisito Associado:** [RF09.4](../../elicitacao/requisitos_finais.md#RF09.4)

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | CEXX      |
| **Título**      | Visualizar Histórico de Coparticipações |
| **Metas/Objetivos** | Permitir ao usuário consultar cobranças de coparticipação detalhadas, visualizar valores, datas, serviços e status de pagamento. |
| **Contexto**    | Usuário autenticado deseja conferir valores cobrados em coparticipação para controle financeiro e contestação de cobranças. |
| **Ator(es)**    | - Usuário cadastrado no GDF Saúde |
| **Recursos**    | - App GDF Saúde<br>- Banco de dados financeiro<br>- Conexão à internet<br>- Interface de histórico de coparticipações com filtros e busca<br>- Sistema de autenticação<br>- Sistema de exportação/visualização de detalhes<br>- Canal de contestação de cobrança |
| **Exceções**    | - Nenhuma cobrança registrada: sistema exibe "Nenhuma coparticipação encontrada".<br>- Erro técnico ao carregar histórico: sistema exibe mensagem de erro e opção de tentar novamente.<br>- Falha de autenticação: usuário é redirecionado para tela de login.<br>- Conexão instável: sistema exibe aviso e tenta recarregar.<br>- Dados corrompidos: sistema orienta a contatar suporte.<br>- Contestação não permitida para cobranças antigas: sistema exibe mensagem de restrição. |
| **Restrições**  | - Apenas usuários autenticados podem acessar.<br>- Dados protegidos por LGPD.<br>- Histórico disponível apenas para titulares e dependentes autorizados.<br>- Contestação permitida apenas para cobranças dos últimos 30 dias.<br>- Tempo de carregamento deve ser inferior a 2 segundos.<br>- Histórico limitado aos últimos 5 anos. |
| **Episódios**   | 1. Usuário faz login.<br>2. Acessa "Histórico de Coparticipações".<br>3. Sistema exibe lista de cobranças detalhadas (valor, data, serviço, status).<br>4. Usuário pode filtrar por período, tipo de serviço ou status.<br>5. Usuário busca por palavra-chave.<br>6. Seleciona cobrança para ver detalhes.<br>7. Usuário pode exportar histórico ou iniciar contestação.<br>8. Se não houver cobranças, sistema exibe mensagem adequada.<br>9. Se erro, sistema oferece opção de tentar novamente ou contatar suporte. |

---

## Cenário 5: Favoritar Horários de Consulta

**Requisito Associado:** [RF10](../../elicitacao/requisitos_finais.md#RF10)

| Elemento        | Descrição |
|-----------------|-----------|
| **Título**      | Favoritar Horários de Consulta |
| **Metas/Objetivos** | Permitir ao usuário marcar horários preferidos para agendamento futuro, facilitando o acesso rápido a horários desejados. |
| **Contexto**    | Usuário autenticado deseja salvar horários de consulta como favoritos para agilizar futuros agendamentos. |
| **Ator(es)**    | - Usuário cadastrado no GDF Saúde |
| **Recursos**    | - App GDF Saúde<br>- Interface de agendamento<br>- Banco de dados de favoritos<br>- Conexão à internet<br>- Sistema de autenticação<br>- Notificações de disponibilidade de horários favoritos |
| **Exceções**    | - Horário indisponível: sistema exibe "Horário não disponível para favoritar".<br>- Limite de favoritos atingido: sistema exibe mensagem e impede novo favorito.<br>- Erro ao salvar favorito: sistema exibe mensagem de erro e opção de tentar novamente.<br>- Falha de autenticação: usuário é redirecionado para tela de login.<br>- Conexão instável: sistema exibe aviso e tenta recarregar.<br>- Dados corrompidos: sistema orienta a contatar suporte. |
| **Restrições**  | - Apenas usuários autenticados podem acessar.<br>- Dados protegidos por LGPD.<br>- Limite de 5 favoritos por especialidade ou médico.<br>- Apenas horários disponíveis podem ser favoritados.<br>- Favoritos expiram após 30 dias sem uso.<br>- Tempo de resposta para favoritar deve ser inferior a 1 segundo. |
| **Episódios**   | 1. Usuário faz login.<br>2. Acessa agendamento.<br>3. Visualiza horários disponíveis.<br>4. Marca um ou mais como favoritos.<br>5. Sistema confirma e salva favoritos.<br>6. Usuário pode acessar lista de favoritos em futuras buscas.<br>7. Sistema notifica usuário se horário favorito ficar disponível.<br>8. Se limite atingido, sistema exibe mensagem.<br>9. Se erro, sistema oferece opção de tentar novamente ou contatar suporte. |

---

## Cenário 6: Solicitar Reembolso de Cobrança Indevida

**Requisito Associado:** [RF20](../../elicitacao/requisitos_finais.md#RF20)

| Elemento        | Descrição |
|-----------------|-----------|
| **Título**      | Solicitar Reembolso de Cobrança Indevida |
| **Metas/Objetivos** | Permitir ao usuário solicitar reembolso de valores cobrados indevidamente, anexando justificativa e documentos, e acompanhar o status da solicitação. |
| **Contexto**    | Usuário autenticado identifica cobrança indevida e deseja solicitar reembolso pelo app. |
| **Ator(es)**    | - Usuário cadastrado no GDF Saúde |
| **Recursos**    | - App GDF Saúde<br>- Interface de reembolso<br>- Banco de dados financeiro<br>- Upload de documentos (PDF, imagem)<br>- Conexão à internet<br>- Sistema de autenticação<br>- Canal de acompanhamento de solicitações<br>- Notificações de atualização de status |
| **Exceções**    | - Documentação incompleta: sistema solicita anexos obrigatórios.<br>- Solicitação fora do prazo (após 30 dias): sistema exibe mensagem de restrição.<br>- Erro técnico ao enviar solicitação: sistema exibe mensagem de erro e opção de tentar novamente.<br>- Falha de autenticação: usuário é redirecionado para tela de login.<br>- Conexão instável: sistema exibe aviso e tenta recarregar.<br>- Dados corrompidos: sistema orienta a contatar suporte.<br>- Solicitação duplicada: sistema impede envio e orienta usuário. |
| **Restrições**  | - Apenas usuários autenticados podem acessar.<br>- Dados protegidos por LGPD.<br>- Solicitação permitida apenas para cobranças dos últimos 30 dias.<br>- Anexos obrigatórios: comprovante de pagamento, justificativa.<br>- Tempo de resposta para envio deve ser inferior a 2 segundos.<br>- Usuário pode acompanhar status da solicitação pelo app.<br>- Limite de 3 solicitações simultâneas em análise. |
| **Episódios**   | 1. Usuário faz login.<br>2. Acessa "Reembolso".<br>3. Seleciona cobrança indevida.<br>4. Preenche justificativa e anexa documentos.<br>5. Envia solicitação.<br>6. Sistema valida dados e confirma envio.<br>7. Usuário recebe notificação de protocolo.<br>8. Usuário pode acompanhar status pelo app.<br>9. Se documentação incompleta, sistema solicita complementação.<br>10. Se erro, sistema oferece opção de tentar novamente ou contatar suporte. |

---
