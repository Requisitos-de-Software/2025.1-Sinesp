| Campo                   | Descrição   |
| ----------------------- | ------------------- |
| **ID**                  | US01     |
| **Título**              | Pesquisar Redes Credenciadas com Filtros          |
| **História**            | Como um usuário do plano de saúde,<br>Eu quero pesquisar redes credenciadas utilizando filtros de busca,<br>Para que eu encontre rapidamente as redes que atendam aos meus critérios.                     |
| **Critérios de Aceitação** | <br>- Dado que o usuário acessa a pesquisa de redes,<br>- Quando ele seleciona filtros como localização ou tipo de serviço,<br>- Então o sistema deve retornar redes que correspondam a todos os filtros aplicados. |
| **Rastreabilidade**     |  |
| **Épico Relacionado**   |    |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

| Campo                   | Descrição   |
| ----------------------- | ------------------- |
| **ID**                  | US02     |
| **Título**              | Pesquisar Profissionais de Saúde com Filtros  |
| **História**            | Como um usuário do plano de saúde,<br>Eu quero pesquisar profissionais de saúde (médicos, psicólogos etc.) utilizando filtros,<br>Para que eu encontre o profissional adequado às minhas necessidades.           |
| **Critérios de Aceitação** | <br>- Dado que o usuário está na busca de profissionais,<br>- Quando ele filtra por especialidade médica,<br>- Então o sistema deve listar apenas profissionais dessa especialidade. |
| **Rastreabilidade**     |   |
| **Épico Relacionado**   |   |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

| Campo                   | Descrição   |
| ----------------------- | ------------------- |
| **ID**                  | US03    |
| **Título**              | Combinar Múltiplos Filtros de Pesquisa    |
| **História**            | Como um usuário do plano de saúde,<br>Eu quero combinar diferentes filtros de pesquisa,<br>Para que eu obtenha resultados mais precisos e relevantes.                                                   |
| **Critérios de Aceitação** | <br>- Dado que o usuário aplica múltiplos filtros (ex: região + especialidade),<br>- Quando ele executa a pesquisa,<br>- Então o sistema deve retornar resultados que satisfaçam todas as condições simultaneamente. |
| **Rastreabilidade**     |   |
| **Épico Relacionado**   |   |
<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

| Campo                   | Descrição   |
| ----------------------- | ------------------- |
| **ID**                  | US04      |
| **Título**              | Avaliar Atendimentos com Escala Likert   |
| **História**            | Como um usuário do plano de saúde,<br>Eu quero avaliar atendimentos usando uma escala de 0 a 5,<br>Para que eu possa expressar minha satisfação com o serviço recebido.                                 |
| **Critérios de Aceitação** | br>- Dado que o usuário finalizou um atendimento,<br>- Quando ele seleciona uma nota entre 0 e 5,<br>- Então o sistema deve registrar a avaliação e exibir confirmação. |
| **Rastreabilidade**     |   |
| **Épico Relacionado**   |  |
<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

| Campo                   | Descrição   |
| ----------------------- | ------------------- |
| **ID**                  | US05     |
| **Título**              | Gerenciar Comentários sobre Atendimentos     |
| **História**            | Como um usuário do plano de saúde,<br>Eu quero deixar e ler comentários sobre clínicas/profissionais,<br>Para que eu possa compartilhar experiências e ajudar outros usuários.                           |
| **Critérios de Aceitação** | <br>- Dado que o usuário acessa um perfil de profissional,<br>- Quando ele escreve e envia um comentário,<br>- Então o sistema deve publicá-lo com carimbo de data/hora. |
| **Rastreabilidade**     |   |
| **Épico Relacionado**   |   |
<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

| Campo                   | Descrição   |
| ----------------------- | ------------------- |
| **ID**                  | US06  |
| **Título**              | Receber Recomendações de Especialidade via Chatbot |
| **História**            | Como um usuário do plano de saúde,<br>Eu quero ser direcionado à especialidade médica correta por um chatbot,<br>Para que eu identifique rapidamente o profissional adequado ao meu sintoma.                      |
| **Critérios de Aceitação** | <br>- Dado que o usuário inicia o chatbot,<br>- Quando ele descreve seus sintomas,<br>- Então o sistema deve recomendar uma especialidade médica com pelo menos 80% de precisão. |
| **Rastreabilidade**     |  |
| **Épico Relacionado**   |  |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### História de usuário Receber Notificações sobre Vencimento de Fatura

