# NFR FRamework

## Introdução

Diferentemente dos requisitos funcionais, que descrevem o que o sistema deve fazer, os requisitos não funcionais(RNF) tratam de como o sistema deve se comportar sob determinadas condições. Para lidar com a complexidade e a subjetividade desses requisitos, o NFR Framework, proposto por Chung et al. (2000), oferece uma abordagem estruturada que permite representar, analisar e tomar decisões sobre RNF's por meio do uso de softgoals — objetivos que não possuem critérios de satisfação claramente definidos.Neste trabalho, o NFR Framework é utilizado como base para representar os Requisitos Não-Funcionais, organizando-os em um gráfico de interdependência de softgoals (SIG) que evidencia as relações e os possíveis conflitos entre diferentes requisitos.

## Tabela dos Integrantes do Grupo

Nesta etapa de **Validação dos Casos de Uso**, toda a condução, gravação e documentação foi realizada por:

<p align="center">Tabela 1 - Integralmente conduzido por</p>
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
        <td> <a href="https://github.com/isaqzin">Isaque Camargos</a> </td>
        <td>Fez a introdução, metodologia, as explicações sobre o sig, decomposição, contribuição e procedimento de avaliação, também auxiliou na produção do cartão de especificação 7.</td>
      </tr>
      <tr>
        <td> <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a> </td>
        <td>Fez a documentação dos NFRs produzidos pelo grupo e auxiliou na produção dos mesmos, também ajudou a produzir os cartões de especificação 6 e 7.</td>
      </tr>
        <td> <a href="https://github.com/redjsun">Yzabella Miranda</a> </td>
        <td>Auxiliou na produção dos NFR frameworks</td>
      </tr>
      </tr>
        <td> <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> </td>
        <td>Auxiliou na produção dos NFR frameworks</td>
      </tr>
      <tr>
        <td> <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a> </td>
        <td>Auxiliou na produção do cartão de especificação 6.</td>
      </tr>
    </tbody>
  </table>
</div>
<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

## Gráfico de Interdependência de Softgoals (SIG)

O Gráfico de Interdependência de Softgoals, do inglês Softgoal Interdependency Graph (SIG), é um gráfico utilizado no NFR Framework para representar visualmente os Requisitos Não-Funcionais (NFR) e suas interdependências. Ele registra, de forma gráfica e concisa, as decisões de desenvolvimento, as alternativas consideradas e as justificativas associadas. Através do SIG, é possível analisar como diferentes softgoals influenciam uns aos outros e avaliar se os requisitos de nível superior foram atendidos.

### Tipos de Softgoals

Os softgoals no NFR Framework são classificados em três tipos:

- **Softgoals NFR**: representam os próprios Requisitos Não-Funcionais, podendo ser organizados hierarquicamente e inter-relacionados.
- **Softgoals de Operacionalização**: indicam soluções de implementação para satisfazer os softgoals NFR, como processos, estruturas de dados ou restrições no sistema.

- **Softgoals de Afirmação**: refletem características do domínio, como prioridades e carga de trabalho, justificando decisões e facilitando a revisão e rastreabilidade do sistema.

<p align="center">Figura 1 - Tipos de sofgols  </p>
<p align="center">
  <img src="..\..\..\assets\nfr\tipossoftgol.png" alt="tipos de softgol" width="600">
</p>

<p  align="center">Fonte:<a  href="https://repositorio.ufpe.br/handle/123456789/34150" target="_blank" >Silva, 2019</a></p>

## Decomposições no NFR Framework

As interdependências definem as relações entre os softgoals no NFR Framework. Os principais tipos de interdependências são os\*refinamentos e as contribuições <a  href="https://repositorio.ufpe.br/handle/123456789/34150" target="_blank" >(Silva, 2019).</a>

A decomposição tem como objetivo refinar softgoals, tornando-os mais especializados para facilitar a construção e o entendimento do projeto. O NFR Framework define quatro tipos de decomposição:

- **Decomposição de Softgoal NFR**: refina ou subdivide um softgoal NFR em outros mais específicos. Esta prática ajuda a dividir grandes problemas em partes menores, lidando com ambiguidades e facilitando o estabelecimento de prioridades.

