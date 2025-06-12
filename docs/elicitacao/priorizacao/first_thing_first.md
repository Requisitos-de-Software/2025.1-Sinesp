# First Thing First

## Introdução

Conforme Vazquez, Simões e Albert (2013) em *Engenharia de requisitos: software orientado ao negócio*, a priorização de requisitos é uma etapa crítica da engenharia de requisitos. Ela permite ordenar funcionalidades e características segundo critérios objetivos — valor de negócio, penalidade por não implementação, esforço de desenvolvimento e riscos — garantindo que a equipe concentre recursos no que traz maior retorno e reduz expose a riscos. A técnica *First Things First* combina esses fatores em um único índice para apoiar decisões consistentes e transparentes, essenciais em projetos com restrições de tempo e orçamento.


## Integrantes do Grupo

Na tabela 1 contêm todos os integrantes da equipe que participaram na construção dos cenários e o que a pessoa desenvolveu durante o projeto.

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
                <td>Criou os cenários: 1, 2, 21, 22, 23 e 24. Além disso, consolidou o documento final ao pegar os cenários separados, que se encontravam na plataforma <a href="https://stackedit.io/app#">StackEdit</a> e organizar no documento final para o Github Pages. Além disso refatorou os cenários para fazerem sentido para os novos requisitos finais e arrumou a rastreabilidade de todos os requisitos do antigo para o novo</td>
            </tr>
            <tr>
                <td><a href="https://github.com/isaqzin" target="_blank">Isaque Camargos</a></td>
                <td> Inicou o documento criando a introdução e criou os cenários: 3, 4, 19, 25, 25 e 26.</td>
            </tr>
            <tr>
                <td><a href="https://github.com/matheusdealcantara" target="_blank">Matheus de Alcântara</a></td>
                <td></td>
            </tr>
            <tr>
                <td><a href="https://github.com/bolzanMGB" target="_blank">Othavio Bolzan</a></td>
                <td></td>
            </tr>
            <tr>
                <td><a href="https://github.com/redjsun" target="_blank">Yzabella Miranda</a></td>
                <td></td>
            </tr>
        </tbody>
    </table>
</div>

<p  align="center">Fonte: Autoria de <a  href="https://github.com/isaqzin">Isaque Camargos</a>, <a  href="https://github.com/isaqzin">Yzabella Miranda</a> e <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a></p>

## Metodologia