<p  align="center">Tabela X: História de usuário Receber Notificações sobre Vencimento de Fatura </p>

| Campo                      | Descrição |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                     | US08 |
| **Título**                 | Receber Notificações sobre Vencimento de Fatura |
| **História**               | Como um usuário do plano de saúde,<br>Eu quero receber notificações configuráveis sobre o vencimento da fatura via app, SMS ou e-mail,<br>Para que eu possa me organizar financeiramente e evitar atrasos nos pagamentos. |
| **Critérios de Aceitação** | - Dado que o usuário tenha ativado notificações para vencimento de fatura,<br>- Quando estiver próximo da data de vencimento,<br>- Então o sistema deve enviar uma notificação no(s) canal(is) selecionado(s) pelo usuário: app, SMS e/ou e-mail. |
| **Rastreabilidade**        | RF04.1 |
| **Épico Relacionado**      |  |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### História de usuário Receber Notificações sobre Retornos Médicos Pendentes

<p  align="center">Tabela X: História de usuário Receber Notificações sobre Retornos Médicos Pendentes </p>

| Campo                      | Descrição |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                     | US09 |
| **Título**                 | Receber Notificações sobre Retornos Médicos Pendentes |
| **História**               | Como um usuário do plano de saúde,<br>Eu quero receber notificações configuráveis sobre retornos médicos pendentes via app, SMS ou e-mail,<br>Para que eu não me esqueça de agendar ou comparecer aos retornos recomendados pelos profissionais de saúde. |
| **Critérios de Aceitação** | - Dado que o usuário tenha um retorno médico pendente e tenha ativado as notificações correspondentes,<br>- Quando a data recomendada estiver se aproximando,<br>- Então o sistema deve enviar uma notificação no(s) canal(is) escolhido(s) pelo usuário. |
| **Rastreabilidade**        | RF04.2 |
| **Épico Relacionado**      |  |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### História de usuário Receber Notificações sobre Abertura de Agenda

<p  align="center">Tabela X: História de usuário Receber Notificações sobre Abertura de Agenda </p>

| Campo                      | Descrição |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                     | US10 |
| **Título**                 | Receber Notificações sobre Abertura de Agenda |
| **História**               | Como um usuário do plano de saúde,<br>Eu quero ser notificado quando novas agendas de profissionais forem abertas,<br>Para que eu possa marcar consultas rapidamente, garantindo horários que sejam convenientes para mim. |
| **Critérios de Aceitação** | - Dado que o usuário tenha ativado notificações sobre abertura de agenda,<br>- Quando uma nova agenda for aberta,<br>- Então o sistema deve enviar uma notificação no(s) canal(is) escolhido(s) pelo usuário: app, SMS e/ou e-mail. |
| **Rastreabilidade**        | RF04.3 |
| **Épico Relacionado**      |  |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### História de usuário Receber Notificações sobre Cancelamentos de Horários

<p  align="center">Tabela X: História de usuário Receber Notificações sobre Cancelamentos de Horários </p>

| Campo                      | Descrição |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                     | US11 |
| **Título**                 | Receber Notificações sobre Cancelamentos de Horários |
| **História**               | Como um usuário do plano de saúde,<br>Eu quero ser notificado sobre cancelamentos de horários agendados via app, SMS ou e-mail,<br>Para que eu possa reorganizar meus compromissos e, se necessário, agendar um novo horário. |
| **Critérios de Aceitação** | - Dado que o usuário tenha um horário agendado e que tenha ativado notificações de cancelamento,<br>- Quando o profissional ou o sistema cancelar o horário,<br>- Então o usuário deve receber uma notificação pelo(s) canal(is) configurado(s). |
| **Rastreabilidade**        | RF04.4 |
| **Épico Relacionado**      |  |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### História de usuário Receber Notificações sobre Disponibilidade de Horários Favoritos

<p  align="center">Tabela X: História de usuário Receber Notificações sobre Disponibilidade de Horários Favoritos </p>

