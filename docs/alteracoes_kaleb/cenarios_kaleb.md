## Cenário 2: Agendar Consulta Médica pelo Aplicativo

**Requisito Associado:** [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1)

| Elemento | Descrição |
|---|---|
| **Título** | Agendar Consulta Médica pelo Aplicativo com Pagamento Integrado |
| **Metas/Objetivos** | Permitir ao usuário encontrar um profissional, escolher um horário e agendar uma consulta, realizando o pagamento da coparticipação de forma automática e segura. |
| **Ator(es)** | - Beneficiário do plano de saúde |
| **Contexto** | O usuário está com dor de garganta há alguns dias e deseja marcar uma consulta com um clínico geral o mais rápido possível, utilizando o aplicativo para evitar ligações e otimizar seu tempo. |
| **Recursos** | - App GDF Saúde<br>- Conexão com a internet<br>- Sistema de autenticação de usuário<br>- Banco de dados da rede credenciada (médicos, clínicas, horários)<br>- Gateway de pagamento seguro<br>- Sistema de notificações (e-mail/push) |
| **Exceções** | - O horário selecionado pelo usuário se torna indisponível durante o processo.<br>- Falha na comunicação com o sistema de pagamento.<br>- A agenda do médico está desatualizada no sistema.<br>- Usuário sem conexão com a internet no momento da confirmação. |
| **Restrições** | - O agendamento só pode ser feito para profissionais e clínicas da rede credenciada do plano do usuário.<br>- A transação de pagamento deve ser criptografada e seguir normas de segurança.<br>- A confirmação do agendamento deve ser enviada ao usuário em menos de 1 minuto após a conclusão. |
| **Episódios** | 1. Usuário faz login no aplicativo.<br>2. Acessa a funcionalidade "Agendar Consulta".<br>3. Busca pela especialidade "Clínico Geral".<br>4. O sistema exibe a lista de profissionais e seus horários disponíveis.<br>5. Usuário seleciona um médico e um horário compatível.<br>6. O sistema apresenta um resumo do agendamento, incluindo o valor da coparticipação.<br>7. Usuário confirma a consulta.<br>8. O sistema processa o pagamento com o método cadastrado e exibe a mensagem "Consulta agendada com sucesso!".<br>9. Usuário recebe um e-mail e uma notificação no app com os detalhes da consulta. |

---

## Cenário 3: Cancelar um Agendamento de Consulta

**Requisito Associado:** [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2)

| Elemento | Descrição |
|---|---|
| **Título** | Cancelar Agendamento de Consulta pelo Aplicativo |
| **Metas/Objetivos** | Permitir ao usuário cancelar uma consulta agendada de forma simples e receber o estorno do valor pago, de acordo com as regras do plano. |
| **Ator(es)** | - Beneficiário do plano de saúde |
| **Contexto** | O usuário agendou uma consulta, mas um compromisso de trabalho inadiável surgiu no mesmo horário. Ele precisa cancelar o agendamento para liberar o horário e evitar a cobrança. |
| **Recursos** | - App GDF Saúde<br>- Conexão com a internet<br>- Sistema de autenticação de usuário<br>- Banco de dados com os agendamentos do usuário<br>- Gateway de pagamento para processar o estorno |
| **Exceções** | - Usuário tenta cancelar após o prazo limite para estorno.<br>- Falha na comunicação com o sistema financeiro para efetivar o estorno.<br>- A consulta selecionada já foi realizada ou previamente cancelada. |
| **Restrições** | - A política de cancelamento (ex: estorno integral somente com 24h de antecedência) deve ser claramente exibida.<br>- O processamento do estorno deve ser iniciado imediatamente após a confirmação do cancelamento. |
| **Episódios** | 1. Usuário faz login no aplicativo.<br>2. Acessa a seção "Meus Agendamentos".<br>3. Localiza a consulta que deseja cancelar na lista de próximos agendamentos.<br>4. Seleciona a opção "Cancelar Consulta".<br>5. O sistema exibe a política de cancelamento e solicita a confirmação.<br>6. Usuário confirma o cancelamento.<br>7. O sistema processa a ação e exibe a mensagem "Consulta cancelada. O estorno será processado em seu método de pagamento.". |

---

## Cenário 4: Verificar Preço de Consulta Antes de Agendar

