# Técnica de Priorização: MoSCoW

## Introdução

A técnica MoSCoW é uma abordagem amplamente reconhecida para a priorização de requisitos em projetos de software, especialmente em ambientes ágeis. Desenvolvida por Dai Clegg em 1994 para o método de Desenvolvimento Rápido de Aplicações (RAD), ela foi posteriormente incorporada ao Dynamic Systems Development Method (DSDM) .

O acrônimo MoSCoW representa quatro categorias de prioridade:

- **Must Have**: Requisitos essenciais que são críticos para o sucesso do projeto. A ausência de qualquer um deles compromete a entrega.
- **Should Have**: Requisitos importantes, mas não vitais. Sua ausência pode ser contornada sem afetar significativamente o projeto.
- **Could Have**: Requisitos desejáveis que podem melhorar a experiência do usuário ou a eficiência do sistema, mas que não são essenciais.
- **Won't Have (por agora)**: Requisitos acordados como de menor prioridade e que não serão implementados na atual fase do projeto, podendo ser considerados em futuras iterações.

A técnica MoSCoW facilita a comunicação entre stakeholders, ajuda a gerenciar expectativas e garante que os recursos sejam alocados de forma eficiente.

---

## Objetivos

- **Priorizar Requisitos**: Identificar e classificar os requisitos com base em sua importância e urgência.
- **Alinhar Expectativas**: Assegurar que todos os stakeholders tenham uma compreensão comum das prioridades do projeto.
- **Gerenciar Recursos**: Otimizar o uso de tempo e recursos, focando nos requisitos mais críticos.
- **Facilitar Planejamento**: Auxiliar na definição do escopo mínimo viável para entregas incrementais.

---

## Metodologia de Aplicação

1. **Levantamento de Requisitos**: Coleta de todos os requisitos identificados durante a fase de elicitação.
2. **Classificação**: Cada requisito é avaliado e classificado em uma das quatro categorias do MoSCoW, com base em sua importância para os objetivos do projeto.
3. **Validação com Stakeholders**: As classificações são revisadas e validadas com os stakeholders para garantir consenso.
4. **Revisões Periódicas**: As prioridades podem ser reavaliadas ao longo do projeto para refletir mudanças nas necessidades ou no contexto.

---

## Estrutura de Priorização

### Must Have
Requisitos essenciais para o funcionamento do sistema.

<p align="center">Tabela 1: Must have</p>

