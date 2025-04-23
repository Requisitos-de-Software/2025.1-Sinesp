# Introspecção

## Introdução

A introspecção é uma técnica de elicitação de requisitos baseada na imaginação de cenários hipotéticos de uso. Por meio de uma análise individual, os participantes se colocam no lugar de um usuário comum do sistema e descrevem funcionalidades e características desejadas. Esta seção apresenta os requisitos funcionais e não funcionais elicitados para o aplicativo **GDF Saúde** por meio dessa técnica.

## Metodologia

O processo de introspecção foi conduzido individualmente pelos participantes [Lucas Alves Oliveira dos Santos](https://github.com/LucasAlves71) e [Othavio Araujo Bolzan](https://github.com/bolzanMGB), seguindo o cronograma apresentado na tabela 1. Cada participante imaginou-se utilizando o aplicativo GDF Saúde em situações diversas. A partir dessas cenários hipotéticos de usos, foram definidos os requisitos desejados, que foram organizados em duas tabelas: **Requisitos Funcionais (Tabela 2)** e **Requisitos Não-Funcionais (Tabela 3)**.

## Cronograma - tabela 1

<font size="3"><p style="text-align: center">Tabela 1: Participantes da técnica de elicitação introspecção.</p></font>

<center>

| Nome                                             | Data                   |  Hora |
| ------------------------------------------------ | ------------------------ | -------------- |
| [Othavio Bolzan](https://github.com/bolzanMGB)   |  23/04/2025|  09:10 |
| [Lucas Alves](https://github.com/LucasAlves71) |  23/04/2025|   10:00 |

</center>

<font size="3"><p style="text-align: center">Fonte: [Lucas Alves](https://github.com/LucasAlves71) e [Othavio Bolzan](https://github.com/bolzanMGB).</p></font>


## Participantes

### [Othavio Bolzan](https://github.com/bolzanMGB)

Já que o aplicativo oferece serviços de um plano de saúde, imaginei-me como um beneficiário buscando uma rede credenciada próxima que oferecesse atendimentos com neurologistas. A partir disso, refleti sobre os filtros e funcionalidades que o aplicativo deveria oferecer, bem como sobre sua interface, de modo a facilitar a experiência do usuário.

### [Lucas Alves](https://github.com/LucasAlves71)

Considerando que o aplicativo é destinado a beneficiários de um plano de saúde, pensei na importância de incluir uma seção financeira de fácil acesso. Isso se deve à necessidade de acessar documentos como o demonstrativo de despesas médicas para o imposto de renda, exigido ao menos uma vez por ano, ou mesmo para solicitar reembolsos de consultas e procedimentos não cobertos pelo plano. Portanto, essa funcionalidade se mostra essencial e bastante útil para os usuários da aplicação.

---

## Requisitos Elicitados

### Legenda para as tabelas 2 e 3

- **RFx**: Requisito Funcional nº x  
- **RNFx**: Requisito Não-Funcional nº x  
- **ISx**: Requisito nº x elicitado pela introspecção  

### Tabela 2: Requisitos Funcionais

<center>

| Tipo | Descrição | ID | Implementado |
|------|-----------|----|--------------|
| RF01 | O aplicativo permite agendar consultas médicas. | IS01 | Não |
| RF02 | O aplicativo mostra e possibilita filtrar a lista de médicos, exames e especialidades disponíveis. | IS02 | Sim |
| RF03 | O aplicativo permite consultar o resultado de exames laboratoriais. | IS03 | Sim |
| RF04 | O aplicativo permite consultar o histórico de atendimentos. | IS04 | Sim |
| RF05 | O aplicativo permite cancelar consultas. | IS05 | Não |
| RF06 | O aplicativo exibe e filtra locais de atendimento próximos. | IS06 | Sim |
| RF07 | O aplicativo envia notificações de confirmação ou alteração de agendamento. | IS07 | Não |
| RF08 | O aplicativo permite baixar comprovantes de agendamento. | IS08 | Não |
| RF09 | O aplicativo permite acessar a carteirinha digital do plano | IS09 | Sim |
| RF10 | O aplicativo permite gerar e baixar demonstrativos de despesas médicas para imposto de renda. | IS10 | Sim |
| RF11 | O aplicativo permite consultar o histórico de demonstrativos de IR de anos anteriores. | IS11 | Sim |
| RF12 | O aplicativo envia notificação quando o demonstrativo de IR estiver disponível. | IS12 | Não |

</center>

<font size="3"><p style="text-align: center">Fonte: [Lucas Alves](https://github.com/LucasAlves71) e [Othavio Bolzan](https://github.com/bolzanMGB).</p></font>

### Tabela 3: Requisitos Não-Funcionais

<center>

| Tipo | Descrição | ID | Implementado |
|------|-----------|----|--------------|
| RNF01 | Deve ter interface clara e adaptada para idosos e pessoas com baixa familiaridade tecnológica. | IS13 | Parcial |
| RNF02 | O tempo médio de resposta entre telas não deve ultrapassar 2 segundos. | IS14 | Sim |
| RNF03 | O aplicativo deve oferecer suporte por chat ou telefone. | IS15 | Sim |
| RNF04 | A carteirinha digital deve ser acessível com no máximo 2 cliques a partir da tela inicial. | IS16 | Sim |
| RNF05 | Deve estar disponível para Android e iOS. | IS17 | Sim |
| RNF06 | Deve apresentar alto nível de segurança no armazenamento de dados sensíveis (como CPF e resultados médicos). | IS18 | Sim |
| RNF07 | Deve funcionar de forma offline para acesso à carteirinha e histórico de consultas. | IS19 | Não |
| RNF08 | O aplicativo deve ser compatível com leitores de tela para garantir acessibilidade a pessoas com deficiencia visual. | IS20 | Não |

</center>

<font size="3"><p style="text-align: center">Fonte: [Lucas Alves](https://github.com/LucasAlves71) e [Othavio Bolzan](https://github.com/bolzanMGB).</p></font>

---

## Considerações Finais

A técnica de introspecção revelou-se eficaz para identificar requisitos que refletem as necessidades reais dos usuários do aplicativo **GDF Saúde**. Os requisitos elicitados destacam tanto funcionalidades já implementadas quanto oportunidades de melhoria, como a inclusão de suporte offline e maior acessibilidade para pessoas com deficiência visual. Além disso, a análise evidenciou a importância de uma interface intuitiva e de funcionalidades financeiras acessíveis, que atendam às demandas específicas dos beneficiários. Esses insights reforçam o potencial do aplicativo em oferecer uma experiência mais completa e inclusiva, alinhada às expectativas dos usuários. A introspecção, portanto, contribuiu significativamente para a compreensão das necessidades do público-alvo e para o direcionamento de futuras melhorias no aplicativo.
---

## Bibliografia

- SERRANO, Milene; SERRANO, Maurício. *Requisitos (Aula 07): Elicitação, Modelagem e Análise*. UnB Gama, Brasília, 2023. Disponível em: https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 23/04/2025.

---

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|-----------|-----------|-------------|
| 1.0 | 23/04/2025 | Introdução e requisitos iniciais | [Lucas Alves](https://github.com/LucasAlves71) e [Othavio Bolzan](https://github.com/bolzanMGB) | [Kaleb Macedo](https://github.com/kalebmacedo) |
| 1.1 | 23/04/2025 | Revisão e ajustes nas tabelas | [Lucas Alves](https://github.com/LucasAlves71) e [Othavio Bolzan](https://github.com/bolzanMGB) | [Kaleb Macedo](https://github.com/kalebmacedo) |
