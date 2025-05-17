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
## Descrição casos de uso 

### UC01 – Filtrar redes credenciadas

<p align="center">Tabela 2 - Caso de Uso 1 </p>

| Campo              | Descrição                                                                                                                                       |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| UC01                 |Filtrar redes credenciadas                                                                                                               |
| Descrição          | Permitir ao usuário buscar clínicas/profissionais do INAS buscando pelo nome ou por meio de filtros como especialidade, região, tipo de atendimento e proximidade. |
| Ator               | Usuário do aplicativo GDF Saúde                                                                                                                 |
| Pré-condições      | 1. Conexão com internet. <br>2. Usuário é beneficiário do Plano INAS <br>3. Usuário realizou o cadastro no GDF Saúde                           |
| Ação               | Usuário aplica os filtros que ele deseja e/ou busca pelo nome da rede credenciada.                                                             |
| Fluxo principal    | - Usuário abre o aplicativo <br>- Usuário abre a aba de redes credenciadas <br>- Usuário seleciona filtros ou busca por uma rede credenciada <br>- Sistema exibe lista de redes credenciadas correspondentes. |
| Fluxo alternativo  | - Usuário abre o aplicativo <br>- Usuário abre a aba de redes credenciadas <br>- Usuário não filtra e nem busca pela rede credenciada <br>- São listadas aleatoriamente todas as redes credenciadas |
| Fluxo de exceção   | - Usuário abre o aplicativo <br>- Usuário abre a aba de redes credenciadas <br>- Usuário seleciona filtros ou busca por uma rede credenciada <br>- Não aparece nenhuma rede credenciada correspondente |
| Pós-condições      | Lista de redes filtradas é exibida com dados (endereço, telefone, horário).                                                                    |
| Rastreabilidade    | [RF01]()                                                                                                                                       |
| Data de criação    | 17/05/2025                                                                                                                                     |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

---

### UC02 – Acessar avaliações das redes credenciadas

<p align="center">Tabela 3 - Caso de Uso 2 </p>

| Campo              | Descrição                                                                                                                                       |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| UC02                 |Acessar avaliações das redes credenciadas                                                                                                |
| Descrição          | Permitir ao usuário visualizar e dar notas e comentários sobre as redes credenciadas.                                                          |
| Ator               | Usuário do aplicativo GDF Saúde                                                                                                                 |
| Pré-condições      | 1. Conexão com internet. <br>2. Usuário é beneficiário do Plano INAS <br>3. Usuário realizou o cadastro no GDF Saúde                           |
| Ação               | Usuário acessa a seção "Avaliações" da rede desejada.                                                                                           |
| Fluxo principal    | - Usuário abre o aplicativo <br>- Usuário abre a aba de "Avaliações" <br>- Usuário seleciona filtros ou busca por uma rede credenciada <br>- Sistema exibe as avaliações disponíveis referentes à rede credenciada <br>- O usuário pode avaliar o atendimento |
| Fluxo alternativo  | - Usuário abre o aplicativo <br>- Usuário abre a aba de "Avaliações" <br>- Não filtra e nem busca pela rede credenciada <br>- Sistema exibe as avaliações disponíveis referentes à rede credenciada <br>- O usuário pode avaliar o atendimento |
| Fluxo de exceção   | - Usuário abre o aplicativo <br>- Usuário abre a aba de "Avaliações" <br>- Usuário seleciona filtros ou busca por uma rede credenciada <br>- Não aparece nenhuma rede credenciada correspondente |
| Pós-condições      | Avaliações são exibidas ou opção de registrar nova avaliação.                                                                                  |
| Rastreabilidade    | [RF02]()                                                                                                                                       |
| Data de criação    | 17/05/2025                                                                                                                                     |

<p align="center">Fonte: Autoria de <a src="https://github.com/Ana-Luiza-SC" targe="_blank">Ana Luiza Soares</a></p>

---

### UC03 – Iniciar conversa com chatbot de triagem

<p align="center">Tabela 4 - Caso de Uso 3 </p>

