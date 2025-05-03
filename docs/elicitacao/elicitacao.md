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

## OUTRA
### Tabela de Requisitos Funcionais (RF)

| **ID Consolidado** | **Descrição**                                                                                                      | **Técnicas**                  |
|--------------------|--------------------------------------------------------------------------------------------------------------------|-------------------------------|
| RF01               | Permitir ao usuário pesquisar e filtrar clínicas e profissionais credenciados por especialidade, região administrativa, tipo de atendimento e proximidade. | EN01, EN02, IS02, IS06, QT03, QT08 |
| RF02               | Disponibilizar sistema de avaliação de clínicas com notas e comentários.                                           | EN03, GF01                    |
| RF03               | Exibir carteirinha digital mesmo sem conexão (modo offline) e permitir acesso rápido e estável.                    | EN04, IS09, QT01              |
| RF04               | Enviar notificações configuráveis sobre vencimento de fatura, retornos médicos pendentes, abertura de agenda, cancelamentos de horários, horários favoritos disponíveis, prazos importantes, confirmações ou alterações de agendamento e disponibilidade de demonstrativos de IR. | EN05, EN06, GF02, GF03, GF07, GF10, IS07, IS12, QT06 |
| RF05               | Permitir agendamento, cancelamento de consultas e exames diretamente pelo aplicativo, com pagamento automático para prestadores da Rede de Atendimento. | EN07, GL06, IS01, IS05       |
| RF06               | Exibir valor específico de consulta em cada clínica, aplicar percentuais de coparticipação, gerar e baixar demonstrativos de despesas médicas para imposto de renda, consultar histórico de demonstrativos de IR e mostrar extrato financeiro atualizado diariamente. | EN08, GL04, IS10, IS11, QT02, QT05 |
| RF07               | Permitir cadastro de titulares, dependentes e optantes com validação de documentos e elegibilidade.                | GL01, GL08, GL09           |
| RF08               | Verificar se procedimentos estão na TABGDFSAÚDE, atendem às DUT, estão sujeitos a carência ou são excluídos, exigindo solicitação médica e análise técnica para autorizações prévias. | GL02, GL03, GL05, GL07, QT09 |
| RF09               | Permitir ao usuário visualizar histórico de consultas, exames realizados, resultados de exames laboratoriais e coparticipações. | GF04, GF08, IS03, IS04, QT04  |
| RF10               | Permitir que o usuário favorite horários de consulta desejados.                                                    | GF06                          |
| RF11               | Oferecer um canal para o usuário enviar feedback sobre atendimentos.                                               | GF09                          |
| RF12               | Divulgar informações sobre novas funcionalidades no aplicativo.                                                    | GF05                          |
| RF13               | Adicionar consulta à rede odontológica.                                                                            | QT07                          |
| RF14               | Apresentar novas clínicas e clínicas próximas de acordo com a localização do usuário.                              | EN09                          |
| RF15               | Permitir baixar comprovantes de agendamento.                                                                       | IS08                          |

### Tabela de Requisitos Não Funcionais (RNF)

| **ID Consolidado** | **Descrição**                                                                                                      | **Técnicas**                  |
|--------------------|--------------------------------------------------------------------------------------------------------------------|-------------------------------|
| RNF01              | A interface deve ser intuitiva, clara, adaptada para idosos e pessoas com baixa familiaridade tecnológica, organizada em categorias e responsiva em smartphones Android e iOS. | EN10, GF13, IS13, QT11        |
| RNF02              | Garantir carregamento rápido e fluído de todas as telas, com tempo de resposta das ações não ultrapassando 2 segundos. | EN11, GF17, IS14, QT12        |
| RNF03              | Assegurar segurança no acesso e armazenamento de dados pessoais, criptografar dados sensíveis conforme LGPD, incluir autenticação em dois fatores e ser transparente quanto ao uso e segurança dos dados. | EN12, GL12, GF12, GF14, IS18, QT15 |
| RNF04              | Manter o sistema disponível 24/7 para autorizações de urgência/emergência e apresentar alta disponibilidade (mínimo de 99% uptime). | GL11, QT10                   |
| RNF05              | O sistema deve ser compatível com diferentes versões do Android e iOS, a partir das versões mais utilizadas no mercado. | GF18, IS17, QT11              |
| RNF06              | O aplicativo deve ser compatível com leitores de tela para garantir acessibilidade a pessoas com deficiência visual. | IS20, QT14                    |
| RNF07              | Garantir conformidade com a Portaria nº 127/2024, legislações complementares e padrões da LGPD.                    | GL10, QT15                   |
| RNF08              | Processar autorizações prévias em até 10 dias úteis.                                                              | GL13                         |
| RNF09              | Comunicar-se com a folha de pagamento do GDF para descontos de mensalidades.                                       | GL14                         |
| RNF10              | Garantir que informações críticas, como a carteirinha digital, estejam acessíveis em até três cliques ou com no máximo 2 cliques a partir da tela inicial. | GF15, IS16                    |
| RNF11              | Manter histórico de notificações acessível ao usuário por no mínimo 6 meses.                                      | GF16                          |
| RNF12              | O aplicativo deve oferecer suporte por chat ou telefone.                                                          | IS15                          |
| RNF13              | Deve funcionar de forma offline para acesso à carteirinha e histórico de consultas.                               | IS19                          |
| RNF14              | O layout deve ser consistente com o portal oficial do plano.                                                      | QT16                          |
| RNF15              | O sistema deve exigir autenticação via GovBR para login.                                                          | GF11                          |
|RNF16               | As informações exibidas devem ser claras, completas e atualizadas em tempo real |  QT13  |

## Histórico de Versões

| Versão | Data       | Descrição                                        | Autor(es)           | Revisor(es)         |
|--------|------------|--------------------------------------------------|---------------------|---------------------|
| 1.0    | 10/04/2025 | Criação da Documentação inicial contendo: A introdução, requisitos e as tabelas dos requisitos funcionais e os não funcionais          | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC), [Othavio Bolzan](https://github.com/bolzanMGB) e [Yzabella Miranda](https://github.com/redjsun)| [Isaque Camargos](https://github.com/isaqzin) |