- **Decomposição de Operacionalização**: subdivide um softgoal de operacionalização em outros mais específicos. É útil para definir uma solução geral e detalhá-la em soluções mais específicas.

- **Decomposição de Afirmação (Claims)**: refina um softgoal de afirmação em outros softgoals de afirmação. Esse tipo de decomposição é importante para apoiar ou negar justificativas específicas do projeto.

- **Priorização**: trata-se de um refinamento especial, no qual um softgoal é refinado em outro do mesmo tipo e tópico, mas com uma prioridade associada. Esse tipo de decomposição é essencial para indicar a relevância relativa entre softgoals semelhantes.

As **operacionalizações** definem técnicas de desenvolvimento que ajudam a alcançar os softgoals NFR, transformando-os em softgoals de operacionalização.

Por fim, as **afirmações** também podem ser refinadas, subdividindo um softgoal de afirmação em outros claims. Esse processo é útil para fortalecer ou refutar justificativas específicas relacionadas ao projeto.

<p align="center">Figura 2 - Tipos de decomposição  </p>
<p align="center">
  <img src="..\..\..\assets\nfr\decomposicao.png" alt="tipos de decomposicao" width="600">
</p>

<p  align="center">Fonte:<a  href="https://repositorio.ufpe.br/handle/123456789/34150" target="_blank" >Silva, 2019</a></p>

## Contribuições no NFR Framework

Durante o processo de refinamento dos softgoals no NFR Framework, um softgoal descendente pode contribuir de maneira positiva ou negativa, total ou parcial, para a satisfação do softgoal ascendente. É importante destacar que a "satisfação de softgoal" refere-se ao atendimento de um requisito não-funcional dentro de limites aceitáveis, e não de forma absoluta (CHUNG et al., 2000).

O framework define diversos tipos de contribuições que indicam como a satisfação (ou não) de um softgoal descendente influencia a satisfação do softgoal ascendente. A seguir, são apresentados os principais tipos de contribuições:

- **AND**: indica que todos os softgoals descendentes precisam ser satisfeitos para que o softgoal ascendente também seja satisfeito.

- **OR**: estabelece que basta que um dos softgoals descendentes seja satisfeito para que o softgoal ascendente também seja satisfeito.

- **MAKE (++)**: representa uma contribuição totalmente positiva. Se o softgoal descendente for satisfeito, o softgoal ascendente também será satisfeito no mais alto nível.

- **BREAK (--)**: representa uma contribuição totalmente negativa. Se o softgoal descendente for satisfeito, o softgoal ascendente será negado.

- **HELP (+)**: indica uma contribuição parcialmente positiva. Se o softgoal descendente for parcialmente satisfeito, o softgoal ascendente também será parcialmente satisfeito.

- **HURT (-)**: indica uma contribuição parcialmente negativa. Se o softgoal descendente for satisfeito, o softgoal ascendente será parcialmente negado.

- **UNKNOWN (?)**: representa uma contribuição desconhecida, podendo ser tanto positiva quanto negativa, conforme o contexto.

- **EQUALS**: estabelece que o softgoal descendente só será satisfeito se o softgoal ascendente for satisfeito; da mesma forma, será negado se o ascendente for negado.

- **SOME**: usada quando se conhece o sinal da contribuição (positivo ou negativo), mas não a sua extensão (parcial ou total).
  - **SOME+**: utilizada quando há certeza de que a contribuição é positiva, mas incerteza quanto ao seu grau.
  - **SOME-**: utilizada quando há certeza de que a contribuição é negativa, mas incerteza quanto ao seu grau.

## Procedimento de Avaliação

O procedimento de avaliação no NFR Framework é responsável por determinar o grau em que os requisitos não-funcionais foram satisfeitos por um conjunto de decisões. Esse procedimento avalia se cada softgoal ou interdependência do SIG foi suficientemente satisfeito, utilizando para isso um sistema de rótulos.

Os tipos de rótulos utilizados são:

- (✓) **Satisfeito**
- (𝒲+) **Fracamente Satisfeito**
- ( X) **Negado**
- (𝒲-) **Fracamente Negado**
- (🗲) **Conflitante**
- (u) **Indeterminado**

