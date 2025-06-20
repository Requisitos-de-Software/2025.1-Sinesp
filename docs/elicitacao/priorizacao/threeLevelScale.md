# Three Level Scale

## Introdução

Este documento descreve o objetivo da verificação, a metodologia aplicada e os dados coletados durante a análise do artefato Three Level Scale.



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
Os resultados da verificação do artefato foram obtidos após um processo iterativo de priorização. Inicialmente, foram testadas duas abordagens:

1. **Priorização com Personas:** Método descartado por não atender aos requisitos de validação com usuários reais.

2. **Priorização Online:** Realizada remotamente, mas invalidada devido à exigência de interação presencial para maior confiabilidade dos resultados.

A **versão final** adotada foi a **priorização presencial**, conduzida pelos integrantes [Ana Luiza Soares](https://github.com/Ana-Luiza-SC), [Matheus de Alcântara](https://github.com/matheusdealcantara), [Othavio Bolzan](https://github.com/bolzanMGB), [Yzabella Miranda](https://github.com/redjsun) e **Gustavo Freitas** (usuário real que validou as pontuações) utilizando a escala Three Level Scale (Baixa, Média, Alta).

Os critérios foram definidos em consenso durante a atividade presencial, e os resultados foram organizados por identificadores de funcionalidades, conforme apresentado na Tabela 2: Resultados Three Level Scale.

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
                <td>13:00</td>
                <td>6m 37s</td>
            </tr>
        </tbody>
    </table>
</div>

<p align="center">Fonte: Autoria de <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> </p>

--- 

## Tabela de priorização

<p align="center">Tabela 2: Three Level  Scale</p>


  
  | id    | funcionalidades                                                                                                       | prioridade |
|-------|-----------------------------------------------------------------------------------------------------------------------|------------|
| RF01  | Permitir ao usuário pesquisar e filtrar clínicas e profissionais credenciados por especialidade, região administrativa, tipo de atendimento e proximidade. | ALTA       |
| RF02  | Disponibilizar sistema de avaliação de clínicas com notas e comentários.                                              | MÉDIA      |
| RF03  | Exibir carteirinha digital mesmo sem conexão (modo offline) e permitir acesso rápido e estável.                       | ALTA       |
| RF04  | Enviar notificações configuráveis via app, SMS ou e-mail sobre vencimento de fatura, retornos médicos pendentes, abertura de agenda, cancelamentos de horários, horários favoritos disponíveis, prazos importantes, confirmações ou alterações de agendamento e disponibilidade de demonstrativos de IR. | ALTA       |
| RF05  | Permitir agendamento e cancelamento de consultas e exames diretamente pelo aplicativo, com pagamento automático para prestadores da Rede de Atendimento. | ALTA       |
| RF06  | Exibir valor específico de consulta em cada clínica, aplicar percentuais de coparticipação, gerar e baixar demonstrativos de despesas médicas para imposto de renda, consultar histórico de demonstrativos de IR e mostrar extrato financeiro atualizado diariamente. | MÉDIA      |
| RF07  | Permitir cadastro de titulares, dependentes e optantes com validação de documentos e elegibilidade.                    | MÉDIA      |
| RF08  | Verificar se procedimentos estão na TABGDFSAÚDE, atendem às DUT, estão sujeitos a carência ou são excluídos, exigindo solicitação médica e análise técnica para autorizações prévias. | ALTA       |
| RF09  | Permitir ao usuário visualizar histórico de consultas, exames realizados, resultados de exames laboratoriais e coparticipações. | ALTA       |
| RF10  | Permitir que o usuário favorite horários de consulta desejados.                                                       | BAIXA      |
| RF11  | Oferecer um canal para o usuário enviar feedback sobre atendimentos.                                                  | MÉDIA      |
| RF12  | Divulgar informações sobre novas funcionalidades no aplicativo.                                                       | BAIXA      |
| RF13  | Adicionar consulta à rede odontológica.                                                                               | MÉDIA      |
| RF14  | Apresentar novas clínicas e clínicas próximas de acordo com a localização do usuário.                                 | ALTA       |
| RF15  | Permitir baixar comprovantes de agendamento.                                                                          | MÉDIA      |
| RNF01 | A interface deve ser intuitiva, clara, adaptada para idosos e pessoas com baixa familiaridade tecnológica, organizada em categorias e responsiva em smartphones Android e iOS. | ALTA       |
| RNF02 | Garantir carregamento rápido e fluído de todas as telas, com tempo de resposta das ações não ultrapassando 2 segundos. | MÉDIA      |
| RNF03 | Assegurar segurança no acesso e armazenamento de dados pessoais, criptografar dados sensíveis conforme LGPD, incluir autenticação em dois fatores e ser transparente quanto ao uso e segurança dos dados. | ALTA       |
| RNF04 | Manter o sistema disponível 24/7 para autorizações de urgência/emergência e apresentar alta disponibilidade (mínimo de 99% uptime). | ALTA       |
| RNF05 | O sistema deve ser compatível com diferentes versões do Android e iOS, a partir das versões mais utilizadas no mercado. | MÉDIA      |
| RNF06 | O aplicativo deve ser compatível com leitores de tela para garantir acessibilidade a pessoas com deficiência visual.  | MÉDIA      |
| RNF07 | Garantir conformidade com a Portaria nº 127/2024, legislações complementares e padrões da LGPD.                       | ALTA       |
| RNF08 | Processar autorizações prévias em até 10 dias úteis.                                                                  | MÉDIA      |
| RNF09 | Comunicar-se com a folha de pagamento do GDF para descontos de mensalidades.                                          | BAIXA      |
| RNF10 | Garantir que informações críticas, como a carteirinha digital, estejam acessíveis em até três cliques ou com no máximo 2 cliques a partir da tela inicial. | MÉDIA      |
| RNF11 | Manter histórico de notificações acessível ao usuário por no mínimo 6 meses.                                          | MÉDIA      |
| RNF12 | O aplicativo deve oferecer suporte por chat ou telefone.                                                              | ALTA       |
| RNF13 | Deve funcionar de forma offline para acesso à carteirinha e histórico de consultas.                                    | ALTA       |
| RNF14 | O layout deve ser consistente com o portal oficial do plano.                                                           | BAIXA      |
| RNF15 | O sistema deve exigir autenticação via GovBR para login.                                                              | BAIXA      |
| RNF16 | As informações exibidas devem ser claras, completas e atualizadas em tempo real.                                       | ALTA       |


<font size="3"><p style="text-align: center">Fonte: [Othavio Bolzan](https://github.com/bolzanMGB) e [Yzabella Pimenta](https://github.com/redjsun) .</p></font>

---

## Gravação da Priorização
A priorização e o preenchimento da lista foram gravados e podem ser vistos no Vídeo 1.

<font size="3"><p style="text-align: center">Vídeo 1: Gravação da inspeção do artefato Three Level Scale.</p></font>


<div style="display: flex; justify-content: center;">
  <iframe width="560" height="315" src="https://www.youtube.com/watch?v=AmDLnh4qbeo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>


---

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|-----------|-----------|-------------|
| 1.0 | 04/05/2025 | Criação do documento e adição dos resultados | [Yzabella Miranda Pimenta](https://github.com/redjsun) e [Othavio Bolzan](https://github.com/bolzanMGB) | [Kaleb Macedo](https://github.com/kalebmacedo) |
| 2.0 | 20/06/2025 | Alteração com a priorização com os usuários reais| <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a>, <a href="https://github.com/redjsun">Yzabella Miranda</a>, <a href="https://github.com/matheusdealcantara">Matheus de Alcântara</a>  e <a href="https://github.com/bolzanMGB">Othavio Bolzan</a> </p>| [Kaleb Macedo](https://github.com/kalebmacedo) |