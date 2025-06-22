## Introdução 

As histórias de usuário são uma técnica usada em engenharia de requisitos para capturar funcionalidades do sistema sob a perspectiva do usuário final. Elas descrevem, de forma simples e objetiva, quem precisa de algo, o que precisa ser feito e por que aquilo é importante.

As histórias de usuário focam em comunicar o valor de cada funcionalidade de maneira clara para todos os envolvidos no projeto — desenvolvedores, testadores, analistas e stakeholders.


A estrutura mais comum para um história de usuário é: 

    - Como [tipo de usuário];
    - Quero [objetivo a ser alcançado ou ação];
    - Para [benefício ou motivo].


## Metodologia 

Para conduzir a definição e o gerenciamento dos requisitos dessa etapa, seguimos uma abordagem centrada no usuário e iterativa, com foco na clareza, rastreabilidade e priorização colaborativa. 

Inicialmente, os requisitos funcionais foram elicitados por meio de entrevistas, análise documental e observação de processos. A partir desses requisitos, foram elaboradas as histórias de usuário, organizadas em um formato simples e compreensível, com critérios de aceitação objetivos e rastreabilidade direta com os requisitos formais (RFX).


### Técnica utilizada 

Para priorizar as funcionalidades junto ao cliente, adotamos a técnica de priorização **MoSCoW**, amplamente utilizada em metodologias ágeis. Essa técnica classifica os requisitos em quatro categorias:

- Must have (M) – Itens essenciais. Devem ser implementados obrigatoriamente para que o sistema atenda seus objetivos mínimos.

- Should have (S) – Importantes, mas não críticos. Devem ser incluídos se possível dentro do cronograma.

- Could have (C) – Desejáveis. São funcionalidades complementares que agregam valor, mas não são prioritárias.

- Won't have for now (W) – Não serão implementadas neste ciclo. Podem ser reavaliadas em futuras versões.

Essa priorização será feita em conjunto com o cliente, garantindo que os recursos mais importantes sejam desenvolvidos primeiro e que o escopo esteja sempre alinhado com os objetivos do negócio.



## Atividadades por membro 

<p style="text-align: center"><b>Tabela 1</b> - Tabela de atividade dos membros da equipe </p>