Para tabular e priorizar cada requisito, [Ana Luiza Soares](https://github.com/Ana-Luiza-SC), [Matheus de Alcantara](https://github.com/matheusdealcantara) e [Yzabella Miranda](https://github.com/redjsun) atuaram como personas e desenvolvedores. Cada requisito foi pontuado em quatro dimensões:

- **Benefício relativo**: ganho operacional ou de negócio ao implementar  
- **Penalidade relativa**: custo ou impacto de não implementar  
- **Custo relativo**: esforço e recursos necessários  
- **Risco relativo**: probabilidade de atrasos ou falhas  

Com isso, na tabela 1 está a priorização dos requisitos de **First Thing First**.

## Tabela de Priorização

<p align="center">Tabela 1 - Tabela de Priorização First Things First</p>

| id    | funcionalidades | Benefício relativo | Penalidade relativa | Valor total | Valor % | Custo relativo | Custo % | Risco relativo | Risco % | Prioridade |
|-------|------------------|--------------------|----------------------|-------------|---------|----------------|---------|----------------|---------|------------|
| RF13  | Adicionar consulta à rede odontológica. | 7 | 5 | 12 | 12,00% | 1 | 1,00% | 1 | 1,00% | 8 |
| RF02  | Disponibilizar sistema de avaliação de clínicas com notas e comentários. | 6 | 8 | 14 | 14,00% | 1 | 1,00% | 3 | 3,00% | 5,6 |
| RF10  | Permitir que o usuário favorite horários de consulta desejados. | 4 | 4 | 8 | 8,00% | 1 | 1,00% | 1 | 1,00% | 5,333333333 |
| RF03  | Exibir carteirinha digital mesmo sem conexão (modo offline) e permitir acesso rápido e estável. | 9 | 9 | 18 | 18,00% | 3 | 3,00% | 1 | 1,00% | 5,142857143 |
| RNF13 | Deve funcionar de forma offline para acesso à carteirinha e histórico de consultas. | 9 | 9 | 18 | 18,00% | 3 | 3,00% | 2 | 2,00% | 4,5 |
| RF01  | Permitir ao usuário pesquisar e filtrar clínicas e profissionais credenciados por especialidade, região administrativa, tipo de atendimento e proximidade. | 9 | 8 | 26 | 26,00% | 3 | 3,00% | 7 | 7,00% | 4 |
| RF12  | Divulgar informações sobre novas funcionalidades no aplicativo. | 4 | 2 | 6 | 6,00% | 1 | 1,00% | 1 | 1,00% | 4 |
| RF15  | Permitir baixar comprovantes de agendamento. | 7 | 8 | 15 | 15,00% | 3 | 3,00% | 2 | 2,00% | 3,75 |
| RNF10 | Garantir que informações críticas, como a carteirinha digital, estejam acessíveis em até três cliques ou com no máximo 2 cliques a partir da tela inicial. | 8 | 5 | 13 | 13,00% | 3 | 3,00% | 1 | 1,00% | 3,714285714 |
| RNF12 | O aplicativo deve oferecer suporte por chat ou telefone. | 9 | 8 | 17 | 17,00% | 4 | 4,00% | 2 | 2,00% | 3,4 |
| RF08  | Verificar se procedimentos estão na TABGDFSAÚDE, atendem às DUT, estão sujeitos a carência ou são excluídos, exigindo solicitação médica e análise técnica para autorizações prévias. | 9 | 8 | 17 | 17,00% | 3 | 3,00% | 6 | 6,00% | 2,833333333 |
| RNF14 | O layout deve ser consistente com o portal oficial do plano. | 4 | 3 | 7 | 7,00% | 2 | 2,00% | 1 | 1,00% | 2,8 |
| RNF11 | Manter histórico de notificações acessível ao usuário por no mínimo 6 meses. | 7 | 7 | 14 | 14,00% | 5 | 5,00% | 1 | 1,00% | 2,545454545 |
| RF09  | Permitir ao usuário visualizar histórico de consultas, exames realizados, resultados de exames laboratoriais e coparticipações. | 9 | 7 | 16 | 16,00% | 5 | 5,00% | 5 | 5,00% | 2,133333333 |
| RF11  | Oferecer um canal para o usuário enviar feedback sobre atendimentos. | 6 | 4 | 10 | 10,00% | 4 | 4,00% | 2 | 2,00% | 2 |
| RNF16 | As informações exibidas devem ser claras, completas e atualizadas em tempo real. | 9 | 9 | 18 | 18,00% | 6 | 6,00% | 6 | 6,00% | 2 |
| RNF01 | A interface deve ser intuitiva, clara, adaptada para idosos e pessoas com baixa familiaridade tecnológica, organizada em categorias e responsiva em smartphones Android e iOS. | 9 | 9 | 18 | 18,00% | 7 | 7,00% | 4 | 4,00% | 2 |
| RF04  | Enviar notificações configuráveis via app, SMS ou e-mail sobre vencimento de fatura, retornos médicos pendentes, abertura de agenda, cancelamentos de horários, horários favoritos disponíveis, prazos importantes, confirmações ou alterações de agendamento e disponibilidade de demonstrativos de IR. | 8 | 7 | 15 | 15,00% | 5 | 5,00% | 7 | 7,00% | 1,764705882 |
| RF14  | Apresentar novas clínicas e clínicas próximas de acordo com a localização do usuário. | 8 | 6 | 14 | 14,00% | 5 | 5,00% | 6 | 6,00% | 1,75 |
| RNF04 | Manter o sistema disponível 24/7 para autorizações de urgência/emergência e apresentar alta disponibilidade (mínimo de 99% uptime). | 9 | 9 | 18 | 18,00% | 7 | 7,00% | 7 | 7,00% | 1,714285714 |
| RNF06 | O aplicativo deve ser compatível com leitores de tela para garantir acessibilidade a pessoas com deficiência visual. | 8 | 8 | 16 | 16,00% | 7 | 7,00% | 5 | 5,00% | 1,684210526 |
| RNF02 | Garantir carregamento rápido e fluído de todas as telas, com tempo de resposta das ações não ultrapassando 2 segundos. | 8 | 8 | 16 | 16,00% | 8 | 8,00% | 3 | 3,00% | 1,684210526 |
| RF07  | Permitir cadastro de titulares, dependentes e optantes com validação de documentos e elegibilidade. | 8 | 8 | 16 | 16,00% | 8 | 8,00% | 6 | 6,00% | 1,454545455 |
| RNF03 | Assegurar segurança no acesso e armazenamento de dados pessoais, criptografar dados sensíveis conforme LGPD, incluir autenticação em dois fatores e ser transparente quanto ao uso e segurança dos dados. | 9 | 9 | 18 | 18,00% | 8 | 8,00% | 9 | 9,00% | 1,44 |
| RNF05 | O sistema deve ser compatível com diferentes versões do Android e iOS, a partir das versões mais utilizadas no mercado. | 7 | 8 | 15 | 15,00% | 8 | 8,00% | 8 | 8,00% | 1,25 |
| RNF09 | Comunicar-se com a folha de pagamento do GDF para descontos de mensalidades. | 5 | 5 | 10 | 10,00% | 5 | 5,00% | 6 | 6,00% | 1,25 |
| RNF08 | Processar autorizações prévias em até 10 dias úteis. | 6 | 7 | 13 | 13,00% | 8 | 8,00% | 7 | 7,00% | 1,130434783 |
| RNF07 | Garantir conformidade com a Portaria nº 127/2024, legislações complementares e padrões da LGPD. | 7 | 7 | 14 | 14,00% | 8 | 8,00% | 9 | 7,00% | 1,217391304 |
| RF06  | Exibir valor específico de consulta em cada clínica, aplicar percentuais de coparticipação, gerar e baixar demonstrativos de despesas médicas para imposto de renda, consultar histórico de demonstrativos de IR e mostrar extrato financeiro atualizado diariamente. | 4 | 5 | 9 | 9,00% | 6 | 6,00% | 5 | 5,00% | 1,058823529 |
| RF05  | Permitir agendamento e cancelamento de consultas e exames diretamente pelo aplicativo, com pagamento automático para prestadores da Rede de Atendimento. | 6 | 7 | 13 | 13,00% | 9 | 9,00% | 9 | 9,00% | 0,962962963 |
| RNF15 | O sistema deve exigir autenticação via GovBR para login. | 3 | 3 | 6 | 6,00% | 7 | 7,00% | 7 | 7,00% | 0,5714285714 |

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a>, <a href="https://github.com/redjsun">Yzabella Miranda</a> e <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a> </p>

## Gravação da Lista
A inspeção e o preenchimento da lista foram gravados e podem ser vistos na Gravação 1 e Gravação 2.

## Gravação da Lista

A inspeção e o preenchimento da lista foram gravados e podem ser vistos na Gravação 1 e Gravação 2.

<div align="center">
    <p><strong>Gravação 1</strong> (gravação First Thing First (1))</p>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/9B5d9yufqCE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

<div align="center">
    <p><strong>Gravação 2</strong> (gravação First Thing First (2))</p>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/F8ny5ZZLdxM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## Referências

VAZQUEZ, Bruno; SIMÕES, André; ALBERT, Endrew. *Engenharia de requisitos: software orientado ao negócio*. 1. ed. Rio de Janeiro: Elsevier, 2013. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096085/mod_resource/content/4/Elicitacao%20de%20Req%202.pdf>. Acesso em: 3 maio 2025.

## Histótico de versões

| Versão | Data       | Descrição                                            | Autor(es)                                                                                                  | Revisor(es)                                   |
|--------|------------|------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| 1.0    | 03/05/2025 | Criação do documento de priorização                  | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC), [Yzabella Miranda](https://github.com/redjsun) e [Matheus de Alcântara](https://github.com/matheusdealcantara)        | [Isaque Camargos](https://github.com/isaqzin) |
