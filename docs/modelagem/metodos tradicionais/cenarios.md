# Cenário

## Introdução 

Este documento reúne cenários de uso que ilustram como os usuários interagem com o aplicativo GDF Saúde. Os cenários foram elaborados com base em requisitos funcionais e não funcionais, abordando situações reais de uso, recursos envolvidos, exceções e restrições, a fim de apoiar o desenvolvimento e validação do sistema. 

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
                <td><a href="https://github.com/isaqzin">Isaque Camargos</a></td>
                <td>Criou os cenários: CN03, CN04, CN19, RNF04, RNF05 e RNF06. Além disso, criou o documento inicial no aplicativo Stack.io.</td>	
            </tr>
            <tr>
                <td><a href="https://github.com/isaqzin">Ana Luiza Soares</a></td>
                <td>Criou os cenários referentes aos requisitos: RF01, RF02, RF21, RNF01, RNF02 e RNF03. Formatou a documentação unindo todos os cenários do integrante do grupo de forma colaborativa com o Matheus de Alcântara.</td>	
            </tr>
            <tr>
                <td><a href="https://github.com/redjsun">Yzabella Miranda</a></td>
                <td>Criou os cenários referentes aos requisitos: RF05, RF06 e RF20. Além disso, corrigiu a formatação inicial do documento no Stack.io.</td>	
            </tr>
        </tbody>
    </table>
</div>

<p  align="center">Fonte: Autoria de <a  href="https://github.com/isaqzin">Isaque Camargos</a> e <a  href="https://github.com/isaqzin">Yzabella Miranda</a></p>

### Metodologia

Realizou-se o desenvolvimento dos cenários a partir da identificação dos requisitos, definindo objetivos e contexto. Foram mapeados atores e recursos, e os cenários são criados com: título e metas, contexto, exceções e restrições, e episódios detalhando ações principais e alternativas, a documentação foi padronizada utilizando tabelas no seguinte formato apresentado na Tabela 2 abaixo.

<p  align="center">Tabela 2: padrão de cenários</p>


| **Seção** | **Significado** |
|---------------|---------------------------------------------------------------------------------------------------------------------|
| **Título** | Nome ou identificação do cenário, geralmente relacionado ao requisito funcional ou objetivo principal. |
| **Metas/Objetivos** | Descreve o propósito do cenário, indicando o que se espera alcançar com a funcionalidade ou processo. |
| **Contexto** | Situação inicial ou ambiente em que o cenário ocorre, incluindo informações relevantes para compreensão do fluxo. |
| **Ator(es)** | Pessoas, sistemas ou entidades que interagem diretamente com a funcionalidade descrita no cenário. |
| **Recursos** | Ferramentas, sistemas, dispositivos ou dados necessários para a execução do cenário. |
| **Exceções** | Situações inesperadas ou condições que podem impedir o fluxo normal do cenário. |
| **Restrições**| Limitações, regras ou condições específicas que devem ser respeitadas durante a execução do cenário. |
| **Episódios** | Passos ou ações detalhadas que descrevem o fluxo principal e alternativo do cenário, incluindo interações e decisões.|

<p  align="center">Fonte: Autoria de <a  src="https://github.com/matheusdealcantara"  targe="_blank">Matheus de Alcântara</a>
</p>

### Cenário 1: Pesquisa e Filtro de Clínicas
 
**Requisito Associado:** [RF01]()  

<p align="center">Tabela x - Cenário y </p>

| Elemento        | Descrição                                                                                                                                                                                                                                                  |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Título          | Pesquisa e filtro de clínicas                                                                                                                                                                                                                              |
| Metas/Objetivos | Permitir ao usuário localizar clínicas e profissionais com base em critérios como especialidade, região, tipo de atendimento e proximidade.                                                                                                                |
| Contexto        | O usuário precisa agendar uma consulta com um cardiologista próximo à sua casa. Ao acessar o aplicativo GDF Saúde, ele usa os filtros disponíveis e encontra clínicas na região administrativa de residência.                                              |
| Ator(es)        | - Usuário do GDF Saúde. <br> - Sistema de busca do aplicativo.                                                                                                                                                                                             |
| Recursos        | - Aplicativo GDF Saúde. <br> - Sistema de geolocalização e categorização de dados médicos.                                                                                                                                                                 |
| Exceções        | - Falha na filtragem por região. <br> - A clínica listada está desatualizada ou não atende mais.                                                                                                                                                           |
| Restrições      | Os dados devem ser atualizados periodicamente para garantir a precisão das informações exibidas.                                                                                                                                                           |
| Episódios       | 1. O usuário acessa o aplicativo. <br>2. Entra na aba de “Clínicas e Profissionais”. <br>3. Usa os filtros para buscar “Cardiologista” na “Região Administrativa de Taguatinga”. <br>4. Visualiza uma lista com base na proximidade e tipo de atendimento. |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### Cenário 2: Avaliação de Clínicas  
**Requisito Associado:** [RF02]()  