| Membro                                             | Código das US                      | Feito | Status da validação |
|----------------------------------------------------|------------------------------------|-------|---------------------|
| [José Eduardo](https://github.com/jevprado)        | US01, US02, US03, US04, US05, US06 | SIM      |                     |
| [Thales Germano](https://github.com/thalesgvl)     | US07, US08, US09, US10, US11, US12 |  SIM      |                     |
| [Julia Massuda](https://github.com/JuliaReis18)    | US13, US14, US15, US16, US17, US18 | SIM       |                     |
| [Andre Lopes](https://github.com/andrewslopes)     | US19, US20, US21, US22, US23, US24 |       |                     |
| [Diassis](https://github.com/Diaxiz)               | US25, US26, US27, US28, US29, US30 | SIM       |                     |
| [João Pedro](https://github.com/JpRodrigues2)      | US31, US32, US33, US34, US35, US36 | SIM       |                     |
| [Marco Marques](https://github.com/marcomarquesdc) | US37, US38, US39, US40, US41, US42 |       |                     |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado), 2025.</p></font>

## Histórias de usuários 

Padrão de tabelas para as histórias de usuário
<p style="text-align: center"><b>Tabela 2</b> - Tabela padrão para as histórias de usuário </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | USxx                                                                      |
| **TÍTULO**                 | Nome do requisito                                                         |
| **HISTÓRIA DE USUÁRIO**    | Eu, como contribuinte/profissional contábil, quero [...] para [...]       |
| **CRITÉRIOS DE ACEITAÇÃO** | - crit1;<br>- crit2;<br>- critX;                                          |
| **RASTREABILIDADE**        | RFX                                                                       | 
| **STATUS**                 | Implementada / Não implementada                                           |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado), 2025.</p></font>

### US-01 - Acompanhamento de status da restituição (precisão quanto aos lotes)

<p style="text-align: center"><b>Tabela 3</b> - Tabela da história de usuario 01 (US-01) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-01                                                                      |
| **TÍTULO**                 | Acompanhamento de status da restituição (precisão quanto aos lotes)       |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte,quero visualizar o status detalhado da minha restituição, para saber exatamente em qual lote ela será paga e qual o andamento detalhado do processo.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O  sistema deve exibir o número do lote da restituição ao qual o contribuinte está vinculado. <br> - Deve ser possível visualizar o status atual (ex: "em processamento", "em fila de pagamento", "pago"). <br>- A informação do lote deve ser atualizada automaticamente conforme o status evoluir.<br>- A data prevista de pagamento deve ser exibida, se disponível.<br>- Se o contribuinte não for elegível à restituição, deve ser exibida a mensagem: "Você não possui valores a restituir nesta declaração."                                          |
| **RASTREABILIDADE**        | [RF3](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Não implementada                                                          |
| **PRIORIDADE**             |  MOSCOW -  SHOULD                                                 |
| **VALIDAÇÃO**              | Validada                                 |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado), 2025.</p></font>

### US-02 - Agendar no proprio app da receita atendimentos presenciais

<p style="text-align: center"><b>Tabela 3</b> - Tabela da história de usuario 02 (US-02) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-02                                                                      |
| **TÍTULO**                 | Agendar no proprio app da receita atendimentos presenciais        |
| **HISTÓRIA DE USUÁRIO**    | Como um cidadão, quero agendar atendimentos presenciais diretamente pelo aplicativo da Receita Federal, para que eu possa marcar compromissos de forma rápida, sem a necessidade de acessar o site/aplicativos externos, ou comparecer fisicamente para isso.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O usuário deve conseguir visualizar os postos de atendimento disponíveis com base na sua localização ou por estado/cidade. <br>- O sistema deve exibir os serviços disponíveis para agendamento presencial. <br>- O usuário deve poder selecionar a data e o horário entre os disponíveis para o posto escolhido. <br> - O aplicativo deve confirmar o agendamento e gerar um comprovante com número de protocolo. <br> - O usuário deve ter acesso a uma área no app para visualizar, reagendar ou cancelar seus agendamentos.                                         |
| **RASTREABILIDADE**        | [RF5](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Não implementada                                                          |
| **PRIORIDADE**             | MOSCOW -  MUST                                               |
| **VALIDAÇÃO**              | Validada                                |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado), 2025.</p></font>

### US-03 - Geração de guias de pagamento

<p style="text-align: center"><b>Tabela 4</b> - Tabela da história de usuario 03 (US-03) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-03                                                                      |
| **TÍTULO**                 | Geração de guias de pagamento        |
| **HISTÓRIA DE USUÁRIO**    | Como cidadão, quero gerar guias de pagamento diretamente pelo aplicativo da Receita Federal, para que eu possa quitar meus débitos de forma prática, sem depender de outras plataformas ou atendimento presencial.     |
| **CRITÉRIOS DE ACEITAÇÃO** | - O usuário deve conseguir selecionar o tipo de tributo ou débito para o qual deseja gerar a guia (ex.: DARF, GPS, DAS). <br> - O sistema deve permitir a inserção manual ou seleção de débitos em aberto. <br> - O aplicativo deve oferecer opção para salvar ou compartilhar a guia em formato PDF. <br> - A guia gerada deve conter código de barras e/ou QR Code para pagamento via internet banking ou PIX. <br> - O usuário deve ter acesso ao histórico de guias geradas, com status de pagamento (paga/não paga).                                          |
| **RASTREABILIDADE**        | [RF10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Implementada                                                          |
| **PRIORIDADE**             | MOSCOW -   MUST                                                  |
| **VALIDAÇÃO**              | Validada                                |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado), 2025.</p></font>

### US-04 - Consulta de status do CPF pelo aplicativo da Receita Federal 

<p style="text-align: center"><b>Tabela 5</b> - Tabela da história de usuario 04 (US-04) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-04                                                                      |
| **TÍTULO**                 | Consulta de status do CPF pelo aplicativo da Receita Federal        |
| **HISTÓRIA DE USUÁRIO**    | Como um cidadão, quero consultar o status do meu CPF diretamente pelo aplicativo da Receita Federal, para que eu possa verificar se está ativo, suspenso ou irregular, e tomar providências caso necessário.  |
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve exibir claramente o status atual do CPF (ex.: Ativo, Suspenso, Cancelado, Nulo ou Pendente de Regularização). <br> - A consulta deve apresentar também os dados básicos do CPF, como nome completo, data de nascimento e situação cadastral. <br> - Caso o CPF esteja com pendências, o aplicativo deve orientar o usuário com os próximos passos para regularização.|
| **RASTREABILIDADE**        | [RF11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Implementada                                                          |
| **PRIORIDADE**             | MOSCOW -   MUST                                              |
| **VALIDAÇÃO**              | Validada                                 |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado), 2025.</p></font>


### US-05 - Acesso a informações detalhadas da declaração de imposto de renda por ano

<p style="text-align: center"><b>Tabela 6</b> - Tabela da história de usuario 05 (US-05) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-05                                                                      |
| **TÍTULO**                 | Acesso a informações detalhadas da declaração de imposto de renda por ano        |
| **HISTÓRIA DE USUÁRIO**    | Como um contribuinte, quero acessar as informações detalhadas da minha declaração de imposto de renda de um ano específico pelo aplicativo da Receita Federal, para que eu possa consultar detalhes (dados) de envios, dentro do próprio aplicativo.  |
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve permitir a seleção do ano-base da declaração (ex.: 2022, 2023...). <br>  - O sistema deve permitir o download da declaração em PDF. <br> - O acesso deve ser protegido por autenticação de dois fatores ou biometria, garantindo a confidencialidade das informações. |
| **RASTREABILIDADE**        | [RF14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Implementada                                                          |
| **PRIORIDADE**             | MOSCOW - MUST                                             |
| **VALIDAÇÃO**              | Validada                             |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado), 2025.</p></font>


### US-06 - Emissão de certidão negativa via aplicativo 

<p style="text-align: center"><b>Tabela 7</b> - Tabela da história de usuario 06 (US-06) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-06                                                                      |
| **TÍTULO**                 | Emissão de certidão negativa via aplicativo        |
| **HISTÓRIA DE USUÁRIO**    | Como um contribuinte, quero emitir (via PDF) a certidão negativa de débitos diretamente pelo aplicativo da Receita Federal, para que eu possa comprovar minha regularidade fiscal de forma rápida e sem precisar acessar o site ou comparecer a uma unidade presencial. |
| **CRITÉRIOS DE ACEITAÇÃO** | - O usuário deve estar autenticado para solicitar a certidão negativa. <br> - O sistema deve verificar automaticamente se o contribuinte possui pendências fiscais ou débitos. <br> - Caso não existam pendências, o sistema deve gerar a Certidão Negativa de Débitos (CND) em formato PDF. <br> - Se houver pendências, o sistema deve exibir mensagem informando que a certidão não pode ser emitida, acompanhada das instruções para regularização.|
| **RASTREABILIDADE**        | [RF17](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Implementada                                                          |
| **PRIORIDADE**             | MOSCOW  -     MUST                                     |
| **VALIDAÇÃO**              | Validada                                |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado), 2025.</p></font>


### US-07 - Acesso offline a serviços essenciais do app

<p style="text-align: center"><b>Tabela 7</b> - Tabela da história de usuário 07 (US-07) </p>

| Campo                      | Descrição                                                                                                                                                                                        |
|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **CÓDIGO**                 | US-07                                                                                                                                                                                             |
| **TÍTULO**                 | Acesso offline a serviços essenciais do app                                                                                                                                                       |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero acessar alguns serviços essenciais do aplicativo mesmo sem conexão com a internet, para consultar rapidamente dados como históricos de contribuição e DARFs emitidos.  |
| **CRITÉRIOS DE ACEITAÇÃO** | - O aplicativo deve permitir acesso offline ao histórico de contribuições e DARFs previamente baixados. <br> - O sistema deve alertar que os dados estão desatualizados sem conexão.            |
| **RASTREABILIDADE**        | [RF05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                        | 
| **STATUS**                 | Não implementada                                                                                                                                                                                  |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                                                                                                                                         |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                                                                                                                                         |

<font size="3"><p style="text-align: center">Fonte: [Thales Germano](https://github.com/thalesgvl), 2025.</p></font>

---

### US-08 - Comparativo automático entre declarações de anos anteriores

<p style="text-align: center"><b>Tabela 8</b> - Tabela da história de usuário 08 (US-08) </p>

| Campo                      | Descrição                                                                                                                                                                                             |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **CÓDIGO**                 | US-08                                                                                                                                                                                                  |
| **TÍTULO**                 | Comparativo automático entre declarações de anos anteriores                                                                                                                                           |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero visualizar um comparativo entre minhas declarações de imposto de renda de anos anteriores, para identificar alterações e inconsistências de forma automática.                 |
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve listar informações relevantes lado a lado (ex: rendimentos, deduções, restituições). <br> - O app deve destacar alterações ou divergências de forma visual.                          |
| **RASTREABILIDADE**        | [RF25](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                              | 
| **STATUS**                 | Não implementada                                                                                                                                                                                       |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                                                                                                                                              |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                                                                                                                                             |

<font size="3"><p style="text-align: center">Fonte: [Thales Germano](https://github.com/thalesgvl), 2025.</p></font>

---

### US-09 - Alteração de dados via app

<p style="text-align: center"><b>Tabela 9</b> - Tabela da história de usuário 09 (US-09) </p>

| Campo                      | Descrição                                                                                                                                                         |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **CÓDIGO**                 | US-09                                                                                                                                                              |
| **TÍTULO**                 | Alteração de dados via app                                                                                                                                         |
| **HISTÓRIA DE USUÁRIO**    | Como cidadão, quero poder alterar meus dados cadastrais diretamente no aplicativo da Receita Federal, para manter minhas informações atualizadas de forma prática. |
| **CRITÉRIOS DE ACEITAÇÃO** | - O usuário deve poder alterar endereço, telefone e e-mail. <br> - Alterações devem ser confirmadas com autenticação segura.                                       |
| **RASTREABILIDADE**        | [RF07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                          | 
| **STATUS**                 | Implementada                                                                                                                                                       |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                                                                                                          |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                                                                                                         |

<font size="3"><p style="text-align: center">Fonte: [Thales Germano](https://github.com/thalesgvl), 2025.</p></font>

---

### US-10 - Notificação de vencimento próximo

<p style="text-align: center"><b>Tabela 10</b> - Tabela da história de usuário 10 (US-10) </p>

| Campo                      | Descrição                                                                                                                                                            |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **CÓDIGO**                 | US-10                                                                                                                                                                 |
| **TÍTULO**                 | Notificação de vencimento próximo                                                                                                                                     |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero ser notificado pelo aplicativo quando uma obrigação fiscal estiver próxima do vencimento, para evitar atrasos no pagamento ou envio.        |
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve exibir alertas com antecedência de X dias. <br> - As notificações devem permitir acesso direto à ação correspondente (pagamento/envio).             |
| **RASTREABILIDADE**        | [RF04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                             | 
| **STATUS**                 | Implementada                                                                                                                                                          |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                                                                                                             |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                                                                                                            |

<font size="3"><p style="text-align: center">Fonte: [Thales Germano](https://github.com/thalesgvl), 2025.</p></font>

---

### US-11 - Declaração simplificada do IR

<p style="text-align: center"><b>Tabela 11</b> - Tabela da história de usuário 11 (US-11) </p>

| Campo                      | Descrição                                                                                                                                                          |
|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **CÓDIGO**                 | US-11                                                                                                                                                               |
| **TÍTULO**                 | Declaração simplificada do IR                                                                                                                                       |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero realizar uma declaração de imposto de renda simplificada no app, para agilidade no envio de informações quando não tenho deduções complexas. |
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve oferecer opção de declaração simplificada com cálculo automático. <br> - Deve apresentar simulação de restituição ou valor a pagar.               |
| **RASTREABILIDADE**        | [RF09](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                            | 
| **STATUS**                 | Implementada                                                                                                                                                        |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                                                                                                           |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                                                                                                          |

<font size="3"><p style="text-align: center">Fonte: [Thales Germano](https://github.com/thalesgvl), 2025.</p></font>

---

### US-12 - Consulta de inscrição no CNPJ

<p style="text-align: center"><b>Tabela 12</b> - Tabela da história de usuário 12 (US-12) </p>

| Campo                      | Descrição                                                                                                                                                        |
|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **CÓDIGO**                 | US-12                                                                                                                                                             |
| **TÍTULO**                 | Consulta de inscrição no CNPJ                                                                                                                                    |
| **HISTÓRIA DE USUÁRIO**    | Como cidadão ou empresário, quero consultar a inscrição de um CNPJ diretamente pelo app, para verificar a situação cadastral de empresas de forma rápida.        |
| **CRITÉRIOS DE ACEITAÇÃO** | - Deve ser possível pesquisar pelo número do CNPJ. <br> - O sistema deve exibir dados como razão social, endereço e situação cadastral.                           |
| **RASTREABILIDADE**        | [RF28](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                          | 
| **STATUS**                 | Implementada                                                                                                                                                      |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                                                                                                         |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                                                                                                        |

<font size="3"><p style="text-align: center">Fonte: [Thales Germano](https://github.com/thalesgvl), 2025.</p></font>

### US-13 - Compartilhamento de comprovantes e certidões

<p style="text-align: center"><b>Tabela 13</b> - Tabela da história de usuário 13 (US-13) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-13                                                                     |
| **TÍTULO**                 | Compartilhamento de comprovantes e certidões                             |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero compartilhar meus comprovantes e certidões diretamente pelo aplicativo através de WhatsApp, e-mail ou salvamento em nuvem, para que eu possa enviar documentos oficiais de forma prática e segura quando solicitado.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O aplicativo deve permitir compartilhamento via WhatsApp, e-mail e Google Drive/iCloud. <br> - Documentos devem manter formato oficial e assinatura digital. <br> - Deve ser possível compartilhar múltiplos documentos simultaneamente. <br> - O sistema deve registrar o histórico de compartilhamentos para auditoria. <br> - Deve incluir opções de proteção por senha nos documentos compartilhados.                    |
| **RASTREABILIDADE**        | [RF23](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Não implementada                                                          |
| **PRIORIDADE**             | MOSCOW - Must Have                                                  |
| **VALIDAÇÃO**              | Validada com o usuário                          |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>

### US-14 - Reenvio de notificações perdidas

<p style="text-align: center"><b>Tabela 14</b> - Tabela da história de usuário 14 (US-14) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-14                                                                     |
| **TÍTULO**                 | Reenvio de notificações perdidas                                         |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero poder solicitar o reenvio de notificações importantes que perdi ou não recebi, através de e-mail ou mensagem no aplicativo, para que eu não perca prazos importantes por falha na comunicação.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O usuário deve conseguir visualizar histórico de notificações enviadas. <br> - Deve ser possível reenviar notificações via e-mail ou push no app. <br> - O sistema deve permitir configurar canais preferenciais de comunicação. <br> - Deve incluir filtros por tipo de notificação e período. <br> - Notificações críticas devem ter opção de reenvio automático.                    |
| **RASTREABILIDADE**        | [RF24](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Não implementada                                                          |
| **PRIORIDADE**             | MOSCOW - Should Have                                                 |
| **VALIDAÇÃO**              | Validada pelo usuário

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>


### US-16 - FAQ interativo com busca inteligente

<p style="text-align: center"><b>Tabela 16</b> - Tabela da história de usuário 16 (US-16) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-16                                                                     |
| **TÍTULO**                 | FAQ interativo com busca inteligente                                     |
| **HISTÓRIA DE USUÁRIO**    | Como usuário do aplicativo, quero acessar um FAQ interativo com busca inteligente filtrada por temas como CPF, IRPF e Certidões, para que eu possa encontrar respostas rápidas e precisas para minhas dúvidas sem precisar entrar em contato com atendimento.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve permitir busca por palavras-chave com sugestões automáticas. <br> - Deve incluir filtros por categoria (CPF, IRPF, Certidões, etc.). <br> - As respostas devem ser organizadas por relevância e popularidade. <br> - Deve incluir recursos visuais como imagens e vídeos explicativos. <br> - O usuário deve poder avaliar a utilidade das respostas encontradas.                    |
| **RASTREABILIDADE**        | [RF26](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Não implementada                                                          |
| **PRIORIDADE**             | MOSCOW - Should Have                                                |
| **VALIDAÇÃO**              | Validada pelo usuário                                |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>

### US-17 - Integração com calendário do dispositivo

<p style="text-align: center"><b>Tabela 17</b> - Tabela da história de usuário 17 (US-17) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-17                                                                     |
| **TÍTULO**                 | Integração com calendário do dispositivo                                 |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero que o aplicativo se integre automaticamente com o calendário do meu dispositivo para criar lembretes de obrigações fiscais, para que eu possa visualizar todos os meus compromissos tributários junto com minha agenda pessoal.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O aplicativo deve solicitar permissão para acessar o calendário do usuário. <br> - Deve criar eventos automaticamente para vencimentos de obrigações fiscais. <br> - Os eventos devem incluir informações detalhadas sobre a obrigação. <br> - O usuário deve poder personalizar antecedência dos lembretes. <br> - Deve sincronizar automaticamente mudanças de datas e novos prazos.                    |
| **RASTREABILIDADE**        | [RF27](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Não implementada                                                          |
| **PRIORIDADE**             | MOSCOW - Must Have                                             |
| **VALIDAÇÃO**              | Validada pelo Usuário                               |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>

### US-18 - Dashboard para profissionais contábeis

<p style="text-align: center"><b>Tabela 18</b> - Tabela da história de usuário 18 (US-18) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-18                                                                     |
| **TÍTULO**                 | Dashboard para profissionais contábeis                                   |
| **HISTÓRIA DE USUÁRIO**    | Como profissional contábil, quero ter acesso a um dashboard especializado que me permita gerenciar múltiplos CPFs/CNPJs dos meus clientes, para que eu possa ter uma visão consolidada e eficiente de todas as obrigações fiscais sob minha responsabilidade.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O dashboard deve exibir resumo de todos os clientes vinculados. <br> - Deve mostrar alertas de vencimentos e pendências por cliente. <br> - Deve permitir filtros por tipo de obrigação, status e prazo. <br> - O sistema deve gerar relatórios consolidados. <br> - Deve incluir ferramentas de busca rápida por CPF/CNPJ ou nome do cliente.                    |
| **RASTREABILIDADE**        | [RF19](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Não implementada                                                          |
| **PRIORIDADE**             | MOSCOW - Should Have                                                |
| **VALIDAÇÃO**              | Validada pelo Usuário                              |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>


### US-25 - Acesso simultâneo a múltiplos CPFs/CNPJs

<p style="text-align: center"><b>Tabela 25</b> - Tabela da história de usuário 25 (US-25) </p>

| Campo                      | Descrição                                                                                                                                                                                                                                                               |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **CÓDIGO**                 | US-25                                                                                                                                                                                                                                                                   |
| **TÍTULO**                 | Acompanhamento de processos administrativos |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero acompanhar o andamento dos meus processos administrativos junto à Receita Federal diretamente pelo aplicativo, para que eu possa ter transparência sobre o status e próximos passos sem precisar comparecer presencialmente.|
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve listar todos os processos administrativos do contribuinte.<br>- Deve exibir o status atual (em análise, deferido, aguardando documentos etc.).<br>- Deve mostrar histórico de movimentações e prazos estimados. |
| **RASTREABILIDADE**        | [RF01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                                                                                 |
| **STATUS**                 | Não implementada                                                                                                                                                                                                                                                        |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                                                                                                                                                                                                               |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                                                                                                                                                                                                              |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>

### US-26 - Cadastro de CPF via aplicativo

<p style="text-align: center"><b>Tabela 26</b> - Tabela da história de usuário 26 (US-26) </p>

| Campo                      | Descrição                                                                                                                                                                                                                                                                                                                              |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **CÓDIGO**                 | US-26                                                                                                                                                                                                                                                                                                                                  |
| **TÍTULO**                 | Cadastro de CPF remotamente pelo app                                                                                                                                                                                                                                                                                                   |
| **HISTÓRIA DE USUÁRIO**    | Como cidadão, quero poder cadastrar meu CPF de forma totalmente remota pelo app, para que eu não precise comparecer fisicamente a uma unidade da Receita Federal.                                                                                                                                                                      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O aplicativo deve oferecer um formulário com os dados necessários para emissão de CPF.<br>- O sistema deve validar os dados em tempo real e solicitar documentos via upload.<br>- O status do pedido deve ser atualizado no próprio app.<br>- Ao final, deve permitir o download ou visualização do comprovante de inscrição no CPF. |
| **RASTREABILIDADE**        | [RF02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                                                                                                                                                |
| **STATUS**                 | Não implementada                                                                                                                                                                                                                                                                                                                       |
| **PRIORIDADE**             | MOSCOW - Must Have|
| **VALIDAÇÃO**              | Validada pelo usuário |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>


### US-27 - Integração com conta Gov.br

<p style="text-align: center"><b>Tabela 27</b> - Tabela da história de usuário 27 (US-27) </p>

| Campo                      | Descrição                                                                                                                                                                                                                                     |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **CÓDIGO**                 | US-27                                                                                                                                                                                                                                         |
| **TÍTULO**                 | Login com conta Gov.br                                                                                                                                                                                                                        |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero acessar o app utilizando minha conta Gov.br, para facilitar o login e garantir a segurança dos meus dados.                                                                                                           |
| **CRITÉRIOS DE ACEITAÇÃO** | - O app deve oferecer botão de login com Gov.br já na tela inicial.<br>- A autenticação deve ser redirecionada para o ambiente oficial do Gov.br.<br>- Após autenticar, o usuário deve retornar automaticamente ao app com a sessão iniciada. |
| **RASTREABILIDADE**        | [RF12](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                                                      |
| **STATUS**                 | Implementada                                                                                                                                                                                                                                  |
| **PRIORIDADE**             | MOSCOW - Must Have|
| **VALIDAÇÃO**              | Validada pelo usuário |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>


### US-28 - Envio de documentos para instrução de processos

<p style="text-align: center"><b>Tabela 28</b> - Tabela da história de usuário 28 (US-28) </p>

| Campo                      | Descrição                                                                                                                                                                                                                                             |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **CÓDIGO**                 | US-28                                                                                                                                                                                                                                                 |
| **TÍTULO**                 | Enviar documentos para processos pelo app                                                                                                                                                                                                             |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero enviar documentos diretamente pelo aplicativo, para instruir ou complementar processos junto à Receita Federal sem precisar ir a uma unidade presencial.                                                                     |
| **CRITÉRIOS DE ACEITAÇÃO** | - O usuário deve poder selecionar o tipo de processo que deseja instruir.<br>- O sistema deve aceitar arquivos PDF, JPG e PNG.<br>- O usuário deve receber uma confirmação do envio e protocolo.<br>- O status do processo deve ser visível pelo app. |
| **RASTREABILIDADE**        | [RF13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                                                              |
| **STATUS**                 | Implementada                                                                                                                                                                                                                                          |
| **PRIORIDADE**             | MOSCOW - Must Have |
| **VALIDAÇÃO**              | Validada pelo usuário |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>


### US-29 - Envio da declaração do IR diretamente pelo app

<p style="text-align: center"><b>Tabela 29</b> - Tabela da história de usuário 29 (US-29) </p>

| Campo                      | Descrição                                                                                                                                                                                                                                              |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **CÓDIGO**                 | US-29                                                                                                                                                                                                                                                  |
| **TÍTULO**                 | Envio da declaração do IR pelo app                                                                                                                                                                                                                     |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero enviar minha declaração do Imposto de Renda diretamente pelo aplicativo, para cumprir minha obrigação fiscal de maneira mais rápida e prática.                                                                                |
| **CRITÉRIOS DE ACEITAÇÃO** | - O app deve permitir o preenchimento completo ou importação da declaração.<br>- Deve haver botão de envio oficial da declaração.<br>- O sistema deve emitir um comprovante de entrega ao final.<br>- Caso haja erros, o app deve orientar a correção. |
| **RASTREABILIDADE**        | [RF15](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                                                               |
| **STATUS**                 | Implementada                                                                                                                                                                                                                                           |
| **PRIORIDADE**             | MOSCOW - Must Have |
| **VALIDAÇÃO**              | Validada pelo usuário |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>


### US-30 - Histórico de declarações enviadas

<p style="text-align: center"><b>Tabela 30</b> - Tabela da história de usuário 30 (US-30) </p>

| Campo                      | Descrição                                                                                                                                                                                                                              |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **CÓDIGO**                 | US-30                                                                                                                                                                                                                                  |
| **TÍTULO**                 | Histórico de envio das declarações                                                                                                                                                                                                     |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero visualizar o histórico das minhas declarações já enviadas pelo app, para que eu possa consultar datas, comprovantes e possíveis pendências.                                                                   |
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve listar as declarações enviadas por ano.<br>- Deve ser possível baixar o comprovante em PDF.<br>- Declarações com pendências devem ser sinalizadas com alertas.<br>- O sistema deve permitir filtro por ano ou status. |
| **RASTREABILIDADE**        | [RF16](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                                               |
| **STATUS**                 | Implementada                                                                                                                                                                                                                           |
| **PRIORIDADE**             | MOSCOW - Must Have                                   |
| **VALIDAÇÃO**              | Validada pelo usuário |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>

### US-31 - Consulta de pendências de Malha Fiscal

<p style="text-align: center"><b>Tabela 31</b> - Tabela da história de usuário 31 (US-31) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-31                                                                     |
| **TÍTULO**                 | Consulta de pendências de Malha Fiscal                                   |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero consultar se minha declaração de imposto de renda está na malha fiscal diretamente pelo aplicativo, para que eu possa verificar possíveis inconsistências e tomar as providências necessárias rapidamente.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve exibir o status da declaração em relação à malha fiscal (em análise, liberada, retida). <br> - Deve mostrar detalhes das inconsistências encontradas quando aplicável. <br> - O aplicativo deve orientar sobre os documentos necessários para esclarecimentos. <br> - Deve permitir o acompanhamento do processo de regularização. <br> - As informações devem ser atualizadas em tempo real conforme análise da Receita Federal.                    |
| **RASTREABILIDADE**        | [RF18](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Implementada                                                              |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>
---


### US-33 - Integração com eSocial

<p style="text-align: center"><b>Tabela 33</b> - Tabela da história de usuário 33 (US-33) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-33                                                                     |
| **TÍTULO**                 | Integração com eSocial                                                    |
| **HISTÓRIA DE USUÁRIO**    | Como empregador ou profissional de RH, quero acessar funcionalidades do eSocial diretamente pelo aplicativo da Receita Federal, para que eu possa gerenciar informações trabalhistas e previdenciárias de forma integrada e prática.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O aplicativo deve permitir acesso às principais funcionalidades do eSocial. <br> - Deve ser possível consultar eventos enviados e pendências. <br> - O sistema deve sincronizar dados entre as plataformas automaticamente. <br> - Deve incluir notificações sobre prazos e obrigações do eSocial. <br> - A navegação entre os sistemas deve ser transparente para o usuário.                    |
| **RASTREABILIDADE**        | [RF22](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Não implementada                                                          |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>

---

### US-34 - Autorização de acesso a terceiros

<p style="text-align: center"><b>Tabela 34</b> - Tabela da história de usuário 34 (US-34) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-34                                                                     |
| **TÍTULO**                 | Autorização de acesso a terceiros                                        |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero autorizar o acesso de terceiros (contadores, advogados, familiares) aos meus dados fiscais diretamente pelo aplicativo, para que eu possa permitir que profissionais me auxiliem sem precisar comparecer presencialmente ou usar procuração física.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve permitir buscar e selecionar terceiros por CPF/CNPJ. <br> - Deve ser possível definir quais informações o terceiro pode acessar. <br> - As autorizações devem ter prazo de validade configurável. <br> - O usuário deve poder revogar autorizações a qualquer momento. <br> - Deve manter histórico de acessos realizados pelos terceiros autorizados.                    |
| **RASTREABILIDADE**        | [RF22](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Implementada                                                              |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>

---

### US-35 - Consulta de tabelas auxiliares

<p style="text-align: center"><b>Tabela 35</b> - Tabela da história de usuário 35 (US-35) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-35                                                                     |
| **TÍTULO**                 | Consulta de tabelas auxiliares (CNAE, NCM, unidades da RF)               |
| **HISTÓRIA DE USUÁRIO**    | Como empresário ou profissional contábil, quero consultar tabelas de códigos CNAE, NCM e localizar unidades da Receita Federal diretamente pelo aplicativo, para que eu possa obter informações técnicas necessárias para preenchimento de documentos e obrigações fiscais.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve permitir busca por código ou descrição nas tabelas CNAE e NCM. <br> - Deve incluir filtro geográfico para localizar unidades da Receita Federal próximas. <br> - As informações devem incluir endereços, telefones e horários de funcionamento das unidades. <br> - Deve permitir favoritar códigos ou unidades frequentemente consultados. <br> - As tabelas devem ser atualizadas automaticamente conforme alterações oficiais.                    |
| **RASTREABILIDADE**        | [RF29](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Implementada                                                              |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>

---

### US-36 - Acesso à Caixa Postal oficial

<p style="text-align: center"><b>Tabela 36</b> - Tabela da história de usuário 36 (US-36) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-36                                                                     |
| **TÍTULO**                 | Acesso à Caixa Postal oficial                                            |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero acessar minha caixa postal oficial da Receita Federal diretamente pelo aplicativo, para que eu possa receber e consultar comunicações, intimações e documentos oficiais de forma segura e centralizada.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve exibir todas as mensagens oficiais da Receita Federal. <br> - Mensagens devem ser organizadas por data e tipo (informativa, intimação, cobrança). <br> - Deve permitir marcar mensagens como lidas/não lidas. <br> - O usuário deve poder fazer download de anexos quando disponíveis. <br> - Deve incluir notificações push quando novas mensagens chegarem.                    |
| **RASTREABILIDADE**        | [RF30](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Implementada                                                              |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |


<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>


## Video da validação 


### Validação das US 01 - US 06 

<p style="text-align: center"><b>Video 1</b> - Validacao US 01 - US 06 </p>

<iframe width="600" height="315" 
        src="https://www.youtube.com/embed/VzbIkqX-3Po" 
        title="YouTube video player" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
        referrerpolicy="strict-origin-when-cross-origin" 
        allowfullscreen>
</iframe>

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>

## Referencias 

> <a>1.</a> PRESSMAN, Roger S.; MAXIM, Bruce R. *Engenharia de Software*. McGraw-Hill, 2016.
>

> <a>2.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 15. UnB, 2025. Disponível em: https://aprender3.unb.br/pluginfile.php/3096144/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf. Acesso em: 31 de maio 2025.
>

## Histórico de versão
Versão |   Data     | Descrição | Autor(es) | Revisor(es)
------ | ---------- | --------------------------------------------- | ---------- | ----------
`1.0`  | 31/05/2025 | Criação do documento das histórias de usuário | [Jose Eduardo](https://github.com/jevprado) | [Thales Germano](https://github.com/thalesgvl) |
`1.1`  | 31/05/2025 | Criação das US01 - US06 | [Jose Eduardo](https://github.com/jevprado) | [Thales Germano](https://github.com/thalesgvl) |
`1.2`  | 31/05/2025 | Criação das US25 - US30 | [Diassis](https://github.com/Diaxiz) | [Jose Eduardo](https://github.com/jevprado) |
`1.3`  | 31/05/2025 | Criação das US07 - US12 | [Thales Germano](https://github.com/thalesgvl) |[Diassis](https://github.com/Diaxiz) |
`1.4`  | 31/05/2025 | Criação das US13 - US18 | [Júlia Massuda](https://github.com/JuliaReis18) |[]() |
`1.5`  | 31/05/2025 | Criação das US31 - US36 | [João Pedro Rodrigues](https://github.com/JpRodrigues2) |[Júlia Massuda](https://github.com/JuliaReis18)|
`1.6`  | 06/06/2025 | Adicionando Validaçao e Priorização das US13 - US18 | [Júlia Massuda](https://github.com/JuliaReis18) |[Jose Eduardo](https://github.com/jevprado) |
`1.7`  | 06/06/2025 | Correções e Validações US-25 até US-30 | [Diassis](https://github.com/Diaxiz) |[Jose Eduardo](https://github.com/jevprado) |
`1.8`  | 08/06/2025 | Removendo US repetidas ou sem RF relacionado | [Jose Eduardo](https://github.com/jevprado) | [Diassis](https://github.com/Diaxiz) |
`1.9`  | 08/06/2025 | Adicionando o video de validacao e priorizacao US 01 - US 06 | [Jose Eduardo](https://github.com/jevprado) | [Júlia Massuda](https://github.com/JuliaReis18) |
