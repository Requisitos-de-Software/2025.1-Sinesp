# Glossário

## Introdução

A elaboração de um glossário atua tanto como ferramenta de gestão quanto como documento orientador, consolidando a linguagem técnica essencial para a compreensão de processos e regras específicas de um domínio. No contexto do aplicativo escolhido, [GDF Saúde](https://requisitos-de-software.github.io/2025.1-GDF-Saude/planejamento/aplicativo/), plano de saúde suplementar para servidores públicos do Distrito Federal, essa sistematização é fundamental devido à complexidade de termos que exigem precisão para evitar falhas na comunicação entre beneficiários, gestores e prestadores.

<br>

## Metodologia

De acordo com Vazquez (2016), para identificar os termos candidatos ao glossário, deve-se prestar atenção a termos que apresentem uma ou mais das seguintes características:

* Únicos para o domínio;
* Com mais de uma definição;
* Com definição distinta do senso comum;
* Com definições não intuitivas;
* Técnicos do negócio;
* Abreviações e siglas;
* Sinônimos e antônimos.

A aplicação desses critérios permite selecionar termos relevantes e garantir que o glossário seja claro, útil e coerente com o contexto específico do sistema.


<br>

## Glossário

Para a realização desse glossário, foi utilizado as seguintes as fontes primárias:  

1. [Portaria nº 127/2024](https://inas.df.gov.br/wp-content/uploads/2024/12/Portaria-no127-de-13-de-dezembro-de-2024-Regulamento-GDF-Saude-baixa.pdf) que regulamenta os processos do GDF Saúde  
2. [Catálogo de Normas do INAS-DF](https://www.inas.df.gov.br/normas-e-regulamentacoes/)  
3. [Documentação Técnica de Requisitos](https://www.inas.df.gov.br/requisitos-e-documentos/) 


Na Tabela 1, os termos críticos do GDF Saúde foram organizados e detalhados, com ênfase em sua aplicação prática e impacto operacional. Essa abordagem visa assegurar alinhamento entre todas as partes envolvidas, desde a solicitação de autorizações prévias até a interpretação de portarias regulatórias, garantindo transparência e eficácia na gestão do plano.

<br>

### Termos do Glossário

<br>

<p align="center">Tabela 1 – Termos do Glossário</p>

| **Termo**               | **Definição**                                                                                                                                                     |  
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| **Beneficiário**         | Indivíduos cobertos pelo plano (titulares, dependentes ou optantes). Termo único do domínio, com regras específicas de elegibilidade e direitos.                |  
| **INAS**                 | Sigla para *Instituto de Assistência à Saúde dos Servidores do Distrito Federal*. Entidade gestora do plano. Termo técnico e único do domínio.                  |  
| **GDF SAÚDE**            | Nome do plano de saúde suplementar para servidores públicos do DF. Sigla com definição restrita ao contexto institucional.                                      |  
| **Cobertura**            | Conjunto de serviços e procedimentos incluídos no plano. Definição distinta do senso comum (ex.: não inclui cirurgias estéticas).                              |  
| **Carência**             | Período de espera para acesso a serviços após adesão. Termo técnico com prazos específicos (ex.: 300 dias para parto).                                          |  
| **TABGDFSAÚDE**          | Sigla para *Tabela de Procedimentos e Eventos em Saúde*. Lista técnica de serviços obrigatoriamente cobertos, com códigos e critérios.                         |  
| **DUT**                  | Sigla para *Diretrizes de Utilização*. Critérios clínicos pré-definidos para aprovação de procedimentos (ex.: necessidade comprovada de quimioterapia).         |  
| **Coparticipação**       | Pagamento parcial do beneficiário pelos serviços utilizados. Termo técnico com percentuais variáveis (ex.: 30% para consultas).                                |  
| **Servidor**             | Funcionário público do DF elegível como titular. Termo único do domínio, com subcategorias (ativo, inativo, comissionado).                                      |  
| **Dependente**           | Familiares vinculados ao titular (ex.: filhos até 24 anos). Regras específicas de inclusão e documentação. Termo com definição não intuitiva.                   |  
| **Autorização Prévia**   | Avaliação obrigatória para procedimentos não urgentes. Processo técnico para evitar custos não cobertos.                                                        |  
| **Rede de Atendimento**  | Prestadores de serviços credenciados pelo INAS. Termo técnico que restringe atendimentos a hospitais/clínicas contratadas.                                       |  
| **CID**               | Sigla para *Classificação Estatística Internacional de Doenças (10ª revisão)*. Base para diagnósticos cobertos, especialmente em saúde mental.                   |  
| **Exclusões**            | Serviços não cobertos pelo plano (ex.: terapias alternativas). Lista detalhada com definições não intuitivas (ex.: check-up sem sintomas).                      |  
| **Portaria**             | Ato administrativo que regulamenta o plano (ex.: Portaria nº 127/2024). Termo jurídico específico do contexto brasileiro.                                        |  
| **Processo Administrativo** | Tramitação formal de solicitações ou recursos no INAS. Termo técnico com etapas definidas (ex.: revisão de cobertura).                                          |  
| **Documentos para Admissão** | Exigências para cadastro no plano (ex.: CPF, comprovante de residência). Lista técnica com critérios específicos por categoria (titular/dependente).           |  

<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a> e <a href="https://github.com/redjsun">Yzabella Miranda</a></p>

<br>

### Requisitos elicitados
A partir da análise dos conceitos relacionados ao domínio do GDF Saúde, identificaram-se requisitos críticos para o funcionamento do sistema, descritos na Tabela 2. Cada requisito foi associado a um termo do glossário (indicado pela sigla GLO seguida de um número) e classificado como Requisito Funcional (RF) ou Requisito Não Funcional (RNF), conforme sua natureza operacional ou técnica.

<br>

<p align="center">Tabela 1 – Requisitos Elicitados</p> 

| **ID** | **Descrição**                                                                                                                 |**Tipo** | **Implementado** |
| ------ | ----------------------------------------------------------------------------------------------------------------------------- | -------- | ---------------- |
| <a id="GL01"></a>GL01  | Permitir cadastro de titulares, dependentes e optantes com validação de documentos (CPF, comprovante de residência).          | [RF05](../../elicitacao/elicitacao.md#RF05)       |       não           |
| <a id="GL02"></a>GL02  | Verificar se procedimentos estão na TABGDFSAÚDE e atendem às DUT antes da autorização.                                        | [RF08](../../elicitacao/elicitacao.md#RF08)       |          não        |
| <a id="GL03"></a>GL03  | Bloquear procedimentos sujeitos a carência (ex.: parto após 300 dias) até cumprimento do prazo.                               | [RF08](../../elicitacao/elicitacao.md#RF08)       |        não          |
| <a id="GL04"></a>GL04  | Aplicar percentuais de coparticipação conforme tipo de atendimento (ex.: 30% para consultas).                                 | [RF06](../../elicitacao/elicitacao.md#RF06)       |       sim           |
| <a id="GL05"></a>GL05  | Exigir solicitação médica e análise técnica do INAS para procedimentos eletivos por meio do aplicativo.                       | [RF08](../../elicitacao/elicitacao.md#RF08)       |        não          |
| <a id="GL06"></a>GL06  | Permitir agendamento e pagamento automático para prestadores da Rede de Atendimento.                                          | [RF05](../../elicitacao/elicitacao.md#RF05)       |        não          |
| <a id="GL07"></a>GL07  | Rejeitar automaticamente solicitações de procedimentos listados em Exclusões de acordo com o CID. (ex.: cirurgias estéticas). | [RF08](../../elicitacao/elicitacao.md#RF08)       |        sim          |
| <a id="GL08"></a>GL08  | Validar o vínculo ativo/inativo do servidor com o GDF para elegibilidade.                                                     | [RF07](../../elicitacao/elicitacao.md#RF07)       |         sim         |
| <a id="GL09"></a>GL09  | Validar a elegibilidade do dependente de acordo com as diretrizes do aplicativo.                                              | [RF07](../../elicitacao/elicitacao.md#RF07)       |       sim           |
| <a id="GL10"></a>GL10  | Garantir conformidade com a Portaria nº 127/2024 e legislações complementares (ex.: Lei nº 3.831/2006).                       | [RNF07](../../elicitacao/elicitacao.md#RNF07)      |    sim              |
| <a id="GL11"></a>GL11  | Manter sistema disponível 24/7 para autorizações de urgência/emergência.                                                      | [RNF04](../../elicitacao/elicitacao.md#RNF04)      |        sim          |
| <a id="GL12"></a>GL12  | Criptografar dados sensíveis (ex.: documentos) conforme LGPD.                                                                 | [RNF03](../../elicitacao/elicitacao.md#RNF03)      |        sim          |
| <a id="GL13"></a>GL13  | Processar autorizações prévias em até 10 dias úteis (conforme prazos do Capítulo VI).                                         | [RNF08](../../elicitacao/elicitacao.md#RNF08)      |         sim         |
| <a id="GL14"></a>GL14  | Comunicar-se com a folha de pagamento do GDF para descontos de mensalidades.                                                  | [RNF09](../../elicitacao/elicitacao.md#RNF09)      |        sim          |


<p align="center">Fonte: Autoria de <a href="https://github.com/Ana-Luiza-SC">Ana Luiza Soares</a> e <a href="https://github.com/redjsun">Yzabella Miranda</a></p>



## Referências

VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. *Engenharia de requisitos: software orientado ao negócio*. 1. ed. Rio de Janeiro: Brasport, 2016.​

INAS. *Portaria nº 127, de 13 de dezembro de 2024*. Regulamenta os processos operacionais do GDF Saúde. Brasília: Secretaria de Estado de Saúde, 2024. Disponível em: <https://inas.df.gov.br/wp-content/uploads/2024/12/Portaria-no127-de-13-de-dezembro-de-2024-Regulamento-GDF-Saude-baixa.pdf>. Acesso em: 15 jul. 2024.

INAS-DF. *Normas e Regulamentações*. Brasília: Instituto de Atenção à Saúde do Distrito Federal, 2024. Disponível em: <https://www.inas.df.gov.br/normas-e-regulamentacoes/>. Acesso em: 15 jul. 2024.

INAS-DF. *Requisitos e Documentos Técnicos*. Brasília: Instituto de Atenção à Saúde do Distrito Federal, 2024. Disponível em: <https://www.inas.df.gov.br/requisitos-e-documentos/>. Acesso em: 15 jul. 2024.


## Histórico de Versões

| Versão | Data       | Descrição                                        | Autor(es)           | Revisor(es)         |
|--------|------------|--------------------------------------------------|---------------------|---------------------|
| 1.0    | 01/05/2025 | Criação do documento da elicitação com a técnica glossário                | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) e [Yzabella Miranda](https://github.com/redjsun) | [Isaque Camargos](https://github.com/isaqzin)   |
| 1.1    | 02/05/2025 | Atualização da tabela e adição da metodologia               | [Ana Luiza Soares](https://github.com/Ana-Luiza-SC) e [Yzabella Miranda](https://github.com/redjsun) | [Isaque Camargos](https://github.com/isaqzin)   |
