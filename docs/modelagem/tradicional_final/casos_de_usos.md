# Diagrama e Especificação de Casos de Uso

## Introdução 

Um caso de uso é uma representação detalhada de como os usuários do aplicativo GDF Saúde interagem com o sistema em situações específicas, como acessar a carteirinha, enviar feedback ou visualizar novas funcionalidades. Ele descreve passo a passo como essas interações ocorrem, desde a ação do usuário até a resposta do sistema.

Seu principal objetivo é apoiar o desenvolvimento do aplicativo, oferecendo uma visão clara e prática dos requisitos funcionais. Os casos de uso ajudam a definir o comportamento esperado do sistema diante de ações comuns dos usuários, contribuindo para garantir que as funcionalidades atendam às necessidades reais dos beneficiários do plano de saúde.

É importante notar que esses casos de uso foram **refatorados** para maior clareza e precisão, além de corresponderem com os requisitos finais que foram refinados. Você pode acessar a versão antiga clicando [aqui](../../metodos_tradicionais/casos_de_usos).

## Integrantes do Grupo

Na tabela 1 contêm todos os integrantes da equipe que participaram na construção dos cenários e o que a pessoa desenvolveu durante o projeto.

<p  align="center">Tabela 1 - Integrantes do grupo envolvidos</p>
<div align="center">
<div>
	<table>
		<thead>
				<tr>
					<th>Nome</th>
					<th>Quais etapas participou</th>
				</tr>
		</thead>
	<tbody>
				<tr>
					<td><a  href="https://github.com/Ana-Luiza-SC"">Ana Luiza Soares</a></td>
					<td>Criou o diagrama  e especificações dos casos de uso referentes aos requisitos: RF01.1, RF01.2, RF01.3, RF01.4, RF01.5, RF02.1, RF02.2, RF02.3 e RF21.</0td>	
				</tr>
				<tr>
					<td><a  href="https://github.com/isaqzin">Isaque Camargos</a></td>
					<td>Criou o diagrama referentes aos requisitos: RF03,RF04, RF19, RNF04,  RNF05 e  RNF06 . Criou as especificações dos casos de uso referente a estes requisitos, sendo eles  UC07, UC08, UC09,  UC10, UC11 e UC12. Além disso, criou o documento inicial. </td>	
				</tr>
				<tr>
					<td><a  href="https://github.com/kalebmacedo">Kaleb Macedo</a></td>
					<td>Criou o diagrama referentes aos requisitos: RF05, RF06, RF17 RNF07 e RNF08 . Criou as especificações dos casos de uso referente a estes requisitos, sendo eles  UC13, UC14, UC15,  UC16, UC17, UC18, UC19 e UC20. </td>	
				</tr>
				<tr>
					<td><a  href="https://github.com/LucasAlves71">Lucas Alves</a></td>
					<td>Criou o diagrama referentes aos requisitos: RF07,RF08, RNF09, RNF10 e RF18 . Criou as especificações dos casos de uso referente a estes requisitos, sendo eles  UC21, UC22, UC23,  UC24, UC25 e UC26. </td>	
				</tr>
				<tr>
					<td><a  href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></td>
					<td>Criou o diagrama referentes aos requisitos: RF09, RF10, RF20 RNF11 e RNF12. Criou as especificações dos casos de uso referente a estes requisitos, sendo eles  UC27, UC28, UC29,  UC30 e UC31. </td>	
				</tr>
				<tr>
					<td><a  href="https://github.com/bolzanMGB">Othavio Bolzan</a></td>
					<td>Criou o diagrama referentes aos requisitos: RF11,RF12, RNF13 e RNF14 . Criou as especificações dos casos de uso referente a estes requisitos, sendo eles UC32, UC33 e UC034. </td>	
				</tr>
				<tr>
					<td><a  href="https://github.com/redjsun">Yzabella Miranda</a></td>
					<td>Criou o diagrama referentes aos requisitos: RNF15,RF13, RF14 e RF15 . Criou as especificações dos casos de uso referente a estes requisitos, sendo eles  UC35, UC36, UC37 e UC38. </td>	
				</tr>
		</tbody>
	</table>
</div>
</div> 

<p  align="center">Fonte: Autoria de <a  href="https://github.com/isaqzin">Isaque Camargos</a> e <a  href="https://github.com/isaqzin">Yzabella Miranda</a></p>


## Metodologia 


Para mapear e compreender melhor o funcionamento do aplicativo GDF Saúde, utilizamos o diagrama de caso de uso — uma ferramenta da Engenharia de Requisitos que representa visualmente como os usuários interagem com o sistema. Esse diagrama descreve, por meio de "atores" (como beneficiários do plano) e "casos de uso" (como acessar a carteirinha ou enviar feedback), as funcionalidades oferecidas e os comportamentos esperados do sistema.

No desenvolvimento do diagrama, empregamos dois relacionamentos fundamentais: o include e o extend. O relacionamento include é usado quando uma funcionalidade sempre faz parte de outra, como, por exemplo, o caso “Acessar Aplicativo” incluir automaticamente os casos “Consultar histórico de consultas” e “Acessar carteirinha”. Já o relacionamento extend representa funcionalidades opcionais ou condicionais, que se aplicam em determinados contextos — como o caso “Modo Offline”, que estende o acesso ao histórico e à carteirinha somente quando não há conexão com a internet.

Com foco nos diagramas de caso de uso, a Tabela 2 apresenta os principais elementos que compõem o modelo, oferecendo uma visão clara e organizada da estrutura de interações entre os atores e o sistema.

### Elementos de caso de uso

<p  align="center">Tabela 2: legenda dos diagramas de caso de uso</p>

|Nome|         Função         |      Elemento      |
|----|------------------------|--------------------|
| Ator |Representam os diversos tipos de usuários externos que interagem com o sistema. | <div><img src="..\..\assets\casos-uso\casos-uso-ator.png" alt="Referência do item" width="100px"><br></div> |
| Elipse (Caso de Uso) | É utilizada para representar os casos de uso em um diagrama, destacando funcionalidades ou ações específicas que o sistema realiza em resposta às interações dos atores. | <div><img src="..\..\assets\casos-uso\casos-uso-elipse.png" alt="Referência do item" width="100px"><br></div> |
|Retângulo (Sistema)| É utilizado para representar o sistema ou o componente em análise, agrupando os casos de uso e os atores associados a ele. | <div><img src="..\..\assets\casos-uso\casos-uso-retangulo.png" alt="Referência do item" width="100px"><br></div> |
| Flecha (Relações) | As setas são utilizadas para ilustrar as relações ou interações entre os atores e os casos de uso no diagrama. | <div><img src="..\..\assets\casos-uso\casos-uso-relacionamento.png" alt="Referência do item" width="100px"><br></div> |


<p  align="center">Fonte: Autoria de <a  href="https://github.com/isaqzin">Yzabella Miranda</a></p>

## Diagramas de caso de uso
As figuras 1 a 7 representam as especializações dos casos de uso.

<p align="center">Figura 1 - Caso de uso UC01 a UC03 </p>
<p align="center">
  <img src="..\..\assets\casos-uso\casos-uso-ana-novo.png" width="600">
</p>

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC" target="_blank">Ana Luiza Soares</a></p>


<p align="center">Figura 2 - Caso de uso UC07 a UC12 </p>
<p align="center">
  <img src="..\..\assets\casos-uso\casos-uso-isaque.jpg" alt="Heatmap de disponibilidade da equipe" width="600">
</p>

<p align="center">Fonte: Autoria de <a src="https://github.com/isaqzin" targe="_blank">Isaque Camargos</a></p>


<p align="center">Figura 3 - Caso de uso UC13 a UC20 </p>
<p align="center">
  <img src="..\..\assets\casos-uso\casos-uso-kaleb.jpg" alt="Heatmap de disponibilidade da equipe" width="600">
</p>

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo" target="_blank">Kaleb Macedo</a></p>


<p align="center">Figura 4 - Caso de uso UC21 a UC26 </p>
<p align="center">
  <img src="..\..\assets\casos-uso\casos-uso-lucas.jpg" alt="Heatmap de disponibilidade da equipe" width="600">
</p>

<p  align="center">Fonte: Autoria de <a  href="https://github.com/LucasAlves71" target="_blank">Lucas Alves</a></p>


<p align="center">Figura 5 - Caso de uso UC27 a UC31 </p>
<p align="center">
  <img src="..\..\assets\casos-uso\casos-uso-matheus.jpg" alt="Heatmap de disponibilidade da equipe" width="600">
</p>

<p  align="center">Fonte: Autoria de <a  href="https://github.com/matheusdealcantara" target="_blank" >Matheus de Alcântara</a></p>

<p align="center">Figura 6 - Caso de uso UC32 a UC34 </p>
<p align="center">
  <img src="..\..\assets\casos-uso\casos-uso-othavio.jpg" alt="Heatmap de disponibilidade da equipe" width="600">
</p>

<p  align="center">Fonte: Autoria de <a  href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a></p>

<p align="center">Figura 7 - Caso de uso UC35 a UC38 </p>
<p align="center">
  <img src="..\..\assets\casos-uso\casos-uso-yza.png" alt="Heatmap de disponibilidade da equipe" width="600">
</p>

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

## Especialização dos casos de uso 

