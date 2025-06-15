# Técnica de Priorização: MoSCoW

## Introdução

A técnica MoSCoW, concebida por Dai Clegg para o método RAD e posteriormente incorporada ao DSDM, é amplamente reconhecida na engenharia de requisitos, especialmente em metodologias ágeis. Seu objetivo é facilitar a priorização de funcionalidades com base em sua criticidade e impacto, classificando-as em quatro categorias: **Must Have**, **Should Have**, **Could Have** e **Won't Have (por agora)**. Essa abordagem ajuda equipes a alinhar expectativas, gerenciar recursos de forma eficiente e focar no valor real ao usuário final. Essa técnica é defendida por autores como Milene Serrano e Maurício Serrano, que destacam sua eficácia no projeto, bem como pela Agile Business Consortium. Fonte: <https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf> e <https://www.agilebusiness.org/dsdm-project-framework/moscow-prioririsation.html>.

## Integrantes do Grupo

Na tabela 1 contêm todos os integrantes da equipe que participaram desta etapa de **Priorização dos Requisitos com a técnica MoSCoW** e o que a pessoa desenvolveu durante o projeto.

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
        <td><a href="https://github.com/LucasAlves71">Lucas Alves</a></td>
        <td>Criação e documentação da técnica MoSCoW, incluindo priorização e gravação da validação com personas.</td>
      </tr>
      <tr>
        <td><a href="https://github.com/kalebmacedo">Kaleb Macedo</a></td>
        <td>Criação e padronização do documento, priorização, validação com usuário real e com personas, e implementação das alterações do professor.</td>
      </tr>
      <tr>
        <td><a href="https://github.com/isaqzin">Isaque Camargos</a></td>
        <td>Revisão da versão inicial do documento.</td>
      </tr>
      <tr>
        <td><a href="https://github.com/bolzanMGB">Othavio Bolzan</a></td>
        <td>Revisão final do documento e das alterações solicitadas.</td>
      </tr>
    </tbody>
  </table>
</div>

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>


## Usuários Reais Envolvidos

Na tabela 2 contêm as informações do usuário participante desta etapa de **Validação da Priorização**, ela contêm o nome e informações sobre a gravação que foi feita, incluindo o link para a autorização da gravação e sua postagem no Youtube de forma não listada.

<p align="center">Tabela 2 - Usuários envolvidos</p>

<div align="center">
    <table>
        <thead>
            <tr>
                <th>Nome</th>
                <th>Data</th>
                <th>Hora</th>
                <th>Local</th>
                <th>Duração da etapa</th>
                <th>Autorização da gravação</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Luana Souza</td>
                <td>04/05/2025</td>
                <td>15h30</td>
                <td>Presencial</td>
                <td>20 minutos</td>
                <td><a href="hhttps://drive.google.com/file/d/1aQm16-7rrX30TfBOBeVYdp8WP3lxQ8_1/view?usp=sharing">Link</a></td>
            </tr>
        </tbody>
    </table>
</div>

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>


## Metodologia

A técnica de priorização utilizada nesta etapa foi o **MoSCoW**, que classifica os requisitos de acordo com sua importância. Inicialmente, foi feito o levantamento por meio de técnicas como entrevistas, questionários e introspecção com base em personas, seguido por uma simulação de uso com um usuário real. Essa metodologia é descrita por Milene Serrano e Maurício Serrano (2023), destacando a importância de envolver o usuário na validação de requisitos para maximizar a relevância das funcionalidades priorizadas. Fonte: <https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>

## Estrutura de Priorização

### Must Have
Requisitos essenciais para o funcionamento do sistema.

<p align="center">Tabela 1: Must have</p>

