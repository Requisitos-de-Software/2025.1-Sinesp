# Requisitos Elicitados

## Introdução

Esta página consolida os requisitos identificados para o projeto, eliciados por meio das técnicas Entrevista, Glossário, Questionário, Introspecção e Grupo Focal. O processo de levantamento priorizou a compreensão das necessidades dos usuários e a conformidade com normas técnicas, garantindo clareza e alinhamento aos objetivos propostos.

## Requisitos

Os requisitos foram organizados em duas tabelas: a Tabela 1 apresenta os Requisitos Funcionais, enquanto a Tabela 2 lista os Requisitos Não Funcionais.

Legenda das Tabelas:

- RFx: Requisito Funcional número x;
- RNFx: Requisito Não Funcional número x;
- ENx: Requisito da Entrevista número x;
- GLx: Requisito Glossário número x;
- QTx: Requisito Questionário número x;
- ISx: Requisito da Introspecção número x;
- GFx: Requisito do Grupo de Foco número x;


<br>

## Tabela 1: Requisitos Funcionais

<br>

<p align="center">Tabela 1 – Requisitos funcionais</p>

| Identificador | Descrição                                                                                             | ID Origem              | Implementado       |
| ----: | :---------------------------------------------------------------------------------------------------- | :--------------------- | :----------------- |
|         RF001 | Permitir agendamento de consultas e exames pelo aplicativo                                            | IS01; EN07; GL006      | Não                |
|         RF002 | Permitir cancelamento de consultas                                                                    | IS05                   | Não                |
|         RF003 | Listar e filtrar rede credenciada (médicos, clínicas, especialidades, região)                         | IS02; EN01; EN02; QT03 | Sim                |
|         RF004 | Permitir ao usuário pesquisar clínicas e profissionais por especialidade                              | EN01; QT08             | Sim                |
|         RF005 | Exibir os exames solicitados e permitir consulta de resultados laboratoriais                          | IS03; GF04             | Não         |
|         RF006 | Exibir histórico de atendimentos (consultas, exames, coparticipações)                                 | IS04; QT04; GF08       | Sim |
|         RF007 | Enviar notificações de confirmação, alteração de agendamento ou prazos importantes                    | IS07; GF02; GF03; GF10 | Não                |
|         RF008 | Oferecer notificações personalizadas (tipos importantes, lembretes, abertura de agenda, desistências) | QT06; GF07             | Não                |
|         RF009 | Permitir favoritar horários e alertar o usuário quando ficarem disponíveis                            | GF06; GF07             | Não                |
|         RF010 | Permitir ao usuário avaliar e comentar clínicas após atendimento                                      | GF01; EN03             | Não                |
|         RF011 | Disponibilizar canal de feedback para o usuário enviar sugestões e opiniões                           | GF09                   | Não                |
|         RF012 | Divulgar informações sobre novas funcionalidades no aplicativo                                        | GF05                   | Sem certeza        |
|         RF013 | Exibir e permitir download da carteirinha digital do plano                                            | IS09; EN04             | Sim         |
|         RF014 | Permitir acesso  à carteirinha digital                           | RNF07 EN04            | Não                |
|         RF015 | Permitir baixar comprovantes de agendamento e gerar demonstrativos de despesas médicas (IR)           | IS08; IS10; IS11       | Sim / Não⁴         |
|         RF016 | Exibir extrato financeiro atualizado diariamente                                                      | QT02                   | Sim              |
|         RF017 | Visualizar status de autorizações e solicitações médicas em tempo real                                | QT09                   | Média⁶             |
|         RF018 | Validar e cadastrar titulares, dependentes e documentos (CPF, comprovante)                            | GL001                  | Não                |
|         RF019 | Verificar elegibilidade de procedimentos (TABGDFSAÚDE, DUT, carência) antes da autorização            | GL002; GL003           | Não                |
|         RF020 | Aplicar percentuais de coparticipação conforme tipo de atendimento                                    | GL004                  | Sim                |
|         RF021 | Exigir solicitação médica e análise técnica para procedimentos eletivos                               | GL005                  | Não                |
|         RF022 | Rejeitar automaticamente procedimentos listados em exclusões (CID)                                    | GL007                  | Sim                |
|         RF023 | Validar vínculo e elegibilidade do usuário/dependente (GDF, diretrizes do app)                        | GL008; GL009           | Sim                |
|         RF024 | Exibir carteirinha digital mesmo sem conexão (modo offline)                                   | EN04             | Não         |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a> e <a href="https://github.com/redjsun">Yzabela Miranda</a> </p>


<br>

## Tabela 2: Requisitos Não-Funcionais

<br>

<p align="center">Tabela 1 – Requisitos Não Funcionais</p>

| Identificador | Descrição                                                                             | ID Origem                 | Implementado  |
| ------------: | :------------------------------------------------------------------------------------ | :------------------------ | :------------ |
|        RNF001 | Interface clara, intuitiva e responsiva (incluindo para idosos e baixa familiaridade) | RNF01; RNF02; QT01; RNF13 | Parcial / Sim |
|        RNF002 | Tempo de resposta entre telas ≤ 2 segundos                                            | IS14; RNF03; RNF17        | Sim           |
|        RNF003 | Disponibilidade mínima de 99% uptime ou 24/7 para urgência                            | RNF01; GL011              | Sim           |
|        RNF004 | Suporte (chat, telefone) e canal de atendimento                                       | IS15                      | Sim           |
|        RNF005 | Compatibilidade Android e iOS                                                         | IS17; RNF02; RNF18        | Sim           |
|        RNF006 | Alto nível de segurança e criptografia de dados (LGPD, Portaria 127/2024)             | IS18; GL010; GL012        | Sim           |
|        RNF007 | Acessibilidade: compatível com leitores de tela                                       | IS20; RNF05               | Não           |
|        RNF008 | Histórico de notificações acessível por no mínimo 6 meses                             | GF16                      | Sim            |
|        RNF009 | Layout consistente com portal oficial do plano                                        | RNF07                     | Baixa⁷        |
|        RNF010 | Informação clara, completa e atualizada em tempo real                                 | RNF04                     | Sim           |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a> e <a href="https://github.com/redjsun">Yzabela Miranda</a> </p>



## Histórico de Versões

| Versão | Data       | Descrição                                        | Autor(es)           | Revisor(es)         |
|--------|------------|--------------------------------------------------|---------------------|---------------------|
| 1.0    | 10/04/2025 | Criação da Documentação inicial contendo: A introdução, requisitos e as tabelas dos requisitos funcionais e os não funcionais          | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC), [Othavio Bolzan](https://github.com/bolzanMGB) e [Yzabella Miranda](https://github.com/redjsun)| [Isaque Camargos](https://github.com/isaqzin) |
