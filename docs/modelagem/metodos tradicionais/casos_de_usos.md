# Diagrama e Especificação de Casos de Uso

## introdução 

jhasdbakjcnakjadncaakjcnaackjnakjcnakchaca

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
					<td>Criou o diagrama referentes aos requisitos: RFXX,RFXX, RFXX e RNFXX . Criou as especificações dos casos de uso referente a estes requisitos, sendo eles  UC0x, UC0x, UC0x,  UC0x, UC0x e UC0x. </td>	
				</tr>
				<tr>
					<td><a  href="https://github.com/isaqzin">Isaque Camargos</a></td>
					<td>Criou o diagrama referentes aos requisitos: RF03,RF04, RF19, RNF04,  RNF05 e  RNF06 . Criou as especificações dos casos de uso referente a estes requisitos, sendo eles  UC01, UC02, UC03,  UC04, UC05 e UC06. Além disso, criou o documento inicial. </td>	
				</tr>
				<tr>
					<td><a  href="https://github.com/kalebmacedo">Kaleb Macedo</a></td>
					<td>Criou o diagrama referentes aos requisitos: RFXX,RFXX, RFXX e RNFXX . Criou as especificações dos casos de uso referente a estes requisitos, sendo eles  UC0x, UC0x, UC0x,  UC0x, UC0x e UC0x. </td>	
				</tr>
				<tr>
					<td><a  href="https://github.com/LucasAlves71">Lucas Alves</a></td>
					<td>Criou o diagrama referentes aos requisitos: RFXX,RFXX, RFXX e RNFXX . Criou as especificações dos casos de uso referente a estes requisitos, sendo eles  UC0x, UC0x, UC0x,  UC0x, UC0x e UC0x. </td>	
				</tr>
				<tr>
					<td><a  href="https://github.com/matheusdealcantara">Matheus de Alcântara</a></td>
					<td>Criou o diagrama referentes aos requisitos: RFXX,RFXX, RFXX e RNFXX . Criou as especificações dos casos de uso referente a estes requisitos, sendo eles  UC0x, UC0x, UC0x,  UC0x, UC0x e UC0x. </td>	
				</tr>
				<tr>
					<td><a  href="https://github.com/bolzanMGB">Othavio Bolzan</a></td>
					<td>Criou o diagrama referentes aos requisitos: RFXX,RFXX, RFXX e RNFXX . Criou as especificações dos casos de uso referente a estes requisitos, sendo eles  UC0x, UC0x, UC0x,  UC0x, UC0x e UC0x. </td>	
				</tr>
				<tr>
					<td><a  href="https://github.com/redjsun">Yzabella Miranda</a></td>
					<td>Criou o diagrama referentes aos requisitos: RF13,RF14, RF15 e RNF015 . Criou as especificações dos casos de uso referente a estes requisitos, sendo eles  UC0x, UC0x, UC0x,  UC0x, UC0x e UC0x. </td>	
				</tr>
		</tbody>
	</table>
</div>  

<p  align="center">Fonte: Autoria de <a  href="https://github.com/isaqzin">Isaque Camargos</a> e <a  href="https://github.com/isaqzin">Yzabella Miranda</a></p>

## Metodologia 
vou fazer já já (yza)


## Diagramas de Casos de Uso 

Colocar legenda para os casos de uso 

analisar grupos antigos para ver se tem algo faltando

### Diagrama Casos de Uso Isaque 

colocar foto e breve descrição (rastreavel) dos requisitos que foram trabalhados aqui

### COLOCAR A FOTO DO SEU DIAGRAMA DE CASOS DE USO, somente no repositorio mesmo, EM ORDEM DE QUE VAI COLOCAR OS UC's 
 
## ANA

## ISAQUE
### UC01 – Fazer login

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
|UC01            |  Fazer login                                                        |
| Descrição          | Permitir que o usuário acesse o app com e-mail/CPF e senha.               |
| Ator               | Usuário cadastrado                                                        |
| Pré-condições      | App instalado e com conexão à internet.                                   |
| Ação               | O usuário preenche e-mail/CPF e senha e confirma para entrar.             |
| Fluxo principal    | - O usuário acessa a tela de login.<br>- Insere e-mail/CPF e senha.<br>- O sistema valida os dados.<br>- O usuário é autenticado. |
| Fluxo alternativo  | - Credenciais inválidas: sistema exibe mensagem de erro.                  |
| Fluxo de exceção   | - Ausência de conexão: sistema informa que não é possível conectar.       |
| Pós-condições      | Usuário autenticado e apto a usar o aplicativo.                           |
| Rastreabilidade    |                                                                           |
| Data de criação    | 15/05/2025                                                                |

---

