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

# Requisitos Funcionais e Não Funcionais

## Requisitos Funcionais (RF)

| ID   | IDs Originais      | Descrição                                                                 | Implementado |
|------|--------------------|---------------------------------------------------------------------------|--------------|
| RF01 | EN01, IS08         | Permitir pesquisa/filtro de clínicas e profissionais por especialidade/região. | Sim          |
| RF02 | EN02               | Oferecer filtros de rede credenciada por região administrativa e especialidade. | Sim          |
| RF03 | EN03, GF01         | Sistema de avaliação de clínicas com notas/comentários e feedback.        | Não          |
| RF04 | EN04, IS19         | Exibir carteirinha digital e histórico de consultas em modo offline.      | Não          |
| RF05 | EN05, GF05, IS06   | Configuração de notificações (app/SMS/e-mail) e divulgação de novidades.  | Não          |
| RF06 | EN06, IS12         | Alertas de vencimento de fatura e notificações de demonstrativos de IR.   | Não          |
| RF07 | EN07, IS01         | Agendamento de consultas/exames diretamente pelo aplicativo.              | Não          |
| RF08 | EN08               | Exibir valores específicos de consulta por clínica credenciada.           | Não          |
| RF09 | EN09, IS06         | Apresentar clínicas próximas/novas baseadas na localização do usuário.    | Não          |
| RF10 | GL001              | Cadastro de titulares/dependentes com validação de documentos.            | Não          |
| RF11 | GL002              | Verificar conformidade de procedimentos com TABGDFSAÚDE/DUT.              | Não          |
| RF12 | GL003              | Bloquear procedimentos sujeitos a carência (ex.: parto após 300 dias).    | Não          |
| RF13 | GL004              | Aplicar percentuais de coparticipação conforme tipo de atendimento.       | Sim          |
| RF14 | GL005              | Exigir solicitação médica e análise técnica para procedimentos eletivos. | Não          |
| RF15 | GL006              | Agendamento e pagamento automático para prestadores da Rede.              | Não          |
| RF16 | GL007              | Rejeitar automaticamente procedimentos em lista de exclusões (ex.: cirurgias estéticas). | Sim |
| RF17 | GL008, GL009       | Validar vínculo do servidor com GDF e elegibilidade de dependentes.       | Sim          |
| RF18 | GF02, GF03, GF07   | Notificar retornos médicos, cancelamentos e disponibilidade de horários.  | Não          |
| RF19 | GF04               | Associar exames solicitados a retornos médicos.                           | Não          |
| RF20 | GF06               | Favoritar horários de consulta desejados.                                 | Não          |
| RF21 | GF08, IS04         | Visualizar histórico de consultas/exames/atendimentos.                    | Sim          |
| RF22 | GF09               | Canal para envio de feedback sobre atendimentos.                          | Não          |
| RF23 | GF10               | Notificações sobre prazos importantes de consultas/exames.                | Não          |
| RF24 | IS03               | Consulta de resultados de exames laboratoriais.                           | Não          |
| RF25 | IS05               | Cancelamento de consultas pelo aplicativo.                                | Não          |
| RF26 | IS07               | Notificações de confirmação/alteração de agendamento.                     | Não          |
| RF27 | IS09               | Acesso à carteirinha digital do plano.                                    | Sim          |
| RF28 | IS10               | Geração/download de demonstrativos de despesas médicas para IR.           | Sim          |
| RF29 | IS11               | Consulta de histórico de demonstrativos de IR de anos anteriores.         | Sim          |

## Requisitos Não Funcionais (RNF)

| ID    | IDs Originais             | Descrição                                                                 | Implementado |
|-------|---------------------------|---------------------------------------------------------------------------|--------------|
| RNF01 | EN10, GF13, IS11, IS16    | Interface intuitiva com categorias claras e alinhada ao portal oficial.   | Sim          |
| RNF02 | EN11, IS14, GF17          | Carregamento rápido com tempo de resposta ≤2 segundos.                    | Sim          |
| RNF03 | EN12, GL012, IS15, IS18   | Segurança de dados (criptografia/LGPD) e transparência no uso.            | Sim          |
| RNF04 | GL010, GL011              | Conformidade legal (Portaria nº 127/2024) e disponibilidade 24/7.         | Sim          |
| RNF05 | GL013                     | Processamento de autorizações prévias em ≤10 dias úteis.                  | Sim          |
| RNF06 | GL014                     | Integração com folha de pagamento do GDF para descontos.                  | Sim          |
| RNF07 | GF11, GF12                | Autenticação via GovBR e dois fatores para dados sensíveis.               | Não          |
| RNF08 | GF15                      | Acesso a informações críticas em até três cliques.                        | Não          |
| RNF09 | GF16                      | Histórico de notificações acessível por ≥6 meses.                         | Não          |
| RNF10 | GF18, IS17                | Compatibilidade com versões recentes de Android/iOS.                      | Sim          |
| RNF11 | IS13                      | Interface adaptada para idosos/usuários com baixa familiaridade tecnológica. | Não      |
| RNF12 | IS19, IS07                | Funcionamento offline para carteirinha e histórico de consultas.          | Não          |
| RNF13 | IS20, IS14                | Compatibilidade com leitores de tela para deficientes visuais.            | Não          |
| RNF14 | IS10                      | Alta disponibilidade (≥99% uptime).                                       | Não          |
| RNF15 | IS12                      | Tempo de resposta das ações ≤2 segundos.                                  | Não          |

## Histórico de Versões

| Versão | Data       | Descrição                                        | Autor(es)           | Revisor(es)         |
|--------|------------|--------------------------------------------------|---------------------|---------------------|
| 1.0    | 10/04/2025 | Criação da Documentação inicial contendo: A introdução, requisitos e as tabelas dos requisitos funcionais e os não funcionais          | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC), [Othavio Bolzan](https://github.com/bolzanMGB) e [Yzabella Miranda](https://github.com/redjsun)| [Isaque Camargos](https://github.com/isaqzin) |