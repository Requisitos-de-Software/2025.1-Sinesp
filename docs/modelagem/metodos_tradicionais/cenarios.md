# Cenário

## Introdução 

Este documento apresenta uma coleção detalhada de cenários de uso, projetados para dar vida aos requisitos do aplicativo GDF Saúde. Cada cenário descreve uma jornada específica do usuário, ilustrando como as funcionalidades serão utilizadas em situações práticas e cotidianas.

A construção destes cenários foi fundamentada tanto nos **requisitos funcionais**, que definem o que o sistema deve fazer, quanto nos **requisitos não funcionais**, que especificam como o sistema deve operar em termos de desempenho, segurança e usabilidade. Essa abordagem integrada garante que o desenvolvimento não apenas atenda às necessidades diretas do usuário, mas também proporcione uma experiência robusta, segura e eficiente.

Para cada cenário, são detalhados os **Atores** envolvidos, os **Recursos** necessários, as possíveis **Exceções** que podem ocorrer e as **Restrições** que devem ser observadas. Ao final, os **Episódios** narram o passo a passo da interação. O objetivo é fornecer uma visão clara e inequívoca do comportamento esperado do sistema, servindo como uma ferramenta essencial para as equipes de desenvolvimento, testes e validação.

## Integrantes do Grupo

Na tabela 1 contêm todos os integrantes da equipe que participaram na construção dos cenários e o que a pessoa desenvolveu durante o projeto.

<p align="center">Tabela 1 - Integrantes do grupo envolvidos</p>

<div align="center">
    <table>
        <thead>
            <tr>
                <th>Nome</th>
                <th>Quais etapas participou</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><a href="https://github.com/Ana-Luiza-SC" target="_blank">Ana Luiza Soares</a></td>
                <td>Criou os cenários: 1, 2, 21, 22, 23 e 24. Além disso, consolidou o documento final ao pegar os cenários separados, que se encontravam na plataforma <a href="https://stackedit.io/app#">StackEdit</a> e organizar no documento final para o Github Pages. Além disso refatorou os cenários para fazerem sentido para os novos requisitos finais e arrumou a rastreabilidade de todos os requisitos do antigo para o novo</td>
            </tr>
            <tr>
                <td><a href="https://github.com/isaqzin" target="_blank">Isaque Camargos</a></td>
                <td> Inicou o documento criando a introdução e criou os cenários: 3, 4, 19, 25, 25 e 26.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/kalebmacedo" target="_blank">Kaleb Macedo</a></td>
                <td>Criou os cenários: 5, 6, 17, 27 e 28.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/LucasAlves71" target="_blank">Lucas Alves</a></td>
                <td>Criou os cenários: 7, 8, 16, 18, 29 e 30.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a></td>
                <td>Desenvolveu a metodologia e criou os cenários: 9, 10, 20, 31 e 32.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a></td>
                <td>Criou os cenários: 11, 12, 33 e 34.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></td>
                <td>Ajustou a tabela 1 e criou os cenários: 13, 14, 15, 35 e 36.</td>
            </tr>
        </tbody>
    </table>
</div>

<p  align="center">Fonte: Autoria de <a  href="https://github.com/isaqzin">Isaque Camargos</a>, <a  href="https://github.com/isaqzin">Yzabella Miranda</a> e <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

## Metodologia


