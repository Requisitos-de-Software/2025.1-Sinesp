# Requisitos Elicitados Finais

## Introdução

Fizemos uma análise mais aprofundada dos requisitos funcionais e não funcionais do sistema, revisando e refinando cada um deles de forma a torná-los indivisíveis, testáveis e quantificáveis. Esse refinamento garantiu que cada requisito possa ser claramente entendido, implementado e validado, evitando ambiguidades e sobreposições que prejudicariam nosso processo de desenvolvimento e verificação.

## Tabela de Integrantes

Na tabela 1 contêm todos os integrantes da equipe que participaram no refinamento dos requisitos e o que a pessoa desenvolveu.

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
                <td><a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></td>
                <td>Refinou os requisitos RF01 RF02, RF21, RNF01, RNF02 e RNF03.</td>
            </tr>
        </tbody>
    </table>
</div>

<p  align="center">Fonte: Autoria de <a  href="https://github.com/isaqzin">Isaque Camargos</a>, <a  href="https://github.com/isaqzin">Yzabella Miranda</a> e <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

## Metodologia

Para conduzir essa revisão, seguimos as seguintes etapas:

1. **Levantamento inicial**: Coletamos todos os requisitos atuais disponíveis na página de Requisitos Elicitados:  [Clique aqui](https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/)  

2. **Análise de indivisibilidade**: Quebramos requisitos compostos em subitens (por exemplo, 1.1, 1.2 etc.), garantindo que cada requisito represente uma única necessidade do usuário ou do sistema.  

3. **Critérios de testabilidade e quantificação**: Para cada requisito, definimos métricas ou condições de aceitação claras, de modo que seja possível verificar sua implementação de forma objetiva.  

4. **Validação das elicitações**: Revisamos todas as documentações geradas durante a elicitação, assegurando que nenhum detalhe importante fosse omitido ou duplicado.  

5. **Refinamento iterativo**: A cada iteração, submetemos os requisitos revisados à equipe para revisão cruzada e incorporamos as considerações antes de avançar para a versão final.


## Requisitos Funcionais Refinados

Na tabela 2 encontra-se todos os requisitos funcionais que foram ou não corrijidos.

<p align="center">Tabela 2: Requisitos Funcionais</p>