| Campo                      | Descrição |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                     | US12 |
| **Título**                 | Receber Notificações sobre Disponibilidade de Horários Favoritos |
| **História**               | Como um usuário do plano de saúde,<br>Eu quero receber notificações quando horários que marquei como favoritos ficarem disponíveis,<br>Para que eu possa rapidamente agendar esses horários conforme minha preferência. |
| **Critérios de Aceitação** | - Dado que o usuário tenha marcado horários como favoritos e ativado as notificações correspondentes,<br>- Quando um desses horários for liberado,<br>- Então o sistema deve notificar o usuário pelo(s) canal(is) de comunicação configurado(s). |
| **Rastreabilidade**        | RF04.5 |
| **Épico Relacionado**      |  |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### História de usuário Receber Notificações sobre Prazos Importantes de Consultas e Exames

<p  align="center">Tabela X: Receber Notificações sobre Prazos Importantes de Consultas e Exames </p>

| Campo                      | Descrição |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                     | US13 |
| **Título**                 | Receber Notificações sobre Prazos Importantes de Consultas e Exames |
| **História**               | Como um usuário do plano de saúde,<br>Eu quero receber notificações sobre prazos importantes relacionados às minhas consultas e exames,<br>Para que eu possa me preparar adequadamente e não perder nenhuma data relevante para minha saúde. |
| **Critérios de Aceitação** | - Dado que o usuário tenha consultas ou exames agendados e tenha ativado notificações de prazos,<br>- Quando o prazo relevante estiver se aproximando,<br>- Então o sistema deve enviar uma notificação pelo(s) canal(is) escolhido(s). |
| **Rastreabilidade**        | RF04.6 |
| **Épico Relacionado**      |  |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### História de usuário Receber Notificações sobre Confirmações de Agendamentos

<p  align="center">Tabela X: Receber Notificações sobre Confirmações de Agendamentos </p>

| Campo                      | Descrição |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                     | US14 |
| **Título**                 | Receber Notificações sobre Confirmações de Agendamentos |
| **História**               | Como um usuário do plano de saúde,<br>Eu quero ser notificado quando uma consulta ou exame for confirmado,<br>Para que eu tenha certeza do meu agendamento e possa me planejar com antecedência. |
| **Critérios de Aceitação** | - Dado que o usuário tenha um agendamento pendente e tenha ativado as notificações de confirmação,<br>- Quando o agendamento for confirmado,<br>- Então o sistema deve enviar uma notificação pelo(s) canal(is) configurado(s) pelo usuário. |
| **Rastreabilidade**        | RF04.7 |
| **Épico Relacionado**      |  |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### História de usuário Receber Notificações sobre Alterações de Agendamento

<p  align="center">Tabela X: Receber Notificações sobre Alterações de Agendamento </p>

| Campo                      | Descrição |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                     | US15 |
| **Título**                 | Receber Notificações sobre Alterações de Agendamento |
| **História**               | Como um usuário do plano de saúde,<br>Eu quero ser notificado sobre quaisquer alterações em meus agendamentos,<br>Para que eu possa ajustar minha agenda pessoal e evitar confusões ou faltas. |
| **Critérios de Aceitação** | - Dado que o usuário tenha um agendamento e tenha ativado notificações sobre alterações,<br>- Quando houver uma mudança no horário ou local do agendamento,<br>- Então o sistema deve notificar o usuário pelo(s) canal(is) de comunicação selecionado(s). |
| **Rastreabilidade**        | RF04.8 |
| **Épico Relacionado**      |  |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### História de usuário Receber Notificações sobre Disponibilidade de Demonstrativos de IR

<p  align="center">Tabela X: Receber Notificações sobre Disponibilidade de Demonstrativos de IR </p>

| Campo                      | Descrição |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                     | US16 |
| **Título**                 | Receber Notificações sobre Disponibilidade de Demonstrativos de IR |
| **História**               | Como um usuário do plano de saúde,<br>Eu quero ser notificado quando meu demonstrativo de Imposto de Renda estiver disponível,<br>Para que eu possa acessá-lo rapidamente e utilizá-lo na minha declaração anual. |
| **Critérios de Aceitação** | - Dado que o usuário tenha ativado notificações sobre disponibilidade de demonstrativos de IR,<br>- Quando o documento for gerado e disponibilizado,<br>- Então o sistema deve notificar o usuário pelo(s) canal(is) configurado(s): app, SMS e/ou e-mail. |
| **Rastreabilidade**        | RF04.9 |
| **Épico Relacionado**      |  |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

