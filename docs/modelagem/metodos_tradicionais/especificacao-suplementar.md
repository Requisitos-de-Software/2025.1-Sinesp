# Especificação Suplementar 

## Introdução

A Especificação Suplementar é um artefato importante para o processo de desenvolver um projeto em engenharia de requisitos, particularmente em abordagens orientadas ao processo unificado (RUP). Este documento visa complementar o Documento de Requisitos, detalhando aspectos que não são abordados diretamente nos casos de uso, com foco principal nos requisitos não funcionais.

Diferente dos requisitos funcionais, que descrevem comportamentos e funcionalidades específicas esperadas do sistema, os requisitos não funcionais referem-se a atributos de qualidade que influenciam diretamente a experiência do usuário, a robustez do sistema e a viabilidade de manutenção e evolução do software. Estes incluem características como usabilidade, confiabilidade, desempenho, segurança, portabilidade, entre outros.

Este documento está estruturado com base no modelo **FURPS+**, que categoriza os  funcionais as seguintes classificações:

-   **Functionality (Funcionalidade)**: Aspectos funcionais adicionais não descritos em casos de uso.
    
-   **Usability (Usabilidade)**: Facilidade de uso, acessibilidade, estética, feedback ao usuário.
    
-   **Reliability (Confiabilidade)**: Tolerância a falhas, recuperação de erros, disponibilidade e estabilidade.
    
-   **Performance (Desempenho)**: Tempos de resposta, throughput, tempo de processamento, eficiência.
    
-   **Supportability (Manutenibilidade)**: Facilidade de manutenção, escalabilidade, adaptabilidade, internacionalização, extensibilidade.
  
---

## Integrantes

Na tabela 1 contêm todos os integrantes da equipe que participaram desta etapa de Especificação Suplementar e o que a pessoa desenvolveu durante o projeto.

<p align="center">Tabela 1 -  Integrantes </p>

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
                <td><a href="https://github.com/kalebmacedo">Kaleb Macedo</a></td>
                <td>Criação do documento de E.S., seleção dos  base no FURPS, adição dos <a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF07">RNF07</a> e <a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF08">RNF08</a></td>
            </tr>
            <tr>
                <td><a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></td>
                <td>Classificação dos requisitos não funcionais: <a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF01">RNF01</a>, <a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF02">RNF02</a> e <a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF03">RNF03</a>.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/isaqzin">Isaque Camargos</a></td>
                <td>Classificação dos requisitos não funcionais: <a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF04">RNF04</a>, <a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF06">RNF06</a>.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/bolzanMGB">Othavio Bolzan</a></td>
                <td>Classificação dos requisitos não funcionais: <a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF13">RNF13</a>, <a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF14">RNF14</a>.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/LucasAlves71">Lucas Alves</a></td>
                <td>Classificação dos requisitos não funcionais: <a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF09">RNF09</a>, <a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF10">RNF10</a>.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></td>
                <td>Classificação dos requisitos não funcionais: <a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF11">RNF11</a>, <a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF12">RNF12</a>.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/redjsun">Yzabella Miranda</a></td>
                <td>Classificação dos requisitos não funcionais:<a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF15">RNF15</a>, <a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF16">RNF16</a>.</td>
            </tr>
        </tbody>
    </table>
</div>

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a> e <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

## Metodologia

A construção desta Especificação Suplementar foi feita de forma colaborativa, baseada no modelo FURPS+, a fim de organizar oequisitos não funcionais do projeto de maneira clara e objetiva. Para isso, analisamos os requisitos funcionais já definidos e identificamos atributos de qualidade relevantes ao sistema, como usabilidade, confiabilidade e desempenho.

Evitamos utilizar modelos prontos, buscando adaptar a estrutura às particularidades do nosso projeto. A escrita seguiu uma linguagem natural e acessível, facilitando a compreensão por todos os envolvidos, desde a equipe técnica até os stakeholders não técnicos.gia utilizada durante esta etapa, com fontes, se quiser colocar foto coloque, se for gravado acho bom colocar logo aqui como:


##  Especificação Suplementar Realizada

### 1. Funcionalidade
As funcionalidades foram elicitadas e podem ser encontradas em Elicitação de requisitos e nos Casos de usos levantados.


### 2. Usabilidade

Este tópico lista os requisitos que garantem que a interação do usuário com o sistema seja intuitiva, acessível e eficiente.

<p align="center">Tabela 2 Requisitos de Usabilidade</p>

<table>
  <thead>
    <tr>
      <th>Requisito</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF01">RNF01</a></td><td>A interface deve ser intuitiva, clara e adaptada para idosos/pessoas com baixa familiaridade tecnológica.</td></tr>
    <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF06">RNF06</a></td><td>O aplicativo deve ser compatível com leitores de tela para garantir acessibilidade a pessoas com deficiência visual.</td></tr>
    <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF10">RNF10</a></td><td>As informações críticas para o usuário, como a carteirinha digital, devem estar acessíveis em até 3 cliques, sendo recomendado no máximo 2 cliques a partir da tela inicial do aplicativo.</td></tr>
    <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF12">RNF12</a></td><td>O aplicativo deve oferecer suporte por chat ou telefone.</td></tr>
    <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF14">RNF14</a></td><td>O layout deve ser consistente com o portal oficial do plano.</td></tr>
    <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF16">RNF16</a></td><td>O sistema deve ser acessível em Português.</td></tr>
  </tbody>