Inicialmente, utilizou-se o editor online [StackEdit](https://stackedit.io/app#) na construção e organização do conteúdo para evitar conflitos de formatação, uma vez que todos do grupo estão envolvidos no desenvolvimento deste artefato, e garantir uma documentação limpa e padronizada.

A metodologia de documentação foi aprimorada com base nos conceitos e na estrutura propostos nos slides de aula "Requisitos – Aula 10", de Milene Serrano e Maurício Serrano. O PDF dos slides pode ser acessado [neste link](../../assets/Requisitos-Aula-10.pdf).

A elaboração dos cenários seguiu a estratégia de modelagem de requisitos para compreender as interações entre o ambiente e o sistema, bem como para detalhar o comportamento, a dinâmica e o fluxo do software. Cada cenário foi desenvolvido a partir da identificação dos requisitos do sistema, utilizando um conjunto específico de abstrações para garantir uma documentação clara e padronizada, conforme introduzido na [página 8](../../assets/Requisitos-Aula-10.pdf#page=8) do material de referência.

A estrutura adotada para cada cenário foi padronizada em um formato de tabela, incorporando os seguintes elementos, conforme definido no material de referência:

* **Título:** Identifica o cenário, geralmente vinculado ao objetivo principal ou requisito funcional, conforme exemplificado na [página 9](../../assets/Requisitos-Aula-10.pdf#page=9)
* **Metas/Objetivos:** Descreve o propósito do cenário e o que se espera alcançar com a funcionalidade, conforme exemplificado na [página 9](../../assets/Requisitos-Aula-10.pdf#page=9)
* **Contexto:** Define a situação e o ambiente em que o cenário se desenrola, estabelecendo a pré-condição para o fluxo de eventos, conforme exemplificado na [página 9](../../assets/Requisitos-Aula-10.pdf#page=9)
* **Ator(es):** Mapeia as pessoas, sistemas ou entidades que interagem diretamente com a funcionalidade descrita, conforme exemplificado na [página 9](../../assets/Requisitos-Aula-10.pdf#page=9)
* **Recursos:** Lista as ferramentas, dados ou componentes do sistema necessários para a execução do cenário, conforme exemplificado na [página 10](../../assets/Requisitos-Aula-10.pdf#page=10).
* **Exceções:** Prevê condições ou eventos inesperados que podem interromper o fluxo normal do cenário. Um exemplo prático é ilustrado na [página 10](../../assets/Requisitos-Aula-10.pdf#page=10).
* **Restrições:** Aponta limitações, regras de negócio ou condições que devem ser respeitadas durante a execução, conforme exemplificado na [página 10](../../assets/Requisitos-Aula-10.pdf#page=10).
* **Episódios:** Detalha a sequência de passos ou ações que descrevem o fluxo principal de interações e as decisões tomadas pelos atores,conforme exemplificado na [página 10](../../assets/Requisitos-Aula-10.pdf#page=10).

A documentação foi padronizada utilizando tabelas no seguinte formato apresentado na Tabela 2 abaixo.


<p  align="center">Tabela 2: padrão de cenários</p>


| **Seção** | **Significado** |
|---------------|-------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a>CEX</a>  |
| **Título** | Nome ou identificação do cenário, geralmente relacionado ao requisito funcional ou objetivo principal. |
| **Metas/Objetivos** | Descreve o propósito do cenário, indicando o que se espera alcançar com a funcionalidade ou processo. |
| **Contexto** | Situação inicial ou ambiente em que o cenário ocorre, incluindo informações relevantes para compreensão do fluxo. |
| **Ator(es)**| Pessoas, sistemas ou entidades que interagem diretamente com a funcionalidade descrita no cenário. |
| **Recursos** | Ferramentas, sistemas, dispositivos ou dados necessários para a execução do cenário. |
| **Exceções** | Situações inesperadas ou condições que podem impedir o fluxo normal do cenário. |
| **Restrições**| Limitações, regras ou condições específicas que devem ser respeitadas durante a execução do cenário. |
| **Episódios**| Passos ou ações detalhadas que descrevem o fluxo principal e alternativo do cenário, incluindo interações e decisões.|

<p  align="center">Fonte: Autoria de <a  src="https://github.com/matheusdealcantara"  targe="_blank">Matheus de Alcântara</a>
</p>

---

## Cenários

Os cenários desenvolvidos com base nos requisitos funcionais e não funcionais estão descritos nas Tabelas 3 a 39. Cada cenário apresenta uma situação prática de uso do sistema, contemplando seus elementos principais, como metas, **Contexto**, atores, **Recursos** envolvidos, **Exceções** e **Episódios**. A seguir, são apresentados os cenários de forma detalhada:

### Cenário 1: Pesquisa e filtro de redes credenciadas
 
**Requisito Associado:** [RF01.1](../../../elicitacao/requisitos_finais/#RF01.1)  

<p align="center">Tabela 3 - Cenário 1 </p>


| Elemento | Descrição |
| :--- | :--- |
|**ID**|  <a id="CE01">CE01</a>  |
| **Título** | Pesquisa e filtro de redes credenciadas |
| **Metas/Objetivos** | Permitir ao usuário localizar redes credenciadas (hospitais, clínicas, laboratórios) com base em critérios como especialidade, tipo de serviço, região administrativa e proximidade. |
| **Contexto** | Um usuário precisa realizar um exame de sangue e busca por laboratórios credenciados pelo GDF Saúde que fiquem próximos ao seu trabalho no Plano Piloto. |
| **Ator(es)**| - Usuário do GDF Saúde.<br>- Sistema de busca do aplicativo. |
| **Recursos** | - Aplicativo GDF Saúde com funcionalidade de busca.<br>- Banco de dados com informações das redes credenciadas.<br>- Sistema de geolocalização. |
| **Exceções** | - A busca não retorna nenhum resultado para os filtros aplicados.<br>- As informações de uma clínica (endereço, telefone) estão desatualizadas.<br>- Falha ao carregar o mapa de localização. |
| **Restrições** | Os dados das redes credenciadas devem ser atualizados continuamente para garantir a precisão dos resultados da busca. |
| **Episódios**| 1. O usuário acessa a funcionalidade "Buscar Rede Credenciada".<br>2. Aplica o filtro "Tipo de Estabelecimento: Laboratório".<br>3. Adiciona o filtro "Região Administrativa: Plano Piloto".<br>4. O sistema exibe uma lista de laboratórios no Plano Piloto, ordenados por proximidade.<br>5. O usuário seleciona um laboratório para ver mais detalhes. |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC" target="_blank">Ana Luiza Soares</a></p>

---

### Cenário 2: Avaliação de Clínicas  
**Requisito Associado:** [RF02.1](../../../elicitacao/requisitos_finais/#RF02.1)  

<p align="center">Tabela 4 - Cenário 2 </p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** |  <a id="CE02">CE02</a>  |
| **Título** | Avaliação de Atendimento com Escala Likert |
| **Metas/Objetivos** | Permitir que o usuário avalie a qualidade de um atendimento específico utilizando uma escala Likert de 0 a 5, oferecendo um feedback mais detalhado sobre sua satisfação. |
| **Contexto** | Após uma consulta de rotina, um usuário acessa o aplicativo GDF Saúde para registrar sua experiência. Ele seleciona a opção "4 - Satisfeito" na escala de avaliação e deixa um comentário elogiando a pontualidade do atendimento. |
| **Ator(es)** | - Usuário do GDF Saúde.<br>- Sistema de avaliação do aplicativo. |
| **Recursos** | - Aplicativo GDF Saúde.<br>- Histórico de atendimentos do usuário.<br>- Interface de avaliação com escala Likert de 0 a 5 (onde 0 é "Muito Insatisfeito" e 5 é "Muito Satisfeito") e campo para comentários. |
| **Exceções** | - O sistema apresenta um erro e não consegue registrar a avaliação enviada.<br>- O usuário tenta avaliar um atendimento que ainda não foi concluído. |
| **Restrições** | - O sistema deve permitir apenas uma avaliação por atendimento realizado.<br>- A interface deve exibir claramente o significado de cada nível da escala Likert para orientar o usuário.<br>- O sistema deve possuir um mecanismo para moderar ou filtrar comentários com linguagem inadequada. |
| **Episódios** | 1. O usuário acessa a seção "Histórico de Atendimentos" no aplicativo.<br>2. Localiza e seleciona a consulta que deseja avaliar.<br>3. Clica na opção “Avaliar Atendimento”.<br>4. O sistema exibe a escala de avaliação de 0 a 5.<br>5. O usuário seleciona a nota "4 - Satisfeito".<br>6. Opcionalmente, o usuário escreve um comentário no campo de texto.<br>7. A avaliação é registrada e associada àquele atendimento específico. |


<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC" target="_blank">Ana Luiza Soares</a></p>

---

### Cenário 3: Acesso à carteirinha digital sem conexão à internet  
**Requisito Associado:** [RF03](../../../elicitacao/requisitos_finais/#RF03)  

<p align="center">Tabela 5 - Cenário 3</p>

| Elemento        | Descrição                                                                                                                                                                                                                                          |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID** |  <a id="CE03">CE03</a>  |
| **Título**        | Acesso à carteirinha digital sem conexão à internet                                                                                                                                                                                                |
| **Metas/Objetivos** | Permitir que o usuário baixe a carteirinha para acessá-la posteriormente sem conexão à internet.                                                                                                                                                   |
| **Contexto**        | O usuário está em um hospital, clínica ou laboratório e precisa da carteirinha para solicitar autorização do procedimento. Sem a carteirinha física e sem conexão, ele acessa a galeria de fotos do dispositivo, onde já havia baixado o arquivo. |
| **Ator(es)**        | - Usuário cadastrado (titular ou dependente).<br>- INAS: fornece dados para emissão da carteirinha.<br>- Galeria de fotos: sistema externo que armazena o arquivo local.                                                                           |
| **Recursos**        | - App GDF Saúde (mobile).<br>- Dispositivo do usuário (smartphone, tablet ou computador).<br>- Armazenamento local para a carteirinha.<br>- Conexão à internet (só para o download).<br>- App de galeria de fotos.                                  |
| **Exceções**        | - Usuário não baixou a carteirinha e está sem internet.<br>- Erro técnico ao abrir ou ao baixar (ex.: arquivo corrompido).                                                                                                                         |
| **Restrições**      | Depende de download prévio e espaço suficiente no dispositivo.                                                                                                                                                                                       |
| **Episódios**       | 1. Usuário faz login no GDF Saúde.<br>2. Navega até “Carteirinha” e baixa o arquivo (se necessário).<br>3. Sai do app e abre a galeria de fotos.<br>4. Localiza e visualiza a carteirinha offline.                                                  |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### Cenário 4: Recebimento de notificações configuráveis via app, SMS ou e-mail  
**Requisito Associado:** [RF04](../../../elicitacao/requisitos_finais/#RF04)  

<p align="center">Tabela 6 - Cenário 4</p>

| Elemento        | Descrição                                                                                                                                                                                      |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE04">CE04</a>  |
| **Título**       | Recebimento de notificações configuráveis via app, SMS ou e-mail                                                                                                                               |
| **Metas/Objetivos** | Permitir que o usuário receba notificações personalizadas sobre vencimento de faturas, agendamentos e demonstrativos.                                                                          |
| **Contexto**        | O usuário configura no app GDF Saúde quais eventos quer ser lembrado e por quais canais — app, SMS ou e-mail — e passa a receber alertas conforme sua escolha.                                 |
| **Ator(es)**        | - Usuário (titular ou dependente).<br>- Sistema de notificações do GDF Saúde.<br>- Provedores externos de SMS e e‑mail.                                                                         |
| **Recursos**        | - App móvel GDF Saúde.<br>- Dispositivo do usuário.<br>- Internet para configuração e envio.<br>- Servidores de notificação e APIs de SMS/e-mail.                                             |
| **Exceções**        | - Preferências não configuradas.<br>- Sem conexão ao enviar push.<br>- Provedor de SMS/e-mail indisponível.<br>- Caixa de e‑mail cheia ou número incorreto.                                   |
| **Restrições**      | Depende de conexão ativa e permissões corretas no dispositivo.                                                                                                                                 |
| **Episódios**       | 1. Usuário faz login.<br>2. Acessa “Configurações → Notificações”.<br>3. Seleciona tipos e canais de alerta.<br>4. Sistema salva preferências.<br>5. Evento ocorre e notificação é enviada.<br>6. Usuário recebe e visualiza. |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### Cenário 5: Agendar ou cancelar consultas e exames pelo aplicativo  
**Requisito Associado:** [RF05](../../../elicitacao/requisitos_finais/#RF05)  

<p align="center">Tabela 7 - Cenário 5</p>

| Elemento        | Descrição                                                                                                                      |
|-----------------|-------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE05">CE05</a>  |
| **Título**           | Agendar ou cancelar consultas e exames pelo aplicativo                                                                        |
| **Metas/Objetivos** | Permitir que o usuário realize agendamentos e cancelamentos com agilidade, incluindo pagamento automático aos prestadores.     |
| **Contexto**        | O usuário acessa o aplicativo e seleciona a funcionalidade desejada (agendar ou cancelar).                                     |
| **Ator(es)**        | - Usuário.<br>- Sistema de Saúde.<br>- Prestador da Rede de Atendimento.                                                       |
| **Recursos**        | - Banco de dados de prestadores.<br>- Agenda integrada.<br>- Sistema de pagamentos.                                            |
| **Exceções**        | - Tentativa de agendamento com prestador indisponível.<br>- Falha no pagamento automático.                                     |
| **Restrições**      | Funcionalidade disponível apenas para usuários logados e ativos no plano.                                                     |
| **Episódios**       | 1. Usuário acessa a agenda.<br>2. Escolhe prestador e horário.<br>3. Confirma agendamento.<br>4. Pagamento é realizado automaticamente.<br>5. Usuário pode cancelar posteriormente. |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### Cenário 6: Visualizar valores e demonstrativos financeiros no aplicativo  
**Requisito Associado:** [RF06](../../../elicitacao/requisitos_finais/#RF06)  

<p align="center">Tabela 8 - Cenário 6</p>

| Elemento        | Descrição                                                                                                             |
|-----------------|----------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE06">CE06</a>  |
| **Título**           | Visualizar valores e demonstrativos financeiros no aplicativo                                                        |
| **Metas/Objetivos** | Informar o usuário sobre valores de consulta, coparticipações, histórico e geração de demonstrativos para IR.         |
| **Contexto**        | O usuário acessa a área financeira do aplicativo para consultar valores, baixar demonstrativos e ver histórico de IR. |
| **Ator(es)**        | - Usuário.<br>- Sistema do Plano de Saúde.                                                                             |
| **Recursos**        | - Base de dados de valores.<br>- Demonstrativos em PDF.<br>- Extrato financeiro atualizado diariamente.                 |
| **Exceções**        | - Falha no carregamento de dados.<br>- Ausência de histórico para o usuário.                                          |
| **Restrições**      | Acesso restrito a usuários com plano ativo e dados de coparticipação válidos.                                          |
| **Episódios**       | 1. Usuário acessa área de finanças.<br>2. Visualiza valores da clínica.<br>3. Aplica coparticipação.<br>4. Gera e baixa demonstrativo.<br>5. Consulta extrato atualizado. |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### Cenário 7: Cadastrar titulares, dependentes e optantes com validação de documentos  
**Requisito Associado:** [RF07](../../../elicitacao/requisitos_finais/#RF07)  

<p align="center">Tabela 9 - Cenário 7</p>

| Elemento        | Descrição                                                                                                                                                                          |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE07">CE07</a>  |
| **Título**           | Cadastrar titulares, dependentes e optantes com validação de documentos                                                                                                            |
| **Metas/Objetivos** | Garantir o cadastro completo e validado de usuários, incluindo dependentes e optantes, com conferência de documentos e critérios de elegibilidade.                                    |
| **Contexto**        | O usuário inicia o processo de adesão pelo aplicativo ou portal, informando dados pessoais e anexando documentos oficiais para validação.                                           |
| **Ator(es)**        | - Usuário.<br>- Sistema de Adesão.<br>- Operador do Plano.                                                                                                                         |
| **Recursos**        | - Sistema de verificação documental.<br>- Base de dados de elegibilidade.<br>- APIs de consulta a órgãos oficiais (ex.: Receita Federal, cartórios).                              |
| **Exceções**        | - Documentos ilegíveis ou inválidos.<br>- Usuário não elegível como dependente ou optante.<br>- Inconsistência de dados.                                                             |
| **Restrições**      | Cadastro permitido apenas com documentação completa e validação positiva de elegibilidade.                                                                                          |
| **Episódios**       | 1. Usuário acessa o formulário de cadastro.<br>2. Preenche dados e seleciona tipo (titular, dependente ou optante).<br>3. Anexa documentos.<br>4. Sistema valida documentos e elegibilidade.<br>5. Cadastro é aprovado ou encaminhado para análise manual. |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### Cenário 8: Verificar cobertura e necessidade de autorização prévia para procedimentos  
**Requisito Associado:** [RF08](../../../elicitacao/requisitos_finais/#RF08)  

<p align="center">Tabela 10 - Cenário 8</p>

| Elemento        | Descrição                                                                                                                                                                                   |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE08">CE08</a>  |
| **Título**           | Verificar cobertura e necessidade de autorização prévia para procedimentos                                                                                                                  |
| **Metas/Objetivos** | Garantir que os procedimentos solicitados estejam cobertos segundo normas da TABGDFSAÚDE e DUT, incluindo regras de carência e exclusão.                                                    |
| **Contexto**        | O usuário ou prestador solicita um procedimento através do aplicativo ou sistema de autorização, aguardando confirmação automática ou técnica conforme a tabela vigente.                     |
| **Ator(es)**        | - Usuário ou prestador.<br>- Sistema de Saúde.<br>- Equipe Técnica de Autorização.                                                                                                          |
| **Recursos**        | - Tabela TABGDFSAÚDE.<br>- DUTs.<br>- Regras contratuais de carência/exclusão.<br>- Sistema de autorização técnica.                                                                          |
| **Exceções**        | - Procedimento fora da cobertura.<br>- Ausência de DUT.<br>- Falta de solicitação médica válida.<br>- Necessidade de parecer técnico adicional.                                             |
| **Restrições**      | Procedimentos só podem ser autorizados com documentação médica adequada e dentro das regras da tabela vigente.                                                                              |
| **Episódios**       | 1. Usuário ou prestador solicita o procedimento.<br>2. Sistema verifica na TABGDFSAÚDE.<br>3. Confirma DUT e regras de carência/exclusão.<br>4. Se exigido, solicita encaminhamento médico.<br>5. Análise técnica é realizada antes da liberação. |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### Cenário 9: Visualizar Histórico de Guias  
**Requisito Associado:** [RF09](../../../elicitacao/requisitos_finais/#RF09)  

<p align="center">Tabela 11 - Cenário 09</p>

| Elemento        | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE09">CE09</a>  |
| **Título**          | Visualizar Histórico de Guias RF09                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Metas/Objetivos** | Permitir que o usuário visualize seu histórico de saúde, incluindo consultas médicas, exames realizados, resultados laboratoriais e coparticipações, de forma organizada e acessível para acompanhar seu histórico médico e financeiro.                                                                                                                                                                                                                                                                                                  |
| **Contexto**        | Usuário autenticado no app móvel GDF Saúde deseja revisar seu histórico de atendimentos e despesas relacionadas ao plano (consultas, exames, coparticipações).                                                                                                                                                                                                                                                                                                                                                                        |
| **Ator(es)**        | - Usuário cadastrado no GDF Saúde<br>- Sistema de histórico do aplicativo                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Recursos**        | - App GDF Saúde<br>- Seção “Histórico de Guias” ou equivalente<br>- Banco de dados de consultas, exames, resultados e coparticipações<br>- Conexão à internet<br>- Dispositivo do usuário (smartphone, tablet ou computador)                                                                                                                                                                                                                                                                                                      |
| **Exceções**        | - Usuário não autenticado (impede acesso)<br>- Sem histórico disponível (novo usuário ou falha de sincronização)<br>- Erro técnico (falha no servidor ou BD)<br>- Conexão instável interrompe o carregamento                                                                                                                                                                                                                                                                                                                            |
| **Restrições**      | - Autenticação obrigatória via INAS<br>- Apenas titular ou dependentes autorizados podem acessar<br>- Criptografia e LGPD para armazenamento e transmissão<br>- Desempenho: tempo de carregamento < 2 s<br>- Acessibilidade conforme WCAG 2.1 AA                                                                                                                                                                                                                                                                                      |
| **Episódios**       | 1. Usuário faz login no GDF Saúde.<br>2. Navega até “Histórico de Guias”.<br>3. Sistema exibe lista com consultas, exames, resultados e coparticipações.<br>4. Usuário clica em um item para ver detalhes completos.<br>5. Se sem histórico, exibe “Nenhum histórico disponível”.<br>6. Se erro técnico, exibe “Erro ao carregar histórico” e oferece “Tentar novamente” ou “Suporte”.<br>7. Usuário sai da seção ou do app. |


<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a></p>

---

### Cenário 10: Favoritar Horários de Consulta  
**Requisito Associado:** [RF10](../../../elicitacao/requisitos_finais/#RF10)  

<p align="center">Tabela 12 - Cenário 10</p>

| Elemento        | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE10">CE10</a>  |
| **Título**           | Favoritar Horários de Consulta RF10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Metas/Objetivos** | Permitir que o usuário marque como favoritos horários desejados durante o agendamento, facilitando futuras reservas rápidas e convenientes.                                                                                                                                                                                                                                                                                                                                                                                     |
| **Contexto**        | Usuário autenticado no app móvel GDF Saúde está agendando uma consulta e deseja salvar horários preferidos para uso posterior.                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Ator(es)**        | - Usuário cadastrado no GDF Saúde                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Recursos**        | - App GDF Saúde (mobile)<br>- Interface de agendamento com opção de favoritar<br>- Banco de dados para armazenar favoritos<br>- Conexão à internet<br>- Dispositivo do usuário                                                                                                                                                                                                                                                                                                                                                 |
| **Exceções**        | - Horário já agendado ou indisponível (não pode ser favoritado)<br>- Usuário excede limite de favoritos (ex.: > 5 por médico)<br>- Erro técnico ao salvar favoritos (falha no servidor/BD)<br>- Conexão instável interrompe ação                                                                                                                                                                                                                                                                                                 |
| **Restrições**      | - Verificação em tempo real da disponibilidade<br>- Máximo de 5 favoritos por médico ou especialidade<br>- Lista de favoritos acessível na interface de agendamento<br>- Notificação por e‑mail/app se favoritado tornar‑se indisponível<br>- Feedback visual claro (ícone de estrela e mensagem de confirmação)                                                                                                                                                                                                                  |
| **Episódios**       | 1. Usuário faz login no GDF Saúde.<br>2. Navega até agendamento de consultas.<br>3. Seleciona médico, especialidade ou clínica.<br>4. Sistema exibe horários disponíveis.<br>5. Usuário marca horários com o ícone de favorito.<br>6. Sistema confirma e salva na lista de favoritos.<br>7. Caso horário se torne indisponível, notifica o usuário.                                                                                                                                            |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a></p>

---

### Cenário 11: Canal para o usuário enviar feedback sobre atendimentos  
**Requisito Associado:** [RF11](../../../elicitacao/requisitos_finais/#RF11)  

<p align="center">Tabela 13 - Cenário 11</p>

| Elemento        | Descrição                                                                                                                                                                                                                                                               |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE11">CE11</a> |
| **Título**           | Canal para o usuário enviar feedback sobre atendimentos                                                                                                                                                                                                                 |
| **Metas/Objetivos** | Permitir ao usuário registrar sua experiência, contribuindo para a melhoria da qualidade dos serviços prestados.                                                                                                                                                        |
| **Contexto**        | Após atendimento em clínica agendada pelo app, o usuário acessa o histórico e envia nota e comentário.                                                                                                                                                                     |
| **Ator(es)**        | - Usuário do GDF Saúde.<br>- Módulo de registro de feedback.                                                                                                                                                                                                              |
| **Recursos**        | - App GDF Saúde.<br>- Formulário de avaliação.<br>- Banco de dados de feedback.                                                                                                                                                                                            |
| **Exceções**        | - Falha no envio.<br>- Atendimento não aparece no histórico.                                                                                                                                                                                                              |
| **Restrições**      | Só permite enviar após o atendimento constar no histórico; comentários não podem ser ofensivos.                                                                                                                                                                           |
| **Episódios**       | 1. Usuário acessa o app.<br>2. Abre “Histórico de Atendimentos”.<br>3. Seleciona atendimento e clica em “Enviar Feedback”.<br>4. Preenche nota e comentário.<br>5. Envia o feedback.                                                                                        |

<p align="center">Fonte: Adaptado de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### Cenário 12: Divulgar informações sobre novas funcionalidades no aplicativo  
**Requisito Associado:** [RF12](../../../elicitacao/requisitos_finais/#RF12)  

<p align="center">Tabela 14 - Cenário 12</p>

| Elemento        | Descrição                                                                                                                                                                                                                                                    |
|-----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE12">CE12</a>  |
| **Título**           | Divulgar informações sobre novas funcionalidades                                                                                                                                                                                                             |
| **Metas/Objetivos** | Informar os usuários sobre atualizações e incentivá‑los a usar novos **Recursos**.                                                                                                                                                                               |
| **Contexto**        | Após atualização do app com nova função “Chat com Profissionais”, o sistema exibe uma notificação no primeiro acesso.                                                                                                                                         |
| **Ator(es)**        | - Usuário do GDF Saúde.<br>- Sistema de notificações e gerenciamento de versões.                                                                                                                                                                              |
| **Recursos**        | - App GDF Saúde.<br>- Banco de dados de funcionalidades e changelogs.<br>- Sistema de notificações.                                                                                                                                                            |
| **Exceções**        | - Usuário ignora ou não vê a notificação.<br>- Falha na exibição devido a erro no update.                                                                                                                                                                     |
| **Restrições**      | Notificação exibida apenas uma vez por funcionalidade, de forma não intrusiva.                                                                                                                                                                                |
| **Episódios**       | 1. Atualização instalada.<br>2. Usuário abre o app.<br>3. Notificação sobre a novidade é exibida.<br>4. Usuário clica para saber mais.<br>5. Funcionalidade é apresentada com instruções.                                                                     |

<p align="center">Fonte: Adaptado de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### Cenário 13: Adicionar consulta à rede odontológica  
**Requisito Associado:** [RF13](../../../elicitacao/requisitos_finais/#RF13)  

<p align="center">Tabela 15 - Cenário 13</p>

| Elemento        | Descrição                                                                                                                                                                                                                                          |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE">CE</a>  |
| **Título** <a id="CE13"></a>          | Consulta integrada à rede odontológica pública                                                                                                                                                                                                      |
| **Metas/Objetivos** | Permitir que usuários busquem e agendem consultas em unidades odontológicas públicas via aplicativo, com informações atualizadas da rede de saúde governamental.                                                                                     |
| **Contexto**        | Usuário acessa app GDF Saúde, escolhe “Rede Odontológica”, visualiza clínicas parceiras, horários e vagas em tempo real e agenda o atendimento.                                                                                                       |
| **Ator(es)**        | - Usuário do GDF Saúde<br>- Unidades odontológicas parceiras<br>- Equipe de integração de dados do INAS                                                                                                      |
| **Recursos**        | - Integração com base de dados da rede odontológica pública<br>- Mapa interativo com geolocalização<br>- Sistema de sincronização em tempo real<br>- Filtros (procedimento, localidade, disponibilidade)                                                |
| **Exceções**        | - Informações de vagas ou horários desatualizadas<br>- Falha na integração com a rede odontológica<br>- Erro na exibição do mapa ou filtros                                                                                                         |
| **Restrições**      | - Dados das clínicas devem ser validados diariamente<br>- Atualizações de vagas a cada 15 minutos                                                                                                                                                    |
| **Episódios**       | 1. Usuário acessa “Rede Odontológica”.<br>2. Sistema solicita localização ou usuário insere manualmente.<br>3. Exibe lista/mapa de clínicas e horários disponíveis.<br>4. Usuário filtra e agenda consulta.<br>5. Recebe confirmação via notificação. |

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

---

### Cenário 14: Apresentar novas clínicas e clínicas próximas  
**Requisito Associado:** [RF14](../../../elicitacao/requisitos_finais/#RF14)  

<p align="center">Tabela 16 - Cenário 14</p>

| Elemento        | Descrição                                                                                                                                                                                                  |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE14">CE14</a>  |
| **Título**          | Apresentar clínicas novas e próximas da localização do usuário                                                                                                                                              |
| **Metas/Objetivos** | Permitir ao usuário descobrir facilmente novas clínicas cadastradas e clínicas próximas com base em sua localização atual.                                                                                   |
| **Contexto**        | Usuário abre app com GPS ativo; sistema identifica localização e lista clínicas próximas, destacando novas unidades cadastradas na plataforma.                                                              |
| **Ator(es)**        | - Usuário do GDF Saúde<br>- Sistema de geolocalização do dispositivo<br>- Servidores de GDF Saúde responsáveis pela gestão de clínicas                                                                      |
| **Recursos**        | - Acesso à localização do dispositivo<br>- Banco de dados de clínicas e coordenadas geográficas<br>- Interface de listagem e mapa                                                                            |
| **Exceções**        | - Permissão de localização negada<br>- GPS desativado<br>- Falha ao acessar banco de dados remoto                                                                                                           |
| **Restrições**      | - Depende de permissão de geolocalização<br>- Lista deve ser atualizada periodicamente e exibida de forma clara e acessível                                                                                  |
| **Episódios**       | 1. Usuário abre app com GPS ativo.<br>2. Sistema solicita permissão de localização (se necessário).<br>3. Exibe lista e mapa de clínicas próximas e novas unidades.                                         |

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

---

### Cenário 15: Permitir baixar comprovantes de agendamento  
**Requisito Associado:** [RF15](../../../elicitacao/requisitos_finais/#RF15)  

<p align="center">Tabela 17 - Cenário 15</p>

| Elemento        | Descrição                                                                                                                                                                                                                      |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE15">CE15</a>  |
| **Título**         | Download de comprovantes de agendamento                                                                                                                                                                                       |
| **Metas/Objetivos** | Permitir que o usuário baixe comprovantes de agendamento em formato digital (PDF), garantindo autenticidade e segurança com QR code de validação.                                                                              |
| **Contexto**        | Após agendar uma consulta, o usuário acessa “Meus Agendamentos” e solicita geração de comprovante; o sistema gera PDF criptografado com QR code e oferece opção de download.                                                    |
| **Ator(es)**        | - Usuário do GDF Saúde<br>- Sistema de geração de documentos do INAS<br>- Serviço de armazenamento seguro de arquivos                                                                                                           |
| **Recursos**        | - Gerador de PDF com dados do agendamento e QR code<br>- Armazenamento em nuvem com criptografia<br>- Componente de download integrado ao app                                                                                        |
| **Exceções**        | - Falha ao gerar o comprovante (dados incompletos)<br>- Download não inicia por conexão instável<br>- QR code inválido ou não reconhecido pelo sistema da clínica                                                                   |
| **Restrições**      | - Comprovantes devem conter assinatura digital<br>- Dados sensíveis (ex.: CPF) devem ser mascarados no arquivo                                                                                                                   |
| **Episódios**       | 1. Usuário faz login e acessa “Meus Agendamentos”.<br>2. Seleciona atendimento e clica “Gerar Comprovante”.<br>3. Sistema gera PDF com QR code.<br>4. Usuário baixa ou compartilha o comprovante via e-mail/app. |

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

---

### Cenário 16: Visualizar calendário personalizado com informações do plano  
**Requisito Associado:** [RF16](../../../elicitacao/requisitos_finais/#RF16)  

<p align="center">Tabela 18 - Cenário 16</p>

| Elemento        | Descrição                                                                                                          |
|-----------------|------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE16">CE16</a>  |
| **Título**          | Visualizar calendário personalizado com informações do plano                                                      |
| **Metas/Objetivos** | Permitir ao usuário acompanhar suas consultas, prazos de carência e vencimentos de forma clara e integrada.       |
| **Contexto**        | O usuário acessa o aplicativo e consulta o calendário com eventos relacionados ao seu plano de saúde.             |
| **Ator(es)**        | - Usuário.<br>- Sistema de Saúde.                                                                                  |
| **Recursos**        | - Banco de dados de agendamentos.<br>- Regras de carência.<br>- Datas de vencimento.<br>- Interface de calendário interativo. |
| **Exceções**        | - Falha na sincronização dos dados do calendário.<br>- Ausência de dados atualizados.                             |
| **Restrições**      | Calendário disponível apenas para usuários logados com plano ativo.                                               |
| **Episódios**       | 1. Usuário acessa o aplicativo.<br>2. Entra na aba “Calendário”.<br>3. Visualiza datas de consultas, carência e vencimento.<br>4. Clica em um item para mais detalhes.<br>5. Sistema atualiza automaticamente com novos eventos. |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### Cenário 17: Visualizar painel de metas com gamificação  
**Requisito Associado:** [RF17](../../../elicitacao/requisitos_finais/#RF17)  

<p align="center">Tabela 19 - Cenário 17</p>

| Elemento        | Descrição                                                                                         |
|-----------------|-------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE17">CE17</a>  |
| **Título**          | Visualizar painel de metas com gamificação                                                       |
| **Metas/Objetivos** | Estimular o acompanhamento da saúde por meio de metas e recompensas visuais.                     |
| **Contexto**        | O usuário acessa o painel e verifica seu progresso e as metas a cumprir.                         |
| **Ator(es)**        | - Usuário.<br>- Sistema de Monitoramento de Saúde.                                                |
| **Recursos**        | - Painel com indicadores.<br>- Sistema de gamificação.<br>- Metas configuráveis.                 |
| **Exceções**        | - Falha ao carregar metas personalizadas.<br>- Ausência de dados no perfil.                      |
| **Restrições**      | Requer perfil de saúde completo e permissão para notificações.                                    |
| **Episódios**       | 1. Usuário acessa o painel.<br>2. Visualiza metas ativas.<br>3. Recebe feedback gamificado.<br>4. Acompanha progresso. |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### Cenário 18: Registrar denúncia contra profissional da rede credenciada  
**Requisito Associado:** [RF18](../../../elicitacao/requisitos_finais/#RF18)  

<p align="center">Tabela 20 - Cenário 18</p>

| Elemento        | Descrição                                                                                              |
|-----------------|------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE18">CE18</a>  |
| **Título**          | Registrar denúncia contra profissional da rede credenciada                                             |
| **Metas/Objetivos** | Permitir que usuários denunciem condutas inadequadas de profissionais, garantindo um canal seguro e sigiloso. |
| **Contexto**        | O usuário acessa o aplicativo após atendimento e deseja relatar um problema com um profissional da rede. |
| **Ator(es)**        | - Usuário.<br>- Sistema de Saúde.<br>- Setor de Ouvidoria.                                              |
| **Recursos**        | - Formulário de denúncia.<br>- Base de dados de prestadores.<br>- Canal interno da ouvidoria.           |
| **Exceções**        | - Denúncia com informações insuficientes.<br>- Tentativa de denúncia sem vínculo com atendimento.       |
| **Restrições**      | Apenas usuários logados podem denunciar e devem vincular a denúncia a um atendimento anterior.         |
| **Episódios**       | 1. Usuário acessa o menu “Ouvidoria”.<br>2. Seleciona “Denunciar conduta inadequada”.<br>3. Escolhe profissional/atendimento.<br>4. Preenche formulário e envia.<br>5. Sistema registra e encaminha para análise. |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### Cenário 19: Login por biometria facial ou digital  
**Requisito Associado:** [RF19](../../../elicitacao/requisitos_finais/#RF19)  

<p align="center">Tabela 21 - Cenário 19</p>

| Elemento        | Descrição                                                                                                                                                                                                                                                                                                             |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE19">CE19</a>  |
| **Título**           | Login por biometria facial ou digital                                                                                                                                                                                                                                                                                 |
| **Metas/Objetivos** | Permitir acesso prático e seguro usando biometria, sem digitar senha.                                                                                                                                                                                                                                                  |
| **Contexto**        | Usuário com conta ativa opta por habilitar biometria no primeiro acesso ou depois e passa a usá‑la para autenticar.                                                                                                                                                                                                      |
| **Ator(es)**        | - Usuário do GDF Saúde.<br>- SO (Android/iOS) com suporte biométrico.<br>- App GDF Saúde integrado à biometria.                                                                                                                                                                                                           |
| **Recursos**        | - App móvel GDF Saúde.<br>- Dispositivo com sensor biométrico.<br>- Conexão à internet para configuração inicial.                                                                                                                                                                                                        |
| **Exceções**        | - Dispositivo sem suporte biométrico.<br>- Biometria não cadastrada.<br>- Falha no sensor.<br>- Usuário desativa biometria nas configurações.                                                                                                                                                                            |
| **Restrições**      | Disponível apenas em dispositivos compatíveis e com biometria previamente autorizada.                                                                                                                                                                                                                                   |
| **Episódios**       | 1. Login tradicional com usuário e senha.<br>2. Opção de habilitar biometria é oferecida.<br>3. Usuário confirma e sensor biométrico valida.<br>4. Biometria é configurada com sucesso.<br>5. Futuros logins usam biometria sem senha.                                                                                   |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### Cenário 20: Solicitação de Reembolso de Cobrança Indevida  
**Requisito Associado:** [RF20](../../../elicitacao/requisitos_finais/#RF20)  

<p align="center">Tabela 22 - Cenário 20</p>

| Elemento        | Descrição                                                                                                                              |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE20">CE20</a>  |
| **Título**          | Solicitação de Reembolso de Cobrança Indevida                                                                                          |
| **Metas/Objetivos** | Permitir que o usuário solicite reembolso de uma cobrança indevida de coparticipação, garantindo um processo transparente e eficiente. |
| **Contexto**        | Usuário autenticado no app GDF Saúde identifica uma cobrança indevida e inicia o processo de solicitação de reembolso.                 |
| **Ator(es)**        | - Usuário.<br>- Sistema de reembolso do aplicativo.                                                                                    |
| **Recursos**        | - App GDF Saúde.<br>- Interface de solicitação de reembolso.<br>- Banco de dados de cobranças e coparticipações.<br>- Conexão à internet.<br>- Dispositivo do usuário. |
| **Exceções**        | - Usuário sem acesso ao histórico de cobranças.<br>- Documentação não anexada.<br>- Erro técnico ao enviar a solicitação.                |
| **Restrições**      | Solicitação deve ocorrer em até 30 dias após a cobrança e anexos devem ser criptografados conforme LGPD.                               |
| **Episódios**       | 1. Usuário faz login.<br>2. Navega até “Reembolso” ou “Cobranças”.<br>3. Seleciona “Solicitar Reembolso de Cobrança Indevida”.<br>4. Escolhe cobrança e anexa comprovantes.<br>5. Sistema valida e envia para análise.<br>6. Usuário recebe confirmação via notificação. |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a></p>

---

### Cenário 21: Chatbot para Direcionamento Médico
  
**Requisito Associado:** [RF21](../../../elicitacao/requisitos_finais/#RF21)  

<p align="center">Tabela 23 - Cenário 21 </p>

| Elemento        | Descrição                                                                                                                                                                                                                                 |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE21">CE21</a>  |
| **Título**          | Chatbot para direcionamento médico                                                                                                                                                                                                       |
| **Metas/Objetivos** | Auxiliar o usuário na escolha da especialidade médica adequada com base nos sintomas descritos.                                                                                                                                           |
| **Contexto**        | Um usuário sente dores persistentes nas costas, mas não sabe qual especialidade deve procurar. Ele acessa o chatbot do aplicativo GDF Saúde, descreve seus sintomas e recebe a sugestão de procurar um ortopedista.                       |
| **Ator(es)**        | - Usuário do GDF Saúde. <br> - Chatbot embutido no aplicativo.                                                                                                                                                                            |
| **Recursos**        | - Aplicativo GDF Saúde com chatbot funcional. <br> - Base de conhecimento médica para interpretação de sintomas.                                                                                                                          |
| **Exceções**        | - O chatbot não compreende os sintomas descritos. <br> - A especialidade sugerida é inadequada.                                                                                                                                           |
| **Restrições**      | O chatbot deve limitar-se a fornecer sugestões e não diagnósticos médicos.                                                                                                                                                                |
| **Episódios**       | 1. O usuário acessa o aplicativo e abre o chatbot. <br>2. Escreve: “Estou com dores nas costas e no ombro”. <br>3. O chatbot responde: “Recomendamos procurar um ortopedista.” <br>4. O aplicativo exibe clínicas com essa especialidade. |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### Cenário 22: Interface Intuitiva e Acessível  

**Requisito Associado:** [RNF01.1](../../../elicitacao/requisitos_finais/#RNF01.1)  

<p align="center">Tabela 24 - Cenário 22 </p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE22">CE22</a> |
| **Título** | Responsividade da Interface em Diferentes Dispositivos |
| **Metas/Objetivos** | Garantir que o layout do aplicativo se adapte e funcione corretamente em dispositivos com sistemas operacionais específicos (Android 5.0+ e iOS 13.0+), proporcionando uma experiência de usuário consistente. |
| **Contexto** | Um usuário com um smartphone Samsung Galaxy S6 (Android 7.0) e outro com um iPhone 14 (iOS 16.0) acessam o aplicativo GDF Saúde. Em ambos os dispositivos, a interface se ajusta perfeitamente à tela, com todos os botões, textos e imagens sendo exibidos de forma organizada e legível. |
| **Ator(es)** | - Usuário do GDF Saúde.<br>- Interface do aplicativo. |
| **Recursos** | - Dispositivo móvel com Android 5.0 ou superior.<br>- Dispositivo móvel com iOS 13.0 ou superior. |
| **Exceções** | - O layout apresenta elementos sobrepostos ou cortados em um dispositivo com Android 5.0.<br>- Uma funcionalidade específica não é renderizada corretamente em um iPhone com iOS 13.0. |
| **Restrições** | A interface deve manter sua funcionalidade e integridade visual em todas as versões de tela e sistemas operacionais a partir do Android 5.0 e iOS 13.0. |
| **Episódios** | 1. O usuário abre o aplicativo em um dispositivo com Android 6.0.<br>2. Verifica que a tela inicial, menus e botões estão corretamente dimensionados.<br>3. Um segundo usuário abre o app em um iPhone com iOS 15.<br>4. Confirma que a experiência visual e funcional é igualmente coesa, sem distorções. |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---


### Cenário 23: Carregamento Rápido e Fluido das Telas

**Requisito Associado:** [RNF02.1](../../../elicitacao/requisitos_finais/#RNF02.1)  

<p align="center">Tabela 25 - Cenário 23 </p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE23">CE23</a> |
| **Título** | Performance de Resposta Sob Carga |
| **Metas/Objetivos** | Validar que 95% das interações do usuário no aplicativo tenham um tempo de resposta inferior a 2 segundos, mesmo sob uma carga de 100 usuários simultâneos. |
| **Contexto** | Em um teste de performance, o sistema é submetido a uma carga simulada de 100 usuários realizando diferentes ações (login, busca de clínicas, consulta de carteirinha). Um usuário-teste realiza uma busca por "cardiologistas em Taguatinga" e o resultado é exibido em 1.7 segundos, mesmo com a alta demanda no servidor. |
| **Ator(es)** | - Usuário do GDF Saúde.<br>- Backend do sistema. |
| **Recursos** | - Aplicativo GDF Saúde.<br>- Ferramenta para simulação de carga (ex: JMeter, Gatling).<br>- Ambiente de servidor monitorado. |
| **Exceções** | - O tempo médio de resposta para a funcionalidade de busca ultrapassa 2 segundos durante o teste de carga.<br>- Mais de 5% das requisições totais no teste apresentam falha ou tempo de resposta superior ao limite estabelecido. |
| **Restrições** | O critério de aceite para a performance é que 95% das transações devem ser concluídas em até 2 segundos quando o sistema estiver sob uma carga de 100 usuários simultâneos. |
| **Episódios** | 1. Um teste de carga é configurado para simular 100 usuários concorrentes.<br>2. O teste é iniciado, e os usuários virtuais começam a navegar no aplicativo.<br>3. As métricas de tempo de resposta para cada ação são coletadas.<br>4. Ao final do teste, o relatório indica que 97% das ações foram executadas abaixo de 2 segundos. |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---


### Cenário 24: Segurança e Transparência no Uso de Dados  

**Requisito Associado:** [RNF03.1](../../../elicitacao/requisitos_finais/#RNF03.1)  

<p align="center">Tabela 26 - Cenário 24 </p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE24">CE24</a> |
| **Título** | Criptografia de Dados Sensíveis em Repouso |
| **Metas/Objetivos** | Garantir que todas as informações pessoais e sensíveis dos usuários (CPF, nome, dados médicos) armazenadas nos bancos de dados do sistema estejam protegidas por criptografia. |
| **Contexto** | Um auditor de segurança realiza uma verificação no banco de dados do INAS. Ao inspecionar a tabela de usuários, ele observa que os dados nas colunas "CPF", "NomeCompleto" e "Email" não estão em texto plano, mas sim como uma cadeia de caracteres indecifrável, confirmando que a criptografia em repouso está implementada. |
| **Ator(es)** | - Administrador de Sistema / Auditor de Segurança.<br>- Sistema de Gerenciamento de Banco de Dados (SGBD). |
| **Recursos** | - Acesso autorizado ao banco de dados.<br>- Ferramentas de administração de banco de dados.<br>- Documentação do algoritmo de criptografia utilizado (ex: AES-256). |
| **Exceções** | - Durante a auditoria, um campo contendo um dado sensível (ex: número de telefone) é encontrado em texto plano.<br>- A chave de criptografia está armazenada de forma insegura, comprometendo a eficácia da proteção. |
| **Restrições** | Todos os campos identificados como sensíveis na política de dados devem ser criptografados no banco de dados. O acesso às chaves de descriptografia deve ser restrito e monitorado. |
| **Episódios** | 1. O auditor de segurança executa uma consulta no banco de dados para selecionar um registro de usuário.<br>2. A consulta retorna os dados do usuário.<br>3. O auditor analisa o resultado e confirma que os valores dos campos sensíveis estão criptografados.<br>4. O resultado da auditoria é registrado como "em conformidade". |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### Cenário 25: Disponibilidade 24/7 para autorizações de urgência/emergência  

**Requisito Associado:** [RNF04](../../../elicitacao/requisitos_finais/#RNF04)  

<p align="center">Tabela 8 - Cenário 25</p>

| Elemento         | Descrição |
|------------------|---------|
|**ID**|  <a id="CE25">CE25</a>  |
| **Título**            | Disponibilidade 24/7 para autorizações de urgência/emergência |
| **Metas/Objetivos**  | Garantir que o sistema esteja disponível continuamente (≥ 99% de uptime) para autorizar atendimentos de urgência e emergência. |
| **Contexto**         | Beneficiário chega em emergência fora do expediente e precisa autorizar procedimento pelo GDF Saúde; o sistema deve responder sem atrasos. |
| **Ator(es)**         | - Beneficiário do plano. <br>- Profissional de saúde ou recepcionista. <br>- Sistema GDF Saúde. <br>- Equipe de infraestrutura/DevOps. |
| **Recursos**         | - Infraestrutura em nuvem com alta disponibilidade. <br>- Internet no local de atendimento. <br>- Ferramentas de monitoramento de uptime e logs. |
| **Exceções**         | - Queda de serviço no GDF Saúde. <br>- Instabilidade de rede ou nuvem. <br>- Falhas em janelas críticas de manutenção. |
| **Restrições**       | Manter ≥ 99% de disponibilidade mensal; manutenções planejadas em janelas de baixo impacto. |
| **Episódios**        | 1. Paciente chega na emergência no fim de semana. <br>2. Recepcionista acessa GDF Saúde. <br>3. Sistema autoriza procedimento imediatamente. <br>4. Paciente é atendido sem atrasos. <br>5. Logs de operação e uptime são registrados. |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### Cenário 26: Compatibilidade com diferentes versões do Android e iOS  
**Requisito Associado:** [RNF05](../../../elicitacao/requisitos_finais/#RNF05)  

<p align="center">Tabela 6 - Cenário 26</p>

| Elemento         | Descrição |
|------------------|---------|
|**ID**|  <a id="CE26">CE26</a>  |
| **Título**           | Compatibilidade com diferentes versões do Android e iOS |
| **Metas/Objetivos**  | Garantir que o aplicativo funcione corretamente em dispositivos com versões variadas dos sistemas operacionais Android e iOS, atendendo a maioria dos usuários do mercado. |
| **Contexto**         | O usuário possui um smartphone com uma versão intermediária do Android (ex.: Android 10) ou do iOS (ex.: iOS 14) e precisa utilizar o aplicativo GDF Saúde com todas as funcionalidades ativas, sem falhas ou incompatibilidades. |
| **Ator(es)**         | - Usuário do aplicativo GDF Saúde com diferentes versões de sistema operacional. <br>- Equipe de desenvolvimento e testes. <br>- Lojas de aplicativos (Google Play e App Store). |
| **Recursos**         | - Dispositivos com versões variadas de Android e iOS. <br>- Ambiente de testes com emuladores e dispositivos físicos. <br>- Ferramentas de compatibilidade (ex.: Firebase Test Lab, Xcode, Android Studio). |
| **Exceções**         | - Funcionalidades específicas não disponíveis em versões antigas. <br>- Comportamentos visuais ou de navegação inconsistentes entre versões. <br>- APIs ou permissões não suportadas em versões muito antigas. |
| **Restrições**       | Suporte garantido apenas para versões oficialmente mantidas e com base de usuários significativa (ex.: Android 9+ e iOS 13+). |
| **Episódios**        | 1. Definir mínimo de versões suportadas com base em dados de mercado.<br>2. Desenvolver e testar o app nas versões selecionadas.<br>3. Usuário com Android 10 ou iOS 14 abre o app.<br>4. App inicia sem falhas.<br>5. Usuário utiliza todas as funcionalidades. |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### Cenário 27: Compatibilidade do aplicativo com leitores de tela  
**Requisito Associado:** [RNF06](../../../elicitacao/requisitos_finais/#RNF06)  

<p align="center">Tabela 7 - Cenário 27</p>

| Elemento         | Descrição |
|------------------|---------|
|**ID**|  <a id="CE27">CE27</a>  |
| **Título**           | Compatibilidade do aplicativo com leitores de tela |
| **Metas/Objetivos**  | Garantir que pessoas com deficiência visual possam utilizar o aplicativo GDF Saúde via leitores de tela, com navegação acessível, clara e funcional. |
| **Contexto**         | Usuário com deficiência visual utiliza o leitor de tela nativo (TalkBack ou VoiceOver) para consultar informações médicas no app, esperando que todos os elementos estejam corretamente rotulados e navegáveis. |
| **Ator(es)**         | - Usuário com deficiência visual. <br>- Sistema operacional (Android/iOS) com leitor de tela ativo. |
| **Recursos**         | - App GDF Saúde com rótulos de acessibilidade (contentDescription no Android, accessibilityLabel no iOS). <br>- Leitores de tela: TalkBack e VoiceOver. <br>- Dispositivo móvel compatível. |
| **Exceções**         | - Elementos sem descrição adequada. <br>- Componentes interativos não reconhecidos. <br>- Informações transmitidas apenas visualmente (cores ou ícones sem texto alternativo). |
| **Restrições**       | Seguir diretrizes de acessibilidade dos SO e evitar personalizações que comprometam a leitura automatizada. |
| **Episódios**        | 1. Usuário ativa leitor de tela. <br>2. Abre o app GDF Saúde. <br>3. Leitor de tela identifica botões, menus e textos. <br>4. Usuário navega com gestos/comandos. <br>5. Acessa agendamentos e exames sem assistência visual. |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### Cenário 28: Garantir conformidade legal e proteção de dados  
**Requisito Associado:** [RNF07](../../../elicitacao/requisitos_finais/#RNF07)  

<p align="center">Tabela 30 - Cenário 28</p>

| Elemento        | Descrição                                                                                          |
|-----------------|--------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE28">CE28</a>  |
| **Título**          | Garantir conformidade legal e proteção de dados                                                   |
| **Metas/Objetivos** | Assegurar que o sistema opere em conformidade com a Portaria nº 127/2024, legislações complementares e LGPD. |
| **Contexto**        | O sistema armazena e processa dados pessoais sensíveis de usuários, devendo respeitar normas e consentimentos legais. |
| **Ator(es)**        | - Desenvolvedor<br>- Administrador do sistema<br>- Órgãos reguladores                               |
| **Recursos**        | - Políticas de privacidade<br>- Logs de acesso<br>- Criptografia de dados<br>- Módulo de consentimento de uso |
| **Exceções**        | - Falhas de segurança detectadas<br>- Coleta de dados sem consentimento válido                      |
| **Restrições**      | - Uso restrito de dados sensíveis<br>- Validações legais obrigatórias antes de qualquer processamento |
| **Episódios**       | 1. Sistema solicita consentimento ao usuário.<br>2. Registra logs de acesso.<br>3. Criptografa dados sensíveis e monitora conformidade. |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### Cenário 29: Processar autorizações prévias dentro do prazo legal  
**Requisito Associado:** [RNF08](../../../elicitacao/requisitos_finais/#RNF08)  

<p align="center">Tabela 31 - Cenário 29</p>

| Elemento        | Descrição                                                                                   |
|-----------------|-------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE29">CE29</a>  |
| **Título**           | Processar autorizações prévias dentro do prazo legal                                       |
| **Metas/Objetivos** | Garantir que autorizações para procedimentos sejam analisadas em até 10 dias úteis.        |
| **Contexto**        | O usuário solicita uma autorização via aplicativo para um procedimento médico.             |
| **Ator(es)**        | - Usuário<br>- Sistema de Autorização<br>- Equipe de Análise Médica                         |
| **Recursos**        | - Formulário digital de solicitação<br>- Base de procedimentos<br>- Fluxo de trabalho de autorização |
| **Exceções**        | - Solicitação incompleta<br>- Falta de documentos obrigatórios                              |
| **Restrições**      | - Contagem de prazo apenas em dias úteis<br>- Anexos obrigatórios antes da análise          |
| **Episódios**       | 1. Usuário preenche solicitação.<br>2. Sistema verifica preenchimento.<br>3. Encaminha para equipe médica.<br>4. Resposta é enviada em até 10 dias úteis. |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### Cenário 30: Comunicar-se com a folha de pagamento do GDF para aplicar descontos  
**Requisito Associado:** [RNF09](../../../elicitacao/requisitos_finais/#RNF09)  

<p align="center">Tabela 32 - Cenário 30</p>

| Elemento        | Descrição                                                                                       |
|-----------------|-----------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE30">CE30</a>  |
| **Título**         | Comunicar-se com a folha de pagamento do GDF para aplicar descontos                             |
| **Metas/Objetivos** | Garantir que o valor das mensalidades seja corretamente descontado na folha de pagamento.       |
| **Contexto**        | Após cadastro do titular, o sistema envia informações à folha de pagamento do GDF.              |
| **Ator(es)**        | - Sistema do Plano de Saúde<br>- Sistema da Folha de Pagamento do GDF<br>- Usuário              |
| **Recursos**        | - API de integração com o GDF<br>- Banco de dados de contratos e valores de mensalidades         |
| **Exceções**        | - Falha na comunicação com a folha de pagamento<br>- Dados inconsistentes ou ausência de matrícula |
| **Restrições**      | - Aplicável apenas a servidores públicos do GDF com matrícula ativa e vínculo permitido         |
| **Episódios**       | 1. Conclusão do cadastro do titular.<br>2. Envio de dados à folha do GDF.<br>3. Folha confirma recebimento.<br>4. Desconto é aplicado.<br>5. Sistema registra sucesso da operação. |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### Cenário 31: Acessar carteirinha digital com no máximo dois cliques  
**Requisito Associado:** [RNF10](../../../elicitacao/requisitos_finais/#RNF10)  

<p align="center">Tabela 33 - Cenário 31</p>

| Elemento        | Descrição                                                                                                        |
|-----------------|----------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE31">CE31</a>  |
| **Título**           | Acessar carteirinha digital com no máximo dois cliques                                                          |
| **Metas/Objetivos** | Facilitar acesso rápido à carteirinha digital diretamente da tela inicial.                                       |
| **Contexto**        | Usuário autentica-se e precisa apresentar a carteirinha em atendimento.                                         |
| **Ator(es)**        | - Usuário<br>- Sistema do aplicativo                                                                              |
| **Recursos**        | - Interface com atalho na home<br>- Módulo de exibição da carteirinha integrado ao perfil                        |
| **Exceções**        | - Falha de rede impede exibição<br>- Usuário não autenticado                                                     |
| **Restrições**      | Funcionalidade acessível em no máximo dois cliques a partir da tela inicial.                                     |
| **Episódios**       | 1. Usuário abre o app.<br>2. Clica em “Carteirinha Digital”.<br>3. Carteirinha é exibida na tela.                  |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### Cenário 32: Manter histórico de notificações acessível ao usuário por no mínimo 6 meses

Este cenário está relacionado com o requisito não funcional **não implementado** [RNF11](../../../elicitacao/requisitos_finais/).

<p align="center">Tabela 34 - Cenário 32</p>

| **Elemento**         | **Descrição**                                                                                   |
|----------------------|----------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE32">CE32</a>  |
| **Título**           | Acesso ao Histórico de Notificações                                                            |
| **Metas/Objetivos**  | Permitir que o usuário visualize notificações recebidas nos últimos 6 meses.                   |
| **Contexto**         | O usuário está logado no sistema INAS e deseja consultar notificações anteriores.              |
| **Ator(es)**        | Usuário (beneficiário).                                                                         |
| **Recursos**         | Sistema INAS, banco de dados de notificações.                                                  |
| **Exceções**         | Notificações indisponíveis devido a falhas técnicas ou expiradas após 6 meses.                 |
| **Episódios**       | 1. O usuário acessa a seção "Notificações" no sistema.<br>2. O sistema exibe uma lista de notificações dos últimos 6 meses.<br>3. O usuário pode filtrar ou buscar notificações específicas.<br>4. Notificações fora do período de 6 meses não são exibidas. |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a></p>

---

### Cenário 33: Suporte ao Usuário via Chat ou Telefone

Este cenário está relacionado com o requisito não funcional **implementado** [RNF12](../../../elicitacao/requisitos_finais/).

<p align="center">Tabela 35 - Cenário 33</p>

| **Elemento**         | **Descrição**                                                                                      |
|----------------------|---------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE33">CE33</a>  |
| **Título**          | Suporte ao Usuário via Chat ou Telefone   |
| **Metas/Objetivos**  | Fornecer assistência ao usuário para resolver dúvidas ou problemas.                               |
| **Contexto**         | O usuário está utilizando o sistema e precisa de ajuda.                                           |
| **Ator(es)**        | Usuário (beneficiário), Agente de Suporte.                                                        |
| **Recursos**         | Sistema INAS, canal de chat ou telefone.                                                          |
| **Exceções**         | Canal de suporte indisponível ou tempo de espera excessivo.                                       |
| **Episódios**       | 1. O usuário acessa a seção "Outros" no sistema.<br>2. O usuário seleciona a opção "Ajuda e ouvidoria".<br>3. Escolhe a opção "Central de relacionamento 24h".<br>4. Para telefone: liga para o número fornecido e fala com um agente. |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a></p>

---


### Cenário 34: Funcionar de forma offline para acesso à carteirinha e histórico de consultas  
**Requisito Associado:** [RNF13](../../../elicitacao/requisitos_finais/#RNF13)  

<p align="center">Tabela 36 - Cenário 34</p>

| Elemento        | Descrição                                                                                                                          |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE34">CE34</a>  |
| **Título**           | Funcionar de forma offline para acesso à carteirinha e histórico de consultas                                                      |
| **Metas/Objetivos** | Garantir que a carteirinha e o histórico de consultas estejam disponíveis mesmo sem conexão à internet.                            |
| **Contexto**        | Usuário está em local sem cobertura e precisa consultar carteirinha ou histórico de atendimentos médicos.                          |
| **Ator(es)**        | - Usuário do GDF Saúde<br>- Sistema de sincronização offline                                                                         |
| **Recursos**        | - Armazenamento local de dados sincronizados previamente<br>- Interface dedicada ao modo offline                                     |
| **Exceções**        | - Dados não sincronizados previamente (não disponíveis offline)                                                                     |
| **Restrições**      | - Apenas carteirinha e histórico de consultas ficam disponíveis offline<br>- Dados devem ser armazenados de forma segura e criptografada |
| **Episódios**       | 1. Usuário habilita GovBR e autentica offline.<br>2. Abre o app sem conexão.<br>3. Interface reduzida exibe carteirinha e histórico sincronizados. |

<p align="center">Fonte: Adaptado de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### Cenário 35: Apresentar clínicas novas e próximas da localização do usuário  
**Requisito Associado:** [RNF14](../../../elicitacao/requisitos_finais/#RNF14)  

<p align="center">Tabela 37 - Cenário 35</p>

| Elemento        | Descrição                                                                                                                                           |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE35">CE35</a>  |
| **Título**          | Apresentar clínicas novas e próximas da localização do usuário                                                                                     |
| **Metas/Objetivos** | Permitir que o usuário descubra facilmente novas clínicas cadastradas e clínicas próximas com base em sua localização atual.                        |
| **Contexto**        | Usuário abre o app com GPS ativado; o sistema identifica a localização e lista clínicas próximas, destacando novas unidades cadastradas.             |
| **Ator(es)**        | - Usuário do GDF Saúde<br>- Sistema de geolocalização do dispositivo<br>- Servidores de GDF Saúde responsáveis pela gestão de clínicas               |
| **Recursos**        | - Acesso à localização do dispositivo<br>- Banco de dados de clínicas e coordenadas geográficas<br>- Interface de listagem e mapa                   |
| **Exceções**        | - Permissão de localização negada<br>- GPS desativado<br>- Falha de acesso ao banco de dados remoto                                                |
| **Restrições**      | - Depende de permissão de geolocalização<br>- Lista deve ser atualizada periodicamente e exibida de forma clara e acessível                         |
| **Episódios**       | 1. Usuário abre o app com GPS ativo.<br>2. Sistema solicita permissão (se necessário).<br>3. Exibe lista de clínicas próximas e novas unidades.      |

<p align="center">Fonte: Adaptado de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### Cenário 36: Exigir autenticação via GovBR para login  
**Requisito Associado:** [RNF15](../../../elicitacao/requisitos_finais/#RNF15)  

<p align="center">Tabela 38 - Cenário 36</p>

| Elemento        | Descrição                                                                                                                                                                   |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE36">CE36</a>  |
| **Título**          | Autenticação segura via GovBR |
| **Metas/Objetivos** | Garantir acesso seguro ao sistema, exigindo autenticação pelo GovBR com nível de segurança adequado. |
| **Contexto**        | Usuário tenta fazer login no app GDF Saúde e é redirecionado à plataforma GovBR para validar sua identidade e credenciais (certificado digital ou conta gov.br). |
| **Ator(es)**        | - Usuário do GDF Saúde<br>- Plataforma GovBR<br>- Servidores do INAS responsáveis pela integração |
| **Recursos**        | - App GDF Saúde integrado ao GovBR<br>- Certificado digital ou conta gov.br válida<br>- Protocolo OAuth/OpenID Connect para autenticação |
| **Exceções**        | - Plataforma GovBR indisponível<br>- Usuário sem conta GovBR<br>- Falha na comunicação entre app e GovBR |
| **Restrições**      | - Acesso só é permitido após autenticação bem-sucedida na GovBR<br>- Dados sensíveis devem ser transmitidos e armazenados com criptografia ponta a ponta                     |
| **Episódios**       | 1. Usuário seleciona “Entrar com GovBR”.<br>2. Redirecionamento para GovBR e inserção de credenciais.<br>3. GovBR valida e retorna ao app.<br>4. App concede acesso ao usuário. |

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

---

### Cenário 37: Exibir informações claras, completas e atualizadas em tempo real  
**Requisito Associado:** [RNF16](../../../elicitacao/requisitos_finais/#RNF16)  

<p align="center">Tabela 39 - Cenário 37</p>

| Elemento        | Descrição                                                                                                                                                                                                      |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE37">CE37</a>  |
| **Título**           | Exibição de informações claras, completas e atualizadas em tempo real | 
| **Metas/Objetivos** | Garantir que dados exibidos (ex.: resultados de exames, histórico de guias) sejam precisos, contextualizados e sincronizados instantaneamente com fontes oficiais.                                            |
| **Contexto**        | Usuário acessa seção “Resultados de Exames” ou “Histórico de Saúde” e espera ver data/hora da última atualização, com indicadores visuais de status (síncro OK, pendente, erro).                               |
| **Ator(es)**        | - Usuário do GDF Saúde<br>- Sistemas de backend do INAS (bases governamentais)<br>- Equipe de gestão de dados |
| **Recursos**        | - API de integração em tempo real<br>- Ferramentas de validação e sanitização<br>- Componentes visuais (selos de atualização, ícones de status)<br>- Notificações push para mudanças críticas |
| **Exceções**        | - Falha na conexão impede atualização<br>- Dados incompletos ou inconsistentes<br>- Componentes visuais não carregam corretamente                                             |
| **Restrições**      | - Todas as informações devem ser validadas antes da exibição<br>- Atualizações automáticas com intervalo máximo de 5 minutos                                        |
| **Episódios**       | 1. Usuário abre seção de dados.<br>2. Sistema consulta API e valida timestamp.<br>3. Exibe selo “Atualizado em [horário]” e ícones de status.<br>4. Push notifica se há nova versão. |

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>


---



## Referência Bibliográfica

SERRANO, Milene; SERRANO, Maurício. *Requisitos - Aula 10*. Disponível em: [https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf). Acesso em: 17 maio 2025.

> Observação: O PDF dos slides utilizados como referência pode ser acessado [clicando aqui](../../assets/Requisitos-Aula-10.pdf)

## Histórico de Versões

| Versão | Data       | Descrição                                                                                                     | Autor(es)                                                                                           | Revisor(es)                                                                                      |
|--------|------------|---------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| `1.0`  | 16/05/2025 | Criação do esboço do documento, com a introdução                                                                                         | [Isaque Camargos](https://github.com/isaqzin)                                                       | [Yzabella Miranda](https://github.com/redjsun)                                                  |
| `1.1`  | 16/05/2025 | Criou a metodologia e a tabela referência utilizada por todos os integrantes posteriormente                                                                      | [Matheus de Alcântara](https://github.com/matheusdealcantara)                                      | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC)                                                   |
| `1.2`  | 16/05/2025 | Correção de bug na tabela 1                                                                                   | [Yzabella Miranda](https://github.com/redjsun)                                                      | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC)                                             |
| `1.3`  | 16/05/2025 | Adição dos cenários 1, 2 e 21, 22, 23 e 24                                                  | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC)                                                 | [Yzabella Miranda](https://github.com/redjsun)                                                  |
| `1.4`  | 16/05/2025 | Adição dos cenários 3, 4, 19, 25 e 26                                                             | [Isaque Camargos](https://github.com/isaqzin)                                                       | [Yzabella Miranda](https://github.com/redjsun)                                                  |
| `1.5`  | 17/05/2025 | Adição dos cenários 13, 14, 15, 35 e 36                                                                       | [Yzabella Miranda](https://github.com/redjsun)                                                      |  [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) |
| `1.6`  | 17/05/2025 | Adição dos cenários 11, 12, 33 e 34                                                                           | [Othavio Bolzan](https://github.com/bolzanMGB)                                                      | [Yzabella Miranda](https://github.com/redjsun)                                                  |
| `1.7`  | 17/05/2025 | Adição dos cenários 5, 6, 17, 27 e 28                                                                         | [Kaleb Macedo](https://github.com/kalebmacedo)                                                      | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC)                                             |
| `1.8`  | 17/05/2025| Adição dos cenários 7, 8, 16, 18, 29 e 30                                                                     | [Lucas Alves](https://github.com/LucasAlves71)                                                      | [Yzabella Miranda](https://github.com/redjsun)                                                  |
| `1.9`  | 16/05/2025 | Adição dos cenários 9, 10, 20, 31 e 32                                                                        | [Matheus de Alcântara](https://github.com/matheusdealcantara)                                      | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC)                                                   |
| `2.0`  | 17/05/2025 | Consolidação final do documento: organização e união de todos os cenários entregues pelos integrantes         | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC)                                                 | [Yzabella Miranda](https://github.com/redjsun) e [Matheus de Alcântara](https://github.com/matheusdealcantara)                                                  |
|`2.1`  | 08/06/2025  | Adição de ancoras | [Isaque Camargos](https://github.com/isaqzin) | [Lucas Alves](https://github.com/LucasAlves71) |
|`2.2`  | 11/06/2025  | Corrigindo âncoras e metodologia para uma melhor rastreabilidade e identificação dos cenários. Além disso, foi refatorado os cenários qeu foram alocados para mim, uma vez que houve o refinamento dos requisitos | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) | [Matheus de Alcântara](https://github.com/matheusdealcantara) |
