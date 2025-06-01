

| Campo                   | Descrição                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**                 | US01                                                                                                                                                                                                      |
| **Título**             | Cadastro de Titular                                                                                                                                                                                       |
| **História**           | Como um usuário responsável pelo atendimento,<br>Eu quero cadastrar titulares no sistema,<br>Para que eles possam acessar os serviços oferecidos pelo plano de saúde.                                     |
| **Critérios de Aceitação** | - Dado que estou na tela de cadastro de titular,<br>- Quando preencho os dados obrigatórios e submeto o formulário,<br>- Então o sistema deve salvar o cadastro e gerar uma confirmação de registro.     |
| **Rastreabilidade**    |         [RF07](../../elicitacao/elicitacao.md#RF07)                                                                                                                                                                                            |
| **Épico Relacionado**  |                                                                                                                                                                                  |
<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---



| Campo                   | Descrição                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**                 | US02                                                                                                                                                                                                      |
| **Título**             | Cadastro de Dependente                                                                                                                                                                                    |
| **História**           | Como um usuário responsável pelo atendimento,<br>Eu quero cadastrar dependentes vinculados a um titular,<br>Para que esses dependentes possam usufruir dos serviços do plano.                             |
| **Critérios de Aceitação** | - Dado que estou na tela de cadastro de dependente,<br>- Quando escolho um titular existente e preencho os dados do dependente,<br>- Então o sistema deve vincular corretamente e confirmar o cadastro.     |
| **Rastreabilidade**    |         [RF07](../../elicitacao/elicitacao.md#RF07)                                                                                                                                                                                            |
| **Épico Relacionado**  |                                                                                                                                                                                  |
<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---



| Campo                   | Descrição                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**                 | US03                                                                                                                                                                                                      |
| **Título**             | Cadastro de Optante                                                                                                                                                                                       |
| **História**           | Como um usuário responsável pelo atendimento,<br>Eu quero cadastrar optantes,<br>Para que eles possam ser incluídos como beneficiários do plano.                                                          |
| **Critérios de Aceitação** | - Dado que estou na tela de cadastro de optante,<br>- Quando preencho corretamente os dados e submeto o formulário,<br>- Então o sistema deve registrar o optante e vincular sua elegibilidade.         |
| **Rastreabilidade**    |      [RF07](../../elicitacao/elicitacao.md#RF07)                                                                                                                                                                                               |
| **Épico Relacionado**  |                                                                                                                                                                                  |
<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---



| Campo                   | Descrição                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**                 | US04                                                                                                                                                                                                      |
| **Título**             | Validação de Documentos durante o Cadastro                                                                                                                                                                |
| **História**           | Como um atendente do sistema,<br>Eu quero que os documentos apresentados sejam validados durante o cadastro,<br>Para garantir a autenticidade e integridade das informações fornecidas.                    |
| **Critérios de Aceitação** | - Dado que estou realizando o cadastro de um beneficiário,<br>- Quando os documentos são enviados,<br>- Então o sistema deve verificar sua validade (formato, obrigatoriedade e autenticidade).            |
| **Rastreabilidade**    |        [RF07](../../elicitacao/elicitacao.md#RF07)                                                                                                                                                                                             |
| **Épico Relacionado**  |                                                                                                                                                                                  |
<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---



| Campo                   | Descrição                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**                 | US05                                                                                                                                                                                                      |
| **Título**             | Verificação de Elegibilidade no Cadastro                                                                                                                                                                  |
| **História**           | Como um atendente do sistema,<br>Eu quero que a elegibilidade dos titulares, dependentes e optantes seja verificada durante o cadastro,<br>Para garantir que apenas usuários aptos sejam cadastrados.      |
| **Critérios de Aceitação** | - Dado que estou finalizando o cadastro de um beneficiário,<br>- Quando os dados são submetidos,<br>- Então o sistema deve verificar a elegibilidade com base em critérios pré-definidos.                  |
| **Rastreabilidade**    |        [RF07](../../elicitacao/elicitacao.md#RF07)                                                                                                                                                                                             |
| **Épico Relacionado**  |                                                                                                                                                                                  |
<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---



| Campo                   | Descrição                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**                 | US06                                                                                                                                                                                                      |
| **Título**             | Verificar Procedimentos com Regras da Tabela                                                                                                                                                              |
| **História**           | Como um analista de autorizações,<br>Eu quero verificar se os procedimentos estão na tabela TABGDFSAÚDE e seguem as regras das DUT e carência,<br>Para decidir se a autorização prévia é necessária.       |
| **Critérios de Aceitação** | - Dado que estou analisando um procedimento solicitado,<br>- Quando informo o código do procedimento,<br>- Então o sistema deve verificar a tabela e indicar se exige análise técnica ou médica.         |
| **Rastreabilidade**    |       [RF08](../../elicitacao/elicitacao.md#RF08)                                                                                                                                                                                                |
| **Épico Relacionado**  |                                                                                                                                                                                   |
<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---


| Campo                   | Descrição                                                                                                                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**                 | US07                                                                                                                                                                                                      |
| **Título**             | Permitir Denúncias de Condutas Inadequadas                                                                                                                                                                |
| **História**           | Como um beneficiário do plano de saúde,<br>Eu quero denunciar condutas inadequadas de profissionais credenciados,<br>Para que a operadora possa tomar as devidas providências.                              |
| **Critérios de Aceitação** | - Dado que estou insatisfeito com o atendimento de um profissional,<br>- Quando acesso o canal de denúncias e preencho as informações,<br>- Então o sistema deve registrar e encaminhar para análise.     |
| **Rastreabilidade**    |       [RF18](../../elicitacao/elicitacao.md#RF18)                                                                                                                                                                                               |
| **Épico Relacionado**  |                                                                                                                                                                                |
<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>