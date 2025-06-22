# Diagrama e Especificação de Casos de Uso

## Introdução 

Um caso de uso é uma representação detalhada de como os usuários do aplicativo GDF Saúde interagem com o sistema em situações específicas, como acessar a carteirinha, enviar feedback ou visualizar novas funcionalidades. Ele descreve passo a passo como essas interações ocorrem, desde a ação do usuário até a resposta do sistema.

Seu principal objetivo é apoiar o desenvolvimento do aplicativo, oferecendo uma visão clara e prática dos requisitos funcionais. Os casos de uso ajudam a definir o comportamento esperado do sistema diante de ações comuns dos usuários, contribuindo para garantir que as funcionalidades atendam às necessidades reais dos beneficiários do plano de saúde.

É importante notar que esses casos de uso foram **refatorados** para maior clareza e precisão, além de corresponderem com os requisitos finais que foram refinados. Você pode acessar a versão antiga clicando [aqui](../../metodos_tradicionais/casos_de_usos).

## Integrantes do Grupo

Na tabela 1 contêm todos os integrantes da equipe que participaram na construção dos cenários e o que a pessoa desenvolveu durante o projeto.

<p  align="center">Tabela 1 - Integrantes do grupo envolvidos</p>
<div align="center">
<div>
    <table>
        <thead>
                <tr>
                    <th>Nome</th>
                    <th>Quais etapas participou</th>
                </tr>
        </thead>
    <tbody>
                <tr>
                    <td><a  href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></td>
                    <td>Criou o diagrama  e especificações dos casos de uso referentes aos requisitos: RF01.1, RF01.2, RF01.3, RF01.4, RF01.5, RF02.1, RF02.2, RF02.3 e RF21.1. <br> Casos de uso: UC01, UC02, UC03, UC44, UC45, UC46, UC47, UC48 e UC49.</td>	
                </tr>
                <tr>
                    <td><a  href="https://github.com/isaqzin">Isaque Camargos</a></td>
                    <td>Criou o diagrama referentes aos requisitos: RF03,RF04.1, RF04.9 e RF19. Criou as especificações dos casos de uso referente a estes requisitos, sendo eles UC04, UC05, UC06, UC07, UC08 e UC09. Além disso, criou o documento inicial.</td>	
                </tr>
                <tr>
                    <td><a  href="https://github.com/kalebmacedo">Kaleb Macedo</a></td>
                    <td>Criou o diagrama referentes aos requisitos: RF05, RF06 e RF17. Criou as especificações dos casos de uso referente a estes requisitos, sendo eles UC13, UC14, UC15, UC16, UC28, UC29, UC30, UC31, UC32, UC33, UC34, UC35.</td>	
                </tr>
                <tr>
                    <td><a  href="https://github.com/LucasAlves71">Lucas Alves</a></td>
                    <td>Criou o diagrama referentes aos requisitos: RF07, RF08 e RF18. Criou as especificações dos casos de uso referente a estes requisitos, sendo eles UC17, UC18, UC19, UC20, UC21, UC22, UC23.</td>	
                </tr>
                <tr>
                    <td><a  href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></td>
                    <td>Criou o diagrama referentes aos requisitos: RF09.1 a RF09.4, RF10 e RF20. Criou as especificações dos casos de uso referente a estes requisitos, sendo eles UC27, UC28, UC29, UC30, UC31, UC32.</td>	
                </tr>
                <tr>
                    <td><a  href="https://github.com/bolzanMGB">Othavio Bolzan</a></td>
                    <td>Criou o diagrama referentes aos requisitos: RF11, RF12.1, RF12.2, RF12.3, RF12.4, RF12.5, RF12.6. Criou as especificações dos casos de uso referente a estes requisitos, sendo eles UC33, UC34, UC35, UC38, UC39.</td>	
                </tr>
                <tr>
                    <td><a  href="https://github.com/redjsun">Yzabella Miranda</a></td>
                    <td>Criou o diagrama referentes aos requisitos: RF3, RF13, RF14.1, RF14.2, RF15 e RF22. Criou as especificações dos casos de uso referente a estes requisitos, sendo eles UC36, UC37, UC38, UC39, UC42, UC43.</td>	
                </tr>
        </tbody>
    </table>
</div>
</div> 

<p  align="center">Fonte: Autoria de <a  href="https://github.com/isaqzin">Isaque Camargos</a> e <a  href="https://github.com/isaqzin">Yzabella Miranda</a></p>


## Metodologia 


Para mapear e compreender melhor o funcionamento do aplicativo GDF Saúde, utilizamos o diagrama de caso de uso — uma ferramenta da Engenharia de Requisitos que representa visualmente como os usuários interagem com o sistema. Esse diagrama descreve, por meio de "atores" (como beneficiários do plano) e "casos de uso" (como acessar a carteirinha ou enviar feedback), as funcionalidades oferecidas e os comportamentos esperados do sistema.

No desenvolvimento do diagrama, empregamos dois relacionamentos fundamentais: o include e o extend. O relacionamento include é usado quando uma funcionalidade sempre faz parte de outra, como, por exemplo, o caso “Acessar Aplicativo” incluir automaticamente os casos “Consultar histórico de consultas” e “Acessar carteirinha”. Já o relacionamento extend representa funcionalidades opcionais ou condicionais, que se aplicam em determinados contextos — como o caso “Modo Offline”, que estende o acesso ao histórico e à carteirinha somente quando não há conexão com a internet.

Com foco nos diagramas de caso de uso, a Tabela 2 apresenta os principais elementos que compõem o modelo, oferecendo uma visão clara e organizada da estrutura de interações entre os atores e o sistema.

### Elementos de caso de uso

<p  align="center">Tabela 2: legenda dos diagramas de caso de uso</p>

|Nome|         Função         |      Elemento      |
|----|------------------------|--------------------|
| Ator |Representam os diversos tipos de usuários externos que interagem com o sistema. | <div><img src="..\..\assets\casos-uso\casos-uso-ator.png" alt="Referência do item" width="100px"><br></div> |
| Elipse (Caso de Uso) | É utilizada para representar os casos de uso em um diagrama, destacando funcionalidades ou ações específicas que o sistema realiza em resposta às interações dos atores. | <div><img src="..\..\assets\casos-uso\casos-uso-elipse.png" alt="Referência do item" width="100px"><br></div> |
|Retângulo (Sistema)| É utilizado para representar o sistema ou o componente em análise, agrupando os casos de uso e os atores associados a ele. | <div><img src="..\..\assets\casos-uso\casos-uso-retangulo.png" alt="Referência do item" width="100px"><br></div> |
| Flecha (Relações) | As setas são utilizadas para ilustrar as relações ou interações entre os atores e os casos de uso no diagrama. | <div><img src="..\..\assets\casos-uso\casos-uso-relacionamento.png" alt="Referência do item" width="100px"><br></div> |


<p  align="center">Fonte: Autoria de <a  href="https://github.com/isaqzin">Yzabella Miranda</a></p>

## Diagramas de caso de uso
As figuras 1 a 7 representam as especializações dos casos de uso.

<p align="center">Figura 1 - Caso de uso UC01 a UC03 </p>
<p align="center">
  <img src="..\..\assets\casos-uso\casos-uso-ana-novo.png" width="600">
</p>

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC" target="_blank">Ana Luiza Soares</a></p>


<p align="center">Figura 2 - Caso de uso UC07 a UC12 </p>
<p align="center">
  <img src="..\..\assets\casos-uso\new_diagrama_isaque.png" alt="Heatmap de disponibilidade da equipe" width="600">
</p>

<p align="center">Fonte: Autoria de <a src="https://github.com/isaqzin" targe="_blank">Isaque Camargos</a></p>


<p align="center">Figura 3 - Caso de uso UC13 a UC20 </p>
<p align="center">
  <img src="..\..\assets\casos-uso\casos-uso-kaleb-rf.png" alt="Heatmap de disponibilidade da equipe" width="600">
</p>

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo" target="_blank">Kaleb Macedo</a></p>


<p align="center">Figura 4 - Caso de uso UC21 a UC26 </p>
<p align="center">
  <img src="..\..\assets\casos-uso\new_diagrama_lucas.png" alt="Heatmap de disponibilidade da equipe" width="600">
</p>

<p  align="center">Fonte: Autoria de <a  href="https://github.com/LucasAlves71" target="_blank">Lucas Alves</a></p>


<p align="center">Figura 5 - Caso de uso UC27 a UC32 </p>
<p align="center">
  <img src="..\..\assets\casos-uso\new_diagrama_matheus.jpeg" alt="Diagrama de casos de uso Matheus" width="600">
</p>

<p  align="center">Fonte: Autoria de <a  href="https://github.com/matheusdealcantara" target="_blank" >Matheus de Alcântara</a></p>

<p align="center">Figura 6 - Caso de uso UC32 a UC34 </p>
<p align="center">
  <img src="..\..\assets\casos-uso\casos-de-uso-othavio-novo.jpg" alt="Heatmap de disponibilidade da equipe" width="600">
</p>

<p  align="center">Fonte: Autoria de <a  href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a></p>

<p align="center">Figura 7 - Caso de uso UC35 a UC38 </p>
<p align="center">
  <img src="..\..\assets\casos-uso\casos-uso-yza.png" alt="Heatmap de disponibilidade da equipe" width="600">
</p>

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

## Especialização dos casos de uso 

### UC01 – Pesquisar Redes por Filtros

<p align="center">Tabela 3 - Caso de Uso UC01</p>

