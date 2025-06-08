Este documento apresenta a execução da rastreabilidade forward-from no nosso projeto de estudo do aplicativo GDF Saúde, uma prática fundamental na engenharia de requisitos. A rastreabilidade forward-from estabelece ligações  entre os requisitos elicitados com os artefatos de desenho e implementação do sistema, garantindo que cada funcionalidade especificada seja devidamente desenvolvida e rastreada. Esse método contribui para o controle de qualidade e facilita a verificação do cumprimento dos requisitos 


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
            </tr>
            <tr>
                <td><a href="https://github.com/kalebmacedo">Kaleb Macedo</a></td>
            </tr>
            <tr>
                <td><a href="https://github.com/isaqzin">Isaque Camargos</a></td>
                <td>Iniciou o documento colocando a tabela com todos os requisitos e fez o backward from <a href="#FF15">FF15</a> a <a href="#FF21">FF21</a>, <a href="#FF58">FF58</a> e <a href="#FF59">FF59</a> e os elos de mesmo intervalo, <a href="#ELO15">ELO15</a> a <a href="#ELO21">ELO21</a>, <a href="#ELO58">ELO58</a> e <a href="#ELO59">ELO59</a> </td>
            </tr>
            <tr>
                <td><a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></td>
                <td>Realizou a rastreabilidade backward-from <a href="#FF22">FF22</a> a <a href="#FF28">FF27</a>, <a href="#FF60">FF60</a>, <a href="FF61">FF61</a> e <a href="#FF68">FF68</a>. Além dos ELOS do mesmo intervalo, <a href="#ELO22">ELO22</a> a <a href="#ELO28">ELO28</a>, <a href="#ELO60">ELO60</a>, <a href="#ELO61">ELO61</a> e <a href="#ELO68">ELO68</a></td>
            </tr>
            <tr>
                <td><a href="https://github.com/bolzanMGB">Othavio Bolzan</a></td>  
            </tr>
            <tr>
                <td><a href="https://github.com/redjsun">Yzabella Miranda</a></td>   
            </tr>
            <tr>
                <td><a href="https://github.com/LucasAlves71">Lucas Alves</a></td>
            </tr>
        </tbody>
    </table>
</div>

<p  align="center">Fonte: Autoria de <a  href="https://github.com/isaqzin">Isaque Camargos</a>, <a  href="https://github.com/isaqzin">Yzabella Miranda</a>, <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a>, <a href="https://github.com/kalebmacedo">Kaleb Macedo</a> e <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

## Legenda das Tabelas:

- RFx: Requisito Funcional número x;
- RNFx: Requisito Não Funcional número x;
- USx: História de usuário número x;
- CEx: Cenário número x;
- UCx: Casos de Uso número x;
- LEx: Léxico número x;
- EPx: Épico número x;
- ELOx: Eelo número x;
- FFx: Forward from número x;



