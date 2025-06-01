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

Para a criação do NFR Framework, selecionamos todos os requisitos não funcionais elicitados no projeto (ver [docs/elicitacao/elicitacao.md](docs/elicitacao/elicitacao.md)), classificando-os em temas como usabilidade, desempenho, segurança, acessibilidade e conformidade legal. Cada requisito foi detalhado em um cartão de especificação, contendo nome, descrição, fonte, critérios de aceitação e possíveis conflitos.

A seguir, organizamos os requisitos em um Gráfico de Interdependência de Softgoals (SIG), representando visualmente as relações de contribuição (MAKE, HELP, HURT, BREAK, etc.) e refinamento entre os softgoals. Utilizamos ferramentas como draw.io para a construção do SIG.

A avaliação dos softgoals foi realizada aplicando os rótulos do NFR Framework, propagando as decisões do nível mais baixo até o topo da hierarquia, conforme descrito no procedimento de avaliação.

### Cartões de Especificação

As tabelas a seguir detalham os requisitos não-funcionais elicitados para o projeto, com base nas fontes e critérios definidos.

<center>

**Tabela 1** - Cartão de Especificação 1

| Nº Requisito: RNF01 | Classificação: Usabilidade |
|---------------------|---------------------------|
| **Descrição:** O sistema deve ser fácil de usar para todos os perfis de usuário. |
| **Justificativa:** Facilitar o uso do sistema para todos os usuários, reduzindo a curva de aprendizado. |
| **Origem do Requisito:** Brainstorm, Introspecção |
| **Critério de Aceitação:** Usuários realizam tarefas básicas sem auxílio externo. |
| **Dependências:** Nenhuma |
| **Prioridade:**  |
| **Conflitos:** Nenhum |
| **História:** 2025 |

