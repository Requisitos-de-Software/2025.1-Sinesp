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
                <td>Criou os cenários  referentes aos requisitos: RF01.1, RF01.2, RF01.3, RF01.4, RF01.5, RF02.1, RF02.2, RF02.3. Além disso, consolidou o documento final ao pegar os cenários separados, que se encontravam na plataforma <a href="https://stackedit.io/app#">StackEdit</a> e organizar no documento final para o Github Pages. Além disso refatorou os cenários para fazerem sentido para os novos requisitos finais e arrumou a rastreabilidade de todos os requisitos do antigo para o novo</td>
            </tr>
            <tr>
                <td><a href="https://github.com/isaqzin" target="_blank">Isaque Camargos</a></td>
                <td> Inicou o documento criando a introdução e criou os cenários:10, 11, 12 e 46.</td>
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
                <td>Criou os cenários  referentes aos requisitos:: RF11, RF12.1, RF12.2, RF12.3, RF12.4, RF12.5 e RF12.6.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></td>
                <td>Realizou o ajuste da tabela 1, que estava quebra. Além disso, criou os cenários referentes aos requisitos: RF3, RF13, RF14.1, RF14.2, RF15 e RF22.</td>
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
### Cenário 2: Pesquisa de Profissionais da Saúde

**Requisito Associado:** [RF01.2](../../../elicitacao/requisitos_finais/#RF01.2) - O usuário poderá pesquisar profissionais da saúde (médicos, psicólogos etc.) por meio de filtros de busca.

<p align="center">Tabela 4 - Cenário 2</p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE02">CE02</a> |
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

### Cenário 3: Combinação de Filtros de Pesquisa

**Requisito Associado:** [RF01.3](../../../elicitacao/requisitos_finais/#RF01.3) - Será possível combinar filtros de pesquisa (por ex. “região administrativa + especialidade”).

<p align="center">Tabela 5 - Cenário 3</p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE03">CE03</a> |
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

### Cenário 4: Busca por Proximidade

**Requisito Associado:** [RF01.4](../../../elicitacao/requisitos_finais/#RF01.4) - O filtro de pesquisa deve permitir buscas por proximidade do usuário (distância em até 10 km).

<p align="center">Tabela 6 - Cenário 4</p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE04">CE04</a> |
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


### Cenário 5: Busca por Especialidade Médica

**Requisito Associado:** [RF01.5](../../../elicitacao/requisitos_finais/#RF01.5) - O Filtro permite busca pela especialidade médica.

<p align="center">Tabela 7 - Cenário 5</p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE05">CE05</a> |
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

### Cenário 6: Avaliação de Atendimento com escala de 1 a 5 
**Requisito Associado:** [RF02.1](../../../elicitacao/requisitos_finais/#RF02.1)  

<p align="center">Tabela 8 - Cenário 6 </p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** |  <a id="CE06">CE06</a>  |
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


### Cenário 7: Leitura e Publicação de Comentários

**Requisito Associado:** [RF02.2](../../../elicitacao/requisitos_finais/#RF02.2) - O usuário poderá deixar e/ou ler comentários sobre atendimentos em clínicas ou com profissionais específicos.

<p align="center">Tabela 9 - Cenário 7</p>

| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE07">CE07</a> |
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


### Cenário 8: Classificação de Relevância dos Comentários

**Requisito Associado:** [RF02.3](../../../elicitacao/requisitos_finais/#RF02.2) - O sistema classificará comentários como “relevantes” ou “não relevantes” automaticamente com base em palavras-chave e upvotes de outros usuários.

<p align="center">Tabela 10 - Cenário 8</p>


| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE08">CE08</a> |
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


### Cenário 9: Ordenação por Nota Média de Atendimento

**Requisito Associado:** [RF02.4](../../../elicitacao/requisitos_finais/#RF02.2) - O sistema ordenará clínicas por nota média de atendimento, do maior para o menor.

<p align="center">Tabela 11 - Cenário 9</p>


| Elemento | Descrição |
| :--- | :--- |
| **ID** | <a id="CE09">CE09</a> |
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


### Cenário 10: Acesso à carteirinha digital sem conexão à internet  

**Requisito Associado:** [RF03](../../../elicitacao/requisitos_finais/#RF03)  

<p align="center">Tabela 12 - Cenário 10</p>

| Elemento        | Descrição                                                                                                                                                                                                                                          |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID** |  <a id="CE10">CE10</a>  |
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

### Cenário 11: Configuração de preferências de notificação pelo usuário  
**Requisito Associado:** [RF04.1](../../elicitacao/requisitos_finais.md#RF04.1)  e [RF04.9](../../elicitacao/requisitos_finais.md#RF04.9)

<p align="center">Tabela 13 - Cenário 11</p>

| Elemento        | Descrição|
|-----------------|--------------------------------------------------------|
| **ID**|  <a id="CE11">CE11</a>|
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

### Cenário 12: Envio de notificação sobre demonstrativo de IR e vencimento de fatura  
**Requisito Associado:** [RF04.1](../../elicitacao/requisitos_finais.md#RF04.1)  e [RF04.9](../../elicitacao/requisitos_finais.md#RF04.9)

<p align="center">Tabela 14 - Cenário 12</p>

| Elemento        | Descrição|
|-----------------|----------------------------------------------------|
| **ID**          |  <a id="CE12">CE12</a>|
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

### Cenário 13: Agendar Consulta Médica pelo Aplicativo

**Requisito Associado:** [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1)

<p align="center">Tabela 15 - Cenário 13</p>

| Elemento | Descrição |
|---|---|
| **ID** | <a id="CE13">CE13</a> |
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

### Cenário 14: Cancelar um Agendamento de Consulta

**Requisito Associado:** [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2)
<p align="center">Tabela 16 - Cenário 14</p>

| Elemento | Descrição |
|---|---|
| **ID** | <a id="CE14">CE14</a> |
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

### Cenário 15: Verificar Preço de Consulta Antes de Agendar

**Requisito Associado:** [RF06.1](../../elicitacao/requisitos_finais.md#RF06.1)
<p align="center">Tabela 17 - Cenário 15</p>

| Elemento | Descrição |
|---|---|
| **ID** | <a id="CE15">CE15</a> |
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

### Cenário 16: Simular Custo de Coparticipação

**Requisito Associado:** [RF06.2](../../elicitacao/requisitos_finais.md#RF06.2)
<p align="center">Tabela 18 - Cenário 16</p>

| Elemento | Descrição |
|---|---|
| **ID** | <a id="CE16">CE16</a> |
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

### Cenário 17: Emitir Demonstrativo para Imposto de Renda

**Requisito Associado:** [RF06.3](../../elicitacao/requisitos_finais.md#RF06.3)
<p align="center">Tabela 19 - Cenário 17</p>

| Elemento | Descrição |
|---|---|
| **ID** | <a id="CE17">CE17</a> |
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

### Cenário 18: Acessar Demonstrativos de Anos Anteriores

**Requisito Associado:** [RF06.4](../../elicitacao/requisitos_finais.md#RF06.4)
<p align="center">Tabela 20 - Cenário 18</p>

| Elemento | Descrição |
|---|---|
| **ID** | <a id="CE18">CE18</a> |
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

### Cenário 19: Conferir Despesas no Extrato Financeiro

**Requisito Associado:** [RF06.5](../../elicitacao/requisitos_finais.md#RF06.5)
<p align="center">Tabela 21 - Cenário 19</p>

| Elemento | Descrição |
|---|---|
| **ID** | <a id="CE19">CE19</a> |
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

### Cenário 20: Acompanhar Metas de Saúde Preventiva

**Requisito Associado:** [RF17](../../elicitacao/requisitos_finais.md#RF17)
<p align="center">Tabela 22 - Cenário 20</p>

| Elemento | Descrição |
|---|---|
| **ID** | <a id="CE20">CE20</a> |
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

### Cenário 21: Cadastrar Titular no Sistema

**Requisito Associado:** [RF07.1](../../elicitacao/requisitos_finais.md#RF07.1)
<p align="center">Tabela 23 - Cenário 21</p>

| Elemento | Descrição |
|---|---|
| **ID** | <a id="CE21">CE21</a> |
| **Título** | Cadastro de Titular pelo Aplicativo |
| **Metas/Objetivos** | Permitir ao usuário titular realizar seu cadastro no sistema, anexando documentos obrigatórios e validando suas informações. |
| **Ator(es)** | - Usuário (Titular) |
| **Contexto** | O usuário deseja se tornar titular do plano e precisa cadastrar seus dados e documentos pelo aplicativo. |
| **Recursos** | - App GDF Saúde<br>- Conexão com a internet<br>- Sistema de autenticação<br>- Módulo de upload de documentos<br>- Banco de dados de titulares |
| **Exceções** | - Falha no upload de documentos.<br>- Dados incompletos ou inválidos.<br>- Perda de conexão durante o cadastro. |
| **Restrições** | - Documentos obrigatórios devem ser anexados.<br>- Cadastro só é concluído após validação dos dados. |
| **Episódios** | 1. Usuário acessa a área de cadastro.<br>2. Preenche dados pessoais.<br>3. Anexa documentação.<br>4. Sistema valida informações.<br>5. Cadastro é confirmado e usuário recebe notificação. |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### Cenário 22: Cadastrar Dependente Vinculado ao Titular

**Requisito Associado:** [RF07.2](../../elicitacao/requisitos_finais.md#RF07.2)
<p align="center">Tabela 24 - Cenário 22</p>

| Elemento | Descrição |
|---|---|
| **ID** | <a id="CE22">CE22</a> |
| **Título** | Cadastro de Dependente pelo Titular |
| **Metas/Objetivos** | Permitir ao titular cadastrar dependentes, anexando documentos e vinculando-os ao seu plano. |
| **Ator(es)** | - Usuário (Titular) |
| **Contexto** | O titular deseja incluir um dependente em seu plano de saúde pelo aplicativo. |
| **Recursos** | - App GDF Saúde<br>- Conexão com a internet<br>- Sistema de autenticação<br>- Módulo de upload de documentos<br>- Banco de dados de dependentes |
| **Exceções** | - Falha no upload de documentos.<br>- Dados do dependente incompletos.<br>- Perda de conexão durante o cadastro. |
| **Restrições** | - Documentos obrigatórios do dependente devem ser anexados.<br>- Cadastro só é concluído após validação dos dados. |
| **Episódios** | 1. Titular acessa área de dependentes.<br>2. Inicia cadastro.<br>3. Preenche dados do dependente.<br>4. Anexa documentação.<br>5. Sistema valida e confirma cadastro.<br>6. Dependente é vinculado ao titular. |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### Cenário 23: Cadastrar Optante no Sistema

**Requisito Associado:** [RF07.3](../../elicitacao/requisitos_finais.md#RF07.3)
<p align="center">Tabela 25 - Cenário 23</p>

| Elemento | Descrição |
|---|---|
| **ID** | <a id="CE23">CE23</a> |
| **Título** | Cadastro de Optante pelo Aplicativo |
| **Metas/Objetivos** | Permitir ao usuário optante realizar seu cadastro, anexando documentos obrigatórios e validando suas informações. |
| **Ator(es)** | - Usuário (Optante) |
| **Contexto** | O usuário deseja se cadastrar como optante do plano pelo aplicativo. |
| **Recursos** | - App GDF Saúde<br>- Conexão com a internet<br>- Sistema de autenticação<br>- Módulo de upload de documentos<br>- Banco de dados de optantes |
| **Exceções** | - Falha no upload de documentos.<br>- Dados incompletos ou inválidos.<br>- Perda de conexão durante o cadastro. |
| **Restrições** | - Documentos obrigatórios devem ser anexados.<br>- Cadastro só é concluído após validação dos dados. |
| **Episódios** | 1. Usuário acessa área de cadastro.<br>2. Seleciona opção "Optante".<br>3. Preenche dados.<br>4. Anexa documentação.<br>5. Sistema valida e confirma cadastro. |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### Cenário 24: Validar Documentos no Cadastro

**Requisito Associado:** [RF07.4](../../elicitacao/requisitos_finais.md#RF07.4)
<p align="center">Tabela 26 - Cenário 24</p>

| Elemento | Descrição |
|---|---|
| **ID** | <a id="CE24">CE24</a> |
| **Título** | Validação de Documentos no Processo de Cadastro |
| **Metas/Objetivos** | Garantir que os documentos anexados no cadastro de titulares, dependentes e optantes sejam válidos e legíveis. |
| **Ator(es)** | - Sistema |
| **Contexto** | O usuário anexou documentos durante o cadastro e aguarda a validação automática do sistema. |
| **Recursos** | - App GDF Saúde<br>- Módulo de validação automática de documentos<br>- Banco de dados de documentos |
| **Exceções** | - Documento ilegível.<br>- Falha técnica na validação.<br>- Documento incompatível com o formato exigido. |
| **Restrições** | - Apenas documentos válidos e legíveis são aceitos.<br>- Usuário deve reenviar documentos rejeitados. |
| **Episódios** | 1. Sistema recebe documentos anexados.<br>2. Realiza validação automática.<br>3. Informa resultado ao usuário.<br>4. Se inválido, solicita novo envio. |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### Cenário 25: Verificar Elegibilidade no Cadastro

**Requisito Associado:** [RF07.5](../../elicitacao/requisitos_finais.md#RF07.5)
<p align="center">Tabela 27 - Cenário 25</p>

| Elemento | Descrição |
|---|---|
| **ID** | <a id="CE25">CE25</a> |
| **Título** | Verificação de Elegibilidade durante o Cadastro |
| **Metas/Objetivos** | Verificar se titulares, dependentes e optantes atendem aos critérios de elegibilidade do plano durante o cadastro. |
| **Ator(es)** | - Sistema |
| **Contexto** | Após envio dos dados e documentos, o sistema realiza a verificação de elegibilidade. |
| **Recursos** | - App GDF Saúde<br>- Banco de dados de critérios de elegibilidade<br>- Sistema de validação automática |
| **Exceções** | - Dados inconsistentes.<br>- Falha técnica na verificação.<br>- Critérios de elegibilidade não atendidos. |
| **Restrições** | - Cadastro só é aprovado se todos os critérios forem atendidos.<br>- Usuário deve corrigir dados inconsistentes. |
| **Episódios** | 1. Sistema recebe dados e documentos.<br>2. Verifica critérios de elegibilidade.<br>3. Informa resultado ao usuário.<br>4. Se necessário, solicita correção de dados. |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### Cenário 26: Verificar Procedimentos para Autorização

**Requisito Associado:** [RF08](../../elicitacao/requisitos_finais.md#RF08)
<p align="center">Tabela 28 - Cenário 26</p>

| Elemento | Descrição |
|---|---|
| **ID** | <a id="CE26">CE26</a> |
| **Título** | Verificação de Procedimentos para Autorização Prévia |
| **Metas/Objetivos** | Verificar se o procedimento solicitado está coberto, exige análise técnica ou documentação adicional antes da autorização. |
| **Ator(es)** | - Titular<br>- Profissional de saúde<br>- Analista técnico |
| **Contexto** | Um procedimento médico é solicitado e precisa ser analisado conforme regras do plano. |
| **Recursos** | - App GDF Saúde<br>- Banco TABGDFSAÚDE<br>- Sistema de análise técnica<br>- Módulo de upload de laudos médicos |
| **Exceções** | - Solicitação incompleta.<br>- Falha técnica no sistema.<br>- Procedimento não coberto pelo plano. |
| **Restrições** | - Procedimentos fora das regras não são autorizados.<br>- Documentação médica obrigatória para análise técnica. |
| **Episódios** | 1. Usuário submete solicitação.<br>2. Sistema verifica TABGDFSAÚDE e DUT.<br>3. Verifica carência e exclusões.<br>4. Solicita análise técnica se necessário.<br>5. Informa resultado ao usuário. |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### Cenário 27: Visualizar Histórico de Consultas Realizadas


**Requisito Associado:** [RF09.1](../../elicitacao/requisitos_finais.md#RF09.1)
<p align="center">Tabela 29 - Cenário 27</p>

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | <a id="CE27">CE27</a>      |
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

### Cenário 28: Visualizar Histórico de Exames Realizados



**Requisito Associado:** [RF09.2](../../elicitacao/requisitos_finais.md#RF09.2)
<p align="center">Tabela 30 - Cenário 28</p>

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | <a id="CE28">CE28</a>      |
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

### Cenário 29: Visualizar Resultados de Exames Laboratoriais


**Requisito Associado:** [RF09.3](../../elicitacao/requisitos_finais.md#RF09.3)
<p align="center">Tabela 31 - Cenário 29</p>

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | <a id="CE29">CE29</a>      |
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

### Cenário 30: Visualizar Histórico de Coparticipações

**Requisito Associado:** [RF09.4](../../elicitacao/requisitos_finais.md#RF09.4)
<p align="center">Tabela 32 - Cenário 30</p>

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | <a id="CE30">CE30</a> |
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

### Cenário 31: Favoritar Horários de Consulta  
**Requisito Associado:** [RF10](../../../elicitacao/requisitos_finais/#RF10)  

<p align="center">Tabela 33 - Cenário 31</p>

| Elemento        | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**          | <a id="CE31">CE31</a> |
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

### Cenário 32: Canal para o usuário enviar feedback sobre atendimentos  
**Requisito Associado:** [RF11](../../../elicitacao/requisitos_finais/#RF11)  

<p align="center">Tabela 34 - Cenário 32</p>

| Elemento        | Descrição                                                                                                                                                                                                                                                               |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID**          | <a id="CE32">CE32</a> |
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

### Cenário 33: Apresentar uma Seção no Menu Principal Chamada "Novidades"
**Requisito Associado:** [RF12.1](../../../elicitacao/requisitos_finais/#RF12.1)  
<p align="center">Tabela 35 - Cenário 33</p>

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | <a id="CE33">CE33</a> |
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

### Cenário 34: Exibir Lista de Funcionalidades com Título, Descrição e Data
**Requisito Associado:** [RF12.2](../../../elicitacao/requisitos_finais/#RF12.2)  
<p align="center">Tabela 36 - Cenário 34</p>

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | <a id="CE34">CE34</a> |
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

### Cenário 35: Destacar Funcionalidades com Marcador "Novo"
**Requisito Associado:** [RF12.3](../../../elicitacao/requisitos_finais/#RF12.3)  
<p align="center">Tabela 37 - Cenário 35</p>

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | <a id="CE35">CE35</a> |
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

### Cenário 36: Exibir Pop-ups Informativos com as Principais Novidades
**Requisito Associado:** [RF12.4](../../../elicitacao/requisitos_finais/#RF12.4)  
<p align="center">Tabela 38 - Cenário 36</p>

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | <a id="CE36">CE36</a> |
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

### Cenário 37: Ver Descrição Detalhada ao Tocar na Funcionalidade

**Requisito Associado:** [RF12.5](../../../elicitacao/requisitos_finais/#RF12.5)  
<p align="center">Tabela 39 - Cenário 37</p>

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | <a id="CE37">CE37</a> |
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

### Cenário 38: Ordenar Novidades por Mais Recente ou Mais Antigo  
**Requisito Associado:** [RF12.6](../../../elicitacao/requisitos_finais/#RF12.6)  

<p align="center">Tabela 40 - Cenário 38</p>

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**          | <a id="CE38">CE38</a> |
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

### Cenário 39: Buscar Clínicas Odontológicas

**Requisito Associado:** [RF13](../../elicitacao/requisitos_finais/#RF13)

<p align="center">Tabela 41 - Cenário 39</p>

| Elemento | Descrição |
|---|---|
|**ID**| <a id="CE39">CE39</a> |
| **Título** | Consulta à Rede Odontológica por Filtros |
| **Metas/Objetivos** | Permitir que o usuário encontre clínicas odontológicas cadastradas de forma eficiente, aplicando critérios de busca específicos. |
| **Contexto** | O usuário, já logado no aplicativo via GovBR, deseja encontrar uma clínica odontológica que atenda às suas necessidades, utilizando filtros como especialidade ou bairro. |
| **Ator(es)** | - Usuário autenticado |
| **Recursos** | - Aplicativo GDF Saúde<br>- Banco de dados da rede odontológica<br>- Ferramenta de filtragem de busca |
| **Exceções** | - Nenhum resultado encontrado para os filtros aplicados<br>- Falha na conexão com o servidor de dados |
| **Restrições** | - A funcionalidade só está disponível para usuários autenticados.<br>- Os dados das clínicas devem estar atualizados. |
| **Episódios** | 1. Usuário acessa "Buscar rede odontológica".<br>2. Usuário insere filtros de pesquisa (ex.: "Odontopediatria", "Asa Sul").<br>3. Sistema processa os filtros e consulta o banco de dados.<br>4. Sistema exibe uma lista de clínicas odontológicas que correspondem aos critérios.<br>5. (Fluxo Alternativo) Se não houver resultados, o sistema sugere ampliar os critérios de busca.<br>6. (Fluxo de Exceção) Em caso de falha na conexão, o sistema notifica "Tente novamente mais tarde". |

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

---

### Cenário 40: Visualizar Novas Clínicas Próximas

**Requisito Associado:** [RF14.1](../../elicitacao/requisitos_finais/#RF14.1)

<p align="center">Tabela 42 - Cenário 40</p>

| Elemento | Descrição |
|---|---|
|**ID**| <a id="CE40">CE40</a> |
| **Título** | Descoberta de Novas Clínicas na Proximidade |
| **Metas/Objetivos** | Apresentar ao usuário as clínicas recém-cadastradas que estão próximas à sua localização atual, ou a um endereço especificado. |
| **Contexto** | O usuário, logado no sistema e com permissão de geolocalização, busca por novas unidades de saúde que foram adicionadas recentemente em sua região. |
| **Ator(es)** | - Usuário autenticado<br>- Sistema de geolocalização |
| **Recursos** | - Aplicativo GDF Saúde<br>- Serviço de geolocalização do dispositivo<br>- Banco de dados de clínicas com registro de data de cadastro |
| **Exceções** | - Falha na detecção automática de localização<br>- Geolocalização desativada no dispositivo<br>- Nenhuma nova clínica encontrada na proximidade |
| **Restrições** | - Requer permissão de geolocalização do usuário.<br>- A identificação de "nova clínica" deve ser baseada em um critério de tempo definido. |
| **Episódios** | 1. Usuário acessa a opção "Novas Unidades de Saúde Próximas".<br>2. Sistema tenta detectar a localização automática do usuário.<br>3. (Fluxo Alternativo) Se a detecção automática falhar, o sistema solicita que o usuário insira o endereço manualmente.<br>4. Sistema consulta o banco de dados para identificar novas clínicas na proximidade da localização (automática ou manual).<br>5. (Fluxo de Exceção) Se a geolocalização estiver desativada, o sistema solicita a ativação ou a entrada manual do endereço.<br>6. Sistema exibe uma lista de novas clínicas encontradas, ordenadas por proximidade. |

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

---

### Cenário 41: Visualizar Clínicas Próximas

**Requisito Associado:** [RF14.2](../../elicitacao/requisitos_finais/#RF14.2)

<p align="center">Tabela 43 - Cenário 41</p>

| Elemento | Descrição |
|---|---|
|**ID**| <a id="CE41">CE41</a> |
| **Título** | Busca e Exibição de Clínicas Existentes Próximas |
| **Metas/Objetivos** | Fornecer ao usuário uma lista de clínicas de saúde existentes próximas à sua localização, facilitando o acesso a serviços. |
| **Contexto** | O usuário, logado e com permissão de geolocalização, deseja visualizar as unidades de saúde já cadastradas que estão mais próximas a ele, ou a um endereço especificado. |
| **Ator(es)** | - Usuário autenticado<br>- Sistema de geolocalização |
| **Recursos** | - Aplicativo GDF Saúde<br>- Serviço de geolocalização do dispositivo<br>- Banco de dados de clínicas cadastradas |
| **Exceções** | - Falha na detecção automática de localização<br>- Geolocalização desativada no dispositivo<br>- Nenhuma clínica encontrada na proximidade |
| **Restrições** | - Requer permissão de geolocalização do usuário.<br>- A lista de clínicas deve ser abrangente e atualizada. |
| **Episódios** | 1. Usuário acessa a opção "Buscar Unidades de Saúde Próximas".<br>2. Sistema tenta detectar a localização automática do usuário.<br>3. (Fluxo Alternativo) Se a detecção automática falhar, o sistema solicita que o usuário insira o endereço manualmente.<br>4. Sistema consulta o banco de dados para identificar clínicas na proximidade da localização (automática ou manual).<br>5. (Fluxo de Exceção) Se a geolocalização estiver desativada, o sistema solicita a ativação ou a entrada manual do endereço.<br>6. Sistema exibe uma lista de clínicas encontradas, ordenadas por proximidade. |

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

---

### Cenário 42: Baixar Comprovante de Agendamento

**Requisito Associado:** [RF15](../../elicitacao/requisitos_finais/#RF15)

<p align="center">Tabela 44 - Cenário 42</p>

| Elemento | Descrição |
|---|---|
|**ID**| <a id="CE42">CE42</a> |
| **Título** | Download do Comprovante de Agendamento |
| **Metas/Objetivos** | Permitir que o usuário baixe o comprovante em PDF de um agendamento confirmado para fins de registro ou apresentação. |
| **Contexto** | O usuário, logado e com um agendamento ativo e confirmado, precisa obter o comprovante desse agendamento. |
| **Ator(es)** | - Usuário autenticado |
| **Recursos** | - Aplicativo GDF Saúde<br>- Módulo de gerenciamento de agendamentos<br>- Gerador de PDF |
| **Exceções** | - Agendamento não encontrado ou expirado<br>- Falha na geração do PDF<br>- Falha no servidor |
| **Restrições** | - O download só é permitido para agendamentos confirmados e não expirados.<br>- O comprovante deve ser gerado no formato PDF. |
| **Episódios** | 1. Usuário acessa a área "Comprovantes de agendamento".<br>2. Sistema exibe a lista de agendamentos do usuário.<br>3. Usuário seleciona o agendamento desejado para baixar o comprovante.<br>4. Usuário clica no botão "Baixar".<br>5. Sistema gera o comprovante em formato PDF e inicia o download para o dispositivo do usuário.<br>6. (Fluxo Alternativo) Se o agendamento não for encontrado ou estiver expirado, o sistema notifica "Agendamento não encontrado".<br>7. (Fluxo de Exceção) Em caso de falha no servidor durante a geração ou download, o sistema exibe uma mensagem de erro. |

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

---

### Cenário 43: Visualizar calendário personalizado com informações do plano  

**Requisito Associado:** [RF16](../../../elicitacao/requisitos_finais/#RF16)  

<p align="center">Tabela 45 - Cenário 43</p>

| Elemento        | Descrição                                                                                                          |
|-----------------|------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE43">CE43</a>  |
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

### Cenário 44: Visualizar painel de metas com gamificação  

**Requisito Associado:** [RF17](../../../elicitacao/requisitos_finais/#RF17)  

<p align="center">Tabela 46 - Cenário 44</p>

| Elemento        | Descrição                                                                                         |
|-----------------|-------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE44">CE44</a>  |
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

### Cenário 45: Registrar denúncia contra profissional da rede credenciada  

**Requisito Associado:** [RF18](../../../elicitacao/requisitos_finais/#RF18)  

<p align="center">Tabela 47 - Cenário 45</p>

| Elemento        | Descrição                                                                                              |
|-----------------|------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE45">CE45</a>  |
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

### Cenário 46: Login por biometria facial ou digital  

**Requisito Associado:** [RF19](../../../elicitacao/requisitos_finais/#RF19)  

<p align="center">Tabela 48 - Cenário 46</p>

| Elemento        | Descrição                                                                                                                                                                                                                                                                                                             |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE46">CE46</a>  |
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

### Cenário 47: Solicitação de Reembolso de Cobrança Indevida  

**Requisito Associado:** [RF20](../../../elicitacao/requisitos_finais/#RF20)  

<p align="center">Tabela 49 - Cenário 47</p>

| Elemento        | Descrição                                                                                                                              |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE47">CE47</a>  |
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


### Cenário 48: Chatbot para Direcionamento Médico


**Requisito Associado:** [RF21](../../../elicitacao/requisitos_finais/#RF21)  

<p align="center">Tabela 50 - Cenário 48 </p>

| Elemento        | Descrição                                                                                                                                                                                                                                 |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE48">CE48</a>  |
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

### Cenário 49: Exigir autenticação via GovBR para login  
**Requisito Associado:** [RF22](../../../elicitacao/requisitos_finais/#RF22)  

<p align="center">Tabela 51 - Cenário 49</p>

| Elemento        | Descrição                                                                                                                                                                   |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**ID**|  <a id="CE49">CE49</a>  |
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
| `3.1` | 19/06/2025  | Correção dos cenários para os requisitos RF09.1, RF09.2, RF09.3, RF09.4, RF10 e RF20 de acordo com as revisões da entrega, sendo para 2 requisitos funcionais não implementados no mínimo | [Matheus de Alcântara](https://github.com/matheusdealcantara) | [Othavio Bolzan](https://github.com/bolzanMGB) |
| `3.2` | 21/06/2025  | Adição dos meus cenários refinados | [Lucas Alves](https://github.com/LucasAlves71)  | [Isaque Camargos](https://github.com/isaqzin) |
|`3.3`  | 21/06/2025  | Organização e renomeação dos casos de uso  | [Othavio Bolzan](https://github.com/bolzanMGB) | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) |
|`3.4`  | 22/06/2025  | Criação de cenários pros requisitos RF22, RF14.1 e RF14.2  | [Yzabella Miranda](https://github.com/redjsun) | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) |