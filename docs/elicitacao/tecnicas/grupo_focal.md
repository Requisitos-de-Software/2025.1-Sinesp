# Técnica de Elicitação: Grupo Focal

## Introdução

O Grupo Focal é uma técnica de elicitação de requisitos que consiste em uma discussão estruturada com um grupo de usuários ou stakeholders, mediada por um facilitador, com o objetivo de explorar percepções, opiniões e sugestões em relação a um sistema ou produto. (WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3rd Edition. Microsoft Press, 2013, p. 124)


## Integrantes do grupo

A Tabela 1 contêm todos os integrantes da equipe que participaram da técnica de elicitação Grupo Focal e o que cada integrante desenvolveu durante essa etapa.

<p align="center">Tabela 1: Integrantes do grupo</p>

<div align="center">
    <table>
        <thead>
            <tr>
                <th>Nome</th>
                <th>Grupo Focal</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Matheus de Alcântara</td>
                <td>Desenvolvimento do documento da elicitação, com os requisitos elicitados e a gravação da reunião</td>
            </tr>
            <tr>
                <td>Yzabella Miranda Pimenta</td>
                <td>Desenvolvimento do roteiro da reunião e gravação com os usuários reais</td>
            </tr>
        </tbody>
    </table>
</div>

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>


## Usuários reais envolvidos

A Tabela 2 contêm as informações dos usuários participantes do Grupo Focal, com o nome, informações sobre a gravação realizada, o link para a autorização da gravação e sua postagem no Youtube de forma não listada.

<p align="center">Tabela 2: Usuários reais</p>

<div align="center">
    <table>
        <thead>
            <tr>
                <th>Nome</th>
                <th>Data</th>
                <th>Hora</th>
                <th>Duração da etapa</th>
                <th>Autorização da gravação</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Marcos Goulart</td>
                <td>01/05/2025</td>
                <td>21:05:00</td>
                <td>6m 44s</td>
                <td><a href="../assets/termosGrupoFocal.pdf" target="_blank">Termo de consentimento</a></td>
            </tr>
            <tr>
                <td>Victor Schmidt</td>
                <td>01/05/2025</td>
                <td>21:05:00</td>
                <td>6m 44s</td>
                <td><a href="../assets/termosGrupoFocal.pdf" target="_blank">Termo de consentimento</a></td>
            </tr>
        </tbody>
    </table>
</div>

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

## Metodologia

A técnica do grupo focal envolve reunir de forma presencial ou remota um grupo de participantes representativos do público-alvo. Um moderador conduz a conversa com base em perguntas previamente preparadas, promovendo o debate entre os integrantes. Os dados coletados nessa interação ajudam a identificar necessidades, problemas e ideias valiosas para a definição de requisitos do sistema, essa reunião deverá ser gravada para possíveis consultas aos comentários dos usuários. A análise a partir do Grupo Focal não é quantitativa e sim um retorno mais subjetivo sobre os requisitos, normalmente os participantes desta técnica não possuem autoridade de tomadas de decisão nos requisitos. (WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3rd Edition. Microsoft Press, 2013). Foi realizada pela integrante <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a> com os usuários Victor Schmidt e Marcos Goulart, a Tabela 1 apresenta os dados dos participantes da reunião. 

## Gravação do Grupo Focal

Para realizar esta elicitação, foi realizada uma reunião entre os usuários Marcos Goulart e Victor Schmidt com a integrante Yzabella Miranda, como o auxílio de uma câmera e o roteiro previamente produzido para conduzir a reunião de maneira neutra. Abaixo, é possível assistir no Vídeo 1 a gravação que foi feita para esta técnica, que foi postado no youtube de maneira não listada. 

<div align="center">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/nrQDSP9eyk4" title="Grupo Focal GDF-Saúde" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<p align="center">Vídeo 1: Gravação do grupo focal</p>

## Discussão em Seções

### 1. Experiência do Usuário

Marcos considera que o app poderia ser mais organizado, com seções e categorias. Já Victor o achou intuitivo até então, embora reconheça que ainda está conhecendo suas funcionalidades. 