| **Tipo** | **Descrição**                                                                                                      | **Técnicas**                  | 
|----------|--------------------------------------------------------------------------------------------------------------------|-------------------------------|
| <a id="RF01"></a>RF01     | Permitir ao usuário pesquisar e filtrar clínicas e profissionais credenciados por especialidade, região administrativa, tipo de atendimento e proximidade. | [EN01](../elicitacao/tecnicas/entrevista.md#EN01), [EN02](../elicitacao/tecnicas/entrevista.md#EN02), [IS02](../elicitacao/tecnicas/introspeccao.md#IS02), [IS06](../elicitacao/tecnicas/introspeccao.md#IS06), [QT03](../elicitacao/tecnicas/questionario.md#QT03), [QT08](../elicitacao/tecnicas/questionario.md#QT08) |
| <a id="RF03"></a>RF03     | Exibir carteirinha digital mesmo sem conexão (modo offline) e permitir acesso rápido e estável.                    | [EN04](../elicitacao/tecnicas/entrevista.md#EN04), [IS09](../elicitacao/tecnicas/introspeccao.md#IS09), [QT01](../elicitacao/tecnicas/questionario.md#QT01)              |
| <a id="RF04"></a>RF04     | Enviar notificações configuráveis via app, SMS ou e-mail sobre ven e-mail sobre vencimento de fatura, retornos médicos pendentes, abertura de agenda, cancelamentos de horários, horários favoritos disponíveis, prazos importantes, confirmações ou alterações de agendamento e disponibilidade de demonstrativos de IR. | [EN05](../elicitacao/tecnicas/entrevista.md#EN05), [EN06](../elicitacao/tecnicas/entrevista.md#EN06), [GF02](../elicitacao/tecnicas/grupo_focal.md#GF02), [GF03](../elicitacao/tecnicas/grupo_focal.md#GF03), [GF07](../elicitacao/tecnicas/grupo_focal.md#GF07), [GF10](../elicitacao/tecnicas/grupo_focal.md#GF10), [IS07](../elicitacao/tecnicas/introspeccao.md#IS07), [IS12](../elicitacao/tecnicas/introspeccao.md#IS12), [QT06](../elicitacao/tecnicas/questionario.md#QT06) |
| <a id="RF05"></a>RF05     | Permitir agendamento e cancelamento de consultas e exames diretamente pelo aplicativo, com pagamento automático para prestadores da Rede de Atendimento. | [EN07](../elicitacao/tecnicas/entrevista.md#EN07), [GL01](../elicitacao/tecnicas/glossario.md#GL01), [IS01](../elicitacao/tecnicas/introspeccao.md#IS01), [IS05](../elicitacao/tecnicas/introspeccao.md#IS05), [GL06](../elicitacao/tecnicas/glossario.md#GL06)       |
| <a id="RF09"></a>RF09     | Permitir ao usuário visualizar histórico de consultas, exames realizados, resultados de exames laboratoriais e coparticipações. | [GF04](../elicitacao/tecnicas/grupo_focal.md#GF04), [GF08](../elicitacao/tecnicas/grupo_focal.md#GF08), [IS03](../elicitacao/tecnicas/introspeccao.md#IS03), [IS04](../elicitacao/tecnicas/introspeccao.md#IS04), [QT04](../elicitacao/tecnicas/questionario.md#QT04)  |
| <a id="RF15"></a>RF15     | Permitir baixar comprovantes de agendamento.                                                                       | [IS08](../elicitacao/tecnicas/introspeccao.md#IS08)                          |
| <a id="RNF01"></a>RNF01    | A interface deve ser intuitiva, clara, adaptada para idosos e pessoas com baixa familiaridade tecnológica, organizada em categorias e responsiva em smartphones Android e iOS. | [EN10](../elicitacao/tecnicas/entrevista.md#EN10), [GF13](../elicitacao/tecnicas/grupo_focal.md#GF13), [IS13](../elicitacao/tecnicas/introspeccao.md#IS13), [QT11](../elicitacao/tecnicas/questionario.md#QT11)        |
| <a id="RNF02"></a>RNF02    | Garantir carregamento rápido e fluído de todas as telas, com tempo de resposta das ações não ultrapassando 2 segundos. | [EN11](../elicitacao/tecnicas/entrevista.md#EN11), [GF17](../elicitacao/tecnicas/grupo_focal.md#GF17), [IS14](../elicitacao/tecnicas/introspeccao.md#IS14), [QT12](../elicitacao/tecnicas/questionario.md#QT12)        |
| <a id="RNF03"></a>RNF03    | Assegurar segurança no acesso e armazenamento de dados pessoais, criptografar dados sensíveis conforme LGPD, incluir autenticação em dois fatores e ser transparente quanto ao uso e segurança dos dados. | [EN12](../elicitacao/tecnicas/entrevista.md#EN12), [GL12](../elicitacao/tecnicas/glossario.md#GL12), [GF12](../elicitacao/tecnicas/grupo_focal.md#GF12), [GF14](../elicitacao/tecnicas/grupo_focal.md#GF14), [IS18](../elicitacao/tecnicas/introspeccao.md#IS18), [QT15](../elicitacao/tecnicas/questionario.md#QT15) |
| <a id="RNF05"></a>RNF05    | O sistema deve ser compatível com diferentes versões do Android e iOS, a partir das versões mais utilizadas no mercado. | [GF18](../elicitacao/tecnicas/grupo_focal.md#GF18), [IS17](../elicitacao/tecnicas/introspeccao.md#IS17), [QT11](../elicitacao/tecnicas/questionario.md#QT11)              |
| <a id="RNF07"></a>RNF07    | Garantir conformidade com a Portaria nº 127/2024, legislações complementares e padrões da LGPD.                    | [GL10](../elicitacao/tecnicas/glossario.md#GL10), [QT15](../elicitacao/tecnicas/questionario.md#QT15)                   |
| <a id="RNF10"></a>RNF10    | Garantir que informações críticas, como a carteirinha digital, estejam acessíveis em até três cliques ou com no máximo 2 cliques a partir da tela inicial. | [GF15](../elicitacao/tecnicas/grupo_focal.md#GF15), [IS16](../elicitacao/tecnicas/introspeccao.md#IS16)                    |
| <a id="RNF13"></a>RNF13    | Deve funcionar de forma offline para acesso à carteirinha e histórico de consultas.                               | [IS19](../elicitacao/tecnicas/introspeccao.md#IS19)                          |
| <a id="RNF16"></a>RNF16    | As informações exibidas devem ser claras, completas e atualizadas em tempo real.                                  | [QT13](../elicitacao/tecnicas/questionario.md#QT13)                          |


<font size="3"><p style="text-align: center">Fonte: [Lucas Alves](https://github.com/LucasAlves71) e [Kaleb Macedo](https://github.com/kalebmacedo).</p></font>

---

### Should Have
Requisitos importantes, mas que podem ser adiados se necessário.

<p align="center">Tabela 2: Should have</p>

| **Tipo** | **Descrição**                                                                                                      | **Técnicas**                  |
|----------|--------------------------------------------------------------------------------------------------------------------|-------------------------------|
| <a id="RF06"></a>RF06     | Exibir valor específico de consulta em cada clínica, aplicar percentuais de coparticipação, gerar e baixar demonstrativos de despesas médicas para imposto de renda, consultar histórico de demonstrativos de IR e mostrar extrato financeiro atualizado diariamente. | [EN08](../elicitacao/tecnicas/entrevista.md#EN08), [GL04](../elicitacao/tecnicas/glossario.md#GL04), [IS10](../elicitacao/tecnicas/introspeccao.md#IS10), [IS11](../elicitacao/tecnicas/introspeccao.md#IS11), [QT02](../elicitacao/tecnicas/questionario.md#QT02), [QT05](../elicitacao/tecnicas/questionario.md#QT05) |
| <a id="RF07"></a>RF07     | Permitir cadastro de titulares, dependentes e optantes com validação de documentos e elegibilidade.                | [GL01](../elicitacao/tecnicas/glossario.md#GL01), [GL08](../elicitacao/tecnicas/glossario.md#GL08), [GL09](../elicitacao/tecnicas/glossario.md#GL09)           |
| <a id="RF08"></a>RF08     | Verificar se procedimentos estão na TABGDFSAÚDE, atendem às DUT, estão sujeitos a carência ou são excluídos, exigindo solicitação médica e análise técnica para autorizações prévias. | [GL02](../elicitacao/tecnicas/glossario.md#GL02), [GL03](../elicitacao/tecnicas/glossario.md#GL03), [GL05](../elicitacao/tecnicas/glossario.md#GL05), [GL07](../elicitacao/tecnicas/glossario.md#GL07), [QT09](../elicitacao/tecnicas/questionario.md#QT09) |
| <a id="RF13"></a>RF13     | Adicionar consulta à rede odontológica.                                                                            | [QT07](../elicitacao/tecnicas/questionario.md#QT07)                          |
| <a id="RNF04"></a>RNF04    | Manter o sistema disponível 24/7 para autorizações de urgência/emergência e apresentar alta disponibilidade (mínimo de 99% uptime). | [GL11](../elicitacao/tecnicas/glossario.md#GL11), [QT10](../elicitacao/tecnicas/questionario.md#QT10)                   |
| <a id="RNF08"></a>RNF08    | Processar autorizações prévias em até 10 dias úteis.                                                              | [GL13](../elicitacao/tecnicas/glossario.md#GL13)                         | 
| <a id="RNF12"></a>RNF12    | O aplicativo deve oferecer suporte por chat ou telefone.                                                          | [IS15](../elicitacao/tecnicas/introspeccao.md#IS15)                          |
| <a id="RNF15"></a>RNF15    | O sistema deve exigir autenticação via GovBR para login.                                                          | [GF11](../elicitacao/tecnicas/grupo_focal.md#GF11)                          |


<font size="3"><p style="text-align: center">Fonte: [Lucas Alves](https://github.com/LucasAlves71) e [Kaleb Macedo](https://github.com/kalebmacedo).</p></font>

---

### Could Have
Requisitos desejáveis, mas que não são prioritários.

<p align="center">Tabela 3: Could have</p>

| **Tipo** | **Descrição**                                                                                                      | **Técnicas**                  |
|----------|--------------------------------------------------------------------------------------------------------------------|-------------------------------|
| <a id="RF02"></a>RF02     | Disponibilizar sistema de avaliação de clínicas com notas e comentários.                                           | [EN03](../elicitacao/tecnicas/entrevista.md#EN03), [GF01](../elicitacao/tecnicas/grupo_focal.md#GF01)                    |
| <a id="RF10"></a>RF10     | Permitir que o usuário favorite horários de consulta desejados.                                                    | [GF06](../elicitacao/tecnicas/grupo_focal.md#GF06)                          |
| <a id="RF12"></a>RF12     | Divulgar informações sobre novas funcionalidades no aplicativo.                                                    | [GF05](../elicitacao/tecnicas/grupo_focal.md#GF05)                          |
| <a id="RF14"></a>RF14     | Apresentar novas clínicas e clínicas próximas de acordo com a localização do usuário.                              | [EN09](../elicitacao/tecnicas/entrevista.md#EN09)                          |
| <a id="RNF09"></a>RNF09    | Comunicar-se com a folha de pagamento do GDF para descontos de mensalidades.                                       | [GL14](../elicitacao/tecnicas/glossario.md#GL14)                         |
| <a id="RNF11"></a>RNF11    | Manter histórico de notificações acessível ao usuário por no mínimo 6 meses.                                      | [GF16](../elicitacao/tecnicas/grupo_focal.md#GF16)                          |
| <a id="RNF14"></a>RNF14    | O layout deve ser consistente com o portal oficial do plano.                                                      | [QT16](../elicitacao/tecnicas/questionario.md#QT16)                          |

<font size="3"><p style="text-align: center">Fonte: [Lucas Alves](https://github.com/LucasAlves71) e [Kaleb Macedo](https://github.com/kalebmacedo).</p></font>

---

### Won't Have (por agora)
Requisitos que não serão implementados nesta fase do projeto.

<p align="center">Tabela 4: Won't have</p>

| **Tipo** | **Descrição**                                                                                                      | **Técnicas**                  |
|----------|--------------------------------------------------------------------------------------------------------------------|-------------------------------|
| <a id="RF11"></a>RF11     | Oferecer um canal para o usuário enviar feedback sobre atendimentos.                                               | [GF09](../elicitacao/tecnicas/grupo_focal.md#GF09)                          |
| <a id="RNF06"></a>RNF06    | O aplicativo deve ser compatível com leitores de tela para garantir acessibilidade a pessoas com deficiência visual. | [IS20](../elicitacao/tecnicas/introspeccao.md#IS20), [QT14](../elicitacao/tecnicas/questionario.md#QT14)                    |

<font size="3"><p style="text-align: center">Fonte: [Lucas Alves](https://github.com/LucasAlves71) e [Kaleb Macedo](https://github.com/kalebmacedo).</p></font>

---

## Referências

- SERRANO, Milene; SERRANO, Maurício. *Requisitos (Aula 07): Elicitação, Modelagem e Análise*. UnB Gama, Brasília, 2023. Disponível em: https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 2 de maio de 2025.
- Agile Business Consortium. *MoSCoW Prioritisation*. Disponível em: https://www.agilebusiness.org/dsdm-project-framework/moscow-prioririsation.html. Acesso em: 2 de maio de 2025.
- Visual Paradigm. *Prioritizing Requirements with MoSCoW Method: A Guide for Agile Projects*. Disponível em: https://guides.visual-paradigm.com/prioritizing-requirements-with-moscow-method-a-guide-for-agile-projects/. Acesso em: 2 de maio de 2025.

---

## Histórico de Versão

| Versão | Data       | Descrição                                      | Autor(es)                                   | Revisor(es) |
|--------|------------|------------------------------------------------|---------------------------------------------|-------------|
| 1.0    | 02/05/2025 | Criação do documento com introdução, objetivos, metodologia e estrutura de priorização | [Lucas Alves](https://github.com/LucasAlves71) e [Kaleb Macedo](https://github.com/kalebmacedo) | [Isaque Camargos](https://github.com/isaqzin) |
| 1.1    | 04/05/2025 | Adição dos requisitos e suas classificações | [Lucas Alves](https://github.com/LucasAlves71) e [Kaleb Macedo](https://github.com/kalebmacedo) | [Isaque Camargos](https://github.com/isaqzin) |