| Campo              | Descrição                                                                                                                                       |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| UC03                 |Iniciar conversa com chatbot de triagem                                                                                                  |
| Descrição          | Permitir ao usuário interagir com chatbot para identificar especialidade médica adequada                                                       |
| Ator               | Usuário do aplicativo GDF Saúde                                                                                                                 |
| Pré-condições      | 1. Conexão com internet. <br>2. Usuário é beneficiário do Plano INAS                                                                            |
| Ação               | Usuário inicia conversa e descreve sintomas                                                                                                     |
| Fluxo principal    | - Usuário abre o aplicativo <br>- Usuário seleciona a opção "Chatbot de Saúde" <br>- Sistema exibe tela inicial do chatbot <br>- Usuário descreve sintomas <br>- Chatbot analisa e sugere especialidade médica <br>- Sistema pede confirmação ao usuário posteriormente para análise de desempenho |
| Fluxo alternativo  | - Usuário abre o aplicativo <br>- Usuário seleciona a opção "Chatbot de Saúde" <br>- Sistema exibe tela inicial do chatbot <br>- Usuário tem dúvidas ou fornece informações vagas <br>- Chatbot recomenda buscar hospital para melhor triagem |
| Fluxo de exceção   | - Usuário abre o aplicativo <br>- Usuário seleciona a opção "Chatbot de Saúde" <br>- Inicia a conversa <br>- Chatbot redireciona para especialidade médica incorreta |
| Pós-condições      | Especialidade médica identificada corretamente e confirmado o desempenho do chatbot posteriormente                                              |
| Rastreabilidade    | [RF21]()                                                                                                                                       |
| Data de criação    | 17/05/2025                                                                                                                                     |

<p align="center">Fonte: Autoria de <a src="https://github.com/Ana-Luiza-SC" targe="_blank">Ana Luiza Soares</a></p>

---

### UC04 – Acessar sistema com facilidade

<p align="center">Tabela 5 - Caso de Uso 4 </p>

| Campo              | Descrição                                                                                                                                       |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| UC04                 | Acessar sistema com facilidade                                                                                                           |
| Descrição          | Garantir interface intuitiva e acessível para todos os usuários                                                                                 |
| Ator               | Usuário do aplicativo GDF Saúde                                                                                                                 |
| Pré-condições      | 1. Conexão com internet <br>2. Usuário é beneficiário do Plano INAS <br>3. Aplicativo instalado no dispositivo                                  |
| Ação               | Usuário abre o aplicativo e navega pelas funcionalidades com facilidade                                                                         |
| Fluxo principal    | - Usuário abre o aplicativo <br>- Sistema carrega tela inicial em até 2 segundos <br>- Menu principal com ícones intuitivos é exibido <br>- Usuário navega entre as opções sem dificuldades |
| Fluxo alternativo  | - Usuário abre o aplicativo <br>- Tem dificuldade com alguma funcionalidade <br>- Sistema oferece opção "Ajuda" <br>- Usuário acessa tutorial integrado |
| Fluxo de exceção   | - Usuário abre o aplicativo <br>- Não consegue acessar as funcionalidades <br>- Não consegue acessar os tutoriais <br>- Não fica satisfeito com o aplicativo |
| Pós-condições      | Acesso às funcionalidades realizado com sucesso OU tutorial consultado para solução de dúvidas suficiente                                       |
| Rastreabilidade    | [RNF01]()                                                                                                                                      |
| Data de criação    | 17/05/2025                                                                                                                                     |

<p align="center">Fonte: Autoria de <a src="https://github.com/Ana-Luiza-SC" targe="_blank">Ana Luiza Soares</a></p>

---

### UC05 – Garantir desempenho do sistema

<p align="center">Tabela 6 - Caso de Uso 5 </p>

