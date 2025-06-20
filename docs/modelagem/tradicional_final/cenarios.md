# Cenário

## Introdução 

Este documento apresenta uma coleção detalhada de cenários de uso, projetados para dar vida aos requisitos do aplicativo GDF Saúde. Cada cenário descreve uma jornada específica do usuário, ilustrando como as funcionalidades serão utilizadas em situações práticas e cotidianas. A construção destes cenários foi fundamentada afim de compreendermos os  **requisitos funcionais** e como eles irão interagir com o usuário.

Para cada cenário, são detalhados os **Atores** envolvidos, os **Recursos** necessários, as possíveis **Exceções** que podem ocorrer e as **Restrições** que devem ser observadas. Ao final, os **Episódios** narram o passo a passo da interação. O objetivo é fornecer uma visão clara e inequívoca do comportamento esperado do sistema, servindo como uma ferramenta essencial para as equipes de desenvolvimento, testes e validação.

É importante notar que esses cenários foram **refatorados** para maior clareza e precisão, além de corresponderem com os requisitos finais que foram refinados. Você pode acessar a versão antiga clicando [aqui](../../metodos_tradicionais/cenarios).

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
                <td>Criou os cenários  referentes aos requisitos: RF01.1, RF01.2, RF01.3, RF01.4, RF01.5, RF02.1, RF02.2, RF02.3 e RF21. Além disso, consolidou o documento final ao pegar os cenários separados, que se encontravam na plataforma <a href="https://stackedit.io/app#">StackEdit</a> e organizar no documento final para o Github Pages. Além disso refatorou os cenários para fazerem sentido para os novos requisitos finais e arrumou a rastreabilidade de todos os requisitos do antigo para o novo</td>
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
                <td>Desenvolveu a metodologia e criou os cenários referente aos requisitos RF09.1, RF09.2, RF09.3, RF09.4, RF10 e RF20</td>
            </tr>
            <tr>
                <td><a href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a></td>
                <td>Criou os cenários  referentes aos requisitos:: RF11, RF12.1, RF12.2, RF12.3, RF12.4, RF12.5 e RF12.</td>
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