### UC02 – Login por biometria

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| UC02                 |  Login por biometria                                                |
| Descrição          | Permitir login via impressão digital ou reconhecimento facial.            |
| Ator               | Usuário cadastrado                                                        |
| Pré-condições      | Dispositivo com sensor biométrico, usuário já logado ao menos uma vez.    |
| Ação               | O usuário seleciona "Entrar por biometria" e realiza autenticação.         |
| Fluxo principal    | - O usuário abre o app.<br>- Seleciona “Entrar com biometria”.<br>- Biometria é validada pelo sistema operacional.<br>- O usuário é autenticado. |
| Fluxo alternativo  | - Biometria não reconhecida: sistema oferece login por senha.             |
| Fluxo de exceção   | - Sensor indisponível: app informa erro e redireciona para login comum.   |
| Pós-condições      | Usuário autenticado via biometria ou direcionado para login manual.       |
| Rastreabilidade    |                                                                           |
| Data de criação    | 15/05/2025                                                                |

---

### UC03 – Baixar carteirinha

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| UC03                 | Baixar carteirinha                                                 |
| Descrição          | Permitir download da carteirinha digital para uso offline.                |
| Ator               | Usuário autenticado                                                       |
| Pré-condições      | Conexão com internet e usuário logado.                                    |
| Ação               | O usuário solicita o download da carteirinha.                             |
| Fluxo principal    | - O usuário acessa a seção “Carteirinha”.<br>- Clica em “Baixar”.<br>- O sistema realiza o download.<br>- A carteirinha é salva no dispositivo. |
| Fluxo alternativo  | - Caso já tenha sido baixada, o sistema permite rebaixar.                 |
| Fluxo de exceção   | - Falta de conexão ou falha no armazenamento: erro informado ao usuário.  |
| Pós-condições      | Carteirinha disponível localmente mesmo sem internet.                     |
| Rastreabilidade    |                                                                           |
| Data de criação    | 15/05/2025                                                                |

---

### UC04 – Configurar notificações

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| UC04 –                 |  Configurar notificações                                            |
| Descrição          | Permitir ao usuário selecionar tipos e canais de notificações.            |
| Ator               | Usuário autenticado                                                       |
| Pré-condições      | Login realizado com sucesso.                                              |
| Ação               | O usuário acessa as configurações de notificação e define suas preferências. |
| Fluxo principal    | - O usuário acessa “Configurações”.<br>- Escolhe os tipos e canais desejados.<br>- Salva as alterações.<br>- Preferências são persistidas pelo sistema. |
| Fluxo alternativo  | —                                                                         |
| Fluxo de exceção   | - sistema exibe erro ao tentar salvar.                      |
| Pós-condições      | Preferências de notificação atualizadas.                                  |
| Rastreabilidade    |                                                                           |
| Data de criação    | 15/05/2025                                                                |

---

### UC05 – Enviar notificações

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| UC05                 |  Enviar notificações                                                |
| Descrição          | Enviar notificações com base nas preferências do usuário.                 |
| Ator               | Serviços de notificação                                 |
| Pré-condições      | Configurações de notificação existentes e evento ativador.                |
| Ação               | O sistema identifica evento e envia a notificação pelo canal configurado. |
| Fluxo principal    | - Evento ocorre (ex: consulta cancelada).<br>- Preferências são consultadas.<br>- Sistema envia via canal apropriado(e-mail, SMS e/ou notificação do próprio app).<br>- Envio é registrado. |
| Fluxo alternativo  | - Falha de envio: sistema realiza tentativa posterior.                    |
| Fluxo de exceção   | - Falha permanente: log de erro registrado, equipe notificada.            |
| Pós-condições      | Notificação enviada ou tentativa registrada para análise.                 |
| Rastreabilidade    |                                                                           |
| Data de criação    | 15/05/2025                                                                |

---

### UC06 – Solicitar autorização de urgência/emergência

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| UC06                 |  Solicitar autorização de urgência/emergência                      |
| Descrição          | Permitir que profissionais de saúde solicitem autorização em tempo real. |
| Ator               | Profissional de saúde e INAS                                   |
| Pré-condições      | Sistema disponível e login realizado.                                     |
| Ação               | Profissional preenche dados e solicita autorização imediata.              |
| Fluxo principal    | - Profissional acessa funcionalidade.<br>- Informa dados do paciente.<br>- Sistema ou o INAS valida e aprova.<br>- Autorização emitida. |
| Fluxo alternativo  | - Dados incompletos: sistema solicita complementação.                     |
| Fluxo de exceção   | - Sistema fora do ar: notifica falha e orienta alternativa.               |
| Pós-condições      | Autorização registrada, atendimento liberado.                             |
| Rastreabilidade    |                                                                           |
| Data de criação    | 15/05/2025                                                                |

---



## KALEB

## LUCAS

## MATHEUS

## OTHAVIO

## YZA


## Histórico de Versões

| Versão | Data       | Descrição            | Autor(es)                                       | Revisor(es)                                 |
| ------ | ---------- | -------------------- | ----------------------------------------------- | ------------------------------------------- |
| `1.0` | 15/05/2025  | Criação do documento | [Yzabella Miranda](https://github.com/redjsun) | [Isaque Camargos](https://github.com/isaqzin) |