| Campo              | Descrição                                                                                                                                       |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| UC05                 | Garantir desempenho do sistema                                                                                                           |
| Descrição          | Assegurar que todas as funcionalidades respondam em até 2 segundos                                                                             |
| Ator               | Usuário do aplicativo GDF Saúde                                                                                                                 |
| Pré-condições      | 1. Conexão estável com internet <br>2. Usuário é beneficiário do Plano INAS <br>3. Aplicativo atualizado                                       |
| Ação               | Usuário interage com as funcionalidades do aplicativo                                                                                           |
| Fluxo principal    | - Usuário seleciona qualquer funcionalidade <br>- Sistema processa a requisição <br>- Resposta é exibida em até 2 segundos                      |
| Fluxo alternativo  | - Usuário seleciona funcionalidade <br>- Tempo excede 2 segundos <br>- Sistema exibe ícone de carregamento <br>- Completa ação em até 5 segundos |
| Fluxo de exceção   | - Usuário seleciona funcionalidade <br>- Sistema não responde após 5 segundos <br>- Exibe mensagem "Problema de conexão"                        |
| Pós-condições      | Funcionalidade acessada dentro do tempo esperado                                                                                                |
| Rastreabilidade    | [RNF02]()                                                                                                                                      |
| Data de criação    | 17/05/2025                                                                                                                                     |

<p align="center">Fonte: Autoria de <a src="https://github.com/Ana-Luiza-SC" targe="_blank">Ana Luiza Soares</a></p>

---

### UC06 – Garantir segurança no uso do sistema

<p align="center">Tabela 7 - Caso de Uso 6 </p>

| Campo              | Descrição                                                                                                                                       |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| UC06                 | Garantir segurança no uso do sistema                                                                                                     |
| Descrição          | Assegurar acesso seguro às funcionalidades com proteção de dados e conformidade LGPD                                                           |
| Ator               | Usuário do aplicativo GDF Saúde                                                                                                                 |
| Pré-condições      | 1. Conexão segura (HTTPS) <br>2. Usuário cadastrado no INAS <br>3. Dispositivo compatível                                                       |
| Ação               | Usuário realiza autenticação para acessar o sistema                                                                                             |
| Fluxo principal    | - Usuário insere credenciais <br>- Sistema solicita segundo fator de autenticação <br>- Validação bem-sucedida <br>- Acesso concedido com criptografia de dados |
| Fluxo alternativo  | - Usuário falha na autenticação <br>- Sistema oferece: "Recuperar acesso" ou "Tentar novamente" <br>- Redireciona para fluxo de recuperação    |
| Fluxo de exceção   | - Múltiplas tentativas falhas <br>- Sistema bloqueia acesso temporariamente <br>- Notifica ANPD em caso de violação de dados <br>- Envia alerta para o usuário |
| Pós-condições      | Acesso seguro concedido                                                                                                                         |
| Rastreabilidade    | [RNF03]()                                                                                                                                      |
| Data de criação    | 17/05/2025                                                                                                                                     |

<p align="center">Fonte: Autoria de <a src="https://github.com/Ana-Luiza-SC" targe="_blank">Ana Luiza Soares</a></p>

---

## ISAQUE
### UC07 – Fazer login
<p align="center">Tabela 8 - Caso de Uso 7 </p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
|UC07            |  Fazer login                                                        |
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

<p align="center">Fonte: Autoria de <a src="https://github.com/isaqzin" targe="_blank">Isaque Camargos</a></p>
---

### UC08 – Login por biometria
<p align="center">Tabela 9 - Caso de Uso 8 </p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| UC08                 |  Login por biometria                                                |
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

### UC09 – Baixar carteirinha

<p align="center">Tabela 10 - Caso de Uso 9 </p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| UC09                 | Baixar carteirinha                                                 |
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

<p align="center">Fonte: Autoria de <a src="https://github.com/isaqzin" targe="_blank">Isaque Camargos</a></p>

---

### UC10 – Configurar notificações
<p align="center">Tabela 11 - Caso de Uso 10 </p>

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| UC10                 |  Configurar notificações                                            |
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

<p align="center">Fonte: Autoria de <a src="https://github.com/isaqzin" targe="_blank">Isaque Camargos</a></p>

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

<p align="center">Fonte: Autoria de <a src="https://github.com/isaqzin" targe="_blank">Isaque Camargos</a></p>

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

<p align="center">Fonte: Autoria de <a src="https://github.com/isaqzin" targe="_blank">Isaque Camargos</a></p>

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