### 2. Funcionalidades Essenciais

Foi apontada a ausência de funcionalidades como avaliação de clínicas após atendimento, e a exibição de retornos médicos relacionados a exames solicitados.

### 3. Acompanhamento e Notificações

Os participantes sugeriram notificações sobre abertura de agendas, retornos pendentes e alertas de cancelamento de horários desejados.

### 4. Segurança

Ambos expressaram preocupação com a segurança: ausência de autenticação em duas etapas, uso de login via Google e vulnerabilidade em caso de perda do celular. Recomendam o uso exclusivo de login via GovBR.

### 5. Melhorias e Sugestões

Sugerem reorganização da interface com agrupamento por categorias, melhorias no feedback visual do app e divulgação de funcionalidades novas. Victor, como desenvolvedor, também aponta a falta de comunicação do time técnico com os usuários.

## Conclusão da Reunião

A reunião evidenciou que, apesar de útil em determinadas situações, o aplicativo apresenta diversas falhas de usabilidade, segurança e comunicação. As sugestões dos participantes reforçam a necessidade de repensar a experiência do usuário, aprimorar a segurança e tornar o app mais informativo e transparente.

## Recomendações para o Aplicativo

- Adotar login exclusivo por GovBR.
- Implementar autenticação em dois fatores.
- Permitir avaliação de atendimentos.
- Notificar sobre retornos e novas vagas.
- Reestruturar a interface por categorias.
- Exibir atualizações de funcionalidades.

## Requisitos Elicitados
As tabelas 2 e 3 listadas a seguir contém os requisitos que foram elicitados durante a realização desta técnica de elicitação de requisitos.

## Legendas

<p align="center">Tabela 3: Legenda dos identificadores</p>

<div align="center">
    <table>
        <thead>
            <tr>
                <th>Identificador</th>
                <th>Descrição</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>RF</td>
                <td>Requisito Funcional</td>
            </tr>
            <tr>
                <td>RNF</td>
                <td>Requisito Não Funcional</td>
            </tr>
            <tr>
                <td>GFXX</td>
                <td>Requisito número XX elicitado pelo Grupo Focal</td>
            </tr>
        </tbody>
    </table>
</div>

<p align="center">Autor: <b><a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a></b></p>

## Requisitos Funcionais

<p align="center">Tabela 4: Requisitos funcionais</p>

