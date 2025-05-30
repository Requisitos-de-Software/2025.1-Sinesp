| Campo                   | Descrição                                                                                                                                                                                                 |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID** | US01                                                                                                                                                                                                      |
| **Título** | Agendar Consultas e Exames pelo Aplicativo                                                                                                                                                                |
| **História** | Como um usuário do plano de saúde,<br>Eu quero agendar consultas e exames diretamente pelo aplicativo,<br>Para que eu possa gerenciar minha saúde de forma conveniente e eficiente.                      |
| **Critérios de Aceitação** | <br>- Dado que o usuário está logado no aplicativo,<br>- Quando ele seleciona a opção de agendamento e escolhe uma especialidade/exame, prestador e horário,<br>- Então o sistema deve confirmar o agendamento e exibir os detalhes. |
| **Rastreabilidade** |     [RNF05](../../elicitacao/elicitacao.md#RNF05)                                                                                                                                                                                                      |
| **Épico Relacionado** |                                                                                                                                                                                                           |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>


---

| Campo                   | Descrição                                                                                                                                                                                                 |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID** | US02                                                                                                                                                                                                      |
| **Título** | Realizar Pagamento Automático a Prestadores                                                                                                                                                             |
| **História** | Como um usuário do plano de saúde,<br>Eu quero que o pagamento seja realizado automaticamente para os prestadores da Rede de Atendimento,<br>Para que eu não precise me preocupar com transações manuais após a consulta ou exame. |
| **Critérios de Aceitação** | <br>- Dado que o usuário realiza uma consulta ou exame com um prestador da Rede de Atendimento e possui um método de pagamento configurado,<br>- Quando o atendimento é concluído,<br>- Então o sistema deve processar o pagamento automaticamente ao prestador. |
| **Rastreabilidade** |     [RF05.2](../../elicitacao/elicitacao.md#RF05.2)                                                                                                                                                                                                      |
| **Épico Relacionado** |                                                                                                                                                                                                           |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

| Campo                   | Descrição                                                                                                                                                                                                 |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID** | US03                                                                                                                                                                                                      |
| **Título** | Cancelar Consultas e Exames pelo Aplicativo                                                                                                                                                               |
| **História** | Como um usuário do plano de saúde,<br>Eu quero cancelar consultas e exames diretamente pelo aplicativo,<br>Para que eu possa gerenciar meus compromissos de forma flexível e evitar custos desnecessários. |
| **Critérios de Aceitação** | <br>- Dado que o usuário possui um agendamento de consulta ou exame ativo no aplicativo,<br>- Quando ele seleciona a opção de cancelamento e confirma a ação,<br>- Então o sistema deve cancelar o agendamento e, se aplicável, processar qualquer ajuste financeiro automático com o prestador. |
| **Rastreabilidade** |     [RF05.3](../../elicitacao/elicitacao.md#RF05.3)                                                                                                                                                                                                      |
| **Épico Relacionado** |                                                                                                                                                                                                           |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

| Campo                   | Descrição                                                                                                                                                                                                 |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID** | US04                                                                                                                                                                                                      |
| **Título** | Exibir Valor da Consulta por Clínica                                                                                                                                                                      |
| **História** | Como um usuário do plano de saúde,<br>Eu quero ver o valor específico da consulta para cada clínica,<br>Para que eu possa tomar decisões informadas sobre onde realizar meu atendimento.           |
| **Critérios de Aceitação** | <br>- Dado que o usuário está pesquisando por clínicas ou prestadores de saúde,<br>- Quando ele visualiza os detalhes de uma clínica ou prestador,<br>- Então o sistema deve exibir o valor da consulta associado a essa clínica ou prestador. |
| **Rastreabilidade** |     [RF06.1](../../elicitacao/elicitacao.md#RF06.1)                                                                                                                                                                                                      |
| **Épico Relacionado** |                                                                                                                                                                                                           |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

| Campo                   | Descrição                                                                                                                                                                                                 |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID** | US05                                                                                                                                                                                                      |
| **Título** | Visualizar Valor da Coparticipação                                                                                                                                                                        |
| **História** | Como um beneficiário do plano de saúde,<br>Eu quero que o sistema calcule e exiba o valor da minha coparticipação para cada consulta ou procedimento,<br>Para que eu tenha clareza sobre meus custos e possa planejar minhas despesas. |
| **Critérios de Aceitação** | <br>- Dado que o usuário realiza uma consulta ou procedimento sujeito a coparticipação,<br>- Quando o sistema processa o registro desse atendimento,<br>- Então o valor da coparticipação deve ser calculado e exibido no extrato ou detalhe do atendimento do usuário. |
| **Rastreabilidade** |     [RF06.2](../../elicitacao/elicitacao.md#RF06.2)                                                                                                                                                                                                      |
| **Épico Relacionado** |                                                                                                                                                                                                           |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

| Campo                   | Descrição                                                                                                                                                                                                 |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID** | US06                                                                                                                                                                                                      |
| **Título** | Gerar e Baixar Demonstrativo para Imposto de Renda                                                                                                                                                        |
| **História** | Como um usuário do plano de saúde,<br>Eu quero gerar e baixar um demonstrativo de minhas despesas médicas,<br>Para que eu possa utilizar no meu imposto de renda de forma prática e organizada.       |
| **Critérios de Aceitação** | <br>- Dado que o usuário acessa a seção de demonstrativos no aplicativo,<br>- Quando ele seleciona o período desejado e a opção de gerar/baixar,<br>- Então o sistema deve gerar um arquivo (ex: PDF) com o demonstrativo de despesas médicas, permitindo o download. |
| **Rastreabilidade** |     [RF06.3](../../elicitacao/elicitacao.md#RF06.3)                                                                                                                                                                                                      |
| **Épico Relacionado** |                                                                                                                                                                                                           |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>