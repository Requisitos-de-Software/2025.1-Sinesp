# First Thing First

## Introdução

Conforme Vazquez, Simões e Albert (2013) em *Engenharia de requisitos: software orientado ao negócio*, a priorização de requisitos é uma etapa crítica da engenharia de requisitos. Ela permite ordenar funcionalidades e características segundo critérios objetivos — valor de negócio, penalidade por não implementação, esforço de desenvolvimento e riscos — garantindo que a equipe concentre recursos no que traz maior retorno e reduz expose a riscos. A técnica *First Things First* combina esses fatores em um único índice para apoiar decisões consistentes e transparentes, essenciais em projetos com restrições de tempo e orçamento.


---

## Integrantes do Grupo

Na tabela 1 contêm todos os integrantes da equipe que participaram da priorização e o que a pessoa desenvolveu durante o projeto.

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
                <td><a href="https://github.com/Ana-Luiza-SC" target="_blank">Ana Luiza Soares</a></td>
                <td>Participou da priorização prensencial.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a></td>
                <td>Participou da priorização prensencial.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a></td>
                <td> Fez a documentação do arquivo e participou da priorização prensencial.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></td>
                <td>Participou da priorização prensencial.</td>
            </tr>
        </tbody>
    </table>
</div>

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> </p>

---

## Metodologia


Para tabular e priorizar cada requisito, foram realizadas três abordagens distintas:

