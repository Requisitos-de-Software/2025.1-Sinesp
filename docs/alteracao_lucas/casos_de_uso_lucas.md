## ORDEM NUMÉRICA DOS UC E DAS TABELAS VAO DEPENDER DO DOCUMENTO FINAL

## UC21 – Cadastrar Titular
<p align="center">Tabela 1 - Caso de Uso 21</p>

| Campo | Descrição |
| :--- | :--- |
| **UC21** | Cadastrar Titular |
| **Descrição** | Permitir o cadastro de titulares no sistema, com validação de dados e documentação. |
| **Ator** | Usuário (Titular) |
| **Pré-condições** | Usuário autenticado; documentação necessária digitalizada. |
| **Fluxo principal** | 1. Usuário acessa a área de cadastro.<br>2. Preenche dados pessoais.<br>3. Anexa documentação.<br>4. Sistema valida informações.<br>5. Cadastro é confirmado. |
| **Fluxo alternativo** | Dados incompletos: sistema solicita complementação. |
| **Fluxo de exceção** | Falha no upload de documentos: sistema exibe erro e orienta tentar novamente. |
| **Pós-condições** | Titular cadastrado e apto a utilizar o sistema. |
| **Rastreabilidade** | [RF07.1](../../elicitacao/requisitos_finais.md#RF07.1) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## UC22 – Cadastrar Dependente
<p align="center">Tabela 2 - Caso de Uso 22</p>

| Campo | Descrição |
| :--- | :--- |
| **UC22** | Cadastrar Dependente |
| **Descrição** | Permitir o cadastro de dependentes vinculados a um titular. |
| **Ator** | Usuário (Titular) |
| **Pré-condições** | Titular autenticado; documentação do dependente digitalizada. |
| **Fluxo principal** | 1. Titular acessa área de dependentes.<br>2. Inicia cadastro.<br>3. Preenche dados do dependente.<br>4. Anexa documentação.<br>5. Sistema valida e confirma cadastro. |
| **Fluxo alternativo** | Dados incompletos: sistema solicita complementação. |
| **Fluxo de exceção** | Falha no upload de documentos: sistema exibe erro e orienta tentar novamente. |
| **Pós-condições** | Dependente cadastrado e vinculado ao titular. |
| **Rastreabilidade** | [RF07.2](../../elicitacao/requisitos_finais.md#RF07.2) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## UC23 – Cadastrar Optante
<p align="center">Tabela 3 - Caso de Uso 23</p>

| Campo | Descrição |
| :--- | :--- |
| **UC23** | Cadastrar Optante |
| **Descrição** | Permitir o cadastro de optantes no sistema, com validação de dados e documentação. |
| **Ator** | Usuário (Optante) |
| **Pré-condições** | Usuário autenticado; documentação necessária digitalizada. |
| **Fluxo principal** | 1. Usuário acessa área de cadastro.<br>2. Seleciona opção "Optante".<br>3. Preenche dados.<br>4. Anexa documentação.<br>5. Sistema valida e confirma cadastro. |
| **Fluxo alternativo** | Dados incompletos: sistema solicita complementação. |
| **Fluxo de exceção** | Falha no upload de documentos: sistema exibe erro e orienta tentar novamente. |
| **Pós-condições** | Optante cadastrado e apto a utilizar o sistema. |
| **Rastreabilidade** | [RF07.3](../../elicitacao/requisitos_finais.md#RF07.3) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## UC24 – Validar Documentos no Cadastro
<p align="center">Tabela 4 - Caso de Uso 24</p>

| Campo | Descrição |
| :--- | :--- |
| **UC24** | Validar Documentos no Cadastro |
| **Descrição** | Validar os documentos apresentados durante o cadastro de titulares, dependentes e optantes. |
| **Ator** | Sistema |
| **Pré-condições** | Documentos anexados no processo de cadastro. |
| **Fluxo principal** | 1. Sistema recebe documentos.<br>2. Realiza validação automática.<br>3. Informa resultado ao usuário. |
| **Fluxo alternativo** | Documento ilegível: solicita novo envio. |
| **Fluxo de exceção** | Falha técnica na validação: sistema exibe erro e orienta tentar novamente. |
| **Pós-condições** | Documentos validados ou solicitação de reenvio. |
| **Rastreabilidade** | [RF07.4](../../elicitacao/requisitos_finais.md#RF07.4) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## UC25 – Verificar Elegibilidade no Cadastro
<p align="center">Tabela 5 - Caso de Uso 25</p>

| Campo | Descrição |
| :--- | :--- |
| **UC25** | Verificar Elegibilidade no Cadastro |
| **Descrição** | Verificar a elegibilidade dos titulares, dependentes e optantes durante o processo de cadastro. |
| **Ator** | Sistema |
| **Pré-condições** | Dados e documentos enviados no cadastro. |
| **Fluxo principal** | 1. Sistema recebe dados.<br>2. Verifica critérios de elegibilidade.<br>3. Informa resultado ao usuário. |
| **Fluxo alternativo** | Dados inconsistentes: solicita correção. |
| **Fluxo de exceção** | Falha técnica na verificação: sistema exibe erro e orienta tentar novamente. |
| **Pós-condições** | Cadastro aprovado ou pendente de regularização. |
| **Rastreabilidade** | [RF07.5](../../elicitacao/requisitos_finais.md#RF07.5) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## UC26 – Verificar Procedimentos para Autorização
<p align="center">Tabela 6 - Caso de Uso 26</p>

| Campo | Descrição |
| :--- | :--- |
| **UC26** | Verificar Procedimentos para Autorização |
| **Descrição** | Verificar se procedimentos estão na TABGDFSAÚDE, atendem às DUT, carência ou exclusões, exigindo solicitação médica e análise técnica para autorizações prévias. |
| **Ator** | Titular / Profissional de saúde / Analista técnico |
| **Pré-condições** | Procedimento solicitado e dados médicos anexados. |
| **Fluxo principal** | 1. Usuário submete solicitação.<br>2. Sistema verifica TABGDFSAÚDE e DUT.<br>3. Verifica carência e exclusões.<br>4. Solicita análise técnica se necessário.<br>5. Informa resultado ao usuário. |
| **Fluxo alternativo** | Procedimento coberto e sem exigência de análise: autorização automática. |
| **Fluxo de exceção** | Solicitação incompleta: sistema solicita complementação.<br>Falha técnica: exibe erro e orienta tentar novamente. |
| **Pós-condições** | Procedimento autorizado ou negado com justificativa técnica. |
| **Rastreabilidade** | [RF08](../../elicitacao/requisitos_finais.md#RF08) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>

---

## UC27 – Registrar Denúncia contra Profissional
<p align="center">Tabela 7 - Caso de Uso 27</p>

| Campo | Descrição |
| :--- | :--- |
| **UC27** | Registrar Denúncia contra Profissional |
| **Descrição** | Permitir ao usuário registrar denúncias de condutas inadequadas por parte de profissionais da rede credenciada. |
| **Ator** | Usuário (Titular, Dependente ou Optante) |
| **Pré-condições** | Usuário autenticado; denúncia relacionada a profissional da rede credenciada. |
| **Fluxo principal** | 1. Usuário acessa área de denúncias.<br>2. Preenche formulário com detalhes.<br>3. Anexa evidências, se houver.<br>4. Envia denúncia.<br>5. Sistema registra e encaminha para análise. |
| **Fluxo alternativo** | Usuário não anexa evidências: sistema permite envio apenas com descrição. |
| **Fluxo de exceção** | Falha no envio: sistema exibe erro e orienta tentar novamente. |
| **Pós-condições** | Denúncia registrada e encaminhada para análise. |
| **Rastreabilidade** | [RF18](../../elicitacao/requisitos_finais.md#RF18) |
| **Data de criação** | 15/06/2025 |

<p align="center">Fonte: Autoria de <a href="https://github.com/LucasAlves71">Lucas Alves</a></p>