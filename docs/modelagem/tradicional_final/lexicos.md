# Léxicos

## Introdução

Este documento apresenta os léxicos identificados no projeto GDF Saúde, agrupando termos duplicados ou sinônimos e indicando em quais requisitos cada léxico foi citado. Para cada léxico, é apresentada uma breve introdução, a tabela consolidada com os requisitos relacionados e, quando aplicável, os sinônimos encontrados. As tabelas estão enumeradas conforme a ordem de apresentação.

## <a id="integrantes"></a>Integrantes do Grupo

A tabela a seguir apresenta todos os integrantes da equipe e suas respectivas contribuições na construção dos léxicos durante o projeto.

<p align="center">Tabela 1 - Integrantes do grupo envolvidos</p>

| Nome | Contribuição |
| --- | --- |
| [Matheus de Alcântara](https://github.com/matheusdealcantara) | Criou os léxicos referentes aos requisitos: [RF09.1](../../elicitacao/requisitos_finais.md#RF09.1), [RF09.2](../../elicitacao/requisitos_finais.md#RF09.2), [RF09.3](../../elicitacao/requisitos_finais.md#RF09.3), [RF09.4](../../elicitacao/requisitos_finais.md#RF09.4), [RF10](../../elicitacao/requisitos_finais.md#RF10), [RF20](../../elicitacao/requisitos_finais.md#RF20), [RNF11](../../elicitacao/requisitos_finais.md#RNF11) e [RNF12](../../elicitacao/requisitos_finais.md#RNF12). Elaborou o documento inicial e contribuiu na organização geral do material que estava na plataforma <a href="https://stackedit.io/app#">StackEdit</a>. Por fim, em dupla com o [Isaque Camargos](https://github.com/isaqzin) fez introdução, metodoliga, deixou os lexicos com hyperlinks entre si. |
| [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) | Criou os léxicos [Filtro](./lexicos.md#LX49), [Proximidade](./lexicos.md#LX50), [Especialidade](./lexicos.md#LX51), [Avaliação](./lexicos.md#LX52), [Comentários](./lexicos.md#LX53), [Chatbot](./lexicos.md#LX54), [Desempenho](./lexicos.md#LX55) e [Segurança de Dados](./lexicos.md#LX56), referentes ao refinamento dos antigos requisitos RF01, RF02, RF21, RNF01, RNF02 e RNF03. |
| [Lucas Alves](https://github.com/LucasAlves71) | Elaborou os léxicos dos requisitos [RF07](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF07), [RF08](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF08), [RF16](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF16), [RF18](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF18), [RNF09](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF09) e [RNF10](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF10). Descreveu a metodologia da elaboração dos léxicos |
| [Kaleb Macedo](https://github.com/kalebmacedo) | Responsável pelos léxicos dos requisitos [RF05](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF05), [RF06](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF06), [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17), [RNF07](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF07) e [RNF08](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF08). Adicionou léxicos para os requisitos refinados [RNF05.1](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF5.1), [RNF05.2](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF05.2), [RNF06.](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF06.1) ao [RNF06.5](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF06.5) e [RNF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF17). |
| [Othavio Bolzan](https://github.com/bolzanMGB) | Desenvolveu léxicos para os requisitos [RF11](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF11), [RF12](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF12), [RNF13](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF13) e [RNF14](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF14) |
| [Yzabella Miranda](https://github.com/redjsun) | Elaborou léxicos dos requisitos [RF22](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF22), [RNF15](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF15), [RF03](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF03), [RF13](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF13),[RF14.1](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF14.1), [RF14.2](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF14.2) e [RF15](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF15) |
| [Isaque Camargos](https://github.com/isaqzin) | Adicionou a quais lexicos os requsitos [RF04.1](../../elicitacao/requisitos_finais.md#RF04.1), [RF04.2](../../elicitacao/requisitos_finais.md#RF04.2), [RF04.3](../../elicitacao/requisitos_finais.md#RF04.3), [RF04.4](../../elicitacao/requisitos_finais.md#RF04.4), [RF04.5](../../elicitacao/requisitos_finais.md#RF04.5), [RF04.6](../../elicitacao/requisitos_finais.md#RF04.6), [RF04.7](../../elicitacao/requisitos_finais.md#RF04.7), [RF04.8](../../elicitacao/requisitos_finais.md#RF04.8), [RF04.9](../../elicitacao/requisitos_finais.md#RF04.9), [RF03](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF03) e [RF19](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF19)se relacionavam. Contribuiu na organização do material que estava na plataforma <a href="https://stackedit.io/app#">StackEdit</a>. Por fim, em dupla com o [Matheus de Alcântara](https://github.com/matheusdealcantara) fez introdução, metodoliga, deixou os lexicos com hyperlinks entre si. |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a> e <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

## Metodologia

A elaboração dos léxicos descritos neste documento foi conduzida com base na técnica de modelagem de linguagem conhecida como Léxico Ampliado da LInguagem (LAL), uma abordagem amplamente utilizada na Engenharia de Requisitos para descrever termos relevantes do domínio de forma clara e contextualizada.

Cada léxico foi construído a partir da análise individual de um requisito (funcional ou não funcional), com o objetivo de identificar os principais termos operacionais, objetos e atributos envolvidos no sistema. A técnica adotada segue a estrutura apresentada nos slides Requisitos - Aula 10, de Milene Serrano e Maurício Serrano, composto por:

- Termo: Nome do conceito identificado no requisito.
- Tipo: Classificação do termo como verbo, objeto ou atributo.
- Noção: Definição do termo dentro do contexto do sistema, explicando seu significado e uso.
- Impacto: Consequências ou importância do termo para o funcionamento do sistema e para o usuário.

A extração dos termos foi feita com base em leitura interpretativa dos requisitos especificados, buscando classificar em verbos, objetos e estados que sejam essenciais para o entendimento do funcionamento do sistema e sua interação com os usuários. Para cada tipo de classificação o conteúdo em noção e impacto devem ser preenchidos seguindo o seguinte padrão: 

- Verbo  
  - Noção: quem realiza, quando acontece e quais os procedimentos  
  - Impacto: quais os reflexos das ações no ambiente e novos estados decorrentes

- Objeto  
  - Noção: definir o objeto e identificar outros objetos com os quais ele se relaciona  
  - Impacto: ações que podem ser aplicadas ao objeto

- Estado  
  - Noção: o que indica e ações que levaram a esse estado  
  - Impacto: identificar outros estados que podem ocorrer a partir do estado que se descreve


---
## Léxico 1: <a id="LX01"></a>Beneficiário

**Requisitos relacionados:** [RF07.1](../../elicitacao/requisitos_finais.md#RF07.1), [RF07.2](../../elicitacao/requisitos_finais.md#RF07.2), [RF07.3](../../elicitacao/requisitos_finais.md#RF07.3), [RF07.4](../../elicitacao/requisitos_finais.md#RF07.4), [RF07.5](../../elicitacao/requisitos_finais.md#RF07.5), [RF01.1](../../elicitacao/requisitos_finais.md#RF01.1), [RF01.2](../../elicitacao/requisitos_finais.md#RF01.2), [RF01.3](../../elicitacao/requisitos_finais.md#RF01.3), [RF01.4](../../elicitacao/requisitos_finais.md#RF01.4), [RF01.5](../../elicitacao/requisitos_finais.md#RF01.5), [RF09.1](../../elicitacao/requisitos_finais.md#RF09.1), [RF09.2](../../elicitacao/requisitos_finais.md#RF09.2), [RF09.3](../../elicitacao/requisitos_finais.md#RF09.3), [RF09.4](../../elicitacao/requisitos_finais.md#RF09.4), [RF10](../../elicitacao/requisitos_finais.md#RF10), [RF11](../../elicitacao/requisitos_finais.md#RF11), [RNF11](../../elicitacao/requisitos_finais.md#RNF11)

O termo "Beneficiário" refere-se aos funcionários públicos do GDF e seus dependentes que utilizam o aplicativo GDF Saúde.

<p align="center">Tabela 1: Léxico - Beneficiário</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Usuário | Objeto | Titular, Dependente, Usuário titular, Optante | Titular ou dependente do [plano de Saúde](./lexicos.md#LX38) INAS que utiliza o aplicativo GDF Saúde.| -Usuário é titular ou dependende <br>- Usuário faz [login](./lexicos.md#LX41) <br> - Usuário usa [carteirinha](./lexicos.md#LX12)<br> - Usuário agenda [consulta](./lexicos.md#LX04) <br> | [RF07.1](../../elicitacao/requisitos_finais.md#RF07.1), [RF07.2](../../elicitacao/requisitos_finais.md#RF07.2), [RF07.3](../../elicitacao/requisitos_finais.md#RF07.3), [RF07.4](../../elicitacao/requisitos_finais.md#RF07.4), [RF07.5](../../elicitacao/requisitos_finais.md#RF07.5) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a>, <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a> e <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

## Léxico 2: <a id="LX02"></a>Notificações

**Requisitos relacionados:** [RF04.1](../../elicitacao/requisitos_finais.md#RF04.1), [RF04.2](../../elicitacao/requisitos_finais.md#RF04.2), [RF04.3](../../elicitacao/requisitos_finais.md#RF04.3), [RF04.4](../../elicitacao/requisitos_finais.md#RF04.4), [RF04.5](../../elicitacao/requisitos_finais.md#RF04.5), [RF04.6](../../elicitacao/requisitos_finais.md#RF04.6), [RF04.7](../../elicitacao/requisitos_finais.md#RF04.7), [RF04.8](../../elicitacao/requisitos_finais.md#RF04.8), [RF04.9](../../elicitacao/requisitos_finais.md#RF04.9), [RNF11](../../elicitacao/requisitos_finais.md#RNF11)

O termo "Notificações" refere-se às mensagens ou alertas enviados ao usuário sobre eventos específicos.

<p align="center">Tabela 2: Léxico - Notificações</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Notificações | Objeto | Alertas | - Mensagens enviadas ao [Beneficiário](./lexicos.md#LX01) sobre eventos específicos.<br> - Se relaciona com [histórico](./lexicos.md#LX03) e [armazenar](./lexicos.md#LX43)  | - O [Beneficiário](./lexicos.md#LX01) escolhe receber notificações sobre ações necessárias ou informações relevantes. | [RF04.1](../../elicitacao/requisitos_finais.md#RF04.1), [RF04.2](../../elicitacao/requisitos_finais.md#RF04.2), [RF04.3](../../elicitacao/requisitos_finais.md#RF04.3), [RF04.4](../../elicitacao/requisitos_finais.md#RF04.4), [RF04.5](../../elicitacao/requisitos_finais.md#RF04.5), [RF04.6](../../elicitacao/requisitos_finais.md#RF04.6), [RF04.7](../../elicitacao/requisitos_finais.md#RF04.7), [RF04.8](../../elicitacao/requisitos_finais.md#RF04.8), [RF04.9](../../elicitacao/requisitos_finais.md#RF04.9), [RNF11](../../elicitacao//requisitos_finais.md#RNF11) |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a> e <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 3: <a id="LX03"></a>Histórico

**Requisitos relacionados:** [RF09.1](../../elicitacao/requisitos_finais.md#RF09.1), [RF09.2](../../elicitacao/requisitos_finais.md#RF09.2), [RF09.3](../../elicitacao/requisitos_finais.md#RF09.3), [RF09.4](../../elicitacao/requisitos_finais.md#RF09.4), [RNF11](../../elicitacao/requisitos_finais.md#RNF11), [RNF13](../../elicitacao/requisitos_finais.md#RNF13)

O léxico "Histórico" foi identificado nos requisitos [RF09.1](../../elicitacao/requisitos_finais.md#RF09.1), [RF09.2](../../elicitacao/requisitos_finais.md#RF09.2), [RF09.3](../../elicitacao/requisitos_finais.md#RF09.3), [RF09.4](../../elicitacao/requisitos_finais.md#RF09.4) e [RNF11](../../elicitacao/requisitos_finais.md#RNF11), [RNF13](../../elicitacao/requisitos_finais.md#RNF13), ambos tratando do registro de eventos passados relacionados à saúde do usuário.

<p align="center">Tabela 3: Léxico - Histórico</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Histórico | Objeto | - | - Registro de eventos passados relacionados à saúde do usuário, incluindo [consultas](./lexicos.md#LX04), [exames](./lexicos.md#LX05) realizados, resultados de [exames](./lexicos.md#LX05) e [coparticipações](./lexicos.md#LX06).<br> - Registro de notificações sobre informações relacionadas ao [Beneficiário](./lexicos.md#LX01). | - O [Beneficiário](./lexicos.md#LX01) visualiza seu histório de guias.<br> - O [Beneficiário](./lexicos.md#LX01) visualiza seu histórico de notificações. | [RF09.1](../../elicitacao/requisitos_finais.md#RF09.1), [RF09.2](../../elicitacao/requisitos_finais.md#RF09.2), [RF09.3](../../elicitacao/requisitos_finais.md#RF09.3), [RF09.4](../../elicitacao/requisitos_finais.md#RF09.4), [RNF11](../../elicitacao/requisitos_finais.md#RNF11), [RNF13](../../elicitacao/requisitos_finais.md#RNF13) |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a> e <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

## Léxico 4: <a id="LX04"></a>Consulta

**Requisitos relacionados:** [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1), [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2), [RF13](../../elicitacao/requisitos_finais.md#RF13), [RF14.1](../../elicitacao/requisitos_finais.md#RF14.1), [RF14.2](../../elicitacao/requisitos_finais.md#RF14.2), [RF15](../../elicitacao/requisitos_finais.md#RF15), [RF09.1](../../elicitacao/requisitos_finais.md#RF09.1), [RF01.1](../../elicitacao/requisitos_finais.md#RF01.1), [RF01.2](../../elicitacao/requisitos_finais.md#RF01.2), [RF01.5](../../elicitacao/requisitos_finais.md#RF01.5), [RF10](../../elicitacao/requisitos_finais.md#RF10), [RF04.6](../../elicitacao/requisitos_finais.md#RF04.6)

O termo "Consulta" aparece em diversos requisitos, sempre relacionado ao atendimento clínico agendado entre o [Beneficiário](./lexicos.md#LX01) e um profissional de saúde.

<p align="center">Tabela 4: Léxico - Consulta</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Consulta | Objeto | Atendimento | - Atendimento clínico agendado entre o [Beneficiário](./lexicos.md#LX01) e um [profissional](./lexicos.md#LX14). | - O [Beneficiário](./lexicos.md#LX01) agenda uma consulta - O [Beneficiário](./lexicos.md#LX01) desmarca uma consulta | [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1), [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2), [RF13](../../elicitacao/requisitos_finais.md#RF13), [RF14.1](../../elicitacao/requisitos_finais.md#RF14.1), [RF14.2](../../elicitacao/requisitos_finais.md#RF14.2), [RF15](../../elicitacao/requisitos_finais.md#RF15), [RF09.1](../../elicitacao/requisitos_finais.md#RF09.1), [RF10](../../elicitacao/requisitos_finais.md#RF10), [RF04.6](../../elicitacao/requisitos_finais.md#RF04.6) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>, <a href="https://github.com/redjsun">Yzabella Miranda</a>, <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a>, <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a> e <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

## Léxico 5: <a id="LX05"></a>Exame

**Requisitos relacionados:** [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1), [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2), [RF09.1](../../elicitacao/requisitos_finais.md#RF09.1), [RF09.2](../../elicitacao/requisitos_finais.md#RF09.2), [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Exame" refere-se a procedimentos laboratoriais ou de imagem solicitados para fins diagnósticos.

<p align="center">Tabela 5: Léxico - Exame</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Exame | Objeto | - | - Procedimento laboratorial ou de imagem solicitado para diagnóstico. - Faz parte do [histórico](./lexicos.md#LX03) | - Apoia a investigação e monitoramento de condições clínicas.<br> - O [Beneficiário](./lexicos.md#LX01) pode visualizar exames realizdos  - O [Beneficiário](./lexicos.md#LX01) deve conseguir agendar exames| [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1), [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2), [RF09.1](../../elicitacao/requisitos_finais.md#RF09.1), [RF09.2](../../elicitacao/requisitos_finais.md#RF09.2), [RF17](../../elicitacao/requisitos_finais.md#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>, <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 6: <a id="LX06"></a>Coparticipação

**Requisitos relacionados:** [RF06.2](../../elicitacao/requisitos_finais.md#RF06.2), [RF09.4](../../elicitacao/requisitos_finais.md#RF09.4), [RF10](../../elicitacao/requisitos_finais.md#RF10), [RF20](../../elicitacao/requisitos_finais.md#RF20)

O termo "Coparticipação" é utilizado para descrever valores pagos pelo [Beneficiário](./lexicos.md#LX01) além da cobertura do [plano de Saúde](./lexicos.md#LX38).

<p align="center">Tabela 6: Léxico - Coparticipação</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Coparticipação | Objeto | - | - Percentual do valor pago pelo [Beneficiário](./lexicos.md#LX01) além da cobertura do [plano de Saúde](./lexicos.md#LX38).<br> - Faz parte do [histórico](./lexicos.md#LX03) | - O [Beneficiário](./lexicos.md#LX01) pode visualizar suas coparticipações<br> | [RF06.2](../../elicitacao/requisitos_finais.md#RF06.2), [RF09.4](../../elicitacao/requisitos_finais.md#RF09.4), [RF10](../../elicitacao/requisitos_finais.md#RF10), [RF20](../../elicitacao/requisitos_finais.md#RF20) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a> e <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 7: <a id="LX07"></a>Agendar (Marcar)

**Requisitos relacionados:** [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1), [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2), [RF13](../../elicitacao/requisitos_finais.md#RF13), [RF15](../../elicitacao/requisitos_finais.md#RF15), [RF10](../../elicitacao/requisitos_finais.md#RF10), [RF04.7](../../elicitacao/requisitos_finais.md#RF04.7)

O termo "Agendar" refere-se à ação de reservar um horário para consulta ou [exame](./lexicos.md#LX05). "Marcar" é considerado sinônimo.

<p align="center">Tabela 8: Léxico - Agendar</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Agendar | Verbo | Marcar | O [Beneficiário](./lexicos.md#LX01) acessa o GDF Saúde e executa a ação de reservar um horário para consulta ou [exame](./lexicos.md#LX05). | - O [Beneficiário](./lexicos.md#LX01) possui uma consulta ou [exame](./lexicos.md#LX05) agendado. | [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1), [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2), [RF13](../../elicitacao/requisitos_finais.md#RF13), [RF15](../../elicitacao/requisitos_finais.md#RF15), [RF10](../../elicitacao/requisitos_finais.md#RF10), [RF04.7](../../elicitacao/requisitos_finais.md#RF04.7) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>, <a href="https://github.com/redjsun">Yzabella Miranda</a>, <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a> e <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

## Léxico 8: <a id="LX08"></a>Cancelar (Desmarcar)

**Requisitos relacionados:** [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2), [RF04.8](../../elicitacao/requisitos_finais.md#RF04.8)

O termo "Cancelar" refere-se à ação de desmarcar uma consulta ou [exame](./lexicos.md#LX05) previamente agendado. "Desmarcar" é considerado sinônimo.

<p align="center">Tabela 9: Léxico - Cancelar</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Cancelar | Verbo | Desmarcar | - O [Beneficiário](./lexicos.md#LX01) acessa o sistema e desmarca uma consulta ou [exame](./lexicos.md#LX05) previamente agendado. | - Os horários ficam liberados.<br> - Cobranças são desfeitas.| [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2), [RF04.8](../../elicitacao/requisitos_finais.md#RF04.8) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a> e <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

## Léxico 9: <a id="LX09"></a>Agendamento (Reserva)

**Requisitos relacionados:** [RF15](../../elicitacao/requisitos_finais.md#RF15), [RF10](../../elicitacao/requisitos_finais.md#RF10), [RF04.8](../../elicitacao/requisitos_finais.md#RF04.8) e [RF04.7](../../elicitacao/requisitos_finais.md#RF04.7)

O termo "Agendamento" refere-se à reserva de horário para atendimento ou serviço no sistema de saúde. "Reserva" é considerado sinônimo.

<p align="center">Tabela 9: Léxico - Agendamento</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Agendamento | Objeto | Reserva | - Reserva de horário para atendimento ou serviço no sistema de saúde. - O agendamento é feito para uma [consulta](./lexicos.md#LX04) em um determinado horário. | Permite ao [Beneficiário](./lexicos.md#LX01) organizar e acompanhar seus compromissos. | [RF15](../../elicitacao/requisitos_finais.md#RF15), [RF10](../../elicitacao/requisitos_finais.md#RF10), [RF04.8](../../elicitacao/requisitos_finais.md#RF04.8) e [RF04.7](../../elicitacao/requisitos_finais.md#RF04.7) |

<p align="center">Fonte: Autoria de <a href="https://github.com/redjsun">Yzabella Miranda</a>, <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a> e <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

## Léxico 10: <a id="LX10"></a>Comprovante de Agendamento

**Requisitos relacionados:** [RF15](../../elicitacao/requisitos_finais.md#RF15)

O termo "Comprovante de Agendamento" refere-se ao documento digital que confirma a realização de um [agendamento](./lexicos.md#LX09).

<p align="center">Tabela 10: Léxico - Comprovante de Agendamento</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Comprovante de Agendamento | Objeto | - | - Documento digital que confirma a realização de um [agendamento](./lexicos.md#LX09). | - O usuário pode baixar um comprovante de agendamento | [RF15](../../elicitacao/requisitos_finais.md#RF15) |

<p align="center">Fonte: Autoria de <a href="https://github.com/redjsun">Yzabella Miranda</a></p>

## Léxico 11: <a id="LX11"></a>Exibir

**Requisitos relacionados:** [RF06.1](../../elicitacao/requisitos_finais.md#RF06.1), [RF06.2](../../elicitacao/requisitos_finais.md#RF06.2), [RF06.3](../../elicitacao/requisitos_finais.md#RF06.3), [RF06.4](../../elicitacao/requisitos_finais.md#RF06.4), [RF06.5](../../elicitacao/requisitos_finais.md#RF06.5), [RF16](../../elicitacao/requisitos_finais.md#RF16), [RF14.1](../../elicitacao/requisitos_finais.md#RF14.1), [RF14.2](../../elicitacao/requisitos_finais.md#RF14.2), [RNF15](../../elicitacao/requisitos_finais.md#RNF15), [RF03](../../elicitacao/requisitos_finais.md#RF03), [RF09.1](../../elicitacao/requisitos_finais.md#RF09.1), [RF09.2](../../elicitacao/requisitos_finais.md#RF09.2), [RF09.3](../../elicitacao/requisitos_finais.md#RF09.3), [RF09.4](../../elicitacao/requisitos_finais.md#RF09.4)

Os termos "Exibir", "Apresentar" e "Mostrar" são usados para indicar a apresentação de informações ao [Beneficiário](./lexicos.md#LX01).

<p align="center">Tabela 11: Léxico - Exibir</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Exibir | Verbo | Apresentar, Mostrar, Visualizar, Ver | - O sistema apresenta informações visuais na [interface](./lexicos.md#LX36) do sistema. | O [Beneficiário](./lexicos.md#LX01) consegue ver as informações sobre consultas, prazos, vencimentos, etc. | [RF06.1](../../elicitacao/requisitos_finais.md#RF06.1), [RF06.2](../../elicitacao/requisitos_finais.md#RF06.2), [RF06.3](../../elicitacao/requisitos_finais.md#RF06.3), [RF06.4](../../elicitacao/requisitos_finais.md#RF06.4), [RF06.5](../../elicitacao/requisitos_finais.md#RF06.5), [RF16](../../elicitacao/requisitos_finais.md#RF16),[RF14.1](../../elicitacao/requisitos_finais.md#RF14.1), [RF14.2](../../elicitacao/requisitos_finais.md#RF14.2), [RNF15](../../elicitacao/requisitos_finais.md#RNF15), [RF03](../../elicitacao/requisitos_finais.md#RF03) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>, <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/redjsun">Yzabella Miranda</a>, <a href="https://github.com/isaqzin">Isaque Camargos</a> e <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 12: <a id="LX12"></a>Carteirinha Digital (Carteirinha)

**Requisitos relacionados:** [RNF10](../../elicitacao/requisitos_finais.md#RNF10), [RNF13](../../elicitacao/requisitos_finais.md#RNF13), [RF03](../../elicitacao/requisitos_finais.md#RF03)

O termo "Carteirinha Digital" aparece em requisitos relacionados ao acesso rápido e [offline](./lexicos.md#LX13) à identificação do [Beneficiário](./lexicos.md#LX01). "Carteirinha" é considerado sinônimo.

<p align="center">Tabela 12: Léxico - Carteirinha Digital</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Carteirinha Digital | Objeto | Carteirinha | - Identificação virtual do [Beneficiário](./lexicos.md#LX01) no [plano de Saúde](./lexicos.md#LX38). | - O [Beneficiário](./lexicos.md#LX01) [visualiza](./lexicos.md#LX11) a sua carteirinha digital. | [RNF10](../../elicitacao/requisitos_finais.md#RNF10), [RNF13](../../elicitacao/requisitos_finais.md#RNF13), [RF03](../../elicitacao/requisitos_finais.md#RF03) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

## Léxico 13: <a id="LX13"></a>Modo Offline

**Requisitos relacionados:** [RNF13](../../elicitacao/requisitos_finais.md#RNF13), [RF03](../../elicitacao/requisitos_finais.md#RF03)

O termo "Modo Offline" refere-se à condição de funcionamento do aplicativo sem conexão à internet.

<p align="center">Tabela 13: Modo Offline</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Modo Offline | Estado | - | - Condição de funcionamento do aplicativo sem conexão à internet. | - Garante acesso contínuo a informações essenciais. | [RNF13](../../elicitacao/requisitos_finais.md#RNF13), [RF03](../../elicitacao/requisitos_finais.md#RF03) |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

## Léxico 14: <a id="LX14"></a>Prestador (Profissional Credenciado)

**Requisitos relacionados:** [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1), [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2), [RF18.1](../../elicitacao/requisitos_finais.md#RF18.1), [RF01.1](../../elicitacao/requisitos_finais.md#RF01.1), [RF01.2](../../elicitacao/requisitos_finais.md#RF01.2)

Os termos "Prestador" e "Profissional Credenciado" referem-se a profissionais, clínicas ou laboratórios integrantes da rede de atendimento.

<p align="center">Tabela 14: Léxico - Prestador</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Prestador | Objeto | Profissional Credenciado, Prestador de serviço | - Profissional, clínica ou laboratório integrante da Rede de Atendimento. | - Executa os serviços contratados pelos [usuários](./lexicos.md#LX01).<br> - O [Beneficiário](./lexicos.md#LX01) seleciona um prestador. | [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1), [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2), [RF18.1](../../elicitacao/requisitos_finais.md#RF18.1), [RF01.1](../../elicitacao/requisitos_finais.md#RF01.1), [RF01.2](../../elicitacao/requisitos_finais.md#RF01.2) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>, <a href="https://github.com/LucasAlves71">Lucas Alves</a> e <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

## Léxico 15: <a id="LX15"></a>Validar (Verificar, Conferir)

**Requisitos relacionados:** [RF07.4](../../elicitacao/requisitos_finais.md#RF07.4), [RF08.1](../../elicitacao/requisitos_finais.md#RF08.1)

Os termos "Validar", "Verificar" e "Conferir" estão relacionados à checagem de documentos e procedimentos.

<p align="center">Tabela 15: Léxico - Validar</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Validar | Verbo | Verificar, Conferir, Autenticar | - Ação de verificar a autenticidade e conformidade dos documentos ou procedimentos.<br> - O sistema valida as informações dos documentos e procedimentos | - Os documentos e procedimentos estão validados<br> - O [Beneficiário](./lexicos.md#LX01) pode utilizar o sistema | [RF07.4](../../elicitacao/requisitos_finais.md#RF07.4), [RF08.1](../../elicitacao/requisitos_finais.md#RF08.1) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 16: <a id="LX16"></a>Elegibilidade

**Requisitos relacionados:** [RF07.5](../../elicitacao/requisitos_finais.md#RF07.5)

O termo "Elegibilidade" está relacionado à condição que define se o indivíduo pode ser incluído no [plano de Saúde](./lexicos.md#LX38).

<p align="center">Tabela 16: Léxico - Elegibilidade</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Elegibilidade | Objeto | Aptidão, Qualificação | - Condição que define se o indivíduo pode ser incluído no [plano de Saúde](./lexicos.md#LX38).<br> - O [Beneficiário](./lexicos.md#LX01) está elegível para o plano de saúde | - Evita cadastros indevidos e garante o cumprimento das regras do [plano de Saúde](./lexicos.md#LX38). | [RF07.5](../../elicitacao/requisitos_finais.md#RF07.5) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 17: <a id="LX17"></a> TABGDFSAÚDE

**Requisitos relacionados:** [RF08.1](../../elicitacao/requisitos_finais.md#RF08.1)

O termo "TABGDFSAÚDE" refere-se à tabela de procedimentos autorizados e cobertos pelo [plano de Saúde](./lexicos.md#LX38).

<p align="center">Tabela 17: Léxico - TABGDFSAÚDE</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| TABGDFSAÚDE | Objeto | Tabela de procedimentos | - Tabela de procedimentos autorizados e cobertos pelo [plano de Saúde](./lexicos.md#LX38). | - O [Beneficiário](./lexicos.md#LX01) visualiza o que é permitido e financiado pelo [plano de Saúde](./lexicos.md#LX38). | [RF08.1](../../elicitacao/requisitos_finais.md#RF08.1) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 18: <a id="LX18"></a>DUT

**Requisitos relacionados:** [RF08.1](../../elicitacao/requisitos_finais.md#RF08.1)

O termo "DUT" refere-se à Diretriz de Utilização Técnica.

<p align="center">Tabela 18: Léxico - DUT</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| DUT | Objeto | Diretriz Técnica | - Diretriz de Utilização Técnica. | - Orienta decisões médicas e administrativas para autorizações. | [RF08.1](../../elicitacao/requisitos_finais.md#RF08.1) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 19: <a id="LX19"></a>Carência

**Requisitos relacionados:** [RF08.1](../../elicitacao/requisitos_finais.md#RF08.1), [RF16](../../elicitacao/requisitos_finais.md#RF16)

O termo "Carência" refere-se ao período em que o usuário ainda não tem direito a determinados serviços.

<p align="center">Tabela 19: Léxico - Carência</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Carência | Objeto | Período de espera | - Período em que o usuário ainda não tem direito a determinados serviços. - O [Beneficiário](./lexicos.md#LX01) possui um período de carência | - Controla o acesso gradual aos benefícios do [plano de Saúde](./lexicos.md#LX38). | [RF08.1](../../elicitacao/requisitos_finais.md#RF08.1), [RF16](../../elicitacao/requisitos_finais.md#RF16) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 20: <a id="LX20"></a>Exclusão

**Requisitos relacionados:** [RF08.1](../../elicitacao/requisitos_finais.md#RF08.1)

O termo "Exclusão" refere-se a procedimento ou situação não coberta pelo [plano de Saúde](./lexicos.md#LX38).

<p align="center">Tabela 20: Léxico - Exclusão</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Exclusão | Objeto | Não cobertura | - Procedimento ou situação não coberta pelo [plano de Saúde](./lexicos.md#LX38). | - Evita solicitações indevidas ou que violem as regras contratuais. | [RF08.1](../../elicitacao/requisitos_finais.md#RF08.1) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 21: <a id="LX21"></a>Solicitação Médica

**Requisitos relacionados:** [RF08.1](../../elicitacao/requisitos_finais.md#RF08.1)

O termo "Solicitação Médica" refere-se ao pedido emitido por profissional de saúde para execução de um procedimento.

<p align="center">Tabela 21: Léxico - Solicitação Médica</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Solicitação Médica | Objeto | Pedido médico, Prescrição | - Pedido emitido por profissional de saúde para execução de um procedimento.<br> - Os procedimentos da [TABGDFSAÚDE](./lexicos.md#LX17) podem estar excluídos. | - Inicia o processo de autorização técnica. | [RF08.1](../../elicitacao/requisitos_finais.md#RF08.1) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 22: <a id="LX22"></a>Análise Técnica

**Requisitos relacionados:** [RF08.1](../../elicitacao/requisitos_finais.md#RF08.1)

O termo "Análise Técnica" refere-se à avaliação feita pela equipe técnica para [validar](./lexicos.md#LX15) o procedimento.

<p align="center">Tabela 22: Léxico - Análise Técnica</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Análise Técnica | Objeto | Avaliação técnica, Perícia | - Avaliação feita pela equipe técnica para [validar](./lexicos.md#LX15) o procedimento. | - Assegura que apenas procedimentos elegíveis sejam autorizados. | [RF08.1](../../elicitacao/requisitos_finais.md#RF08.1) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 23: <a id="LX23"></a>Calendário Personalizado

**Requisitos relacionados:** [RF16](../../elicitacao/requisitos_finais.md#RF16)

O termo "Calendário Personalizado" refere-se à ferramenta visual que mostra eventos e prazos relacionados ao [plano de Saúde](./lexicos.md#LX38).

<p align="center">Tabela 23: Léxico - Calendário Personalizado</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Calendário Personalizado | Objeto | Agenda personalizada | - Ferramenta visual que mostra eventos e prazos relacionados ao [plano de Saúde](./lexicos.md#LX38).<br> - As [consultas](./lexicos.md#LX04) [agendadas](./lexicos.md#LX24), prazos de [carência](./lexicos.md#LX19) e [vencimento](./lexicos.md#LX25) são exibidos no calendário. | - Centraliza informações importantes e melhora a gestão da saúde pessoal.<br> - O [Beneficiário](./lexicos.md#LX01) pode [visualizar](./lexicos.md#LX11) o calendário. | [RF16](../../elicitacao/requisitos_finais.md#RF16) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 24: <a id="LX24"></a> Consulta Agendada

**Requisitos relacionados:** [RF16](../../elicitacao/requisitos_finais.md#RF16), [RF10](../../elicitacao/requisitos_finais.md#RF10), [RF04.8](../../elicitacao/requisitos_finais.md#RF04.8), [RF04.6](../../elicitacao/requisitos_finais.md#RF04.6) e [RF04.7](../../elicitacao/requisitos_finais.md#RF04.7)

O termo "Consulta Agendada" refere-se ao compromisso de atendimento clínico já registrado no sistema.

<p align="center">Tabela 24: Léxico - Consulta Agendada</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Consulta Agendada | Estado | Compromisso médico | - [Consulta](./lexicos.md#LX04) está registrada no sistema.<br> - O [Beneficiário](./lexicos.md#LX01) agendou uma consulta. | - | [RF16](../../elicitacao/requisitos_finais.md#RF16), [RF10](../../elicitacao/requisitos_finais.md#RF10), [RF04.8](../../elicitacao/requisitos_finais.md#RF04.8), [RF04.6](../../elicitacao/requisitos_finais.md#RF04.6) e [RF04.7](../../elicitacao/requisitos_finais.md#RF04.7)|

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a> e <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

## Léxico 25: <a id="LX25"></a>Vencimento

**Requisitos relacionados:** [RF16](../../elicitacao/requisitos_finais.md#RF16),[RF04.1](../../elicitacao/requisitos_finais.md#RF04.1)

O termo "Vencimento" refere-se à data limite para uso de um benefício, pagamento ou renovação.

<p align="center">Tabela 25: Léxico - Vencimento</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Vencimento | Objeto | Data limite, Prazo | Data limite para uso de um benefício, pagamento ou renovação. | Evita perdas de prazos e interrupções de serviços. | [RF16](../../elicitacao/requisitos_finais.md#RF16), [RF04.1](../../elicitacao/requisitos_finais.md#RF04.1)|

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a> e <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

## Léxico 26: <a id="LX26"></a>Denunciar

**Requisitos relacionados:** [RF18.1](../../elicitacao/requisitos_finais.md#RF18.1)

O termo "Denunciar" refere-se à ação de relatar comportamento inadequado ou antiético.

<p align="center">Tabela 26: Léxico - Denunciar</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Denunciar | Verbo | Reportar, Relatar | - Ação de relatar comportamento inadequado ou antiético.<br> - O [Beneficiário](./lexicos.md#LX01) relata uma denúncia no sistema. | - A denúncia é listada e fica vinculada à  | [RF18.1](../../elicitacao/requisitos_finais.md#RF18.1) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 27: <a id="LX27"></a>Conduta Inadequada

**Requisitos relacionados:** [RF18.1](../../elicitacao/requisitos_finais.md#RF18.1)

O termo "Conduta Inadequada" refere-se ao comportamento que fere princípios éticos ou profissionais.

<p align="center">Tabela 27: Léxico - Conduta Inadequada</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Conduta Inadequada | Objeto | Comportamento impróprio, Má conduta | Comportamento que fere princípios éticos ou profissionais. | Gera ações corretivas e melhora a segurança do [Beneficiário](./lexicos.md#LX01). | [RF18.1](../../elicitacao/requisitos_finais.md#RF18.1) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>


## Léxico 28: <a id="LX28"></a>Comunicar (Integrar)

**Requisitos relacionados:** [RNF09](../../elicitacao/requisitos_finais.md#RNF09)

O termo "Comunicar" refere-se à ação de integrar ou enviar dados ao sistema de folha de pagamento. "Integrar" é considerado sinônimo.

<p align="center">Tabela 28: Léxico - Comunicar</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Comunicar | Verbo | Integrar | - O sistema integra ou enviar dados ao sistema de folha de pagamento. | - A [folha de pagamento](./lexicos.md#LX29) está atualizada. | [RNF09](../../elicitacao/requisitos_finais.md#RNF09) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 29: <a id="LX29"></a>Folha de Pagamento

**Requisitos relacionados:** [RNF09](../../elicitacao/requisitos_finais.md#RNF09)

O termo "Folha de Pagamento" refere-se ao sistema responsável por calcular e efetuar pagamentos dos servidores.

<p align="center">Tabela 29: Léxico - Folha de Pagamento</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Folha de Pagamento | Objeto | - | - Sistema responsável por calcular e efetuar pagamentos dos servidores. | - Permite o desconto direto das mensalidades na remuneração do servidor. - O [Beneficiário](./lexicos.md#LX01) consulta a sua folha de pagamento. | [RNF09](../../elicitacao/requisitos_finais.md#RNF09) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 30: <a id="LX30"></a>Desconto de Mensalidade

**Requisitos relacionados:** [RNF09](../../elicitacao/requisitos_finais.md#RNF09)

O termo "Desconto de Mensalidade" refere-se ao valor deduzido automaticamente do pagamento do servidor.

<p align="center">Tabela 30: Léxico - Desconto de Mensalidade</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Desconto de Mensalidade | Objeto | - | - Valor deduzido automaticamente do pagamento do servidor. - A [folha de pagamento](./lexicos.md#LX29) desconta a mensalidade | Garante regularidade e facilita a gestão financeira do [plano de Saúde](./lexicos.md#LX38). | [RNF09](../../elicitacao/requisitos_finais.md#RNF09) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 31: <a id="LX31"></a>Interface consistente

**Requisitos relacionados:** [RNF01.1](../../elicitacao/requisitos_finais.md#RNF01.1), [RNF14](../../elicitacao/requisitos_finais.md#RNF14)

O termo "Interface" refere-se à estrutura visual e organizacional da interface do aplicativo que deve manter semelhança com o Portal Oficial.

<p align="center">Tabela 31: Léxico - Interface</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Interface | Objeto | - | - Estrutura visual e organizacional da interface do aplicativo.<br> - Deve ser consistente com o [portal oficial](./lexicos.md#LX32) | - Afeta diretamente a experiência do [Beneficiário](./lexicos.md#LX01), sendo essencial para garantir usabilidade, estética e coerência visual. | [RNF01.1](../../elicitacao/requisitos_finais.md#RNF01.1), [RNF14](../../elicitacao/requisitos_finais.md#RNF14) |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a> e <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

## Léxico 32: <a id="LX32"></a>Portal Oficial

**Requisitos relacionados:** [RNF14](../../elicitacao/requisitos_finais.md#RNF14)

O termo "Portal Oficial" refere-se ao site institucional do [plano de Saúde](./lexicos.md#LX38).

<p align="center">Tabela 32: Léxico - Portal Oficial</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Portal Oficial | Objeto | - | - Site institucional do [plano de Saúde](./lexicos.md#LX38), que serve como referência para identidade visual e navegação. | - Serve como base para a padronização visual e comportamental do aplicativo, reforçando a identidade do sistema e a confiança do [Beneficiário](./lexicos.md#LX01). | [RNF14](../../elicitacao/requisitos_finais.md#RNF14) |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

## Léxico 33: <a id="LX33"></a>Plano de Saúde

**Requisitos relacionados:** [RNF14](../../elicitacao/requisitos_finais.md#RNF14)

O termo "Plano de Saúde" refere-se à instituição responsável pela oferta de serviços médicos.

<p align="center">Tabela 33: Léxico - Plano de Saúde</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Plano de Saúde | Objeto | - | - Instituição responsável pela oferta de serviços médicos e pelo desenvolvimento do portal e aplicativo utilizados pelo [Beneficiário](./lexicos.md#LX01). | - Define as diretrizes de identidade visual que devem ser refletidas no aplicativo para garantir coerência e profissionalismo. | [RNF14](../../elicitacao/requisitos_finais.md#RNF14) |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

## Léxico 34: <a id="LX34"></a>Exigir autenticação via GovBR

**Requisitos relacionados:** [RF22](../../elicitacao/requisitos_finais.md#RF22)

O termo "Exigir" refere-se à ação de obrigar ou requerer um método específico de autenticação.

<p align="center">Tabela 34: Léxico - Exigir autenticação via GovBR</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Exigir autenticação via GovBR| Verbo | - | - O [Beneficiário](./lexicos.md#LX01) acessa o sistema e realiza [login](./lexicos.md#LX41) via GovBR. | - O [Beneficiário](./lexicos.md#LX01) realizou [login](./lexicos.md#LX41).<br> - O [Beneficiário](./lexicos.md#LX01) pode acessar o sistema | [RF22](../../elicitacao/requisitos_finais.md#RF22) |

<p align="center">Fonte: Autoria de <a href="https://github.com/redjsun">Yzabella Miranda</a></p>

---

## Léxico 35: <a id="LX35"></a>Login

**Requisitos relacionados:** [RF22](../../elicitacao/requisitos_finais.md#RF22), [RF19](../../elicitacao/requisitos_finais.md#RF19)

O termo "Login" refere-se ao acesso inicial do [Beneficiário](./lexicos.md#LX01) ao sistema após autenticação.

<p align="center">Tabela 35: Léxico - Login</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Login | Objeto | Autenticação, Acesso | - Acesso inicial do [Beneficiário](./lexicos.md#LX01) ao sistema após autenticação. | - O [Beneficiário](./lexicos.md#LX01) entra no aplicativo | [RF22](../../elicitacao/requisitos_finais.md#RF22), [RF19](../../elicitacao/requisitos_finais.md#RF19) |

<p align="center">Fonte: Autoria de <a href="https://github.com/redjsun">Yzabella Miranda</a> e <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

## Léxico 36: <a id="LX36"></a>Divulgar novas funcionalidades

**Requisitos relacionados:** [RF12.1](../../elicitacao/requisitos_finais.md#RF12.1), [RF12.2](../../elicitacao/requisitos_finais.md#RF12.2), [RF12.3](../../elicitacao/requisitos_finais.md#RF12.3), [RF12.4](../../elicitacao/requisitos_finais.md#RF12.4), [RF12.5](../../elicitacao/requisitos_finais.md#RF12.5), [RF12.6](../../elicitacao/requisitos_finais.md#RF12.6)

O termo "Divulgar novas funcionalidades" refere-se à ação de tornar públicas ou acessíveis as informações sobre novas funcionalidades.

<p align="center">Tabela 36: Léxico - Divulgar</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Divulgar | Verbo | - | - Ação de tornar públicas ou acessíveis as informações sobre novas funcionalidades. | - O [Beneficiário](./lexicos.md#LX01) pode visualizar as novas funcionalidades | [RF12.1](../../elicitacao/requisitos_finais.md#RF12.1), [RF12.2](../../elicitacao/requisitos_finais.md#RF12.2), [RF12.3](../../elicitacao/requisitos_finais.md#RF12.3), [RF12.4](../../elicitacao/requisitos_finais.md#RF12.4), [RF12.5](../../elicitacao/requisitos_finais.md#RF12.5), [RF12.6](../../elicitacao/requisitos_finais.md#RF12.6) |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

## Léxico 37: <a id="LX37"></a>Armazenar

**Requisitos relacionados:** [RNF11](../../elicitacao/requisitos_finais.md#RNF11)

O termo "Armazenar" refere-se à ação de preservar ou conservar algo em determinado estado.

<p align="center">Tabela 37: Léxico - Armazenar</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Armazenar | Verbo | Preservar, Manter | -  O sistema preserva ou conserva algo em determinado estado. | - O [histórico](./lexicos.md#LX03) de [notificações](./lexicos.md#LX02) está disponível para acesso pelo usuário durante o período estabelecido. | [RNF11](../../elicitacao/requisitos_finais.md#RNF11) |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 38: <a id="LX38"></a>Suporte

**Requisitos relacionados:** [RNF12](../../elicitacao/requisitos_finais.md#RNF12)

O termo "Suporte" refere-se ao sistema ou serviço que fornece assistência ao usuário.

<p align="center">Tabela 38: Léxico - Suporte</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Suporte | Objeto | Assistência, Ajuda | - Sistema ou serviço que fornece assistência ao usuário por diferentes canais de comunicação.<br> - O [Beneficiário](./lexicos.md#LX01) solicita atendimento do suporte. | - Melhora a usabilidade e a satisfação do usuário ao resolver dúvidas ou problemas encontrados durante o uso do aplicativo.<br> - O [Beneficiário](./lexicos.md#LX01) é atendido pelo sistema. | [RNF12](../../elicitacao/requisitos_finais.md#RNF12) |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 39: <a id="LX39"></a>Chat

**Requisitos relacionados:** [RNF12](../../elicitacao/requisitos_finais.md#RNF12)

O termo "Chat" refere-se a um canal de comunicação em tempo real via texto.

<p align="center">Tabela 39: Léxico - Chat</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Chat | Objeto | Mensageiro | - Canal de comunicação em tempo real via texto entre o usuário e a equipe de [suporte](./lexicos.md#LX38).<br> - O [Beneficiário](./lexicos.md#LX01) conversa com o [suporte](./lexicos.md#LX38) pelo chat. | - Facilita a interação rápida e eficiente, fornecendo respostas imediatas a dúvidas e problemas. | [RNF12](../../elicitacao/requisitos_finais.md#RNF12) |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico  40: <a id="LX40"></a>Favoritar horários de consulta



**Requisitos relacionados:** [RF10](../../elicitacao/requisitos_finais.md#RF10)

O termo "Favoritar" refere-se à ação de marcar horários de consulta preferidos para uso futuro.

<p align="center">Tabela 40: Léxico - Favoritar</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Favoritar | Verbo | Marcar como preferido | - O [Beneficiário](./lexicos.md#LX01) salva horários de consulta preferidos para [agendamento](./lexicos.md#LX09) futuro. | - O [horário está favoritado](./lexicos.md#LX41).<br> - Os horários favoritos podem ser visualizados com destaque. | [RF10](../../elicitacao/requisitos_finais.md#RF10) |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 41: <a id="LX41"></a>Horário está favoritado

**Requisitos relacionados:** [RF10](../../elicitacao/requisitos_finais.md#RF10)

O termo "Horários Preferidos" refere-se aos períodos de tempo salvos pelo [Beneficiário](./lexicos.md#LX01) como preferenciais para consultas.

<p align="center">Tabela 41: Léxico - Horário está favoritado</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Horário está favoritado | Estado | Horários favoritos | - Horários salvos pelo [Beneficiário](./lexicos.md#LX01) como preferenciais para [agendamento](./lexicos.md#LX09) de consultas.<br> - O horário foi escolhido como favorito. | - Consulta é agendada no horário favorito. | [RF10](../../elicitacao/requisitos_finais.md#RF10) |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 42: <a id="LX42"></a>Solicitar Reembolso

**Requisitos relacionados:** [RF20](../../elicitacao/requisitos_finais.md#RF20)

O termo "Solicitar Reembolso" refere-se à ação de enviar uma requisição formal para devolução de valores cobrados indevidamente.

<p align="center">Tabela 42: Léxico - Solicitar Reembolso</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Solicitar Reembolso | Verbo | Pedir ressarcimento | Ação de enviar uma requisição formal ao sistema para análise e possível devolução de valores de coparticipação cobrados indevidamente. | Inicia o processo de [reembolso](./lexicos.md#LX42) para análise e eventual correção financeira a favor do usuário. | [RF20](../../elicitacao/requisitos_finais.md#RF20) |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 43: <a id="LX43"></a>Agendamento com Pagamento Automático

**Requisitos relacionados:** [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1), [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2)

O termo refere-se ao processo completo de agendamento que inclui a transação financeira automática.

<p align="center">Tabela 43: Léxico - Agendamento com Pagamento Automático</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Agendamento com Pagamento Automático | Objeto | - | Processo de reserva de consulta/exame que inclui cobrança automática ao prestador da rede | Simplifica o processo para o usuário e garante pagamento imediato ao prestador | [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1), [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 44: <a id="LX44"></a>Valor de Consulta

**Requisitos relacionados:** [RF06.1](../../elicitacao/requisitos_finais.md#RF06.1)

O termo refere-se ao preço específico cobrado por cada clínica.

<p align="center">Tabela 44: Léxico - Valor de Consulta</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Valor de Consulta | Objeto | Preço, Custo | Valor específico cobrado por cada clínica para diferentes tipos de consulta | Permite comparação de preços e planejamento financeiro | [RF06.1](../../elicitacao/requisitos_finais.md#RF06.1) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 45: <a id="LX45"></a>Cálculo de Coparticipação

**Requisitos relacionados:** [RF06.2](../../elicitacao/requisitos_finais.md#RF06.2)

O termo refere-se ao processo automático de determinação da parte do valor que cabe ao beneficiário.

<p align="center">Tabela 45: Léxico - Cálculo de Coparticipação</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Cálculo de Coparticipação | Verbo | - | Processo automático que determina a parte do valor que cabe ao beneficiário | Garante transparência nos custos compartilhados | [RF06.2](../../elicitacao/requisitos_finais.md#RF06.2) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 46: <a id="LX46"></a>Demonstrativo de IR

**Requisitos relacionados:** [RF06.3](../../elicitacao/requisitos_finais.md#RF06.3), [RF06.4](../../elicitacao/requisitos_finais.md#RF06.4)

O termo refere-se ao documento fiscal para declaração de impostos.

<p align="center">Tabela 46: Léxico - Demonstrativo de IR</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Demonstrativo de IR | Objeto | Comprovante fiscal | Documento que comprova despesas médicas para declaração do imposto de renda | Facilita a declaração anual de impostos | [RF06.3](../../elicitacao/requisitos_finais.md#RF06.3), [RF06.4](../../elicitacao/requisitos_finais.md#RF06.4) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 47: <a id="LX47"></a>Extrato Financeiro

**Requisitos relacionados:** [RF06.5](../../elicitacao/requisitos_finais.md#RF06.5)

O termo refere-se ao relatório financeiro atualizado diariamente.

<p align="center">Tabela 47: Léxico - Extrato Financeiro</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Extrato Financeiro | Objeto | Histórico financeiro | Relatório atualizado diariamente com todas as transações financeiras relacionadas ao plano | Permite acompanhamento de gastos e pagamentos | [RF06.5](../../elicitacao/requisitos_finais.md#RF06.5) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 48: <a id="LX48"></a>Painel de Metas de Saúde

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo refere-se à interface gamificada de acompanhamento de metas de saúde.

<p align="center">Tabela 48: Léxico - Painel de Metas de Saúde</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Painel de Metas de Saúde | Objeto | Dashboard de saúde | Interface que exibe metas personalizadas com elementos de gamificação | Incentiva o acompanhamento preventivo da saúde | [RF17](../../elicitacao/requisitos_finais.md#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---
## Léxico 49: <a id="LX49"></a>Filtro

**Requisitos relacionados:** [RF01.1](../../elicitacao/requisitos_finais.md#RF01.1), [RF01.2](../../elicitacao/requisitos_finais.md#RF01.2), [RF01.3](../../elicitacao/requisitos_finais.md#RF01.3), [RF01.4](../../elicitacao/requisitos_finais.md#RF01.4), [RF01.5](../../elicitacao/requisitos_finais.md#RF01.5)

O termo "Filtro" refere-se à ferramenta que permite ao usuário refinar os resultados de uma busca.

<p align="center">Tabela 49: Léxico - Filtro</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Filtro | Objeto | Critério de busca | Ferramenta que permite ao [Beneficiário](./lexicos.md#LX01) refinar os resultados de uma busca por [prestadores](./lexicos.md#LX14), combinando critérios como [especialidade](./lexicos.md#LX51) e [proximidade](./lexicos.md#LX50). | Permite que o usuário encontre informações de forma mais rápida e precisa, melhorando a usabilidade da funcionalidade de pesquisa. | [RF01.1](../../elicitacao/requisitos_finais.md#RF01.1), [RF01.2](../../elicitacao/requisitos_finais.md#RF01.2), [RF01.3](../../elicitacao/requisitos_finais.md#RF01.3), [RF01.4](../../elicitacao/requisitos_finais.md#RF01.4), [RF01.5](../../elicitacao/requisitos_finais.md#RF01.5) |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---
## Léxico 50: <a id="LX50"></a>Proximidade

**Requisitos relacionados:** [RF01.4](../../elicitacao/requisitos_finais.md#RF01.4)

O termo "Proximidade" refere-se ao critério de busca baseado na distância geográfica entre o usuário e o prestador.

<p align="center">Tabela 50: Léxico - Proximidade</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Proximidade | Objeto | Distância | Critério de [filtro](./lexicos.md#LX49) que ordena ou seleciona [prestadores](./lexicos.md#LX14) com base na distância geográfica (até 10 km) em relação à localização atual do [Beneficiário](./lexicos.md#LX01). | Facilita a localização de serviços de saúde convenientes e de fácil acesso para o usuário. | [RF01.4](../../elicitacao/requisitos_finais.md#RF01.4) |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---
## Léxico 51: <a id="LX51"></a>Especialidade

**Requisitos relacionados:** [RF01.5](../../elicitacao/requisitos_finais.md#RF01.5)

O termo "Especialidade" refere-se à área de atuação de um profissional ou serviço de saúde.

<p align="center">Tabela 51: Léxico - Especialidade</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Especialidade | Objeto | Área Médica | Critério de [filtro](./lexicos.md#LX49) que permite ao [Beneficiário](./lexicos.md#LX01) pesquisar por [prestadores](./lexicos.md#LX14) com base em sua área de atuação (ex: Cardiologia, Psicologia). | Direciona o usuário ao profissional mais adequado para sua necessidade de saúde. | [RF01.5](../../elicitacao/requisitos_finais.md#RF01.5) |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---
## Léxico 52: <a id="LX52"></a>Avaliação

**Requisitos relacionados:** [RF02.1](../../elicitacao/requisitos_finais.md#RF02.1), [RF02.4](../../elicitacao/requisitos_finais.md#RF02.4)

O termo "Avaliação" refere-se ao sistema de feedback onde o usuário atribui uma nota a um atendimento.

<p align="center">Tabela 52: Léxico - Avaliação</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Avaliação | Objeto | Nota, Classificação | Feedback fornecido pelo [Beneficiário](./lexicos.md#LX01) sobre um atendimento, utilizando uma escala Likert de 1 a 5. As avaliações são usadas para gerar uma nota média para os [prestadores](./lexicos.md#LX14). | A nota média impacta a ordenação dos prestadores na busca, ajudando outros usuários a tomar decisões informadas. | [RF02.1](../../elicitacao/requisitos_finais.md#RF02.1), [RF02.4](../../elicitacao/requisitos_finais.md#RF02.4) |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---
## Léxico 53: <a id="LX53"></a>Comentários

**Requisitos relacionados:** [RF02.2](../../elicitacao/requisitos_finais.md#RF02.2), [RF02.3](../../elicitacao/requisitos_finais.md#RF02.3)

O termo "Comentários" refere-se ao texto descritivo que o usuário pode deixar sobre um atendimento.

<p align="center">Tabela 53: Léxico - Comentários</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Comentários | Objeto | Depoimento, Opinião | Texto escrito que um [Beneficiário](./lexicos.md#LX01) pode registrar para detalhar sua experiência com um [prestador](./lexicos.md#LX14). O sistema pode classificar esses comentários. | Permite que outros usuários leiam experiências detalhadas, complementando a [avaliação](./lexicos.md#LX52) numérica e fornecendo mais contexto. | [RF02.2](../../elicitacao/requisitos_finais.md#RF02.2), [RF02.3](../../elicitacao/requisitos_finais.md#RF02.3) |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---
## Léxico 54: <a id="LX54"></a>Chatbot

**Requisitos relacionados:** [RF21.1](../../elicitacao/requisitos_finais.md#RF21.1)

O termo "Chatbot" refere-se a um assistente conversacional automatizado para triagem de especialidades.

<p align="center">Tabela 54: Léxico - Chatbot</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Chatbot | Objeto | Assistente Virtual | Sistema conversacional automatizado que interage com o [Beneficiário](./lexicos.md#LX01) para identificar sintomas e recomendar a [especialidade](./lexicos.md#LX51) médica mais adequada. | Direciona o usuário para o cuidado correto, otimizando a busca por profissionais e agilizando o processo de agendamento. | [RF21.1](../../elicitacao/requisitos_finais.md#RF21.1) |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---
## Léxico 55: <a id="LX55"></a>Desempenho

**Requisitos relacionados:** [RNF02.1](../../elicitacao/requisitos_finais.md#RNF02.1)

O termo "Desempenho" refere-se à velocidade e fluidez com que o sistema responde às ações do usuário.

<p align="center">Tabela 55: Léxico - Desempenho</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Desempenho | Atributo | Velocidade, Tempo de Resposta | Medida da rapidez com que a [interface](./lexicos.md#LX31) do aplicativo responde às interações do [Beneficiário](./lexicos.md#LX01). O objetivo é que 95% das ações tenham um tempo de resposta de até 2 segundos. | Garante uma experiência de uso fluida e sem atrasos, o que afeta diretamente a satisfação e a usabilidade do aplicativo. | [RNF02.1](../../elicitacao/requisitos_finais.md#RNF02.1) |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---
## Léxico 56: <a id="LX56"></a>Segurança de Dados

**Requisitos relacionados:** [RNF03.1.1](../../elicitacao/requisitos_finais.md#RNF03.1.1), [RNF03.2.1](../../elicitacao/requisitos_finais.md#RNF03.2.1), [RNF07](../../elicitacao/requisitos_finais.md#RNF07)

O termo "Segurança de Dados" refere-se às medidas de proteção para informações sensíveis do usuário.

<p align="center">Tabela 56: Léxico - Segurança de Dados</p>

| Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| Segurança de Dados | Objeto | Proteção de Dados | Conjunto de medidas técnicas, como criptografia e autenticação de dois fatores, implementadas para proteger os dados pessoais e de saúde dos [beneficiários](./lexicos.md#LX01) contra acessos não autorizados. | Assegura a confidencialidade e a integridade das informações do usuário, em conformidade com a LGPD, e aumenta a confiança no uso do aplicativo. | [RNF03.1](../../elicitacao/requisitos_finais.md#RNF03.1), [RNF03.2](../../elicitacao/requisitos_finais.md#RNF03.2) |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

## Referência Bibliográfica

SAYÃO, Miriam, CARVALHO, Gustavo. **Construção do léxico de aplicações**. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: Disponível em: <http://www.nilc.icmc.usp.br/til/til2006/0030.pdf>. Acesso em 15 de maio de 2025.

SERRANO, Milene; SERRANO, Maurício. **Engenharia de Requisitos – Aula 10: Modelagem de Requisitos com Casos de Uso**. Brasília: Universidade de Brasília – FGA, 2024. 29 slides. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 15 maio 2025.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| --- | --- | --- | --- | --- |
|`1.0`|15/05/2025|Contribuiram criando os seus respectivos léxicos em outra plataforma, mais detalhado em [Integrantes do Grupo](./lexicos.md/#integrantes) |[Ana Luiza Soares](https://github.com/Ana-Luiza-SC) [Isaque Camargos](https://github.com/isaqzin) [Kaleb de Souza](https://github.com/kalebmacedo) [Lucas Alves](https://github.com/LucasAlves71) [Matheus de Alcântara](https://github.com/matheusdealcantara) [Othavio Bolzan](https://github.com/bolzanMGB) [Yzabella Miranda](https://github.com/redjsun)|[Lucas Alves](https://github.com/LucasAlves71)|
| `1.1` | 16/05/2025 | Criação do documento e adição dos léxicos dos requisitos funcionais RF09, RF10 e RF20, além dos requisitos não funcionais RNF11 e RNF12 | [Matheus de Alcântara](https://github.com/matheusdealcantara) | [Lucas Alves](https://github.com/LucasAlves71) |
| `1.2` | 18/05/2025 | Transcrição de todos os léxicos e adição de rastreabilidade | [Matheus de Alcântara](https://github.com/matheusdealcantara) e [Isaque Camargos](https://github.com/isaqzin) | [Lucas Alves](https://github.com/LucasAlves71) |
| `1.3` | 20/06/2025 | Adição dos léxicos para os requisitos refinados RF05.1, RF05.2, RF06.1-RF06.5 e RF17 | [Kaleb Macedo](https://github.com/kalebmacedo) | [Matheus de Alcântara](https://github.com/matheusdealcantara) |
| `1.4` | 19/06/2025 | Correção da rastreabilidade para as novas versões dos requisitos RF09.1, RF09.2, RF09.3, RF09.4, RF10, RF20, RNF11 e RNF12 | [Matheus de Alcântara](https://github.com/matheusdealcantara) | [Isaque Camargos](https://github.com/isaqzin) |
| `1.5` | 21/06/2025 | Correção na rastreabilidado dos requisitos que faltavam e na rastrebailidade dos léxicos para padronizar os ids, além de criar novos léxicos para os meus RNF e RF que não haviam léxicos | [Matheus de Alcântara](https://github.com/matheusdealcantara) | [Isaque Camargos](https://github.com/isaqzin) |
| `1.6` | 21/06/2025 | Adição de sinônimos aos léxicos com base nos meus cenários | [Lucas Alves](https://github.com/LucasAlves71) | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) |
|`1.7`  | 22/06/2025  | Ajuste dos léxicos dos requisios RF22, RF14.1 e RF14.2 | [Yzabella Miranda](https://github.com/redjsun) | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) |