1. **Primeira Tentativa (Personas):**

    Inicialmente, [Ana Luiza Soares](https://github.com/Ana-Luiza-SC), [Matheus de Alcântara](https://github.com/matheusdealcantara) e [Yzabella Miranda](https://github.com/redjsun) utilizaram *personas* fictícias para simular a priorização. 
    
    No entanto, essa abordagem foi **inutilizada**, pois não refletia adequadamente as necessidades reais do projeto.

2. **Segunda Tentativa (Online):**
    
    Foi conduzida uma priorização remota com [Othavio Bolzan](https://github.com/bolzanMGB), [Yzabella Miranda](https://github.com/redjsun) e **Gustavo Freitas** (usuário real que participou ativamente do preenchimento)

    Porém, esse método foi **descartado** após exigência de uma avaliação presencial com stakusuários reais.

3. **Terceira Tentativa (Presencial - Validação Final):**

    A priorização definitiva foi realizada presencialmente com [Ana Luiza Soares](https://github.com/Ana-Luiza-SC), [Matheus de Alcântara](https://github.com/matheusdealcantara), [Othavio Bolzan](https://github.com/bolzanMGB), [Yzabella Miranda](https://github.com/redjsun) e **Gustavo Freitas** (usuário real que validou as pontuações). Os critérios utilizados foram:

    - **Benefício relativo**: ganho operacional ou de negócio ao implementar.

    - **Penalidade relativa**: custo ou impacto de não implementar.

    - **Custo relativo**: esforço e recursos necessários.

    - **Risco relativo**: probabilidade de atrasos ou falhas.

Com isso, na tabela 2 está a priorização dos requisitos de **First Thing First**.



---

## Usuários reais envolvidos

A Tabela 1 contêm as informações do usuário participante da Priorização, com o nome, informações sobre a gravação realizada e sua postagem no Youtube de forma não listada.

<p align="center">Tabela 1: Usuários reais</p>

<div align="center">
    <table>
        <thead>
            <tr>
                <th>Nome</th>
                <th>Data</th>
                <th>Hora</th>
                <th>Duração da etapa</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Gustavo Freitas</td>
                <td>10/06/2025</td>
                <td>12:30</td>
                <td>28m 50s</td>
            </tr>
        </tbody>
    </table>
</div>

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> </p>

---


## Tabela de Priorização

<p align="center">Tabela 2 - Tabela de Priorização First Things First</p>

| id     | funcionalidades                                                                                                       | Benefício relativo | Penalidade relativa | Valor total | Valor %  | Custo relativo | Custo % | Risco relativo | Risco % | Prioridade       |
|--------|-----------------------------------------------------------------------------------------------------------------------|--------------------|---------------------|-------------|----------|----------------|---------|----------------|---------|------------------|
| RF13   | Adicionar consulta à rede odontológica.                                                                               | 7                  | 8                   | 15          | 15,00%   | 1              | 1,00%   | 1              | 1,00%   | 10               |
| RF02   | Disponibilizar sistema de avaliação de clínicas com notas e comentários.                                              | 6                  | 5                   | 11          | 11,00%   | 1              | 1,00%   | 3              | 3,00%   | 4,4              |
| RF10   | Permitir que o usuário favorite horários de consulta desejados.                                                       | 4                  | 3                   | 7           | 7,00%    | 1              | 1,00%   | 1              | 1,00%   | 4,666666667      |
| RF03   | Exibir carteirinha digital mesmo sem conexão (modo offline) e permitir acesso rápido e estável.                       | 9                  | 9                   | 18          | 18,00%   | 3              | 3,00%   | 1              | 1,00%   | 5,142857143      |
| RNF13  | Deve funcionar de forma offline para acesso à carteirinha e histórico de consultas.                                    | 9                  | 9                   | 18          | 18,00%   | 3              | 3,00%   | 2              | 2,00%   | 4,5              |
| RF01   | Permitir ao usuário pesquisar e filtrar clínicas e profissionais credenciados por especialidade, região administrativa, tipo de atendimento e proximidade. | 8                  | 8                   | 24          | 24,00%   | 3              | 3,00%   | 7              | 7,00%   | 3,692307692      |
| RF12   | Divulgar informações sobre novas funcionalidades no aplicativo.                                                       | 3                  | 1                   | 4           | 4,00%    | 1              | 1,00%   | 1              | 1,00%   | 2,666666667      |
| RF15   | Permitir baixar comprovantes de agendamento.                                                                          | 5                  | 5                   | 10          | 10,00%   | 3              | 3,00%   | 2              | 2,00%   | 2,5              |
| RNF10  | Garantir que informações críticas, como a carteirinha digital, estejam acessíveis em até três cliques ou com no máximo 2 cliques a partir da tela inicial. | 5                  | 4                   | 9           | 9,00%    | 3              | 3,00%   | 1              | 1,00%   | 2,571428571      |
| RNF12  | O aplicativo deve oferecer suporte por chat ou telefone.                                                              | 7                  | 7                   | 14          | 14,00%   | 4              | 4,00%   | 2              | 2,00%   | 2,8              |
| RF08   | Verificar se procedimentos estão na TABGDFSAÚDE, atendem às DUT, estão sujeitos a carência ou são excluídos, exigindo solicitação médica e análise técnica para autorizações prévias. | 7                  | 6                   | 13          | 13,00%   | 3              | 3,00%   | 6              | 6,00%   | 2,166666667      |
| RNF14  | O layout deve ser consistente com o portal oficial do plano.                                                           | 2                  | 1                   | 3           | 3,00%    | 2              | 2,00%   | 1              | 1,00%   | 1,2              |
| RNF11  | Manter histórico de notificações acessível ao usuário por no mínimo 6 meses.                                          | 5                  | 6                   | 11          | 11,00%   | 5              | 5,00%   | 3              | 3,00%   | 1,692307692      |
| RF09   | Permitir ao usuário visualizar histórico de consultas, exames realizados, resultados de exames laboratoriais e coparticipações. | 9                  | 8                   | 17          | 17,00%   | 5              | 5,00%   | 5              | 5,00%   | 2,266666667      |
| RF11   | Oferecer um canal para o usuário enviar feedback sobre atendimentos.                                                  | 5                  | 5                   | 10          | 10,00%   | 4              | 4,00%   | 2              | 2,00%   | 2                |
| RNF16  | As informações exibidas devem ser claras, completas e atualizadas em tempo real.                                       | 8                  | 9                   | 17          | 17,00%   | 6              | 6,00%   | 6              | 6,00%   | 1,888888889      |
| RNF01  | A interface deve ser intuitiva, clara, adaptada para idosos e pessoas com baixa familiaridade tecnológica, organizada em categorias e responsiva em smartphones Android e iOS. | 7                  | 8                   | 15          | 15,00%   | 7              | 7,00%   | 4              | 4,00%   | 1,666666667      |
| RF04   | Enviar notificações configuráveis via app, SMS ou e-mail sobre vencimento de fatura, retornos médicos pendentes, abertura de agenda, cancelamentos de horários, horários favoritos disponíveis, prazos importantes, confirmações ou alterações de agendamento e disponibilidade de demonstrativos de IR. | 7                  | 7                   | 14          | 14,00%   | 5              | 5,00%   | 7              | 7,00%   | 1,647058824      |
| RF14   | Apresentar novas clínicas e clínicas próximas de acordo com a localização do usuário.                                 | 8                  | 8                   | 16          | 16,00%   | 5              | 5,00%   | 6              | 6,00%   | 2                |
| RNF04  | Manter o sistema disponível 24/7 para autorizações de urgência/emergência e apresentar alta disponibilidade (mínimo de 99% uptime). | 9                  | 9                   | 18          | 18,00%   | 8              | 8,00%   | 7              | 7,00%   | 1,565217391      |
| RNF06  | O aplicativo deve ser compatível com leitores de tela para garantir acessibilidade a pessoas com deficiência visual.  | 7                  | 8                   | 15          | 15,00%   | 7              | 7,00%   | 5              | 5,00%   | 1,578947368      |
| RNF02  | Garantir carregamento rápido e fluído de todas as telas, com tempo de resposta das ações não ultrapassando 2 segundos. | 5                  | 5                   | 10          | 10,00%   | 8              | 8,00%   | 3              | 3,00%   | 1,052631579      |
| RF07   | Permitir cadastro de titulares, dependentes e optantes com validação de documentos e elegibilidade.                    | 5                  | 5                   | 10          | 10,00%   | 8              | 8,00%   | 6              | 6,00%   | 0,9090909091     |
| RNF03  | Assegurar segurança no acesso e armazenamento de dados pessoais, criptografar dados sensíveis conforme LGPD, incluir autenticação em dois fatores e ser transparente quanto ao uso e segurança dos dados. | 6                  | 9                   | 15          | 15,00%   | 8              | 8,00%   | 9              | 9,00%   | 1,2              |
| RNF05  | O sistema deve ser compatível com diferentes versões do Android e iOS, a partir das versões mais utilizadas no mercado. | 6                  | 7                   | 13          | 13,00%   | 8              | 8,00%   | 8              | 8,00%   | 1,083333333      |
| RNF09  | Comunicar-se com a folha de pagamento do GDF para descontos de mensalidades.                                          | 4                  | 4                   | 8           | 8,00%    | 5              | 5,00%   | 6              | 6,00%   | 1                |
| RNF08  | Processar autorizações prévias em até 10 dias úteis.                                                                  | 7                  | 5                   | 12          | 12,00%   | 8              | 8,00%   | 7              | 7,00%   | 1,043478261      |
| RNF07  | Garantir conformidade com a Portaria nº 127/2024, legislações complementares e padrões da LGPD.                       | 6                  | 8                   | 14          | 14,00%   | 8              | 8,00%   | 9              | 7,00%   | 1,217391304      |
| RF06   | Exibir valor específico de consulta em cada clínica, aplicar percentuais de coparticipação, gerar e baixar demonstrativos de despesas médicas para imposto de renda, consultar histórico de demonstrativos de IR e mostrar extrato financeiro atualizado diariamente. | 7                  | 6                   | 13          | 13,00%   | 6              | 6,00%   | 5              | 5,00%   | 1,529411765      |
| RF05   | Permitir agendamento e cancelamento de consultas e exames diretamente pelo aplicativo, com pagamento automático para prestadores da Rede de Atendimento. | 9                  | 7                   | 16          | 16,00%   | 9              | 9,00%   | 9              | 9,00%   | 1,185185185      |
| RNF15  | O sistema deve exigir autenticação via GovBR para login.                                                              | 7                  | 7                   | 14          | 14,00%   | 7              | 7,00%   | 7              | 7,00%   | 1,333333333      |


<br>
<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a>, <a href="https://github.com/redjsun">Yzabella Miranda</a>, <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a>  e <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> </p>

---

## Gravação da  priorização da lista

A priorização da lista foio gravada e pode ser vista na Gravação 1.

<div align="center">
    <p><strong>Gravação 1</strong> (gravação First Thing First (1))</p>
    <iframe width="560" height="315" src="https://www.youtube.com/watch?v=uR6bilKISNk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

---

## Referências

VAZQUEZ, Bruno; SIMÕES, André; ALBERT, Endrew. *Engenharia de requisitos: software orientado ao negócio*. 1. ed. Rio de Janeiro: Elsevier, 2013. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096085/mod_resource/content/4/Elicitacao%20de%20Req%202.pdf>. Acesso em: 3 maio 2025.

---

## Histótico de versões

| Versão | Data       | Descrição                                            | Autor(es)                                                                                                  | Revisor(es)                                   |
|--------|------------|------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| 1.0    | 03/05/2025 | Criação do documento de priorização                  | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC), [Yzabella Miranda](https://github.com/redjsun) e [Matheus de Alcântara](https://github.com/matheusdealcantara)        | [Isaque Camargos](https://github.com/isaqzin) |
| 2.0    | 20/06/2025 | Criação do documento de priorização                  | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC), [Yzabella Miranda](https://github.com/redjsun), [Matheus de Alcântara](https://github.com/matheusdealcantara)   e <a href="https://github.com/bolzanMGB">Othavio Bolzan</a>      | [Isaque Camargos](https://github.com/isaqzin) |

