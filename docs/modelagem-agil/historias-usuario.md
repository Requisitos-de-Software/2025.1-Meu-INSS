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
| [José Eduardo](https://github.com/jevprado)        | US01, US02, US03, US04, US05, US06 |       |                     |
| [Thales Germano](https://github.com/thalesgvl)     | US07, US08, US09, US10, US11, US12 |       |                     |
| [Julia Massuda](https://github.com/JuliaReis18)    | US13, US14, US15, US16, US17, US18 |       |                     |
| [Andre Lopes](https://github.com/andrewslopes)     | US19, US20, US21, US22, US23, US24 |       |                     |
| [Diassis](https://github.com/Diaxiz)               | US25, US26, US27, US28, US29, US30 |       |                     |
| [João Pedro](https://github.com/JpRodrigues2)      | US31, US32, US33, US34, US35, US36 |       |                     |
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
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

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
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

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
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

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
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

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
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

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
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado), 2025.</p></font>


### US-07 - Acesso offline a serviços essenciais do app

<p style="text-align: center"><b>Tabela 7</b> - Tabela da história de usuário 07 (US-07) </p>

| Campo                      | Descrição                                                                                                                                                                                        |
|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **CÓDIGO**                 | US-07                                                                                                                                                                                             |
| **TÍTULO**                 | Acesso offline a serviços essenciais do app                                                                                                                                                       |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero acessar alguns serviços essenciais do aplicativo mesmo sem conexão com a internet, para consultar rapidamente dados como históricos de contribuição e DARFs emitidos.  |
| **CRITÉRIOS DE ACEITAÇÃO** | - O aplicativo deve permitir acesso offline ao histórico de contribuições e DARFs previamente baixados. <br> - O sistema deve alertar que os dados estão desatualizados sem conexão.            |
| **RASTREABILIDADE**        | [RF20](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                        | 
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
| **RASTREABILIDADE**        | [RF26](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                              | 
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
| **RASTREABILIDADE**        | [RF06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                          | 
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
| **RASTREABILIDADE**        | [RF29](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                          | 
| **STATUS**                 | Implementada                                                                                                                                                      |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                                                                                                         |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                                                                                                        |

<font size="3"><p style="text-align: center">Fonte: [Thales Germano](https://github.com/thalesgvl), 2025.</p></font>

```markdown
### US-13 - Compartilhamento de comprovantes e certidões

<p style="text-align: center"><b>Tabela 13</b> - Tabela da história de usuário 13 (US-13) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-13                                                                     |
| **TÍTULO**                 | Compartilhamento de comprovantes e certidões                             |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero compartilhar meus comprovantes e certidões diretamente pelo aplicativo através de WhatsApp, e-mail ou salvamento em nuvem, para que eu possa enviar documentos oficiais de forma prática e segura quando solicitado.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O aplicativo deve permitir compartilhamento via WhatsApp, e-mail e Google Drive/iCloud. <br> - Documentos devem manter formato oficial e assinatura digital. <br> - Deve ser possível compartilhar múltiplos documentos simultaneamente. <br> - O sistema deve registrar o histórico de compartilhamentos para auditoria. <br> - Deve incluir opções de proteção por senha nos documentos compartilhados.                    |
| **RASTREABILIDADE**        | [RF24](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Não implementada                                                          |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>

### US-14 - Reenvio de notificações perdidas

<p style="text-align: center"><b>Tabela 14</b> - Tabela da história de usuário 14 (US-14) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-14                                                                     |
| **TÍTULO**                 | Reenvio de notificações perdidas                                         |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero poder solicitar o reenvio de notificações importantes que perdi ou não recebi, através de e-mail ou mensagem no aplicativo, para que eu não perca prazos importantes por falha na comunicação.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O usuário deve conseguir visualizar histórico de notificações enviadas. <br> - Deve ser possível reenviar notificações via e-mail ou push no app. <br> - O sistema deve permitir configurar canais preferenciais de comunicação. <br> - Deve incluir filtros por tipo de notificação e período. <br> - Notificações críticas devem ter opção de reenvio automático.                    |
| **RASTREABILIDADE**        | [RF25](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Não implementada                                                          |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>

### US-15 - Comparativo automático entre declarações

<p style="text-align: center"><b>Tabela 15</b> - Tabela da história de usuário 15 (US-15) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-15                                                                     |
| **TÍTULO**                 | Comparativo automático entre declarações                                 |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte que declara imposto de renda anualmente, quero visualizar um comparativo automático entre minha declaração atual e as de anos anteriores, para que eu possa identificar discrepâncias e garantir consistência nas informações prestadas.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve gerar comparativo visual entre declarações de diferentes anos. <br> - Deve destacar variações significativas em rendimentos, deduções e impostos. <br> - O usuário deve poder selecionar quais anos comparar. <br> - Deve incluir alertas para divergências que possam gerar questionamentos. <br> - O comparativo deve ser exportável em formato PDF.                    |
| **RASTREABILIDADE**        | [RF26](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Não implementada                                                          |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>

### US-16 - FAQ interativo com busca inteligente

<p style="text-align: center"><b>Tabela 16</b> - Tabela da história de usuário 16 (US-16) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-16                                                                     |
| **TÍTULO**                 | FAQ interativo com busca inteligente                                     |
| **HISTÓRIA DE USUÁRIO**    | Como usuário do aplicativo, quero acessar um FAQ interativo com busca inteligente filtrada por temas como CPF, IRPF e Certidões, para que eu possa encontrar respostas rápidas e precisas para minhas dúvidas sem precisar entrar em contato com atendimento.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve permitir busca por palavras-chave com sugestões automáticas. <br> - Deve incluir filtros por categoria (CPF, IRPF, Certidões, etc.). <br> - As respostas devem ser organizadas por relevância e popularidade. <br> - Deve incluir recursos visuais como imagens e vídeos explicativos. <br> - O usuário deve poder avaliar a utilidade das respostas encontradas.                    |
| **RASTREABILIDADE**        | [RF27](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Não implementada                                                          |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>

### US-17 - Integração com calendário do dispositivo

<p style="text-align: center"><b>Tabela 17</b> - Tabela da história de usuário 17 (US-17) </p>

| Campo                      | Descrição                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **CÓDIGO**                 | US-17                                                                     |
| **TÍTULO**                 | Integração com calendário do dispositivo                                 |
| **HISTÓRIA DE USUÁRIO**    | Como contribuinte, quero que o aplicativo se integre automaticamente com o calendário do meu dispositivo para criar lembretes de obrigações fiscais, para que eu possa visualizar todos os meus compromissos tributários junto com minha agenda pessoal.      |
| **CRITÉRIOS DE ACEITAÇÃO** | - O aplicativo deve solicitar permissão para acessar o calendário do usuário. <br> - Deve criar eventos automaticamente para vencimentos de obrigações fiscais. <br> - Os eventos devem incluir informações detalhadas sobre a obrigação. <br> - O usuário deve poder personalizar antecedência dos lembretes. <br> - Deve sincronizar automaticamente mudanças de datas e novos prazos.                    |
| **RASTREABILIDADE**        | [RF28](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                      | 
| **STATUS**                 | Não implementada                                                          |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

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
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                 |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>
```

### US-25 - Acesso simultâneo a múltiplos CPFs/CNPJs

<p style="text-align: center"><b>Tabela 25</b> - Tabela da história de usuário 25 (US-25) </p>

| Campo                      | Descrição                                                                                                                                                                                                                                                               |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **CÓDIGO**                 | US-25                                                                                                                                                                                                                                                                   |
| **TÍTULO**                 | Acesso simultâneo a múltiplos CPFs/CNPJs                                                                                                                                                                                                                                |
| **HISTÓRIA DE USUÁRIO**    | Como contador, quero acessar rapidamente diversos CPFs e CNPJs de meus clientes pelo app, para que eu possa gerenciar múltiplas declarações e obrigações fiscais de forma prática e eficiente.                                                                          |
| **CRITÉRIOS DE ACEITAÇÃO** | - O sistema deve permitir o login e alternância entre diferentes CPFs/CNPJs.<br>- Deve haver um menu ou dashboard que exiba todos os perfis acessíveis com seus respectivos nomes.<br>- O usuário deve conseguir alternar entre perfis sem precisar sair do aplicativo. |
| **RASTREABILIDADE**        | [RF1](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                                                                                 |
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
| **RASTREABILIDADE**        | [RF2](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#tabela-01-requisitos-funcionais)                                                                                                                                                                                                |
| **STATUS**                 | Não implementada                                                                                                                                                                                                                                                                                                                       |
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                                                                                                                                                                                                                                                                              |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                                                                                                                                                                                                                                                                             |

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
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                                                                                                                                                                                     |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                                                                                                                                                                                    |

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
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                                                                                                                                                                                             |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                                                                                                                                                                                            |

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
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                                                                                                                                                                                              |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                                                                                                                                                                                             |

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
| **PRIORIDADE**             | MOSCOW *(Cliente define)*                                                                                                                                                                                                              |
| **VALIDAÇÃO**              | Validada / Não validada *(Cliente define)*                                                                                                                                                                                             |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>


## Video da validação 



## Referencias 

## Histórico de versão
Versão |   Data     | Descrição | Autor(es) | Revisor(es)
------ | ---------- | --------------------------------------------- | ---------- | ----------
`1.0`  | 31/05/2025 | Criação do documento das histórias de usuário | [Jose Eduardo](https://github.com/jevprado) | [Thales Germano](https://github.com/thalesgvl) |
`1.1`  | 31/05/2025 | Criação das US01 - US06 | [Jose Eduardo](https://github.com/jevprado) | [Thales Germano](https://github.com/thalesgvl) |
`1.2`  | 31/05/2025 | Criação das US25 - US30 | [Diassis](https://github.com/Diaxiz) | [Jose Eduardo](https://github.com/jevprado) |
`1.3`  | 31/05/2025 | Criação das US07 - US12 | [Thales Germano](https://github.com/thalesgvl) |[Diassis](https://github.com/Diaxiz) |
`1.4`  | 31/05/2025 | Criação das US13 - US18 | [Júlia Massuda](https://github.com/JuliaReis18) |[]() |