Esses rótulos são fundamentais para analisar as decisões de projeto, pois indicam como as alternativas escolhidas impactam a satisfação dos requisitos não-funcionais.

A análise dos softgoals começa pelo nível mais baixo da hierarquia do SIG, onde são tomadas decisões sobre aceitar ou negar alternativas no projeto. Essas decisões formam um **conjunto inicial de rótulos** que, posteriormente, é propagado para os níveis superiores da hierarquia. O procedimento continua até atingir os softgoals no nível mais alto do SIG, garantindo uma avaliação completa do impacto das decisões ao longo de todo o sistema.

## Metodologia

Para a criação do NFR Framework, selecionamos todos os requisitos não funcionais elicitados no projeto (ver [docs/elicitacao/elicitacao.md](docs/elicitacao/elicitacao.md)), classificando-os em temas como usabilidade, desempenho, segurança, acessibilidade e conformidade legal. Cada requisito foi detalhado em um cartão de especificação, contendo nome, descrição, fonte, critérios de aceitação e possíveis conflitos.

A seguir, organizamos os requisitos em um Gráfico de Interdependência de Softgoals (SIG), representando visualmente as relações de contribuição (MAKE, HELP, HURT, BREAK, etc.) e refinamento entre os softgoals. Utilizamos ferramentas como draw.io para a construção do SIG.

A avaliação dos softgoals foi realizada aplicando os rótulos do NFR Framework, propagando as decisões do nível mais baixo até o topo da hierarquia, conforme descrito no procedimento de avaliação.

### Cartões de Especificação

As tabelas a seguir detalham os requisitos não-funcionais elicitados para o projeto, com e critérios definidos.

<p align="center"><b>Tabela 1 - Cartão de Especificação 1</b></p>

| Nº Requisito: RNF01                                                                                     | Classificação: Usabilidade |
| ------------------------------------------------------------------------------------------------------- | -------------------------- |
| **Descrição:** O sistema deve ser fácil de usar para todos os perfis de usuário.                        |
| **Justificativa:** Facilitar o uso do sistema para todos os usuários, reduzindo a curva de aprendizado. |
| **Origem do Requisito:** Brainstorm, Introspecção                                                       |
| **Critério de Aceitação:** Usuários realizam tarefas básicas sem auxílio externo.                       |
| **Dependências:** Nenhuma                                                                               |
| **Prioridade:**                                                                                         |
| **Conflitos:** Nenhum                                                                                   |
| **História:** 2025                                                                                      |

<p align="center">Fonte: <a href="https://github.com/kalebmacedo">Kaleb Macedo</a> e <a href="https://github.com/">Lucas Alves</a></p>

<p align="center"><b>Tabela 2 - Cartão de Especificação 2</b></p>

| Nº Requisito: RNF02                                                         | Classificação: Desempenho |
| --------------------------------------------------------------------------- | ------------------------- |
| **Descrição:** Tempo de resposta das ações não deve ultrapassar 2 segundos. |
| **Justificativa:** Garantir eficiência e boa experiência ao usuário.        |
| **Origem do Requisito:** Entrevista, MoSCoW                                 |
| **Critério de Aceitação:** 95% das ações respondem em até 2s.               |
| **Dependências:** Infraestrutura adequada                                   |
| **Prioridade:**                                                             |
| **Conflitos:** Pode conflitar com segurança em operações críticas           |
| **História:** 2025                                                          |

<p align="center">Fonte: <a href="https://github.com/kalebmacedo">Kaleb Macedo</a> e <a href="https://github.com/">Lucas Alves</a></p>

<p align="center"><b>Tabela 3 - Cartão de Especificação 3</b></p>

| Nº Requisito: RNF07                                                            | Classificação: Conformidade |
| ------------------------------------------------------------------------------ | --------------------------- |
| **Descrição:** Garantir conformidade com a Portaria nº 127/2024 e LGPD.        |
| **Justificativa:** Atender às exigências legais e proteger dados dos usuários. |
| **Origem do Requisito:** Documentação oficial                                  |
| **Critério de Aceitação:** Auditoria confirma aderência legal.                 |
| **Dependências:** Implementação de políticas de privacidade                    |
| **Prioridade:**                                                                |
| **Conflitos:** Pode impactar desempenho                                        |
| **História:** 2025                                                             |