</table>

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>, <a href="https://github.com/isaqzin">Isaque Camargos</a>,  <a href="https://github.com/bolzanMGB">Othavio Bolzan</a>, <a href="https://github.com/redjsun">Yzabella Miranda</a> <a ref="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a> e <a  href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>



### 3. Confiabilidade


Esta seção trata da estabilidade e segurança dadas pelo sistema, bem como sua capacidade de operar corretamente mesmo em situações inesperadas.

<p align="center"> Tabela 3 Requisitos de Confiabilidade</p>

<table>
  <thead>
    <tr>
      <th>Requisito</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF03">RNF03</a></td><td>Assegurar segurança no acesso e armazenamento de dados pessoais, criptografar dados sensíveis conforme LGPD, incluir autenticação em dois fatores e ser transparente quanto ao uso e segurança dos dados.</td></tr>
   <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF04">RNF04</a></td><td>Manter o sistema disponível 24/7 para autorizações de urgência/emergência e apresentar alta disponibilidade (mínimo de 99% uptime).</td></tr>
    <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF07">RNF07</a></td><td>Garantir conformidade com a Portaria nº 127/2024, legislações complementares e padrões da LGPD.</td></tr>
    <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF09">RNF09</a></td><td>O sistema deve garantir comunicação segura e periódica com a folha de pagamento do GDF para processar descontos de mensalidades dos titulares, com mecanismos de verificação para garantir a integridade e consistência dos valores deco.</td></tr>
    <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF13">RNF13</a></td><td>Funciona offline para carteirinha e histórico.</td</tr>
    <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF15">RNF15</a></td><td>Autenticação via GovBR.</td></tr>
  </tbody>
</table>

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>, <a href="https://github.com/isaqzin">Isaque Camargos</a>,  <a href="https://github.com/bolzanMGB">Othavio Bolzan</a>, <a href="https://github.com/redjsun">Yzabella Miranda</a> <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a> e <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>


### 4. Suportabilidade

Esta seção descreve os requisitos relacionados istema de oferecer manutenção, escalabilidade, adaptabilidade, internacionalização e extensibilidade.

<p align="center">Tabela  4 - Requisitos de Suportabilidade</p>

<table>
  <thead>
    <tr>
      <th>Requisito</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF05">RNF05</a></td><td>O sistema deve ser compatível com diferentes versões do Android e iOS, a partir das versões mais utilizadas no mercado.</td></tr>
  </tbody>
</table>

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>  e  <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

### 5. Performance

Esta seção descreve os requisitos relacionados ao desempenho do sistema, incluindo tempos de resposta, escalabilidade e eficiência sob carga.

<p align= "center"> Tabela 5 - Requisitos de Performance</p>

<table>
  <thead>
    <tr>
      <th>Requisito</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF02">RNF02</a></td><td>Todas as funcionalidades devem responder em ≤2 segundos.</td></tr>
    <tr><td><a href="https://requisitos-de-software.github.io/2025.1-GDF-Saude/elicitacao/elicitacao/#RNF08">RNF08</a></td><td>Processar autorizações prévias em até 10 dias úteis.</td></tr>
  </tbody>
</table>

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a> e <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>


## Referências Bibliográficas

SERRANO, Milene; SERRANO, Maurício. **Requisitos - Aula 13**, disponível em:[slide](https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf), s.d, slides 28-30

BRASIL. Ministério da Ciência, Tecnologia e Inovações. **Especificação Suplementar**. pag 4-5. Disponível em: [especificação suplementar](https://pdp.mctic.gov.br/MCTI-PDP/guidances/examples/Especificacao%20Suplementar_4C68A4F4.html). Acesso em: 17 maio 2025.



## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|-----------|-----------|-------------|
| 1.0 | 16/05/2025 | Criação detalhada do documento e escolha dos requeisitos | [Kaleb Macedo](https://github.com/kalebmacedo)  |[Ana Luiza Soares](https://github.com/Ana-Luiza-SC) |
| 1.1 | 17/05/2025 | Adição das especificações relacionadas aos RNF15, RNF15 | [Yzabella](https://github.com/redjsun)  | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) |
| 1.2 | 17/05/2025 | Adição das especificações relacionadas aos RNF01, RNF02 e RNF03 | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC)  | [Kaleb Macedo](https://github.com/kalebmacedo)|
| 1.3 | 18/05/2025 | Adição das especificações relacionadas aos RNF10, RNF09 | [Lucas Alves](https://github.com/)  | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC)|
| 1.4 | 18/05/2025 | Adição detalhada do documento e escolha dos requisitos |  [Kaleb Macedo](https://github.com/kalebmacedo) |  [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) |
| 1.5 | 18/05/2025 | Adição das especificações relacionadas aos RNF04, RNF06 | [Isaque Camargos](https://github.com/isaqzin)  | [Lucas Alves](https://github.com/)|
| 1.6 | 18/05/2025 | Adição das especificações relacionadas aos RNF11, RNF12 | [Matheus de Alcântara](https://github.com/matheusdealcantara)  | [Lucas Alves](https://github.com/)|
| 1.7 | 18/05/2025 | Adição das especificações relacionadas aos RNF13, RNF14 | [Othavio Bolzan](https://github.com/bolzanMG)  | [Lucas Alves](https://github.com/)|