<p align="center">Tabela x - Cenário y </p>

| Elemento        | Descrição                                                                                                                                                                                                |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Título          | Avaliação de clínicas                                                                                                                                                                                    |
| Metas/Objetivos | Permitir que o usuário avalie clínicas após o atendimento, contribuindo com comentários e notas.                                                                                                         |
| Contexto        | Após realizar uma consulta em uma clínica conveniada, o usuário acessa o aplicativo GDF Saúde e deixa uma nota de 4 estrelas e um comentário positivo sobre o atendimento recebido.                      |
| Ator(es)        | - Usuário do GDF Saúde. <br> - Clínicas credenciadas. <br> - Sistema de avaliação do aplicativo.                                                                                                         |
| Recursos        | - Aplicativo GDF Saúde. <br> - Interface de avaliação com notas e campo para comentários.                                                                                                                |
| Exceções        | - O sistema não salva a avaliação. <br> - Comentários ofensivos ou inadequados são publicados.                                                                                                           |
| Restrições      | O sistema deve permitir uma única avaliação por atendimento e prever moderação automática para linguagem imprópria.                                                                                      |
| Episódios       | 1. O usuário acessa o histórico de atendimentos. <br>2. Clica em “Avaliar atendimento”. <br>3. Atribui uma nota e escreve um comentário. <br>4. A avaliação é registrada e exibida para outros usuários. |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### Cenário 3: Chatbot para Direcionamento Médico
  
**Requisito Associado:** [RF21]()  

<p align="center">Tabela x - Cenário y </p>

| Elemento        | Descrição                                                                                                                                                                                                                                 |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Título          | Chatbot para direcionamento médico                                                                                                                                                                                                       |
| Metas/Objetivos | Auxiliar o usuário na escolha da especialidade médica adequada com base nos sintomas descritos.                                                                                                                                           |
| Contexto        | Um usuário sente dores persistentes nas costas, mas não sabe qual especialidade deve procurar. Ele acessa o chatbot do aplicativo GDF Saúde, descreve seus sintomas e recebe a sugestão de procurar um ortopedista.                       |
| Ator(es)        | - Usuário do GDF Saúde. <br> - Chatbot embutido no aplicativo.                                                                                                                                                                            |
| Recursos        | - Aplicativo GDF Saúde com chatbot funcional. <br> - Base de conhecimento médica para interpretação de sintomas.                                                                                                                          |
| Exceções        | - O chatbot não compreende os sintomas descritos. <br> - A especialidade sugerida é inadequada.                                                                                                                                           |
| Restrições      | O chatbot deve limitar-se a fornecer sugestões e não diagnósticos médicos.                                                                                                                                                                |
| Episódios       | 1. O usuário acessa o aplicativo e abre o chatbot. <br>2. Escreve: “Estou com dores nas costas e no ombro”. <br>3. O chatbot responde: “Recomendamos procurar um ortopedista.” <br>4. O aplicativo exibe clínicas com essa especialidade. |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### Cenário 4: Interface Intuitiva e Acessível  

**Requisito Associado:** [RNF01]()  

<p align="center">Tabela x - Cenário y </p>

