# Léxicos

## Introdução

Este documento apresenta os léxicos identificados no projeto GDF Saúde, agrupando termos duplicados ou sinônimos e indicando em quais requisitos cada léxico foi citado. Para cada léxico, é apresentada uma breve introdução, a tabela consolidada com os requisitos relacionados e, quando aplicável, os sinônimos encontrados. As tabelas estão enumeradas conforme a ordem de apresentação.

## <a id="integrantes"></a>Integrantes do Grupo

A tabela a seguir apresenta todos os integrantes da equipe e suas respectivas contribuições na construção dos léxicos durante o projeto.

<p align="center">Tabela 1 - Integrantes do grupo envolvidos</p>

| Nome | Contribuição |
| --- | --- |
| [Matheus de Alcântara](https://github.com/matheusdealcantara) | Criou os léxicos referentes aos requisitos: [RF09](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF09), [RF10](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF10), [RF20](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF20), [RNF11](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF11) e [RNF12](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF12). Elaborou o documento inicial e contribuiu na organização geral do material que estava na plataforma <a href="https://stackedit.io/app#">StackEdit</a>. Por fim, em dupla com o [Isaque Camargos](https://github.com/isaqzin) fez introdução, metodologia, deixou os léxicos com hyperlinks entre si. |
| [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) | Desenvolveu léxicos para os requisitos [RF01](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF01), [RF02](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF02), [RF21](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF21), [RNF01](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF01), [RNF02](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF02) e [RNF03](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF03) |
| [Lucas Alves](https://github.com/LucasAlves71) | Elaborou os léxicos dos requisitos refinados [RF07.1](../../elicitacao/requisitos_finais.md#RF07.1), [RF07.2](../../elicitacao/requisitos_finais.md#RF07.2), [RF07.3](../../elicitacao/requisitos_finais.md#RF07.3), [RF07.4](../../elicitacao/requisitos_finais.md#RF07.4), [RF07.5](../../elicitacao/requisitos_finais.md#RF07.5), [RF08](../../elicitacao/requisitos_finais.md#RF08), [RF18](../../elicitacao/requisitos_finais.md#RF18), além de [RF16](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF16), [RNF09](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF09) e [RNF10](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF10). Atualizou os léxicos para refletir os novos casos de uso e cenários. |
| [Kaleb Macedo](https://github.com/kalebmacedo) | Responsável pelos léxicos dos requisitos [RF05](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF05), [RF06](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF06), [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17), [RNF07](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF07) e [RNF08](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF08) e pela adição dos requisitos refinados aos léxicos existentes. |
| [Othavio Bolzan](https://github.com/bolzanMGB) | Desenvolveu léxicos para os requisitos [RF11](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF11), [RF12](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF12), [RNF13](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF13) e [RNF14](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF14) |
| [Yzabella Miranda](https://github.com/redjsun) | Elaborou léxicos dos requisitos [RNF15](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF15), [RNF16](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF16), [RF13](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF13), [RF14](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF14) e [RF15](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF15) |
| [Isaque Camargos](https://github.com/isaqzin) | Adicionou a quais léxicos os requisitos [RF04](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF04), [RF03](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF03) e [RF19](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF19) se relacionavam. Contribuiu na organização do material que estava na plataforma <a href="https://stackedit.io/app#">StackEdit</a>. Por fim, em dupla com o [Matheus de Alcântara](https://github.com/matheusdealcantara) fez introdução, metodologia, deixou os léxicos com hyperlinks entre si. |

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a> e <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

## Metodologia

A elaboração dos léxicos descritos neste documento foi conduzida com base na técnica de modelagem de linguagem conhecida como Léxico Ampliado da Linguagem (LAL), uma abordagem amplamente utilizada na Engenharia de Requisitos para descrever termos relevantes do domínio de forma clara e contextualizada.

Cada léxico foi construído a partir da análise individual de um requisito (funcional ou não funcional), com o objetivo de identificar os principais termos operacionais, objetos e atributos envolvidos no sistema. A técnica adotada segue a estrutura apresentada nos slides Requisitos - Aula 10, de Milene Serrano e Maurício Serrano, composto por:

- Termo: Nome do conceito identificado no requisito.
- Tipo: Classificação do termo como verbo, objeto ou atributo.
- Noção: Definição do termo dentro do contexto do sistema, explicando seu significado e uso.
- Impacto: Consequências ou importância do termo para o funcionamento do sistema e para o usuário.

A extração dos termos foi feita com base em leitura interpretativa dos requisitos refinados, casos de uso e cenários, buscando classificar em verbos, objetos e estados que sejam essenciais para o entendimento do funcionamento do sistema e sua interação com os usuários. Para cada tipo de classificação o conteúdo em noção e impacto devem ser preenchidos seguindo o seguinte padrão: 

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

## Léxico 01: Beneficiário

**Requisitos relacionados:** [RF07.1](../../elicitacao/requisitos_finais.md#RF07.1), [RF07.2](../../elicitacao/requisitos_finais.md#RF07.2), [RF07.3](../../elicitacao/requisitos_finais.md#RF07.3), [RF07.4](../../elicitacao/requisitos_finais.md#RF07.4), [RF07.5](../../elicitacao/requisitos_finais.md#RF07.5), [RF08](../../elicitacao/requisitos_finais.md#RF08), [RF18](../../elicitacao/requisitos_finais.md#RF18)

O termo "Beneficiário" refere-se aos titulares, dependentes e optantes do plano GDF Saúde que utilizam o sistema.

<p align="center">Tabela 2: Léxico 01 - Beneficiário</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX01 | Beneficiário | Objeto | Titular, Dependente, Optante, Usuário | Pessoa cadastrada como titular, dependente ou optante do plano GDF Saúde, que pode acessar funcionalidades do sistema, realizar solicitações, anexar documentos e registrar denúncias. | Permite rastrear ações e permissões no sistema, garantindo que apenas usuários elegíveis possam acessar funcionalidades específicas. | [RF07.1](../../elicitacao/requisitos_finais.md#RF07.1), [RF07.2](../../elicitacao/requisitos_finais.md#RF07.2), [RF07.3](../../elicitacao/requisitos_finais.md#RF07.3), [RF07.4](../../elicitacao/requisitos_finais.md#RF07.4), [RF07.5](../../elicitacao/requisitos_finais.md#RF07.5), [RF08](../../elicitacao/requisitos_finais.md#RF08), [RF18](../../elicitacao/requisitos_finais.md#RF18) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 15: Validar (Verificar, Conferir)

**Requisitos relacionados:** [RF07.4](../../elicitacao/requisitos_finais.md#RF07.4), [RF08](../../elicitacao/requisitos_finais.md#RF08)

Os termos "Validar", "Verificar" e "Conferir" estão relacionados à checagem de documentos e procedimentos apresentados no cadastro ou em solicitações.

<p align="center">Tabela 16: Léxico 15 - Validar</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX15 | Validar | Verbo | Verificar, Conferir | Ação do sistema de checar a autenticidade e conformidade dos documentos anexados no cadastro de titulares, dependentes e optantes, bem como de procedimentos médicos solicitados. | Garante que apenas documentos e procedimentos válidos sejam aceitos, evitando fraudes e erros no cadastro e nas autorizações. | [RF07.4](../../elicitacao/requisitos_finais.md#RF07.4), [RF08](../../elicitacao/requisitos_finais.md#RF08) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 16: Elegibilidade

**Requisitos relacionados:** [RF07.5](../../elicitacao/requisitos_finais.md#RF07.5)

O termo "Elegibilidade" está relacionado à condição que define se o titular, dependente ou optante pode ser incluído no plano de saúde.

<p align="center">Tabela 17: Léxico 16 - Elegibilidade</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX16 | Elegibilidade | Objeto | - | Condição avaliada pelo sistema durante o cadastro para verificar se o usuário atende aos critérios do plano. | Evita cadastros indevidos e garante o cumprimento das regras do plano de saúde. | [RF07.5](../../elicitacao/requisitos_finais.md#RF07.5) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 17: TABGDFSAÚDE

**Requisitos relacionados:** [RF08](../../elicitacao/requisitos_finais.md#RF08)

O termo "TABGDFSAÚDE" refere-se à tabela de procedimentos autorizados e cobertos pelo plano de saúde.

<p align="center">Tabela 18: Léxico 17 - TABGDFSAÚDE</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX17 | TABGDFSAÚDE | Objeto | - | Tabela consultada pelo sistema para verificar se um procedimento está coberto, exige análise técnica ou está sujeito a carência/exclusão. | Permite automatizar a autorização de procedimentos e garantir conformidade com as regras do plano. | [RF08](../../elicitacao/requisitos_finais.md#RF08) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 18: DUT

**Requisitos relacionados:** [RF08](../../elicitacao/requisitos_finais.md#RF08)

O termo "DUT" refere-se à Diretriz de Utilização Técnica, utilizada para análise de procedimentos médicos.

<p align="center">Tabela 19: Léxico 18 - DUT</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX18 | DUT | Objeto | - | Diretriz consultada pelo sistema e analistas técnicos para avaliar a necessidade de autorização prévia de procedimentos. | Orienta decisões médicas e administrativas para autorizações. | [RF08](../../elicitacao/requisitos_finais.md#RF08) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 19: Carência

**Requisitos relacionados:** [RF08](../../elicitacao/requisitos_finais.md#RF08)

O termo "Carência" refere-se ao período em que o usuário ainda não tem direito a determinados serviços do plano.

<p align="center">Tabela 20: Léxico 19 - Carência</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX19 | Carência | Objeto | - | Período controlado pelo sistema para liberar gradualmente o acesso do beneficiário a determinados procedimentos. | Garante o cumprimento das regras contratuais e evita uso indevido dos serviços. | [RF08](../../elicitacao/requisitos_finais.md#RF08) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 20: Exclusão

**Requisitos relacionados:** [RF08](../../elicitacao/requisitos_finais.md#RF08)

O termo "Exclusão" refere-se a procedimentos ou situações não cobertas pelo plano de saúde.

<p align="center">Tabela 21: Léxico 20 - Exclusão</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX20 | Exclusão | Objeto | - | Procedimento ou situação identificada pelo sistema como não coberta, bloqueando solicitações e autorizações. | Evita solicitações indevidas e garante o cumprimento das regras do plano. | [RF08](../../elicitacao/requisitos_finais.md#RF08) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 21: Solicitação Médica

**Requisitos relacionados:** [RF08](../../elicitacao/requisitos_finais.md#RF08)

O termo "Solicitação Médica" refere-se ao pedido emitido por profissional de saúde para execução de um procedimento.

<p align="center">Tabela 22: Léxico 21 - Solicitação Médica</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX21 | Solicitação Médica | Objeto | - | Pedido anexado pelo usuário ou profissional de saúde ao solicitar autorização de procedimento. | Inicia o processo de análise técnica e autorização. | [RF08](../../elicitacao/requisitos_finais.md#RF08) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 22: Análise Técnica

**Requisitos relacionados:** [RF08](../../elicitacao/requisitos_finais.md#RF08)

O termo "Análise Técnica" refere-se à avaliação feita pela equipe técnica para validar o procedimento solicitado.

<p align="center">Tabela 23: Léxico 22 - Análise Técnica</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX22 | Análise Técnica | Objeto | - | Avaliação realizada por analista técnico quando o procedimento exige autorização prévia, conforme DUT e TABGDFSAÚDE. | Garante que apenas procedimentos elegíveis e justificados sejam autorizados. | [RF08](../../elicitacao/requisitos_finais.md#RF08) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 26: Denunciar

**Requisitos relacionados:** [RF18](../../elicitacao/requisitos_finais.md#RF18)

O termo "Denunciar" refere-se à ação de relatar comportamento inadequado ou antiético de profissionais credenciados.

<p align="center">Tabela 27: Léxico 26 - Denunciar</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX26 | Denunciar | Verbo | - | Ação do beneficiário de registrar uma denúncia no sistema, preenchendo formulário e anexando evidências, se houver. | Permite rastrear e tratar condutas inadequadas, promovendo segurança e ética na rede credenciada. | [RF18](../../elicitacao/requisitos_finais.md#RF18) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 27: Conduta Inadequada

**Requisitos relacionados:** [RF18](../../elicitacao/requisitos_finais.md#RF18)

O termo "Conduta Inadequada" refere-se ao comportamento que fere princípios éticos ou profissionais por parte de profissionais credenciados.

<p align="center">Tabela 28: Léxico 27 - Conduta Inadequada</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX27 | Conduta Inadequada | Objeto | - | Comportamento relatado em denúncias, analisado pelo sistema e equipe responsável. | Gera ações corretivas e melhora a segurança do beneficiário. | [RF18](../../elicitacao/requisitos_finais.md#RF18) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 28: Comunicar (Integrar)

**Requisitos relacionados:** [RNF09](../../elicitacao/requisitos_finais.md#RNF09)

O termo "Comunicar" refere-se à ação de integrar ou enviar dados ao sistema de folha de pagamento. "Integrar" é considerado sinônimo.

<p align="center">Tabela 29: Léxico 28 - Comunicar</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX28 | Comunicar | Verbo | Integrar | - O sistema integra ou enviar dados ao sistema de folha de pagamento. | - A [folha](./lexicos.md/#folha_pagamento) [de](./lexicos.md/#folha_pagamento) [pagamento](./lexicos.md/#folha_pagamento) está atualizada. | [RNF09](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF09) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 29: Folha de Pagamento

**Requisitos relacionados:** [RNF09](../../elicitacao/requisitos_finais.md#RNF09)

O termo "Folha de Pagamento" refere-se ao sistema responsável por calcular e efetuar pagamentos dos servidores.

<p align="center">Tabela 30: Léxico 29 - Folha de Pagamento</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX29 | Folha de Pagamento | Objeto | - | - Sistema responsável por calcular e efetuar pagamentos dos servidores. | - Permite o desconto direto das mensalidades na remuneração do servidor.<br>- O [Beneficiário](./lexicos.md/#usuario) consulta a sua folha de pagamento. | [RNF09](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF09) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 30: Desconto de Mensalidade

**Requisitos relacionados:** [RNF09](../../elicitacao/requisitos_finais.md#RNF09)

O termo "Desconto de Mensalidade" refere-se ao valor deduzido automaticamente do pagamento do servidor.

<p align="center">Tabela 31: Léxico 30 - Desconto de Mensalidade</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX30 | Desconto de Mensalidade | Objeto | - | - Valor deduzido automaticamente do pagamento do servidor.<br>- A [folha](./lexicos.md/#folha_pagamento) [de](./lexicos.md/#folha_pagamento) [pagamento](./lexicos.md/#folha_pagamento) desconta a mensalidade | Garante regularidade e facilita a gestão financeira do [plano de Saúde](./lexicos.md/#plano_saude). | [RNF09](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF09) |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## Léxico 31: Interface consistente

**Requisitos relacionados:** [RNF01.1](../../elicitacao/requisitos_finais.md#RNF01.1), [RNF14](../../elicitacao/requisitos_finais.md#RNF14)

O termo "Interface" refere-se à estrutura visual e organizacional da interface do aplicativo que deve manter semelhança com o Portal Oficial.

<p align="center">Tabela 32: Léxico 31 - Interface</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX31 | Interface | Objeto | - | - Estrutura visual e organizacional da interface do aplicativo.<br>- Deve ser consistente com o [portal](./lexicos.md/#portal_oficial) [oficial](./lexicos.md/#portal_oficial) | - Afeta diretamente a experiência do [Beneficiário](./lexicos.md/#usuario), sendo essencial para garantir usabilidade, estética e coerência visual. | [RNF01](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF01), RNF14 |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a> e <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

## Léxico 32: Portal Oficial

**Requisitos relacionados:** [RNF14](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF14)

O termo "Portal Oficial" refere-se ao site institucional do [plano de Saúde](./lexicos.md/#plano_saude).

<p align="center">Tabela 33: Léxico 32 - Portal Oficial</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX32 | Portal Oficial | Objeto | - | - Site institucional do [plano de Saúde](./lexicos.md/#plano_saude), que serve como referência para identidade visual e navegação. | - Serve como base para a padronização visual e comportamental do aplicativo, reforçando a identidade do sistema e a confiança do [Beneficiário](./lexicos.md/#usuario). | [RNF14](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF14) |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

## Léxico 33: Plano de Saúde

**Requisitos relacionados:** [RNF14](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF14)

O termo "Plano de Saúde" refere-se à instituição responsável pela oferta de serviços médicos.

<p align="center">Tabela 34: Léxico 33 - Plano de Saúde</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX33 | Plano de Saúde | Objeto | - | - Instituição responsável pela oferta de serviços médicos e pelo desenvolvimento do portal e aplicativo utilizados pelo [Beneficiário](./lexicos.md/#usuario). | - Define as diretrizes de identidade visual que devem ser refletidas no aplicativo para garantir coerência e profissionalismo. | [RNF14](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF14) |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

## Léxico 34: Exigir autenticação via GovBR

**Requisitos relacionados:** [RNF15](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF15)

O termo "Exigir" refere-se à ação de obrigar ou requerer um método específico de autenticação.

<p align="center">Tabela 35: Léxico 34 - Exigir autenticação via GovBR</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX34 | Exigir autenticação via GovBR| Verbo | - | - O [Beneficiário](./lexicos.md/#usuario) acessa o sistema e realiza [login](./lexicos.md/#login) via GovBR. | - O [Beneficiário](./lexicos.md/#usuario) realizou [login](./lexicos.md/#login).<br>- O [Beneficiário](./lexicos.md/#usuario) pode acessar o sistema | [RNF15](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF15) |

<p align="center">Fonte: Autoria de <a href="https://github.com/redjsun">Yzabella Miranda</a></p>

---

## Léxico 35: Login

**Requisitos relacionados:** [RNF15](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF15), [RF19](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF19)

O termo "Login" refere-se ao acesso inicial do [Beneficiário](./lexicos.md/#usuario) ao sistema após autenticação.

<p align="center">Tabela 36: Léxico 35 - Login</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX35 | Login | Objeto | - | - Acesso inicial do [Beneficiário](./lexicos.md/#usuario) ao sistema após autenticação. | - O [Beneficiário](./lexicos.md/#usuario) entra no aplicativo | RNF15, [RF19](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF19) |

<p align="center">Fonte: Autoria de <a href="https://github.com/redjsun">Yzabella Miranda</a> e <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

---

## Léxico 36: Divulgar novas funcionalidades

**Requisitos relacionados:** [RF12](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF12)

O termo "Divulgar novas funcionalidades" refere-se à ação de tornar públicas ou acessíveis as informações sobre novas funcionalidades.

<p align="center">Tabela 37: Léxico 36 - Divulgar</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX36 | Divulgar | Verbo | - | - Ação de tornar públicas ou acessíveis as informações sobre novas funcionalidades. | - O [Beneficiário](./lexicos.md/#usuario) pode visualizar as novas funcionalidades | [RF12](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF12) |

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

## Léxico 37: Armazenar

**Requisitos relacionados:** [RNF11](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF11)

O termo "Armazenar" refere-se à ação de preservar ou conservar algo em determinado estado.

<p align="center">Tabela 38: Léxico 37 - Armazenar</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX37 | Armazenar | Verbo | Preservar, Manter | -  O sistema preserva ou conserva algo em determinado estado. | - O [histórico](./lexicos.md/#historico) de [notificações](./lexicos.md/#Notificacoes) está disponível para acesso pelo usuário durante o período estabelecido. | [RNF11](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF11) |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 38: Suporte

**Requisitos relacionados:** [RNF12](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF12)

O termo "Suporte" refere-se ao sistema ou serviço que fornece assistência ao usuário.

<p align="center">Tabela 39: Léxico 38 - Suporte</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX38 | Suporte | Objeto | Assistência, Ajuda | - Sistema ou serviço que fornece assistência ao usuário por diferentes canais de comunicação.<br>- O [Beneficiário](./lexicos.md/#usuario) solicita atendimento do suporte. | - Melhora a usabilidade e a satisfação do usuário ao resolver dúvidas ou problemas encontrados durante o uso do aplicativo.<br>- O [Beneficiário](./lexicos.md/#usuario) é atendido pelo sistema. | [RNF12](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF12) |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 39: Chat

**Requisitos relacionados:** [RNF12](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF12)

O termo "Chat" refere-se a um canal de comunicação em tempo real via texto.

<p align="center">Tabela 40: Léxico 39 - Chat</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX39 | Chat | Objeto | Mensageiro | - Canal de comunicação em tempo real via texto entre o usuário e a equipe de [suporte](./lexicos.md/#suporte).<br>- O [Beneficiário](./lexicos.md/#usuario) conversa com o [suporte](./lexicos.md/#suporte) pelo chat. | - Facilita a interação rápida e eficiente, fornecendo respostas imediatas a dúvidas e problemas. | [RNF12](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF12) |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 40: Favoritar horários de consulta

**Requisitos relacionados:** [RF10](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF10)

O termo "Favoritar" refere-se à ação de marcar horários de consulta preferidos para uso futuro.

<p align="center">Tabela 41: Léxico 40 - Favoritar</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX40 | Favoritar | Verbo | Marcar como preferido | - O [Beneficiário](./lexicos.md/#usuario) salva horários de consulta preferidos para [agendamento](./lexicos.md/#agendamento) futuro. | - O [horário está favoritado](./lexicos.md/#horario_favorito).<br>- Os horários favoritos podem ser visualizados com destaque. | [RF10](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF10) |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 41: Horário está favoritado

**Requisitos relacionados:** [RF10](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF10)

O termo "Horários Preferidos" refere-se aos períodos de tempo salvos pelo [Beneficiário](./lexicos.md/#usuario) como preferenciais para consultas.

<p align="center">Tabela 42: Léxico 41 - Horário está favoritado</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX41 | Horário está favoritado | Estado | Horários favoritos | - Horários salvos pelo [Beneficiário](./lexicos.md/#usuario) como preferenciais para [agendamento](./lexicos.md/#agendamento) de consultas.<br>- O horário foi escolhido como favorito. | - Consulta é agendada no horário favorito. | [RF10](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF10) |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 42: Solicitar Reembolso

**Requisitos relacionados:** [RF20](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF20)

O termo "Solicitar Reembolso" refere-se à ação de enviar uma requisição formal para devolução de valores cobrados indevidamente.

<p align="center">Tabela 43: Léxico 42 - Solicitar Reembolso</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX42 | Solicitar Reembolso | Verbo | Pedir ressarcimento | Ação de enviar uma requisição formal ao sistema para análise e possível devolução de valores de coparticipação cobrados indevidamente. | Inicia o processo de [reembolso](./lexicos.md/#reembolso) para análise e eventual correção financeira a favor do usuário. | [RF20](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF20) |

<p align="center">Fonte: Autoria de <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

## Léxico 43: Pagamento Automático

**Requisitos relacionados:** [RF05.1](../../elicitacao/requisitos_finais.md#RF05.1), [RF05.2](../../elicitacao/requisitos_finais.md#RF05.2)

O termo "Pagamento Automático" refere-se à transação financeira processada pelo sistema sem intervenção manual no momento do serviço.

<p align="center">Tabela 44: Léxico 43 - Pagamento Automático</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX43 | Pagamento Automático | Objeto | - | - Transação financeira processada pelo sistema para quitar valores de [agendamentos](./lexicos.md/#agendamento) ou [cancelamentos](./lexicos.md/#cancelar).<br>- Se relaciona com o [agendamento](./lexicos.md/#agendamento) e o [prestador](./lexicos.md/#prestador). | - Simplifica o processo de agendamento e cancelamento, automatizando as cobranças e estornos para o [beneficiário](./lexicos.md/#beneficiario). | [RF05.1](...), [RF05.2](...) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 44: Valor

**Requisitos relacionados:** [RF06.1](../../elicitacao/requisitos_finais.md#RF06.1)

O termo "Valor" refere-se ao custo monetário de um serviço.

<p align="center">Tabela 45: Léxico 44 - Valor</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX44 | Valor | Objeto | Preço, Custo | - Custo monetário de uma [consulta](./lexicos.md/#consulta) ou procedimento em um [prestador](./lexicos.md/#prestador) específico. | - Permite ao [beneficiário](./lexicos.md/#beneficiario) ter transparência sobre os custos antes de [agendar](./lexicos.md/#agendar) um serviço. | [RF06.1](...) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 45: Calcular

**Requisitos relacionados:** [RF06.2](../../elicitacao/requisitos_finais.md#RF06.2)

O termo "Calcular" refere-se à ação do sistema de processar dados para determinar um resultado numérico.

<p align="center">Tabela 46: Léxico 45 - Calcular</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX45 | Calcular | Verbo | Processar | - O sistema, ao identificar um procedimento, realiza o processamento de regras do plano para determinar o valor da [coparticipação](./lexicos.md/#coparticipacao). | - O valor da [coparticipação](./lexicos.md/#coparticipacao) é [exibido](./lexicos.md/#exibir) ao [beneficiário](./lexicos.md/#beneficiario), garantindo transparência. | [RF06.2](...) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 46: Gerar

**Requisitos relacionados:** [RF06.3](../../elicitacao/requisitos_finais.md#RF06.3)

O termo "Gerar" refere-se à ação do sistema de criar um novo artefato ou documento.

<p align="center">Tabela 47: Léxico 46 - Gerar</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX46 | Gerar | Verbo | Criar, Produzir | - O sistema, a pedido do [beneficiário](./lexicos.md/#beneficiario), compila dados financeiros e cria um [demonstrativo de despesas](./lexicos.md/#demonstrativo). | - Um documento (PDF) é produzido e fica disponível para [baixar](./lexicos.md/#baixar). | [RF06.3](...) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 47: Baixar

**Requisitos relacionados:** [RF06.3](../../elicitacao/requisitos_finais.md#RF06.3)

O termo "Baixar" refere-se à ação de transferir um arquivo do sistema para o dispositivo do usuário.

<p align="center">Tabela 48: Léxico 47 - Baixar</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX47 | Baixar | Verbo | Fazer download | - O [beneficiário](./lexicos.md/#beneficiario), após [gerar](./lexicos.md/#gerar) um documento, executa a ação de transferi-lo para seu dispositivo. | - O [beneficiário](./lexicos.md/#beneficiario) possui uma cópia local do [demonstrativo de despesas](./lexicos.md/#demonstrativo). | [RF06.3](...) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 48: Demonstrativo de Despesas (Demonstrativo de IR)

**Requisitos relacionados:** [RF06.3](../../elicitacao/requisitos_finais.md#RF06.3), [RF06.4](../../elicitacao/requisitos_finais.md#RF06.4)

O termo "Demonstrativo de Despesas" refere-se ao documento consolidado para fins de declaração de Imposto de Renda.

<p align="center">Tabela 49: Léxico 48 - Demonstrativo de Despesas</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX48 | Demonstrativo de Despesas | Objeto | Demonstrativo de IR | - Documento que consolida despesas médicas (mensalidades, [coparticipações](./lexicos.md/#coparticipacao)) para a declaração de Imposto de Renda.<br>- Faz parte do [histórico](./lexicos.md/#historico) do usuário. | - O [beneficiário](./lexicos.md/#beneficiario) pode [gerar](./lexicos.md/#gerar), [baixar](./lexicos.md/#baixar) e [consultar](./lexicos.md/#exibir) o documento. | [RF06.3](...), [RF06.4](...) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 49: Extrato Financeiro

**Requisitos relacionados:** [RF06.5](../../elicitacao/requisitos_finais.md#RF06.5)

O termo "Extrato Financeiro" refere-se ao registro detalhado de todas as transações financeiras do usuário com o plano.

<p align="center">Tabela 50: Léxico 49 - Extrato Financeiro</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX49 | Extrato Financeiro | Objeto | - | - Registro detalhado e atualizado de transações financeiras ([coparticipações](./lexicos.md/#coparticipacao), mensalidades) do [beneficiário](./lexicos.md/#beneficiario). | - O [beneficiário](./lexicos.md/#beneficiario) pode [consultar](./lexicos.md/#exibir) suas movimentações para controle financeiro. | [RF06.5](...) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 50: Painel de Metas

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Painel de Metas" refere-se à interface visual para acompanhamento de objetivos de saúde.

<p align="center">Tabela 51: Léxico 50 - Painel de Metas</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX50 | Painel de Metas | Objeto | Painel de Saúde | - [Interface](./lexicos.md/#interface) que [exibe](./lexicos.md/#exibir) as [metas de saúde](./lexicos.md/#metas_saude) personalizadas para o [beneficiário](./lexicos.md/#beneficiario).<br>- Utiliza elementos de [gamificação](./lexicos.md/#gamificacao). | - Permite ao [beneficiário](./lexicos.md/#beneficiario) acompanhar seu progresso em cuidados preventivos. | [RF17](...) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 51: Metas de Saúde

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Metas de Saúde" refere-se aos objetivos de cuidado preventivo recomendados ao usuário.

<p align="center">Tabela 52: Léxico 51 - Metas de Saúde</p>

| ID   | Termo | Tipo | Sinônimos | Noção | Impacto | Requisitos |
| --- | --- | --- | --- | --- | --- |
| LX51 | Metas de Saúde | Objeto | Metas personalizadas | - Objetivos de cuidado preventivo (exames, consultas, vacinas) definidos com base no histórico de saúde e recomendações médicas. | - O [Beneficiário](./lexicos.md/#usuario) pode visualizar e acompanhar suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 52: Gamificação

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Gamificação" refere-se à aplicação de elementos de jogos em contextos não relacionados a jogos, como o acompanhamento de metas de saúde.

<p align="center">Tabela 53: Léxico 52 - Gamificação</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX52 | Gamificação | Objeto | - | - Aplicação de elementos de jogos (como pontos, medalhas e desafios) para engajar o beneficiário no cumprimento de metas de saúde. | - Aumenta a motivação e o engajamento do beneficiário em atividades de saúde preventiva. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 53: Acompanhamento de Metas

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Acompanhamento de Metas" refere-se ao monitoramento do progresso em direção ao cumprimento das metas de saúde estabelecidas.

<p align="center">Tabela 54: Léxico 53 - Acompanhamento de Metas</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX53 | Acompanhamento de Metas | Objeto | - | - Monitoramento regular do progresso em direção ao cumprimento das metas de saúde, com base em dados de consultas, exames e atividades de saúde. | - Permite ajustes nas ações de saúde do beneficiário, garantindo que as metas sejam alcançadas de forma eficaz. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 54: Notificações de Metas

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Notificações de Metas" refere-se aos alertas ou lembretes enviados ao beneficiário sobre suas metas de saúde.

<p align="center">Tabela 55: Léxico 54 - Notificações de Metas</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX54 | Notificações de Metas | Objeto | Alertas de Metas | - Mensagens enviadas ao beneficiário para lembrá-lo sobre suas metas de saúde e incentivá-lo a completá-las. | - Melhora o engajamento do beneficiário no acompanhamento e cumprimento de suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 55: Interface de Acompanhamento

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Interface de Acompanhamento" refere-se à tela ou seção do aplicativo onde o beneficiário pode visualizar suas metas de saúde e seu progresso.

<p align="center">Tabela 56: Léxico 55 - Interface de Acompanhamento</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX55 | Interface de Acompanhamento | Objeto | Tela de Metas | - Seção do aplicativo onde o beneficiário visualiza suas metas de saúde, histórico de cumprimento e notificações relacionadas. | - Centraliza as informações sobre metas de saúde, facilitando o acompanhamento e a gestão da saúde pelo beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 56: Relatório de Metas

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Relatório de Metas" refere-se ao documento que compila informações sobre o cumprimento das metas de saúde pelo beneficiário.

<p align="center">Tabela 57: Léxico 56 - Relatório de Metas</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX56 | Relatório de Metas | Objeto | - | - Documento que apresenta de forma consolidada o desempenho do beneficiário em relação às metas de saúde estabelecidas. | - Permite ao beneficiário e à equipe de saúde avaliar o progresso e realizar ajustes nas estratégias de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 57: Feedback de Metas

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Feedback de Metas" refere-se ao retorno ou avaliação sobre o cumprimento das metas de saúde pelo beneficiário.

<p align="center">Tabela 58: Léxico 57 - Feedback de Metas</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX57 | Feedback de Metas | Objeto | - | - Avaliação periódica do progresso do beneficiário em relação às metas de saúde, com sugestões de melhoria e ajustes. | - Auxilia o beneficiário a manter o foco e a motivação no cumprimento de suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 58: Ajuste de Metas

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Ajuste de Metas" refere-se à modificação dos objetivos de saúde estabelecidos para o beneficiário, com base em novas informações ou mudanças na condição de saúde.

<p align="center">Tabela 59: Léxico 58 - Ajuste de Metas</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX58 | Ajuste de Metas | Verbo | - | - Ação de modificar as metas de saúde do beneficiário, podendo incluir, excluir ou alterar objetivos e prazos. | - Garante que as metas de saúde estejam sempre alinhadas com a realidade e necessidades do beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 59: Histórico de Metas

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Histórico de Metas" refere-se ao registro das metas de saúde anteriores e seu status de cumprimento pelo beneficiário.

<p align="center">Tabela 60: Léxico 59 - Histórico de Metas</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX59 | Histórico de Metas | Objeto | - | - Registro que permite ao beneficiário e à equipe de saúde visualizar as metas de saúde anteriores, prazos e status de cumprimento. | - Facilita a avaliação do progresso ao longo do tempo e a identificação de padrões ou necessidades de intervenção. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 60: Notificações de Lembrete

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Notificações de Lembrete" refere-se aos alertas enviados ao beneficiário para lembrá-lo de suas metas de saúde e prazos importantes.

<p align="center">Tabela 61: Léxico 60 - Notificações de Lembrete</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX60 | Notificações de Lembrete | Objeto | Alertas de Lembrete | - Mensagens enviadas ao beneficiário para lembrá-lo sobre suas metas de saúde e prazos importantes. | - Ajuda o beneficiário a manter o foco e a organização em relação às suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 61: Progresso de Metas

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Progresso de Metas" refere-se ao avanço do beneficiário em direção ao cumprimento de suas metas de saúde.

<p align="center">Tabela 62: Léxico 61 - Progresso de Metas</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX61 | Progresso de Metas | Objeto | - | - Medição do avanço do beneficiário em direção ao cumprimento de suas metas de saúde, podendo incluir percentuais, etapas concluídas e prazos. | - Permite ao beneficiário visualizar seu desempenho e ajustar suas ações para alcançar suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 62: Ajuste de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Ajuste de Progresso" refere-se à modificação dos parâmetros de avaliação do progresso das metas de saúde do beneficiário.

<p align="center">Tabela 63: Léxico 62 - Ajuste de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX62 | Ajuste de Progresso | Verbo | - | - Ação de modificar os parâmetros de avaliação do progresso das metas de saúde, como percentuais, etapas e prazos. | - Garante que o acompanhamento do progresso esteja sempre alinhado com a realidade e necessidades do beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 63: Histórico de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Histórico de Progresso" refere-se ao registro das avaliações anteriores do progresso das metas de saúde do beneficiário.

<p align="center">Tabela 64: Léxico 63 - Histórico de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX63 | Histórico de Progresso | Objeto | - | - Registro que permite ao beneficiário e à equipe de saúde visualizar as avaliações anteriores do progresso em relação às metas de saúde. | - Facilita a avaliação da evolução ao longo do tempo e a identificação de padrões ou necessidades de intervenção. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 64: Notificações de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Notificações de Progresso" refere-se aos alertas enviados ao beneficiário sobre seu progresso em relação às metas de saúde.

<p align="center">Tabela 65: Léxico 64 - Notificações de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX64 | Notificações de Progresso | Objeto | Alertas de Progresso | - Mensagens enviadas ao beneficiário para informá-lo sobre seu progresso em relação às metas de saúde. | - Ajuda o beneficiário a manter o foco e a motivação em relação às suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 65: Interface de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Interface de Progresso" refere-se à tela ou seção do aplicativo onde o beneficiário pode visualizar seu progresso em relação às metas de saúde.

<p align="center">Tabela 66: Léxico 65 - Interface de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX65 | Interface de Progresso | Objeto | Tela de Progresso | - Seção do aplicativo onde o beneficiário visualiza seu progresso em relação às metas de saúde, histórico de cumprimento e notificações relacionadas. | - Centraliza as informações sobre progresso de metas de saúde, facilitando o acompanhamento e a gestão da saúde pelo beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 66: Relatório de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Relatório de Progresso" refere-se ao documento que compila informações sobre o progresso do beneficiário em relação às metas de saúde.

<p align="center">Tabela 67: Léxico 66 - Relatório de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX66 | Relatório de Progresso | Objeto | - | - Documento que apresenta de forma consolidada o desempenho do beneficiário em relação ao cumprimento de suas metas de saúde. | - Permite ao beneficiário e à equipe de saúde avaliar o progresso e realizar ajustes nas estratégias de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 67: Feedback de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Feedback de Progresso" refere-se ao retorno ou avaliação sobre o progresso do beneficiário em relação às metas de saúde.

<p align="center">Tabela 68: Léxico 67 - Feedback de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX67 | Feedback de Progresso | Objeto | - | - Avaliação periódica do progresso do beneficiário em relação às metas de saúde, com sugestões de melhoria e ajustes. | - Auxilia o beneficiário a manter o foco e a motivação no cumprimento de suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 68: Ajuste de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Ajuste de Progresso" refere-se à modificação dos parâmetros de avaliação do progresso das metas de saúde do beneficiário.

<p align="center">Tabela 69: Léxico 68 - Ajuste de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX68 | Ajuste de Progresso | Verbo | - | - Ação de modificar os parâmetros de avaliação do progresso das metas de saúde, como percentuais, etapas e prazos. | - Garante que o acompanhamento do progresso esteja sempre alinhado com a realidade e necessidades do beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 69: Histórico de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Histórico de Progresso" refere-se ao registro das avaliações anteriores do progresso das metas de saúde do beneficiário.

<p align="center">Tabela 70: Léxico 69 - Histórico de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX69 | Histórico de Progresso | Objeto | - | - Registro que permite ao beneficiário e à equipe de saúde visualizar as avaliações anteriores do progresso em relação às metas de saúde. | - Facilita a avaliação da evolução ao longo do tempo e a identificação de padrões ou necessidades de intervenção. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 70: Notificações de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Notificações de Progresso" refere-se aos alertas enviados ao beneficiário sobre seu progresso em relação às metas de saúde.

<p align="center">Tabela 71: Léxico 70 - Notificações de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX70 | Notificações de Progresso | Objeto | Alertas de Progresso | - Mensagens enviadas ao beneficiário para informá-lo sobre seu progresso em relação às metas de saúde. | - Ajuda o beneficiário a manter o foco e a motivação em relação às suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 71: Interface de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Interface de Progresso" refere-se à tela ou seção do aplicativo onde o beneficiário pode visualizar seu progresso em relação às metas de saúde.

<p align="center">Tabela 72: Léxico 71 - Interface de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX71 | Interface de Progresso | Objeto | Tela de Progresso | - Seção do aplicativo onde o beneficiário visualiza seu progresso em relação às metas de saúde, histórico de cumprimento e notificações relacionadas. | - Centraliza as informações sobre progresso de metas de saúde, facilitando o acompanhamento e a gestão da saúde pelo beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 72: Relatório de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Relatório de Progresso" refere-se ao documento que compila informações sobre o progresso do beneficiário em relação às metas de saúde.

<p align="center">Tabela 73: Léxico 72 - Relatório de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX72 | Relatório de Progresso | Objeto | - | - Documento que apresenta de forma consolidada o desempenho do beneficiário em relação ao cumprimento de suas metas de saúde. | - Permite ao beneficiário e à equipe de saúde avaliar o progresso e realizar ajustes nas estratégias de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 73: Feedback de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Feedback de Progresso" refere-se ao retorno ou avaliação sobre o progresso do beneficiário em relação às metas de saúde.

<p align="center">Tabela 74: Léxico 73 - Feedback de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX73 | Feedback de Progresso | Objeto | - | - Avaliação periódica do progresso do beneficiário em relação às metas de saúde, com sugestões de melhoria e ajustes. | - Auxilia o beneficiário a manter o foco e a motivação no cumprimento de suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 74: Ajuste de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Ajuste de Progresso" refere-se à modificação dos parâmetros de avaliação do progresso das metas de saúde do beneficiário.

<p align="center">Tabela 75: Léxico 74 - Ajuste de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX74 | Ajuste de Progresso | Verbo | - | - Ação de modificar os parâmetros de avaliação do progresso das metas de saúde, como percentuais, etapas e prazos. | - Garante que o acompanhamento do progresso esteja sempre alinhado com a realidade e necessidades do beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 75: Histórico de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Histórico de Progresso" refere-se ao registro das avaliações anteriores do progresso das metas de saúde do beneficiário.

<p align="center">Tabela 76: Léxico 75 - Histórico de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX75 | Histórico de Progresso | Objeto | - | - Registro que permite ao beneficiário e à equipe de saúde visualizar as avaliações anteriores do progresso em relação às metas de saúde. | - Facilita a avaliação da evolução ao longo do tempo e a identificação de padrões ou necessidades de intervenção. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 76: Notificações de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Notificações de Progresso" refere-se aos alertas enviados ao beneficiário sobre seu progresso em relação às metas de saúde.

<p align="center">Tabela 77: Léxico 76 - Notificações de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX76 | Notificações de Progresso | Objeto | Alertas de Progresso | - Mensagens enviadas ao beneficiário para informá-lo sobre seu progresso em relação às metas de saúde. | - Ajuda o beneficiário a manter o foco e a motivação em relação às suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 77: Interface de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Interface de Progresso" refere-se à tela ou seção do aplicativo onde o beneficiário pode visualizar seu progresso em relação às metas de saúde.

<p align="center">Tabela 78: Léxico 77 - Interface de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX77 | Interface de Progresso | Objeto | Tela de Progresso | - Seção do aplicativo onde o beneficiário visualiza seu progresso em relação às metas de saúde, histórico de cumprimento e notificações relacionadas. | - Centraliza as informações sobre progresso de metas de saúde, facilitando o acompanhamento e a gestão da saúde pelo beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 78: Relatório de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Relatório de Progresso" refere-se ao documento que compila informações sobre o progresso do beneficiário em relação às metas de saúde.

<p align="center">Tabela 79: Léxico 78 - Relatório de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX78 | Relatório de Progresso | Objeto | - | - Documento que apresenta de forma consolidada o desempenho do beneficiário em relação ao cumprimento de suas metas de saúde. | - Permite ao beneficiário e à equipe de saúde avaliar o progresso e realizar ajustes nas estratégias de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 79: Feedback de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Feedback de Progresso" refere-se ao retorno ou avaliação sobre o progresso do beneficiário em relação às metas de saúde.

<p align="center">Tabela 80: Léxico 79 - Feedback de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX79 | Feedback de Progresso | Objeto | - | - Avaliação periódica do progresso do beneficiário em relação às metas de saúde, com sugestões de melhoria e ajustes. | - Auxilia o beneficiário a manter o foco e a motivação no cumprimento de suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 80: Ajuste de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Ajuste de Progresso" refere-se à modificação dos parâmetros de avaliação do progresso das metas de saúde do beneficiário.

<p align="center">Tabela 81: Léxico 80 - Ajuste de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX80 | Ajuste de Progresso | Verbo | - | - Ação de modificar os parâmetros de avaliação do progresso das metas de saúde, como percentuais, etapas e prazos. | - Garante que o acompanhamento do progresso esteja sempre alinhado com a realidade e necessidades do beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 81: Histórico de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Histórico de Progresso" refere-se ao registro das avaliações anteriores do progresso das metas de saúde do beneficiário.

<p align="center">Tabela 82: Léxico 81 - Histórico de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX81 | Histórico de Progresso | Objeto | - | - Registro que permite ao beneficiário e à equipe de saúde visualizar as avaliações anteriores do progresso em relação às metas de saúde. | - Facilita a avaliação da evolução ao longo do tempo e a identificação de padrões ou necessidades de intervenção. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 82: Notificações de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Notificações de Progresso" refere-se aos alertas enviados ao beneficiário sobre seu progresso em relação às metas de saúde.

<p align="center">Tabela 83: Léxico 82 - Notificações de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX82 | Notificações de Progresso | Objeto | Alertas de Progresso | - Mensagens enviadas ao beneficiário para informá-lo sobre seu progresso em relação às metas de saúde. | - Ajuda o beneficiário a manter o foco e a motivação em relação às suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 83: Interface de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Interface de Progresso" refere-se à tela ou seção do aplicativo onde o beneficiário pode visualizar seu progresso em relação às metas de saúde.

<p align="center">Tabela 84: Léxico 83 - Interface de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX83 | Interface de Progresso | Objeto | Tela de Progresso | - Seção do aplicativo onde o beneficiário visualiza seu progresso em relação às metas de saúde, histórico de cumprimento e notificações relacionadas. | - Centraliza as informações sobre progresso de metas de saúde, facilitando o acompanhamento e a gestão da saúde pelo beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 84: Relatório de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Relatório de Progresso" refere-se ao documento que compila informações sobre o progresso do beneficiário em relação às metas de saúde.

<p align="center">Tabela 85: Léxico 84 - Relatório de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX84 | Relatório de Progresso | Objeto | - | - Documento que apresenta de forma consolidada o desempenho do beneficiário em relação ao cumprimento de suas metas de saúde. | - Permite ao beneficiário e à equipe de saúde avaliar o progresso e realizar ajustes nas estratégias de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 85: Feedback de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Feedback de Progresso" refere-se ao retorno ou avaliação sobre o progresso do beneficiário em relação às metas de saúde.

<p align="center">Tabela 86: Léxico 85 - Feedback de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX85 | Feedback de Progresso | Objeto | - | - Avaliação periódica do progresso do beneficiário em relação às metas de saúde, com sugestões de melhoria e ajustes. | - Auxilia o beneficiário a manter o foco e a motivação no cumprimento de suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 86: Ajuste de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Ajuste de Progresso" refere-se à modificação dos parâmetros de avaliação do progresso das metas de saúde do beneficiário.

<p align="center">Tabela 87: Léxico 86 - Ajuste de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX86 | Ajuste de Progresso | Verbo | - | - Ação de modificar os parâmetros de avaliação do progresso das metas de saúde, como percentuais, etapas e prazos. | - Garante que o acompanhamento do progresso esteja sempre alinhado com a realidade e necessidades do beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 87: Histórico de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Histórico de Progresso" refere-se ao registro das avaliações anteriores do progresso das metas de saúde do beneficiário.

<p align="center">Tabela 88: Léxico 87 - Histórico de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX87 | Histórico de Progresso | Objeto | - | - Registro que permite ao beneficiário e à equipe de saúde visualizar as avaliações anteriores do progresso em relação às metas de saúde. | - Facilita a avaliação da evolução ao longo do tempo e a identificação de padrões ou necessidades de intervenção. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 88: Notificações de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Notificações de Progresso" refere-se aos alertas enviados ao beneficiário sobre seu progresso em relação às metas de saúde.

<p align="center">Tabela 89: Léxico 88 - Notificações de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX88 | Notificações de Progresso | Objeto | Alertas de Progresso | - Mensagens enviadas ao beneficiário para informá-lo sobre seu progresso em relação às metas de saúde. | - Ajuda o beneficiário a manter o foco e a motivação em relação às suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 89: Interface de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Interface de Progresso" refere-se à tela ou seção do aplicativo onde o beneficiário pode visualizar seu progresso em relação às metas de saúde.

<p align="center">Tabela 90: Léxico 89 - Interface de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX89 | Interface de Progresso | Objeto | Tela de Progresso | - Seção do aplicativo onde o beneficiário visualiza seu progresso em relação às metas de saúde, histórico de cumprimento e notificações relacionadas. | - Centraliza as informações sobre progresso de metas de saúde, facilitando o acompanhamento e a gestão da saúde pelo beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 90: Relatório de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Relatório de Progresso" refere-se ao documento que compila informações sobre o progresso do beneficiário em relação às metas de saúde.

<p align="center">Tabela 91: Léxico 90 - Relatório de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX90 | Relatório de Progresso | Objeto | - | - Documento que apresenta de forma consolidada o desempenho do beneficiário em relação ao cumprimento de suas metas de saúde. | - Permite ao beneficiário e à equipe de saúde avaliar o progresso e realizar ajustes nas estratégias de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 91: Feedback de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Feedback de Progresso" refere-se ao retorno ou avaliação sobre o progresso do beneficiário em relação às metas de saúde.

<p align="center">Tabela 92: Léxico 91 - Feedback de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX91 | Feedback de Progresso | Objeto | - | - Avaliação periódica do progresso do beneficiário em relação às metas de saúde, com sugestões de melhoria e ajustes. | - Auxilia o beneficiário a manter o foco e a motivação no cumprimento de suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 92: Ajuste de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Ajuste de Progresso" refere-se à modificação dos parâmetros de avaliação do progresso das metas de saúde do beneficiário.

<p align="center">Tabela 93: Léxico 92 - Ajuste de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX92 | Ajuste de Progresso | Verbo | - | - Ação de modificar os parâmetros de avaliação do progresso das metas de saúde, como percentuais, etapas e prazos. | - Garante que o acompanhamento do progresso esteja sempre alinhado com a realidade e necessidades do beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 93: Histórico de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Histórico de Progresso" refere-se ao registro das avaliações anteriores do progresso das metas de saúde do beneficiário.

<p align="center">Tabela 94: Léxico 93 - Histórico de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX93 | Histórico de Progresso | Objeto | - | - Registro que permite ao beneficiário e à equipe de saúde visualizar as avaliações anteriores do progresso em relação às metas de saúde. | - Facilita a avaliação da evolução ao longo do tempo e a identificação de padrões ou necessidades de intervenção. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 94: Notificações de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Notificações de Progresso" refere-se aos alertas enviados ao beneficiário sobre seu progresso em relação às metas de saúde.

<p align="center">Tabela 95: Léxico 94 - Notificações de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX94 | Notificações de Progresso | Objeto | Alertas de Progresso | - Mensagens enviadas ao beneficiário para informá-lo sobre seu progresso em relação às metas de saúde. | - Ajuda o beneficiário a manter o foco e a motivação em relação às suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 95: Interface de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Interface de Progresso" refere-se à tela ou seção do aplicativo onde o beneficiário pode visualizar seu progresso em relação às metas de saúde.

<p align="center">Tabela 96: Léxico 95 - Interface de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX95 | Interface de Progresso | Objeto | Tela de Progresso | - Seção do aplicativo onde o beneficiário visualiza seu progresso em relação às metas de saúde, histórico de cumprimento e notificações relacionadas. | - Centraliza as informações sobre progresso de metas de saúde, facilitando o acompanhamento e a gestão da saúde pelo beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 96: Relatório de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Relatório de Progresso" refere-se ao documento que compila informações sobre o progresso do beneficiário em relação às metas de saúde.

<p align="center">Tabela 97: Léxico 96 - Relatório de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX96 | Relatório de Progresso | Objeto | - | - Documento que apresenta de forma consolidada o desempenho do beneficiário em relação ao cumprimento de suas metas de saúde. | - Permite ao beneficiário e à equipe de saúde avaliar o progresso e realizar ajustes nas estratégias de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 97: Feedback de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Feedback de Progresso" refere-se ao retorno ou avaliação sobre o progresso do beneficiário em relação às metas de saúde.

<p align="center">Tabela 98: Léxico 97 - Feedback de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX97 | Feedback de Progresso | Objeto | - | - Avaliação periódica do progresso do beneficiário em relação às metas de saúde, com sugestões de melhoria e ajustes. | - Auxilia o beneficiário a manter o foco e a motivação no cumprimento de suas metas de saúde. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 98: Ajuste de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Ajuste de Progresso" refere-se à modificação dos parâmetros de avaliação do progresso das metas de saúde do beneficiário.

<p align="center">Tabela 99: Léxico 98 - Ajuste de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX98 | Ajuste de Progresso | Verbo | - | - Ação de modificar os parâmetros de avaliação do progresso das metas de saúde, como percentuais, etapas e prazos. | - Garante que o acompanhamento do progresso esteja sempre alinhado com a realidade e necessidades do beneficiário. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

## Léxico 99: Histórico de Progresso

**Requisitos relacionados:** [RF17](../../elicitacao/requisitos_finais.md#RF17)

O termo "Histórico de Progresso" refere-se ao registro das avaliações anteriores do progresso das metas de saúde do beneficiário.

<p align="center">Tabela 100: Léxico 99 - Histórico de Progresso</p>

| ID   | Termo   | Tipo   | Sinônimos | Noção | Impacto | Requisitos |
|------|---------|--------|-----------|-------|---------|------------|
| LX99 | Histórico de Progresso | Objeto | - | - Registro que permite ao beneficiário e à equipe de saúde visualizar as avaliações anteriores do progresso em relação às metas de saúde. | - Facilita a avaliação da evolução ao longo do tempo e a identificação de padrões ou necessidades de intervenção. | [RF17](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RF17) |

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---