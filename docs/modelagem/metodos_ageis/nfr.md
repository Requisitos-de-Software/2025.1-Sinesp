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
                <td> <a href="https://github.com/isaqzin">Isaque Camarogs</a> </td>
                <td>Fez a introdução, metodologia, as explicações sobre o sig, decomposição, contribuição e procedimento de avaliação.</td>
            </tr>
        </tbody>
    </table>
</div>
<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>


## Gráfico de Interdependência de Softgoals (SIG)


O Gráfico de Interdependência de Softgoals, do inglês Softgoal Interdependency Graph (SIG),  é um gráfico utilizado no NFR Framework para representar visualmente os Requisitos Não-Funcionais (NFR) e suas interdependências. Ele registra, de forma gráfica e concisa, as decisões de desenvolvimento, as alternativas consideradas e as justificativas associadas. Através do SIG, é possível analisar como diferentes softgoals influenciam uns aos outros e avaliar se os requisitos de nível superior foram atendidos.

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

As interdependências definem as relações entre os softgoals no NFR Framework. Os principais tipos de interdependências são os*refinamentos e as contribuições <a  href="https://repositorio.ufpe.br/handle/123456789/34150" target="_blank" >(Silva, 2019).</a>

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

Para a criação do NRF selecionamos os requisitos não funcionais e os classificamos em temas, usabilidade e performance, montamos os cartões de espécificação e o gráfico de cada tema com a utilização da ferramente XXXXXXXXXXXXXXXX. 













## Referência Bibliográfica

SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: [Link](https://repositorio.ufpe.br/handle/123456789/34150). Acesso em: 30 de maio de 2025.

CHUNG, L.; NIXON, B. A.; YU, E.; MYLOPOULOS, J. Non-functional requirements in software engineering. Springer Science & Business Media: [s.n.], 2000. v. 5.



 Autor(es)                         | Revisor(es)          |
|--------|------------|-------------------------------------------|-----------------------------------|----------------------|
| `1.0`  | 18/05/2025 | Dstruturação do documento inicial, adicionando introdução, metodologia, as explicações sobre o sig, decomposição, contribuição, procedimento de avaliação e refenrencias.      | [Isaque Camargos](https://github.com/isaqzin)    |  [Ana Luiza Soares](https://github.com/Ana-Luiza-SC)                   |    