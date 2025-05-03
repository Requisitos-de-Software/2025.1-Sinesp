# Questionário de Perfil de Usuário - Aplicativo GDF-Saúde

## Introdução

O presente relatório tem como objetivo apresentar uma análise detalhada do perfil dos usuários do aplicativo **GDF-Saúde**. Trata-se de uma iniciativa que visa compreender melhor o uso do aplicativo, os problemas enfrentados, as expectativas dos usuários, além de levantar oportunidades de melhoria baseadas em dados reais. O estudo é parte integrante do processo de elicitação de requisitos do sistema.

Ao entender a vivência dos beneficiários com o aplicativo, é possível estabelecer critérios mais claros para evoluções no produto, alinhando a solução tecnológica às reais necessidades da população usuária do plano de saúde.

---

## Metodologia

Para este estudo foi utilizada uma **técnica de coleta quantitativa**, estruturada por meio de um questionário eletrônico. A metodologia foi orientada pelos seguintes princípios:

- **Instrumento de Coleta**:  
  Foi utilizado o **Google Forms**, permitindo a coleta de dados de forma ágil, segura e anônima. O formulário respeitou integralmente os princípios da **LGPD – Lei Geral de Proteção de Dados (Lei 13.709/2018)**.

- **Composição do Questionário**:  
  O questionário foi composto por perguntas **fechadas** (de múltipla escolha ou escala) e **abertas** (respostas discursivas), abordando temas como:
  - Perfil demográfico
  - Frequência e finalidade de uso
  - Funcionalidades mais relevantes
  - Problemas encontrados no uso do app
  - Nível de satisfação e confiabilidade
  - Sugestões, elogios e críticas

- **Público-Alvo e Amostragem**:  
  O questionário foi direcionado a usuários e não usuários do aplicativo GDF-Saúde, beneficiários do plano oferecido pelo **Instituto de Assistência à Saúde dos Servidores do GDF (INAS)**.

- **Divulgação e Coleta**:  
  A aplicação do questionário foi realizada, por meio dos seguintes canais:
  - Grupos de WhatsApp com servidores públicos usuários do INAS
  - Divulgação espontânea em redes de contato pessoal e profissional dos autores
  - Compartilhamento direto com colegas de trabalho, familiares e membros da administração pública

---

## Objetivo  
Este relatório tem como finalidade analisar em profundidade as respostas obtidas por meio do questionário aplicado a usuários e não usuários do aplicativo GDF-Saúde. Busca-se identificar perfis de uso, principais dificuldades enfrentadas, funcionalidades valorizadas, bem como oportunidades de melhoria a partir da experiência real dos respondentes.

---

## Requisitos Elicitados
As tabelas 1 e 2 listadas a seguir contém os requisitos que foram elicitados durante a realização desta técnica de elicitação de requisitos.

## Requisitos Funcionais

