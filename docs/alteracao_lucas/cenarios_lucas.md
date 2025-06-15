## Cenário 1: Cadastrar Titular no Sistema

**Requisito Associado:** [RF07.1](../../elicitacao/requisitos_finais.md#RF07.1)

| Elemento | Descrição |
|---|---|
| **Título** | Cadastro de Titular pelo Aplicativo |
| **Metas/Objetivos** | Permitir ao usuário titular realizar seu cadastro no sistema, anexando documentos obrigatórios e validando suas informações. |
| **Ator(es)** | - Usuário (Titular) |
| **Contexto** | O usuário deseja se tornar titular do plano e precisa cadastrar seus dados e documentos pelo aplicativo. |
| **Recursos** | - App GDF Saúde<br>- Conexão com a internet<br>- Sistema de autenticação<br>- Módulo de upload de documentos<br>- Banco de dados de titulares |
| **Exceções** | - Falha no upload de documentos.<br>- Dados incompletos ou inválidos.<br>- Perda de conexão durante o cadastro. |
| **Restrições** | - Documentos obrigatórios devem ser anexados.<br>- Cadastro só é concluído após validação dos dados. |
| **Episódios** | 1. Usuário acessa a área de cadastro.<br>2. Preenche dados pessoais.<br>3. Anexa documentação.<br>4. Sistema valida informações.<br>5. Cadastro é confirmado e usuário recebe notificação. |

---

## Cenário 2: Cadastrar Dependente Vinculado ao Titular

**Requisito Associado:** [RF07.2](../../elicitacao/requisitos_finais.md#RF07.2)

| Elemento | Descrição |
|---|---|
| **Título** | Cadastro de Dependente pelo Titular |
| **Metas/Objetivos** | Permitir ao titular cadastrar dependentes, anexando documentos e vinculando-os ao seu plano. |
| **Ator(es)** | - Usuário (Titular) |
| **Contexto** | O titular deseja incluir um dependente em seu plano de saúde pelo aplicativo. |
| **Recursos** | - App GDF Saúde<br>- Conexão com a internet<br>- Sistema de autenticação<br>- Módulo de upload de documentos<br>- Banco de dados de dependentes |
| **Exceções** | - Falha no upload de documentos.<br>- Dados do dependente incompletos.<br>- Perda de conexão durante o cadastro. |
| **Restrições** | - Documentos obrigatórios do dependente devem ser anexados.<br>- Cadastro só é concluído após validação dos dados. |
| **Episódios** | 1. Titular acessa área de dependentes.<br>2. Inicia cadastro.<br>3. Preenche dados do dependente.<br>4. Anexa documentação.<br>5. Sistema valida e confirma cadastro.<br>6. Dependente é vinculado ao titular. |

---

## Cenário 3: Cadastrar Optante no Sistema

**Requisito Associado:** [RF07.3](../../elicitacao/requisitos_finais.md#RF07.3)

| Elemento | Descrição |
|---|---|
| **Título** | Cadastro de Optante pelo Aplicativo |
| **Metas/Objetivos** | Permitir ao usuário optante realizar seu cadastro, anexando documentos obrigatórios e validando suas informações. |
| **Ator(es)** | - Usuário (Optante) |
| **Contexto** | O usuário deseja se cadastrar como optante do plano pelo aplicativo. |
| **Recursos** | - App GDF Saúde<br>- Conexão com a internet<br>- Sistema de autenticação<br>- Módulo de upload de documentos<br>- Banco de dados de optantes |
| **Exceções** | - Falha no upload de documentos.<br>- Dados incompletos ou inválidos.<br>- Perda de conexão durante o cadastro. |
| **Restrições** | - Documentos obrigatórios devem ser anexados.<br>- Cadastro só é concluído após validação dos dados. |
| **Episódios** | 1. Usuário acessa área de cadastro.<br>2. Seleciona opção "Optante".<br>3. Preenche dados.<br>4. Anexa documentação.<br>5. Sistema valida e confirma cadastro. |

---

## Cenário 4: Validar Documentos no Cadastro

**Requisito Associado:** [RF07.4](../../elicitacao/requisitos_finais.md#RF07.4)

| Elemento | Descrição |
|---|---|
| **Título** | Validação de Documentos no Processo de Cadastro |
| **Metas/Objetivos** | Garantir que os documentos anexados no cadastro de titulares, dependentes e optantes sejam válidos e legíveis. |
| **Ator(es)** | - Sistema |
| **Contexto** | O usuário anexou documentos durante o cadastro e aguarda a validação automática do sistema. |
| **Recursos** | - App GDF Saúde<br>- Módulo de validação automática de documentos<br>- Banco de dados de documentos |
| **Exceções** | - Documento ilegível.<br>- Falha técnica na validação.<br>- Documento incompatível com o formato exigido. |
| **Restrições** | - Apenas documentos válidos e legíveis são aceitos.<br>- Usuário deve reenviar documentos rejeitados. |
| **Episódios** | 1. Sistema recebe documentos anexados.<br>2. Realiza validação automática.<br>3. Informa resultado ao usuário.<br>4. Se inválido, solicita novo envio. |

---

## Cenário 5: Verificar Elegibilidade no Cadastro

**Requisito Associado:** [RF07.5](../../elicitacao/requisitos_finais.md#RF07.5)

| Elemento | Descrição |
|---|---|
| **Título** | Verificação de Elegibilidade durante o Cadastro |
| **Metas/Objetivos** | Verificar se titulares, dependentes e optantes atendem aos critérios de elegibilidade do plano durante o cadastro. |
| **Ator(es)** | - Sistema |
| **Contexto** | Após envio dos dados e documentos, o sistema realiza a verificação de elegibilidade. |
| **Recursos** | - App GDF Saúde<br>- Banco de dados de critérios de elegibilidade<br>- Sistema de validação automática |
| **Exceções** | - Dados inconsistentes.<br>- Falha técnica na verificação.<br>- Critérios de elegibilidade não atendidos. |
| **Restrições** | - Cadastro só é aprovado se todos os critérios forem atendidos.<br>- Usuário deve corrigir dados inconsistentes. |
| **Episódios** | 1. Sistema recebe dados e documentos.<br>2. Verifica critérios de elegibilidade.<br>3. Informa resultado ao usuário.<br>4. Se necessário, solicita correção de dados. |

---

## Cenário 6: Verificar Procedimentos para Autorização

**Requisito Associado:** [RF08](../../elicitacao/requisitos_finais.md#RF08)

| Elemento | Descrição |
|---|---|
| **Título** | Verificação de Procedimentos para Autorização Prévia |
| **Metas/Objetivos** | Verificar se o procedimento solicitado está coberto, exige análise técnica ou documentação adicional antes da autorização. |
| **Ator(es)** | - Titular<br>- Profissional de saúde<br>- Analista técnico |
| **Contexto** | Um procedimento médico é solicitado e precisa ser analisado conforme regras do plano. |
| **Recursos** | - App GDF Saúde<br>- Banco TABGDFSAÚDE<br>- Sistema de análise técnica<br>- Módulo de upload de laudos médicos |
| **Exceções** | - Solicitação incompleta.<br>- Falha técnica no sistema.<br>- Procedimento não coberto pelo plano. |
| **Restrições** | - Procedimentos fora das regras não são autorizados.<br>- Documentação médica obrigatória para análise técnica. |
| **Episódios** | 1. Usuário submete solicitação.<br>2. Sistema verifica TABGDFSAÚDE e DUT.<br>3. Verifica carência e exclusões.<br>4. Solicita análise técnica se necessário.<br>5. Informa resultado ao usuário. |

---

## Cenário 7: Registrar Denúncia contra Profissional

**Requisito Associado:** [RF18](../../elicitacao/requisitos_finais.md#RF18)

| Elemento | Descrição |
|---|---|
| **Título** | Registro de Denúncia contra Profissional da Rede |
| **Metas/Objetivos** | Permitir ao usuário registrar denúncias de condutas inadequadas de profissionais credenciados. |
| **Ator(es)** | - Usuário (Titular, Dependente ou Optante) |
| **Contexto** | O usuário deseja denunciar um profissional da rede credenciada por conduta inadequada. |
| **Recursos** | - App GDF Saúde<br>- Sistema de denúncias<br>- Módulo de upload de evidências<br>- Banco de dados de profissionais |
| **Exceções** | - Falha no envio da denúncia.<br>- Usuário não anexa evidências.<br>- Denúncia não relacionada a profissional credenciado. |
| **Restrições** | - Apenas usuários autenticados podem registrar denúncias.<br>- Denúncia deve ser relacionada a profissional da rede credenciada. |
| **Episódios** | 1. Usuário acessa área de denúncias.<br>2. Preenche formulário com detalhes.<br>3. Anexa evidências, se houver.<br>4. Envia denúncia.<br>5. Sistema registra e encaminha para análise.