|**ID**|**Requisito Original**| **Requisito Final**  | **Descrição**   |  **Implementado** |**Elo**| **Casos de uso** | **Cenários** | **Léxicos**| **Histórias de usuário** | **Backlog** | **Protótipo** |
| ------- | --- | ----| --- |---|---|---|---|---|---|---|---|
|<a id="FF01"></a>FF01 | [RF01](../elicitacao/elicitacao.md#RF01) | [RF01.1](../elicitacao/requisitos_finais.md#RF01.1) | O usuário poderá pesquisar redes credenciadas por meio de filtros de busca.| Sim              | ELO | CASO USO | CENARIO | LEXICO | HISTORIA | BACKLOG |  | 
| <a id="FF02"></a>FF02 | [RF01](../elicitacao/elicitacao.md#RF01) | [RF01.2](../elicitacao/requisitos_finais.md#RF01.2) | O usuário poderá pesquisar profissionais da saúde (médicos, psicólogos etc.) por meio de filtros de busca.| Não              | ELO | CASO USO | CENARIO | LEXICO | HISTORIA | BACKLOG |  |
| <a id="FF03"></a>FF03 | [RF01](../elicitacao/elicitacao.md#RF01) | [RF01.3](../elicitacao/requisitos_finais.md#RF01.3) | Será possível combinar filtros de pesquisa (por ex. “região administrativa + especialidade”).| Sim              | ELO | CASO USO | CENARIO | LEXICO | HISTORIA | BACKLOG |  |
| <a id="FF04"></a>FF04 | [RF01](../elicitacao/elicitacao.md#RF01) | [RF01.4](../elicitacao/requisitos_finais.md#RF01.4) | O filtro de pesquisa deve permitir buscas por proximidade do usuário (distância em até 10 km).| Não              | ELO | CASO USO | CENARIO | LEXICO | HISTORIA | BACKLOG |  |
| <a id="FF05"></a>FF05 | [RF01](../elicitacao/elicitacao.md#RF01) | [RF01.6](../elicitacao/requisitos_finais.md#RF01.6) | O Filtro permite busca pela especialidade médica   | Sim | ELO | CASO USO | CENARIO | LEXICO | HISTORIA | BACKLOG |  |
| <a id="FF06"></a>FF06 | [RF02](../elicitacao/elicitacao.md#RF02) | [RF02.1](../elicitacao/requisitos_finais.md#RF02.1) | O usuário poderá avaliar atendimentos com nota na escala Likert de 0 a 5.   |  Não       | ELO | CASO USO | CENARIO | LEXICO | HISTORIA | BACKLOG |  |
| <a id="FF07"></a>FF07 | [RF02](../elicitacao/elicitacao.md#RF02) | [RF02.2](../elicitacao/requisitos_finais.md#RF02.2) | O usuário poderá deixar e/ou ler comentários sobre atendimentos em clínicas ou com profissionais específicos.    | Não     | ELO | CASO USO | CENARIO | LEXICO | HISTORIA | BACKLOG |  |
| <a id="FF08"></a>FF08 || <a id="RF02.3"></a>RF02.3 | O sistema classificará comentários como “relevantes” ou “não relevantes” automaticamente com base em palavras-chave e upvotes de outros usuários.|  Não    | ELO | CASO USO | CENARIO | LEXICO | HISTORIA | BACKLOG |  |
| <a id="FF09"></a>FF09 || <a id="RF02.4"></a>RF02.4 | O sistema ordenará clínicas por nota média de atendimento, do maior para o menor.         |  Não              ||
| <a id="FF10"></a>FF10 || <a id="RF03"></a>RF03     | Exibir carteirinha digital mesmo sem conexão (modo offline) e permitir acesso rápido e estável.  |  Sim              ||
| <a id="FF11"></a>FF11 |[RF04](../elicitacao/elicitacao.md#RF04)| <a id="RF04.1"></a>RF04.1 | Enviar notificações configuráveis via app, SMS ou e-mail sobre vencimento de fatura       | Não||[UC10](../modelagem/metodos_tradicionais/casos_de_usos.md#UC10) e [UC11](../modelagem/metodos_tradicionais/casos_de_usos.md#UC11)|[CE04](../modelagem/metodos_tradicionais/cenarios.md#CE04)|[LE02](../modelagem/metodos_tradicionais/lexicos.md#Notificacoes) |
| <a id="FF12"></a>FF12 |[RF04](../elicitacao/elicitacao.md#RF04)| <a id="RF04.2"></a>RF04.2 | Enviar notificações configuráveis via app, SMS ou e-mail retornos médicos pendentes        | Não||[UC10](../modelagem/metodos_tradicionais/casos_de_usos.md#UC10) e [UC11](../modelagem/metodos_tradicionais/casos_de_usos.md#UC11)|[CE04](../modelagem/metodos_tradicionais/cenarios.md#CE04)|[LE02](../modelagem/metodos_tradicionais/lexicos.md#Notificacoes) |
| <a id="FF13"></a>FF13 |[RF04](../elicitacao/elicitacao.md#RF04)| <a id="RF04.3"></a>RF04.3 | Enviar notificações configuráveis via app, SMS ou e-mail sobre, abertura de agenda    |  Não||[UC10](../modelagem/metodos_tradicionais/casos_de_usos.md#UC10) e [UC11](../modelagem/metodos_tradicionais/casos_de_usos.md#UC11)|[CE04](../modelagem/metodos_tradicionais/cenarios.md#CE04)|[LE02](../modelagem/metodos_tradicionais/lexicos.md#Notificacoes) |
| <a id="FF14"></a>FF14 |[RF04](../elicitacao/elicitacao.md#RF04)| <a id="RF04.4"></a>RF04.4 | Enviar notificações configuráveis via app, SMS ou e-mail sobre cancelamentos de horários|Não||[UC10](../modelagem/metodos_tradicionais/casos_de_usos.md#UC10) e [UC11](../modelagem/metodos_tradicionais/casos_de_usos.md#UC11)|[CE04](../modelagem/metodos_tradicionais/cenarios.md#CE04)|[LE02](../modelagem/metodos_tradicionais/lexicos.md#Notificacoes) |
|<a id="FF15"></a>FF15|[RF04](../elicitacao/elicitacao.md#RF04)| [RF04.5](../elicitacao/requisitos_finais.md#RF04.5) | Enviar notificações configuráveis via app, SMS ou e-mail sobre horários favoritos disponíveis| Não|[ELO15](#ELO15)|[UC10](../modelagem/metodos_tradicionais/casos_de_usos.md#UC10) e [UC11](../modelagem/metodos_tradicionais/casos_de_usos.md#UC11)|[CE04](../modelagem/metodos_tradicionais/cenarios.md#CE04)|[LE02](../modelagem/metodos_tradicionais/lexicos.md#Notificacoes) |[US11](../modelagem/metodos_ageis/historias_todos02.md#US11)|<a href="../backlog#EP08">EP08</a>|
|<a id="FF16"></a>FF16|[RF04](../elicitacao/elicitacao.md#RF04)| [RF04.6](../elicitacao/requisitos_finais.md#RF04.6) | Enviar notificações configuráveis via app, SMS ou e-mail sobre prazos importantes relacionados a consultas e exames.|Não|[ELO16](#ELO16)|[UC10](../modelagem/metodos_tradicionais/casos_de_usos.md#UC10) e [UC11](../modelagem/metodos_tradicionais/casos_de_usos.md#UC11)|[CE04](../modelagem/metodos_tradicionais/cenarios.md#CE04)|[LE02](../modelagem/metodos_tradicionais/lexicos.md#Notificacoes) [LE04](../modelagem/metodos_tradicionais/lexicos.md#consulta) [LE24](../modelagem/metodos_tradicionais/lexicos.md#consulta_agendada) |[US12](../modelagem/metodos_ageis/historias_todos02.md#US12)|<a href="../backlog#EP07">EP07</a>|
|<a id="FF17"></a>FF17|[RF04](../elicitacao/elicitacao.md#RF04)| [RF04.7](../elicitacao/requisitos_finais.md#RF04.7) | Enviar notificações configuráveis via app, SMS ou e-mail sobre confirmações de agendamentos| Não|[ELO17](#ELO17)|[UC10](../modelagem/metodos_tradicionais/casos_de_usos.md#UC10) e [UC11](../modelagem/metodos_tradicionais/casos_de_usos.md#UC11)|[CE04](../modelagem/metodos_tradicionais/cenarios.md#CE04)|[LE02](../modelagem/metodos_tradicionais/lexicos.md#Notificacoes) [LE07](../modelagem/metodos_tradicionais/lexicos.md#agendar)  [LE09](../modelagem/metodos_tradicionais/lexicos.md#agendamento) [LE24](../modelagem/metodos_tradicionais/lexicos.md#consulta_agendada) |[US13](../modelagem/metodos_ageis/historias_todos02.md#US13)|<a href="../backlog#EP08">EP08</a>|
|<a id="FF18"></a>FF18|[RF04](../elicitacao/elicitacao.md#RF04)| [RF04.8](../elicitacao/requisitos_finais.md#RF04.8) | Enviar notificações configuráveis via app, SMS ou e-mail sobre alterações de agendamento| Não|[ELO18](#ELO18)|[UC10](../modelagem/metodos_tradicionais/casos_de_usos.md#UC10) e [UC11](../modelagem/metodos_tradicionais/casos_de_usos.md#UC11)|[CE04](../modelagem/metodos_tradicionais/cenarios.md#CE04)|[LE02](../modelagem/metodos_tradicionais/lexicos.md#Notificacoes) [LE08](../modelagem/metodos_tradicionais/lexicos.md#cancelar) [LE09](../modelagem/metodos_tradicionais/lexicos.md#agendamento) [LE24](../modelagem/metodos_tradicionais/lexicos.md#consulta_agendada)|[US14](../modelagem/metodos_ageis/historias_todos02.md#US14)|<a href="../backlog#EP08">EP08</a>|
|<a id="FF19"></a>FF19|[RF04](../elicitacao/elicitacao.md#RF04)| [RF04.9](../elicitacao/requisitos_finais.md#RF04.9) | Enviar notificações configuráveis via app, SMS ou e-mail sobre disponibilidade de demonstrativos de IR       | Não|[ELO19](#ELO19)|[UC10](../modelagem/metodos_tradicionais/casos_de_usos.md#UC10) e [UC11](../modelagem/metodos_tradicionais/casos_de_usos.md#UC11)|[CE04](../modelagem/metodos_tradicionais/cenarios.md#CE04)|[LE02](../modelagem/metodos_tradicionais/lexicos.md#Notificacoes) |[US15](../modelagem/metodos_ageis/historias_todos02.md#US15)|<a href="../backlog#EP07">EP07</a>|
|<a id="FF20"></a>FF20|[RF05](../elicitacao/elicitacao.md#RF05)| [RF05.1](../elicitacao/requisitos_finais.md#RF05.1) | Permitir agendamento de consultas e exames diretamente pelo aplicativo, com pagamento automático para prestadores da Rede de Atendimento.|  Não|[ELO20](#ELO20)|[UC13](../modelagem/metodos_tradicionais/casos_de_usos.md#UC13)|[CE05](../modelagem/metodos_tradicionais/cenarios.md#CE05)|[LE04](../modelagem/metodos_tradicionais/lexicos.md#consulta) [LE05](../modelagem/metodos_tradicionais/lexicos.md#exame) [LE07](../modelagem/metodos_tradicionais/lexicos.md#agendar) [LE14](../modelagem/metodos_tradicionais/lexicos.md#prestador)|[US16](../modelagem/metodos_ageis/historias_todos02.md#US16)|<a href="../backlog#EP09">EP09</a>|
|<a id="FF21"></a>FF21|[RF05](../elicitacao/elicitacao.md#RF05)| [RF05.2](../elicitacao/requisitos_finais.md#RF05.2) | Permitir cancelamento de consultas e exames diretamente pelo aplicativo, com pagamento automático para prestadores da Rede de Atendimento.|  Não|[ELO21](#ELO21)|[UC14](../modelagem/metodos_tradicionais/casos_de_usos.md#UC14)|[CE05](../modelagem/metodos_tradicionais/cenarios.md#CE05)|[LE04](../modelagem/metodos_tradicionais/lexicos.md#consulta) [LE05](../modelagem/metodos_tradicionais/lexicos.md#exame) [LE08](../modelagem/metodos_tradicionais/lexicos.md#cancelar) [LE14](../modelagem/metodos_tradicionais/lexicos.md#prestador)|[US18](../modelagem/metodos_ageis/historias_todos02.md#US18)|<a href="../backlog#EP09">EP09</a>|
|<a id="FF22"></a>FF22|[RF06](../elicitacao/elicitacao.md#RF06) | [RF06.1](../elicitacao/requisitos_finais.md#RF06.1) | Exibir valor específico de consulta em cada clínica.    | [EN08](../elicitacao/tecnicas/entrevista.md#EN08), [GL04](../elicitacao/tecnicas/glossario.md#GL04), [IS10](../elicitacao/tecnicas/introspeccao.md#IS10), [IS11](../elicitacao/tecnicas/introspeccao.md#IS11), [QT02](../elicitacao/tecnicas/questionario.md#QT02), [QT05](../elicitacao/tecnicas/questionario.md#QT05) | Sim              ||
|<a id="FF23"></a>FF23| [RF06](../elicitacao/elicitacao.md#RF06) | [RF06.2](../elicitacao/requisitos_finais.md#RF06.2) | O sistema deve calcular e exibir o valor da coparticipação do beneficiário para cada consulta e procedimento médico realizado que esteja sujeito a este regime. | [EN08](../elicitacao/tecnicas/entrevista.md#EN08), [GL04](../elicitacao/tecnicas/glossario.md#GL04), [IS10](../elicitacao/tecnicas/introspeccao.md#IS10), [IS11](../elicitacao/tecnicas/introspeccao.md#IS11), [QT02](../elicitacao/tecnicas/questionario.md#QT02), [QT05](../elicitacao/tecnicas/questionario.md#QT05) | Sim              |
|<a id="FF24"></a>FF24| [RF06](../elicitacao/elicitacao.md#RF06) | [RF06.3](../elicitacao/requisitos_finais.md#RF06.3) | Gerar e baixar demonstrativos de despesas médicas para imposto de renda.  | [EN08](../elicitacao/tecnicas/entrevista.md#EN08), [GL04](../elicitacao/tecnicas/glossario.md#GL04), [IS10](../elicitacao/tecnicas/introspeccao.md#IS10), [IS11](../elicitacao/tecnicas/introspeccao.md#IS11), [QT02](../elicitacao/tecnicas/questionario.md#QT02), [QT05](../elicitacao/tecnicas/questionario.md#QT05) | Sim              ||
|<a id="FF25"></a>FF25| [RF06](../elicitacao/elicitacao.md#RF06) | [RF06.4](../elicitacao/requisitos_finais.md#RF06.4) | Consultar histórico de demonstrativos de IR.    | [EN08](../elicitacao/tecnicas/entrevista.md#EN08), [GL04](../elicitacao/tecnicas/glossario.md#GL04), [IS10](../elicitacao/tecnicas/introspeccao.md#IS10), [IS11](../elicitacao/tecnicas/introspeccao.md#IS11), [QT02](../elicitacao/tecnicas/questionario.md#QT02), [QT05](../elicitacao/tecnicas/questionario.md#QT05) | Sim              ||
|<a id="FF26"></a>FF26| [RF06](../elicitacao/elicitacao.md#RF06) | [RF06.5](../elicitacao/requisitos_finais.md#RF06.5) | Mostrar extrato financeiro atualizado diariamente.   | [EN08](../elicitacao/tecnicas/entrevista.md#EN08), [GL04](../elicitacao/tecnicas/glossario.md#GL04), [IS10](../elicitacao/tecnicas/introspeccao.md#IS10), [IS11](../elicitacao/tecnicas/introspeccao.md#IS11), [QT02](../elicitacao/tecnicas/questionario.md#QT02), [QT05](../elicitacao/tecnicas/questionario.md#QT05) | Sim              ||
|<a id="FF27"></a>FF27| [RF07](../elicitacao/elicitacao.md#RF07) | [RF07.1](../elicitacao/requisitos_finais.md#RF07.1) | O sistema deve permitir o cadastro de titulares.             | [GL01](../elicitacao/tecnicas/glossario.md#GL01), [GL08](../elicitacao/tecnicas/glossario.md#GL08), [GL09](../elicitacao/tecnicas/glossario.md#GL09)           | Sim              ||
| <a id="FF28"></a>FF28 || <a id="RF07.2"></a>RF07.2 | O sistema deve permitir o cadastro de dependentes vinculados a um titular| Sim              ||
| <a id="FF29"></a>FF29 || <a id="RF07.3"></a>RF07.3 | O sistema deve permitir o cadastro de optantes.|  Sim              ||
| <a id="FF30"></a>FF30 || <a id="RF07.4"></a>RF07.4 | O sistema deve validar os documentos apresentados durante o cadastro.|  Sim              ||
| <a id="FF31"></a>FF31 || <a id="RF07.5"></a>RF07.5 | O sistema deve verificar a elegibilidade dos titulares, dependentes e optantes durante o processo de cadastro.| Sim              ||
| <a id="FF32"></a>FF32 || <a id="RF08.1"></a>RF08.1 | Verificar se procedimentos estão na TABGDFSAÚDE, atendem às DUT, estão sujeitos a carência ou são excluídos, exigindo solicitação médica e análise técnica para autorizações prévias.| Sim| |
| <a id="FF33"></a>FF33 || <a id="RF09.1"></a>RF09.1 | Permitir ao usuário visualizar o histórico de consultas realizadas.|  Não              ||
| <a id="FF34"></a>FF34 || <a id="RF09.2"></a>RF09.2 | Permitir ao usuário visualizar o histórico de exames realizados.|  Não              ||
| <a id="FF35"></a>FF35 || <a id="RF09.3"></a>RF09.3 | Permitir ao usuário visualizar os resultados de seus exames laboratoriais.| Não              ||
| <a id="FF36"></a>FF36 | [RF09](../elicitacao/elicitacao.md#RF09) | [RF09.4](../elicitacao/requisitos_finais.md#RF09.4) | Permitir ao usuário visualizar o histórico de suas coparticipações.| Não| ELO | CASO USO | CENARIO | LEXICO | HISTORIA | BACKLOG |  |
| <a id="FF37"></a>FF37 | [RF10](../elicitacao/elicitacao.md#RF10) | [RF10](../elicitacao/requisitos_finais.md#RF10) | Permitir que o usuário favorite horários de consulta desejados.|  Não              | ELO | CASO USO | CENARIO | LEXICO | HISTORIA | BACKLOG |  |
| <a id="FF38"></a>FF38 | [RF11](../elicitacao/elicitacao.md#RF11) | [RF11](../elicitacao/requisitos_finais.md#RF11) | Oferecer um canal para o usuário enviar feedback sobre atendimentos.| Não              | ELO | CASO USO | CENARIO | LEXICO | HISTORIA | BACKLOG |  |
| <a id="FF39"></a>FF39 | [RF12](../elicitacao/elicitacao.md#RF12) | [RF12.1](../elicitacao/requisitos_finais.md#RF12.1) | Apesentar uma seção no menu principal chamada "Novidades".| Não | ELO | CASO USO | CENARIO | LEXICO | HISTORIA | BACKLOG |  |
| <a id="FF40"></a>FF40 | [RF12](../elicitacao/elicitacao.md#RF12) | [RF12.2](../elicitacao/requisitos_finais.md#RF12.2) | Exibir uma lista com título, descrição e data de lançamento das novas funcionalidades.| Não | ELO | CASO USO | CENARIO | LEXICO | HISTORIA | BACKLOG |  |
| <a id="FF41"></a>FF41 | [RF12](../elicitacao/elicitacao.md#RF12) | [RF12.3](../elicitacao/requisitos_finais.md#RF12.3) | Destacar funcionalidades novas com um marcador de "Novo" por um período configurável (ex: 7 dias).|  Não              | ELO | CASO USO | CENARIO | LEXICO | HISTORIA | BACKLOG |  |
| <a id="FF42"></a>FF42 || <a id="RF12.4"></a>RF12.4 |Exibir pop-ups informativos com as principais novidades após a atualização do aplicativo.|  Não||
| <a id="FF45"></a>FF45 || <a id="12.5"></a>RF12.5 | Permitir que o usuário toque em uma funcionalidade da lista de novidades para ver uma descrição detalhada.|  Não||
| <a id="FF46"></a>FF46 || <a id="RF12.6"></a>RF12.6 |Permitir que o usuário ordene as novidades por "mais recente" e "mais antigo" no topo da lista.| Não| |
| <a id="FF47"></a>FF47 || <a id="RF13"></a>RF13     | Adicionar consulta à rede odontológica.| Sim| |
| <a id="FF48"></a>FF48 || <a id="RF14.1"></a>RF14.1     | Apresentar novas clínicas próximas de acordo com a localização do usuário.| Não||
| <a id="FF49"></a>FF49 || <a id="RF14.2"></a>RF14.2     | Apresentarclí nicas próximas de acordo com a localização do usuário.|  Não|| 
| <a id="FF50"></a>FF50 || <a id="RF15"></a>RF15     | Permitir baixar comprovantes de agendamento.| Não||
| <a id="FF51"></a>FF51 ||  <a id="RF16"></a>RF16     | Disponibilizar calendário personalizado com visualização de consultas agendadas, prazos de carência e vencimentos.| Não | |
| <a id="FF52"></a>FF52 || <a id="RF17"></a>RF17     | Exibir painel com metas de saúde personalizadas (ex: exames periódicos, consultas anuais) com gamificação para incentivar acompanhamento.| Não||
| <a id="FF53"></a>FF53 || <a id="RF18.1"></a>RF18.1 | Permitir denúncias de condutas inadequadas por parte de profissionais da rede credenciada.|  Não | |
| <a id="FF54"></a>FF54 || <a id="RF19"></a>RF19     | Permitir login por biometria facial ou digital.|  Não||
| <a id="FF55"></a>FF55 || <a id="RF20"></a>RF20     | Permitir solicitação de reembolso de uma cobrança indevida de coparticipação.| Não||
| <a id="FF56"></a>FF56 || <a id="RF21.1"></a>RF21.1 | Chatbot conversacional que direciona o usuário à especialidade médica adequada, com precisão de pelo menos 80 % nas recomendações.|  Não              ||

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>

## Requisitos Não Funcionais Refinados

Na tabela 3 encontra-se a rastreabilidade Forward from dos requisitos não funcionais.

<p align="center">Tabela 3: Requisitos Não Funcionais</p>

|**ID**|**Requisito Original**| **Requisito Final**  | **Descrição**   | **Implementado** |**Elo**|**Léxicos**|**Especificação Suplementar**| **NFR**|
| ---------------- | ----------- | --------------------- | ---------------- |---|---|---|---|---|
| <a id="FF57"></a>FF57 | [RNF01](../elicitacao/elicitacao.md#RNF01) | [RNF01.1](../elicitacao/requisitos_finais.md#RNF01.1) | A interface deve ser responsiva para dispositivos Android 5.0 ou superiores e iOS 13.0 ou superiores.                               | Não              | cc|
| <a id="FF57"></a>FF57 | [RNF02](../elicitacao/elicitacao.md#RNF02)  | [RNF02.1](../elicitacao/requisitos_finais.md#RNF02.1) | 95 % das ações devem ter tempo de resposta ≤ 2 segundos, medido em ambiente com até 100 usuários simultâneos.                       | Não              ||
| <a id="FF58"></a>FF58 || <a id="RNF03.1"></a>RNF03.1 | Todos os dados sensíveis em repouso devem ser criptografados com ao menos um recurso de criptografia.                               |  Sim              ||
| <a id="FF59"></a>FF59 || <a id="RNF03.2"></a>RNF03.2 | Autenticação de dois fatores deve estar disponível via SMS ou app de autenticação externa.| Não              ||
|<a id="FF60"></a>FF60|[RNF04](../elicitacao/elicitacao.md#RNF04)| [RNF04](../elicitacao/requisitos_finais.md#RNF04)     | Manter o sistema disponível 24/7 para autorizações de urgência/emergência e apresentar alta disponibilidade (mínimo de 99% uptime). |Sim              |[ELO58](#ELO58)|-|[Confiabilidade](../modelagem/metodos_tradicionais/especificacao-suplementar.md#RNF05)|-|
|<a id="FF61"></a>FF61|[RNF05](../elicitacao/elicitacao.md#RNF05)| [RNF05](../elicitacao/requisitos_finais.md#RNF05)     | O sistema deve ser compatível com as versões 5.0 ou superioresdo Android e 13.0 ou superiores do iOS.            | Sim              |[ELO59](#ELO58)|-|[Suportabilidade](../modelagem/metodos_tradicionais/especificacao-suplementar.md#RNF05)|-|
| <a id="FF62"></a>FF62 || <a id="RNF06"></a>RNF06     | O aplicativo deve ser compatível com leitores de tela para garantir acessibilidade a pessoas com deficiência visual.| Não||
| <a id="FF63"></a>FF63 || <a id="RNF07"></a>RNF07     | Garantir conformidade com a Portaria nº 127/2024, legislações complementares e padrões da LGPD.              |  Sim              ||
| <a id="FF64"></a>FF64 || <a id="RNF08"></a>RNF08     | Processar autorizações prévias em até 10 dias úteis.|Sim              ||
| <a id="FF65"></a>FF65 || <a id="RNF09"></a>RNF09    | Comunicar-se com a folha de pagamento do GDF para descontos de mensalidades.| Sim              ||
| <a id="FF66"></a>FF66 | [RNF10](../elicitacao/elicitacao.md#RNF10) | [RNF10](../elicitacao/requisitos_finais.md#RNF10)    | Garantir que informações críticas, como a carteirinha digital, estejam acessíveis em até três cliques ou com no máximo 2 cliques a partir da tela inicial. | Sim              ||
| <a id="FF67"></a>FF67 | [RNF11](../elicitacao/elicitacao.md#RNF11) | [RNF11](../elicitacao/requisitos_finais.md#RNF11)     | Manter histórico de notificações acessível ao usuário por no mínimo 6 meses.| Não              ||
| <a id="FF68"></a>FF68 || <a id="RNF12"></a>RNF12     | O aplicativo deve oferecer suporte por chat ou telefone.    | Sim              ||
| <a id="FF69"></a>FF69 || <a id="RNF13"></a>RNF13    | Deve funcionar de forma offline para acesso à carteirinha e histórico de consultas.                               |  Não              ||
| <a id="FF70"></a>FF70 || <a id="RNF14"></a>RNF14    | O layout deve ser consistente com o portal oficial do plano.                                                      |  Não              |
| <a id="FF71"></a>FF71 || <a id="RNF15"></a>RNF15    | O sistema deve exigir autenticação via GovBR para login.| Não              ||
| <a id="FF72"></a>FF72 || <a id="RNF16"></a>RNF16    | As informações exibidas devem ser claras, completas e atualizadas em tempo real.                                  |  Sim ||

<p align="center">Fonte: Autoria de <a href="https://github.com/isaqzin">Isaque Camargos</a></p>


## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |  08/06/2025 |  Iniciou o documento colocando a tabela com todos os requisitos e fez o backward from <a href="#FF15">FF15</a> a <a href="#FF21">FF21</a>, <a href="#FF58">FF58</a> e <a href="#FF59">FF59</a> e os elos de mesmo intervalo, <a href="#ELO15">ELO15</a> a <a href="#ELO21">ELO21</a>, <a href="#ELO58">ELO58</a> e <a href="#ELO59">ELO59</a>| [Isaque Camargos](https://github.com/isaqzin)  | [Ana Luiza](https://github.com/Ana-Luiza-SC) |

