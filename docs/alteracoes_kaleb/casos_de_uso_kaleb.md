## ORDEM NUMÉRICA DOS UC E DAS TABELAS VAO DEPENDER DO DOCUMENTO FINAL

## UC28 – Agendar Consulta ou Exame
<p align="center">Tabela 2 - Caso de Uso 28</p>

| Campo | Descrição |
| :--- | :--- |
| **UC28** | Agendar consulta ou exame |
| **Descrição** | Permitir ao usuário agendar consultas e exames diretamente pelo aplicativo, com pagamento automático para prestadores da Rede de Atendimento. |
| **Ator** | Beneficiário (Usuário do plano de saúde) |
| **Pré-condições** | O usuário deve estar autenticado no sistema. |
| **Fluxo principal** | 1. Usuário acessa a seção "Agendamentos".<br>2. Usuário seleciona a opção "Novo Agendamento".<br>3. O sistema solicita que o usuário busque por especialidade, profissional ou clínica.<br>4. O usuário realiza a busca e seleciona o profissional e o horário desejado.<br>5. O sistema exibe um resumo do agendamento (data, hora, profissional, local).<br>6. O sistema informa que o pagamento da coparticipação (se aplicável) será processado.<br>7. Usuário confirma os detalhes do agendamento.<br>8. O sistema processa o pagamento automático.<br>9. O sistema confirma o agendamento e envia uma notificação ao usuário. |
| **Fluxo alternativo** | **A1. Horário tornou-se indisponível:**<br>- Se o horário selecionado for ocupado durante o processo, o sistema exibe a mensagem "Este horário não está mais disponível" e solicita que o usuário escolha um novo horário. |
| **Fluxo de exceção** | **E1. Falha no processamento do pagamento:**<br>- Sistema exibe mensagem "Falha ao processar o pagamento. Verifique seus dados ou tente outro método.".<br>- O agendamento não é concluído.<br>**E2. Sessão expirada:**<br>- Sistema solicita novo login. |
| **Pós-condições** | A consulta ou exame está agendada no sistema. O pagamento aplicável foi processado. |
| **Rastreabilidade** | [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

***

## UC29 – Cancelar Consulta ou Exame
<p align="center">Tabela 3 - Caso de Uso 29</p>

| Campo | Descrição |
| :--- | :--- |
| **UC29** | Cancelar consulta ou exame |
| **Descrição** | Permitir ao usuário cancelar uma consulta ou exame agendado diretamente pelo aplicativo, com o devido processamento de estorno de pagamento conforme as regras de negócio. |
| **Ator** | Beneficiário (Usuário do plano de saúde) |
| **Pré-condições** | O usuário deve estar autenticado no sistema e ter ao menos uma consulta ou exame futuro agendado. |
| **Fluxo principal** | 1. Usuário acessa a seção "Meus Agendamentos".<br>2. O sistema exibe a lista de agendamentos futuros.<br>3. Usuário seleciona o agendamento que deseja cancelar.<br>4. O sistema exibe os detalhes do agendamento e a opção "Cancelar Agendamento".<br>5. Usuário confirma o cancelamento.<br>6. O sistema processa o cancelamento e o estorno do pagamento, se aplicável.<br>7. O sistema exibe a mensagem "Agendamento cancelado com sucesso.". |
| **Fluxo alternativo** | **A1. Cancelamento sujeito a taxas:**<br>- O sistema informa que o cancelamento está sujeito a uma taxa de acordo com a política e pergunta se o usuário deseja continuar. |
| **Fluxo de exceção** | **E1. Falha ao processar o estorno:**<br>- O sistema exibe a mensagem "O agendamento foi cancelado, mas houve um erro ao processar o estorno. Entre em contato com o suporte." |
| **Pós-condições** | A consulta ou exame está com o status "Cancelado". O valor correspondente foi estornado, se aplicável. |
| **Rastreabilidade** | [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

***

## UC30 – Exibir Valor de Consulta em Clínica
<p align="center">Tabela 4 - Caso de Uso 30</p>

| Campo | Descrição |
| :--- | :--- |
| **UC30** | Exibir Valor de Consulta em Clínica |
| **Descrição** | Permitir ao usuário visualizar o valor específico de uma consulta ou procedimento em cada clínica disponível na rede. |
| **Ator** | Beneficiário (Usuário do plano de saúde) |
| **Pré-condições** | O usuário deve estar autenticado no sistema. |
| **Fluxo principal** | 1. Usuário acessa a "Rede de Atendimento".<br>2. Usuário busca por uma especialidade ou procedimento.<br>3. O sistema exibe a lista de clínicas e profissionais que atendem ao critério.<br>4. Para cada resultado da lista, o sistema exibe o valor específico da consulta naquele local. |
| **Fluxo alternativo** | **A1. Valor não informado:**<br>- Se uma clínica não disponibiliza o valor, o sistema exibe a mensagem "Valor a consultar". |
| **Fluxo de exceção** | **E1. Falha ao carregar a rede:**<br>- O sistema exibe a mensagem "Erro ao carregar a rede de atendimento. Tente novamente." |
| **Pós-condições** | O usuário visualizou os valores das consultas nas clínicas de seu interesse. |
| **Rastreabilidade** | [RF06.1](../../elicitacao/requisitos_finais.md#RF06.1) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

***

## UC31 – Calcular e Exibir Valor da Coparticipação
<p align="center">Tabela 5 - Caso de Uso 31</p>

| Campo | Descrição |
| :--- | :--- |
| **UC31** | Calcular e Exibir Valor da Coparticipação |
| **Descrição** | O sistema deve calcular e exibir o valor da coparticipação do beneficiário para cada consulta e procedimento médico realizado que esteja sujeito a este regime. |
| **Ator** | Beneficiário (Usuário do plano de saúde) |
| **Pré-condições** | O usuário deve estar autenticado e visualizando um procedimento sujeito a coparticipação. |
| **Fluxo principal** | 1. O usuário seleciona um procedimento (ex: durante um agendamento).<br>2. O sistema identifica o procedimento e o plano do beneficiário.<br>3. O sistema acessa as regras de coparticipação do plano.<br>4. O sistema calcula o valor exato ou estimado da coparticipação.<br>5. O sistema exibe o valor calculado para o usuário de forma clara. |
| **Fluxo alternativo** | **A1. Procedimento isento:**<br>- Se o procedimento for isento, o sistema exibe "Coparticipação: R$ 0,00" ou "Isento". |
| **Fluxo de exceção** | **E1. Erro no cálculo:**<br>- O sistema exibe a mensagem "Não foi possível calcular a coparticipação. O valor será detalhado no seu extrato." |
| **Pós-condições** | O usuário foi informado sobre o valor da sua coparticipação para um procedimento. |
| **Rastreabilidade** | [RF06.2](../../elicitacao/requisitos_finais.md#RF06.2) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

***

## UC32 – Gerar Demonstrativo de Despesas para IR
<p align="center">Tabela 6 - Caso de Uso 32</p>

| Campo | Descrição |
| :--- | :--- |
| **UC32** | Gerar Demonstrativo de Despesas para Imposto de Renda |
| **Descrição** | Permitir ao usuário gerar e baixar o demonstrativo consolidado de despesas médicas de um ano específico para a declaração de Imposto de Renda. |
| **Ator** | Beneficiário (Usuário do plano de saúde) |
| **Pré-condições** | O usuário deve estar autenticado no sistema. |
| **Fluxo principal** | 1. Usuário acessa a seção "Financeiro" ou "Documentos".<br>2. Usuário seleciona a opção "Demonstrativo para Imposto de Renda".<br>3. O sistema solicita ao usuário que selecione o ano-calendário.<br>4. Usuário seleciona o ano e confirma.<br>5. O sistema compila as despesas e gera o documento em PDF.<br>6. O sistema disponibiliza o arquivo para download. |
| **Fluxo alternativo** | **A1. Nenhuma despesa no período:**<br>- O sistema exibe a mensagem "Nenhuma despesa médica foi encontrada para o ano selecionado.". |
| **Fluxo de exceção** | **E1. Erro na geração do documento:**<br>- O sistema exibe a mensagem "Ocorreu um erro ao gerar seu demonstrativo. Por favor, tente novamente." |
| **Pós-condições** | O usuário obteve o arquivo com seu demonstrativo de despesas. |
| **Rastreabilidade** | [RF06.3](../../elicitacao/requisitos_finais.md#RF06.3) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

***

## UC33 – Consultar Histórico de Demonstrativos de IR
<p align="center">Tabela 7 - Caso de Uso 33</p>

| Campo | Descrição |
| :--- | :--- |
| **UC33** | Consultar Histórico de Demonstrativos de IR |
| **Descrição** | Permitir ao usuário visualizar e baixar demonstrativos de Imposto de Renda que foram gerados anteriormente. |
| **Ator** | Beneficiário (Usuário do plano de saúde) |
| **Pré-condições** | O usuário deve estar autenticado no sistema. |
| **Fluxo principal** | 1. Usuário acessa a seção "Financeiro" ou "Documentos".<br>2. Usuário navega até a área "Histórico de Demonstrativos de IR".<br>3. O sistema exibe a lista de demonstrativos disponíveis, por ano.<br>4. Usuário seleciona um demonstrativo da lista para baixar. |
| **Fluxo alternativo** | **A1. Histórico vazio:**<br>- O sistema exibe a mensagem "Nenhum demonstrativo foi gerado anteriormente.". |
| **Fluxo de exceção** | **E1. Falha na recuperação do arquivo:**<br>- O sistema exibe a mensagem "Erro ao carregar o arquivo do demonstrativo." |
| **Pós-condições** | O usuário visualizou seu histórico e/ou baixou um demonstrativo antigo. |
| **Rastreabilidade** | [RF06.4](../../elicitacao/requisitos_finais.md#RF06.4) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

***

## UC34 – Consultar Extrato Financeiro
<p align="center">Tabela 8 - Caso de Uso 34</p>

| Campo | Descrição |
| :--- | :--- |
| **UC34** | Consultar Extrato Financeiro |
| **Descrição** | Permitir ao usuário consultar seu extrato financeiro detalhado e atualizado diariamente. |
| **Ator** | Beneficiário (Usuário do plano de saúde) |
| **Pré-condições** | O usuário deve estar autenticado no sistema. |
| **Fluxo principal** | 1. Usuário acessa a seção "Financeiro".<br>2. O sistema exibe o extrato, com as transações mais recentes primeiro.<br>3. Cada item exibe data, descrição da transação e valor.<br>4. O usuário pode aplicar filtros para buscar transações. |
| **Fluxo alternativo** | **A1. Nenhuma transação no período:**<br>- O sistema exibe a mensagem "Nenhuma transação encontrada para o período selecionado.". |
| **Fluxo de exceção** | **E1. Falha ao carregar o extrato:**<br>- Sistema exibe mensagem "Erro ao carregar o extrato financeiro." |
| **Pós-condições** | O usuário visualizou suas movimentações financeiras. |
| **Rastreabilidade** | [RF06.5](../../elicitacao/requisitos_finais.md#RF06.5) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

***

## UC35 – Visualizar Painel de Metas de Saúde
<p align="center">Tabela 9 - Caso de Uso 35</p>

| Campo | Descrição |
| :--- | :--- |
| **UC35** | Visualizar Painel de Metas de Saúde |
| **Descrição** | Exibir um painel personalizado com metas de saúde e gamificação para incentivar o acompanhamento. |
| **Ator** | Beneficiário (Usuário do plano de saúde) |
| **Pré-condições** | O usuário deve estar autenticado no sistema. |
| **Fluxo principal** | 1. Usuário acessa a seção "Minha Saúde" ou "Painel de Metas".<br>2. O sistema exibe o painel de metas personalizadas.<br>3. O painel mostra as metas, o progresso e elementos de gamificação (pontos, emblemas).<br>4. Usuário pode clicar em uma meta para ver detalhes ou agendar o procedimento correspondente. |
| **Fluxo alternativo** | **A1. Usuário sem metas definidas:**<br>- O sistema exibe uma mensagem de boas-vindas e incentiva a configuração das primeiras metas. |
| **Fluxo de exceção** | **E1. Falha ao carregar o painel de metas:**<br>- O sistema exibe a mensagem "Não foi possível carregar suas metas de saúde." |
| **Pós-condições** | O usuário visualizou seu progresso em relação às suas metas de saúde. |
| **Rastreabilidade** | [RF17](../../elicitacao/requisitos_finais.md#RF17) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>