**Requisito Associado:** [RF06.1](../../elicitacao/requisitos_finais.md#RF06.1)

| Elemento | Descrição |
|---|---|
| **Título** | Verificar o Valor Específico de uma Consulta |
| **Metas/Objetivos** | Permitir que o usuário saiba o valor total de uma consulta em uma clínica específica antes de decidir pelo agendamento. |
| **Ator(es)** | - Beneficiário do plano de saúde |
| **Contexto** | O usuário está considerando agendar uma consulta com um dermatologista e quer comparar os valores cobrados por duas clínicas diferentes para tomar uma decisão informada. |
| **Recursos** | - App GDF Saúde<br>- Conexão com a internet<br>- Banco de dados da rede credenciada com tabela de preços dos prestadores |
| **Exceções** | - A clínica não informou o valor do procedimento no sistema.<br>- O valor exibido está desatualizado. |
| **Restrições** | - Os valores devem ser buscados em tempo real ou ter uma data de última atualização visível.<br>- O valor exibido é o "valor cheio" do procedimento, sem considerar a coparticipação. |
| **Episódios** | 1. Usuário acessa a "Rede Credenciada" no aplicativo.<br>2. Busca pela especialidade "Dermatologia".<br>3. O sistema lista as clínicas e profissionais disponíveis.<br>4. Ao lado do nome de cada clínica, o sistema exibe o "Valor da Consulta: R$ XXX,XX".<br>5. O usuário compara os valores para decidir onde agendar. |

---

## Cenário 5: Simular Custo de Coparticipação

**Requisito Associado:** [RF06.2](../../elicitacao/requisitos_finais.md#RF06.2)

| Elemento | Descrição |
|---|---|
| **Título** | Calcular e Exibir o Valor da Coparticipação |
| **Metas/Objetivos** | Informar de forma clara ao usuário o valor que ele efetivamente pagará (coparticipação) por um procedimento, ajudando em seu planejamento financeiro. |
| **Ator(es)** | - Beneficiário do plano de saúde |
| **Contexto** | O médico solicitou um exame de ressonância magnética. Antes de agendar, o usuário quer saber qual será o custo de sua coparticipação para este exame específico. |
| **Recursos** | - App GDF Saúde<br>- Conexão com a internet<br>- Sistema de autenticação<br>- Regras de negócio do plano do usuário (percentuais, valores fixos)<br>- Tabela de preços dos procedimentos |
| **Exceções** | - As regras do plano do usuário não estão disponíveis ou são ambíguas.<br>- O procedimento selecionado é isento de coparticipação. |
| **Restrições** | - O cálculo deve ser preciso, baseado nas regras atuais do contrato do beneficiário.<br>- Deve haver um aviso de que o valor é uma estimativa caso haja variáveis. |
| **Episódios** | 1. Usuário está no fluxo de agendamento de um exame de "Ressonância Magnética".<br>2. Ao selecionar o exame e a clínica, o sistema exibe os detalhes.<br>3. Em uma seção destacada, o sistema mostra: "Valor Total: R$ 800,00".<br>4. Logo abaixo, exibe: "Sua Coparticipação (30%): R$ 240,00".<br>5. O usuário visualiza o custo e prossegue com o agendamento. |

---

## Cenário 6: Emitir Demonstrativo para Imposto de Renda

**Requisito Associado:** [RF06.3](../../elicitacao/requisitos_finais.md#RF06.3)

| Elemento | Descrição |
|---|---|
| **Título** | Gerar e Baixar Demonstrativo de Despesas Médicas para o IR |
| **Metas/Objetivos** | Fornecer ao usuário um documento oficial e consolidado com todas as suas despesas médicas do ano anterior para facilitar a declaração do Imposto de Renda. |
| **Ator(es)** | - Beneficiário do plano de saúde |
| **Contexto** | É o mês de abril, e o usuário está preparando sua declaração de IR. Ele precisa do informe de pagamentos do plano de saúde para preencher as deduções de despesas médicas. |
| **Recursos** | - App GDF Saúde<br>- Sistema de autenticação<br>- Histórico financeiro completo do usuário (mensalidades, coparticipações)<br>- Gerador de relatórios em PDF |
| **Exceções** | - Não há despesas registradas para o usuário no ano selecionado.<br>- Erro na geração do arquivo PDF. |
| **Restrições** | - O documento deve seguir o layout e conter as informações exigidas pela Receita Federal (CNPJ da operadora, dados do beneficiário, valores detalhados).<br>- O acesso à funcionalidade exige autenticação robusta. |
| **Episódios** | 1. Usuário acessa o aplicativo e faz login.<br>2. Navega até a seção "Financeiro" e depois "Imposto de Renda".<br>3. Seleciona o "Ano-Calendário" desejado (ex: o ano passado).<br>4. Clica no botão "Gerar Demonstrativo".<br>5. O sistema processa os dados e gera um arquivo PDF.<br>6. O usuário clica em "Baixar" e salva o documento em seu dispositivo. |

---

## Cenário 7: Acessar Demonstrativos de Anos Anteriores

**Requisito Associado:** [RF06.4](../../elicitacao/requisitos_finais.md#RF06.4)

| Elemento | Descrição |
|---|---|
| **Título** | Consultar Histórico de Demonstrativos de Imposto de Renda |
| **Metas/Objetivos** | Permitir que o usuário acesse e baixe informes de pagamento de anos anteriores de forma rápida e segura. |
| **Ator(es)** | - Beneficiário do plano de saúde |
| **Contexto** | O usuário caiu na malha fina da Receita Federal e precisa do demonstrativo de despesas médicas de dois anos atrás para comprovar os valores declarados. |
| **Recursos** | - App GDF Saúde<br>- Sistema de autenticação<br>- Repositório de documentos históricos (demonstrativos já gerados) |
| **Exceções** | - O histórico não contém o demonstrativo do ano solicitado.<br>- O arquivo do demonstrativo está corrompido ou indisponível. |
| **Restrições** | - O sistema deve armazenar os demonstrativos por um período mínimo de 5 anos, conforme a legislação. |
| **Episódios** | 1. Usuário acessa a seção "Imposto de Renda".<br>2. Clica na opção "Ver Histórico".<br>3. O sistema exibe uma lista com os demonstrativos dos anos anteriores.<br>4. O usuário localiza o ano desejado e clica para visualizar ou baixar o documento. |

---

## Cenário 8: Conferir Despesas no Extrato Financeiro

**Requisito Associado:** [RF06.5](../../elicitacao/requisitos_finais.md#RF06.5)

| Elemento | Descrição |
|---|---|
| **Título** | Mostrar Extrato Financeiro Detalhado |
| **Metas/Objetivos** | Oferecer ao usuário uma visão transparente e atualizada de todas as suas transações financeiras com o plano de saúde. |
| **Ator(es)** | - Beneficiário do plano de saúde |
| **Contexto** | O usuário recebeu a fatura do seu cartão de crédito e viu uma cobrança do plano de saúde que não reconhece de imediato. Ele quer acessar o extrato no app para ver a que se refere aquele valor. |
| **Recursos** | - App GDF Saúde<br>- Sistema de autenticação<br>- Banco de dados com o histórico de transações financeiras do usuário |
| **Exceções** | - Atraso na sincronização dos dados, mostrando um extrato não atualizado.<br>- Erro técnico ao carregar os detalhes de uma transação. |
| **Restrições** | - O extrato deve ser atualizado diariamente (D+1).<br>- As descrições das transações devem ser claras e inequívocas. |
| **Episódios** | 1. Usuário faz login e acessa a seção "Financeiro".<br>2. O sistema exibe o extrato com as últimas movimentações.<br>3. O usuário localiza a transação com o valor correspondente à sua dúvida.<br>4. A descrição informa: "Coparticipação - Exame de Sangue - Laboratório X - 10/06/2025".<br>5. O usuário se recorda do exame e sua dúvida é esclarecida. |

---

## Cenário 9: Acompanhar Metas de Saúde Preventiva

**Requisito Associado:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

| Elemento | Descrição |
|---|---|
| **Título** | Exibir Painel com Metas de Saúde Personalizadas |
| **Metas/Objetivos** | Incentivar o usuário a cuidar da saúde de forma proativa, mostrando metas de cuidados preventivos e utilizando gamificação para motivar a conclusão. |
| **Ator(es)** | - Beneficiário do plano de saúde |
| **Contexto** | O usuário tem 45 anos e quer garantir que está fazendo todos os exames preventivos recomendados para sua idade, mas tem dificuldade de lembrar e se organizar. |
| **Recursos** | - App GDF Saúde<br>- Sistema de autenticação<br>- Perfil de saúde do usuário (idade, gênero, histórico)<br>- Motor de regras para sugerir metas<br>- Sistema de gamificação (pontos, emblemas/badges) |
| **Exceções** | - O perfil do usuário está incompleto, impedindo a sugestão de metas.<br>- Erro ao carregar o status de uma meta (ex: não reconhece que um exame já foi feito). |
| **Restrições** | - As metas sugeridas devem ser baseadas em protocolos médicos reconhecidos.<br>- A interface deve ser motivadora e fácil de entender. |
| **Episódios** | 1. Usuário acessa a seção "Minha Saúde" ou "Painel de Metas".<br>2. O sistema exibe um painel: "Olá! Você completou 2 de 5 metas de saúde para este ano!".<br>3. O painel mostra as metas: "Consulta anual com cardiologista" (Concluído), "Exames de sangue anuais" (Pendente), etc.<br>4. Ao lado das metas concluídas, há um emblema de "check".<br>5. O usuário clica na meta pendente "Exames de sangue anuais".<br>6. O sistema oferece a opção "Encontrar laboratórios e agendar", iniciando o fluxo de agendamento. |