| Elemento        | Descrição                                                                                                                                                                                                                                                                                                                                        |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Título          | Interface intuitiva e acessível                                                                                                                                                                                                                                                                                                                  |
| Metas/Objetivos | Tornar a experiência do usuário simples, clara e adaptada para pessoas idosas ou com pouca familiaridade com tecnologia, mantendo a organização e responsividade em dispositivos móveis.                                                                                                                                                         |
| Contexto        | Um servidor público aposentado acessa o aplicativo GDF Saúde em seu smartphone Android para verificar informações sobre sua carteirinha e agendar uma consulta. A interface do aplicativo apresenta botões grandes, texto legível, categorias bem definidas e respostas claras. O usuário consegue concluir as ações desejadas sem dificuldades. |
| Ator(es)        | - Usuário do GDF Saúde com baixa familiaridade tecnológica. <br> - Interface do aplicativo (sistema interno).                                                                                                                                                                                                                                    |
| Recursos        | - Aplicativo GDF Saúde (Android ou iOS). <br> - Dispositivo móvel com tela sensível ao toque. <br> - Layout adaptado com foco em acessibilidade.                                                                                                                                                                                                 |
| Exceções        | - O design não é responsivo e elementos ficam desorganizados. <br> - Ícones ou textos não são compreensíveis para o público-alvo.                                                                                                                                                                                                                |
| Restrições      | A interface deve seguir diretrizes de acessibilidade e design responsivo para funcionar em diferentes tamanhos de tela e sistemas operacionais.                                                                                                                                                                                                  |
| Episódios       | 1. O usuário abre o aplicativo GDF Saúde. <br>2. Navega pelas seções utilizando menus autoexplicativos e ícones ilustrativos. <br>3. Localiza rapidamente a opção desejada (ex.: carteirinha, agendamento, pesquisa de clínicas). <br>4. Conclui a tarefa sem necessidade de auxílio externo.                                                    |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

---

### Cenário 5: Carregamento Rápido e Fluido das Telas

**Requisito Associado:** [RNF02]()  

<p align="center">Tabela x - Cenário y </p>

| Elemento        | Descrição                                                                                                                                                                                                                                                               |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Título          | Carregamento rápido e fluido das telas                                                                                                                                                                                                                                  |
| Metas/Objetivos | Garantir que o aplicativo responda rapidamente a comandos do usuário, sem travamentos ou lentidão, com tempo de resposta inferior a 2 segundos.                                                                                                                         |
| Contexto        | Um usuário acessa o aplicativo GDF Saúde para verificar o status de uma autorização médica. Ele navega entre diferentes telas — login, menu principal, autorizações — e todas as transições ocorrem de maneira rápida e suave, sem atrasos perceptíveis.                |
| Ator(es)        | - Usuário do GDF Saúde (titular ou dependente). <br> - Backend do sistema (servidores de dados e processamento).                                                                                                                                                        |
| Recursos        | - Aplicativo GDF Saúde. <br> - Conexão com internet estável. <br> - Arquitetura otimizada para performance.                                                                                                                                                             |
| Exceções        | - O sistema demora mais de 2 segundos para carregar uma funcionalidade. <br> - O aplicativo apresenta travamentos durante a navegação.                                                                                                                                  |
| Restrições      | Tempo de resposta das ações deve ser menor que 2 segundos sob condições normais de uso.                                                                                                                                                                                 |
| Episódios       | 1. O usuário abre o aplicativo e realiza login. <br>2. A tela principal é exibida em menos de 2 segundos. <br>3. O usuário navega entre as seções (clínicas, autorizações, carteirinha). <br>4. Cada clique resulta em carregamento instantâneo ou quase imperceptível. |


<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---


### Cenário 6: Segurança e Transparência no Uso de Dados  

**Requisito Associado:** [RNF03]()  

<p align="center">Tabela x - Cenário y </p>

| Elemento        | Descrição                                                                                                                                                                                                                                         |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Título          | Segurança e transparência no uso de dados                                                                                                                                                                                                         |
| Metas/Objetivos | Proteger os dados pessoais do usuário, garantindo criptografia e autenticação em dois fatores, em conformidade com a LGPD.                                                                                                                        |
| Contexto        | Um usuário realiza login no aplicativo GDF Saúde e recebe um código de verificação por SMS como segunda etapa de autenticação. Ao acessar seus dados pessoais, ele visualiza um aviso sobre como as informações estão sendo usadas e armazenadas. |
| Ator(es)        | - Usuário do GDF Saúde. <br> - Servidores do INAS responsáveis pela proteção dos dados.                                                                                                                                                           |
| Recursos        | - Aplicativo GDF Saúde. <br> - Sistema de autenticação em dois fatores. <br> - Mecanismos de criptografia de dados. <br> - Mensagem informativa sobre a LGPD e privacidade.                                                                       |
| Exceções        | - O segundo fator de autenticação não é enviado. <br> - O usuário não consegue visualizar as políticas de privacidade.                                                                                                                            |
| Restrições      | O acesso só pode ser liberado mediante autenticação segura; todos os dados sensíveis devem ser criptografados.                                                                                                                                    |
| Episódios       | 1. O usuário realiza login com CPF e senha. <br>2. Recebe um código via SMS e insere no aplicativo. <br>3. Acesso concedido após verificação de dois fatores. <br>4. Visualiza informações pessoais com aviso de segurança e uso conforme LGPD.   |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---