| Campo                   | Descrição   |
| ----------------------- | -------- |
| **ID** | US01  |
| **Título** | Agendar Consultas e Exames pelo Aplicativo  |
| **História** | Como um usuário do plano de saúde,<br>Eu quero agendar consultas e exames diretamente pelo aplicativo,<br>Para que eu possa gerenciar minha saúde de forma conveniente e eficiente.                      |
| **Critérios de Aceitação** | <br>- Dado que o usuário está logado no aplicativo,<br>- Quando ele seleciona a opção de agendamento e escolhe uma especialidade/exame, prestador e horário,<br>- Então o sistema deve confirmar o agendamento e exibir os detalhes. |
| **Rastreabilidade** |     [RNF05](../../elicitacao/elicitacao.md#RNF05)  |
| **Épico Relacionado** | |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>


---

| Campo                   | Descrição   |
| ----------------------- | ----------|
| **ID** | US02   |
| **Título** | Realizar Pagamento Automático a Prestadores      |
| **História** | Como um usuário do plano de saúde,<br>Eu quero que o pagamento seja realizado automaticamente para os prestadores da Rede de Atendimento,<br>Para que eu não precise me preocupar com transações manuais após a consulta ou exame. |
| **Critérios de Aceitação** | <br>- Dado que o usuário realiza uma consulta ou exame com um prestador da Rede de Atendimento e possui um método de pagamento configurado,<br>- Quando o atendimento é concluído,<br>- Então o sistema deve processar o pagamento automaticamente ao prestador. |
| **Rastreabilidade** |     [RF05.2](../../elicitacao/elicitacao.md#RF05.2)     |
| **Épico Relacionado** |    |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---
| Campo                   | Descrição   |
| ----------------------- | ----------|
| **ID** | US03   |
| **Título** | Cancelar Consultas e Exames pelo Aplicativo     |
| **História** | Como um usuário do plano de saúde,<br>Eu quero cancelar consultas e exames diretamente pelo aplicativo,<br>Para que eu possa gerenciar meus compromissos de forma flexível e evitar custos desnecessários. |
| **Critérios de Aceitação** | <br>- Dado que o usuário possui um agendamento de consulta ou exame ativo no aplicativo,<br>- Quando ele seleciona a opção de cancelamento e confirma a ação,<br>- Então o sistema deve cancelar o agendamento e, se aplicável, processar qualquer ajuste financeiro automático com o prestador. |
| **Rastreabilidade** |     [RF05.3](../../elicitacao/elicitacao.md#RF05.3)  |
| **Épico Relacionado** |   |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

| Campo                   | Descrição   |
| ----------------------- | ----------|
| **ID** | US04   |
| **Título** | Exibir Valor da Consulta por Clínica  |
| **História** | Como um usuário do plano de saúde,<br>Eu quero ver o valor específico da consulta para cada clínica,<br>Para que eu possa tomar decisões informadas sobre onde realizar meu atendimento.           |
| **Critérios de Aceitação** | <br>- Dado que o usuário está pesquisando por clínicas ou prestadores de saúde,<br>- Quando ele visualiza os detalhes de uma clínica ou prestador,<br>- Então o sistema deve exibir o valor da consulta associado a essa clínica ou prestador. |
| **Rastreabilidade** |     [RF06.1](../../elicitacao/elicitacao.md#RF06.1)  |
| **Épico Relacionado** |    |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

| Campo                   | Descrição   |
| ----------------------- | ----------|
| **ID** | US05     |
| **Título** | Visualizar Valor da Coparticipação    |
| **História** | Como um beneficiário do plano de saúde,<br>Eu quero que o sistema calcule e exiba o valor da minha coparticipação para cada consulta ou procedimento,<br>Para que eu tenha clareza sobre meus custos e possa planejar minhas despesas. |
| **Critérios de Aceitação** | <br>- Dado que o usuário realiza uma consulta ou procedimento sujeito a coparticipação,<br>- Quando o sistema processa o registro desse atendimento,<br>- Então o valor da coparticipação deve ser calculado e exibido no extrato ou detalhe do atendimento do usuário. |
| **Rastreabilidade** |     [RF06.2](../../elicitacao/elicitacao.md#RF06.2)    |
| **Épico Relacionado** |      |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

| Campo                   | Descrição   |
| ----------------------- | ----------|
| **ID** | US06  |
| **Título** | Gerar e Baixar Demonstrativo para Imposto de Renda     |
| **História** | Como um usuário do plano de saúde,<br>Eu quero gerar e baixar um demonstrativo de minhas despesas médicas,<br>Para que eu possa utilizar no meu imposto de renda de forma prática e organizada.       |
| **Critérios de Aceitação** | <br>- Dado que o usuário acessa a seção de demonstrativos no aplicativo,<br>- Quando ele seleciona o período desejado e a opção de gerar/baixar,<br>- Então o sistema deve gerar um arquivo (ex: PDF) com o demonstrativo de despesas médicas, permitindo o download. |
| **Rastreabilidade** |     [RF06.3](../../elicitacao/elicitacao.md#RF06.3)   |
| **Épico Relacionado** |   |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>




| Campo                   | Descrição                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**                 | US01                                                                                                                                                                                                      |
| **Título**             | Cadastro de Titular                                                                                                                                                                                       |
| **História**           | Como um usuário responsável pelo atendimento,<br>Eu quero cadastrar titulares no sistema,<br>Para que eles possam acessar os serviços oferecidos pelo plano de saúde.                                     |
| **Critérios de Aceitação** | - Dado que estou na tela de cadastro de titular,<br>- Quando preencho os dados obrigatórios e submeto o formulário,<br>- Então o sistema deve salvar o cadastro e gerar uma confirmação de registro.     |
| **Rastreabilidade**    |                                                                                                                                                                                                     |
| **Épico Relacionado**  |                                                                                                                                                                                  |
<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---



| Campo                   | Descrição                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**                 | US02                                                                                                                                                                                                      |
| **Título**             | Cadastro de Dependente                                                                                                                                                                                    |
| **História**           | Como um usuário responsável pelo atendimento,<br>Eu quero cadastrar dependentes vinculados a um titular,<br>Para que esses dependentes possam usufruir dos serviços do plano.                             |
| **Critérios de Aceitação** | - Dado que estou na tela de cadastro de dependente,<br>- Quando escolho um titular existente e preencho os dados do dependente,<br>- Então o sistema deve vincular corretamente e confirmar o cadastro.     |
| **Rastreabilidade**    |                                                                                                                                                                                                     |
| **Épico Relacionado**  |                                                                                                                                                                                  |
<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---



| Campo                   | Descrição                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**                 | US03                                                                                                                                                                                                      |
| **Título**             | Cadastro de Optante                                                                                                                                                                                       |
| **História**           | Como um usuário responsável pelo atendimento,<br>Eu quero cadastrar optantes,<br>Para que eles possam ser incluídos como beneficiários do plano.                                                          |
| **Critérios de Aceitação** | - Dado que estou na tela de cadastro de optante,<br>- Quando preencho corretamente os dados e submeto o formulário,<br>- Então o sistema deve registrar o optante e vincular sua elegibilidade.         |
| **Rastreabilidade**    |                                                                                                                                                                                                     |
| **Épico Relacionado**  |                                                                                                                                                                                  |
<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---



| Campo                   | Descrição                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**                 | US04                                                                                                                                                                                                      |
| **Título**             | Validação de Documentos durante o Cadastro                                                                                                                                                                |
| **História**           | Como um atendente do sistema,<br>Eu quero que os documentos apresentados sejam validados durante o cadastro,<br>Para garantir a autenticidade e integridade das informações fornecidas.                    |
| **Critérios de Aceitação** | - Dado que estou realizando o cadastro de um beneficiário,<br>- Quando os documentos são enviados,<br>- Então o sistema deve verificar sua validade (formato, obrigatoriedade e autenticidade).            |
| **Rastreabilidade**    |                                                                                                                                                                                                     |
| **Épico Relacionado**  |                                                                                                                                                                                  |
<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---



| Campo                   | Descrição                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**                 | US05                                                                                                                                                                                                      |
| **Título**             | Verificação de Elegibilidade no Cadastro                                                                                                                                                                  |
| **História**           | Como um atendente do sistema,<br>Eu quero que a elegibilidade dos titulares, dependentes e optantes seja verificada durante o cadastro,<br>Para garantir que apenas usuários aptos sejam cadastrados.      |
| **Critérios de Aceitação** | - Dado que estou finalizando o cadastro de um beneficiário,<br>- Quando os dados são submetidos,<br>- Então o sistema deve verificar a elegibilidade com base em critérios pré-definidos.                  |
| **Rastreabilidade**    |                                                                                                                                                                                                     |
| **Épico Relacionado**  |                                                                                                                                                                                  |
<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---



| Campo                   | Descrição                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**                 | US06                                                                                                                                                                                                      |
| **Título**             | Verificar Procedimentos com Regras da Tabela                                                                                                                                                              |
| **História**           | Como um analista de autorizações,<br>Eu quero verificar se os procedimentos estão na tabela TABGDFSAÚDE e seguem as regras das DUT e carência,<br>Para decidir se a autorização prévia é necessária.       |
| **Critérios de Aceitação** | - Dado que estou analisando um procedimento solicitado,<br>- Quando informo o código do procedimento,<br>- Então o sistema deve verificar a tabela e indicar se exige análise técnica ou médica.         |
| **Rastreabilidade**    |                                                                                                                                                                                                       |
| **Épico Relacionado**  |                                                                                                                                                                                   |
<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---


| Campo                   | Descrição                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**                 | US07   |
| **Título**             | Permitir Denúncias de Condutas Inadequadas  |
| **História**           | Como um beneficiário do plano de saúde,<br>Eu quero denunciar condutas inadequadas de profissionais credenciados,<br>Para que a operadora possa tomar as devidas providências.                              |
| **Critérios de Aceitação** | - Dado que estou insatisfeito com o atendimento de um profissional,<br>- Quando acesso o canal de denúncias e preencho as informações,<br>- Então o sistema deve registrar e encaminhar para análise.     |
| **Rastreabilidade**    | |
| **Épico Relacionado**  | |
<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

| Campo                      | Descrição |
| -------------------------- | ------------------------ |
| **ID**                     | US01  |
| **Título**                 | Visualizar Histórico de Consultas Realizadas |
| **História**               | Como um usuário do plano de saúde,<br>Eu quero visualizar meu histórico de consultas realizadas,<br>Para que eu possa me lembrar das datas e dos profissionais que visitei para meu próprio controle e para agendar retornos.  |
| **Critérios de Aceitação** | **Cenário 01: Visualizar a lista de consultas**<br>- Dado que o usuário está logado em sua conta,<br>- Quando ele acessa a seção de "Histórico de Consultas",<br>- Então o sistema deve exibir uma lista de todas as suas consultas passadas, ordenadas da mais recente para a mais antiga.<br>- E cada item da lista deve mostrar a data, o nome do profissional e a especialidade da consulta. |
| **Rastreabilidade**        | |
| **Épico Relacionado**      | |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

| Campo                      | Descrição |
| -------------------------- | ------------------------ |
| **ID**                     | US02 |
| **Título**                 | Visualizar Histórico de Exames Realizados |
| **História**               | Como um usuário do plano de saúde,<br>Eu quero ver um histórico de todos os exames que já realizei,<br>Para que eu possa manter um registro dos exames diagnósticos que fiz e quando foram realizados, especialmente para acompanhamento médico de longo prazo.    |
| **Critérios de Aceitação** | **Cenário 01: Visualizar a lista de exames**<br>- Dado que o usuário está logado em sua conta,<br>- Quando ele acessa a seção de "Histórico de Exames",<br>- Então o sistema deve exibir uma lista com todos os seus exames realizados.<br>- E cada item da lista deve detalhar o nome do exame e a data em que foi realizado. |
| **Rastreabilidade**        | |
| **Épico Relacionado**      | |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

| Campo                      | Descrição |
| -------------------------- | ------------------------ |
| **ID**                     | US03 |
| **Título**                 | Visualizar Resultados de Exames Laboratoriais |
| **História**               | Como um usuário do plano de saúde,<br>Eu quero poder visualizar os resultados dos meus exames laboratoriais diretamente no sistema,<br>Para que eu possa entender minha condição de saúde atual e compartilhar os resultados facilmente com meus médicos.  |
| **Critérios de Aceitação** | **Cenário 01: Acessar um resultado de exame**<br>- Dado que o usuário está no "Histórico de Exames",<br>- Quando ele localiza um exame laboratorial que possui um resultado disponível,<br>- Então deve haver um botão ou link claramente identificado como "Ver Resultado" ou similar.<br>- E ao clicar, o sistema deve exibir o resultado, seja em uma nova página ou permitindo o download de um arquivo (ex: PDF). |
| **Rastreabilidade**        | |
| **Épico Relacionado**      | |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

| Campo                      | Descrição |
| -------------------------- | ------------------------ |
| **ID**                     | US04 |
| **Título**                 | Visualizar Histórico de Coparticipações |
| **História**               | Como um usuário do plano de saúde,<br>Eu quero acessar meu histórico detalhado de cobranças de coparticipação,<br>Para que eu possa controlar meus gastos com o plano de saúde e verificar se todas as cobranças estão corretas.    |
| **Critérios de Aceitação** | - Dado que o usuário está logado em sua conta,<br>- Quando ele acessa a seção "Histórico de Coparticipações" ou "Financeiro",<br>- Então o sistema deve exibir uma lista de todas as suas cobranças de coparticipação.<br>- E cada item na lista deve especificar o serviço ao qual a cobrança se refere, a data e o valor cobrado. |
| **Rastreabilidade**        | |
| **Épico Relacionado**      |   |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

| Campo                      | Descrição |
| -------------------------- | ------------------------ |
| **ID**                     | US05  |
| **Título**                 | Favoritar Horários de Consulta Desejados |
| **História**               | Como um usuário que busca agendamento,<br>Eu quero salvar ou "favoritar" horários de consulta que são mais convenientes para mim,<br>Para que eu possa agilizar o processo de marcação no futuro e ter acesso rápido às minhas preferências.  |
| **Critérios de Aceitação** | - Dado que o usuário está visualizando a agenda de um profissional,<br>- Quando ele encontra um horário de sua preferência,<br>- Então deve existir um ícone (como uma estrela) ou botão que permita marcar aquele horário como favorito.<br>- E o sistema deve confirmar que a preferência foi salva. |
| **Rastreabilidade**        |   |
| **Épico Relacionado**      | |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

| Campo                      | Descrição |
| -------------------------- | ------------------------ |
| **ID**                     | US06     |
| **Título**                 | Solicitar Reembolso de Cobrança Indevida de Coparticipação |
| **História**               | Como um usuário do plano de saúde,<br>Eu quero iniciar uma solicitação de reembolso para uma cobrança de coparticipação que considero incorreta,<br>Para que eu possa corrigir o erro financeiro e reaver o valor que foi pago indevidamente.  |
| **Critérios de Aceitação** | - Dado que o usuário está visualizando seu histórico de coparticipações,<br>- Quando ele identifica uma cobrança indevida e clica na opção "Contestar" ou "Solicitar Reembolso",<br>- Então o sistema deve abrir um formulário para a solicitação.<br>- E o formulário deve permitir que o usuário escreva uma justificativa e anexe documentos, se necessário.<br>- E após o envio, o sistema deve exibir uma mensagem de confirmação com um número de protocolo para acompanhamento. |
| **Rastreabilidade**        |           |
| **Épico Relacionado**      |  |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

# US01 – Apresentar uma seção no menu principal chamada "Novidades"

| Campo                   | Descrição                                                                                                                                                                                                 |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ID | USO1 |
| Título | Apresentar seção "Novidades" no menu principal |
| História | Como um usuário do aplicativo,<br>Eu quero ver uma seção chamada "Novidades" no menu principal,<br>Para que eu possa acessar facilmente as novas funções. |
| Critérios de Aceitação | <br>- Dado que o usuário acessa o menu principal,<br>- Quando o sistema estiver atualizado com essa funcionalidade,<br>- Então a opção "Novidades" deve estar visível. |
| Rastreabilidade | RF12.1 |
| Épico Relacionado |   |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB"> Othavio Araujo Bolzan</a></p>

---

# US02 – Exibir uma lista com título, descrição e data de lançamento das novas funcionalidades
| Campo                   | Descrição                                                                                                                                                                                                 |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ID | US02 |
| Título | Exibir lista de funcionalidades com título, descrição e data |
| História | Como um usuário do aplicativo,<br>Eu quero ver uma lista com o título, descrição e data de lançamento das funcionalidades,<br>Para entender o que foi adicionado recentemente. |
| Critérios de Aceitação | <br>- Dado que o usuário acessou a seção "Novidades",<br>- Quando houver funcionalidades disponíveis,<br>- Então o sistema deve exibir uma lista com título, descrição e data. |
| Rastreabilidade | RF12.2 |
| Épico Relacionado |   |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB"> Othavio Araujo Bolzan</a></p>

---

# US03 – Destacar funcionalidades novas com um marcador de "Novo" por um período configurável
| Campo                   | Descrição                                                                                                                                                                                                 |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ID | US12.3 |
| Título | Marcar funcionalidades novas com "Novo" |
| História | Como um usuário do aplicativo,<br>Eu quero ver um marcador "Novo" em funcionalidades recém-lançadas,<br>Para identificar rapidamente o que acabou de ser adicionado. |
| Critérios de Aceitação | <br>- Dado que uma funcionalidade foi lançada,<br>- Quando ela estiver dentro do período configurado (ex: 7 dias),<br>- Então o sistema deve exibir um marcador "Novo" ao lado dela. |
| Rastreabilidade | RF12.3 |
| Épico Relacionado |   |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB"> Othavio Araujo Bolzan</a></p>

---

# US04 – Notificar via push quando novas funcionalidades forem lançadas
| Campo                   | Descrição                                                                                                                                                                                                 |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ID | US04 |
| Título | Notificar o usuário sobre novas funcionalidades |
| História | Como um usuário do aplicativo,<br>Eu quero receber notificações push quando uma nova funcionalidade for lançada,<br>Para me manter informado das novidades sem precisar abrir o app. |
| Critérios de Aceitação | <br>- Dado que uma nova funcionalidade foi lançada,<br>- Quando as notificações estiverem ativadas,<br>- Então o sistema deve enviar uma notificação push ao usuário. |
| Rastreabilidade | RF12.4 |
| Épico Relacionado |   |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB"> Othavio Araujo Bolzan</a></p>

---

# US05 – Permitir ver descrição detalhada, imagens ou vídeos das funcionalidades
| Campo                   | Descrição                                                                                                                                                                                                 |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ID | US05 |
| Título | Ver detalhes de funcionalidades novas |
| História | Como um usuário do aplicativo,<br>Eu quero tocar em uma funcionalidade da lista de novidades,<br>Para visualizar uma descrição detalhada, imagens ou vídeos demonstrativos dessa funcionalidade. |
| Critérios de Aceitação | <br>- Dado que o usuário acessou a seção "Novidades",<br>- Quando ele tocar em um item da lista,<br>- Então o sistema deve exibir uma tela com descrição completa, imagens e/ou vídeos da funcionalidade. |
| Rastreabilidade | RF12.5 |
| Épico Relacionado |   |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB"> Othavio Araujo Bolzan</a></p>

---

# US06 – Permitir ordenar as novidades por "mais recente" e "mais antigo"
| Campo                   | Descrição                                                                                                                                                                                                 |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ID | US06 |
| Título | Ordenar novidades por data |
| História | Como um usuário do aplicativo,<br>Eu quero poder ordenar a lista de novidades por "mais recente" ou "mais antigo",<br>Para encontrar facilmente funcionalidades conforme a data. |
| Critérios de Aceitação | <br>- Dado que o usuário está visualizando a lista de novidades,<br>- Quando ele selecionar a opção de ordenação desejada,<br>- Então o sistema deve reordenar a lista conforme a escolha. |
| Rastreabilidade | RF12.6 |
| Épico Relacionado |   |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB"> Othavio Araujo Bolzan</a></p>

---


## Histórico de Versões

| Versão | Data       | Descrição            | Autor(es)                                       | Revisor(es)                                 |
| ------ | ---------- | -------------------- | ----------------------------------------------- | ------------------------------------------- |
| `1.0` | 30/05/2025  | Criação do documento, adição das histórias de usuários vindas dos arquivos temporários dos integrantes do grupo |  [Isaque Camargos](https://github.com/isaqzin)| [Othavio Bolzan ](https://github.com/bolzanMGB) |