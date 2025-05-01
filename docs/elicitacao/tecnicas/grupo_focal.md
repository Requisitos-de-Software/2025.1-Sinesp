
# Técnica de Elicitação: Grupo Focal

## Introdução

O grupo focal é uma técnica de elicitação de requisitos que consiste em uma discussão estruturada com um grupo de usuários ou stakeholders, mediada por um facilitador, com o objetivo de explorar percepções, opiniões e sugestões em relação a um sistema ou produto.

## Metodologia

A técnica do grupo focal envolve reunir de forma presencial ou remota um grupo de participantes representativos do público-alvo. Um moderador conduz a conversa com base em perguntas previamente preparadas, promovendo o debate entre os integrantes. Os dados coletados nessa interação ajudam a identificar necessidades, problemas e ideias valiosas para a definição de requisitos do sistema. Foi realizada pela integrante [Yzabella Miranda](https://github.com/redsjun) com os usuários Victor Schmidt e Marcos Goulart, a Tabela 1 apresenta os dados dos participantes da reunião. 

## Dados da Reunião

<p align="center">Tabela 1: Participantes</p>

| Participantes     | Idade | Frequência de Uso do App | Perfil de Uso                       |
|-------------------|-------|---------------------------|-------------------------------------|
| Marcos Goulart            | 20    | A cada 2 a 3 meses        | Usa para exames e consultas         |
| Victor Schmidt            | 20    | 1x por semana             | Novo usuário, ainda explorando      |

<p align="center">Autor: <b><a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></b></p>

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

<p align="center">Tabela 1.1: Legenda dos identificadores</p>

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
                <td>RFXX</td>
                <td>Requisito Funcional número XX</td>
            </tr>
            <tr>
                <td>RNFXX</td>
                <td>Requisito Não Funcional número XX</td>
            </tr>
            <tr>
                <td>GFXX</td>
                <td>Requisito número XX elicitado pelo Grupo Focal</td>
            </tr>
        </tbody>
    </table>
</div>

<p align="center">Autor: <b><a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></b></p>

## Requisitos Funcionais

<p align="center">Tabela 2: Requisitos funcionais</p>

| Tipo   | Descrição                                                                                             | ID      | Elaborado   | Implementado |
|--------|-------------------------------------------------------------------------------------------------------|---------|-------------|--------------|
| RF01   | O sistema deve permitir ao usuário avaliar uma clínica após o atendimento.                            | GF01    | Sim         |              |
| RF02   | O sistema deve notificar o usuário sobre retornos médicos pendentes.                                  | GF02    | Sim         |              |
| RF03   | O sistema deve notificar o usuário sobre abertura de agenda e cancelamentos de horários de interesse. | GF03    | Sim         |              |
| RF04   | O sistema deve exibir os exames solicitados e associar aos respectivos retornos médicos.              | GF04    | Sim         |              |
| RF05   | O sistema deve divulgar informações sobre novas funcionalidades no aplicativo.                        | GF05    | Sim         |              |
| RF06   | O sistema deve permitir que o usuário favorite horários de consulta desejados.                        | GF06    | Sim         |              |
| RF07   | O sistema deve alertar o usuário caso algum horário favorito fique disponível por desistência.        | GF07    | Sim         |              |
| RF08   | O sistema deve permitir ao usuário visualizar um histórico de consultas e exames realizados.          | GF08    | Sim         |              |
| RF09   | O sistema deve oferecer um canal para o usuário enviar feedback sobre atendimentos.                   | GF09    | Sim         |              |
| RF10   | O sistema deve exibir notificações sobre prazos importantes relacionados a consultas e exames.        | GF10    | Sim         |              |

<p align="center">Autor: <b><a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></b></p>

## Requisitos Não Funcionais

<p align="center">Tabela 3: Requisitos não funcionais</p>

| Tipo    | Descrição                                                                                                               | ID      | Elaborado   | Implementado |
|---------|-------------------------------------------------------------------------------------------------------------------------|---------|-------------|--------------|
| RNF01   | O sistema deve exigir autenticação via GovBR para login.                                                                | GF11    | Sim         |              |
| RNF02   | O sistema deve incluir autenticação em dois fatores para acesso aos dados de saúde.                                     | GF12    | Sim         |              |
| RNF03   | O sistema deve ter uma interface organizada em categorias.                                                              | GF13    | Sim         |              |
| RNF04   | O sistema deve ser transparente quanto ao uso e segurança dos dados do usuário.                                         | GF14    | Sim         |              |
| RNF05   | O sistema deve garantir que informações críticas estejam acessíveis em até três cliques.                                | GF15    | Sim         |              |
| RNF06   | O sistema deve manter histórico de notificações acessível ao usuário por no mínimo 6 meses.                             | GF16    | Sim         |              |
| RNF07   | O sistema deve apresentar desempenho adequado, respondendo a interações em até 2 segundos.                              | GF17    | Sim         |              |
| RNF08   | O sistema deve ser compatível com diferentes versões do Android e iOS, a partir das versões mais utilizadas no mercado. | GF18    | Sim         |              |

<p align="center">Autor: <b><a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></b></p>

## Referência bibliográfica

WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3rd Edition. Microsoft Press, 2013. Disponível em: https://olivroqueaprende.com/WDK/Software_Requirements_3rd_Edition.pdf. Acesso em: 01 de maio 2025.

<img src="../assets/img/grupo_focal_1.png">
<img src="../assets/img/grupo_focal_2.png">

## Histórico de versões

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |  01/05/2025 |  Criação inicial do documento com as tabelas dos requisitos elicitados e seus tipos. A participante [Yzabella Miranda](https://github.com/redsjun) realizou a reunião. | [Matheus de Alcântara](https://github.com/matheusdealcantara)  | [Othavio Bolzan](https://github.com/bolzanMGB) |