<p align="center">Fonte: <a href="https://github.com/kalebmacedo">Kaleb Macedo</a> e <a href="https://github.com/">Lucas Alves</a></p>

<p align="center"><b>Tabela 4 - Cartão de Especificação 4</b></p>

| Nº Requisito: RNF08                                                    | Classificação: Desempenho |
| ---------------------------------------------------------------------- | ------------------------- |
| **Descrição:** Processar autorizações prévias em até 10 dias úteis.    |
| **Justificativa:** Cumprir prazos regulatórios e garantir agilidade.   |
| **Origem do Requisito:** Three Level Scale                             |
| **Critério de Aceitação:** 100% das autorizações processadas no prazo. |
| **Dependências:** Processos internos otimizados                        |
| **Prioridade:**                                                        |
| **Conflitos:** Nenhum                                                  |
| **História:** 2025                                                     |

<p align="center">Fonte: <a href="https://github.com/kalebmacedo">Kaleb Macedo</a> e <a href="https://github.com/">Lucas Alves</a></p>

<p align="center"><b>Tabela 5 - Cartão de Especificação 5</b></p>

| Nº Requisito: RNF15                                                                      | Classificação: Acessibilidade |
| ---------------------------------------------------------------------------------------- | ----------------------------- |
| **Descrição:** Compatibilidade com leitores de tela para pessoas com deficiência visual. |
| **Justificativa:** Tornar o sistema acessível a todos os usuários.                       |
| **Origem do Requisito:** Introspecção                                                    |
| **Critério de Aceitação:** Testes com leitores de tela aprovados.                        |
| **Dependências:** Implementação de padrões de acessibilidade                             |
| **Prioridade:**                                                                          |
| **Conflitos:** Nenhum                                                                    |
| **História:** 2025                                                                       |

<p align="center">Fonte: <a href="https://github.com/kalebmacedo">Kaleb Macedo</a> e <a href="https://github.com/">Lucas Alves</a></p>

<p align="center"><b>Tabela 6 - Cartão de Especificação 6</b></p>

| Nº Requisito: RNF10                                                                 | Classificação: Usabilidade |
| ----------------------------------------------------------------------------------- | -------------------------- |
| **Descrição:** As informações críticas para o usuário, como a carteirinha digital, devem estar acessíveis em até 3 cliques, sendo recomendado no máximo 2 cliques a partir da tela inicial do aplicativo. |
| **Justificativa:** Facilitar o acesso rápido a informações essenciais, melhorando a experiência do usuário. |
| **Origem do Requisito:** Grupo Focal, Introspecção                                  |
| **Critério de Aceitação:** Usuário acessa a carteirinha digital em até 3 cliques.   |
| **Dependências:** Estrutura de navegação clara                                      |
| **Prioridade:** Alta                                                                |
| **Conflitos:** Pode impactar a complexidade do layout                               |
| **História:** 2025                                                                  |

<p align="center">Fonte: <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a> e <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

<p align="center"><b>Tabela 7 - Cartão de Especificação 7</b></p>

| Nº Requisito: RNF12                                                                 | Classificação: Suporte     |
| ----------------------------------------------------------------------------------- | -------------------------- |
| **Descrição:** O aplicativo deve disponibilizar uma funcionalidade de chat com um atendente em até 2 cliques a partir da tela inicial e mostrar um número de telefone para suporte. |
| **Justificativa:** Garantir suporte eficiente e acessível ao usuário.               |
| **Origem do Requisito:** Introspecção                                               |
| **Critério de Aceitação:** Suporte disponível e funcional nos canais especificados e o usuário acessa em até 2 cliques.  |
| **Dependências:** Integração com sistema de atendimento                             |
| **Prioridade:** Média                                                               |
| **Conflitos:** Pode aumentar o custo de manutenção                                  |
| **História:** 2025                                                                  |

<p align="center">Fonte: <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a> e <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

## Requisitos Não-Funcionais

<p align="center"><b>Tabela 8 - Requisitos Não-Funcionais Utilizados</b></p>

