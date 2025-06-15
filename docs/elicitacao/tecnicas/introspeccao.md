# Introspecção

## Introdução

A introspecção é uma técnica de elicitação de requisitos baseada na imaginação de cenários hipotéticos de uso. Por meio de uma análise individual, os participantes se colocam no lugar de um usuário comum do sistema e descrevem funcionalidades e características desejadas. Esta seção apresenta os requisitos funcionais e não funcionais elicitados para o aplicativo **GDF Saúde** por meio dessa técnica.

## Integrantes do Grupo

Na tabela 1 contêm todos os integrantes da equipe que participaram na construção deste documento e o que cada pessoa desenvolveu durante o projeto.

<p align="center">Tabela 1 - Integrantes do grupo envolvidos</p>

<div align="center">
  <table>
    <thead>
      <tr>
        <th>Nome</th>
        <th>Quais etapas participou</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><a href="https://github.com/LucasAlves71">Lucas Alves</a></td>
        <td>Criação da introdução, elaboração dos requisitos iniciais e revisão da tabela.</td>
      </tr>
      <tr>
        <td><a href="https://github.com/bolzanMGB">Othavio Bolzan</a></td>
        <td>Criação da introdução e elaboração dos requisitos iniciais.</td>
      </tr>
       <tr>
        <td><a href="https://github.com/kalebmacedo">Kaleb Macedo</a></td>
        <td>Revisão completa do documento e ajuste das tabelas.</td>
      </tr>
    </tbody>
  </table>
</div>

<p align="center">Fonte: Autoria de <a href="https://github.com/kalebmacedo">Kaleb Macedo</a></p>

## Metodologia

