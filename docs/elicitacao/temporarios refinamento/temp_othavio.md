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
                <td><a href="https://github.com/Ana-Luiza-SC">Othavio Araujo Bolzan</a></td>
                <td>Refinou os requisitos RF11, RF12.1, RF12.2, RF12.3, RF12.4, RF12.5, RF12.6 RNF13 e RNF14.</td>
            </tr>
        </tbody>
    </table>
</div>

<p  align="center">Fonte: Autoria de <a  href="https://github.com/isaqzin">Isaque Camargos</a>, <a  href="https://github.com/isaqzin">Yzabella Miranda</a>, <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a> e <a href="https://github.com/bolzanMGB">Othavio Araujo Bolzan</a></p>

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
| <a id="RF11"></a>RF11 | Oferecer um canal para o usuário enviar feedback sobre atendimentos.|[GF09](../elicitacao/tecnicas/grupo_focal.md#GF09)    | Não              |
| <a id="RF12.1"></a>RF12.1 | Apesentar uma seção no menu principal chamada "Novidades".                                         |[GF05](../elicitacao/tecnicas/grupo_focal.md#GF05)      | Não
| <a id="RF12.2"></a>RF12.2 | Exibir uma lista com título, descrição e data de lançamento das novas funcionalidades.                                                      | [GF05](../elicitacao/tecnicas/grupo_focal.md#GF05)      | Não             |
| <a id="RF12.3"></a>RF12.3 | Destacar funcionalidades novas com um marcador de "Novo" por um período configurável (ex: 7 dias).                                                   |  [GF05](../elicitacao/tecnicas/grupo_focal.md#GF05)      | Não              |
| <a id="RF12.4"></a>RF12.4 |Exibir pop-ups informativos com as principais novidades após a atualização do aplicativo.                                                      | [GF05](../elicitacao/tecnicas/grupo_focal.md#GF05)      | Não             |
| <a id="12.5"></a>RF12.5 | Permitir que o usuário toque em uma funcionalidade da lista de novidades para ver uma descrição detalhada.                                                                       | [GF05](../elicitacao/tecnicas/grupo_focal.md#GF05)      | Não              |
| <a id="RF12.6"></a>RF12.6 |Permitir que o usuário ordene as novidades por "mais recente" e "mais antigo" no topo da lista.                         | [GF05](../elicitacao/tecnicas/grupo_focal.md#GF05)      | Não                                   | 

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzabMGB"> Othavio Araujo Bolzan</a></p>


## Requisitos Não Funcionais Refinados

Na tabela 3 encontra-se todos os requisitos não funcionais que foram ou não corrijidos.

<p align="center">Tabela 3: Requisitos Não Funcionais</p>

| **Tipo**       | **Descrição**                                                                                                                        | **Técnicas**                                                                                                                                                                         | **Implementado** |
|----------------|--------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------|
| <a id="RNF13"></a>RNF13    | Deve funcionar de forma offline para acesso à carteirinha e histórico de consultas.                               | [IS19](../elicitacao/tecnicas/introspeccao.md#IS19)                          | Não              |
| <a id="RNF14"></a>RNF14    | O layout deve ser consistente com o portal oficial do plano.                                                      | [QT16](../elicitacao/tecnicas/questionario.md#QT16)                          | Não              |
<p align="center">Fonte: Autoria de <a href="https://github.com/bolzabMGB"> Othavio Araujo Bolzan</a></p>


## Conclusão

O refinamento dos requisitos funcionais e não funcionais foi fundamental para elevar a qualidade da nossa análise. Ao torná-los indivisíveis, testáveis e quantificáveis, conseguimos mapear claramente as necessidades do usuário, planejar estratégias de validação e reduzir significativamente o risco de retrabalho durante a implementação e testes. Esse processo iterativo de revisão fortaleceu nosso entendimento do domínio e contribuiu para a robustez e confiabilidade do produto final.



## Histórico de Versões

| Versão | Data       | Descrição                                                                                                     | Autor(es)                                                                                                                                           | Revisor(es)                                      |
|--------|------------|---------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| 1.0    | 10/04/2025 | Criação da Documentação inicial contendo: A introdução, requisitos e as tabelas dos requisitos funcionais e os não funcionais          | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC), [Othavio Bolzan](https://github.com/bolzanMGB) e [Yzabella Miranda](https://github.com/redjsun) | [Isaque Camargos](https://github.com/isaqzin)     |
| 1.1    | 03/05/2025 | Atualização da tabela com a separação correta de ID e seus respectivos agrupamentos de descrição em comum                        | [Yzabella Miranda](https://github.com/redjsun) e [Matheus de Alcântara](https://github.com/matheusdealcantara)                                        | [Isaque Camargos](https://github.com/isaqzin)     |
| 1.2    | 15/05/2025 | Adição de todo o tópico Adição de novos requisitos funcionais                                                      | [Isaque Camargos](https://github.com/isaqzin)                                                                                                        | [Yzabella Miranda](https://github.com/redjsun)   |
| 2.0    | 29/05/2025 | Corrigindo os requisitos funcionais e não funcionais de forma que eles fiquem testáveis, quantificáveis e indivisíveis dos requisitos: RF01 RF02, RF21, RNF01, RNF02 e RNF03        | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC)                                                                                                   | [Matheus de Alcântara](https://github.com/matheusdealcantara) |
| 2.1    | 29/05/2025 | Adicionando meus novos requisitos funcionais: 12.1, 12.2, 12.3, 12.4, 12.5  | [Othavio Araujo Bolzan](https://github.com/bolzanMGB)                                                                                                   | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC)   |     