| ID                                                                                              | Tema           | Descrição                                                                                                                                                                                  | Fonte                                                                                                                                                                                                                       | Critério de Aceitação                                    | Implementação |
| ----------------------------------------------------------------------------------------------- | -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- | ------------- |
| [RNF02](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF02) | Desempenho     | Tempo de resposta das ações não deve ultrapassar 2 segundos.                                                                                                                               | [EN11](../../elicitacao/tecnicas/entrevista.md#EN11), [GF17](../../elicitacao/tecnicas/grupo_focal.md#GF17), [IS14](../../elicitacao/tecnicas/introspeccao.md#IS14), [QT12](../../elicitacao/tecnicas/questionario.md#QT12) | 95% das ações respondem em até 2s.                       | Não           |
| [RNF06](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF06) | Acessibilidade | O aplicativo deve ser compatível com leitores de tela para garantir acessibilidade a pessoas com deficiência visual.                                                                       | [IS20](../../elicitacao/tecnicas/introspeccao.md#IS20), [QT14](../../elicitacao/tecnicas/questionario.md#QT14)                                                                                                              | Testes com leitores de tela aprovados.                   | Não           |
| [RNF07](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF07) | Conformidade   | Garantir conformidade com a Portaria nº 127/2024 e LGPD.                                                                                                                                   | [GL10](../../elicitacao/tecnicas/glossario.md#GL10), [QT15](../../elicitacao/tecnicas/questionario.md#QT15)                                                                                                                 | Auditoria confirma aderência legal.                      | Não           |
| [RNF08](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF08) | Desempenho     | Processar autorizações prévias em até 10 dias úteis.                                                                                                                                       | [GL13](../../elicitacao/tecnicas/glossario.md#GL13)                                                                                                                                                                         | 100% das autorizações processadas no prazo.              | Não           |
| [RNF10](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF10) | Usabilidade    | As informações críticas para o usuário, como a carteirinha digital, devem estar acessíveis em até 3 cliques, sendo recomendado no máximo 2 cliques a partir da tela inicial do aplicativo. | [GF15](../../elicitacao/tecnicas/grupo_focal.md#GF15), [IS16](../../elicitacao/tecnicas/introspeccao.md#IS16)                                                                                                               | Usuário acessa a carteirinha digital em até 3 cliques.   | Não           |
| [RNF11](../../elicitacao/requisitos_finais.md#RNF11)                                            | Usabilidade    | O sistema deve armazenar e permitir o acesso ao histórico de notificações do usuário por no mínimo 180 dias.                                                                               | [GF16](../../elicitacao/tecnicas/grupo_focal.md#GF16)                                                                                                                                                                       | Histórico de notificações acessível por 180 dias.        | Não           |
| [RNF12](../../elicitacao/requisitos_finais.md#RNF12)                                            | Suporte        | O aplicativo deve disponibilizar uma funcionalidade de chat com um atendente em até 2 cliques a partir da tela inicial e mostrar um número de telefone para suporte.                       | [IS15](../../elicitacao/tecnicas/introspeccao.md#IS15)                                                                                                                                                                      | Suporte disponível e funcional nos canais especificados. | Não           |
| [RNF14](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF14) | Usabilidade    | O layout deve ser consistente com o portal oficial do plano.                                                                                                                               | [QT16](../../elicitacao/tecnicas/questionario.md#QT16)                                                                                                                                                                      | Layout aprovado em revisão de consistência visual.       | Não           |
| [RNF06](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF06) | Acessibilidade | Compatibilidade com leitores de tela para pessoas com deficiência visual.                                                                                                                  | [IS20](../../elicitacao/tecnicas/introspeccao.md#IS20), [QT14](../../elicitacao/tecnicas/questionario.md#QT14)                                                                                                              | Testes com leitores de tela aprovados.                   | Não           |
| [RNF16](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF16) | Acessibilidade | O sistema deve ser acessível em Português.                                                                                                                                                 | [IS21](../../elicitacao/tecnicas/introspeccao.md#IS21)                                                                                                                                                                      | Todo o conteúdo disponível em Português.                 | Não           |

<p align="center">Fonte: <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>, <a href="https://github.com/">Lucas Alves</a> e <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

## Gráfico de Interdependência de Softgoals (SIG)

A Figura 3 apresenta o Gráfico de Interdependência de Softgoals (SIG) para os Requisitos Não-Funcionais do projeto. Este gráfico ilustra as relações entre os softgoals, destacando como cada requisito contribui para a satisfação dos objetivos gerais do sistema.

<p align="center">Figura 3 - Gráfico de Interdependência de Softgoals (SIG)</p>

<img src="..\..\..\assets\nfr\geral.jpeg" alt="Gráfico de Interdependência de Softgoals (SIG)" width="800">

<p align="center">Fonte: (SILVA, 2019)</p>

### <a id="NFR01"></a>NFR 01 - Usabilidade

Os requisitos utilizados para o NFR 01 (usabilidade) estão presentes na tabela 6, e são:

- RNF06: O aplicativo deve ser compatível com leitores de tela para garantir acessibilidade a pessoas com deficiência visual.
- RNF12: O aplicativo deve disponibilizar uma funcionalidade de chat com um atendente em até 2 cliques a partir da tela inicial e mostrar um número de telefone para suporte.
- RNF10: As informações críticas para o usuário, como a carteirinha digital, devem estar acessíveis em até 3 cliques, sendo recomendado no máximo 2 cliques a partir da tela inicial do aplicativo.
- RNF14: O layout deve ser consistente com o portal oficial do plano.
- RNF16: O sistema deve ser acessível em Português.

A figura 4 apresenta o gráfico de interdependência de softgoals (SIG) para o NFR 01, destacando as relações de contribuição entre os requisitos de usabilidade.

<p align="center">Figura 4 - Gráfico de Interdependência de Softgoals (SIG) - NFR 01</p>

<img src="..\..\..\assets\nfr\usabilidade.jpeg" alt="Gráfico de Interdependência de Softgoals (SIG) - NFR 01" width="800">

<p align="center">Fonte: (SILVA, 2019)</p>

**Avaliação dos softgoals de usabilidade:**

- **RNF06 (Acessibilidade)**: Francamente Satisfeito (𝒲+) – O aplicativo é compatível com leitores de tela, mas com algumas limitações
- **RNF12 (Suporte)**: Francamente Satisfeito (𝒲+) – O suporte por chat não está disponível, mas por telefone está funcionando adequadamente.
- **RNF10 (Acessibilidade)**: Satisfeito (✓) – A carteirinha digital é acessível em até 3 cliques.
- **RNF11 (Histórico)**: Negado (X) – O sistema não armazena o histórico de notificações por 180 dias conforme especificado.
- **RNF14 (Consistência Visual)**: Indeterminado (u)

### <a id="NFR02"></a>NFR 02 - Desempenho

Os requisitos utilizados para o NFR 02 (desempenho) estão presentes na tabela 6, e são:

- RNF02: Tempo de resposta das ações não deve ultrapassar 2 segundos.
- RNF08: Processar autorizações prévias em até 10 dias úteis.

A figura 5 apresenta o gráfico de interdependência de softgoals (SIG) para o NFR 02, destacando as relações de contribuição entre os requisitos de desempenho.

<p align="center">Figura 5 - Gráfico de Interdependência de Softgoals (SIG) - NFR 02</p>

<img src="..\..\..\assets\nfr\desempenho.jpeg" alt="Gráfico de Interdependência de Softgoals (SIG) - NFR 02" width="800">

<p align="center">Fonte: (SILVA, 2019)</p>

**Avaliação dos softgoals de desempenho:**

- **RNF02 (Desempenho)**: Francamente (𝒲-) – Testes mostram que algumas ações possuem tempo de resposta maior que 2s.
- **RNF08 (Desempenho)**: Satisfeito (✓) – 100% das autorizações prévias são processadas em até 10 dias úteis.

### <a id="NFR03"></a>NFR 03 - Conformidade

Os requisitos utilizados para o NFR 03 (conformidade) estão presentes na tabela 6, e são:

- RNF07: Garantir conformidade com a Portaria nº 127/2024 e LGPD.

A figura 6 apresenta o gráfico de interdependência de softgoals (SIG) para o NFR 03, destacando as relações de contribuição entre os requisitos de conformidade.

<p align="center">Figura 6 - Gráfico de Interdependência de Softgoals (SIG) - NFR 03</p>

<div align="center">
  <img src="..\..\..\assets\nfr\conformidade.jpeg" alt="Gráfico de Interdependência de Softgoals (SIG) - NFR 03" width="300" height="100">
</div>

<p align="center">Fonte: (SILVA, 2019)</p>

**Avaliação dos softgoals de conformidade:**

- **RNF07 (Conformidade)**: Indeterminado (u) – Auditoria pendente para verificar a conformidade com a Portaria nº 127/2024 e LGPD.

### <a id="NFR04"></a>NFR 04 - Acessibilidade

Os requisitos utilizados para o NFR 04 (acessibilidade) estão presentes na tabela 6, e são:

- RNF06: O aplicativo deve ser compatível com leitores de tela para garantir acessibilidade a pessoas com deficiência visual.
- RNF16: O sistema deve ser acessível em Português.

A figura 7 apresenta o gráfico de interdependência de softgoals (SIG) para o NFR 04, destacando as relações de contribuição entre os requisitos de acessibilidade.

<p align="center">Figura 7 - Gráfico de Interdependência de Softgoals (SIG) - NFR 04</p>

<div align="center">
  <img src="..\..\..\assets\nfr\acessibilidade.jpeg" alt="Gráfico de Interdependência de Softgoals (SIG) - NFR 04" width="300" height="100">
</div>

<p align="center">Fonte: (SILVA, 2019)</p>

**Avaliação dos softgoals de acessibilidade:**

- **RNF06 (Acessibilidade)**: Francamente Satisfeito (𝒲+) – O aplicativo é compatível com leitores de tela, mas com algumas limitações.
- **RNF16 (Acessibilidade)**: Satisfeito (✓) – Todo o conteúdo do sistema está disponível em Português.

### Exemplo de Avaliação

- **RNF02 (Desempenho)**: Satisfeito (✓) – Testes mostram tempo de resposta adequado.
- **RNF15 (Acessibilidade)**: Fracamente Satisfeito (𝒲+) – Compatível com leitores de tela, mas com pequenas limitações.
- **RNF07 (Conformidade)**: Indeterminado (u) – Auditoria pendente.

### Responsáveis

- Modelagem: Isaque Camargos, Ana Luiza Soares, Kaleb Macedo, Lucas Alves, Matheus de Alcântara, Othavio Bolzan, Yzabella Miranda
- Validação: conforme tabelas de integrantes do grupo.

## Referência Bibliográfica

SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: [Link](https://repositorio.ufpe.br/handle/123456789/34150). Acesso em: 30 de maio de 2025.

CHUNG, L.; NIXON, B. A.; YU, E.; MYLOPOULOS, J. Non-functional requirements in software engineering. Springer Science & Business Media: [s.n.], 2000. v. 5.

<p align="center"><b>Tabela 8 - Histórico de Versões</b></p>

| Versão | Data       | Descrição                                                                                                                                                                 | Autor(es)                                                                                                                                                      | Revisor(es)                                    |
| ------ | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| `1.0`  | 01/06/2025 | Estruturação do documento inicial, adicionando introdução, metodologia, as explicações sobre o sig, decomposição, contribuição, procedimento de avaliação e refenrencias. | [Lucas Alves](https://github.com/)                                                                                                                             | [Kaleb Macedo](https://github.com/kalebmacedo) |
| `1.1`  | 01/06/2025 | Arrumando questões de imagem, fonte e prioridade.                                                                                                                         | [Lucas Alves](https://github.com/)                                                                                                                             | [Kaleb Macedo](https://github.com/kalebmacedo) |
| `1.2`  | 01/06/2025 | Fonte nas tabelas.                                                                                                                                                        | [Lucas Alves](https://github.com/)                                                                                                                             | [Kaleb Macedo](https://github.com/kalebmacedo) |
| `1.3`  | 01/06/2025 | Adicionando os SIG de cada NFR e a avaliação dos softgoals.                                                                                                               | [Matheus de Alcântara](https://github.com/matheusdealcantara), [Yzabella Miranda](https://github.com/redjsun) e [Othavio Bolzan](https://github.com/BolzanMGB) | [Kaleb Macedo](https://github.com/kalebmacedo) |