O processo de introspecção foi conduzido individualmente pelos participantes [Lucas Alves Oliveira dos Santos](https://github.com/LucasAlves71) e [Othavio Araujo Bolzan](https://github.com/bolzanMGB), seguindo o cronograma apresentado na tabela 1. Cada participante imaginou-se utilizando o aplicativo GDF Saúde em situações diversas. A partir dessas cenários hipotéticos de usos, foram definidos os requisitos desejados, que foram organizados em duas tabelas: **Requisitos Funcionais (Tabela 2)** e **Requisitos Não-Funcionais (Tabela 3)**.

## Cronograma - tabela 1

<font size="3"><p style="text-align: center">Tabela 1: Participantes da técnica de elicitação introspecção.</p></font>



<div style="display: flex; justify-content: center;">
  <table>
    <thead>
      <tr>
        <th>Nome</th>
        <th>Data</th>
        <th>Hora</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><a href="https://github.com/bolzanMGB">Othavio Bolzan</a></td>
        <td>23/04/2025</td>
        <td>09:10</td>
      </tr>
      <tr>
        <td><a href="https://github.com/LucasAlves71">Lucas Alves</a></td>
        <td>23/04/2025</td>
        <td>10:00</td>
      </tr>
    </tbody>
  </table>
</div>

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


| Tipo | Descrição | ID | Implementado |
|------|-----------|----|--------------|
| [RF05](../../elicitacao/elicitacao.md#RF05) | O aplicativo permite agendar consultas médicas. | <a id="IS01"></a>IS01 | Não |
| [RF01](../../elicitacao/elicitacao.md#RF01) | O aplicativo mostra e possibilita filtrar a lista de médicos, exames e especialidades disponíveis. | <a id="IS02"></a>IS02 | Sim |
| [RF09](../../elicitacao/elicitacao.md#RF09) | O aplicativo permite consultar o resultado de exames laboratoriais. | <a id="IS03"></a>IS03 | Não |
| [RF09](../../elicitacao/elicitacao.md#RF09) | O aplicativo permite consultar o histórico de atendimentos. | <a id="IS04"></a>IS04 | Sim |
| [RF05](../../elicitacao/elicitacao.md#RF05) | O aplicativo permite cancelar consultas. | <a id="IS05"></a>IS05 | Não |
| [RF01](../../elicitacao/elicitacao.md#RF01) | O aplicativo exibe e filtra locais de atendimento próximos. | <a id="IS06"></a>IS06 | Sim |
| [RF04](../../elicitacao/elicitacao.md#RF04)| O aplicativo envia notificações de confirmação ou alteração de agendamento. | <a id="IS07"></a>IS07 | Não |
| [RF15](../../elicitacao/elicitacao.md#RF15) | O aplicativo permite baixar comprovantes de agendamento. | <a id="IS08"></a>IS08 | Não |
| [RF03](../../elicitacao/elicitacao.md#RF03) | O aplicativo permite acessar a carteirinha digital do plano | <a id="IS09"></a>IS09 | Sim |
| [RF06](../../elicitacao/elicitacao.md#RF06) | O aplicativo permite gerar e baixar demonstrativos de despesas médicas para imposto de renda. | <a id="IS10"></a>IS10 | Sim |
| [RF06](../../elicitacao/elicitacao.md#RF06) | O aplicativo permite consultar o histórico de demonstrativos de IR de anos anteriores. | <a id="IS11"></a>IS11 | Sim |
| [RF04](../../elicitacao/elicitacao.md#RF01) | O aplicativo envia notificação quando o demonstrativo de IR estiver disponível. | <a id="IS12"></a>IS12 | Não |


<font size="3"><p style="text-align: center">Fonte: [Lucas Alves](https://github.com/LucasAlves71) e [Othavio Bolzan](https://github.com/bolzanMGB).</p></font>

### Tabela 3: Requisitos Não-Funcionais


| Tipo | Descrição | ID | Implementado |
|------|-----------|----|--------------|
| [RNF01](../../elicitacao/elicitacao.md#RNF01) | Deve ter interface clara e adaptada para idosos e pessoas com baixa familiaridade tecnológica. | <a id="IS13"></a>IS13 | Não |
| [RNF02](../../elicitacao/elicitacao.md#RNF02) | O tempo médio de resposta entre telas não deve ultrapassar 2 segundos. | <a id="IS14"></a>IS14 | Sim |
| [RNF12](../../elicitacao/elicitacao.md#RNF12)| O aplicativo deve oferecer suporte por chat ou telefone. | <a id="IS15"></a>IS15 | Sim |
| [RNF10](../../elicitacao/elicitacao.md#RNF10) | A carteirinha digital deve ser acessível com no máximo 2 cliques a partir da tela inicial. | <a id="IS06"></a>IS16 | Sim |
| [RNF05](../../elicitacao/elicitacao.md#RNF05) | Deve estar disponível para Android e iOS. | <a id="IS17"></a>IS17 | Sim |
| [RNF03](../../elicitacao/elicitacao.md#RNF03) | Deve apresentar alto nível de segurança no armazenamento de dados sensíveis (como CPF e resultados médicos). | <a id="IS18"></a>IS18 | Sim |
| [RNF13](../../elicitacao/elicitacao.md#RF13) | Deve funcionar de forma offline para acesso à carteirinha e histórico de consultas. | <a id="IS19"></a>IS19 | Não |
| [RNF06](../../elicitacao/elicitacao.md#RF01) | O aplicativo deve ser compatível com leitores de tela para garantir acessibilidade a pessoas com deficiencia visual. | <a id="IS20"></a>IS20 | Não |



<font size="3"><p style="text-align: center">Fonte: [Lucas Alves](https://github.com/LucasAlves71) e [Othavio Bolzan](https://github.com/bolzanMGB).</p></font>

---

## Considerações Finais

A técnica de introspecção revelou-se eficaz para identificar requisitos que refletem as necessidades reais dos usuários do aplicativo **GDF Saúde**. Os requisitos elicitados destacam tanto funcionalidades já implementadas quanto oportunidades de melhoria, como a inclusão de suporte offline e maior acessibilidade para pessoas com deficiência visual. Além disso, a análise evidenciou a importância de uma interface intuitiva e de funcionalidades financeiras acessíveis, que atendam às demandas específicas dos beneficiários. Esses insights reforçam o potencial do aplicativo em oferecer uma experiência mais completa e inclusiva, alinhada às expectativas dos usuários. A introspecção, portanto, contribuiu significativamente para a compreensão das necessidades do público-alvo e para o direcionamento de futuras melhorias no aplicativo.

---

## Vídeo de apresentação da Elicitação
- **Reunião de Apresentação - Introspecção** – Apresentação da elicitação de requisitos introspecção  
  🔗 [Assistir no YouTube](https://youtu.be/N8buZteffsk)

## Bibliografia

- SERRANO, Milene; SERRANO, Maurício. *Requisitos (Aula 07): Elicitação, Modelagem e Análise*. UnB Gama, Brasília, 2023. Disponível em: https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 23/04/2025.

---

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|-----------|-----------|-------------|
| 1.0 | 23/04/2025 | Introdução e requisitos iniciais | [Lucas Alves](https://github.com/LucasAlves71) e [Othavio Bolzan](https://github.com/bolzanMGB) | [Kaleb Macedo](https://github.com/kalebmacedo) |
| 1.1 | 23/04/2025 | Revisão e ajustes nas tabelas | [Lucas Alves](https://github.com/LucasAlves71) e [Othavio Bolzan](https://github.com/bolzanMGB) | [Kaleb Macedo](https://github.com/kalebmacedo) |