| ID   | Descrição                                                                                                  | Tipo | Implementado |
|------|------------------------------------------------------------------------------------------------------------|------|--------------|
| <a id="QT01"></a>QT01 | Permitir acesso rápido e estável à carteirinha digital                                                    | [RF03](../../elicitacao/elicitacao.md#RF03)   | Sim          |
| <a id="QT02"></a>QT02 | Exibir extrato financeiro atualizado diariamente                                                          | [RF06](../../elicitacao/elicitacao.md#RF06)   | Não          |
| <a id="QT03"></a>QT03 | Listar rede credenciada com filtro por região, especialidade e tipo de atendimento                        | [RF01](../../elicitacao/elicitacao.md#RF01)   | Sim          |
| <a id="QT04"></a>QT04 | Mostrar histórico de consultas, exames e coparticipações                                                  | [RF09](../../elicitacao/elicitacao.md#RF09)   | Sim          |
| <a id="QT05"></a>QT05 | Permitir visualização dos valores a serem cobrados no mês                                                | [RF06](../../elicitacao/elicitacao.md#RF06)   | Sim          |
| <a id="QT06"></a>QT06 | Habilitar notificações personalizadas por tipo (importantes, lembretes etc.)                             | [RF04](../../elicitacao/elicitacao.md#RF04)   | Não         |
| <a id="QT07"></a>QT07 | Adicionar consulta à rede odontológica                                                                    | [RF13](../../elicitacao/elicitacao.md#RF13)   | Sim          |
| <a id="QT08"></a>QT08 | Oferecer ferramenta de busca por especialidade em determinada localidade                                 | [RF01](../../elicitacao/elicitacao.md#RF01)   | Sim          |
| <a id="QT09"></a>QT09 | Visualizar status de autorizações e solicitações médicas em tempo real                                   | [RF08](../../elicitacao/elicitacao.md#RF08)   | Sim          |


---

## Requisitos Não Funcionais

| ID    | Descrição                                                                                                 | Tipo  | Implementado |
|-------|-----------------------------------------------------------------------------------------------------------|-------|--------------|
| <a id="QT10"></a>QT10  | O aplicativo deve apresentar **alta disponibilidade** (mínimo de 99% uptime)                             | [RNF04](../../elicitacao/elicitacao.md#RNF04)   | Não          |
| <a id="QT11"></a>QT11  | A interface deve ser **intuitiva, acessível e responsiva** em smartphones Android e iOS                 | [RNF05](../../elicitacao/elicitacao.md#RNF05)   | Sim          |
| <a id="QT12"></a>QT12  | O tempo de resposta das ações não deve ultrapassar 2 segundos                                            | [RNF02](../../elicitacao/elicitacao.md#RNF02)   | Não          |
| <a id="QT13"></a>QT13  | As informações exibidas devem ser **claras, completas e atualizadas em tempo real**                     | [RNF16](../../elicitacao/elicitacao.md#RNF16)   | Sim          |
| <a id="QT14"></a>QT14  | O app deve ser compatível com leitores de tela (acessibilidade digital)                                  | [RNF06](../../elicitacao/elicitacao.md#RNF06)   | Não          |
| <a id="QT15"></a>QT15  | A segurança das informações do usuário deve seguir os padrões da LGPD                                    | [RNF03](../../elicitacao/elicitacao.md#RNF03)   | Sim          |
| <a id="QT16"></a>QT16  | O layout deve ser consistente com o portal oficial do plano                                              | [RNF14](../../elicitacao/elicitacao.md#RNF14)   | Não          |



---
## INAS

### Utiliza
- Majoritariamente usam
- Apenas poucos não utilizam

<p align="center"><strong>Figura 1 da Utilização</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\inas.png" alt="10" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### Já Utilizou?
- Grande maioria sim

<p align="center"><strong>Figura 2 Utilização </strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\ja-utilizou.png" alt="10" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

## 1. Perfil Demográfico dos Participantes

### 1.1 Faixa Etária
As faixas etárias mais recorrentes entre os respondentes são:
- 45–54 anos
- 55–64 anos
- Seguida de 18–24 anos e 65 anos ou mais

<p align="center"><strong>Figura 1: Faixa Etária</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\01.png" alt="01" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>


### 1.2 Gênero
- Feminino: maioria absoluta dos respondentes
- Masculino: minoria, embora presente em todas as faixas etárias

<p align="center"><strong>Figura 2: Gênero</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\02.png" alt="02" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### 1.3 Região Administrativa
As regiões mais citadas incluem:
- Ceilândia
- Taguatinga
- Águas Claras
- Plano Piloto
- Vicente Pires
- Samambaia

<p align="center"><strong>Figura 3: Região Administrativa</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\03.png" alt="03" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### 1.4 Escolaridade
- Predominância de respondentes com pós-graduação ou ensino superior completo
- Pequena parcela com ensino médio completo/incompleto

<p align="center"><strong>Figura 4: Escolaridade</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\04.png" alt="04" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### 1.5 Ocupação
- Educação e Saúde são as áreas mais comuns
- Estudantes também têm presença significativa

<p align="center"><strong>Figura 5: Ocupação</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\05.png" alt="05" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### 1.6 Outro Plano
- Quase unanimidade são os que dizem não
- Poucos respondentes afirmam que usam outro plano fora o INAS

<p align="center"><strong>Figura 6: Outro Plano</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\06.png" alt="06" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### 1.7 Titular ou Dependente
- Quase unanimidade são titulares
- Poucos respondentes afirmam que são dependentes

<p align="center"><strong>Figura 7: Titular ou Dependente</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\07.png" alt="07" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### 1.8 Dependentes
- Muitos afirmam que têm apenas 1 dependente  
- Poucos respondentes afirmam que 2
- Nenhum afirmou mais que 2 dependentes

<p align="center"><strong>Figura 8: Dependentes</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\08.png" alt="08" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

---

## 2. Uso e Frequência do Aplicativo

### 2.1 Frequência de Uso
- A maioria relata utilizar o aplicativo **raramente** ou **algumas vezes por semana**
- Menor parte afirma uso **diário** ou **sempre**

<p align="center"><strong>Figura 9: Frequência de Uso</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\09.png" alt="09" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### 2.2 Finalidades Mais Comuns
As principais funcionalidades acessadas foram:
- Análise da rede credenciada
- Visualização de exames
- Acesso à carteirinha digital
- Consultas e extratos financeiros
- Acesso às orientações de saúde

<p align="center"><strong>Figura 10: Finalidades Mais Comuns</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\10.png" alt="10" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### 2.3 Funcionalidades Mais Importantes
As principais respostas foram:
- Análise da rede e visualização de exames
- Nem sempre consigo ver a rede credenciada.
- Extrato financeiro
- Fraco este apliicativo
- Ver o histórico de consultas.
- Gostaria que o app tivesse mais clareza nas suas informações
- Acho o aplicativo pessimo
- Pesquisar clínicas.
- Ver o valor a ser cobrado no mês
- Saber gastos
- Valores da Coparticipação
- Extrato dos procedimentos
- Extrato de utilização atualizado diariamente
- Nenhuma.
- Consultas e exames

---

## 3. Avaliação da Experiência do Usuário

### 3.1 Erros e Travamentos
- A maioria avaliou que apresenta frequentemente
- Parte afirma que sempre
- Alguns casos dizem que raramente
- Poucos dizem que nunca

<p align="center"><strong>Figura 11: Erros e Travamentos </strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\12.png" alt="11" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### 3.2 Escala de Facilidade de Uso (1 a 5)
- A maioria avaliou com notas entre **2 e 4**
- Poucos atribuíram nota máxima (5)
- Casos extremos com nota 1 revelam problemas críticos

<p align="center"><strong>Figura 12: Escala de Facilidade</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\13.png" alt="12" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### 3.2 Problemas Identificados
Aos que afirmaram sim a esta pergunta, as mais frequêntes são:
- Travamentos constantes e lentidão
- Aplicativo que não abre ou fecha sozinho
- Ausência ou atraso no extrato financeiro e coparticipação
- Falta de informações claras e atualizadas
- Dificuldade de navegação e busca por especialidades

<p align="center"><strong>Figura 13: Problemas Identificados</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\14.png" alt="13" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

---

## 4. Necessidades e Expectativas

### 4.1 Atendimento das Expectativas
- Em sua maioria, os participantes relataram que o aplicativo **atende parcialmente** às expectativas
- Poucos relataram atendimento pleno

<p align="center"><strong>Figura 14: Expectativa</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\15.png" alt="10" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### 4.2 Atendimento das Necessidades de Saúde
- A maior parte relatou que **não atende completamente** suas necessidades
- Problemas de funcionalidade têm impacto direto nessa percepção

<p align="center"><strong>Figura 15: Finalidades Mais Comuns</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\16.png" alt="10" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### 4.3 Adição de Funcionalidade
As respostas foram:
- Avaliação de hospitais da rede credenciada
- Incluir atendimento odontológico
- Que abra com facilidade
- Rede credenciada é extrato financeiro atual
- Visualizar os valores de cada serviço
- Ter todos os extratos dos seus gastos
- Acesso ao extrato detalhado das cobranças e um outro guia que permita a negociação dos pagamentos da coparticipação.
- Mostrar as funcionalidades igual no site
- Acessibilidade as informações
- As solicitações ficam em analise, por muito tempo, e isso torna o tratamento bem demorado. Deveriam melhorar isso
- Localização de especialidade que realmente atende pelo plano, realizei busca pela especialidade no contato com a clinica ela nao dispunha de profissional vinculada ao plano.
- Se ele funcionassem o básico estaria bom.
- Extrato de utilização atualizado diariamente
- Pesquisar por especialidade médica por região. Exemplo: Endocrinologista em Ceilândia.
- Mais redes credenciadas.

### 4.4 Percepção de Segurança
- A maioria afirma confiar no uso dos dados **somente em casos importantes**
- Sinaliza dúvidas quanto à segurança da informação pessoal e financeira

<p align="center"><strong>Figura 16: Segurança</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\18.png" alt="10" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### 4.5 Frequência de Notificações
- Grande parte colocou que gostaria somente em casos importantes
- Pequena variação entre os outros 

<p align="center"><strong>Figura 17: Frquência de Notificação</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\19.png" alt="10" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

---

## 5. Perfil e Comportamento Digital

### 5.1 Familiaridade
- Maioria afirma mediana
- Uma parte afirma allta familiaridade
- Alterna entre muito alto e baixo

<p align="center"><strong>Figura 18: Familiaridade</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\20.png" alt="10" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

### 5.2 Dispositivo de Costume
- A maioria afirma utilizar o smartphone para utilizar o INAS 
- Pequena parte usa no computador
- Ninguém utiliza em tablets

<p align="center"><strong>Figura 20: Dispositivo de Costume</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\21.png" alt="10" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

---

## 6. Comentários Finais 

### 6.1 O que mais gosta no app
As respostas mais frequêntes foram:
- Visualização da rede credenciada
- A facilidade de acompanhar os exames.
- Nada. Não consigo nem alterar senha
- Acesso a carteirinha
- Nada
- Que ele seja objetivo
- Neste momento sou indiferente.
- Encontrar a rede credenciada
- Não gosto
- Ajuda na procura das clínicas.
- A carteira de saúde digital
- Depois que mudou, tive bastante dificuldade pra saber minhas coparticipações
- Acesso facil
- Quando funciona
- Nada! O mesmo não funciona.
- nada
- Quase nada
- Pode acessar os dados do plano.
- Agilidade em me atender

### 6.2 O que menos gosta no app
As respostas foram:
- Tudo
- Problemas de desempenho
- Quando ele não funciona.
- A falta de desenvolvimento do aplicativo.
- Sempre desatualizado e confuso na questão financeira
- Não tem dados imediatos ,é lerdo
- O link para acesso às consultas realizadas não funciona.
- O acesso às informações quanto ao pagamento da coparticipação não existe.
- Não há como negociar o pagamento da coparticipação, como há em outros planos de saúde.
- Trava muito
- Facilidade nas informações
- A falta de acesso a boletos/histórico financeiro; rede credenciada desatualizada
- Tá sempre sem resultados quando solicitamos extratos, hoje consegui abrir.
- Acesso de dependentes separado do titular
- Quando não funciona
- App sem funcionalidade.
- tudo
- Pelo fato de não ter o extrato de utilização diário
- Há poucos médicos e clínicas credenciados que estão no aplicativo. Deveria aparecer mais profissionais, pois às vezes o médico atende ao plano, mas não aparece o nome no aplicativo. Então, preciso ligar em várias clínicas para confirmar se atendem ao plano.
- O credenciamento

---

## 7. Críticas, Sugestões e Elogios

### 7.1 Sugestões Frequentes
- Inclusão de atendimento odontológico
- Guia para localização de especialistas por região
- Interface mais intuitiva e objetiva
- Atualização em tempo real dos extratos financeiros e valores de coparticipação
- Disponibilização de funcionalidades presentes no site também no aplicativo

### 7.2 Críticas Repetidas
- "App não funciona"
- "Não consigo visualizar o que preciso"
- "Falta de informações claras"
- "Poucos médicos credenciados visíveis"
- "Nada funciona direito"

### 7.3 Elogios Pontuais
- Facilidade em acompanhar exames (quando funcional)
- Acesso rápido à carteirinha
- Ideia é útil, mas precisa de melhorias

---

## 8. Perfil dos Não Usuários

### Motivações Relatadas
- Nunca souberam da existência do aplicativo
- Falta de necessidade percebida
- Falta de interesse ou preferência por canais alternativos

<p align="center"><strong>Figura 21: Nunca Utilizou, motivos</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\Porque-nunca-utilizou.png" alt="10" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

---

## Conclusão
Os dados evidenciam que o aplicativo GDF-Saúde é conhecido e utilizado por boa parte dos beneficiários entrevistados, mas apresenta sérios desafios operacionais. A experiência do usuário é prejudicada por instabilidades, falta de clareza e não atendimento das funcionalidades esperadas. O engajamento ainda é baixo, refletindo na baixa frequência de uso.

---

## Recomendações

1. **Melhoria de performance e estabilidade**:
      - Reduzir travamentos
      - Corrigir bugs de acesso e carregamento

2. **Reestruturação das funcionalidades principais**:
      - Extrato financeiro e coparticipação em tempo real
      - Ampliar e atualizar rede credenciada

3. **Experiência do usuário (UX)**:
      - Melhorar interface
      - Tornar navegação mais intuitiva
      - Incluir filtros por especialidade, localização e atendimento

4. **Transparência e comunicação**:
      - Criar guia para novos usuários
      - Maior divulgação dos canais oficiais

5. **Acessibilidade**:
      - Interface adaptada a públicos diversos, incluindo idosos

---

**Fonte dos dados**: Questionário de Perfil de Usuário - GDF Saúde, aplicado entre 22 e 24 de abril de 2025, via formulário online. Todas as respostas são anônimas e respeitam a LGPD (Lei 13.709/2018).

<p align="center"><strong>Figura 22: LGPD</strong> </p>
<p align="center">
  <img src="..\..\..\assets\img-questionario\lgpd.png" alt="10" width="500"/>
</p>
<p style="text-align: center; font-size: 16px;">
  Fonte: <a href="https://github.com/LucasAlves71">Lucas Alves</a>, <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> e <a href="https://github.com/kalebmacedo">Kaleb Macedo</a>
</p>

---

### Historico de Versionamento

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|-----------|-----------|-------------|
| 1.0 | 23/04/2025 | Elaboração do Questionário |  [Lucas Alves](https://github.com/LucasAlves71) e [Othavio Bolzan](https://github.com/bolzanMGB)  | [Kaleb Macedo](https://github.com/kalebmacedo) |
| 1.1 | 01/05/20225 | Elaboração da Documentação do Questionário | [Kaleb Macedo](https://github.com/kalebmacedo) | -- |
| 1.2 | 02/05/2025 | Correção das Imagens |  [Isaque Camargos](https://github.com/isaqzin)   | [Kaleb Macedo](https://github.com/kalebmacedo) |
| 1.3 | 02/05/2025 | Adição de mais informação ao documento | [Kaleb Macedo](https://github.com/kalebmacedo)    | [Isaque Camargos](https://github.com/isaqzin) |
| 1.4 | 03/05/2025 | Adição de mais informações e correção de tabelas e imagens | [Kaleb Macedo](https://github.com/kalebmacedo) | [Isaque Camargos](https://github.com/isaqzin) |
| 1.5 | 03/05/2025 | Correção de imagens | [Kaleb Macedo](https://github.com/kalebmacedo) | [Isaque Camargos](https://github.com/isaqzin) |
| 1.6 | 03/05/2025 | Correção de imagens 2 (socorro) | [Isaque Camargos](https://github.com/isaqzin) | [Matheus de Alcântara](https://github.com/matheusdealcantara) |