| **Tipo**       | **Descrição**                                                                                                                                       | **Técnicas**                                                                                                                                                           | **Implementado** |
|----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------|
| <a id="RF01.1"></a>RF01.1 | O usuário poderá pesquisar redes credenciadas por meio de filtros de busca.              | [EN01](../elicitacao/tecnicas/entrevista.md#EN01), [EN02](../elicitacao/tecnicas/entrevista.md#EN02), [IS06](../elicitacao/tecnicas/introspeccao.md#IS06), [QT03](../elicitacao/tecnicas/questionario.md#QT03), [QT08](../elicitacao/tecnicas/questionario.md#QT08) | Sim              |
| <a id="RF01.2"></a>RF01.2 | O usuário poderá pesquisar profissionais da saúde (médicos, psicólogos etc.) por meio de filtros de busca.                                         | [EN01](../elicitacao/tecnicas/entrevista.md#EN01), [EN02](../elicitacao/tecnicas/entrevista.md#EN02), [IS06](../elicitacao/tecnicas/introspeccao.md#IS06), [QT03](../elicitacao/tecnicas/questionario.md#QT03), [QT08](../elicitacao/tecnicas/questionario.md#QT08) | Não              |
| <a id="RF01.3"></a>RF01.3 | Será possível combinar filtros de pesquisa (por ex. “região administrativa + especialidade”).                                                      | [EN01](../elicitacao/tecnicas/entrevista.md#EN01), [EN02](../elicitacao/tecnicas/entrevista.md#EN02), [IS06](../elicitacao/tecnicas/introspeccao.md#IS06), [QT03](../elicitacao/tecnicas/questionario.md#QT03), [QT08](../elicitacao/tecnicas/questionario.md#QT08) | Sim             |
| <a id="RF01.4"></a>RF01.4 | O filtro de pesquisa deve permitir buscas por proximidade do usuário (distância em até 10 km).                                                   |  [IS06](../elicitacao/tecnicas/introspeccao.md#IS06) | Não              |
| <a id="RF01.6"></a>RF01.6 | O Filtro permite busca pela especialidade médica                                                      | [EN01](../elicitacao/tecnicas/entrevista.md#EN01), [EN02](../elicitacao/tecnicas/entrevista.md#EN02), [IS02](../elicitacao/tecnicas/introspeccao.md#IS02), [QT03](../elicitacao/tecnicas/questionario.md#QT03), [QT08](../elicitacao/tecnicas/questionario.md#QT08) | Sim             |
| <a id="RF02.1"></a>RF02.1 | O usuário poderá avaliar atendimentos com nota na escala Likert de 0 a 5.                                                                        | [EN03](../elicitacao/tecnicas/entrevista.md#EN03), [GF01](../elicitacao/tecnicas/grupo_focal.md#GF01)                                                                     | Não              |
| <a id="RF02.2"></a>RF02.2 | O usuário poderá deixar e/ou ler comentários sobre atendimentos em clínicas ou com profissionais específicos.                                     | [EN03](../elicitacao/tecnicas/entrevista.md#EN03), [GF01](../elicitacao/tecnicas/grupo_focal.md#GF01)                                                                     | Não              |
| <a id="RF02.3"></a>RF02.3 | O sistema classificará comentários como “relevantes” ou “não relevantes” automaticamente com base em palavras-chave e upvotes de outros usuários. | [EN03](../elicitacao/tecnicas/entrevista.md#EN03), [GF01](../elicitacao/tecnicas/grupo_focal.md#GF01)                                                                     | Não              |
| <a id="RF02.4"></a>RF02.4 | O sistema ordenará clínicas por nota média de atendimento, do maior para o menor.                                                               | [EN03](../elicitacao/tecnicas/entrevista.md#EN03), [GF01](../elicitacao/tecnicas/grupo_focal.md#GF01)                                                                     | Não              |
| <a id="RF21.1"></a>RF21.1 | Chatbot conversacional que direciona o usuário à especialidade médica adequada, com precisão de pelo menos 80 % nas recomendações.               | [BS06](../elicitacao/tecnicas/brainstorm.md#BS06)                                                                                                                      | Não              |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>


## Requisitos Não Funcionais Refinados

Na tabela 3 encontra-se todos os requisitos não funcionais que foram ou não corrijidos.

<p align="center">Tabela 3: Requisitos Não Funcionais</p>

| **Tipo**       | **Descrição**                                                                                                                        | **Técnicas**                                                                                                                                                                         | **Implementado** |
|----------------|--------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------|
| <a id="RNF01.1"></a>RNF01.1 | A interface deve usar fonte mínima de 16 px e contraste de cores ≥ 4.5:1 (WCAG AA).                                                   | [EN10](../elicitacao/tecnicas/entrevista.md#EN10), [GF13](../elicitacao/tecnicas/grupo_focal.md#GF13), [IS13](../elicitacao/tecnicas/introspeccao.md#IS13), [QT11](../elicitacao/tecnicas/questionario.md#QT11) | Não              |
| <a id="RNF01.2"></a>RNF01.2 | A interface deve ser responsiva para resoluções entre 320 px e 1920 px, adaptada a dispositivos Android e iOS.                       | [EN10](../elicitacao/tecnicas/entrevista.md#EN10), [GF13](../elicitacao/tecnicas/grupo_focal.md#GF13), [IS13](../elicitacao/tecnicas/introspeccao.md#IS13), [QT11](../elicitacao/tecnicas/questionario.md#QT11) | Não              |
| <a id="RNF02.1"></a>RNF02.1 | 95 % das ações devem ter tempo de resposta ≤ 2 segundos, medido em ambiente com até 100 usuários simultâneos.                        | [EN11](../elicitacao/tecnicas/entrevista.md#EN11), [GF17](../elicitacao/tecnicas/grupo_focal.md#GF17), [IS14](../elicitacao/tecnicas/introspeccao.md#IS14), [QT12](../elicitacao/tecnicas/questionario.md#QT12) | Não              |
| <a id="RNF03.1"></a>RNF03.1 | Todos os dados sensíveis em repouso devem ser criptografados com AES-256.                                                             | [EN12](../elicitacao/tecnicas/entrevista.md#EN12), [GL12](../elicitacao/tecnicas/glossario.md#GL12), [GF12](../elicitacao/tecnicas/grupo_focal.md#GF12), [GF14](../elicitacao/tecnicas/grupo_focal.md#GF14), [IS18](../elicitacao/tecnicas/introspeccao.md#IS18), [QT15](../elicitacao/tecnicas/questionario.md#QT15) | Sim              |
| <a id="RNF03.2"></a>RNF03.2 | Autenticação de dois fatores deve estar disponível via SMS ou app de autenticação externa.                                            | [EN12](../elicitacao/tecnicas/entrevista.md#EN12), [GL12](../elicitacao/tecnicas/glossario.md#GL12), [GF12](../elicitacao/tecnicas/grupo_focal.md#GF12), [GF14](../elicitacao/tecnicas/grupo_focal.md#GF14), [IS18](../elicitacao/tecnicas/introspeccao.md#IS18), [QT15](../elicitacao/tecnicas/questionario.md#QT15) | Sim              |
| <a id="RNF03.3"></a>RNF03.3 | Logs de acesso devem ser coletados e armazenados por no mínimo 6 meses, com consulta em menos de 1 segundo por entrada de log.        | [EN12](../elicitacao/tecnicas/entrevista.md#EN12), [GL12](../elicitacao/tecnicas/glossario.md#GL12), [GF12](../elicitacao/tecnicas/grupo_focal.md#GF12), [GF14](../elicitacao/tecnicas/grupo_focal.md#GF14), [IS18](../elicitacao/tecnicas/introspeccao.md#IS18), [QT15](../elicitacao/tecnicas/questionario.md#QT15) | Sim              |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

## Conclusão

O refinamento dos requisitos funcionais e não funcionais foi fundamental para elevar a qualidade da nossa análise. Ao torná-los indivisíveis, testáveis e quantificáveis, conseguimos mapear claramente as necessidades do usuário, planejar estratégias de validação e reduzir significativamente o risco de retrabalho durante a implementação e testes. Esse processo iterativo de revisão fortaleceu nosso entendimento do domínio e contribuiu para a robustez e confiabilidade do produto final.



## Histórico de Versões

| Versão | Data       | Descrição                                                                                                     | Autor(es)                                                                                                                                           | Revisor(es)                                      |
|--------|------------|---------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| 1.0    | 10/04/2025 | Criação da Documentação inicial contendo: A introdução, requisitos e as tabelas dos requisitos funcionais e os não funcionais          | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC), [Othavio Bolzan](https://github.com/bolzanMGB) e [Yzabella Miranda](https://github.com/redjsun) | [Isaque Camargos](https://github.com/isaqzin)     |
| 1.1    | 03/05/2025 | Atualização da tabela com a separação correta de ID e seus respectivos agrupamentos de descrição em comum                        | [Yzabella Miranda](https://github.com/redjsun) e [Matheus de Alcântara](https://github.com/matheusdealcantara)                                        | [Isaque Camargos](https://github.com/isaqzin)     |
| 1.2    | 15/05/2025 | Adição de todo o tópico Adição de novos requisitos funcionais                                                      | [Isaque Camargos](https://github.com/isaqzin)                                                                                                        | [Yzabella Miranda](https://github.com/redjsun)   |
| 2.0    | 29/05/2025 | Corrigindo os requisitos funcionais e não funcionais de forma que eles fiquem testáveis, quantificáveis e indivisíveis dos requisitos: RF01 RF02, RF21, RNF01, RNF02 e RNF03        | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC)                                                                                                   | [Matheus de Alcântara](https://github.com/matheusdealcantara) |