| Campo                    | Descrição                                                                                                                                                                                                                                  |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC01"></a>UC01     | Pesquisar Redes Credenciadas por Filtros|
| Descrição                | Permitir ao usuário localizar redes credenciadas aplicando filtros de busca gerais para refinar os resultados.|
| Ator                     | Usuário do aplicativo GDF Saúde|
| Pré-condições            | 1. Conexão com internet. <br>2. Usuário é beneficiário do Plano INAS e está logado.|
| Ação                     | Usuário aplica um ou mais filtros na tela de busca e inicia a pesquisa. |
| Fluxo principal          | - Usuário abre o aplicativo e acessa a aba "Rede Credenciada". <br>- Sistema exibe a interface de busca com as opções de filtro. <br>- Usuário seleciona o filtro "Região Administrativa" e escolhe uma opção. <br>- Sistema exibe os resultados que correspondem ao filtro aplicado. |
| Fluxo alternativo        | - Usuário realiza a busca sem aplicar nenhum filtro. <br>- Sistema exibe a lista completa de todas as redes credenciadas, ordenadas alfabeticamente.|
| Fluxo de exceção         | - Usuário aplica um filtro que não possui nenhuma rede correspondente. <br>- Sistema exibe a mensagem "Nenhuma rede credenciada encontrada para os critérios selecionados." |
| Pós-condições            | A lista de redes credenciadas que atende aos filtros aplicados é exibida com sucesso para o usuário.|
| Rastreabilidade          | [RF01.1](../../elicitacao/requisitos_finais.md#RF01.1)|
| Data de criação          | 12/06/2025|

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### UC02 – Pesquisar Profissionais da Saúde

<p align="center">Tabela 4 - Caso de Uso UC02</p>

| Campo                    | Descrição                                                                                                                                                                                                                                  |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC02"></a>UC02     | Pesquisar Profissionais da Saúde|
| Descrição                | Permitir ao usuário encontrar um profissional da saúde específico (médico, psicólogo, etc.) através de uma busca dedicada.|
| Ator                     | Usuário do aplicativo GDF Saúde|
| Pré-condições            | 1. Conexão com internet. <br>2. Usuário é beneficiário do Plano INAS e está logado.|
| Ação                     | Usuário insere o nome de um profissional ou seleciona uma especialidade na área de busca de profissionais.|
| Fluxo principal          | - Usuário acessa a seção "Buscar Profissional". <br>- Sistema exibe o campo de busca. <br>- Usuário digita o nome do profissional. <br>- Usuário aciona a busca. <br>- Sistema exibe o perfil detalhado do profissional encontrado.           |
| Fluxo alternativo        | - Usuário digita um nome parcial ou incompleto. <br>- Sistema exibe uma lista de profissionais cujos nomes correspondem à busca parcial para que o usuário selecione o correto.|
| Fluxo de exceção         | - A busca não retorna nenhum profissional com o nome inserido. <br>- Sistema exibe a mensagem "Nenhum profissional encontrado com os dados informados."|
| Pós-condições            | O perfil do profissional de saúde desejado é encontrado e suas informações são exibidas para o usuário.|
| Rastreabilidade          | [RF01.2](../../elicitacao/requisitos_finais.md#RF01.2)|
| Data de criação          | 12/06/2025|

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### UC03 – Atribuir Nota de Avaliação

<p align="center">Tabela 5 - Caso de Uso UC03</p>

| Campo                    | Descrição                                                 |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC03"></a>UC03     | Atribuir Nota de Avaliação                                      |
| Descrição                | Permitir ao usuário classificar a qualidade de um atendimento utilizando uma nota na escala Likert de 1 a 5. |
| Ator                     | Usuário do aplicativo GDF Saúde           |
| Pré-condições            | 1. Usuário teve um atendimento registrado na rede a ser avaliada. <br>2. Usuário está logado no aplicativo.   |
| Ação                     | Usuário seleciona uma nota de 1 a 5 estrelas na tela de avaliação de um atendimento. |
| Fluxo principal          | - Usuário acessa o perfil da clínica e seleciona a opção "Avaliar Atendimento". <br>- Sistema exibe a interface de avaliação. <br>- Usuário seleciona a nota desejada (ex: 4 de 5 estrelas). <br>- Usuário confirma a submissão da nota.      |
| Fluxo alternativo        | - O usuário seleciona uma nota, mas decide alterá-la antes de submeter. <br>- O usuário toca em uma nova quantidade de estrelas, e o sistema atualiza a seleção.                 |
| Fluxo de exceção         | - O usuário tenta submeter a avaliação, mas ocorre uma falha de conexão. <br>- Sistema exibe uma mensagem de erro e oferece a opção de tentar novamente, mantendo a nota selecionada.                                                        |
| Pós-condições            | A nota de avaliação do usuário é registrada com sucesso no sistema e associada ao respectivo atendimento. |
| Rastreabilidade          | [RF02.1](../../elicitacao/requisitos_finais.md#RF02.1) |
| Data de criação          | 12/06/2025   |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### UC04 – Ler e Escrever Comentários

<p align="center">Tabela 6 - Caso de Uso UC04</p>

| Campo                    | Descrição                                               |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC04"></a>UC04     | Ler e Escrever Comentários                                        |
| Descrição                | Permitir ao usuário ler as experiências de outros beneficiários e deixar seus próprios comentários sobre atendimentos. |
| Ator                     | Usuário do aplicativo GDF Saúde |
| Pré-condições            | 1. Usuário está logado. <br>2. Usuário está visualizando o perfil de uma clínica ou profissional.|
| Ação                     | Usuário acessa a seção de comentários para ler as avaliações ou preenche o campo de texto para submeter um novo comentário.                                                                                                                |
| Fluxo principal          | - Leitura: Usuário acessa a aba "Avaliações" e percorre a lista de comentários existentes. <br>- Escrita: Na mesma tela, usuário toca em "Deixar um comentário", digita seu feedback no campo de texto e toca em "Enviar".              |
| Fluxo alternativo        | - Ao escrever um comentário, o usuário decide cancelar a ação antes de enviar. <br>- O usuário toca no botão "Cancelar" e o sistema o retorna à tela anterior sem salvar o rascunho.     |
| Fluxo de exceção         | - O comentário do usuário contém termos inadequados bloqueados pelo sistema. <br>- Ao tentar enviar, o sistema exibe uma mensagem informando que o comentário não pode ser publicado e destaca as diretrizes da comunidade.                |
| Pós-condições            | Usuário visualiza os comentários de outros ou tem seu novo comentário submetido com sucesso para moderação e publicação. |
| Rastreabilidade          | [RF02.2](../../elicitacao/requisitos_finais.md#RF02.2) |
| Data de criação          | 12/06/2025   |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### UC05 – Visualizar Comentários Relevantes

<p align="center">Tabela 7 - Caso de Uso UC05</p>

| Campo                    | Descrição                                                 |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC05"></a>UC05     | Visualizar Comentários Relevantes                                |
| Descrição                | Permitir ao usuário visualizar primeiro os comentários que o sistema classifica automaticamente como os mais "relevantes", com base em critérios como utilidade e palavras-chave.                                                           |
| Ator                     | Usuário do aplicativo GDF Saúde    |
| Pré-condições            | Usuário está na seção de avaliações de uma clínica que possui múltiplos comentários. |
| Ação                     | Usuário abre a lista de comentários de um profissional ou clínica. |
| Fluxo principal          | - Usuário acessa a aba de "Avaliações" de uma clínica. <br>- A lista de comentários é carregada. <br>- O sistema, por padrão, exibe no topo os comentários que foram identificados como os mais relevantes.                                      |
| Fluxo alternativo        | - O usuário prefere ver os comentários mais recentes. <br>- O usuário seleciona a opção de ordenação "Mais Recentes". <br>- O sistema recarrega a lista, exibindo os comentários em ordem cronológica decrescente.                             |
| Fluxo de exceção         | - A clínica não possui comentários suficientes para que a classificação por relevância seja significativa. <br>- O sistema exibe todos os comentários disponíveis, ordenados por data como padrão alternativo.                                |
| Pós-condições            | O usuário tem acesso rápido às opiniões consideradas mais úteis, otimizando seu tempo de análise. |
| Rastreabilidade          | [RF02.3](../../elicitacao/requisitos_finais.md#RF02.3)  |
| Data de criação          | 12/06/2025   |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### UC06 – Iniciar Conversa com Chatbot de Triagem

<p align="center">Tabela 8 - Caso de Uso UC06</p>

| Campo              | Descrição                                                                                                                                       |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC06"></a>UC06 | Iniciar Conversa com Chatbot de Triagem |
| Descrição          | Permitir ao usuário interagir com chatbot para identificar especialidade médica adequada |
| Ator               | Usuário do aplicativo GDF Saúde |
| Pré-condições      | 1. Conexão com internet. <br>2. Usuário é beneficiário do Plano INAS |
| Ação               | Usuário inicia conversa e descreve sintomas |
| Fluxo principal    | - Usuário abre o aplicativo <br>- Usuário seleciona a opção "Chatbot de Saúde" <br>- Sistema exibe tela inicial do chatbot <br>- Usuário descreve sintomas <br>- Chatbot analisa e sugere especialidade médica <br>- Sistema pede confirmação ao usuário posteriormente para análise de desempenho |
| Fluxo alternativo  | - Usuário abre o aplicativo <br>- Usuário seleciona a opção "Chatbot de Saúde" <br>- Sistema exibe tela inicial do chatbot <br>- Usuário tem dúvidas ou fornece informações vagas <br>- Chatbot recomenda buscar hospital para melhor triagem |
| Fluxo de exceção   | - Usuário abre o aplicativo <br>- Usuário seleciona a opção "Chatbot de Saúde" <br>- Inicia a conversa <br>- Chatbot redireciona para especialidade médica incorreta |
| Pós-condições      | Especialidade médica identificada corretamente e confirmado o desempenho do chatbot posteriormente |
| Rastreabilidade    | [RF21.1](../../elicitacao/requisitos_finais.md#RF21.1) |
| Data de criação    | 17/05/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### UC07 – Fazer Login

<p align="center">Tabela 9 - Caso de Uso UC07</p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| <a id="UC07"></a>UC07 | Fazer Login                                                        |
| Descrição          | Permitir que o usuário acesse o app com e-mail/CPF e senha.               |
| Ator               | Usuário cadastrado                                                        |
| Pré-condições      | App instalado e com conexão à internet.                                   |
| Ação               | O usuário preenche e-mail/CPF e senha e confirma para entrar.             |
| Fluxo principal    | - O usuário acessa a tela de login.<br>- Insere e-mail/CPF e senha.<br>- O sistema valida os dados.<br>- O usuário é autenticado. |
| Fluxo alternativo  | - Credenciais inválidas: sistema exibe mensagem de erro.                  |
| Fluxo de exceção   | - Ausência de conexão: sistema informa que não é possível conectar.       |
| Pós-condições      | Usuário autenticado e apto a usar o aplicativo.                           |
| Rastreabilidade    | [RF19](../../elicitacao/requisitos_finais.md#RF19)                                                                         |
| Data de criação    | 15/05/2025                                                                |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### UC08 – Login por Biometria

<p align="center">Tabela 10 - Caso de Uso UC08</p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| <a id="UC08"></a>UC08 | Login por Biometria                                                |
| Descrição          | Permitir login via impressão digital ou reconhecimento facial.            |
| Ator               | Usuário cadastrado                                                        |
| Pré-condições      | Dispositivo com sensor biométrico, usuário já logado ao menos uma vez.    |
| Ação               | O usuário seleciona "Entrar por biometria" e realiza autenticação.         |
| Fluxo principal    | - O usuário abre o app.<br>- Seleciona “Entrar com biometria”.<br>- Biometria é validada pelo sistema operacional.<br>- O usuário é autenticado. |
| Fluxo alternativo  | - Biometria não reconhecida: sistema oferece login por senha.             |
| Fluxo de exceção   | - Sensor indisponível: app informa erro e redireciona para login comum.   |
| Pós-condições      | Usuário autenticado via biometria ou direcionado para login manual.       |
| Rastreabilidade    | [RF19](../../elicitacao/requisitos_finais.md#RF19)          |
| Data de criação    | 15/05/2025                 |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### UC09 – Baixar Carteirinha

<p align="center">Tabela 11 - Caso de Uso UC09</p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| <a id="UC09"></a>UC09 | Baixar Carteirinha                                                 |
| Descrição          | Permitir download da carteirinha digital para uso offline.                |
| Ator               | Usuário autenticado                                                       |
| Pré-condições      | Conexão com internet e usuário logado.                                    |
| Ação               | O usuário solicita o download da carteirinha.                             |
| Fluxo principal    | - O usuário acessa a seção “Carteirinha”.<br>- Clica em “Baixar”.<br>- O sistema realiza o download.<br>- A carteirinha é salva no dispositivo. |
| Fluxo alternativo  | - Caso já tenha sido baixada, o sistema permite rebaixar.                 |
| Fluxo de exceção   | - Falta de conexão ou falha no armazenamento: erro informado ao usuário.  |
| Pós-condições      | Carteirinha disponível localmente mesmo sem internet.                     |
| Rastreabilidade    | [RF03](../../elicitacao/requisitos_finais.md#RF03)               |
| Data de criação    | 15/05/2025                                                                |

<p align="center">Fonte: Autoria de <a href="https://github.com/redjsun">Yzabella Miranda</a></p>

---

### UC10 – Configurar Notificações

<p align="center">Tabela 12 - Caso de Uso UC10</p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| <a id="UC10"></a>UC10 | Configurar Notificações                                            |
| Descrição          | Permitir ao usuário selecionar tipos e canais de notificações.            |
| Ator               | Usuário autenticado                                                       |
| Pré-condições      | Login realizado com sucesso.                                              |
| Ação               | O usuário acessa as configurações de notificação e define suas preferências. |
| Fluxo principal    | - O usuário acessa “Configurações”.<br>- Escolhe os tipos e canais desejados.<br>- Salva as alterações.<br>- Preferências são persistidas pelo sistema. |
| Fluxo alternativo  | —                                                                         |
| Fluxo de exceção   | - Sistema exibe erro ao tentar salvar.                      |
| Pós-condições      | Preferências de notificação atualizadas.                                  |
| Rastreabilidade    | [RF04.1](../../elicitacao/requisitos_finais.md#RF04.1) e [RF04.9](../../elicitacao/requisitos_finais.md#RF04.9)                  |
| Data de criação    | 15/05/2025                                                                |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### UC11 – Enviar Notificações

<p align="center">Tabela 13 - Caso de Uso UC11</p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| <a id="UC11"></a>UC11 | Enviar Notificações                                                |
| Descrição          | Enviar notificações com base nas preferências do usuário.                 |
| Ator               | Serviços de notificação                                 |
| Pré-condições      | Configurações de notificação existentes e evento ativador.                |
| Ação               | O sistema identifica evento e envia a notificação pelo canal configurado. |
| Fluxo principal    | - Evento ocorre (ex: consulta cancelada).<br>- Preferências são consultadas.<br>- Sistema envia via canal apropriado (e-mail, SMS e/ou notificação do próprio app).<br>- Envio é registrado. |
| Fluxo alternativo  | - Falha de envio: sistema realiza tentativa posterior.                    |
| Fluxo de exceção   | - Falha permanente: log de erro registrado, equipe notificada.            |
| Pós-condições      | Notificação enviada ou tentativa registrada para análise.                 |
| Rastreabilidade    | [RF04.1](../../elicitacao/requisitos_finais.md#RF04.1) e [RF04.9](../../elicitacao/requisitos_finais.md#RF04.9)                                                                      |
| Data de criação    | 15/05/2025                                                                |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

### UC12 – Agendar Consulta ou Exame

<p align="center">Tabela 14 - Caso de Uso UC12</p>

| Campo | Descrição |
|-------|-----------|
| <a id="UC12"></a>UC12 | Agendar Consulta ou Exame |
| Descrição | Permitir ao usuário agendar consultas e exames diretamente pelo aplicativo, com pagamento automático para prestadores da Rede de Atendimento. |
| Ator | Beneficiário (Usuário do plano de saúde) |
| Pré-condições | O usuário deve estar autenticado no sistema. |
| Fluxo principal | 1. Usuário acessa a seção "Agendamentos".<br>2. Usuário seleciona a opção "Novo Agendamento".<br>3. O sistema solicita que o usuário busque por especialidade, profissional ou clínica.<br>4. O usuário realiza a busca e seleciona o profissional e o horário desejado.<br>5. O sistema exibe um resumo do agendamento (data, hora, profissional, local).<br>6. O sistema informa que o pagamento da coparticipação (se aplicável) será processado.<br>7. Usuário confirma os detalhes do agendamento.<br>8. O sistema processa o pagamento automático.<br>9. O sistema confirma o agendamento e envia uma notificação ao usuário. |
| Fluxo alternativo | **A1. Horário tornou-se indisponível:**<br>- Se o horário selecionado for ocupado durante o processo, o sistema exibe a mensagem "Este horário não está mais disponível" e solicita que o usuário escolha um novo horário. |
| Fluxo de exceção | **E1. Falha no processamento do pagamento:**<br>- Sistema exibe mensagem "Falha ao processar o pagamento. Verifique seus dados ou tente outro método.".<br>- O agendamento não é concluído.<br>**E2. Sessão expirada:**<br>- Sistema solicita novo login. |
| Pós-condições | A consulta ou exame está agendada no sistema. O pagamento aplicável foi processado. |
| Rastreabilidade | [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1) |
| Data de criação | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC13 – Cancelar Consulta ou Exame

<p align="center">Tabela 15 - Caso de Uso UC13</p>

| Campo | Descrição |
|-------|-----------|
| <a id="UC13"></a>UC13 | Cancelar Consulta ou Exame |
| Descrição | Permitir ao usuário cancelar uma consulta ou exame agendado diretamente pelo aplicativo, com o devido processamento de estorno de pagamento conforme as regras de negócio. |
| Ator | Beneficiário (Usuário do plano de saúde) |
| Pré-condições | O usuário deve estar autenticado no sistema e ter ao menos uma consulta ou exame futuro agendado. |
| Fluxo principal | 1. Usuário acessa a seção "Meus Agendamentos".<br>2. O sistema exibe a lista de agendamentos futuros.<br>3. Usuário seleciona o agendamento que deseja cancelar.<br>4. O sistema exibe os detalhes do agendamento e a opção "Cancelar Agendamento".<br>5. Usuário confirma o cancelamento.<br>6. O sistema processa o cancelamento e o estorno do pagamento, se aplicável.<br>7. O sistema exibe a mensagem "Agendamento cancelado com sucesso.". |
| Fluxo alternativo | **A1. Cancelamento sujeito a taxas:**<br>- O sistema informa que o cancelamento está sujeito a uma taxa de acordo com a política e pergunta se o usuário deseja continuar. |
| Fluxo de exceção | **E1. Falha ao processar o estorno:**<br>- O sistema exibe a mensagem "O agendamento foi cancelado, mas houve um erro ao processar o estorno. Entre em contato com o suporte." |
| Pós-condições | A consulta ou exame está com o status "Cancelado". O valor correspondente foi estornado, se aplicável. |
| Rastreabilidade | [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2) |
| Data de criação | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC14 – Exibir Valor de Consulta em Clínica

<p align="center">Tabela 16 - Caso de Uso UC14</p>

| Campo | Descrição |
|-------|-----------|
| <a id="UC14"></a>UC14 | Exibir Valor de Consulta em Clínica |
| Descrição | Permitir ao usuário visualizar o valor específico de uma consulta ou procedimento em cada clínica disponível na rede. |
| Ator | Beneficiário (Usuário do plano de saúde) |
| Pré-condições | O usuário deve estar autenticado no sistema. |
| Fluxo principal | 1. Usuário acessa a "Rede de Atendimento".<br>2. Usuário busca por uma especialidade ou procedimento.<br>3. O sistema exibe a lista de clínicas e profissionais que atendem ao critério.<br>4. Para cada resultado da lista, o sistema exibe o valor específico da consulta naquele local. |
| Fluxo alternativo | **A1. Valor não informado:**<br>- Se uma clínica não disponibiliza o valor, o sistema exibe a mensagem "Valor a consultar". |
| Fluxo de exceção | **E1. Falha ao carregar a rede:**<br>- O sistema exibe a mensagem "Erro ao carregar a rede de atendimento. Tente novamente." |
| Pós-condições | O usuário visualizou os valores das consultas nas clínicas de seu interesse. |
| Rastreabilidade | [RF06.1](../../elicitacao/requisitos_finais.md#RF06.1) |
| Data de criação | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC15 – Calcular e Exibir Valor da Coparticipação

<p align="center">Tabela 17 - Caso de Uso UC15</p>

| Campo | Descrição |
|-------|-----------|
| <a id="UC15"></a>UC15 | Calcular e Exibir Valor da Coparticipação |
| Descrição | O sistema deve calcular e exibir o valor da coparticipação do beneficiário para cada consulta e procedimento médico realizado que esteja sujeito a este regime. |
| Ator | Beneficiário (Usuário do plano de saúde) |
| Pré-condições | O usuário deve estar autenticado e visualizando um procedimento sujeito a coparticipação. |
| Fluxo principal | 1. O usuário seleciona um procedimento (ex: durante um agendamento).<br>2. O sistema identifica o procedimento e o plano do beneficiário.<br>3. O sistema acessa as regras de coparticipação do plano.<br>4. O sistema calcula o valor exato ou estimado da coparticipação.<br>5. O sistema exibe o valor calculado para o usuário de forma clara. |
| Fluxo alternativo | **A1. Procedimento isento:**<br>- Se o procedimento for isento, o sistema exibe "Coparticipação: R$ 0,00" ou "Isento". |
| Fluxo de exceção | **E1. Erro no cálculo:**<br>- O sistema exibe a mensagem "Não foi possível calcular a coparticipação. O valor será detalhado no seu extrato." |
| Pós-condições | O usuário foi informado sobre o valor da sua coparticipação para um procedimento. |
| Rastreabilidade | [RF06.2](../../elicitacao/requisitos_finais.md#RF06.2) |
| Data de criação | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC16 – Gerar Demonstrativo de Despesas para IR

<p align="center">Tabela 18 - Caso de Uso UC16</p>

| Campo | Descrição |
|-------|-----------|
| <a id="UC16"></a>UC16 | Gerar Demonstrativo de Despesas para Imposto de Renda |
| Descrição | Permitir ao usuário gerar e baixar o demonstrativo consolidado de despesas médicas de um ano específico para a declaração de Imposto de Renda. |
| Ator | Beneficiário (Usuário do plano de saúde) |
| Pré-condições | O usuário deve estar autenticado no sistema. |
| Fluxo principal | 1. Usuário acessa a seção "Financeiro" ou "Documentos".<br>2. Usuário seleciona a opção "Demonstrativo para Imposto de Renda".<br>3. O sistema solicita ao usuário que selecione o ano-calendário.<br>4. Usuário seleciona o ano e confirma.<br>5. O sistema compila as despesas e gera o documento em PDF.<br>6. O sistema disponibiliza o arquivo para download. |
| Fluxo alternativo | **A1. Nenhuma despesa no período:**<br>- O sistema exibe a mensagem "Nenhuma despesa médica foi encontrada para o ano selecionado.". |
| Fluxo de exceção | **E1. Erro na geração do documento:**<br>- O sistema exibe a mensagem "Ocorreu um erro ao gerar seu demonstrativo. Por favor, tente novamente." |
| Pós-condições | O usuário obteve o arquivo com seu demonstrativo de despesas. |
| Rastreabilidade | [RF06.3](../../elicitacao/requisitos_finais.md#RF06.3) |
| Data de criação | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC17 – Consultar Histórico de Demonstrativos de IR

<p align="center">Tabela 19 - Caso de Uso UC17</p>

| Campo | Descrição |
|-------|-----------|
| <a id="UC17"></a>UC17 | Consultar Histórico de Demonstrativos de IR |
| Descrição | Permitir ao usuário visualizar e baixar demonstrativos de Imposto de Renda que foram gerados anteriormente. |
| Ator | Beneficiário (Usuário do plano de saúde) |
| Pré-condições | O usuário deve estar autenticado no sistema. |
| Fluxo principal | 1. Usuário acessa a seção "Financeiro" ou "Documentos".<br>2. Usuário navega até a área "Histórico de Demonstrativos de IR".<br>3. O sistema exibe a lista de demonstrativos disponíveis, por ano.<br>4. Usuário seleciona um demonstrativo da lista para baixar. |
| Fluxo alternativo | **A1. Histórico vazio:**<br>- O sistema exibe a mensagem "Nenhum demonstrativo foi gerado anteriormente.". |
| Fluxo de exceção | **E1. Falha na recuperação do arquivo:**<br>- O sistema exibe a mensagem "Erro ao carregar o arquivo do demonstrativo." |
| Pós-condições | O usuário visualizou seu histórico e/ou baixou um demonstrativo antigo. |
| Rastreabilidade | [RF06.4](../../elicitacao/requisitos_finais.md#RF06.4) |
| Data de criação | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC18 – Consultar Extrato Financeiro

<p align="center">Tabela 20 - Caso de Uso UC18</p>

| Campo | Descrição |
|-------|-----------|
| <a id="UC18"></a>UC18 | Consultar Extrato Financeiro |
| Descrição | Permitir ao usuário consultar seu extrato financeiro detalhado e atualizado diariamente. |
| Ator | Beneficiário (Usuário do plano de saúde) |
| Pré-condições | O usuário deve estar autenticado no sistema. |
| Fluxo principal | 1. Usuário acessa a seção "Financeiro".<br>2. O sistema exibe o extrato, com as transações mais recentes primeiro.<br>3. Cada item exibe data, descrição da transação e valor.<br>4. O usuário pode aplicar filtros para buscar transações. |
| Fluxo alternativo | **A1. Nenhuma transação no período:**<br>- O sistema exibe a mensagem "Nenhuma transação encontrada para o período selecionado.". |
| Fluxo de exceção | **E1. Falha ao carregar o extrato:**<br>- Sistema exibe mensagem "Erro ao carregar o extrato financeiro." |
| Pós-condições | O usuário visualizou suas movimentações financeiras. |
| Rastreabilidade | [RF06.5](../../elicitacao/requisitos_finais.md#RF06.5) |
| Data de criação | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC19 – Visualizar Painel de Metas de Saúde

<p align="center">Tabela 21 - Caso de Uso UC19</p>

| Campo | Descrição |
|-------|-----------|
| <a id="UC19"></a>UC19 | Visualizar Painel de Metas de Saúde |
| Descrição | Exibir um painel personalizado com metas de saúde e gamificação para incentivar o acompanhamento. |
| Ator | Beneficiário (Usuário do plano de saúde) |
| Pré-condições | O usuário deve estar autenticado no sistema. |
| Fluxo principal | 1. Usuário acessa a seção "Minha Saúde" ou "Painel de Metas".<br>2. O sistema exibe o painel de metas personalizadas.<br>3. O painel mostra as metas, o progresso e elementos de gamificação (pontos, emblemas).<br>4. Usuário pode clicar em uma meta para ver detalhes ou agendar o procedimento correspondente. |
| Fluxo alternativo | **A1. Usuário sem metas definidas:**<br>- O sistema exibe uma mensagem de boas-vindas e incentiva a configuração das primeiras metas. |
| Fluxo de exceção | **E1. Falha ao carregar o painel de metas:**<br>- O sistema exibe a mensagem "Não foi possível carregar suas metas de saúde." |
| Pós-condições | O usuário visualizou seu progresso em relação às suas metas de saúde. |
| Rastreabilidade | [RF17](../../elicitacao/requisitos_finais.md#RF17) |
| Data de criação | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC20 – Cadastrar Titular

<p align="center">Tabela 22 - Caso de Uso UC20</p>

| Campo             | Descrição                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC20"></a>UC20 | Cadastrar Titular                                                                |
| Descrição         | Permitir o cadastro de titulares no sistema, com validação de dados e documentação.                |
| Ator              | Usuário (Titular)                                                                                  |
| Pré-condições     | Usuário autenticado; documentação necessária digitalizada.                                         |
| Fluxo principal   | 1. Usuário acessa a área de cadastro.<br>2. Preenche dados pessoais.<br>3. Anexa documentação.<br>4. Sistema valida informações.<br>5. Cadastro é confirmado. |
| Fluxo alternativo | Dados incompletos: sistema solicita complementação.                                                |
| Fluxo de exceção  | Falha no upload de documentos: sistema exibe erro e orienta tentar novamente.                      |
| Pós-condições     | Titular cadastrado e apto a utilizar o sistema.                                                    |
| Rastreabilidade   | [RF07.1](../../elicitacao/requisitos_finais.md#RF07.1)                                             |
| Data de criação   | 15/06/2025                                                                                         |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### UC21 – Cadastrar Dependente

<p align="center">Tabela 23 - Caso de Uso UC21</p>

| Campo             | Descrição                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC21"></a>UC21 | Cadastrar Dependente                                                             |
| Descrição         | Permitir o cadastro de dependentes vinculados a um titular.                                        |
| Ator              | Usuário (Titular)                                                                                  |
| Pré-condições     | Titular autenticado; documentação do dependente digitalizada.                                      |
| Fluxo principal   | 1. Titular acessa área de dependentes.<br>2. Inicia cadastro.<br>3. Preenche dados do dependente.<br>4. Anexa documentação.<br>5. Sistema valida e confirma cadastro. |
| Fluxo alternativo | Dados incompletos: sistema solicita complementação.                                                |
| Fluxo de exceção  | Falha no upload de documentos: sistema exibe erro e orienta tentar novamente.                      |
| Pós-condições     | Dependente cadastrado e vinculado ao titular.                                                      |
| Rastreabilidade   | [RF07.2](../../elicitacao/requisitos_finais.md#RF07.2)                                             |
| Data de criação   | 15/06/2025                                                                                         |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### UC22 – Cadastrar Optante

<p align="center">Tabela 24 - Caso de Uso UC22</p>

| Campo             | Descrição                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC22"></a>UC22 | Cadastrar Optante                                                                |
| Descrição         | Permitir o cadastro de optantes no sistema, com validação de dados e documentação.                 |
| Ator              | Usuário (Optante)                                                                                  |
| Pré-condições     | Usuário autenticado; documentação necessária digitalizada.                                         |
| Fluxo principal   | 1. Usuário acessa área de cadastro.<br>2. Seleciona opção "Optante".<br>3. Preenche dados.<br>4. Anexa documentação.<br>5. Sistema valida e confirma cadastro. |
| Fluxo alternativo | Dados incompletos: sistema solicita complementação.                                                |
| Fluxo de exceção  | Falha no upload de documentos: sistema exibe erro e orienta tentar novamente.                      |
| Pós-condições     | Optante cadastrado e apto a utilizar o sistema.                                                    |
| Rastreabilidade   | [RF07.3](../../elicitacao/requisitos_finais.md#RF07.3)                                             |
| Data de criação   | 15/06/2025                                                                                         |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### UC23 – Validar Documentos no Cadastro

<p align="center">Tabela 25 - Caso de Uso UC23</p>

| Campo             | Descrição                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC23"></a>UC23 | Validar Documentos no Cadastro                                                   |
| Descrição         | Validar os documentos apresentados durante o cadastro de titulares, dependentes e optantes.        |
| Ator              | Sistema                                                                                            |
| Pré-condições     | Documentos anexados no processo de cadastro.                                                       |
| Fluxo principal   | 1. Sistema recebe documentos.<br>2. Realiza validação automática.<br>3. Informa resultado ao usuário. |
| Fluxo alternativo | Documento ilegível: solicita novo envio.                                                           |
| Fluxo de exceção  | Falha técnica na validação: sistema exibe erro e orienta tentar novamente.                        |
| Pós-condições     | Documentos validados ou solicitação de reenvio.                                                    |
| Rastreabilidade   | [RF07.4](../../elicitacao/requisitos_finais.md#RF07.4)                                             |
| Data de criação   | 15/06/2025                                                                                         |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### UC24 – Verificar Elegibilidade no Cadastro

<p align="center">Tabela 26 - Caso de Uso UC24</p>

| Campo             | Descrição                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC24"></a>UC24 | Verificar Elegibilidade no Cadastro                                              |
| Descrição         | Verificar a elegibilidade dos titulares, dependentes e optantes durante o processo de cadastro.    |
| Ator              | Sistema                                                                                            |
| Pré-condições     | Dados e documentos enviados no cadastro.                                                           |
| Fluxo principal   | 1. Sistema recebe dados.<br>2. Verifica critérios de elegibilidade.<br>3. Informa resultado ao usuário. |
| Fluxo alternativo | Dados inconsistentes: solicita correção.                                                           |
| Fluxo de exceção  | Falha técnica na verificação: sistema exibe erro e orienta tentar novamente.                       |
| Pós-condições     | Cadastro aprovado ou pendente de regularização.                                                    |
| Rastreabilidade   | [RF07.5](../../elicitacao/requisitos_finais.md#RF07.5)                                             |
| Data de criação   | 15/06/2025                                                                                         |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### UC25 – Verificar Procedimentos para Autorização

<p align="center">Tabela 27 - Caso de Uso UC25</p>

| Campo             | Descrição                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC25"></a>UC25 | Verificar Procedimentos para Autorização                                         |
| Descrição         | Verificar se procedimentos estão na TABGDFSAÚDE, atendem às DUT, carência ou exclusões, exigindo solicitação médica e análise técnica para autorizações prévias. |
| Ator              | Titular / Profissional de saúde / Analista técnico                                                 |
| Pré-condições     | Procedimento solicitado e dados médicos anexados.                                                  |
| Fluxo principal   | 1. Usuário submete solicitação.<br>2. Sistema verifica TABGDFSAÚDE e DUT.<br>3. Verifica carência e exclusões.<br>4. Solicita análise técnica se necessário.<br>5. Informa resultado ao usuário. |
| Fluxo alternativo | Procedimento coberto e sem exigência de análise: autorização automática.                           |
| Fluxo de exceção  | Solicitação incompleta: sistema solicita complementação.<br>Falha técnica: exibe erro e orienta tentar novamente. |
| Pós-condições     | Procedimento autorizado ou negado com justificativa técnica.                                       |
| Rastreabilidade   | [RF08](../../elicitacao/requisitos_finais.md#RF08)                                                 |
| Data de criação   | 15/06/2025                                                                                         |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### UC26 – Registrar Denúncia contra Profissional

<p align="center">Tabela 28 - Caso de Uso UC26</p>

| Campo             | Descrição                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC26"></a>UC26 | Registrar Denúncia contra Profissional                                           |
| Descrição         | Permitir ao usuário registrar denúncias de condutas inadequadas por parte de profissionais da rede credenciada. |
| Ator              | Usuário (Titular, Dependente ou Optante)                                                           |
| Pré-condições     | Usuário autenticado; denúncia relacionada a profissional da rede credenciada.                      |
| Fluxo principal   | 1. Usuário acessa área de denúncias.<br>2. Preenche formulário com detalhes.<br>3. Anexa evidências, se houver.<br>4. Envia denúncia.<br>5. Sistema registra e encaminha para análise. |
| Fluxo alternativo | Usuário não anexa evidências: sistema permite envio apenas com descrição.                          |
| Fluxo de exceção  | Falha no envio: sistema exibe erro e orienta tentar novamente.                                     |
| Pós-condições     | Denúncia registrada e encaminhada para análise.                                                    |
| Rastreabilidade   | [RF18](../../elicitacao/requisitos_finais.md#RF18)                                                 |
| Data de criação   | 15/06/2025                                                                                         |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### UC27 – Visualizar Histórico de Consultas Realizadas

<p align="center">Tabela 29 - Caso de Uso UC27</p>

| Campo              | Descrição                                                                                                                                       |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC27"></a>UC27 | Visualizar Histórico de Consultas Realizadas                                                                                   |
| Descrição          | Permitir ao usuário visualizar a lista de todas as consultas realizadas, com data, profissional e especialidade.                               |
| Ator               | Usuário cadastrado no plano de saúde GDF Saúde                                                           |
| Pré-condições      | O usuário deve estar autenticado no sistema.                                                             |
| Ação               | O usuário acessa a seção "Histórico de Consultas".                                                      |
| Fluxo principal    | 1. Usuário faz login no sistema.<br>2. Usuário navega até a seção "Histórico de Consultas".<br>3. Sistema recupera e exibe a lista de consultas realizadas, ordenadas da mais recente para a mais antiga.<br>4. Cada item exibe data, profissional e especialidade.<br>5. Usuário pode buscar ou filtrar consultas por período, profissional ou especialidade.<br>6. Usuário seleciona uma consulta para ver detalhes.<br>7. Sistema exibe detalhes completos da consulta selecionada.<br>8. Usuário retorna à lista ou encerra a navegação. |
| Fluxo alternativo  | A1. Se não houver consultas registradas:<br>  - Sistema exibe mensagem "Nenhuma consulta encontrada".<br>  - Usuário pode retornar ao menu principal. |
| Fluxo de exceção   | E1. Falha na recuperação dos dados:<br>  - Sistema exibe mensagem "Erro ao carregar histórico de consultas".<br>  - Usuário pode tentar novamente ou contatar o suporte.<br>E2. Sessão expirada:<br>  - Sistema solicita novo login. |
| Pós-condições      | O usuário visualizou seu histórico de consultas.                                                         |
| Rastreabilidade    | [RF09.1](../../elicitacao/requisitos_finais.md#RF09.1)                                                  |
| Data de criação    | 15/05/2025                                                                                               |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

### UC28 – Visualizar Histórico de Exames Realizados

<p align="center">Tabela 30 - Caso de Uso UC28</p>

| Campo              | Descrição                                                                                                  |
|--------------------|----------------------------------------------------------------------------------------------------------|
| <a id="UC28"></a>UC28 | Visualizar Histórico de Exames Realizados                                                |
| Descrição          | Permitir ao usuário visualizar a lista de todos os exames realizados, com nome do exame e data.           |
| Ator               | Usuário cadastrado no plano de saúde GDF Saúde                                                           |
| Pré-condições      | O usuário deve estar autenticado no sistema.                                                             |
| Ação               | O usuário acessa a seção "Histórico de Exames".                                                          |
| Fluxo principal    | 1. Usuário faz login.<br>2. Acessa "Histórico de Exames".<br>3. Sistema exibe lista de exames realizados.<br>4. Cada item mostra nome do exame e data.<br>5. Usuário pode buscar ou filtrar exames.<br>6. Usuário seleciona exame para ver detalhes.<br>7. Sistema exibe detalhes do exame.<br>8. Usuário retorna à lista ou encerra. |
| Fluxo alternativo  | A1. Se não houver exames:<br>  - Sistema exibe "Nenhum exame encontrado".<br>  - Usuário pode retornar ao menu principal. |
| Fluxo de exceção   | E1. Falha ao carregar exames:<br>  - Sistema exibe "Erro ao carregar exames".<br>  - Usuário pode tentar novamente ou contatar suporte.<br>E2. Sessão expirada:<br>  - Sistema solicita novo login. |
| Pós-condições      | O usuário visualizou seu histórico de exames.                                                            |
| Rastreabilidade    | [RF09.2](../../elicitacao/requisitos_finais.md#RF09.2)                                                  |
| Data de criação    | 15/05/2025                                                                                               |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

### UC29 – Visualizar Resultados de Exames Laboratoriais

<p align="center">Tabela 31 - Caso de Uso UC29</p>

| Campo              | Descrição                                                                                                  |
|--------------------|----------------------------------------------------------------------------------------------------------|
| <a id="UC29"></a>UC29 | Visualizar Resultados de Exames Laboratoriais                                            |
| Descrição          | Permitir ao usuário acessar e visualizar os resultados de exames laboratoriais realizados.                |
| Ator               | Usuário cadastrado no plano de saúde GDF Saúde                                                           |
| Pré-condições      | O usuário deve estar autenticado e ter exames laboratoriais com resultado disponível.                     |
| Ação               | O usuário acessa a seção "Histórico de Exames" e seleciona um exame com resultado.                       |
| Fluxo principal    | 1. Usuário faz login.<br>2. Acessa "Histórico de Exames".<br>3. Sistema exibe lista de exames laboratoriais.<br>4. Exames com resultado disponível exibem botão "Ver Resultado".<br>5. Usuário clica para visualizar ou baixar o resultado.<br>6. Sistema exibe ou permite download do resultado.<br>7. Usuário retorna à lista ou encerra. |
| Fluxo alternativo  | A1. Se não houver resultados disponíveis:<br>  - Sistema exibe "Nenhum resultado disponível".<br>  - Usuário pode retornar ao menu principal. |
| Fluxo de exceção   | E1. Falha ao carregar resultados:<br>  - Sistema exibe "Erro ao carregar resultados".<br>  - Usuário pode tentar novamente ou contatar suporte.<br>E2. Arquivo corrompido:<br>  - Sistema exibe mensagem de erro e orienta novo download.<br>E3. Sessão expirada:<br>  - Sistema solicita novo login. |
| Pós-condições      | O usuário visualizou o resultado do exame laboratorial.                                                  |
| Rastreabilidade    | [RF09.3](../../elicitacao/requisitos_finais.md#RF09.3)                                                  |
| Data de criação    | 15/05/2025                                                                                               |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

### UC30 – Visualizar Histórico de Coparticipações

<p align="center">Tabela 32 - Caso de Uso UC30</p>

| Campo              | Descrição                                                                                                  |
|--------------------|----------------------------------------------------------------------------------------------------------|
| <a id="UC30"></a>UC30 | Visualizar Histórico de Coparticipações                                                  |
| Descrição          | Permitir ao usuário acessar o histórico detalhado de cobranças de coparticipação.                         |
| Ator               | Usuário cadastrado no plano de saúde GDF Saúde                                                           |
| Pré-condições      | O usuário deve estar autenticado no sistema.                                                             |
| Ação               | O usuário acessa a seção "Histórico de Coparticipações" ou "Financeiro".                                 |
| Fluxo principal    | 1. Usuário faz login.<br>2. Acessa "Histórico de Coparticipações".<br>3. Sistema exibe lista de cobranças de coparticipação.<br>4. Cada item mostra serviço, data e valor cobrado.<br>5. Usuário pode buscar ou filtrar cobranças.<br>6. Usuário seleciona uma cobrança para ver detalhes.<br>7. Sistema exibe detalhes completos.<br>8. Usuário retorna à lista ou encerra. |
| Fluxo alternativo  | A1. Se não houver cobranças:<br>  - Sistema exibe "Nenhuma coparticipação encontrada".<br>  - Usuário pode retornar ao menu principal. |
| Fluxo de exceção   | E1. Falha ao carregar histórico:<br>  - Sistema exibe "Erro ao carregar histórico de coparticipações".<br>  - Usuário pode tentar novamente ou contatar suporte.<br>E2. Sessão expirada:<br>  - Sistema solicita novo login. |
| Pós-condições      | O usuário visualizou seu histórico de coparticipações.                                                   |
| Rastreabilidade    | [RF09.4](../../elicitacao/requisitos_finais.md#RF09.4)                                                  |
| Data de criação    | 15/05/2025                                                                                               |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

### UC31 – Favoritar Horários de Consulta

<p align="center">Tabela 33 - Caso de Uso UC31</p>

| Campo              | Descrição                                                                                                  |
|--------------------|----------------------------------------------------------------------------------------------------------|
| <a id="UC31"></a>UC31 | Favoritar Horários de Consulta                                                          |
| Descrição          | Permitir ao usuário marcar horários preferidos para agendamentos futuros.                                |
| Ator               | Usuário cadastrado no plano de saúde GDF Saúde                                                           |
| Pré-condições      | O sistema deve exibir horários disponíveis para consulta.                                                |
| Ação               | O usuário acessa a seção de agendamento, seleciona horários para favoritar e confirma a ação.            |
| Fluxo principal    | 1. Usuário faz login.<br>2. Acessa a seção de agendamento.<br>3. Sistema exibe horários disponíveis.<br>4. Usuário seleciona um ou mais horários para favoritar.<br>5. Usuário confirma a ação.<br>6. Sistema salva horários favoritos no perfil do usuário.<br>7. Sistema exibe confirmação de sucesso.<br>8. Usuário pode visualizar ou editar favoritos. |
| Fluxo alternativo  | A1. Horário indisponível:<br>  - Sistema notifica "Horário não disponível" e remove da seleção.<br>  - Usuário pode escolher outro horário.<br>A2. Limite de favoritos atingido:<br>  - Sistema informa o limite e impede seleção adicional. |
| Fluxo de exceção   | E1. Erro ao salvar favoritos:<br>  - Sistema exibe "Erro ao salvar horário favorito" e oferece tentar novamente.<br>E2. Sessão expirada:<br>  - Sistema solicita novo login. |
| Pós-condições      | Horários favoritados salvos no perfil do usuário.                                                        |
| Rastreabilidade    | [RF10](../../elicitacao/requisitos_finais.md#RF10)                                                      |
| Data de criação    | 15/05/2025                                                                                               |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

### UC32 – Solicitar Reembolso de Cobrança Indevida

<p align="center">Tabela 34 - Caso de Uso UC32</p>

| Campo              | Descrição                                                                                                  |
|--------------------|----------------------------------------------------------------------------------------------------------|
| <a id="UC32"></a>UC32 | Solicitar Reembolso de Cobrança Indevida                                                |
| Descrição          | Permitir ao usuário solicitar reembolso de valores cobrados indevidamente, fornecendo justificativa e documentos. |
| Ator               | Usuário cadastrado no plano de saúde GDF Saúde                                                           |
| Pré-condições      | 1. O usuário deve ter uma cobrança registrada.<br>2. Solicitação feita em até 30 dias da cobrança.        |
| Ação               | O usuário acessa a seção de reembolso, seleciona a cobrança, preenche justificativa, anexa documentos e envia. |
| Fluxo principal    | 1. Usuário faz login.<br>2. Acessa a seção de reembolso.<br>3. Sistema exibe lista de cobranças.<br>4. Usuário seleciona cobrança indevida.<br>5. Sistema apresenta formulário para justificativa e anexos.<br>6. Usuário preenche justificativa e anexa documentos.<br>7. Usuário envia solicitação.<br>8. Sistema valida dados e envia solicitação.<br>9. Sistema notifica usuário sobre o recebimento.<br>10. Usuário pode acompanhar o status da solicitação. |
| Fluxo alternativo  | A1. Documentação incompleta:<br>  - Sistema solicita arquivos faltantes.<br>  - Usuário anexa documentos adicionais.<br>  - Sistema retoma validação. |
| Fluxo de exceção   | E1. Erro técnico ao enviar solicitação:<br>  - Sistema exibe "Erro ao enviar solicitação" e oferece tentar novamente.<br>E2. Prazo excedido:<br>  - Sistema informa que o prazo para solicitação expirou e impede envio.<br>E3. Sessão expirada:<br>  - Sistema solicita novo login. |
| Pós-condições      | Solicitação registrada e enviada para análise.                                                           |
| Rastreabilidade    | [RF20](../../elicitacao/requisitos_finais.md#RF20)                                                      |
| Data de criação    | 15/05/2025                                                                                               |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

### UC33 – Enviar Feedback de Atendimento

<p align="center">Tabela 35 - Caso de Uso UC33</p>

| Campo | Descrição | 
|-------|-----------|
| <a id="UC33"></a>UC33 | Enviar Feedback de Atendimento |
| Descrição | Permitir que o usuário envie feedback sobre o atendimento de uma consulta realizada. |
| Ator | Usuário cadastrado no GovBR |
| Pré-condições | 1. Usuário autenticado <br> 2. Consulta já realizada <br> 3. Conexão com a internet ativa |
| Ação | Usuário acessa o canal de feedback, seleciona uma consulta anterior e preenche o formulário com a avaliação. |
| Fluxo principal | - Usuário acessa a área de feedback <br> - Seleciona uma consulta <br> - Preenche formulário de avaliação <br> - Envia feedback |
| Fluxo alternativo | - Consulta ainda não realizada: sistema bloqueia envio <br> - Avaliação incompleta: sistema solicita preenchimento obrigatório |
| Fluxo de exceção | - Falha de rede durante envio <br> - Erro de autenticação do usuário |
| Pós-condições | Feedback registrado e vinculado à consulta avaliada |
| Rastreabilidade | [RF11](../../elicitacao/requisitos_finais.md#RF11) |
| Data de criação | 17/05/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### UC34 – Apresentar Seção “Novidades” no Menu Principal

<p align="center">Tabela 36 - Caso de Uso UC34</p>

| Campo | Descrição |
|-------|-----------|
| <a id="UC34"></a>UC34 | Apresentar Seção “Novidades” no Menu Principal |
| Descrição | Permitir que o usuário visualize no menu principal uma nova seção chamada “Novidades”. |
| Ator | Usuário do plano de saúde <br> Sistema do GDF Saúde |
| Pré-condições | 1. Aplicativo iniciado <br> 2. Conexão com a internet ativada |
| Ação | Sistema exibe a seção "Novidades" no menu principal. |
| Fluxo principal | - Sistema atualiza menu <br> - Seção “Novidades” aparece visível para o usuário |
| Fluxo alternativo | - Menu não atualizado <br> - Seção não aparece até próxima atualização |
| Fluxo de exceção | - Falha na exibição do menu <br> - Problema de renderização no aplicativo |
| Pós-condições | Usuário pode acessar a área de novidades a partir do menu principal |
| Rastreabilidade | [RF12.1](../../elicitacao/requisitos_finais.md#RF12.1) |
| Data de criação | 20/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### UC35 – Exibir Lista de Funcionalidades com Título, Descrição e Data

<p align="center">Tabela 37 - Caso de Uso UC35</p>

| Campo | Descrição |
|-------|-----------|
| <a id="UC35"></a>UC35 | Exibir Lista de Funcionalidades com Título, Descrição e Data |
| Descrição | Permitir que o usuário visualize uma lista contendo as novas funcionalidades, incluindo título, descrição e data de lançamento. |
| Ator | Usuário do plano de saúde <br> Sistema do GDF Saúde |
| Pré-condições | 1. Aplicativo iniciado <br> 2. Conexão com a internet ativada |
| Ação | Sistema apresenta uma lista com as informações das novas funcionalidades |
| Fluxo principal | - Sistema busca e exibe as funcionalidades na tela de novidades |
| Fluxo alternativo | - Lista vazia ou sem novas entradas <br> - Exibe mensagem de "nenhuma novidade disponível" |
| Fluxo de exceção | - Falha ao carregar dados do servidor |
| Pós-condições | Usuário visualiza a lista informativa de funcionalidades lançadas |
| Rastreabilidade | [RF12.2](../../elicitacao/requisitos_finais.md#RF12.2) |
| Data de criação | 20/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### UC36 – Destacar Funcionalidades com Marcador “Novo”
<p align="center">Tabela 38 - Caso de Uso 36 </p>

| Campo | Descrição |
|--------------------|-------------------------------------------------------------|
| UC34.3 | Destacar Funcionalidades com Marcador “Novo” |
| Descrição | Destacar funcionalidades lançadas recentemente com um marcador visual “Novo” por um período configurável. |
| Ator | - Usuário do plano de saúde <br> - Sistema do GDF Saúde |
| Pré-condições | 1. Aplicativo iniciado <br> 2. Conexão com a internet ativada |
| Ação | Sistema exibe marcador “Novo” para funcionalidades recentes |
| Fluxo principal | - Funcionalidade foi lançada nos últimos X dias <br> - Sistema adiciona marcador visual “Novo” |
| Fluxo alternativo | - Funcionalidade foi lançada há mais de X dias <br> - Nenhum marcador é exibido |
| Fluxo de exceção | - Erro de cálculo no período do marcador |
| Pós-condições | Funcionalidades novas são facilmente identificáveis pelo usuário |
| Rastreabilidade | [RF12.3](../../elicitacao/requisitos_finais.md#RF12.3) |
| Data de criação | 20/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### UC37 – Exibir Pop-ups com Novidades Após Atualização
<p align="center">Tabela 39 - Caso de Uso 37 </p>

| Campo | Descrição |
|--------------------|-------------------------------------------------------------|
| UC34.4 | Exibir Pop-ups com Novidades Após Atualização |
| Descrição | Exibir automaticamente pop-ups informativos com as principais novidades sempre que o aplicativo for atualizado. |
| Ator | - Usuário do plano de saúde <br> - Sistema do GDF Saúde |
| Pré-condições | 1. Aplicativo recém-atualizado <br> 2. Conexão com a internet ativada |
| Ação | Sistema apresenta pop-up informativo ao iniciar o app após atualização |
| Fluxo principal | - Sistema detecta atualização <br> - Pop-up com resumo das novidades é exibido |
| Fluxo alternativo | - Pop-up já exibido anteriormente <br> - Sistema não exibe novamente |
| Fluxo de exceção | - Falha na verificação de versão ou na exibição do pop-up |
| Pós-condições | Usuário toma conhecimento das principais mudanças |
| Rastreabilidade | [RF12.4](../../elicitacao/requisitos_finais.md#RF12.4) |
| Data de criação | 20/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### UC38 – Ver Descrição Detalhada de Funcionalidade
<p align="center">Tabela 40 - Caso de Uso 38 </p>

| Campo | Descrição |
|--------------------|-------------------------------------------------------------|
| UC34.5 | Ver Descrição Detalhada de Funcionalidade |
| Descrição | Permitir que o usuário acesse uma descrição detalhada de uma nova funcionalidade ao tocá-la na lista de novidades. |
| Ator | - Usuário do plano de saúde <br> - Sistema do GDF Saúde |
| Pré-condições | 1. Aplicativo iniciado <br> 2. Conexão com a internet ativada |
| Ação | Sistema carrega e exibe os detalhes da funcionalidade selecionada |
| Fluxo principal | - Usuário toca em uma funcionalidade <br> - Detalhes completos são exibidos |
| Fluxo alternativo | - Nenhuma funcionalidade tocada <br> - Nenhuma ação ocorre |
| Fluxo de exceção | - Falha no carregamento dos dados detalhados |
| Pós-condições | Usuário visualiza informações completas da funcionalidade selecionada |
| Rastreabilidade | [RF12.5](../../elicitacao/requisitos_finais.md#RF12.5) |
| Data de criação | 20/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### UC39 – Ordenar Novidades por Data
<p align="center">Tabela 41 - Caso de Uso 39 </p>

| Campo | Descrição |
|--------------------|-------------------------------------------------------------|
| UC34.6 | Ordenar Novidades por Data |
| Descrição | Permitir que o usuário ordene as novidades exibidas por "mais recente" ou "mais antigo". |
| Ator | - Usuário do plano de saúde <br> - Sistema do GDF Saúde |
| Pré-condições | 1. Aplicativo iniciado <br> 2. Conexão com a internet ativada |
| Ação | Sistema exibe opção de ordenação e reorganiza a lista conforme escolha do usuário |
| Fluxo principal | - Usuário seleciona critério de ordenação <br> - Sistema aplica filtro e exibe resultado |
| Fluxo alternativo | - Ordenação não alterada <br> - Lista permanece na ordem padrão |
| Fluxo de exceção | - Falha na ordenação ou erro na interface de filtro |
| Pós-condições | Usuário visualiza as novidades ordenadas conforme preferência |
| Rastreabilidade | [RF12.6](../../elicitacao/requisitos_finais.md#RF12.6) |
| Data de criação | 20/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>


---

### UC40 – Fazer login via GovBR
<p align="center">Tabela 42 - Caso de Uso 40 </p>

| Campo | Descrição | 
|-----------------------|-------------------------------------------------------------------------------| 
| <a id="UC35"></a>UC35 | Fazer login via GovBR |
| Descrição | Permitir que o usuário acesse o app mediante autenticação GovBR. |
| Ator | Usuário cadastrado no GovBR |
| Pré-condições | App instalado, conexão à internet e conta GovBR ativa. |
| Ação | O usuário seleciona "Login com GovBR" e realiza a autenticação. |
| Fluxo principal | 1. Usuário acessa a tela de login.<br>2. Seleciona "Autenticar com GovBR".<br>3. Sistema redireciona para a plataforma GovBR.<br>4. Usuário insere credenciais GovBR.<br>5. Sistema valida e autentica o usuário. |
| Fluxo alternativo | Credenciais inválidas: sistema exibe mensagem de erro e sugere recuperação de senha. |
| Fluxo de exceção | Falha na conexão com GovBR: sistema informa indisponibilidade temporária. |
| Pós-condições | Usuário autenticado e com acesso às funcionalidades do app. |
| Rastreabilidade | [RF22](../../elicitacao/elicitacao.md#RF22) |
| Data de criação | 17/05/2025 | 

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

---

### UC41 – Consultar rede odontológica
<p align="center">Tabela 43 - Caso de Uso 41 </p>

| Campo | Descrição |
|-----------------------|-------------------------------------------------------------------------------|
| <a id="UC36"></a>UC36 | Consultar rede odontológica |
| Descrição | Permitir ao usuário buscar clínicas odontológicas cadastradas. |
| Ator | Usuário autenticado |
| Pré-condições | Usuário estar logado via GovBR. |
| Ação | O usuário acessa a funcionalidade de busca e insere critérios de pesquisa. |
| Fluxo principal | 1. Usuário acessa "Buscar rede odontológica".<br>2. Insere filtros (ex.: especialidade, bairro).<br>3. Sistema exibe lista de clínicas disponíveis. |
| Fluxo alternativo | Nenhum resultado: sistema sugere ampliar critérios de busca. |
| Fluxo de exceção | Falha na conexão: sistema notifica "Tente novamente mais tarde". |
| Pós-condições | Usuário visualiza clínicas odontológicas compatíveis. |
| Rastreabilidade | [RF13](../../elicitacao/elicitacao.md#RF13) |
| Data de criação | 17/05/2025 | 
---
<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

### UC42 – Apresentar Novas Clínicas Próximas
<p align="center">Tabela 44 - Caso de Uso 42 </p>

| Campo | Descrição |
|---|---|
| <a id="UC37.1"></a>UC37| Apresentar Novas Clínicas Próximas|
| Descrição | Exibir novas clínicas que surgiram na região do usuário, com base em sua localização. |
| Ator | Usuário autenticado |
| Pré-condições | Usuário logado e permissão para uso de geolocalização. |
| Ação| O sistema detecta a localização do usuário e apresenta uma lista de novas clínicas na proximidade. |
| Fluxo principal | 1. Usuário acessa a opção "Novas Unidades de Saúde Próximas".<br>2. Sistema detecta a localização automática do usuário.<br>3. Exibe uma lista de novas clínicas em ordem de proximidade. |
| Fluxo alternativo | Localização automática falha: usuário insere o endereço manualmente. |
| Fluxo de exceção | Geolocalização desativada: sistema solicita ativação ou entrada manual. |
| Pós-condições | Usuário visualiza novas clínicas próximas ou resultados conforme o endereço inserido. |
| Rastreabilidade | [RF14.1](../../elicitacao/elicitacao.md#RF14.1) |
| Data de criação | 20/06/2025 |

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>
---

### UC43 – Apresentar Clínicas Próximas
<p align="center">Tabela 45 - Caso de Uso 43 </p>

| Campo | Descrição |
|---|---|
| <a id="UC38"></a>UC38| Apresentar Clínicas Próximas |
| Descrição| Exibir clínicas existentes na região do usuário, com base em sua localização. |
| Ator | Usuário autenticado |
| Pré-condições | Usuário logado e permissão para uso de geolocalização. |
| Ação| O sistema detecta a localização do usuário e apresenta uma lista de clínicas próximas. |
| Fluxo principal | 1. Usuário acessa a opção "Buscar Unidades de Saúde Próximas".<br>2. Sistema detecta a localização automática do usuário.<br>3. Exibe uma lista de clínicas em ordem de proximidade. |
| Fluxo alternativo | Localização automática falha: usuário insere o endereço manualmente. |
| Fluxo de exceção | Geolocalização desativada: sistema solicita ativação ou entrada manual. |
| Pós-condições | Usuário visualiza clínicas próximas ou resultados conforme o endereço inserido. |
| Rastreabilidade | [RF14.2](../../elicitacao/elicitacao.md#RF14.2) |
|Data de criação | 20/06/2025 |

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

---

### UC44 – Baixar comprovante de agendamento
<p align="center">Tabela 46 - Caso de Uso 44 </p>

| Campo | Descrição |
|-----------------------|-------------------------------------------------------------------------------|
| <a id="UC38"></a>UC38 | Baixar comprovante de agendamento |
| Descrição | Permitir ao usuário baixar comprovantes de agendamentos realizados. |
| Ator | Usuário autenticado com agendamento ativo. |
| Pré-condições | Usuário logado e agendamento confirmado. |
| Ação | O usuário acessa a lista de agendamentos e seleciona "Baixar comprovante". |
| Fluxo principal | 1. Usuário acessa "Comprovantes de agendamento".<br>2. Seleciona o agendamento desejado.<br>3. Clica em "Baixar" e o sistema gera um PDF. |
| Fluxo alternativo | Comprovante expirado: sistema notifica "Agendamento não encontrado". |
| Fluxo de exceção | Falha no servidor: sistema exibe mensagem de erro. |
| Pós-condições | Comprovante é salvo no dispositivo do usuário. |
| Rastreabilidade | [RF15](../../elicitacao/elicitacao.md#RF15) |
| Data de criação | 17/05/2025 |

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>



---

## Referência Bibliográfica

DevMedia. *O que é UML e Diagramas de Caso de Uso: Introdução Prática à UML*. 2012. Disponível em: https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408. Acessado em 25 mai. de 2025


Lucid Software Português. *Tutorial de Caso de Uso UML*. Youtube, 25 abr. 2019. Disponível em: https://youtu.be/ab6eDdwS3rA?si=rWAOOakqyrtqkKng. Accesso em 25 mai. 2025.


---

## Histórico de Versões

| Versão | Data       | Descrição            | Autor(es)                                       | Revisor(es)                                 |
| ------ | ---------- | -------------------- | ----------------------------------------------- | ------------------------------------------- |
| `1.0` | 15/05/2025  | Criação do documento | [Yzabella Miranda](https://github.com/redjsun) e [Isaque Camargos](https://github.com/isaqzin)| [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) |
| `1.1` | 15/05/2025  | Adição dos casos de usos referentes aos requisitos funcionais 3, 4 e 19 e dos requisitos não funcionais 4, 5 e 6 | [Isaque Camargos](https://github.com/isaqzin) | [Lucas Alves](https://github.com/LucasAlves71) |
|`1.2`  | 15/05/2025  | Adição dos casos de usos referentes aos requisitos funcionais 9, 10 e 20 e dos requisitos não funcionais 11 e 12 | [Matheus de Alcântara](https://github.com/matheusdealcantara) |[Isaque Camargos](https://github.com/isaqzin) |
|`1.3`  | 17/05/2025  | Adição dos casos de usos referentes aos requisitos funcionais 1, 2 e 21 e dos requisitos não funcionais 1, 2 e 3 | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) | [Kaleb Macedo](https://github.com/kalebmacedo) |
|`1.4`  | 17/05/2025  | Adição dos casos de usos referentes aos requisitos funcionais 5, 6 e 17 e dos requisitos não funcionais 7 e 8 | [Kaleb Macedo](https://github.com/kalebmacedo) | [Matheus de Alcântara](https://github.com/matheusdealcantara) |
|`1.5`  | 17/05/2025  | Adição dos casos de usos referentes aos requisitos funcionais 7, 8 e 18 e dos requisitos não funcionais 9 e 10 | [Lucas Alves](https://github.com/LucasAlves71) | [Yzabella Miranda](https://github.com/redjsun) |
|`1.6`  | 17/05/2025  | Adição dos casos de usos referentes aos requisitos funcionais 11 e 12 e dos requisitos não funcionais 13 e 14 | [Othavio Bolzan](https://github.com/bolzanMGB) | [Kaleb Macedo](https://github.com/kalebmacedo) |
|`1.7`  | 17/05/2025  | Adição dos casos de usos referentes aos requisitos funcionais 13, 14 e 15 e dos requisitos não funcionais 15 | [Yzabella Miranda](https://github.com/redjsun) |[Othavio Bolzan](https://github.com/bolzanMGB) |
|`1.8`  | 08/06/2025  | Adição de ancoras | [Isaque Camargos](https://github.com/isaqzin) | [Lucas Alves](https://github.com/LucasAlves71) |
|`1.9`  | 17/05/2025  | Retirando o diagrama de caso de uso referente aos requisitos funcionais da Ana| [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) | [Kaleb Macedo](https://github.com/kalebmacedo) |
|`2.0`  | 11/06/2025  | Corrigi os meus cenários, retirando as especificações e diagrama dos casos de uso de requisitos não funcionais e criando casos de uso para os requisitos: RF01.1, RF01.2, RF01.3, RF01.4, RF01.5, RF02.1, RF02.2 e RF02.3 .  | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) | [Matheus de Alcântara](https://github.com/matheusdealcantara) |
|`2.1`  | 20/06/2025  | Criando casos de uso para os requisitos: RF12.1, RF12.2, RF12.3, RF12.4, RF12.5, RF12.6 | [Othavio Bolzan](https://github.com/bolzanMGB) | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) | 
|`2.2`  | 21/06/2025  | Adição dos meus casos de uso certos, além da enumeração e padronização do documento  | [Lucas Alves](https://github.com/LucasAlves71) | [Kaleb Macedo](https://github.com/kalebmacedo) |
|`2.3`  | 21/06/2025  | Renomeação dos casos de uso  | [Othavio Bolzan](https://github.com/bolzanMGB) | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) |
|`2.4`  | 22/06/2025  | Criação de casos de uso pros requisitos RF22, RF14.1 e RF14.2  | [Yzabella Miranda](https://github.com/redjsun) | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) |