Fonte: [Kaleb Macedo](https://github.com/kalebmacedo) e [Lucas Alves](https://github.com/)

</center>

<center>

**Tabela 2** - Cartão de Especificação 2

| Nº Requisito: RNF02 | Classificação: Desempenho |
|---------------------|--------------------------|
| **Descrição:** Tempo de resposta das ações não deve ultrapassar 2 segundos. |
| **Justificativa:** Garantir eficiência e boa experiência ao usuário. |
| **Origem do Requisito:** Entrevista, MoSCoW |
| **Critério de Aceitação:** 95% das ações respondem em até 2s. |
| **Dependências:** Infraestrutura adequada |
| **Prioridade:**  |
| **Conflitos:** Pode conflitar com segurança em operações críticas |
| **História:** 2025 |

Fonte: [Kaleb Macedo](https://github.com/kalebmacedo) e [Lucas Alves](https://github.com/)

</center>

<center>

**Tabela 3** - Cartão de Especificação 3

| Nº Requisito: RNF07 | Classificação: Conformidade |
|---------------------|----------------------------|
| **Descrição:** Garantir conformidade com a Portaria nº 127/2024 e LGPD. |
| **Justificativa:** Atender às exigências legais e proteger dados dos usuários. |
| **Origem do Requisito:** Documentação oficial |
| **Critério de Aceitação:** Auditoria confirma aderência legal. |
| **Dependências:** Implementação de políticas de privacidade |
| **Prioridade:**  |
| **Conflitos:** Pode impactar desempenho |
| **História:** 2025 |

Fonte: [Kaleb Macedo](https://github.com/kalebmacedo) e [Lucas Alves](https://github.com/)

</center>

<center>

**Tabela 4** - Cartão de Especificação 4

| Nº Requisito: RNF08 | Classificação: Desempenho |
|---------------------|--------------------------|
| **Descrição:** Processar autorizações prévias em até 10 dias úteis. |
| **Justificativa:** Cumprir prazos regulatórios e garantir agilidade. |
| **Origem do Requisito:** Three Level Scale |
| **Critério de Aceitação:** 100% das autorizações processadas no prazo. |
| **Dependências:** Processos internos otimizados |
| **Prioridade:**  |
| **Conflitos:** Nenhum |
| **História:** 2025 |

Fonte: [Kaleb Macedo](https://github.com/kalebmacedo) e [Lucas Alves](https://github.com/)

</center>

<center>

**Tabela 5** - Cartão de Especificação 5

| Nº Requisito: RNF15 | Classificação: Acessibilidade |
|---------------------|------------------------------|
| **Descrição:** Compatibilidade com leitores de tela para pessoas com deficiência visual. |
| **Justificativa:** Tornar o sistema acessível a todos os usuários. |
| **Origem do Requisito:** Introspecção |
| **Critério de Aceitação:** Testes com leitores de tela aprovados. |
| **Dependências:** Implementação de padrões de acessibilidade |
| **Prioridade:**  |
| **Conflitos:** Nenhum |
| **História:** 2025 |

Fonte: [Kaleb Macedo](https://github.com/kalebmacedo) e [Lucas Alves](https://github.com/)

</center>

## Requisitos Não-Funcionais

A tabela a seguir lista os requisitos não-funcionais utilizados para a criação do NFR Framework deste projeto.

| ID    | Tema           | Descrição                                                                 | Fonte                | Critério de Aceitação                  | Implementação |
|-------|----------------|--------------------------------------------------------------------------|----------------------|----------------------------------------|---------------|
| RNF01 | Usabilidade    | O sistema deve ser fácil de usar para todos os perfis de usuário.         | [Kaleb Macedo](https://github.com/kalebmacedo) e [Lucas Alves](https://github.com/) | Usuários realizam tarefas básicas sem auxílio externo. | Não           |
| RNF02 | Desempenho     | Tempo de resposta das ações não deve ultrapassar 2 segundos.              | [Kaleb Macedo](https://github.com/kalebmacedo) e [Lucas Alves](https://github.com/)   | 95% das ações respondem em até 2s.     | Não           |
| RNF07 | Conformidade   | Garantir conformidade com a Portaria nº 127/2024 e LGPD.                 | [Kaleb Macedo](https://github.com/kalebmacedo) e [Lucas Alves](https://github.com/) | Auditoria confirma aderência legal.    | Não           |
| RNF08 | Desempenho     | Processar autorizações prévias em até 10 dias úteis.                     | [Kaleb Macedo](https://github.com/kalebmacedo) e [Lucas Alves](https://github.com/)    | 100% das autorizações processadas no prazo. | Não           |
| RNF15 | Acessibilidade | Compatibilidade com leitores de tela para pessoas com deficiência visual. | [Kaleb Macedo](https://github.com/kalebmacedo) e [Lucas Alves](https://github.com/)        | Testes com leitores de tela aprovados. | Não           |

Fonte: [Kaleb Macedo](https://github.com/kalebmacedo) e [Lucas Alves](https://github.com/)

### Gráfico de Interdependência de Softgoals (SIG)

- **Usabilidade**  
  - Contribui para: Satisfação do usuário (HELP)
  - Refinado em: Facilidade de uso, Acessibilidade

- **Desempenho**
  - Contribui para: Eficiência operacional (MAKE)
  - Refinado em: Tempo de resposta, Processamento de autorizações

- **Segurança**
  - Contribui para: Conformidade legal (HELP), pode conflitar com Desempenho (HURT)

- **Acessibilidade**
  - Contribui para: Usabilidade (MAKE)

- **Conformidade legal**
  - Refinado em: LGPD, Portaria 127/2024


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



| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
|--------|------------|-------------------------------------------|-----------------------------------|----------------------|
| `1.0`  | 01/06/2025 | Estruturação do documento inicial, adicionando introdução, metodologia, as explicações sobre o sig, decomposição, contribuição, procedimento de avaliação e refenrencias.      | [Lucas Alves](https://github.com/)  | [Kaleb Macedo](https://github.com/kalebmacedo) |
| `1.1`  | 01/06/2025 | Arrumando questões de imagem, fonte e prioridade.      | [Lucas Alves](https://github.com/)  | [Kaleb Macedo](https://github.com/kalebmacedo) |
| `1.2`  | 01/06/2025 | Fonte nas tabelas.      | [Lucas Alves](https://github.com/)  | [Kaleb Macedo](https://github.com/kalebmacedo) |