### UC01 – Pesquisar Redes por Filtros

| Campo                    | Descrição                                                                                                                                                                                                                                  |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC01"></a>UC01     | Pesquisar Redes Credenciadas por Filtros|
| Descrição                | Permitir ao usuário localizar redes credenciadas aplicando filtros de busca gerais para refinar os resultados.|
| Ator                     | Usuário do aplicativo GDF Saúde|
| Pré-condições            | 1. Conexão com internet. <br>2. Usuário é beneficiário do Plano INAS e está logado.|
| Ação                     | Usuário aplica um ou mais filtros na tela de busca e inicia a pesquisa. |
| Fluxo principal          | - Usuário abre o aplicativo e acessa a aba "Rede Credenciada". <br>- Sistema exibe a interface de busca com as opções de filtro. <br>- Usuário seleciona o filtro "Região Administrativa" e escolhe uma opção. <br>- Sistema exibe os resultados que correspondem ao filtro aplicado. |
| Fluxo alternativo        | - Usuário realiza a busca sem aplicar nenhum filtro. <br>- Sistema exibe a lista completa de todas as redes credenciadas, ordenadas alfabeticamente.|
| Fluxo de exceção         | - Usuário aplica um filtro que não possui nenhuma rede correspondente. <br>- Sistema exibe a mensagem "Nenhuma rede credenciada encontrada para os critérios selecionados." |
| Pós-condições            | A lista de redes credenciadas que atende aos filtros aplicados é exibida com sucesso para o usuário.|
| Rastreabilidade          | [RF01.1](../../elicitacao/requisitos_finais.md#RF01.1)|
| Data de criação          | 12/06/2025|

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### UC02 – Pesquisar Profissionais da Saúde

<p align="center">Tabela 4 - Caso de Uso 2 </p>

| Campo                    | Descrição                                                                                                                                                                                                                                  |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC02"></a>UC02     | Pesquisar Profissionais da Saúde|
| Descrição                | Permitir ao usuário encontrar um profissional da saúde específico (médico, psicólogo, etc.) através de uma busca dedicada.|
| Ator                     | Usuário do aplicativo GDF Saúde|
| Pré-condições            | 1. Conexão com internet. <br>2. Usuário é beneficiário do Plano INAS e está logado.|
| Ação                     | Usuário insere o nome de um profissional ou seleciona uma especialidade na área de busca de profissionais.|
| Fluxo principal          | - Usuário acessa a seção "Buscar Profissional". <br>- Sistema exibe o campo de busca. <br>- Usuário digita o nome do profissional. <br>- Usuário aciona a busca. <br>- Sistema exibe o perfil detalhado do profissional encontrado.           |
| Fluxo alternativo        | - Usuário digita um nome parcial ou incompleto. <br>- Sistema exibe uma lista de profissionais cujos nomes correspondem à busca parcial para que o usuário selecione o correto.|
| Fluxo de exceção         | - A busca não retorna nenhum profissional com o nome inserido. <br>- Sistema exibe a mensagem "Nenhum profissional encontrado com os dados informados."|
| Pós-condições            | O perfil do profissional de saúde desejado é encontrado e suas informações são exibidas para o usuário.|
| Rastreabilidade          | [RF01.2](../../elicitacao/requisitos_finais.md#RF01.2)|
| Data de criação          | 12/06/2025|

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### UC03 – Iniciar conversa com chatbot de triagem

<p align="center">Tabela 5 - Caso de Uso 3 </p>

| Campo              | Descrição                                                                                                                                       |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC03"></a>UC03 | Iniciar conversa com chatbot de triagem |
| Descrição          | Permitir ao usuário interagir com chatbot para identificar especialidade médica adequada |
| Ator               | Usuário do aplicativo GDF Saúde |
| Pré-condições      | 1. Conexão com internet. <br>2. Usuário é beneficiário do Plano INAS |
| Ação               | Usuário inicia conversa e descreve sintomas |
| Fluxo principal    | - Usuário abre o aplicativo <br>- Usuário seleciona a opção "Chatbot de Saúde" <br>- Sistema exibe tela inicial do chatbot <br>- Usuário descreve sintomas <br>- Chatbot analisa e sugere especialidade médica <br>- Sistema pede confirmação ao usuário posteriormente para análise de desempenho |
| Fluxo alternativo  | - Usuário abre o aplicativo <br>- Usuário seleciona a opção "Chatbot de Saúde" <br>- Sistema exibe tela inicial do chatbot <br>- Usuário tem dúvidas ou fornece informações vagas <br>- Chatbot recomenda buscar hospital para melhor triagem |
| Fluxo de exceção   | - Usuário abre o aplicativo <br>- Usuário seleciona a opção "Chatbot de Saúde" <br>- Inicia a conversa <br>- Chatbot redireciona para especialidade médica incorreta |
| Pós-condições      | Especialidade médica identificada corretamente e confirmado o desempenho do chatbot posteriormente |
| Rastreabilidade    | [RF21](../../elicitacao/requisitos_finais.md#RF21) |
| Data de criação    | 17/05/2025 |

<p align="center">Fonte: Autoria de <a src="https://github.com/Ana-Luiza-SC" targe="_blank">Ana Luiza Soares</a></p>

---

### UC07 – Fazer login
<p align="center">Tabela 9 - Caso de Uso 7 </p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
|<a id="UC07"></a>UC07            |  Fazer login                                                        |
| Descrição          | Permitir que o usuário acesse o app com e-mail/CPF e senha.               |
| Ator               | Usuário cadastrado                                                        |
| Pré-condições      | App instalado e com conexão à internet.                                   |
| Ação               | O usuário preenche e-mail/CPF e senha e confirma para entrar.             |
| Fluxo principal    | - O usuário acessa a tela de login.<br>- Insere e-mail/CPF e senha.<br>- O sistema valida os dados.<br>- O usuário é autenticado. |
| Fluxo alternativo  | - Credenciais inválidas: sistema exibe mensagem de erro.                  |
| Fluxo de exceção   | - Ausência de conexão: sistema informa que não é possível conectar.       |
| Pós-condições      | Usuário autenticado e apto a usar o aplicativo.                           |
| Rastreabilidade    |   [RF19](../../elicitacao/requisitos_finais.md#RF19)                                                                         |
| Data de criação    | 15/05/2025                                                                |

<p align="center">Fonte: Autoria de <a src="https://github.com/isaqzin" targe="_blank">Isaque Camargos</a></p>
---

### UC08 – Login por biometria
<p align="center">Tabela 10 - Caso de Uso 8 </p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| <a id="UC08"></a>UC08                 |  Login por biometria                                                |
| Descrição          | Permitir login via impressão digital ou reconhecimento facial.            |
| Ator               | Usuário cadastrado                                                        |
| Pré-condições      | Dispositivo com sensor biométrico, usuário já logado ao menos uma vez.    |
| Ação               | O usuário seleciona "Entrar por biometria" e realiza autenticação.         |
| Fluxo principal    | - O usuário abre o app.<br>- Seleciona “Entrar com biometria”.<br>- Biometria é validada pelo sistema operacional.<br>- O usuário é autenticado. |
| Fluxo alternativo  | - Biometria não reconhecida: sistema oferece login por senha.             |
| Fluxo de exceção   | - Sensor indisponível: app informa erro e redireciona para login comum.   |
| Pós-condições      | Usuário autenticado via biometria ou direcionado para login manual.       |
| Rastreabilidade    | [RF19](../../elicitacao/requisitos_finais.md#RF19)          |
| Data de criação    | 15/05/2025                 |

---

### UC09 – Baixar carteirinha

<p align="center">Tabela 11 - Caso de Uso 9 </p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| <a id="UC09"></a>UC09                 | Baixar carteirinha                                                 |
| Descrição          | Permitir download da carteirinha digital para uso offline.                |
| Ator               | Usuário autenticado                                                       |
| Pré-condições      | Conexão com internet e usuário logado.                                    |
| Ação               | O usuário solicita o download da carteirinha.                             |
| Fluxo principal    | - O usuário acessa a seção “Carteirinha”.<br>- Clica em “Baixar”.<br>- O sistema realiza o download.<br>- A carteirinha é salva no dispositivo. |
| Fluxo alternativo  | - Caso já tenha sido baixada, o sistema permite rebaixar.                 |
| Fluxo de exceção   | - Falta de conexão ou falha no armazenamento: erro informado ao usuário.  |
| Pós-condições      | Carteirinha disponível localmente mesmo sem internet.                     |
| Rastreabilidade    |  [RF03](../../elicitacao/requisitos_finais.md#RF03)               |
| Data de criação    | 15/05/2025                                                                |

<p align="center">Fonte: Autoria de <a src="https://github.com/isaqzin" targe="_blank">Isaque Camargos</a></p>

---

### UC10 – Configurar notificações
<p align="center">Tabela 12 - Caso de Uso 10 </p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| <a id="UC10"></a>UC10                 |  Configurar notificações                                            |
| Descrição          | Permitir ao usuário selecionar tipos e canais de notificações.            |
| Ator               | Usuário autenticado                                                       |
| Pré-condições      | Login realizado com sucesso.                                              |
| Ação               | O usuário acessa as configurações de notificação e define suas preferências. |
| Fluxo principal    | - O usuário acessa “Configurações”.<br>- Escolhe os tipos e canais desejados.<br>- Salva as alterações.<br>- Preferências são persistidas pelo sistema. |
| Fluxo alternativo  | —                                                                         |
| Fluxo de exceção   | - sistema exibe erro ao tentar salvar.                      |
| Pós-condições      | Preferências de notificação atualizadas.                                  |
| Rastreabilidade    |[RF04](../../elicitacao/requisitos_finais.md#RF04)                    |
| Data de criação    | 15/05/2025                                                                |

<p align="center">Fonte: Autoria de <a src="https://github.com/isaqzin" targe="_blank">Isaque Camargos</a></p>

---

### UC11 – Enviar notificações
<p align="center">Tabela 13 - Caso de Uso 11 </p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| <a id="UC11"></a>UC11                 |  Enviar notificações                                                |
| Descrição          | Enviar notificações com base nas preferências do usuário.                 |
| Ator               | Serviços de notificação                                 |
| Pré-condições      | Configurações de notificação existentes e evento ativador.                |
| Ação               | O sistema identifica evento e envia a notificação pelo canal configurado. |
| Fluxo principal    | - Evento ocorre (ex: consulta cancelada).<br>- Preferências são consultadas.<br>- Sistema envia via canal apropriado(e-mail, SMS e/ou notificação do próprio app).<br>- Envio é registrado. |
| Fluxo alternativo  | - Falha de envio: sistema realiza tentativa posterior.                    |
| Fluxo de exceção   | - Falha permanente: log de erro registrado, equipe notificada.            |
| Pós-condições      | Notificação enviada ou tentativa registrada para análise.                 |
| Rastreabilidade    |    [RF04](../../elicitacao/requisitos_finais.md#RF04)                                                                       |
| Data de criação    | 15/05/2025                                                                |

<p align="center">Fonte: Autoria de <a src="https://github.com/isaqzin" targe="_blank">Isaque Camargos</a></p>

---

### UC12 – Solicitar autorização de urgência/emergência
<p align="center">Tabela 14 - Caso de Uso 12 </p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| <a id="UC12"></a>UC12                 |  Solicitar autorização de urgência/emergência                      |
| Descrição          | Permitir que profissionais de saúde solicitem autorização em tempo real. |
| Ator               | Profissional de saúde e INAS                                   |
| Pré-condições      | Sistema disponível e login realizado.                                     |
| Ação               | Profissional preenche dados e solicita autorização imediata.              |
| Fluxo principal    | - Profissional acessa funcionalidade.<br>- Informa dados do paciente.<br>- Sistema ou o INAS valida e aprova.<br>- Autorização emitida. |
| Fluxo alternativo  | - Dados incompletos: sistema solicita complementação.                     |
| Fluxo de exceção   | - Sistema fora do ar: notifica falha e orienta alternativa.               |
| Pós-condições      | Autorização registrada, atendimento liberado.                             |
| Rastreabilidade    | [RNF04](../../elicitacao/requisitos_finais.md#RNF04)                                                                           |
| Data de criação    | 15/05/2025                                                                |

<p align="center">Fonte: Autoria de <a src="https://github.com/isaqzin" targe="_blank">Isaque Camargos</a></p>

---

### UC13 – Agendar consulta ou exame
<p align="center">Tabela 15 - Caso de Uso 13 </p>

| Campo             | Descrição                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC13"></a>UC13                | Agendar consulta ou exame                                                                   |
| Descrição         | Permitir que o titular agende uma consulta ou exame com prestadores credenciados via aplicativo, com pagamento automático integrado. |
| Ator              | Titular do plano de saúde                                                                           |
| Pré-condições     | 1. Titular autenticado no aplicativo <br> 2. Estar com plano de saúde ativo <br> 3. Ter conexão com internet |
| Ação              | Usuário seleciona tipo de atendimento (consulta ou exame), define prestador e horário e confirma o agendamento. O sistema realiza o pagamento automático. |
| Fluxo principal   | - Usuário abre o aplicativo <br> - Acessa a seção de agendamento <br> - Escolhe tipo de atendimento <br> - Seleciona prestador e horário <br> - Confirma agendamento <br> - Sistema realiza pagamento automático |
| Fluxo alternativo | - Usuário cancela o agendamento antes da confirmação <br> - Sistema não realiza pagamento |
| Fluxo de exceção  | - Prestador indisponível para o horário escolhido <br> - Falha no pagamento automático <br> - Exibe mensagem de erro ao usuário |
| Pós-condições     | Agendamento é confirmado e exibido ao usuário; valor debitado automaticamente do saldo ou coparticipação processada |
| Rastreabilidade   | [RF05](../../elicitacao/requisitos_finais.md#RF05)                                                                                              |
| Data de criação   | 17/05/2025                                                                                          |
<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC14 – Cancelar consulta ou exame

<p align="center">Tabela 16 - Caso de Uso 14 </p>

| Campo             | Descrição                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC14"></a>UC14                | Cancelar consulta ou exame                                                                  |
| Descrição         | Permitir que o titular cancele um agendamento de consulta ou exame feito anteriormente pelo aplicativo. |
| Ator              | Titular do plano de saúde                                                                           |
| Pré-condições     | 1. Titular autenticado no aplicativo <br> 2. Existir um agendamento ativo para consulta ou exame <br> 3. Conexão com internet |
| Ação              | Usuário acessa a lista de agendamentos, escolhe o atendimento que deseja cancelar e confirma a ação. |
| Fluxo principal   | - Usuário acessa o aplicativo <br> - Entra na seção de agendamentos ativos <br> - Seleciona uma consulta ou exame <br> - Confirma o cancelamento <br> - Sistema remove o agendamento |
| Fluxo alternativo | - Usuário visualiza detalhes mas não confirma o cancelamento <br> - Nenhuma alteração é feita |
| Fluxo de exceção  | - Tentativa de cancelar um agendamento já expirado <br> - Falha de conexão com o servidor <br> - Exibe mensagem de erro ao usuário |
| Pós-condições     | O atendimento é removido da agenda e o usuário visualiza a confirmação de cancelamento              |
| Rastreabilidade   | RF05 [RF05](../../elicitacao/requisitos_finais.md#RF05)                                                                                               |
| Data de criação   | 17/05/2025                                                                                          |


<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC15 – Visualizar valor da consulta

<p align="center">Tabela 17 - Caso de Uso 15 </p>

| Campo             | Descrição                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC15"></a>UC15                | Visualizar valor da consulta                                                                |
| Descrição         | Permitir que o titular visualize o valor exato de uma consulta em uma clínica específica, considerando a aplicação automática de coparticipação. |
| Ator              | Titular do plano de saúde                                                                           |
| Pré-condições     | 1. Estar autenticado no aplicativo <br> 2. Ter plano de saúde ativo <br> 3. Conexão com internet     |
| Ação              | O usuário navega até a aba de valores, seleciona uma clínica e visualiza o valor final com a coparticipação aplicada. |
| Fluxo principal   | - Usuário acessa o aplicativo <br> - Vai até a seção de consultas <br> - Escolhe uma clínica específica <br> - Sistema exibe o valor bruto e o valor com coparticipação aplicada |
| Fluxo alternativo | - Usuário apenas visualiza a lista de clínicas sem selecionar nenhuma <br> - Sistema exibe faixa de preço genérica |
| Fluxo de exceção  | - Clínica não possui valor cadastrado <br> - Falha ao aplicar a coparticipação <br> - Sistema exibe mensagem de erro |
| Pós-condições     | O usuário compreende o valor final que será cobrado no agendamento da consulta                     |
| Rastreabilidade   | [RF06](../../elicitacao/requisitos_finais.md#RF06)                                                                                             |
| Data de criação   | 17/05/2025                                                                                          |


<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC16 – Gerar demonstrativo de IR

<p align="center">Tabela 18 - Caso de Uso 16 </p>

| Campo             | Descrição             |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC16"></a>UC16                | Gerar demonstrativo de IR                                                                   |
| Descrição         | Permitir que o titular gere um demonstrativo com os dados de despesas médicas para fins de declaração do Imposto de Renda. |
| Ator              | Titular do plano de saúde                                                                           |
| Pré-condições     | 1. Titular autenticado <br> 2. Existência de despesas médicas registradas no sistema <br> 3. Conexão ativa com internet |
| Ação              | O usuário seleciona o período desejado e solicita a geração do demonstrativo de IR.                |
| Fluxo principal   | - Usuário acessa o aplicativo <br> - Entra na seção de impostos <br> - Seleciona o ano-base desejado <br> - Clica em “Gerar demonstrativo” <br> - Sistema processa os dados |
| Fluxo alternativo | - Usuário seleciona o período, mas não finaliza a geração <br> - Nenhum arquivo é criado            |
| Fluxo de exceção  | - Nenhuma despesa registrada no período <br> - Falha ao gerar o documento <br> - Sistema exibe mensagem de erro |
| Pós-condições     | O demonstrativo é gerado e pode ser baixado pelo usuário em seguida                                |
| Rastreabilidade   |  [RF06](../../elicitacao/requisitos_finais.md#RF06)                                                                                              |
| Data de criação   | 17/05/2025                                                                                          |


<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC17 – Visualizar histórico de IR	

<p align="center">Tabela 19 - Caso de Uso 17 </p>

| Campo             | Descrição                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC17"></a>UC17                | Visualizar histórico de IR                                                                   |
| Descrição         | Permitir que o titular consulte todos os demonstrativos de despesas médicas já gerados para declaração do Imposto de Renda. |
| Ator              | Titular do plano de saúde                                                                           |
| Pré-condições     | 1. Titular autenticado <br> 2. Existência de demonstrativos anteriores <br> 3. Conexão com internet |
| Ação              | O usuário acessa a seção de histórico de IR e visualiza os demonstrativos disponíveis por ano.     |
| Fluxo principal   | - Usuário acessa o aplicativo <br> - Entra na seção de histórico de IR <br> - Visualiza a lista de demonstrativos por ano <br> - Seleciona um deles para consulta |
| Fluxo alternativo | - Nenhum demonstrativo é selecionado <br> - Tela permanece apenas com listagem                     |
| Fluxo de exceção  | - Nenhum histórico encontrado <br> - Erro ao carregar dados <br> - Sistema exibe alerta ao usuário |
| Pós-condições     | O demonstrativo consultado é exibido com detalhes ao usuário                                       |
| Rastreabilidade   | [RF06](../../elicitacao/requisitos_finais.md#RF06)                                                                                              |
| Data de criação   | 17/05/2025                                                                                          |


<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC18 – Visualizar painel de metas
<p align="center">Tabela 20 - Caso de Uso 18 </p>

| Campo             | Descrição                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC18"></a>UC18                | Visualizar painel de metas                                                                  |
| Descrição         | Permitir que o titular ou dependente acesse um painel com metas de saúde personalizadas, como exames periódicos ou consultas anuais. |
| Ator              | Titular do plano de saúde, Dependente                                                              |
| Pré-condições     | 1. Usuário autenticado <br> 2. Perfil de saúde configurado <br> 3. Metas cadastradas no sistema    |
| Ação              | O usuário acessa a seção de metas e visualiza objetivos ativos, status de cumprimento e progresso gamificado. |
| Fluxo principal   | - Usuário acessa o aplicativo <br> - Entra na área de metas <br> - Visualiza metas personalizadas <br> - Sistema exibe progresso com gamificação |
| Fluxo alternativo | - Usuário acessa a seção, mas não possui metas registradas <br> - Sistema exibe mensagem de ausência de metas |
| Fluxo de exceção  | - Falha ao carregar dados de metas <br> - Sistema exibe mensagem de erro ao usuário                |
| Pós-condições     | O usuário pode acompanhar suas metas de saúde e é incentivado a cumpri-las                         |
| Rastreabilidade   | [RF17](../../elicitacao/requisitos_finais.md#RF17)                                                                                              |
| Data de criação   | 17/05/2025                                                                                          |


<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC19 – Solicitar autorização
<p align="center">Tabela 21 - Caso de Uso 19 </p>

| Campo             | Descrição                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC19"></a>UC19                | Solicitar autorização                                                                       |
| Descrição         | Permitir que o titular ou dependente solicite uma autorização prévia para a realização de procedimentos que exigem aprovação do plano. |
| Ator              | Titular do plano de saúde, Dependente                                                              |
| Pré-condições     | 1. Usuário autenticado <br> 2. Procedimento exige autorização <br> 3. Documentação necessária anexada |
| Ação              | O usuário acessa a funcionalidade, preenche o formulário de solicitação e envia os documentos exigidos para análise. |
| Fluxo principal   | - Usuário acessa o aplicativo <br> - Entra na seção de autorizações <br> - Preenche o formulário <br> - Anexa documentos <br> - Envia solicitação para análise |
| Fluxo alternativo | - Usuário acessa a seção, mas não finaliza o envio <br> - Solicitação não é registrada             |
| Fluxo de exceção  | - Documento obrigatório não anexado <br> - Falha no envio dos dados <br> - Sistema exibe mensagem de erro |
| Pós-condições     | A solicitação é registrada no sistema e encaminhada para análise, respeitando o prazo máximo de 10 dias úteis |
| Rastreabilidade   | [RNF08](../../elicitacao/requisitos_finais.md#RNF08)                                                                                             |
| Data de criação   | 17/05/2025                                                                                          |


<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

---

### UC20 – Verificar conformidade com LGPD
<p align="center">Tabela 22 - Caso de Uso 20 </p>

| Campo             | Descrição                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------|
| <a id="UC20"></a>UC20                | Verificar conformidade com LGPD                                                             |
| Descrição         | Garantir que o sistema esteja em conformidade com a Portaria nº 127/2024, legislações complementares e os princípios da LGPD durante o uso das funcionalidades que tratam dados pessoais. |
| Ator              | Sistema                                                                                             |
| Pré-condições     | 1. Ação do usuário envolve tratamento de dados pessoais <br> 2. Consentimento válido registrado    |
| Ação              | O sistema valida automaticamente se os dados estão sendo processados conforme as políticas da LGPD e as normas vigentes antes de executar operações sensíveis. |
| Fluxo principal   | - Usuário inicia uma ação (ex: agendamento, geração de documento) <br> - Sistema verifica conformidade com as normas <br> - Caso positivo, a ação prossegue |
| Fluxo alternativo | - Consentimento expirado ou ausente <br> - Sistema bloqueia operação e solicita aceite atualizado |
| Fluxo de exceção  | - Violação detectada na política de privacidade <br> - Sistema registra ocorrência e nega a operação |
| Pós-condições     | O sistema garante que as operações executadas seguem as exigências legais e mantém rastreamento das ações realizadas |
| Rastreabilidade   | [RNF07](../../elicitacao/requisitos_finais.md#RNF07)                                                                                               |
| Data de criação   | 17/05/2025                                                                                          |
<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

<p align="center">Tabela 23 - Caso de Uso 21 </p>

###  UC21 – Cadastrar titulares, dependentes e optantes
| Campo | Descrição |
|  -----------------  |  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------  |
| <a id="UC21"></a>UC21 | Cadastrar titulares, dependentes e optantes |
| Descrição | Permitir o cadastro de titulares, dependentes e optantes no sistema com validação de documentos e elegibilidade. |
| Ator | Atendente do plano de saúde / Titular |
| Pré-condições | 1. Usuário autenticado (se for o titular) <br> 2. Documentação digitalizada |
| Ação | Usuário preenche os dados, envia documentos e confirma o cadastro; sistema valida e registra. |
| Fluxo principal | - Usuário acessa a seção de cadastro <br> - Escolhe tipo de pessoa (titular, dependente, optante) <br> - Preenche dados e anexa documentos <br> - Sistema valida documentação e elegibilidade <br> - Cadastro é confirmado |
| Fluxo alternativo | - Sistema identifica documentos inválidos <br> - Informa o usuário e solicita novo envio |
| Fluxo de exceção | - Falha no upload de documentos <br> - Erro no processo de validação |
| Pós-condições | Cadastro realizado e pessoa adicionada à base de dados com status elegível ou pendente |
| Rastreabilidade | [RF07](../../elicitacao/requisitos_finais.md#RF07) |
| Data de criação | 17/05/2025 |

<p  align="center">Fonte: Autoria de <a  href="https://github.com/LucasAlves71">Lucas Alves</a></p>


---


###  UC22 – Verificar procedimentos para autorização
<p align="center">Tabela 24 - Caso de Uso 22 </p>
  

| Campo | Descrição |
|  -----------------  |  -----------------------------------------------------------------------------------------------------------------------------------------------------------  |
| <a id="UC22"></a>UC22 | Verificar procedimentos para autorização |
| Descrição | Verificar se procedimentos estão na TABGDFSAÚDE, se atendem às DUT, carência ou exclusões, exigindo solicitação médica e análise técnica. |
| Ator | Titular / Profissional de saúde / Analista técnico |
| Pré-condições | 1. Procedimento solicitado <br> 2. Dados médicos anexados |
| Ação | Usuário submete solicitação de procedimento; sistema verifica regras e, se necessário, aciona análise técnica. |
| Fluxo principal | - Solicitação médica submetida <br> - Sistema verifica TABGDFSAÚDE e DUT <br> - Verifica carência e exclusões <br> - Solicita análise técnica se necessário |
| Fluxo alternativo | - Procedimento está coberto e não exige análise <br> - Autorização é liberada automaticamente |
| Fluxo de exceção | - Solicitação incompleta ou sem documentação médica <br> - Exibe erro e solicita correção |
| Pós-condições | Procedimento autorizado ou negado com justificativa técnica |
| Rastreabilidade | [RF08](../../elicitacao/requisitos_finais.md#RF08) |
| Data de criação | 17/05/2025 |

  
  

<p  align="center">Fonte: Autoria de <a  href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---


###  UC23 – Visualizar calendário personalizado
<p align="center">Tabela 25 - Caso de Uso 23 </p>
  

| Campo | Descrição |
|  -----------------  |  ---------------------------------------------------------------------------------------------------------------------------------  |
| <a id="UC23"></a>UC23 | Visualizar calendário personalizado |
| Descrição | Disponibilizar ao titular um calendário com consultas agendadas, prazos de carência e vencimentos. |
| Ator | Titular |
| Pré-condições | 1. Titular autenticado <br> 2. Ter eventos vinculados ao seu plano |
| Ação | Usuário acessa calendário e visualiza eventos pessoais e datas importantes |
| Fluxo principal | - Usuário acessa a área de calendário <br> - Sistema exibe visualização personalizada com: <br> consultas, carências, vencimentos |
| Fluxo alternativo | - Não há consultas ou prazos registrados <br> - Sistema informa ausência de eventos |
| Fluxo de exceção | - Falha na recuperação de dados <br> - Exibe mensagem de erro |
| Pós-condições | Titular visualiza suas obrigações e compromissos relacionados ao plano |
| Rastreabilidade | [RF16](../../elicitacao/requisitos_finais.md#RF16) |
| Data de criação | 17/05/2025 |


<p  align="center">Fonte: Autoria de <a  href="https://github.com/LucasAlves71">Lucas Alves</a></p>

--- 

###  UC24 – Registrar denúncia contra profissional
<p align="center">Tabela 26 - Caso de Uso 24 </p>
  

| Campo | Descrição |
|  -----------------  |  ------------------------------------------------------------------------------------------------------------------------------  |
| <a id="UC24"></a>UC24 | Registrar denúncia contra profissional |
| Descrição | Permitir que o titular registre denúncias sobre condutas inadequadas de profissionais da rede credenciada. |
| Ator | Titular |
| Pré-condições | 1. Titular autenticado <br> 2. Consulta ou atendimento realizado com profissional credenciado |
| Ação | Usuário preenche formulário de denúncia e submete com descrição dos fatos |
| Fluxo principal | - Usuário acessa seção de denúncias <br> - Informa dados do atendimento <br> - Descreve a denúncia <br> - Submete para análise |
| Fluxo alternativo | - Usuário salva denúncia como rascunho para enviar depois |
| Fluxo de exceção | - Falha no envio da denúncia <br> - Sistema exibe erro e sugere reenvio |
| Pós-condições | Denúncia registrada e encaminhada para análise pelo setor responsável |
| Rastreabilidade | [RF18](../../elicitacao/requisitos_finais.md#RF18) |
| Data de criação | 17/05/2025 |

<p  align="center">Fonte: Autoria de <a  href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

###  UC25 – Comunicar com folha de pagamento do GDF
<p align="center">Tabela 27 - Caso de Uso 25 </p>
  

| Campo | Descrição |
|  -----------------  |  ---------------------------------------------------------------------------------------------------------------------------------------------  |
| <a id="UC25"></a>UC25 |Comunicar com folha de pagamento do GDF |
| Descrição | Permitir comunicação automatizada entre o sistema e a folha de pagamento do GDF para descontos de mensalidades. |
| Ator | Sistema |
| Pré-condições | 1. Titular com vínculo ativo ao GDF <br> 2. Plano de saúde com mensalidade ativa |
| Ação | Sistema envia dados de cobrança à folha de pagamento e recebe confirmação de desconto |
| Fluxo principal | - Sistema verifica titulares vinculados <br> - Gera informações de cobrança <br> - Envia à folha do GDF <br> - Recebe confirmação de desconto |
| Fluxo alternativo | - Sistema reprograma envio se falha temporária na comunicação |
| Fluxo de exceção | - Falha na integração com sistema do GDF <br> - Notifica equipe técnica |
| Pós-condições | Mensalidade é descontada automaticamente na folha |
| Rastreabilidade | [RNF09](../../elicitacao/requisitos_finais.md#RNF09) |
| Data de criação | 17/05/2025 |


<p  align="center">Fonte: Autoria de <a  href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

###  UC26 – Acesso rápido à carteirinha digital
<p align="center">Tabela 28 - Caso de Uso 26 </p>

| Campo | Descrição |
|  -----------------  |  -------------------------------------------------------------------------------------------------------------------  |
| <a id="UC26"></a>UC26 | Acesso rápido à carteirinha digital |
| Descrição | Garantir que a carteirinha digital esteja acessível em até três cliques ou no máximo dois a partir da tela inicial. |
| Ator | Titular |
| Pré-condições | 1. Aplicativo instalado <br> 2. Titular autenticado |
| Ação | Usuário navega pela interface do app até a carteirinha digital com acessibilidade rápida |
| Fluxo principal | - Usuário abre o aplicativo <br> - Acessa a área de carteirinha (máximo 2 cliques) <br> - Visualiza dados |
| Fluxo alternativo | - Carteirinha disponível via atalho na tela inicial |
| Fluxo de exceção | - Falha no carregamento da carteirinha <br> - Exibe erro e instruções |
| Pós-condições | Titular acessa rapidamente seus dados de identificação do plano |
| Rastreabilidade | [RNF10](../../elicitacao/requisitos_finais.md#RNF10) |
| Data de criação | 17/05/2025 |


<p  align="center">Fonte: Autoria de <a  href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

### UC27 - Visualizar Histórico de Guias
<p align="center">Tabela 29 - Caso de Uso 27 </p>

| Campo | Descrição |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC27"></a>UC27 | Visualizar histórico de guias |
| Descrição | O caso de uso possibilita ao usuário visualizar seu histórico de guias, incluindo consultas médicas, exames realizados, resultados de exames laboratoriais e coparticipações, de forma organizada e acessível no GDF Saúde. |
| Ator | Usuário cadastrado no plano de saúde GDF Saúde. |
| Pré-condições | O GDF Saúde deve conter registros de saúde do usuário. |
| Ação | O usuário acessa a seção "Histórico de Saúde" para visualizar informações do seu histórico de saúde. |
| Fluxo Básico | 1. O sistema exibe uma lista com as informações do histórico (consultas, exames, resultados e coparticipações).<br>2. O usuário pode aplicar filtros ou buscar por palavras-chave.<br>3. O usuário seleciona um item para visualizar detalhes.<br>4. O sistema exibe os detalhes completos do item selecionado.<br>5. Finaliza caso de uso. |
| Fluxo Alternativo | FA1. Sem Histórico Disponível: No passo 1, se não houver histórico, o sistema exibe "Nenhum histórico disponível". Finaliza fluxo. |
| Fluxo de Exceção | FE1. Erro Técnico: No passo 1, caso ocorra um erro técnico, o sistema exibe "Erro ao carregar histórico" e oferece opções de tentar novamente ou contatar o suporte. Finaliza fluxo. |
| Pós-condições | O usuário visualizou seu histórico de saúde. |
| Rastreabilidade | [RF09](../../elicitacao/requisitos_finais.md#RF09) |
| Data de Criação | 15/05/2025 |

<p  align="center">Fonte: Autoria de <a  href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

### UC28 - Favoritar Horários de Consulta
<p align="center">Tabela 30 - Caso de Uso 28 </p>

| Campo           | Descrição                                                                                                                                        |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC28"></a>UC28            | Favoritar Horários de Consulta|
| Descrição       | Permite ao usuário marcar horários preferidos para agendamentos futuros no GDF Saúde, facilitando agendamentos com rapidez e conveniência.|
| Ator            | Usuário cadastrado no plano de saúde GDF Saúde.|
| Pré-condições   | O GDF Saúde deve exibir horários disponíveis para consulta.|
| Ação            | O usuário acessa a seção de agendamento, seleciona horários para favoritar e confirma a ação.|
| Fluxo Básico    | 1. O sistema exibe horários disponíveis.<br>2. O usuário seleciona horários para favoritar.<br>3. O usuário confirma a ação.<br>4. O sistema salva os horários na lista de favoritos.<br>5. Finaliza caso de uso.                                                                                                            |
| Fluxo Alternativo| FA1. Horário Indisponível:<br>- Se um horário selecionado estiver indisponível, o sistema notifica "Horário não disponível" e remove-o da seleção.<br>- O sistema retoma ao passo 2 do fluxo básico.                                                                                                                         |
| Fluxo de Exceção| FE1. Erro Técnico:<br>- Se ocorrer erro ao salvar, o sistema exibe "Erro ao salvar horário" e oferece opção de tentar novamente.<br>- Finaliza fluxo.                                                                                                                                |
| Pós-condições   | Os horários favoritados estão salvos no perfil do usuário.                                                                                                                                                                                                                                                |
| Rastreabilidade | [RF10](../../elicitacao/requisitos_finais.md#RF10)                                                                                                                                                  |
| Data de Criação | 15/05/2025                                                                                                                                                                                                          

<p align="center">Fonte: Autoria de <a  href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

### UC29 - Solicitação de Reembolso de Cobrança Indevida
<p align="center">Tabela 31 - Caso de Uso 29 </p>

| Campo           | Descrição                                                                                                                                                                                                                                            |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC29"></a>UC29            | Solicitação de Reembolso de Cobrança Indevida|
| Descrição       | Permite ao usuário solicitar reembolso de valores cobrados indevidamente no GDF Saúde, fornecendo justificativa e documentos para análise, garantindo um processo transparente e eficiente.|
| Ator            | Usuário cadastrado no plano de saúde GDF Saúde.|
| Pré-condições   | 1. O usuário deve ter uma cobrança registrada no GDF Saúde.<br>2. A solicitação deve ser feita dentro de 30 dias da cobrança indevida.|
| Ação            | O usuário acessa a seção de reembolso, seleciona a cobrança indevida, preenche justificativa, anexa documentos e envia a solicitação para análise.|
| Fluxo Básico    | 1. O sistema exibe uma lista de cobranças recentes.<br>2. O usuário seleciona a cobrança indevida.<br>3. O sistema apresenta formulário para justificativa e anexos.<br>4. O usuário preenche justificativa e anexa documentos.<br>5. O sistema valida e envia a solicitação.<br>6. O sistema notifica o usuário.<br>7. Finaliza caso de uso.                                                                                                    |
| Fluxo Alternativo| FA1. Documentação Incompleta:<br>- No passo 4, se a documentação estiver incompleta, o sistema solicita os arquivos faltantes.<br>- O usuário anexa os documentos adicionais.<br>- O sistema retoma ao passo 5.                                                                                                                                          |
| Fluxo de Exceção| FE1. Erro Técnico:<br>- No passo 5, caso ocorra erro técnico, o sistema exibe "Erro ao enviar solicitação" e oferece opção de tentar novamente.<br>- Finaliza fluxo.                                                                                                                                             |
| Pós-condições   | A solicitação de reembolso foi registrada e enviada para análise.                                                                                                                     |
| Rastreabilidade |   [RF20](../../elicitacao/requisitos_finais.md#RF20)                                                                        |
| Data de Criação | 15/05/2025                                                                                                                                             |

<p align="center">Fonte: Autoria de <a  href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

### UC30 - Acessar Histórico de Notificações
<p align="center">Tabela 32 - Caso de Uso 30 </p>

| Campo           | Descrição                                                                                           |
|-----------------|-----------------------------------------------------------------------------------------------------|
| <a id="UC30"></a>UC30            | Acessar Histórico de Notificações                                                                   |
| Descrição       | Permite ao usuário visualizar notificações recebidas nos últimos 6 meses no GDF Saúde.              |
| Ator            | Usuário cadastrado no plano de saúde GDF Saúde.                                                     |
| Pré-condições   | O GDF Saúde deve ter notificações armazenadas por pelo menos 6 meses.                               |
| Ação            | Usuário acessa a seção "Notificações" para visualizar o histórico.                                  |
| Fluxo Básico    | 1. Sistema exibe lista de notificações dos últimos 6 meses.<br>2. Usuário pode filtrar ou buscar notificações.<br>3. Finaliza caso de uso. |
| Fluxo Alternativo| FA1. Se não houver notificações, o sistema exibe "Nenhuma notificação disponível" e finaliza fluxo. |
| Fluxo de Exceção| FE1. Em caso de erro técnico, o sistema exibe "Erro ao carregar notificações" e oferece tentar novamente. |
| Pós-condições   | O usuário acessou o histórico de notificações.                                                      |
| Rastreabilidade |       [RNF11](../../elicitacao/requisitos_finais.md#RNF11)                                                                                              |
| Data de Criação | 15/05/2025                                                                                               |

<p align="center">Fonte: Autoria de <a  href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

### UC31 - Receber Suporte via Chat ou Telefone
<p align="center">Tabela 33 - Caso de Uso 31 </p>

| Campo           | Descrição                                                                                                                                                                                                                  |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC31"></a>UC31            | Receber suporte via chat ou telefone                                                                                                                                                |
| Descrição       | O caso de uso possibilita ao usuário receber suporte por chat ou telefone para resolver dúvidas ou problemas, com tempos de resposta definidos.                                      |
| Ator            | Usuário cadastrado no plano de saúde GDF Saúde, Agente de Suporte                                                                            |
| Pré-condições   | O GDF Saúde deve ter canais de suporte (chat ou telefone) ativos.                                                                            |
| Ação            | O usuário acessa a seção "Suporte" no GDF Saúde e escolhe entre chat ou telefone para receber assistência.                                   |
| Fluxo Básico    | 1. O sistema exibe opções de chat ou telefone.<br>2. O usuário seleciona chat ou telefone.<br>3. Para chat: O sistema abre uma janela e o usuário envia uma mensagem.<br>4. Para telefone: O usuário liga para o número fornecido.<br>5. O agente de suporte responde e auxilia o usuário.<br>6. Finaliza caso de uso. |
| Fluxo Alternativo| FA1. Tempo de Espera Excedido: No passo 4, se o tempo de resposta exceder 5 minutos (chat) ou 2 toques (telefone), o sistema notifica "Aguarde, estamos atendendo" e retoma ao passo 4.                                    |
| Fluxo de Exceção| FE1. Canal Indisponível: No passo 2, caso o canal esteja indisponível, o sistema exibe "Suporte temporariamente indisponível" e sugere tentar mais tarde. Finaliza fluxo.                                                  |
| Pós-condições   | O usuário recebeu assistência ou foi informado sobre a solução.                                                                             |
| Rastreabilidade | [RNF12](../../elicitacao/requisitos_finais.md#RNF12)                                                                                                                                                                                |
| Data de Criação | 15/05/2025                                                                                                                                                                               |

<p align="center">Fonte: Autoria de <a  href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></p>

---

### UC32 – Enviar Feedback de Atendimento
<p align="center">Tabela 34 - Caso de Uso 32 </p>

| Campo | Descrição | 
|-----------------------|-------------------------------------------------------------------------------| 
| <a id="UC32"></a>UC32 | Enviar Feedback de Atendimento     |
| Descrição | Permitir que o usuário acesse o app mediante autenticação GovBR. |
| Ator | - Usuário cadastrado no GovBR|
| Pré-condições | 1. Usuário autenticado <br> 2. Consulta já realizada <br> 3. Conexão com a internet ativa|
| Ação | Usuário acessa o canal de feedback, seleciona uma consulta anterior e preenche o formulário com a avaliação. |
| Fluxo principal |- Usuário acessa a área de feedback <br> - Seleciona uma consulta <br> - Preenche formulário de avaliação <br> - Envia feedback |
| Fluxo alternativo |- Consulta ainda não realizada: sistema bloqueia envio <br> - Avaliação incompleta: sistema solicita preenchimento obrigatório|
| Fluxo de exceção | - Falha de rede durante envio <br> - Erro de autenticação do usuário|
| Pós-condições | Feedback registrado e vinculado à consulta avaliada  |
| Rastreabilidade | [RF11](../../elicitacao/requisitos_finais.md#RF11) |
| Data de criação | 17/05/2025 | 
<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>


### UC33 – Acessar Informações sobre Novas Funcionalidades
<p align="center">Tabela 35 - Caso de Uso 33 </p>

| Campo | Descrição | 
|-----------------------|-------------------------------------------------------------------------------| 
| <a id="UC33"></a>UC33 |Acessar Informações sobre Novas Funcionalidades    |
| Descrição | Permitir que o usuário acesse informações divulgadas pelo sistema sobre novas funcionalidades do aplicativo. |
| Ator | - Usuário do plano de saúde. -Sistema do GDF Saúde  |
| Pré-condições | 1. Aplicativo iniciado <br> 2. Conexão com a internet ativ|
| Ação | Sistema adiciona informações sobre novas funcionalidades; usuário acessa e visualiza essas informações. |
| Fluxo principal |- Sistema publica nova funcionalidade <br> - Usuário acessa área de novidades <br> - Visualiza detalhes da funcionalidade. |
| Fluxo alternativo |- Usuário não acessa a área de novidades <br> - Nenhuma ação ocorre.| 
| Fluxo de exceção | - Falha na atualização de dados pelo sistema <br> - Problemas de conexão no acesso do usuário.| 
| Pós-condições | Usuário visualiza informações atualizadas sobre novas funcionalidades. |
| Rastreabilidade | [RF12](../../elicitacao/requisitos_finais.md#RF12) |
| Data de criação | 17/05/2025 | 

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

### UC34 – Acessar Aplicativo em Modo Offline
<p align="center">Tabela 36 - Caso de Uso 34 </p>

| Campo | Descrição | 
|-----------------------|-------------------------------------------------------------------------------| 
| <a id="UC34"></a>UC34 |Acessar Aplicativo em Modo Offline.    |
| Descrição | Permitir que o usuário acesse o aplicativo e utilize funcionalidades básicas como carteirinha e histórico de consultas sem conexão com a internet. |
| Ator | - Usuário do plano de saúde. |
| Pré-condições | 1. Aplicativo instalado <br> 2. Dados sincronizados previamente <br> 3. Sem conexão com internet.| 
| Ação | Usuário inicia o aplicativo sem conexão; sistema carrega funcionalidades offline permitidas. |
| Fluxo principal |- Usuário abre aplicativo <br> - Sistema detecta ausência de internet <br> - Ativa modo offline <br> - Usuário acessa carteirinha e histórico de consultas |
| Fluxo alternativo |- Caso dados offline não estejam atualizados, sistema exibe aviso de possível desatualização. |
| Fluxo de exceção | - Dados offline corrompidos ou indisponíveis| 
| Pós-condições | Usuário acessa funcionalidades básicas com dados disponíveis em modo offline| 
| Rastreabilidade | [RNF13](../../elicitacao/requisitos_finais.md#RNF13) |
| Data de criação | 17/05/2025 | 

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a></p>

---

### UC35 – Fazer login via GovBR
<p align="center">Tabela 37 - Caso de Uso 35 </p>

| Campo | Descrição | 
|-----------------------|-------------------------------------------------------------------------------| 
| <a id="UC35"></a>UC35 | Fazer login via GovBR |
| Descrição | Permitir que o usuário acesse o app mediante autenticação GovBR. |
| Ator | Usuário cadastrado no GovBR |
| Pré-condições | App instalado, conexão à internet e conta GovBR ativa. |
| Ação | O usuário seleciona "Login com GovBR" e realiza a autenticação. |
| Fluxo principal | 1. Usuário acessa a tela de login.<br>2. Seleciona "Autenticar com GovBR".<br>3. Sistema redireciona para a plataforma GovBR.<br>4. Usuário insere credenciais GovBR.<br>5. Sistema valida e autentica o usuário. |
| Fluxo alternativo | Credenciais inválidas: sistema exibe mensagem de erro e sugere recuperação de senha. |
| Fluxo de exceção | Falha na conexão com GovBR: sistema informa indisponibilidade temporária. |
| Pós-condições | Usuário autenticado e com acesso às funcionalidades do app. |
| Rastreabilidade | [RNF15](../../elicitacao/requisitos_finais.md#RNF15) |
| Data de criação | 17/05/2025 | 
---
<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

### UC36 – Consultar rede odontológica
<p align="center">Tabela 38 - Caso de Uso 36 </p>

| Campo | Descrição |
|-----------------------|-------------------------------------------------------------------------------|
| <a id="UC36"></a>UC36 | Consultar rede odontológica |
| Descrição | Permitir ao usuário buscar clínicas odontológicas cadastradas. |
| Ator | Usuário autenticado |
| Pré-condições | Usuário estar logado via GovBR. |
| Ação | O usuário acessa a funcionalidade de busca e insere critérios de pesquisa. |
| Fluxo principal | 1. Usuário acessa "Buscar rede odontológica".<br>2. Insere filtros (ex.: especialidade, bairro).<br>3. Sistema exibe lista de clínicas disponíveis. |
| Fluxo alternativo | Nenhum resultado: sistema sugere ampliar critérios de busca. |
| Fluxo de exceção | Falha na conexão: sistema notifica "Tente novamente mais tarde". |
| Pós-condições | Usuário visualiza clínicas odontológicas compatíveis. |
| Rastreabilidade | [RF13](../../elicitacao/requisitos_finais.md#RF13) |
| Data de criação | 17/05/2025 | 
---
<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

### UC37 – Buscar clínicas próximas
<p align="center">Tabela 39 - Caso de Uso 37 </p>

| Campo | Descrição |
|-----------------------|-------------------------------------------------------------------------------| 
| <a id="UC37"></a>UC37| Buscar clínicas próximas |
| Descrição | Apresentar clínicas próximas com base na localização do usuário. |
| Ator | Usuário autenticado |
| Pré-condições | Usuário logado e permissão para uso de geolocalização. |
| Ação| O sistema detecta a localização do usuário e exibe clínicas próximas. |
| Fluxo principal | 1. Usuário acessa "Buscar Unidades de Saúde Próximas".<br>2. Sistema detecta localização automática.<br>3. Exibe lista de clínicas em ordem de proximidade. |
| Fluxo alternativo | Localização automática falha: usuário insere endereço manualmente. |
| Fluxo de exceção | Geolocalização desativada: sistema solicita ativação ou entrada manual. |
| Pós-condições | Usuário visualiza clínicas próximas ou resultados conforme endereço. |
| Rastreabilidade | [RF14](../../elicitacao/requisitos_finais.md#RF14) |
| Data de criação | 17/05/2025 | 
---
<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

### UC38 – Baixar comprovante de agendamento

<p align="center">Tabela 40 - Caso de Uso 38 </p>

| Campo | Descrição |
|-----------------------|-------------------------------------------------------------------------------|
| <a id="UC38"></a>UC38 | Baixar comprovante de agendamento |
| Descrição | Permitir ao usuário baixar comprovantes de agendamentos realizados. |
| Ator | Usuário autenticado com agendamento ativo. |
| Pré-condições | Usuário logado e agendamento confirmado. |
| Ação | O usuário acessa a lista de agendamentos e seleciona "Baixar comprovante". |
| Fluxo principal | 1. Usuário acessa "Comprovantes de agendamento".<br>2. Seleciona o agendamento desejado.<br>3. Clica em "Baixar" e o sistema gera um PDF. |
| Fluxo alternativo | Comprovante expirado: sistema notifica "Agendamento não encontrado". |
| Fluxo de exceção | Falha no servidor: sistema exibe mensagem de erro. |
| Pós-condições | Comprovante é salvo no dispositivo do usuário. |
| Rastreabilidade | [RF15](../../elicitacao/requisitos_finais.md#RF15) |
| Data de criação | 17/05/2025 |

<p align="center">Fonte: Adaptado de <a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></p>

---

### UC39 - Combinar Filtros de Pesquisa

<p align="center">Tabela 41 - Caso de Uso 39 </p>

| Campo                    | Descrição|
|--------------------------|-----------------------------------------|
| <a id="UC39"></a>UC39     | Combinar Filtros de Pesquisa|
| Descrição                | Permitir ao usuário refinar progressivamente sua busca ao aplicar múltiplos filtros de forma simultânea.|
| Ator                     | Usuário do aplicativo GDF Saúde|
| Pré-condições            | 1. Conexão com internet. <br>2. Usuário está na tela de busca.|
| Ação                     | Usuário aplica um filtro inicial e, em seguida, adiciona um segundo filtro para restringir ainda mais os resultados.|
| Fluxo principal          | - Usuário acessa a busca e aplica o filtro "Especialidade: Ortopedia". <br>- Sistema atualiza a lista de resultados. <br>- Em seguida, o usuário aplica o filtro "Região: Taguatinga". <br>- Sistema atualiza a lista novamente, mostrando apenas resultados que atendem a ambos os filtros. |
| Fluxo alternativo        | - Usuário aplica múltiplos filtros, mas decide remover um deles. <br>- O usuário desmarca o filtro "Região: Taguatinga". <br>- Sistema recalcula os resultados, exibindo todos os ortopedistas, independentemente da região.                 |
| Fluxo de exceção         | - A combinação de filtros aplicada é muito restritiva e não retorna resultados. <br>- Sistema exibe a mensagem "Nenhum resultado para a combinação de filtros selecionada."|
| Pós-condições            | A lista de resultados exibida atende a todos os critérios dos filtros combinados pelo usuário.|
| Rastreabilidade          | [RF01.3](../../elicitacao/requisitos_finais.md#RF01.3)|
| Data de criação          | 12/06/2025|

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---
### UC40 – Buscar por Proximidade

<p align="center">Tabela 42 - Caso de Uso 40 </p>

| Campo                    | Descrição |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC40"></a>UC40     | Buscar por Proximidade|
| Descrição                | Permitir ao usuário encontrar redes credenciadas em um raio de até 10 km de sua localização geográfica atual.|
| Ator                     | Usuário do aplicativo GDF Saúde|
| Pré-condições            | 1. Conexão com internet. <br>2. Os serviços de localização do dispositivo estão ativados.|
| Ação                     | Usuário ativa a opção de filtro "Buscar Perto de Mim" na tela de pesquisa.|
| Fluxo principal          | - Na tela de busca, o usuário ativa o filtro de proximidade. <br>- Sistema solicita permissão para acessar a localização, caso ainda não a tenha. <br>- Usuário concede a permissão. <br>- Sistema obtém a localização e exibe os resultados em um raio de 10 km. |
| Fluxo alternativo        | - O usuário ativa o filtro, mas nega a permissão de acesso à localização. <br>- Sistema exibe uma mensagem informativa explicando que a funcionalidade requer a permissão para operar.                                                         |
| Fluxo de exceção         | - O sistema não consegue obter a localização do usuário devido a um erro de GPS ou de rede. <br>- Sistema exibe a mensagem "Não foi possível determinar sua localização. Tente novamente."                                                     |
| Pós-condições            | A lista de resultados é filtrada para exibir apenas as redes credenciadas próximas ao usuário, ordenadas pela distância.|
| Rastreabilidade          | [RF01.4](../../elicitacao/requisitos_finais.md#RF01.4)|
| Data de criação          | 12/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---
### UC41 – Filtrar por Especialidade Médica

<p align="center">Tabela 43 - Caso de Uso 41 </p>

| Campo                    | Descrição |
|--------------------------|-------------------------------------------------------------------------------------------------------------|
| <a id="UC41"></a>UC41     | Filtrar por Especialidade Médica |
| Descrição                | Permitir ao usuário filtrar a busca de redes credenciadas selecionando uma especialidade médica específica em uma lista. |
| Ator                     | Usuário do aplicativo GDF Saúde |
| Pré-condições            | 1. Conexão com internet. <br>2. Usuário está na tela de busca. |
| Ação                     | Usuário seleciona a opção de filtro "Especialidade" e escolhe um item da lista. |
| Fluxo principal          | - Usuário toca no campo de filtro "Especialidade". <br>- Sistema exibe uma lista de todas as especialidades disponíveis. <br>- Usuário seleciona "Dermatologia" da lista. <br>- Sistema atualiza a busca para mostrar apenas redes com essa especialidade. |
| Fluxo alternativo        | - O usuário começa a digitar no campo de busca de especialidades. <br>- O sistema filtra dinamicamente a lista de especialidades para corresponder ao texto digitado.                                                                       |
| Fluxo de exceção         | - A lista de especialidades não pode ser carregada devido a uma falha de conexão. <br>- Sistema exibe uma mensagem de erro com a opção de tentar novamente.                                                                                 |
| Pós-condições            | A lista de resultados contém apenas redes que atendem à especialidade médica selecionada. |
| Rastreabilidade          | [RF01.5](../../elicitacao/requisitos_finais.md#RF01.5) |
| Data de criação          | 12/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---
### UC42 – Atribuir Nota de Avaliação

<p align="center">Tabela 44 - Caso de Uso 42 </p>

| Campo                    | Descrição                                                 |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC42"></a>UC42     | Atribuir Nota de Avaliação                                      |
| Descrição                | Permitir ao usuário classificar a qualidade de um atendimento utilizando uma nota na escala Likert de 1 a 5. |
| Ator                     | Usuário do aplicativo GDF Saúde           |
| Pré-condições            | 1. Usuário teve um atendimento registrado na rede a ser avaliada. <br>2. Usuário está logado no aplicativo.   |
| Ação                     | Usuário seleciona uma nota de 1 a 5 estrelas na tela de avaliação de um atendimento. |
| Fluxo principal          | - Usuário acessa o perfil da clínica e seleciona a opção "Avaliar Atendimento". <br>- Sistema exibe a interface de avaliação. <br>- Usuário seleciona a nota desejada (ex: 4 de 5 estrelas). <br>- Usuário confirma a submissão da nota.      |
| Fluxo alternativo        | - O usuário seleciona uma nota, mas decide alterá-la antes de submeter. <br>- O usuário toca em uma nova quantidade de estrelas, e o sistema atualiza a seleção.                 |
| Fluxo de exceção         | - O usuário tenta submeter a avaliação, mas ocorre uma falha de conexão. <br>- Sistema exibe uma mensagem de erro e oferece a opção de tentar novamente, mantendo a nota selecionada.                                                        |
| Pós-condições            | A nota de avaliação do usuário é registrada com sucesso no sistema e associada ao respectivo atendimento. |
| Rastreabilidade          | [RF02.1](../../elicitacao/requisitos_finais.md#RF02.1) |
| Data de criação          | 12/06/2025   |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---
### UC43 – Ler e Escrever Comentários

<p align="center">Tabela 45 - Caso de Uso 43 </p>

| Campo                    | Descrição                                               |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC43"></a>UC43     | Ler e Escrever Comentários                                        |
| Descrição                | Permitir ao usuário ler as experiências de outros beneficiários e deixar seus próprios comentários sobre atendimentos. |
| Ator                     | Usuário do aplicativo GDF Saúde |
| Pré-condições            | 1. Usuário está logado. <br>2. Usuário está visualizando o perfil de uma clínica ou profissional.|
| Ação                     | Usuário acessa a seção de comentários para ler as avaliações ou preenche o campo de texto para submeter um novo comentário.                                                                                                                |
| Fluxo principal          | - Leitura: Usuário acessa a aba "Avaliações" e percorre a lista de comentários existentes. <br>- Escrita: Na mesma tela, usuário toca em "Deixar um comentário", digita seu feedback no campo de texto e toca em "Enviar".              |
| Fluxo alternativo        | - Ao escrever um comentário, o usuário decide cancelar a ação antes de enviar. <br>- O usuário toca no botão "Cancelar" e o sistema o retorna à tela anterior sem salvar o rascunho.     |
| Fluxo de exceção         | - O comentário do usuário contém termos inadequados bloqueados pelo sistema. <br>- Ao tentar enviar, o sistema exibe uma mensagem informando que o comentário não pode ser publicado e destaca as diretrizes da comunidade.                |
| Pós-condições            | Usuário visualiza os comentários de outros ou tem seu novo comentário submetido com sucesso para moderação e publicação. |
| Rastreabilidade          | [RF02.2](../../elicitacao/requisitos_finais.md#RF02.2) |
| Data de criação          | 12/06/2025   |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---
### UC44 – Visualizar Comentários Relevantes

<p align="center">Tabela 46 - Caso de Uso 44 </p>

| Campo                    | Descrição                                                 |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a id="UC44"></a>UC44     | Visualizar Comentários Relevantes                                |
| Descrição                | Permitir ao usuário visualizar primeiro os comentários que o sistema classifica automaticamente como os mais "relevantes", com base em critérios como utilidade e palavras-chave.                                                           |
| Ator                     | Usuário do aplicativo GDF Saúde    |
| Pré-condições            | Usuário está na seção de avaliações de uma clínica que possui múltiplos comentários. |
| Ação                     | Usuário abre a lista de comentários de um profissional ou clínica. |
| Fluxo principal          | - Usuário acessa a aba de "Avaliações" de uma clínica. <br>- A lista de comentários é carregada. <br>- O sistema, por padrão, exibe no topo os comentários que foram identificados como os mais relevantes.                                      |
| Fluxo alternativo        | - O usuário prefere ver os comentários mais recentes. <br>- O usuário seleciona a opção de ordenação "Mais Recentes". <br>- O sistema recarrega a lista, exibindo os comentários em ordem cronológica decrescente.                             |
| Fluxo de exceção         | - A clínica não possui comentários suficientes para que a classificação por relevância seja significativa. <br>- O sistema exibe todos os comentários disponíveis, ordenados por data como padrão alternativo.                                |
| Pós-condições            | O usuário tem acesso rápido às opiniões consideradas mais úteis, otimizando seu tempo de análise. |
| Rastreabilidade          | [RF02.3](../../elicitacao/requisitos_finais.md#RF02.3)  |
| Data de criação          | 12/06/2025   |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>


## Referência Bibliográfica

DevMedia. *O que é UML e Diagramas de Caso de Uso: Introdução Prática à UML*. 2012. Disponível em: https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408. Acessado em 25 mai. de 2025


Lucid Software Português. *Tutorial de Caso de Uso UML*. Youtube, 25 abr. 2019. Disponível em: https://youtu.be/ab6eDdwS3rA?si=rWAOOakqyrtqkKng. Accesso em 25 mai. 2025.


---

## Histórico de Versões

| Versão | Data       | Descrição            | Autor(es)                                       | Revisor(es)                                 |
| ------ | ---------- | -------------------- | ----------------------------------------------- | ------------------------------------------- |
| `1.0` | 15/05/2025  | Criação do documento | [Yzabella Miranda](https://github.com/redjsun) e [Isaque Camargos](https://github.com/isaqzin)| [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) |
| `1.1` | 15/05/2025  | Adição dos casos de usos referentes aos requisitos funcionais 3, 4 e 19 e dos requisitos não funcionais 4, 5 e 6 | [Isaque Camargos](https://github.com/isaqzin) | [Lucas Alves](https://github.com/LucasAlves71) |
|`1.2`  | 15/05/2025  | Adição dos casos de usos referentes aos requisitos funcionais 9, 10 e 20 e dos requisitos não funcionais 11 e 12 | [Matheus de Alcântara](https://github.com/matheusdealcantara) |[Isaque Camargos](https://github.com/isaqzin) |
|`1.3`  | 17/05/2025  | Adição dos casos de usos referentes aos requisitos funcionais 1, 2 e 21 e dos requisitos não funcionais 1, 2 e 3 | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) | [Kaleb Macedo](https://github.com/kalebmacedo) |
|`1.4`  | 17/05/2025  | Adição dos casos de usos referentes aos requisitos funcionais 5, 6 e 17 e dos requisitos não funcionais 7 e 8 | [Kaleb Macedo](https://github.com/kalebmacedo) | [Matheus de Alcântara](https://github.com/matheusdealcantara) |
|`1.5`  | 17/05/2025  | Adição dos casos de usos referentes aos requisitos funcionais 7, 8 e 18 e dos requisitos não funcionais 9 e 10 | [Lucas Alves](https://github.com/LucasAlves71) | [Yzabella Miranda](https://github.com/redjsun) |
|`1.6`  | 17/05/2025  | Adição dos casos de usos referentes aos requisitos funcionais 11 e 12 e dos requisitos não funcionais 13 e 14 | [Othavio Bolzan](https://github.com/bolzanMGB) | [Kaleb Macedo](https://github.com/kalebmacedo) |
|`1.7`  | 17/05/2025  | Adição dos casos de usos referentes aos requisitos funcionais 13, 14 e 15 e dos requisitos não funcionais 15 | [Yzabella Miranda](https://github.com/redjsun) |[Othavio Bolzan](https://github.com/bolzanMGB) |
|`1.8`  | 08/06/2025  | Adição de ancoras | [Isaque Camargos](https://github.com/isaqzin) | [Lucas Alves](https://github.com/LucasAlves71) |
|`1.9`  | 17/05/2025  | Retirando o diagrama de caso de uso referente aos requisitos funcionais da Ana| [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) | [Kaleb Macedo](https://github.com/kalebmacedo) |
|`2.0`  | 11/06/2025  | Corrigi os meus cenários, retirando as especificações e diagrama dos casos de uso de requisitos não funcionais e criando casos de uso para os requisitos: RF01.1, RF01.2, RF01.3, RF01.4, RF01.5, RF02.1, RF02.2 e RF02.3 .  | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) | [Matheus de Alcântara](https://github.com/matheusdealcantara) |