| Tipo   | Descrição                                                                                             | ID      | Implementado |
|--------|-------------------------------------------------------------------------------------------------------|---------|--------------|
| [RF02](../../elicitacao/elicitacao.md#RF02)   | O sistema deve permitir ao usuário avaliar uma clínica após o atendimento.                            | <a id="GF01"></a>GF01  |         Não     |
| [RF04](../../elicitacao/elicitacao.md#RF04)   | O sistema deve notificar o usuário sobre retornos médicos pendentes.                                  | <a id="GF02"></a>GF02    |       Não       |
| [RF04](../../elicitacao/elicitacao.md#RF04)   | O sistema deve notificar o usuário sobre abertura de agenda e cancelamentos de horários de interesse. | <a id="GF03"></a>GF03    |       Não       |
| [RF09](../../elicitacao/elicitacao.md#RF09)   | O sistema deve exibir os exames solicitados e associar aos respectivos retornos médicos.              | <a id="GF04"></a>GF04    |       Não       |
| [RF12](../../elicitacao/elicitacao.md#RF12)   | O sistema deve divulgar informações sobre novas funcionalidades no aplicativo.                        | <a id="GF05"></a>GF05    |        Sem certeza ainda      |
| [RF10](../../elicitacao/elicitacao.md#RF10)   | O sistema deve permitir que o usuário favorite horários de consulta desejados.                        | <a id="GF06"></a>GF06    |        Não      |
| [RF04](../../elicitacao/elicitacao.md#RF04)   | O sistema deve alertar o usuário caso algum horário favorito fique disponível por desistência.        | <a id="GF07"></a>GF07    |     Não         |
| [RF09](../../elicitacao/elicitacao.md#RF09)   | O sistema deve permitir ao usuário visualizar um histórico de consultas e exames realizados.          | <a id="GF08"></a>GF08    |       Sem certeza ainda       |
| [RF11](../../elicitacao/elicitacao.md#RF1)  | O sistema deve oferecer um canal para o usuário enviar feedback sobre atendimentos.                   | <a id="GF09"></a>GF09    |     Não      |
| [RF04](../../elicitacao/elicitacao.md#RF04)  | O sistema deve exibir notificações sobre prazos importantes relacionados a consultas e exames.        | <a id="GF02"></a>GF10    |        Não     |

<p align="center">Autor: <b><a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a></b></p>

## Requisitos Não Funcionais

<p align="center">Tabela 5: Requisitos não funcionais</p>

| Tipo    | Descrição                                                                                                               | ID      |
|---------|-------------------------------------------------------------------------------------------------------------------------|---------|
| [RNF15](../../elicitacao/elicitacao.md#RNF15)   | O sistema deve exigir autenticação via GovBR para login.                                                                | <a id="GF11"></a>GF11    |
| [RNF03](../../elicitacao/elicitacao.md#RNF03)   | O sistema deve incluir autenticação em dois fatores para acesso aos dados de saúde.                                     | <a id="GF12"></a>GF12    |
| [RNF01](../../elicitacao/elicitacao.md#RNF01)   | O sistema deve ter uma interface organizada em categorias.                                                              | <a id="GF13"></a>GF13 | 
| [RNF03](../../elicitacao/elicitacao.md#RNF03)   | O sistema deve ser transparente quanto ao uso e segurança dos dados do usuário.                                         | <a id="GF14"></a>GF14    |
| [RNF10](../../elicitacao/elicitacao.md#RNF10)   | O sistema deve garantir que informações críticas estejam acessíveis em até três cliques.                                | <a id="GF15"></a>GF15    |
| [RNF11](../../elicitacao/elicitacao.md#RNF11)   | O sistema deve manter histórico de notificações acessível ao usuário por no mínimo 6 meses.                             | <a id="GF16"></a>GF16    |
| [RNF02](../../elicitacao/elicitacao.md#RNF02)   | O sistema deve apresentar desempenho adequado, respondendo a interações em até 2 segundos.                              | <a id="GF17"></a>GF17    |
| [RNF05](../../elicitacao/elicitacao.md#RNF05)   | O sistema deve ser compatível com diferentes versões do Android e iOS, a partir das versões mais utilizadas no mercado. | <a id="GF18"></a>GF18    |

<p align="center">Autor: <b><a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a></b></p>



## Referência bibliográfica

WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3rd Edition. Microsoft Press, 2013. Disponível em: <a href="https://olivroqueaprende.com/WDK/Software_Requirements_3rd_Edition.pdf" target="_blank">https://olivroqueaprende.com/WDK/Software_Requirements_3rd_Edition.pdf</a>. Acesso em: 01 de maio 2025.

## Histórico de versões

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |  01/05/2025 |  Criação inicial do documento com as tabelas dos requisitos elicitados e seus tipos. A participante <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a> realizou a reunião. | <a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a>  | <a href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a> |
| `1.1`  | 02/05/2025  | Criação da lista de verificação do artefato e atualização dos links para criar uma nova guia no navegador para melhor usabilidade | <a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a> | <a href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a> |
| `1.2`  | 02/05/2025  | Ajuste de tabela, link de imagens e enumeração de requisitos funcionais e não funcionais | <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a> | <a href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a> |
| `1.3`  | 03/05/2025  | Adicionar vídeo da elicitação integrado ao documento | <a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a> | <a href="https://github.com/bolzanMGB" target="_blank">Othabio Bolzan</a> |
| `1.4`  | 09/05/2025  | Refatorações após correções sugeridas: Tabela com os integrantes do grupo quer participaram, informações adicionais na tabela dos usuários, metodologia mais detalhada e com referência, também adicionado o link com a autorização de gravação. | <a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a> | <a href="https://github.com/bolzanMGB" target="_blank">Yzabella Miranda</a> |