### Cenário 2: Avaliação de Atendimento com escala de 1 a 5 
**Requisito Associado:** [RF02.1](../../../elicitacao/requisitos_finais/#RF02.1)  

<p align="center">Tabela 4 - Cenário 2 </p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** |  <a id="CE02">CE02</a>  |
| **Título** | Avaliação de Atendimento com escala de 1 a 5 |
| **Metas/Objetivos** | Permitir que o usuário avalie a qualidade de um atendimento específico utilizando uma escala Likert de 1 a 5, oferecendo um feedback mais detalhado sobre sua satisfação. |
| **Contexto** | Após uma consulta de rotina, um usuário acessa o aplicativo GDF Saúde para registrar sua experiência. Ele seleciona a opção "4 - Satisfeito" na escala de avaliação e deixa um comentário elogiando a pontualidade do atendimento. |
| **Ator(es)** | - Usuário do GDF Saúde.<br>- Sistema de avaliação do aplicativo. |
| **Recursos** | - Aplicativo GDF Saúde.<br>- Histórico de atendimentos do usuário.<br>- Interface de avaliação com escala Likert de 0 a 5 (onde 0 é "Muito Insatisfeito" e 5 é "Muito Satisfeito") e campo para comentários. |
| **Exceções** | - O sistema apresenta um erro e não consegue registrar a avaliação enviada.<br>- O usuário tenta avaliar um atendimento que ainda não foi concluído. |
| **Restrições** | - O sistema deve permitir apenas uma avaliação por atendimento realizado.<br>- A interface deve exibir claramente o significado de cada nível da escala Likert para orientar o usuário.<br>- O sistema deve possuir um mecanismo para moderar ou filtrar comentários com linguagem inadequada. |
| **Episódios** | 1. O usuário acessa a seção "Histórico de Atendimentos" no aplicativo.<br>2. Localiza e seleciona a consulta que deseja avaliar.<br>3. Clica na opção “Avaliar Atendimento”.<br>4. O sistema exibe a escala de avaliação de 1 a 5.<br>5. O usuário seleciona a nota "4 - Satisfeito".<br>6. Opcionalmente, o usuário escreve um comentário no campo de texto.<br>7. A avaliação é registrada e associada àquele atendimento específico. |


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
### Cenário x: Configuração de preferências de notificação pelo usuário  
**Requisito Associado:** [RF04.1](../../elicitacao/requisitos_finais.md#RF04.1)  e [RF04.9](../../elicitacao/requisitos_finais.md#RF04.9)

<p align="center">Tabela x - Cenário x</p>

| Elemento        | Descrição|
|-----------------|--------------------------------------------------------|
| **ID**|  <a id="CE05">CE05</a>|
| **Título**| Configuração de preferências de notificação pelo usuário|
| **Metas/Objetivos** | Permitir que o usuário escolha quais tipos de eventos deseja ser notificado (ex.: vencimento de fatura, demonstrativo IR) e por quais canais (app, SMS, e-mail).|
| **Contexto**| O usuário acessa o app GDF Saúde, entra nas configurações e define os eventos e canais pelos quais deseja ser notificado. As preferências ficam salvas no sistema.            |
| **Ator(es)**| - Usuário (titular ou dependente).<br>- Sistema de notificações do GDF Saúde.|
| **Recursos**| - App móvel GDF Saúde.<br>- Dispositivo do usuário.<br>- Conexão com internet.<br>- Interface de configuração de notificações.|
| **Exceções**        | - Falha na conexão durante salvamento.<br>- Falha de autenticação do usuário.<br>- Erro de permissão no dispositivo (notificações desativadas).|
| **Restrições**      | É necessário estar autenticado e com conexão ativa.|
| **Episódios**       | 1. Usuário faz login no app.<br>2. Acessa “Outros → Configurações → Notificações”.<br>3. Escolhe eventos (ex.: fatura, IR) e canais (app, SMS, e-mail).<br>4. Sistema salva preferências. |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### Cenário X: Envio de notificação sobre demonstrativo de IR e vencimento de fatura  
**Requisito Associado:** [RF04.1](../../elicitacao/requisitos_finais.md#RF04.1)  e [RF04.9](../../elicitacao/requisitos_finais.md#RF04.9)

<p align="center">Tabela X - Cenário X</p>

| Elemento        | Descrição|
|-----------------|----------------------------------------------------|
| **ID**          |  <a id="CE06">CE06</a>|
| **Título**      | Envio de notificação sobre demonstrativo de IR e vencimento de fatura|
| **Metas/Objetivos** | Informar o usuário sobre a disponibilidade do demonstrativo do Imposto de Renda e o vencimento de sua fatura de forma automática.|
| **Contexto**| Após o sistema identificar que um demonstrativo está disponível ou uma fatura está prestes a vencer, ele envia uma notificação usando os canais configurados pelo usuário.|
| **Ator(es)**| - Sistema de notificações do GDF Saúde.<br>- Usuário (titular ou dependente).<br>- Provedores externos de SMS e e‑mail.|
| **Recursos**| - Preferências de notificação já configuradas.<br>- Servidor de eventos (ex.: gerador de alertas de IR/fatura).<br>- Internet.<br>- APIs de envio de SMS, e-mail e push.|
| **Exceções**| - Configurações ausentes ou inválidas.<br>- Falha no envio por canal externo.<br>- Caixa de e-mail cheia ou número de celular inválido.|
| **Restrições**| Envio condicionado às preferências do usuário e à disponibilidade do provedor.|
| **Episódios**| 1. Sistema detecta a liberação do demonstrativo de IR e o vencimento próximo da fatura.<br>2. Consulta preferências do usuário.<br>3. Envia notificações pelos canais definidos.<br>4. Usuário recebe alerta e visualiza conteúdo. |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

## Cenário x: Agendar Consulta Médica pelo AplicativoAdd commentMore actions

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

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Cenário x: Cancelar um Agendamento de Consulta

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

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Cenário x: Verificar Preço de Consulta Antes de Agendar

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

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Cenário x: Simular Custo de Coparticipação

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

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Cenário x: Emitir Demonstrativo para Imposto de Renda

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

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Cenário x: Acessar Demonstrativos de Anos Anteriores

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

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Cenário x: Conferir Despesas no Extrato Financeiro

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

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Cenário x: Acompanhar Metas de Saúde Preventiva

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

### Cenário 9: Visualizar Histórico de Consultas Realizadas

<p align="center">Tabela 11 - Cenário 9</p>

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

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a></p>

---

### Cenário X: Visualizar Histórico de Exames Realizados

<p align="center">Tabela X - Cenário X</p>

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

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a></p>

---

### Cenário X: Visualizar Resultados de Exames Laboratoriais

<p align="center">Tabela X - Cenário X</p>

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

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a></p>

---

### Cenário X: Visualizar Histórico de Coparticipações

<p align="center">Tabela X - Cenário X</p>

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

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>


---

### Cenário 12 – Apresentar uma Seção no Menu Principal Chamada "Novidades"
**Requisito Associado:** [RF12.1](../../../elicitacao/requisitos_finais/#RF12.1)  

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | CE12.1 |
| **Título**      | Apresentar uma seção no menu principal chamada "Novidades" |
| **Metas/Objetivos** | Facilitar o acesso dos usuários às informações recentes do app por meio de uma entrada dedicada no menu. |
| **Contexto**    | O app é aberto e apresenta no menu principal uma nova seção intitulada “Novidades”. |
| **Ator(es)**    | - Usuário do GDF Saúde <br> - Sistema de menu e interface |
| **Recursos**    | - App GDF Saúde <br> - Módulo de navegação e layout |
| **Exceções**    | - Erro na exibição da seção <br> - Menu não atualizado |
| **Restrições**  | A seção deve ser visível sem ações adicionais por parte do usuário. |
| **Episódios**   | 1. Usuário abre o app <br> 2. Menu principal é carregado <br> 3. Seção “Novidades” está visível |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### Cenário 13 – Exibir Lista de Funcionalidades com Título, Descrição e Data
**Requisito Associado:** [RF12.2](../../../elicitacao/requisitos_finais/#RF12.2)  

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | CE12.2 |
| **Título**      | Exibir lista de funcionalidades com título, descrição e data de lançamento |
| **Metas/Objetivos** | Permitir que o usuário se informe sobre as funcionalidades lançadas recentemente. |
| **Contexto**    | Ao acessar a seção “Novidades”, o usuário visualiza uma lista de funcionalidades lançadas. |
| **Ator(es)**    | - Usuário do GDF Saúde <br> - Sistema de exibição de novidades |
| **Recursos**    | - App GDF Saúde <br> - Banco de dados de funcionalidades |
| **Exceções**    | - Falha ao carregar a lista <br> - Lista vazia |
| **Restrições**  | Os dados devem ser exibidos de forma legível e organizada |
| **Episódios**   | 1. Usuário acessa seção “Novidades” <br> 2. Lista de funcionalidades é exibida com título, descrição e data |


<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### Cenário 14 – Destacar Funcionalidades com Marcador "Novo"
**Requisito Associado:** [RF12.3](../../../elicitacao/requisitos_finais/#RF12.3)  

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | CE12.3 |
| **Título**      | Destacar funcionalidades novas com marcador "Novo" |
| **Metas/Objetivos** | Ajudar o usuário a identificar rapidamente o que foi recentemente lançado. |
| **Contexto**    | Na lista de novidades, as funcionalidades lançadas recentemente exibem um marcador "Novo". |
| **Ator(es)**    | - Usuário do GDF Saúde <br> - Sistema de exibição de marcadores |
| **Recursos**    | - App GDF Saúde <br> - Banco de dados de lançamento |
| **Exceções**    | - Data de lançamento incorreta <br> - Marcador não exibido corretamente |
| **Restrições**  | Marcador deve ser exibido apenas por um período configurável (ex: 7 dias) |
| **Episódios**   | 1. Usuário abre a seção “Novidades” <br> 2. Funcionalidades lançadas nos últimos 7 dias exibem o marcador "Novo" |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### Cenário 15 – Exibir Pop-ups Informativos com as Principais Novidades
**Requisito Associado:** [RF12.4](../../../elicitacao/requisitos_finais/#RF12.4)  

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | CE12.4 |
| **Título**      | Exibir pop-ups informativos com as principais novidades após atualização |
| **Metas/Objetivos** | Informar imediatamente o usuário sobre novas funcionalidades após atualização do app. |
| **Contexto**    | Ao abrir o app após uma atualização, um pop-up apresenta um resumo das novidades. |
| **Ator(es)**    | - Usuário do GDF Saúde <br> - Sistema de notificações e controle de versão |
| **Recursos**    | - App GDF Saúde <br> - Sistema de notificações e changelog |
| **Exceções**    | - Pop-up não aparece <br> - Usuário ignora o conteúdo |
| **Restrições**  | Pop-up exibido uma única vez por funcionalidade |
| **Episódios**   | 1. App é atualizado <br> 2. Usuário abre o app <br> 3. Pop-up com novidades é exibido |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

## Cenário 16 – Ver Descrição Detalhada ao Tocar na Funcionalidade
**Requisito Associado:** [RF12.5](../../../elicitacao/requisitos_finais/#RF12.5)  


| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | CE12.5 |
| **Título**      | Permitir que o usuário toque em uma funcionalidade para ver detalhes |
| **Metas/Objetivos** | Fornecer informações completas sobre as funcionalidades listadas. |
| **Contexto**    | O usuário toca em uma funcionalidade na seção de novidades e acessa a descrição detalhada. |
| **Ator(es)**    | - Usuário do GDF Saúde <br> - Sistema de navegação |
| **Recursos**    | - App GDF Saúde <br> - Banco de dados de funcionalidades |
| **Exceções**    | - Erro ao carregar os detalhes |
| **Restrições**  | Funcionalidade precisa estar presente na lista |
| **Episódios**   | 1. Usuário acessa a seção de novidades <br> 2. Toca em uma funcionalidade <br> 3. Sistema exibe detalhes |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### Cenário 17: Ordenar Novidades por Mais Recente ou Mais Antigo  
**Requisito Associado:** [RF12.6](../../../elicitacao/requisitos_finais/#RF12.6)  

<p align="center">Tabela x - Cenário x</p>

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | CE12.6 |
| **Título**      | Permitir ordenação das novidades por "mais recente" e "mais antigo" |
| **Metas/Objetivos** | Facilitar a navegação do usuário entre diferentes novidades conforme sua preferência. |
| **Contexto**    | O usuário acessa a lista de novidades e escolhe como deseja ordenar os itens. |
| **Ator(es)**    | - Usuário do GDF Saúde <br> - Sistema de exibição de lista |
| **Recursos**    | - App GDF Saúde <br> - Banco de dados de funcionalidades |
| **Exceções**    | - Ordenação não funciona corretamente |
| **Restrições**  | Lista deve ser reordenada imediatamente após seleção |
| **Episódios**   | 1. Usuário acessa lista de novidades <br> 2. Seleciona ordenação <br> 3. Lista é reorganizada |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

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

### Cenário 38: Pesquisa de Profissionais da Saúde

**Requisito Associado:** [RF01.2](../../../elicitacao/requisitos_finais/#RF01.2) - O usuário poderá pesquisar profissionais da saúde (médicos, psicólogos etc.) por meio de filtros de busca.

<p align="center">Tabela 40 - Cenário 38</p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE38">CE38</a> |
| **Título** | Pesquisa de Profissionais da Saúde por Categoria |
| **Metas/Objetivos** | Permitir que o usuário encontre um profissional de saúde (médico, psicólogo, etc.) utilizando um filtro específico de categoria profissional. |
| **Contexto** | Um beneficiário precisa de acompanhamento psicológico e utiliza o aplicativo para encontrar uma lista de todos os psicólogos credenciados na rede GDF Saúde. |
| **Ator(es)** | - Usuário do GDF Saúde<br>- Sistema de busca do aplicativo |
| **Recursos** | - Interface com filtros de pesquisa<br>- Banco de dados de profissionais categorizados |
| **Exceções** | - A busca por uma categoria específica não retorna nenhum profissional.<br>- O profissional listado não atende mais pela rede credenciada. |
| **Restrições** | - A lista de profissionais e suas categorias deve ser mantida atualizada pelo INAS. |
| **Episódios** | 1. O usuário acessa a funcionalidade de busca da rede credenciada.<br>2. Seleciona o filtro "Tipo de Profissional".<br>3. Escolhe a opção "Psicólogo" na lista.<br>4. O sistema exibe uma lista com todos os psicólogos disponíveis. |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC" target="_blank">Ana Luiza Soares</a></p>

---

### Cenário 39: Combinação de Filtros de Pesquisa

**Requisito Associado:** [RF01.3](../../../elicitacao/requisitos_finais/#RF01.3) - Será possível combinar filtros de pesquisa (por ex. “região administrativa + especialidade”).

<p align="center">Tabela 41 - Cenário 39</p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE39">CE39</a> |
| **Título** | Refinamento da Busca com Filtros Combinados |
| **Metas/Objetivos** | Permitir que o usuário refine os resultados da busca aplicando múltiplos filtros de forma simultânea para encontrar um atendimento altamente específico. |
| **Contexto** | Um usuário precisa agendar uma consulta com um cardiologista que atenda na Asa Sul. Para otimizar sua busca, ele aplica os filtros "Especialidade" e "Região Administrativa" ao mesmo tempo. |
| **Ator(es)** | - Usuário do GDF Saúde<br>- Sistema de busca do aplicativo |
| **Recursos** | - Interface de busca que permite a seleção de múltiplos filtros.<br>- Backend capaz de processar consultas com lógica "E" (AND). |
| **Exceções** | - A combinação de filtros resulta em uma lista vazia, sem nenhuma correspondência.<br>- O sistema interpreta a busca com a lógica "OU" (OR) em vez de "E", retornando resultados imprecisos. |
| **Restrições** | - O sistema deve aplicar uma lógica "E" (AND) para todos os filtros selecionados, garantindo que todos os critérios sejam atendidos simultaneamente. |
| **Episódios** | 1. O usuário seleciona o filtro "Especialidade: Cardiologia".<br>2. Sem limpar o primeiro filtro, ele adiciona "Região Administrativa: Asa Sul".<br>3. O sistema processa a busca combinada.<br>4. A tela de resultados exibe apenas os cardiologistas que atendem na Asa Sul. |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC" target="_blank">Ana Luiza Soares</a></p>

---

### Cenário 40: Busca por Proximidade

**Requisito Associado:** [RF01.4](../../../elicitacao/requisitos_finais/#RF01.4) - O filtro de pesquisa deve permitir buscas por proximidade do usuário (distância em até 10 km).

<p align="center">Tabela 42 - Cenário 40</p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE40">CE40</a> |
| **Título** | Localização de Atendimento por Proximidade |
| **Metas/Objetivos** | Facilitar a vida do usuário permitindo que ele encontre opções de atendimento próximas à sua localização atual, dentro de um raio de 10 km. |
| **Contexto** | Um usuário está em seu local de trabalho e precisa de atendimento odontológico com urgência. Ele utiliza a função "Buscar Perto de Mim" para ver as clínicas mais próximas. |
| **Ator(es)** | - Usuário do GDF Saúde<br>- Sistema de busca e geolocalização |
| **Recursos** | - GPS do dispositivo móvel do usuário.<br>- API de geolocalização (ex: Google Maps).<br>- Banco de dados com as coordenadas geográficas das clínicas. |
| **Exceções** | - O usuário não concede a permissão de acesso à localização.<br>- O GPS do dispositivo está desativado ou com baixa precisão.<br>- Nenhuma clínica é encontrada no raio de 10 km. |
| **Restrições** | - A funcionalidade requer permissão explícita do usuário para acessar a localização do dispositivo.<br>- A busca é estritamente limitada a um raio de 10 km da posição atual do usuário. |
| **Episódios** | 1. O usuário toca no ícone de busca por proximidade.<br>2. O aplicativo solicita e obtém permissão para usar o GPS.<br>3. O sistema captura as coordenadas atuais e busca no banco de dados.<br>4. Uma lista de clínicas é exibida, ordenada da mais próxima para a mais distante (até 10 km). |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC" target="_blank">Ana Luiza Soares</a></p>

---

### Cenário 41: Busca por Especialidade Médica

**Requisito Associado:** [RF01.5](../../../elicitacao/requisitos_finais/#RF01.5) - O Filtro permite busca pela especialidade médica.

<p align="center">Tabela 43 - Cenário 41</p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE41">CE41</a> |
| **Título** | Filtro por Especialidade Médica |
| **Metas/Objetivos** | Permitir que o usuário encontre facilmente profissionais e clínicas que ofereçam uma determinada especialidade médica. |
| **Contexto** | Um usuário precisa encontrar um ortopedista para tratar uma lesão no joelho. Ele acessa o aplicativo e utiliza o filtro de especialidades para listar todas as opções disponíveis. |
| **Ator(es)** | - Usuário do GDF Saúde<br>- Sistema de busca do aplicativo |
| **Recursos** | - Interface com campo de busca ou lista de seleção de especialidades.<br>- Banco de dados de profissionais e suas respectivas especialidades. |
| **Exceções** | - O usuário digita o nome de uma especialidade com erro e o sistema não oferece sugestões.<br>- Não existem profissionais da especialidade buscada na rede credenciada. |
| **Restrições** | - A lista de especialidades deve ser padronizada e de fácil compreensão para o usuário leigo. |
| **Episódios** | 1. O usuário vai até a área de busca da rede.<br>2. Clica no filtro "Especialidade".<br>3. Digita ou seleciona "Ortopedia" na lista.<br>4. O sistema retorna todos os ortopedistas e clínicas com essa especialidade. |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC" target="_blank">Ana Luiza Soares</a></p>

---

### Cenário 42: Leitura e Publicação de Comentários

**Requisito Associado:** [RF02.2](../../../elicitacao/requisitos_finais/#RF02.2) - O usuário poderá deixar e/ou ler comentários sobre atendimentos em clínicas ou com profissionais específicos.

<p align="center">Tabela 44 - Cenário 42</p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE42">CE42</a> |
| **Título** | Interação com Comentários de Atendimentos |
| **Metas/Objetivos** | Criar uma comunidade de feedback, permitindo que usuários leiam avaliações de outros e publiquem suas próprias experiências para ajudar na tomada de decisão. |
| **Contexto** | Antes de marcar uma consulta com um novo pediatra para seu filho, uma usuária acessa o perfil do profissional no aplicativo para ler os comentários deixados por outros pais. |
| **Ator(es)** | - Usuário do GDF Saúde<br>- Sistema de avaliação e comentários |
| **Recursos** | - Seção de comentários no perfil de clínicas e profissionais.<br>- Formulário para submissão de texto. |
| **Exceções** | - A seção de comentários não carrega por um erro de conexão.<br>- O comentário enviado pelo usuário viola os termos de uso e é bloqueado. |
| **Restrições** | - Apenas usuários que tiveram um atendimento confirmado podem publicar um comentário.<br>- Os comentários devem passar por um filtro de moderação de conteúdo. |
| **Episódios** | 1. Uma usuária busca por um pediatra e seleciona um perfil.<br>2. Navega até a seção de avaliações e lê os comentários existentes.<br>3. Após sua própria consulta, ela retorna ao perfil e clica em "Deixar um comentário".<br>4. Escreve sua avaliação e a submete para publicação. |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC" target="_blank">Ana Luiza Soares</a></p>

---

### Cenário 43: Classificação de Relevância dos Comentários

**Requisito Associado:** [RF02.3](../../../elicitacao/requisitos_finais/#RF02.2) - O sistema classificará comentários como “relevantes” ou “não relevantes” automaticamente com base em palavras-chave e upvotes de outros usuários.

<p align="center">Tabela 45 - Cenário 43</p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE43">CE43</a> |
| **Título** | Destaque de Comentários Relevantes |
| **Metas/Objetivos** | Melhorar a experiência do usuário, destacando automaticamente os comentários mais úteis e informativos com base em seu conteúdo e na percepção de outros usuários. |
| **Contexto** | Ao ler as avaliações de um hospital, um usuário nota que os comentários no topo da lista são mais detalhados, mencionam aspectos como "tempo de espera" e "qualidade do atendimento", e possuem um selo de "Relevante". |
| **Ator(es)** | - Usuário do GDF Saúde<br>- Sistema de classificação de conteúdo |
| **Recursos** | - Algoritmo de Processamento de Linguagem Natural (PLN) para análise de texto.<br>- Funcionalidade de "upvote" (voto positivo) para comentários. |
| **Exceções** | - Um comentário genérico e pouco útil é classificado erroneamente como "relevante".<br>- O sistema de upvotes é explorado para promover artificialmente um comentário. |
| **Restrições** | - A relevância de um comentário deve ser calculada por um algoritmo que pondere a presença de palavras-chave predefinidas e o número de "upvotes" recebidos. |
| **Episódios** | 1. Um usuário escreve um comentário detalhado sobre sua experiência cirúrgica.<br>2. Outros usuários acham o comentário útil e dão "upvotes".<br>3. O algoritmo do sistema identifica palavras-chave como "cirurgia", "recuperação" e "equipe médica".<br>4. Com base nos upvotes e nas palavras-chave, o comentário recebe a tag "Relevante" e é movido para o topo da lista. |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC" target="_blank">Ana Luiza Soares</a></p>

---

### Cenário 44: Ordenação por Nota Média de Atendimento

**Requisito Associado:** [RF02.4](../../../elicitacao/requisitos_finais/#RF02.2) - O sistema ordenará clínicas por nota média de atendimento, do maior para o menor.

<p align="center">Tabela 46 - Cenário 44</p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE44">CE44</a> |
| **Título** | Ordenação de Resultados por Avaliação |
| **Metas/Objetivos** | Permitir que o usuário organize os resultados de uma busca de clínicas com base na satisfação de outros pacientes, exibindo as mais bem avaliadas primeiro. |
| **Contexto** | Um usuário busca por "laboratórios de análises clínicas" e, para garantir um serviço de qualidade, ele usa a opção de ordenar os resultados pela nota média, do maior para o menor. |
| **Ator(es)** | - Usuário do GDF Saúde<br>- Sistema de busca e ordenação |
| **Recursos** | - Interface com opção de ordenação (menu dropdown, botão, etc.).<br>- Backend com lógica para calcular e ordenar pela nota média das avaliações. |
| **Exceções** | - A função de ordenar não é aplicada corretamente e a lista permanece inalterada.<br>- As notas exibidas estão desatualizadas em relação às últimas avaliações recebidas. |
| **Restrições** | - A nota média deve ser claramente visível em cada item da lista de resultados.<br>- A opção de ordenação por nota deve ser facilmente acessível. |
| **Episódios** | 1. Um usuário executa uma busca por laboratórios.<br>2. Na tela de resultados, ele clica em "Ordenar por" e seleciona "Maior Nota".<br>3. A lista de laboratórios é recarregada.<br>4. O laboratório com nota média 4.9 aparece no topo, seguido pelo de nota 4.8, e assim por diante. |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC" target="_blank">Ana Luiza Soares</a></p>

---

### Cenário XX: O sistema deve permitir o cadastro de dependentes vinculados a um titular

**Requisito Associado:** [RF07.2](../../../elicitacao/requisitos_finais/#RF07.2) - O sistema deve permitir o cadastro de dependentes vinculados a um titular

<p align="center">Tabela XX - Cenário XX</p>

| Elemento            | Descrição|
| :------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | <a id="CEXX">CEXX</a>                                                                                                                                                                                                                                                                                                                                                          |
| **Título**          | Cadastro de Dependentes Vinculados a um Titular                                                                                                                                                                                                                                                                                                                                |
| **Metas/Objetivos** | Permitir que um usuário titular cadastre dependentes no sistema, associando-os ao seu plano de saúde.                                                                                                                                                                                                                                                                          |
| **Contexto**        | Um usuário titular do GDF Saúde deseja incluir seus filhos e cônjuge como dependentes em seu cadastro, para que todos tenham acesso aos serviços vinculados ao plano.                                                                                                                                                                                                          |
| **Ator(es)**        | - Usuário titular do GDF Saúde<br>- Sistema de cadastro e gestão de usuários                                                                                                                                                                                                                                                                                                   |
| **Recursos**        | - Interface para gerenciamento de perfil com opção de adicionar dependentes.<br>- Formulário de cadastro com campos como nome, data de nascimento, parentesco, CPF.<br>- Validações de vínculo e elegibilidade conforme regras do plano.                                                                                                               |
| **Exceções**        | - Dados do dependente são inválidos (ex: CPF duplicado, data de nascimento no futuro).<br>- Limite de número de dependentes excedido.<br>- Tentativa de cadastro por usuário não titular.                                                                                                                                                                                      |
| **Restrições**      | - Apenas usuários titulares podem adicionar ou remover dependentes.<br>- Cada dependente deve estar vinculado a um único titular.<br>- Dados obrigatórios devem ser preenchidos corretamente para concluir o cadastro.                                                                                                                                                         |
| **Episódios**       | 1. O titular acessa seu perfil no sistema.<br>2. Ele seleciona a opção "Gerenciar Dependentes" e clica em "Adicionar Novo".<br>3. Preenche os dados do dependente (ex: nome, parentesco, data de nascimento).<br>4. Confirma a inclusão, e o dependente aparece listado como vinculado ao titular.<br>5. O sistema valida as informações e confirma a associação bem-sucedida. |
|

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a></p>

---

### Cenário XX: O sistema deve permitir o cadastro de optantes

**Requisito Associado:** [RF07.3](../../../elicitacao/requisitos_finais/#RF07.3) - O sistema deve permitir o cadastro de optantes.

<p align="center">Tabela XX - Cenário XX</p>

| Elemento            | Descrição                                                                                                                                                                                                                                                                                                  |
| :------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | <a id="CEXX">CEXX</a>                                                                                                                                                                                                                                                                                      |
| **Título**          | Cadastro de Optantes                                                                                                                                                                                                                                                                                       |
| **Metas/Objetivos** | Permitir que usuários elegíveis realizem seu cadastro como optantes no sistema, vinculando-se formalmente ao plano de saúde GDF Saúde.                                                                                                                                                                     |
| **Contexto**        | Um servidor público que deseja aderir ao GDF Saúde acessa o sistema e realiza seu cadastro como optante, preenchendo os dados exigidos para formalizar a opção pelo plano.                                                                                                                                 |
| **Ator(es)**        | - Usuário elegível (servidor público ou equivalente)<br>- Sistema de cadastro e validação de optantes                                                                                                                                                                                                      |
| **Recursos**        | - Interface com opção de "Cadastrar como Optante".<br>- Formulário com dados pessoais, funcionais e de contato.<br>- Integração com base de dados funcionais para validação da elegibilidade.<br>- Confirmação e geração de comprovante de adesão.                                                         |
| **Exceções**        | - Dados fornecidos não conferem com os registros funcionais.<br>- Tentativa de cadastro por usuário não elegível.<br>- Erro de sistema durante o processo de envio ou validação.                                                                                                                           |
| **Restrições**      | - Apenas usuários elegíveis podem se cadastrar como optantes.<br>- Campos obrigatórios (como matrícula funcional, CPF, e-mail, etc.) devem estar corretamente preenchidos.<br>- Cada usuário só pode se cadastrar uma vez como optante.                                                                    |
| **Episódios**       | 1. Um servidor público acessa o portal do GDF Saúde.<br>2. Seleciona a opção "Quero ser Optante".<br>3. Preenche o formulário com seus dados pessoais e funcionais.<br>4. O sistema valida os dados e confirma a elegibilidade.<br>5. O cadastro é concluído e o usuário recebe uma confirmação de adesão. |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a></p>

---


### Cenário XX: O sistema deve validar os documentos apresentados durante o cadastro

**Requisito Associado:** [RF07.4](../../../elicitacao/requisitos_finais/#RF07.4) - O sistema deve validar os documentos apresentados durante o cadastro

<p align="center">Tabela XX - Cenário XX</p>

| Elemento            | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                       |
| :------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **ID**              | <a id="CEXX">CEXX</a>                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Título**          | Validação de Documentos no Cadastro                                                                                                                                                                                                                                                                                                                                                                                             |
| **Metas/Objetivos** | Garantir que os documentos enviados durante o processo de cadastro sejam válidos, legíveis e correspondam aos dados informados pelo usuário.                                                                                                                                                                                                                                                                                    |
| **Contexto**        | Durante o cadastro como optante ou dependente, o usuário é solicitado a enviar documentos como RG, CPF, comprovante de vínculo e/ou certidão de nascimento. O sistema valida automaticamente esses arquivos antes de permitir a conclusão do processo.                                                                                                                                                                          |
| **Ator(es)**        | - Usuário (titular ou dependente)<br>- Sistema de validação de documentos                                                                                                                                                                                                                                                                                                                                                       |
| **Recursos**        | - Upload de documentos no formato PDF, JPG ou PNG.<br>- Mecanismo de validação automática (formato, tamanho, legibilidade mínima).<br>- Interface para visualização e substituição de documentos inválidos.<br>- Notificação ao usuário em caso de erro.                                                                                                                                                                        |
| **Exceções**        | - Arquivo corrompido ou ilegível.<br>- Documento incompatível com o tipo solicitado (ex: envia CNH no lugar do RG).<br>- Dados no documento não coincidem com os dados informados no formulário.                                                                                                                                                                                                                                |
| **Restrições**      | - Apenas formatos permitidos (PDF, JPG, PNG).<br>- Tamanho máximo de arquivo definido pelo sistema.<br>- Todos os documentos obrigatórios devem ser enviados e validados antes da finalização do cadastro.                                                                                                                                                                                                                      |
| **Episódios**       | 1. O usuário inicia o cadastro e preenche os dados solicitados.<br>2. Anexa os documentos exigidos pelo sistema (ex: RG, CPF, certidão).<br>3. O sistema verifica se os arquivos são legíveis e se correspondem ao tipo solicitado.<br>4. Caso algum documento esteja inválido, o sistema exibe mensagem de erro com a opção de reenviar.<br>5. Com todos os documentos validados, o sistema permite a finalização do cadastro. |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a></p>

---

### Cenário XX: O sistema deve verificar a elegibilidade dos titulares, dependentes e optantes durante o processo de cadastro.
**Requisito Associado:** [RF07.5](../../../elicitacao/requisitos_finais/#RF07.5) - 	O sistema deve verificar a elegibilidade dos titulares, dependentes e optantes durante o processo de cadastro.

<p align="center">Tabela XX - Cenário XX</p>

| Elemento            | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| :------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | <a id="CEXX">CEXX</a>                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Título**          | Verificação de Elegibilidade no Cadastro                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Metas/Objetivos** | Assegurar que apenas usuários elegíveis (titulares, dependentes e optantes) possam ser cadastrados no sistema GDF Saúde, de acordo com critérios definidos pelo plano.                                                                                                                                                                                                                                                                                                     |
| **Contexto**        | Durante o processo de cadastro, o sistema realiza verificações automáticas para validar se o titular é um servidor ativo, se os dependentes possuem vínculo permitido (como filho ou cônjuge) e se o optante atende aos critérios exigidos.                                                                                                                                                                                                                                |
| **Ator(es)**        | - Usuário (titular, dependente ou optante)<br>- Sistema de verificação de elegibilidade<br>- Base de dados funcionais e administrativas                                                                                                                                                                                                                                                                                                                                    |
| **Recursos**        | - Integração com sistemas de RH ou banco de dados oficial de servidores.<br>- Regras de negócio para checagem de vínculos familiares.<br>- Feedback ao usuário sobre aprovação ou recusa de elegibilidade.                                                                                                                                                                                                                                                                 |
| **Exceções**        | - Usuário tenta se cadastrar, mas não consta como servidor ativo ou elegível.<br>- Dependente com vínculo não permitido (ex: sobrinho).<br>- Falha na comunicação com a base de dados de verificação.                                                                                                                                                                                                                                                                      |
| **Restrições**      | - Nenhum cadastro pode ser concluído sem a verificação de elegibilidade.<br>- As regras de elegibilidade devem estar atualizadas conforme diretrizes do plano GDF Saúde.<br>- Em caso de reprovação, o motivo deve ser informado ao usuário.                                                                                                                                                                                                                               |
| **Episódios**       | 1. Um servidor acessa o sistema para se cadastrar como titular ou optante.<br>2. O sistema consulta automaticamente sua situação funcional para verificar se está ativo e apto.<br>3. Ele adiciona um dependente, e o sistema valida o grau de parentesco.<br>4. Caso todos os critérios de elegibilidade sejam atendidos, o sistema permite concluir o cadastro.<br>5. Se alguma pessoa for considerada inelegível, uma mensagem explica o motivo e impede a finalização. |


<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a></p>


---

### Cenário XX: O sistema deve verificar a elegibilidade dos titulares, dependentes e optantes durante o processo de cadastro.
**Requisito Associado:** [RF08.1](../../../elicitacao/requisitos_finais/#RF08.1) - 	Verificar se procedimentos estão na TABGDFSAÚDE, atendem às DUT, estão sujeitos a carência ou são excluídos, exigindo solicitação médica e análise técnica para autorizações prévias.

<p align="center">Tabela XX - Cenário XX</p>

| Elemento            | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| :------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | <a id="CEXX">CEXX</a>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Título**          | Verificação de Procedimentos com Base na TABGDFSAÚDE, DUT, Carência e Regras de Autorização                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Metas/Objetivos** | Verificar automaticamente se um procedimento solicitado está previsto na Tabela TABGDFSAÚDE, se atende às Diretrizes de Utilização Técnica (DUT), se está sujeito a período de carência, se é excluído da cobertura ou se exige solicitação médica e análise técnica para autorização prévia.                                                                                                                                                                                                                                                                                             |
| **Contexto**        | Um beneficiário solicita a realização de um procedimento (ex: ressonância magnética). O sistema consulta as regras da TABGDFSAÚDE, verifica as DUT, analisa se o procedimento requer carência, e determina se é necessário solicitar autorização prévia com análise técnica.                                                                                                                                                                                                                                                                                                              |
| **Ator(es)**        | - Beneficiário<br>- Médico solicitante<br>- Sistema de autorização e regulação<br>- Auditor médico/técnico                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Recursos**        | - Integração com a tabela TABGDFSAÚDE e regras atualizadas de DUT.<br>- Consulta à carência individual do beneficiário.<br>- Módulo para upload de solicitação médica.<br>- Disparo automático de fluxo para análise técnica (quando aplicável).                                                                                                                                                                                                                                                                                                                                          |
| **Exceções**        | - Procedimento não consta na TABGDFSAÚDE.<br>- Beneficiário ainda está em período de carência.<br>- Documentação incompleta para análise técnica.<br>- Falha na leitura das regras de DUT.                                                                                                                                                                                                                                                                                                                                                                                                |
| **Restrições**      | - Procedimentos excluídos não devem seguir para autorização.<br>- Solicitações que exigem análise técnica não podem ser liberadas automaticamente.<br>- O sistema deve exibir justificativa clara para qualquer negativa ou exigência adicional.                                                                                                                                                                                                                                                                                                                                          |
| **Episódios**       | 1. Um médico solicita um procedimento para um beneficiário no sistema.<br>2. O sistema verifica se o procedimento está listado na TABGDFSAÚDE.<br>3. Consulta as DUT para ver se a indicação clínica atende aos critérios.<br>4. Avalia se o beneficiário já cumpriu a carência exigida.<br>5. Caso o procedimento esteja coberto e sem restrições, a solicitação é autorizada.<br>6. Se exigir análise técnica, o sistema solicita documentos médicos e envia para auditoria.<br>7. Em caso de exclusão da cobertura ou descumprimento de critérios, o pedido é recusado com explicação. |


<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a></p>

---

### Cenário XX: Permitir ao usuário visualizar o histórico de consultas realizadas
**Requisito Associado:** [RF09.1](../../../elicitacao/requisitos_finais/#RF09.1) - 	Permitir ao usuário visualizar o histórico de consultas realizadas.
<p align="center">Tabela XX - Cenário XX</p>

| Elemento            | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| :------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | <a id="CE50">CE50</a>                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Título**          | Visualização do Histórico de Consultas                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Metas/Objetivos** | Permitir que o usuário acompanhe todas as consultas médicas já realizadas, com detalhes como data, especialidade, profissional de saúde e local de atendimento.                                                                                                                                                                                                                                                                                     |
| **Contexto**        | Um beneficiário deseja consultar seu histórico de atendimento para verificar quando foi sua última consulta com um cardiologista e em qual clínica ocorreu. Ele acessa o sistema e visualiza todas as consultas registradas em ordem cronológica.                                                                                                                                                                                                   |
| **Ator(es)**        | - Beneficiário (titular ou dependente)<br>- Sistema de registro e exibição de histórico médico                                                                                                                                                                                                                                                                                                                                                      |
| **Recursos**        | - Tela de histórico com filtros por período, especialidade e profissional.<br>- Listagem com informações resumidas (data, especialidade, local, nome do profissional).<br>- Opção de detalhar cada consulta (ex: horário, status, observações).                                                                                                                                                                                                     |
| **Exceções**        | - Nenhuma consulta encontrada para o período selecionado.<br>- Dados incompletos devido a falhas no registro de atendimentos.<br>- Problemas de sincronização com sistemas externos de clínicas credenciadas.                                                                                                                                                                                                                                       |
| **Restrições**      | - O histórico só deve exibir consultas já realizadas, não futuras ou agendadas.<br>- Usuários dependentes só podem ver seu próprio histórico.<br>- Informações sensíveis devem seguir as diretrizes da LGPD (Lei Geral de Proteção de Dados).                                                                                                                                                                                                       |
| **Episódios**       | 1. O beneficiário acessa seu perfil no sistema GDF Saúde.<br>2. Seleciona a opção "Histórico de Consultas".<br>3. A tela exibe uma lista das consultas realizadas em ordem cronológica.<br>4. O usuário aplica filtros para visualizar apenas as consultas com determinada especialidade.<br>5. Ele clica em uma linha da lista para ver detalhes da consulta, como nome do médico, unidade de atendimento e observações clínicas (se disponíveis). |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a></p>
## Referência Bibliográfica

---

### Cenário XX: Visualização do Histórico de Consultas
**Requisito Associado:** [RF09.2](../../../elicitacao/requisitos_finais/#RF09.2) - 	Visualização do Histórico de Consultas
<p align="center">Tabela XX - Cenário XX</p>

| Elemento            | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| :------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | <a id="CEXX">CEXX</a>                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Título**          | Visualização do Histórico de Consultas                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Metas/Objetivos** | Permitir que o usuário acompanhe todas as consultas médicas já realizadas, com detalhes como data, especialidade, profissional de saúde e local de atendimento.                                                                                                                                                                                                                                                                                     |
| **Contexto**        | Um beneficiário deseja consultar seu histórico de atendimento para verificar quando foi sua última consulta com um cardiologista e em qual clínica ocorreu. Ele acessa o sistema e visualiza todas as consultas registradas em ordem cronológica.                                                                                                                                                                                                   |
| **Ator(es)**        | - Beneficiário (titular ou dependente)<br>- Sistema de registro e exibição de histórico médico                                                                                                                                                                                                                                                                                                                                                      |
| **Recursos**        | - Tela de histórico com filtros por período, especialidade e profissional.<br>- Listagem com informações resumidas (data, especialidade, local, nome do profissional).<br>- Opção de detalhar cada consulta (ex: horário, status, observações).                                                                                                                                                                                                     |
| **Exceções**        | - Nenhuma consulta encontrada para o período selecionado.<br>- Dados incompletos devido a falhas no registro de atendimentos.<br>- Problemas de sincronização com sistemas externos de clínicas credenciadas.                                                                                                                                                                                                                                       |
| **Restrições**      | - O histórico só deve exibir consultas já realizadas, não futuras ou agendadas.<br>- Usuários dependentes só podem ver seu próprio histórico.<br>- Informações sensíveis devem seguir as diretrizes da LGPD (Lei Geral de Proteção de Dados).                                                                                                                                                                                                       |
| **Episódios**       | 1. O beneficiário acessa seu perfil no sistema GDF Saúde.<br>2. Seleciona a opção "Histórico de Consultas".<br>3. A tela exibe uma lista das consultas realizadas em ordem cronológica.<br>4. O usuário aplica filtros para visualizar apenas as consultas com determinada especialidade.<br>5. Ele clica em uma linha da lista para ver detalhes da consulta, como nome do médico, unidade de atendimento e observações clínicas (se disponíveis). |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a></p>

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
|`3.0`  | 12/06/2025  | Corrigindo âncoras e metodologia para uma melhor rastreabilidade e identificação dos cenários. Além disso, corrigi os meus cenários, retirando os cenários não funcionais e criando cenários para os Requisitos: RF01.1, RF01.2, RF01.3, RF01.4, RF01.5, RF02.1, RF02.2 e RF02.3 .  | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) | [Matheus de Alcântara](https://github.com/matheusdealcantara) |
