# Matriz Geral de Rastreabilidade

## Introdução

A matriz geral é um documento que permite a apresentação dos requisitos elicitados no projeto juntamente com sua pré e pós-rastreabilidade. Essa matriz, estruturada em forma de tabela, estabelece uma conexão cruzada entre os requisitos e os documentos correspondentes.

Ao utilizar essa técnica de referências e documentos cruzados, é possível identificar e destacar as dependências existentes entre os requisitos. Além disso, a matriz geral também permite a inclusão de elos que evidenciam o relacionamento entre os artefatos criados ao longo do projeto.

Em suma, a matriz geral, por meio de sua abordagem estruturada e de sua capacidade de estabelecer referências cruzadas e elos, desempenha um papel fundamental na análise e compreensão dos requisitos, fornecendo uma visão completa e detalhada das relações entre os elementos do projeto.

## Objetivos

Esse artefato tem como objetivo agregar os resultados obtidos nos artefatos de Backward-From e Forward-From em uma única matriz de rastreabilidade.

## Metodologia

Os requisitos apresentados são os elicitados no artefato de [Requisitos Elicitados](../elicitacao/requisitos_finais.md) e refinados ao longo do projeto.

A matriz é apresentada com 7 colunas sendo elas:

- **ID**: apresenta o identificador relacionado ao requisito;
- **Descrição**: apresenta a descrição do requisito;
- **Pré-Rastreabilidade**: apresenta a origem da elicitação do requisito;
- **Implementado?**: indica se o requisito está ou não implementado no aplicativo (Sim, Não ou Parcialmente).
- **Artefatos**: apresenta os artefatos relacionados ao requisito;
- **Elos**: ligação entre os requisitos e artefatos.

## Matriz Geral

<p align="center"><b>Tabela 1</b> - Matriz Geral de Rastreabilidade</p>

<table>
<thead>
<tr>
<th>ID</th>
<th>Descrição</th>
<th>Pré-Rastreabilidade</th>
<th>Implementado?</th>
<th>Artefatos</th>
<th>Elos</th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="../elicitacao/requisitos_finais.md#RF01.1">RF01.1</a></td>
<td>O usuário poderá pesquisar redes credenciadas por meio de filtros de busca.</td>
<td>[EN01](../elicitacao/tecnicas/entrevista.md#EN01), [EN02](../elicitacao/tecnicas/entrevista.md#EN02), [IS06](../elicitacao/tecnicas/introspeccao.md#IS06), [QT03](../elicitacao/tecnicas/questionario.md#QT03), [QT08](../elicitacao/tecnicas/questionario.md#QT08)</td>
<td>Sim</td>
<td>[Casos de Uso](../modelagem/metodos_tradicionais/casos_de_usos.md#UC01), [Cenários](../modelagem/metodos_tradicionais/cenarios.md#CE01), [Léxicos](../modelagem/metodos_tradicionais/lexicos.md#RedeCredenciada), [Histórias de Usuário](../modelagem/metodos_ageis/historias_todos02.md#US01)</td>
<td>[ELOBF01](backward_from.md#ELOBF01)</td>
</tr>
<tr>
<td><a href="../elicitacao/requisitos_finais.md#RF12.4">RF12.4</a></td>
<td>Exibir pop-ups informativos com as principais novidades após a atualização do aplicativo.</td>
<td>[GF05](../elicitacao/tecnicas/grupo_focal.md#GF05)</td>
<td>Não</td>
<td>[Casos de Uso](../modelagem/metodos_tradicionais/casos_de_usos.md#UC33), [Cenários](../modelagem/metodos_tradicionais/cenarios.md#CE12), [Léxicos](../modelagem/metodos_tradicionais/lexicos.md#Novidades), [Histórias de Usuário](../modelagem/metodos_ageis/historias_todos02.md#US32)</td>
<td>[ELOBF42](backward_from.md#ELOBF42)</td>
</tr>
<tr>
<td><a href="../elicitacao/requisitos_finais.md#RF13">RF13</a></td>
<td>Adicionar consulta à rede odontológica.</td>
<td>[QT07](../elicitacao/tecnicas/questionario.md#QT07)</td>
<td>Sim</td>
<td>[Casos de Uso](../modelagem/metodos_tradicionais/casos_de_usos.md#UC35), [Cenários](../modelagem/metodos_tradicionais/cenarios.md#CE15), [Léxicos](../modelagem/metodos_tradicionais/lexicos.md#Odontologia), [Histórias de Usuário](../modelagem/metodos_ageis/historias_todos02.md#US35)</td>
<td>[ELOBF45](backward_from.md#ELOBF45)</td>
</tr>
<tr>
<td><a href="../elicitacao/requisitos_finais.md#RF16">RF16</a></td>
<td>Disponibilizar calendário personalizado com visualização de consultas agendadas, prazos de carência e vencimentos.</td>
<td>[BS01](../elicitacao/elicitacao.md#RF16)</td>
<td>Não</td>
<td>[Casos de Uso](../modelagem/metodos_tradicionais/casos_de_usos.md#UC38), [Cenários](../modelagem/metodos_tradicionais/cenarios.md#CE19), [Léxicos](../modelagem/metodos_tradicionais/lexicos.md#Calendario), [Histórias de Usuário](../modelagem/metodos_ageis/historias_todos02.md#US39)</td>
<td>[ELOBF49](backward_from.md#ELOBF49)</td>
</tr>
<tr>
<td><a href="../elicitacao/requisitos_finais.md#RNF12">RNF12</a></td>
<td>O aplicativo deve oferecer suporte por chat ou telefone.</td>
<td>[IS15](../elicitacao/tecnicas/introspeccao.md#IS15)</td>
<td>Sim</td>
<td>[Léxicos](../modelagem/metodos_tradicionais/lexicos.md#Suporte), [NFR Framework](../modelagem/metodos_ageis/nfr.md#RNF12)</td>
<td>[ELOBF66](backward_from.md#ELOBF66)</td>
</tr>
<tr>
<td><a href="../elicitacao/requisitos_finais.md#RNF13">RNF13</a></td>
<td>Deve funcionar de forma offline para acesso à carteirinha e histórico de consultas.</td>
<td>[IS19](../elicitacao/tecnicas/introspeccao.md#IS19)</td>
<td>Não</td>
<td>[Léxicos](../modelagem/metodos_tradicionais/lexicos.md#Offline), [NFR Framework](../modelagem/metodos_ageis/nfr.md#RNF13)</td>
<td>[ELOBF67](backward_from.md#ELOBF67)</td>
</tr>
<!-- Adicione mais linhas conforme necessário para os requisitos do seu projeto -->
</tbody>
</table>

<p align="center">Fonte: Autoria dos integrantes do Grupo 09, 2025</p>

## Bibliografia



## Histórico de Versões

| Versão | Data       | Descrição                 | Autor(es) | Revisor(es) |
| ------ | ---------- | ------------------------- | --------- | ----------- |
| `1.0`    | 08/06/2025 | Criação da matriz geral   | [Lucas Alves](https://github.com/LucasAlves71) | [Kaleb Macedo](https://github.com/kalebmacedo)   |