| *Tipo* | *Descrição* | *Técnicas* | 
|----------|--------------------------------------------------------------------------------------------------------------------|-------------------------------|
| <a id="RF01"></a>RF01     | Permitir ao usuário pesquisar e filtrar clínicas e profissionais credenciados por especialidade, região administrativa, tipo de atendimento e proximidade. | [EN01](../elicitacao/tecnicas/entrevista.md#EN01), [EN02](../elicitacao/tecnicas/entrevista.md#EN02), [IS02](../elicitacao/tecnicas/introspeccao.md#IS02), [IS06](../elicitacao/tecnicas/introspeccao.md#IS06), [QT03](../elicitacao/tecnicas/questionario.md#QT03), [QT08](../elicitacao/tecnicas/questionario.md#QT08) |
| <a id="RF03"></a>RF03     | Exibir carteirinha digital mesmo sem conexão (modo offline) e permitir acesso rápido e estável.                    | [EN04](../elicitacao/tecnicas/entrevista.md#EN04), [IS09](../elicitacao/tecnicas/introspeccao.md#IS09), [QT01](../elicitacao/tecnicas/questionario.md#QT01)              |
| <a id="RF04"></a>RF04     | Enviar notificações configuráveis via app, SMS ou e-mail sobre ven e-mail sobre vencimento de fatura, retornos médicos pendentes, abertura de agenda, cancelamentos de horários, horários favoritos disponíveis, prazos importantes, confirmações ou alterações de agendamento e disponibilidade de demonstrativos de IR. | [EN05](../elicitacao/tecnicas/entrevista.md#EN05), [EN06](../elicitacao/tecnicas/entrevista.md#EN06), [GF02](../elicitacao/tecnicas/grupo_focal.md#GF02), [GF03](../elicitacao/tecnicas/grupo_focal.md#GF03), [GF07](../elicitacao/tecnicas/grupo_focal.md#GF07), [GF10](../elicitacao/tecnicas/grupo_focal.md#GF10), [IS07](../elicitacao/tecnicas/introspeccao.md#IS07), [IS12](../elicitacao/tecnicas/introspeccao.md#IS12), [QT06](../elicitacao/tecnicas/questionario.md#QT06) |
| <a id="RF05"></a>RF05     | Permitir agendamento e cancelamento de consultas e exames diretamente pelo aplicativo, com pagamento automático para prestadores da Rede de Atendimento. | [EN07](../elicitacao/tecnicas/entrevista.md#EN07), [GL01](../elicitacao/tecnicas/glossario.md#GL01), [IS01](../elicitacao/tecnicas/introspeccao.md#IS01), [IS05](../elicitacao/tecnicas/introspeccao.md#IS05), [GL06](../elicitacao/tecnicas/glossario.md#GL06)       |
| <a id="RF09"></a>RF09     | Permitir ao usuário visualizar histórico de consultas, exames realizados, resultados de exames laboratoriais e coparticipações. | [GF04](../elicitacao/tecnicas/grupo_focal.md#GF04), [GF08](../elicitacao/tecnicas/grupo_focal.md#GF08), [IS03](../elicitacao/tecnicas/introspeccao.md#IS03), [IS04](../elicitacao/tecnicas/introspeccao.md#IS04), [QT04](../elicitacao/tecnicas/questionario.md#QT04)  |
| <a id="RF15"></a>RF15     | Permitir baixar comprovantes de agendamento.                                                                       | [IS08](../elicitacao/tecnicas/introspeccao.md#IS08)                          |
| <a id="RNF01"></a>RNF01    | A interface deve ser intuitiva, clara, adaptada para idosos e pessoas com baixa familiaridade tecnológica, organizada em categorias e responsiva em smartphones Android e iOS. | [EN10](../elicitacao/tecnicas/entrevista.md#EN10), [GF13](../elicitacao/tecnicas/grupo_focal.md#GF13), [IS13](../elicitacao/tecnicas/introspeccao.md#IS13), [QT11](../elicitacao/tecnicas/questionario.md#QT11)        |
| <a id="RNF02"></a>RNF02    | Garantir carregamento rápido e fluído de todas as telas, com tempo de resposta das ações não ultrapassando 2 segundos. | [EN11](../elicitacao/tecnicas/entrevista.md#EN11), [GF17](../elicitacao/tecnicas/grupo_focal.md#GF17), [IS14](../elicitacao/tecnicas/introspeccao.md#IS14), [QT12](../elicitacao/tecnicas/questionario.md#QT12)        |
| <a id="RNF03"></a>RNF03    | Assegurar segurança no acesso e armazenamento de dados pessoais, criptografar dados sensíveis conforme LGPD, incluir autenticação em dois fatores e ser transparente quanto ao uso e segurança dos dados. | [EN12](../elicitacao/tecnicas/entrevista.md#EN12), [GL12](../elicitacao/tecnicas/glossario.md#GL12), [GF12](../elicitacao/tecnicas/grupo_focal.md#GF12), [GF14](../elicitacao/tecnicas/grupo_focal.md#GF14), [IS18](../elicitacao/tecnicas/introspeccao.md#IS18), [QT15](../elicitacao/tecnicas/questionario.md#QT15) |
| <a id="RNF05"></a>RNF05    | O sistema deve ser compatível com diferentes versões do Android e iOS, a partir das versões mais utilizadas no mercado. | [GF18](../elicitacao/tecnicas/grupo_focal.md#GF18), [IS17](../elicitacao/tecnicas/introspeccao.md#IS17), [QT11](../elicitacao/tecnicas/questionario.md#QT11)              |
| <a id="RNF07"></a>RNF07    | Garantir conformidade com a Portaria nº 127/2024, legislações complementares e padrões da LGPD.                    | [GL10](../elicitacao/tecnicas/glossario.md#GL10), [QT15](../elicitacao/tecnicas/questionario.md#QT15)                   |
| <a id="RNF10"></a>RNF10    | Garantir que informações críticas, como a carteirinha digital, estejam acessíveis em até três cliques ou com no máximo 2 cliques a partir da tela inicial. | [GF15](../elicitacao/tecnicas/grupo_focal.md#GF15), [IS16](../elicitacao/tecnicas/introspeccao.md#IS16)                    |
| <a id="RNF13"></a>RNF13    | Deve funcionar de forma offline para acesso à carteirinha e histórico de consultas.                               | [IS19](../elicitacao/tecnicas/introspeccao.md#IS19)                          |
| <a id="RNF16"></a>RNF16    | As informações exibidas devem ser claras, completas e atualizadas em tempo real.                                  | [QT13](../elicitacao/tecnicas/questionario.md#QT13)                          |


<font size="3"><p style="text-align: center">Fonte: [Lucas Alves](https://github.com/LucasAlves71) e [Kaleb Macedo](https://github.com/kalebmacedo).</p></font>

---

### Should Have
Requisitos importantes, mas que podem ser adiados se necessário.

<p align="center">Tabela 2: Should have</p>

| *Tipo* | *Descrição* | *Técnicas* |
|----------|--------------------------------------------------------------------------------------------------------------------|-------------------------------|
| <a id="RF06"></a>RF06     | Exibir valor específico de consulta em cada clínica, aplicar percentuais de coparticipação, gerar e baixar demonstrativos de despesas médicas para imposto de renda, consultar histórico de demonstrativos de IR e mostrar extrato financeiro atualizado diariamente. | [EN08](../elicitacao/tecnicas/entrevista.md#EN08), [GL04](../elicitacao/tecnicas/glossario.md#GL04), [IS10](../elicitacao/tecnicas/introspeccao.md#IS10), [IS11](../elicitacao/tecnicas/introspeccao.md#IS11), [QT02](../elicitacao/tecnicas/questionario.md#QT02), [QT05](../elicitacao/tecnicas/questionario.md#QT05) |
| <a id="RF07"></a>RF07     | Permitir cadastro de titulares, dependentes e optantes com validação de documentos e elegibilidade.                | [GL01](../elicitacao/tecnicas/glossario.md#GL01), [GL08](../elicitacao/tecnicas/glossario.md#GL08), [GL09](../elicitacao/tecnicas/glossario.md#GL09)           |
| <a id="RF08"></a>RF08     | Verificar se procedimentos estão na TABGDFSAÚDE, atendem às DUT, estão sujeitos a carência ou são excluídos, exigindo solicitação médica e análise técnica para autorizações prévias. | [GL02](../elicitacao/tecnicas/glossario.md#GL02), [GL03](../elicitacao/tecnicas/glossario.md#GL03), [GL05](../elicitacao/tecnicas/gloss