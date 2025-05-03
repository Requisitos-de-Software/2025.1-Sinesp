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

### Funcionais

<p align="center">Tabela 1: Requisitos Funcionais</p>

| **Tipo** | **Descrição**                                                                                                      | **Técnicas**                  | **Implementado** |
|----------|--------------------------------------------------------------------------------------------------------------------|-------------------------------|------------------|
| <a id="RF01"></a>RF01     | Permitir ao usuário pesquisar e filtrar clínicas e profissionais credenciados por especialidade, região administrativa, tipo de atendimento e proximidade. | [EN01](../elicitacao/tecnicas/entrevista.md#EN01), [EN02](../elicitacao/tecnicas/entrevista.md#EN02), [IS02](../elicitacao/tecnicas/introspeccao.md#IS02), [IS06](../elicitacao/tecnicas/introspeccao.md#IS06), [QT03](../elicitacao/tecnicas/questionario.md#QT03), [QT08](../elicitacao/tecnicas/questionario.md#QT08) | Sim              |
| <a id="RF02"></a>RF02     | Disponibilizar sistema de avaliação de clínicas com notas e comentários.                                           | [EN03](../elicitacao/tecnicas/entrevista.md#EN03), [GF01](../elicitacao/tecnicas/grupo_focal.md#GF01)                    | Não              |
| <a id="RF03"></a>RF03     | Exibir carteirinha digital mesmo sem conexão (modo offline) e permitir acesso rápido e estável.                    | [EN04](../elicitacao/tecnicas/entrevista.md#EN04), [IS09](../elicitacao/tecnicas/introspeccao.md#IS09), [QT01](../elicitacao/tecnicas/questionario.md#QT01)              | Não              |
| RF04     | Enviar notificações configuráveis via app, SMS ou e-mail sobre ven e-mail sobre vencimento de fatura, retornos médicos pendentes, abertura de agenda, cancelamentos de horários, horários favoritos disponíveis, prazos importantes, confirmações ou alterações de agendamento e disponibilidade de demonstrativos de IR. | [EN05](../elicitacao/tecnicas/entrevista.md#EN05), [EN06](../elicitacao/tecnicas/entrevista.md#EN06), [GF02](../elicitacao/tecnicas/grupo_focal.md#GF02), [GF03](../elicitacao/tecnicas/grupo_focal.md#GF03), [GF07](../elicitacao/tecnicas/grupo_focal.md#GF07), [GF10](../elicitacao/tecnicas/grupo_focal.md#GF10), [IS07](../elicitacao/tecnicas/introspeccao.md#IS07), [IS12](../elicitacao/tecnicas/introspeccao.md#IS12), [QT06](../elicitacao/tecnicas/questionario.md#QT06) | Não              |
| <a id="RF05"></a>RF05     | Permitir agendamento e cancelamento de consultas e exames diretamente pelo aplicativo, com pagamento automático para prestadores da Rede de Atendimento. | [EN07](../elicitacao/tecnicas/entrevista.md#EN07), [GL01](../elicitacao/tecnicas/glossario.md#GL01), [IS01](../elicitacao/tecnicas/introspeccao.md#IS01), [IS05](../elicitacao/tecnicas/introspeccao.md#IS05), [GL06](../elicitacao/tecnicas/glossario.md#GL06)       | Não              |
| <a id="RF06"></a>RF06     | Exibir valor específico de consulta em cada clínica, aplicar percentuais de coparticipação, gerar e baixar demonstrativos de despesas médicas para imposto de renda, consultar histórico de demonstrativos de IR e mostrar extrato financeiro atualizado diariamente. | [EN08](../elicitacao/tecnicas/entrevista.md#EN08), [GL04](../elicitacao/tecnicas/glossario.md#GL04), [IS10](../elicitacao/tecnicas/introspeccao.md#IS10), [IS11](../elicitacao/tecnicas/introspeccao.md#IS11), [QT02](../elicitacao/tecnicas/questionario.md#QT02), [QT05](../elicitacao/tecnicas/questionario.md#QT05) | Sim              |
| <a id="RF07"></a>RF07     | Permitir cadastro de titulares, dependentes e optantes com validação de documentos e elegibilidade.                | [GL01](../elicitacao/tecnicas/glossario.md#GL01), [GL08](../elicitacao/tecnicas/glossario.md#GL08), [GL09](../elicitacao/tecnicas/glossario.md#GL09)           | Sim              |
| <a id="RF08"></a>RF08     | Verificar se procedimentos estão na TABGDFSAÚDE, atendem às DUT, estão sujeitos a carência ou são excluídos, exigindo solicitação médica e análise técnica para autorizações prévias. | [GL02](../elicitacao/tecnicas/glossario.md#GL02), [GL03](../elicitacao/tecnicas/glossario.md#GL03), [GL05](../elicitacao/tecnicas/glossario.md#GL05), [GL07](../elicitacao/tecnicas/glossario.md#GL07), [QT09](../elicitacao/tecnicas/questionario.md#QT09) | Sim              | 
| <a id="RF09"></a>RF09     | Permitir ao usuário visualizar histórico de consultas, exames realizados, resultados de exames laboratoriais e coparticipações. | [GF04](../elicitacao/tecnicas/grupo_focal.md#GF04), [GF08](../elicitacao/tecnicas/grupo_focal.md#GF08), [IS03](../elicitacao/tecnicas/introspeccao.md#IS03), [IS04](../elicitacao/tecnicas/introspeccao.md#IS04), [QT04](../elicitacao/tecnicas/questionario.md#QT04)  | Sim              |
| <a id="RF10"></a>RF10     | Permitir que o usuário favorite horários de consulta desejados.                                                    | [GF06](../elicitacao/tecnicas/grupo_focal.md#GF06)                          | Não              
| <a id="RF11"></a>RF11     | Oferecer um canal para o usuário enviar feedback sobre atendimentos.                                               | [GF09](../elicitacao/tecnicas/grupo_focal.md#GF09)                          | Não              |
| <a id="RF12"></a>RF12     | Divulgar informações sobre novas funcionalidades no aplicativo.                                                    | [GF05](../elicitacao/tecnicas/grupo_focal.md#GF05)                          | Não              
| <a id="RF13"></a>RF13     | Adicionar consulta à rede odontológica.                                                                            | [QT07](../elicitacao/tecnicas/questionario.md#QT07)                          | Sim              | 
| <a id="RF14"></a>RF14     | Apresentar novas clínicas e clínicas próximas de acordo com a localização do usuário.                              | [EN09](../elicitacao/tecnicas/entrevista.md#EN09)                          | Não              | 
| RF15     | Permitir baixar comprovantes de agendamento.                                                                       | [IS08](../elicitacao/tecnicas/introspeccao.md#IS08)                          | Não              |                   | Não              |

<font size="3"><p style="text-align: center">Fonte: [Matheus de Alcântara](https://github.com/matheusdealcantara) e [Yzabella Miranda](https://github.com/redjsun).</p></font>

### Não funcionais

<p align="center">Tabela 2: Requisitos Não Funcionais</p>

| **Tipo** | **Descrição**                                                                                                      | **Técnicas**                  | **Implementado** |
|----------|--------------------------------------------------------------------------------------------------------------------|-------------------------------|------------------|
| <a id="RNF01"></a>RNF01    | A interface deve ser intuitiva, clara, adaptada para idosos e pessoas com baixa familiaridade tecnológica, organizada em categorias e responsiva em smartphones Android e iOS. | [EN10](../elicitacao/tecnicas/entrevista.md#EN10), [GF13](../elicitacao/tecnicas/grupo_focal.md#GF13), [IS13](../elicitacao/tecnicas/introspeccao.md#IS13), [QT11](../elicitacao/tecnicas/questionario.md#QT11)        | Não              |
| <a id="RNF02"></a>RNF02    | Garantir carregamento rápido e fluído de todas as telas, com tempo de resposta das ações não ultrapassando 2 segundos. | [EN11](../elicitacao/tecnicas/entrevista.md#EN11), [GF17](../elicitacao/tecnicas/grupo_focal.md#GF17), [IS14](../elicitacao/tecnicas/introspeccao.md#IS14), [QT12](../elicitacao/tecnicas/questionario.md#QT12)        | Sim              |
| <a id="RNF03"></a>RNF03    | Assegurar segurança no acesso e armazenamento de dados pessoais, criptografar dados sensíveis conforme LGPD, incluir autenticação em dois fatores e ser transparente quanto ao uso e segurança dos dados. | [EN12](../elicitacao/tecnicas/entrevista.md#EN12), [GL12](../elicitacao/tecnicas/glossario.md#GL12), [GF12](../elicitacao/tecnicas/grupo_focal.md#GF12), [GF14](../elicitacao/tecnicas/grupo_focal.md#GF14), [IS18](../elicitacao/tecnicas/introspeccao.md#IS18), [QT15](../elicitacao/tecnicas/questionario.md#QT15) | Sim              |
| <a id="RNF04"></a>RNF04    | Manter o sistema disponível 24/7 para autorizações de urgência/emergência e apresentar alta disponibilidade (mínimo de 99% uptime). | [GL11](../elicitacao/tecnicas/glossario.md#GL11), [QT10](../elicitacao/tecnicas/questionario.md#QT10)                   | Sim              |
| <a id="RNF05"></a>RNF05    | O sistema deve ser compatível com diferentes versões do Android e iOS, a partir das versões mais utilizadas no mercado. | [GF18](../elicitacao/tecnicas/grupo_focal.md#GF18), [IS17](../elicitacao/tecnicas/introspeccao.md#IS17), [QT11](../elicitacao/tecnicas/questionario.md#QT11)              | Sim              |
| <a id="RNF06"></a>RNF06    | O aplicativo deve ser compatível com leitores de tela para garantir acessibilidade a pessoas com deficiência visual. | [IS20](../elicitacao/tecnicas/introspeccao.md#IS20), [QT14](../elicitacao/tecnicas/questionario.md#QT14)                    | Não              |
| <a id="RNF07"></a>RNF07    | Garantir conformidade com a Portaria nº 127/2024, legislações complementares e padrões da LGPD.                    | [GL10](../elicitacao/tecnicas/glossario.md#GL10), [QT15](../elicitacao/tecnicas/questionario.md#QT15)                   | Sim              |
| <a id="RNF08"></a>RNF08    | Processar autorizações prévias em até 10 dias úteis.                                                              | [GL13](../elicitacao/tecnicas/glossario.md#GL13)                         | Sim              |
| <a id="RNF09"></a>RNF09    | Comunicar-se com a folha de pagamento do GDF para descontos de mensalidades.                                       | [GL14](../elicitacao/tecnicas/glossario.md#GL14)                         | Sim              |
| <a id="RNF10"></a>RNF10    | Garantir que informações críticas, como a carteirinha digital, estejam acessíveis em até três cliques ou com no máximo 2 cliques a partir da tela inicial. | [GF15](../elicitacao/tecnicas/grupo_focal.md#GF15), [IS16](../elicitacao/tecnicas/introspeccao.md#IS16)                    | Sim              |
| <a id="RNF11"></a>RNF11    | Manter histórico de notificações acessível ao usuário por no mínimo 6 meses.                                      | [GF16](../elicitacao/tecnicas/grupo_focal.md#GF16)                          | Não              |
| <a id="RNF12"></a>RNF12    | O aplicativo deve oferecer suporte por chat ou telefone.                                                          | [IS15](../elicitacao/tecnicas/introspeccao.md#IS15)                          | Sim              |
| <a id="RNF13"></a>RNF13    | Deve funcionar de forma offline para acesso à carteirinha e histórico de consultas.                               | [IS19](../elicitacao/tecnicas/introspeccao.md#IS19)                          | Não              |
| <a id="RNF14"></a>RNF14    | O layout deve ser consistente com o portal oficial do plano.                                                      | [QT16](../elicitacao/tecnicas/questionario.md#QT16)                          | Não              |
| <a id="RNF15"></a>RNF15    | O sistema deve exigir autenticação via GovBR para login.                                                          | [GF11](../elicitacao/tecnicas/grupo_focal.md#GF11)                          | Não              |
| <a id="RNF16"></a>RNF16    | As informações exibidas devem ser claras, completas e atualizadas em tempo real.                                  | [QT13](../elicitacao/tecnicas/questionario.md#QT13)                          | Sim              |

<font size="3"><p style="text-align: center">Fonte: [Matheus de Alcântara](https://github.com/matheusdealcantara) e [Yzabella Miranda](https://github.com/redjsun).</p></font>

## Histórico de Versões

| Versão | Data       | Descrição                                        | Autor(es)           | Revisor(es)         |
|--------|------------|--------------------------------------------------|---------------------|---------------------|
| 1.0    | 10/04/2025 | Criação da Documentação inicial contendo: A introdução, requisitos e as tabelas dos requisitos funcionais e os não funcionais          | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC), [Othavio Bolzan](https://github.com/bolzanMGB) e [Yzabella Miranda](https://github.com/redjsun)| [Isaque Camargos](https://github.com/isaqzin) |
| 1.1    | 03/05/2025 | Atualização da tabela com a separação correta de ID e seus respectivos agrupamentos de descrição em comum          | [Yzabella Miranda](https://github.com/redjsun) e [Matheus de Alcântara](https://github.com/matheusdealcantara)| [Isaque Camargos](https://github.com/isaqzin) |