## Introdução 

A pós-rastreabilidade desempenha um papel fundamental na verificação da conformidade entre os requisitos elicitados e os elementos que os representam nas fases subsequentes do desenvolvimento. Seu principal objetivo é garantir que cada requisito — funcional ou não funcional — tenha continuidade e seja refletido de forma clara na arquitetura, nos artefatos de projeto e futuramente na implementação do sistema.

## Metodologia 

Para estruturar a análise de pós-rastreabilidade no sistema da Receita Federal, foi adotado um modelo padronizado de cartão que organiza de forma sistemática os vínculos entre os requisitos e seus artefatos relacionados. Esse modelo permite rastrear a evolução dos requisitos a partir de suas fontes de origem até sua implementação, promovendo a transparência e a rastreabilidade entre as diversas fases do processo de engenharia de requisitos.

**Tabela base dessa etapa é:**

Tabela 1 - Template do cartão usado na pós-rastreabilidade

| Artefato Analisado| Classificação do Artefato Analisado |
| ------------- | ---------------------------------- |
| Descrição     |       Descrição do requisito                                               |
| Tipos de Elo  | Ambiental/Organizacional/Gerencial/Desenvolvimento                         |
| Código do req    | RF e RNF/  |
| Backward-from | TIPO DE ELO (Origem) - US,C,L,USA, CON, DES, SUP, AC / INT, ADC, GDF, ST / NFRx, US, E        |
| Foward-from   |  TIPO DE ELO (Relação)                - Satisfação/agregação + descrição                  |
| Representação |         Imagem ou vídeo             |

<font size="3"><p style="text-align: center">Fonte: Seu nome aqui, 2025 </p></font>

## Participação por membro da equipe 

| Nome do membro                                  | Elos do membro    |
| ----------------------------------------------- | ----------------- |
|[José Eduardo](https://github.com/jevprado)      | ----------------- |
|[Diassis](https://github.com/Diaxiz)             | ----------------- |
|[Julia Massuda](https://github.com/JuliaReis18)  | ----------------- |
|[Andre Lopes](https://github.com/andrewslopes)   | ----------------- |
|[João Pedro](https://github.com/JpRodrigues2)    | ----------------- |
|[Marco Marques](https://github.com/marcomarquesdc)| ----------------- |

## Requisitos

### RF02

<p style="text-align: center"><b>Tabela 2</b> - Tabela 2 - Cartão Pós Rastreabilidade RF02 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Cadastro de CPF via app (totalmente remoto) |
| **Tipos de Elo** | Desenvolvimento |
| **Código do req** | [RF02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf02) |
| **Backward-from** | [ADC2](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [US26](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-26-cadastro-de-cpf-via-aplicativo), [C01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/cenarios/#cenario-01) |
| **Foward-from** | Agregação – Relacionado à etapa de inscrição<br>Satisfação – Reduz burocracia para o usuário |
| **Representação** | |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>

### RF03

<p style="text-align: center"><b>Tabela 3</b> - Tabela 3 - Cartão Pós Rastreabilidade RF03 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Acompanhamento de status da restituição (precisão quanto aos lotes) |
| **Tipos de Elo** | Organizacional |
| **Código do req** | [RF03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf03) |
| **Backward-from** | [ADC3](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [ST02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/), [C04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/cenarios/#cenario-04), [L04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/lexicos/#l04-visualizar-restituicao), [US01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/) |
| **Foward-from** | Agregação – Relacionado à etapa de restituição |
| **Representação** | ![prototipo req 03](../assets/prototipacao/prototipo-jose/proto-RF03.gif) |

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>

---
### RF05

<p style="text-align: center"><b>Tabela 5</b> - Tabela 5 - Cartão Pós Rastreabilidade RF05 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Agendar no próprio aplicativo atendimentos presenciais em unidades da Receita Federal |
| **Tipos de Elo** | Organizacional |
| **Código do req** | [RF05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf05) |
| **Backward-from** | [INT3](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/), [US02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-02-agendar-no-proprio-app-da-receita-atendimentos-presenciais)|
| **Foward-from** | Integração – Sistemas de agendamento da Receita<br>Satisfação – Facilidade de acesso aos serviços presenciais |
| **Representação**| ![prototipo req 05](../assets/prototipacao/prototipo-jose/proto-RF05.gif)|

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>

---
### RF07

<p style="text-align: center"><b>Tabela 6</b> - Cartão Pós Rastreabilidade RF07</p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| *Descrição* | O aplicativo deve fornecer uma agenda fiscal com lembretes para prazos de entrega de declarações. |
| *Tipos de Elo* | Desenvolvimento |
| *Código do req* | [RF07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf07) |
| *Backward-from* | [US-04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-04-gerenciamento-de-prazos-fiscais), [C07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/cenarios/#cenario-07), [L07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/lexicos/#l07-agenda-fiscal), [UC-Configurar Lembretes Fiscais](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/casos-de-uso/#uc-configurar-lembretes-fiscais), [E04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/epicos/#e04-atendimento-e-comunicacao), [USA05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/especificacao-suplementar/#usa05-design-responsivo), [USA08](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/especificacao-suplementar/#usa08-notificacoes-automaticas) |
| *Foward-from* | Agregação – História de Usuário: US-04 - Gerenciamento de prazos fiscais; Feature: F04 - Agenda fiscal com lembretes<br>Satisfação – Especificação Suplementar: USA05, USA08 |
| *Representação* | - |

<font size="3"><p style="text-align: center">Fonte: André Lopes, 2025.</p></font>

### RF10

<p style="text-align: center"><b>Tabela 10</b> - Tabela 10 - Cartão Pós Rastreabilidade RF10</p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Geração de guias de pagamento |
| **Tipos de Elo** | Desenvolvimento |
| **Código do req** | [RF10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf10) |
| **Backward-from** | [ADC10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [ST03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/),  [C07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/cenarios/#cenario-07), [L02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/lexicos/#l02-gerar-darf), [L08](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/lexicos/#l08-pagar-divida-ativa), [US03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-03-geracao-de-guias-de-pagamento), [UC](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/casosdeuso/#41-ator-primario-contribuinte) |
| **Foward-from** |  Integração – Conectado ao sistema de arrecadação |
| **Representação** |![guiapagemento - imagem 01](../assets/prints-jose/guia-pagemento%20(1).jpg) e ![guiapagemento - imagem 02](../assets/prints-jose/guia-pagemento%20(2).jpg)|

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>


---

### RF11

<p style="text-align: center"><b>Tabela 11</b> - Tabela 11 - Cartão Pós Rastreabilidade RF11</p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Consultar o status do CPF (ativo ou não) |
| **Tipos de Elo** | Organizacional |
| **Código do req** | [RF11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf11) |
| **Backward-from** | [ADC11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [ST06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/), [C06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/cenarios/#cenario-06), [L01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/lexicos/#l01-consultar-cpf), [US04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-04-consulta-de-status-do-cpf-pelo-aplicativo-da-receita-federal)|  [ELO11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/rastreabilidade/pos-rastreabilidade/) |
| **Foward-from** | Integração – Consulta em bases oficiais da Receita |
| **Representação** | ![status cpf](../assets/prints-jose/status-cpf.png) |

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>

---

### RF12

<p style="text-align: center"><b>Tabela 12</b> - Tabela 12 - Cartão Pós Rastreabilidade RF12 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Integração com conta Gov.br |
| **Tipos de Elo** | Desenvolvimento / Organizacional  |
| **Código do req** | [RF12](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf12) |
| **Backward-from** | [ADC12](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [ST10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/), [ENT04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/entrevista/), [US27](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-27-integracao-com-conta-govbr) |
| **Foward-from** | Agregação – Integração com autenticação do sistema<br>Satisfação – Facilita login com identidade digital |
| **Representação** |-|

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>

### RF13

<p style="text-align: center"><b>Tabela 13</b> - Tabela 13 - Cartão Pós Rastreabilidade RF13 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Envio de documentos para instrução de processos |
| **Tipos de Elo** | Desenvolvimento / Organizacional |
| **Código do req** | [RF13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf13) |
| **Backward-from** | [ADC16](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [US28](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-28-envio-de-documentos-para-instrucao-de-processos) |
| **Foward-from** | Agregação – Alocado no Módulo de Processos<br>Satisfação – Evita deslocamentos físicos para entrega documental |
| **Representação** | - |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>


### RF14

<p style="text-align: center"><b>Tabela 14</b> - Tabela 14 - Cartão Pós Rastreabilidade RF14</p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Acessar informações detalhadas acerca da declaração de imposto de renda de um ano específico |
| **Tipos de Elo** | Organizacional |
| **Código do req** | [RF14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf14) |
| **Backward-from** | [INT1](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/), [ENT03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/entrevista/), [L07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/lexicos/#l07-acompanhar-processamento), [US05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-05-acesso-a-informacoes-detalhadas-da-declaracao-de-imposto-de-renda-por-ano) |
| **Foward-from** | Agregação – Relacionado à análise de dados da declaração por período |
| **Representação** | ![Historico das declaracoes](../assets/prints-jose/historico-declaracoes.jpg) e ![Informações detalhadas]() |

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>


### RF15

<p style="text-align: center"><b>Tabela 15</b> - Tabela 15 - Cartão Pós Rastreabilidade RF15 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | O aplicativo deve permitir o envio da declaração do IR |
| **Tipos de Elo** | Desenvolvimento / Organizacional |
| **Código do req** | [RF15](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf15) |
| **Backward-from** | [INT2](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/),[ENT01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/entrevista/), [US29](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-29-envio-da-declaracao-do-ir-diretamente-pelo-app), [L03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/lexicos/#l03-declarar-imposto-de-renda) |
| **Foward-from** | Agregação – Parte do Módulo de Declarações<br>Satisfação – Simplifica o processo de declaração do IR |
| **Representação** |  |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>

---

### RF16

<p style="text-align: center"><b>Tabela 16</b> - Tabela 16 - Cartão Pós Rastreabilidade RF16 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Mostrar histórico de envio das declarações pelo usuário |
| **Tipos de Elo** | Desenvolvimento / Gerencial |
| **Código do req** | [RF16](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf16) |
| **Backward-from** | [INT5](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/), [ST09](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/), [US30](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-30-historico-de-declaracoes-enviadas) |
| **Foward-from** | Agregação – Alocado no Módulo IR<br>Satisfação – Usuário pode verificar rapidamente o histórico de suas declarações |
| **Representação** |  |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>

### RF17

<p style="text-align: center"><b>Tabela 17</b> - Tabela 17 - Cartão Pós Rastreabilidade RF17</p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Emissão de certidão negativa via aplicativo |
| **Tipos de Elo** | Organizacional |
| **Código do req** | [RF17](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf17) |
| **Backward-from** | [INT6](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/), [ENT02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/entrevista/), [L08](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/lexicos/#l08-pagar-divida-ativa), [US06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-06-emissao-de-certidao-negativa-via-aplicativo), [UC](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/casosdeuso/#41-ator-primario-contribuinte) |
| **Foward-from** | Integração – Conectado à base de débitos da Receita |
| **Representação** | ![Emitir certidão negativa](../assets/prints-jose/certidao-negativa.jpg) |

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>

### RF18

<p style="text-align: center"><b>Tabela 18</b> - Tabela 18 - Cartão Pós Rastreabilidade RF18 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| Descrição | Consulta de pendências de Malha Fiscal |
| Tipos de Elo | Desenvolvimento |
| Código do req | [RF18](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf18) |
| Backward-from | [US-31](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-31-consulta-de-pendencias-de-malha-fiscal)<br>UC: Consultar Situação Fiscal, UC: Acompanhar Processamento<br>[C04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/cenarios/#cenario-04)<br>[E06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/epicos/#e06-gestao-de-documentos-e-processos)<br>[RNF20](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem_agil/nfr-framework/#rnf20)<br>[USA06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#usa06) |
| Foward-from | Agregação – Relacionada ao acompanhamento da declaração de IR<br>Satisfação – Permite ao contribuinte verificar e resolver rapidamente inconsistências fiscais |
| Representação | Não aplicável |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>

### RF19

<p style="text-align: center"><b>Tabela 19</b> - Tabela 19 - Cartão Pós Rastreabilidade RF19 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| Descrição | O aplicativo possui um dashboard especializado que permite gerenciar múltiplos CPFs/CNPJs dos clientes. |
| Tipos de Elo | Desenvolvimento |
| Código do req | [RF19](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf19) |
| Backward-from | [US-18](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-18-dashboard-para-profissionais-contabeis)<br>[C03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/cenarios/#cenario-03)<br>[L09](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/lexicos/#l09-contribuinte)<br>UC: Relacionado a "Consultar Situação Fiscal", "Pagar Tributos", "Consultar Processos", "Acesso simultâneo a múltiplos CPFs/CNPJs"<br>[E05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/epicos/#e05-experiencia-do-usuario-e-acessibilidade)<br>[RNF20](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/nfr-framework/#rnf20), [RNF21](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/nfr-framework/#rnf21)<br>[USA06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#usa06), [CON05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#con05) |
| Foward-from | *Satisfação:* Especificação Suplementar: USA06, CON05<br>*Agregação:* História de Usuário: US-18 - Dashboard para profissionais contábeis; Feature: F21 - Dashboard para profissionais contábeis |
| Representação | Não aplicável |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>


### RF21

<p style="text-align: center"><b>Tabela 22</b> - Tabela 22 - Cartão Pós Rastreabilidade RF22 (US-33) </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| Descrição | Integração com eSocial |
| Tipos de Elo | Desenvolvimento |
| Código do req | [RF21](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf21) |
| Backward-from | [US-33](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-33-integracao-com-esocial)<br>[E07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/epicos/#e07-integracoes-e-autorizacao) |
| Foward-from | Agregação – Relacionada à integração com sistemas externos<br>Satisfação – Facilita a gestão de informações trabalhistas e previdenciárias de forma integrada |
| Representação | Não aplicável |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>

### RF22

<p style="text-align: center"><b>Tabela 22</b> - Tabela 22 - Cartão Pós Rastreabilidade RF22 (US-34) </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| Descrição | Autorização de acesso a terceiros |
| Tipos de Elo | Desenvolvimento / Organizacional |
| Código do req | [RF22](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf22) |
| Backward-from | [US-34](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-34-autorizacao-de-acesso-a-terceiros)<br>[C03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/cenarios/#cenario-03)<br>[E07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/epicos/#e07-integracoes-e-autorizacao)<br>[RNF4](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem_agil/nfr-framework/#rnf4)<br>[CON01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#con01) |
| Foward-from | Agregação – Relacionada à segurança e privacidade dos dados<br>Satisfação – Permite que profissionais auxiliem contribuintes de forma remota |
| Representação | Não aplicável |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>

### RF23

<p style="text-align: center"><b>Tabela 23</b> - Tabela 23 - Cartão Pós Rastreabilidade RF23 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| Descrição | O aplicativo permite o compartilhamento de comprovantes e certidões diretamente pelo aplicativo através de WhatsApp, e-mail ou salvamento em nuvem. |
| Tipos de Elo | Desenvolvimento |
| Código do req | [RF23](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf23) |
| Backward-from | [US-13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-13-compartilhamento-de-comprovantes-e-certidoes)<br>[C06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/cenarios/#cenario-06)<br>[L06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/lexicos/#l06-emitir-comprovante-de-rendimentos)<br>UC: Consultar Recibo<br>[E02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/epicos/#e02-regularizacao-e-pagamentos)<br>[RNF1](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/nfr-framework/#rnf1), [RNF20](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/nfr-framework/#rnf20)<br>[USA01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#usa01), [USA06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#usa06) |
| Foward-from | *Satisfação:* Especificação Suplementar: USA01, USA06<br>*Agregação:* História de Usuário: US-13 - Compartilhamento de comprovantes e certidões; Feature: F11 - Compartilhamento de comprovantes e certidões |
| Representação | Não aplicável |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>


### RF24

<p style="text-align: center"><b>Tabela 24</b> - Tabela 24 - Cartão Pós Rastreabilidade RF24 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| Descrição | O aplicativo permite o reenvio de notificações importantes que o usuário perdeu ou não recebeu. |
| Tipos de Elo | Desenvolvimento |
| Código do req | [RF24](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf24) |
| Backward-from | [US-14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-14-reenvio-de-notificacoes-perdidas)<br>UC: Relacionado a "Receber notificações da Receita"<br>[E04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/epicos/#e04-atendimento-e-comunicacao) |
| Foward-from | *Agregação:* História de Usuário: US-14 - Reenvio de notificações perdidas; Feature: F17 - Reenvio de notificações perdidas |
| Representação | Não aplicável |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>



### RF26

<p style="text-align: center"><b>Tabela 26</b> - Tabela 26 - Cartão Pós Rastreabilidade RF26 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| Descrição | O aplicativo permite acesso a um FAQ interativo com busca inteligente filtrada por temas. |
| Tipos de Elo | Desenvolvimento |
| Código do req | [RF26](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf26) |
| Backward-from | [US-16](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-16-faq-interativo-com-busca-inteligente)<br>[C02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/cenarios/#cenario-02)<br>UC: Relacionado a "Acessar vídeos e notícias institucionais" e "Sistema de Ajuda e Documentação"<br>[E04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/epicos/#e04-atendimento-e-comunicacao)<br>[RNF1](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/nfr-framework/#rnf1), [RNF2](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/nfr-framework/#rnf2)<br>[USA01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#usa01), [USA02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#usa02) |
| Foward-from | *Satisfação:* Especificação Suplementar: USA01, USA02<br>*Agregação:* História de Usuário: US-16 - FAQ interativo com busca inteligente; Feature: F18 - FAQ interativo com busca inteligente |
| Representação | Não aplicável |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>


### RF27

<p style="text-align: center"><b>Tabela 27</b> - Tabela 27 - Cartão Pós Rastreabilidade RF27 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| Descrição | O aplicativo se integra automaticamente com o calendário do dispositivo para criar lembretes de obrigações fiscais. |
| Tipos de Elo | Desenvolvimento |
| Código do req | [RF27](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf27) |
| Backward-from | [US-17](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-17-integracao-com-calendario-do-dispositivo)<br>UC: Relacionado a "Lembretes automáticos" (de Agendar Atendimento)<br>[E05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/epicos/#e05-experiencia-do-usuario-e-acessibilidade) |
| Foward-from | *Satisfação:* Especificação Suplementar: Informação não disponível<br>*Agregação:* História de Usuário: US-17 - Integração com calendário do dispositivo; Feature: F20 - Integração com calendário do dispositivo |
| Representação | Não aplicável |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>

### RF29

<p style="text-align: center"><b>Tabela 29</b> - Tabela 29 - Cartão Pós Rastreabilidade RF29 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| Descrição | Consulta de tabelas auxiliares (CNAE, NCM, unidades da RF) |
| Tipos de Elo | Desenvolvimento |
| Código do req | [RF29](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf29) |
| Backward-from | [US-35](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-35-consulta-de-tabelas-auxiliares)<br>[E07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/epicos/#e07-integracoes-e-autorizacao) |
| Foward-from | Agregação – Relacionada à disponibilização de dados de referência<br>Satisfação – Fornece informações técnicas essenciais para o preenchimento de documentos fiscais |
| Representação | Não aplicável |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>


### RF30

<p style="text-align: center"><b>Tabela 30</b> - Tabela 30 - Cartão Pós Rastreabilidade RF30 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| Descrição | Acesso à Caixa Postal oficial |
| Tipos de Elo | Desenvolvimento |
| Código do req | [RF30](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf30) |
| Backward-from | [US-36](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-36-acesso-a-caixa-postal-oficial)<br>UC: Relacionado a "Receber notificações da Receita"<br>[E07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/epicos/#e07-integracoes-e-autorizacao) |
| Foward-from | Agregação – Relacionada à comunicação oficial com o contribuinte<br>Satisfação – Permite o recebimento e consulta segura de comunicações e documentos oficiais |
| Representação | Não aplicável |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>

### RF32

<p style="text-align: center"><b>Tabela 34</b> - Cartão Pós Rastreabilidade RF32</p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| *Descrição* | O aplicativo deve permitir a integração com sistemas de pagamento para quitar débitos fiscais diretamente. |
| *Tipos de Elo* | Desenvolvimento |
| *Código do req* | [RF32](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rf32) |
| *Backward-from* | [US-15](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-15-pagamento-de-debitos-fiscais), [C10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/cenarios/#cenario-10), [L10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/lexicos/#l10-integracao-de-pagamento), [UC-Pagar Débitos Fiscais](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/casos-de-uso/#uc-pagar-debitos-fiscais), [E02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/epicos/#e02-regularizacao-e-pagamentos), [USA07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/especificacao-suplementar/#usa07-seguranca-de-autenticacao), [USA11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/especificacao-suplementar/#usa11-integracao-com-sistemas-de-pagamento) |
| *Foward-from* | Agregação – História de Usuário: US-15 - Pagamento de débitos fiscais; Feature: F12 - Integração com sistemas de pagamento<br>Satisfação – Especificação Suplementar: USA07, USA11 |
| *Representação* | - |

<font size="3"><p style="text-align: center">Fonte: André Lopes, 2025.</p></font>


### RFN01

<p style="text-align: center"><b>Tabela 35</b> - Tabela 35 - Cartão Pós Rastreabilidade RNF01 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Acessibilidade (chatbot, imagens, vídeos) — melhorias no chatbot |
| **Tipos de Elo** | Ambiental / Organizacional / Desenvolvimento |
| **Código do req** | [RNF01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf01) |
| **Backward-from** | [ADC13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) |
| **Foward-from** | Satisfação – Garante a acessibilidade de usuários com deficiência visual ou baixa escolaridade |
| **Representação** |  |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz) </p></font>

### RFN02

<p style="text-align: center"><b>Tabela 36</b> - Tabela 36 - Cartão Pós Rastreabilidade RNF02 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Conteúdo educativo para iniciantes |
| **Tipos de Elo** | Ambiental / Organizacional / Gerencial / Desenvolvimento |
| **Código do req** | [RNF02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf02) |
| **Backward-from** |[ADC14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem_agil/nfr-framework/#ADC14)<br>[ST08](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/) |
| **Foward-from** | *Satisfação*: Garante contúdo explicativo para pessoas iniciantes |
| **Representação** |  |

<font size="3"><p style="text-align: center">Fonte: [Marco Marques](https://github.com/marcomarquesdc)</p></font>

### RFN03

<p style="text-align: center"><b>Tabela 36</b> - Cartão Pós Rastreabilidade RNF03 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| *Descrição* | Testes de desempenho para suportar alta demanda de usuários simultâneos |
| *Tipos de Elo* | Desenvolvimento |
| *Código do req* | [RNF03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf03) |
| *Backward-from* | [RNF03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem_agil/nfr-framework/#rnf03)<br>[DES01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#des01)<br>[ADC15](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#adc15) |
| *Foward-from* | *Satisfação:* Especificação Suplementar: DES01 (Testes de desempenho para suportar alta demanda de usuários simultâneos)<br>*Agregação:* Informação não disponível |
| *Representação* | - |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>


### RFN03

<p style="text-align: center"><b>Tabela 37</b> - Cartão Pós Rastreabilidade RNF03 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Testes de desempenho para suportar alta demanda de usuários simultâneos |
| **Tipos de Elo** | Desenvolvimento |
| **Código do req** | [RNF03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf03) |
| **Backward-from** | RNF03<br>DES01<br> ADC15 |
| **Foward-from** | **Satisfação:** Especificação Suplementar: DES01 (Testes de desempenho para suportar alta demanda de usuários simultâneos)<br>**Agregação:** Informação não disponível |
| **Representação** | - |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>

### RFN04

<p style="text-align: center"><b>Tabela 38</b> - Tabela 38 - Cartão Pós Rastreabilidade RNF04 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| *Descrição* | A compra deve ser feita em no máximo 5 páginas. |
| *Tipos de Elo* | Desenvolvimento |
| *Código do req* | [RNF04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf04) |
| *Backward-from* | *NFR:* [RNF04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem_agil/nfr-framework/#rnf04)<br>*Especificação Suplementar:* Informação não disponível.<br>*Requisitos Elicitados:* Informação não disponível. |
| *Foward-from* | *Satisfação:* Garante um processo de compra rápido e simplificado para o usuário.<br>*Agregação:* Informação não disponível |
| *Representação* | --- |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>

### RFN05

<p style="text-align: center"><b>Tabela 39</b> - Cartão Pós Rastreabilidade RNF05</p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| *Descrição* | O sistema deve garantir a conformidade com as normas de acessibilidade, permitindo o uso por pessoas com deficiência visual, auditiva ou motora. |
| *Tipos de Elo* | Desenvolvimento |
| *Código do req* | [RNF05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf05) |
| *Backward-from* | [US-01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-01-acessibilidade-para-pessoas-com-deficiencia), [C01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/cenarios/#cenario-01), [L01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/lexicos/#l01-acessibilidade), [UC-Navegação Acessível](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/casos-de-uso/#uc-navegacao-acessivel), [E01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/epicos/#e01-inclusao-e-acessibilidade), [USA01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/especificacao-suplementar/#usa01-acessibilidade) |
| *Foward-from* | Agregação – História de Usuário: US-01 - Acessibilidade para pessoas com deficiência; Feature: F01 - Suporte a acessibilidade<br>Satisfação – Especificação Suplementar: USA01 |
| *Representação* | - |

<font size="3"><p style="text-align: center">Fonte: André Lopes, 2025.</p></font>

### RFN06

<p style="text-align: center"><b>Tabela 40</b> - Tabela 40 - Cartão Pós Rastreabilidade RNF06 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Interface com a possibilidade de uso do modo escuro |
| **Tipos de Elo** | Ambiental / Desenvolvimento |
| **Código do req** | [RNF06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf06) |
| **Backward-from** | [ADC23](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [INT17](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/), [ST11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/) |
| **Foward-from** | Satisfação – Melhora a experiência do usuário em ambientes com baixa luminosidade |
| **Representação** |  |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz) </p></font>

### RFN07

<p style="text-align: center"><b>Tabela 41</b> - Tabela 41 - Cartão Pós Rastreabilidade RNF07 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Testes de segurança para garantir a integridade dos dados e autenticação segura |
| **Tipos de Elo** | Ambiental / Organizacional / Gerencial / Desenvolvimento |
| **Código do req** | [RNF07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf07) |
| **Backward-from** | [ADC19](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#adc19)|
| **Foward-from** | *Satisfação*: Garante testes para a segurança de dados |
| **Representação** |  |

<font size="3"><p style="text-align: center">Fonte: [Marco Marques](https://github.com/marcomarquesdc)</p></font>

### RFN08

<p style="text-align: center"><b>Tabela 42</b> - Cartão Pós Rastreabilidade RNF08 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| *Descrição* | Compatível com Android 8+ e iOS 14+ |
| *Tipos de Elo* | Desenvolvimento |
| *Código do req* | [RNF08](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf08) |
| *Backward-from* | *NFR:* [RNF08](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem_agil/nfr-framework/#rnf08)<br>*Especificação Suplementar:* [SUP02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#sup02)<br>*Requisitos Elicitados:* [ADC20](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#adc20) |
| *Foward-from* | *Satisfação:* Especificação Suplementar: SUP02 (Compatível com Android 8+ e iOS 14+)<br>*Agregação:* Informação não disponível |
| *Representação* | ![Representação do App](../assets/Representação%20app.png) |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>


### RFN09

<p style="text-align: center"><b>Tabela 43</b> - Tabela 43 - Cartão Pós Rastreabilidade RNF09 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| *Descrição* | Testes de usabilidade semestrais com público 60+ |
| *Tipos de Elo* | Desenvolvimento |
| *Código do req* | [RNF09](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf09) |
| *Backward-from* | *NFR:* [RNF09](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem_agil/nfr-framework/#rnf09)<br>*Especificação Suplementar:* [USA04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#usa04)<br>*Requisitos Elicitados:* [ADC21](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#adc21) |
| *Foward-from* | *Satisfação:* Garante que o aplicativo seja acessível e fácil de usar para idosos.<br>*Agregação:* Informação não disponível |
| *Representação* | --- |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>

### RFN10

<p style="text-align: center"><b>Tabela 44</b> - Tabela 44 - Cartão Pós Rastreabilidade RNF10 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | O aplicativo deve ter tempo de resposta inferior a 3 segundos para ações comuns |
| **Tipos de Elo** | Ambiental / Organizacional / Gerencial / Desenvolvimento |
| **Código do req** | [RNF10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf10) |
| **Backward-from** | INT9 |
| **Foward-from** |  |
| **Representação** |  |

<font size="3"><p style="text-align: center">Fonte: </p></font>

### RFN11

<p style="text-align: center"><b>Tabela 45</b> - Tabela 45 - Cartão Pós Rastreabilidade RNF11 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | O aplicativo deve funcionar em smartphones com telas de 4.5" a 7" sem perda de usabilidade |
| **Tipos de Elo** | Ambiental / Desenvolvimento |
| **Código do req** | [RNF11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf11) |
| *Tipos de Elo* | Desenvolvimento |
| *Código do req* | [RNF11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf11) |
| *Backward-from* | [US-09](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-09-interface-responsiva), [C05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/cenarios/#cenario-05), [L05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/lexicos/#l05-responsividade), [UC-Interface Adaptável](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/casos-de-uso/#uc-interface-adaptavel), [E05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/epicos/#e05-experiencia-do-usuario), [USA05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/especificacao-suplementar/#usa05-design-responsivo) |
| *Foward-from* | Agregação – História de Usuário: US-09 - Interface responsiva; Feature: F09 - Interface adaptável a dispositivos<br>Satisfação – Especificação Suplementar: USA05 |
| *Representação* | - |

<font size="3"><p style="text-align: center">Fonte: André Lopes, 2025.</p></font>


### RFN12

<p style="text-align: center"><b>Tabela 46</b> - Tabela 46 - Cartão Pós Rastreabilidade RNF12 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Linguagem da interface deve seguir padrão A2 do CEFR, evitando jargões técnicos |
| **Tipos de Elo** | Ambiental / Organizacional / Gerencial / Desenvolvimento |
| **Código do req** | [RNF12](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf12) |
| **Backward-from** | [ADC25](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) |
| **Foward-from** | *Satisfação*: Garante uma linguagem para todos os públicos |
| **Representação** |  |

<font size="3"><p style="text-align: center">Fonte: [Marco Marques](https://github.com/marcomarquesdc)</p></font>

### RFN13

<p style="text-align: center"><b>Tabela 47</b> - Cartão Pós Rastreabilidade RNF13 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| *Descrição* | O app deve suportar modo de operação em baixa conectividade, com cache de dados essenciais |
| *Tipos de Elo* | Desenvolvimento |
| *Código do req* | [RNF13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf13) |
| *Backward-from* | [RNF13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem_agil/nfr-framework/#rnf13)<br>[DES03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#des03)<br>[INT11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#int11) |
| *Foward-from* | *Satisfação:* Especificação Suplementar: DES03 (Suporte offline com cache de dados essenciais em baixa conectividade)<br>*Agregação:* Informação não disponível |
| *Representação* | Não aplicável |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>



### RFN14

<p style="text-align: center"><b>Tabela 48</b> - Cartão Pós Rastreabilidade RNF14 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| *Descrição* | Atualizações do app não devem causar perda de dados armazenados localmente |
| *Tipos de Elo* | Desenvolvimento |
| *Código do req* | [RNF14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf14) |
| *Backward-from* | *NFR:* [RNF14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem_agil/nfr-framework/#rnf14)<br>*Especificação Suplementar:* [CON03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#con03)<br>*Requisitos Elicitados:* [INT12](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#int12) |
| *Foward-from* | *Satisfação:* Garante a integridade e a segurança dos dados do usuário.<br>*Agregação:* Informação não disponível |
| *Representação* | --- |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>


### RFN15

<p style="text-align: center"><b>Tabela 49</b> - Tabela 49 - Cartão Pós Rastreabilidade RNF15 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Tempo de inatividade programada máximo de 2h por mês, com aviso prévio |
| **Tipos de Elo** | Ambiental / Organizacional / Gerencial / Desenvolvimento |
| **Código do req** | [RNF15](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf15) |
| **Backward-from** | INT13 |
| **Foward-from** |  |
| **Representação** |  |

<font size="3"><p style="text-align: center">Fonte: </p></font>

### RFN16

<p style="text-align: center"><b>Tabela 50</b> - Tabela 50 - Cartão Pós Rastreabilidade RNF16 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Tempo de carregamento inicial do app não deve ultrapassar 5 segundos em conexão móvel |
| **Tipos de Elo** | Ambiental / Desenvolvimento / Gerencial |
| **Código do req** | [RNF16](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf16) |
| **Backward-from** | [ADC24](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) |
| **Foward-from** | Satisfação – Melhora a experiência inicial e reduz evasão no uso do app |
| **Representação** | [US32](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-32-agilidade-no-carregamento-do-app) |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz) </p></font>

### RFN17

<p style="text-align: center"><b>Tabela 51</b> - Tabela 51 - Cartão Pós Rastreabilidade RNF17 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Suporte a leitores de tela (TalkBack, VoiceOver) em todas as funcionalidades |
| **Tipos de Elo** | Ambiental / Organizacional / Gerencial / Desenvolvimento |
| **Código do req** | [RNF17](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf17) |
| **Backward-from** | [INT14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#int14)<br>[ADC22](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) |
| **Foward-from** | *Satisfação*: Fornece suporte para leitura |
| **Representação** |  |

<font size="3"><p style="text-align: center">Fonte: </p></font>

### RFN18

<p style="text-align: center"><b>Tabela 52 </b> - Cartão Pós Rastreabilidade RNF18 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| *Descrição* | Armazenamento anônimo de logs de erro respeitando a LGPD |
| *Tipos de Elo* | Desenvolvimento / Organizacional |
| *Código do req* | [RNF18](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf18) |
| *Backward-from* | [RNF18](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem_agil/nfr-framework/#rnf18)<br>[CON04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#con04)<br>[INT15](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#int15) |
| *Foward-from* | *Satisfação:* Especificação Suplementar: CON04 (Armazenamento anônimo de logs de erro respeitando a LGPD)<br>*Agregação:* Informação não disponível |
| *Representação* | - |

<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>

### RFN19

<p style="text-align: center"><b>Tabela 53</b> - Tabela 53 - Cartão Pós Rastreabilidade RNF19 </p>


| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| *Descrição* | Versão mínima em HTML5 responsiva para acesso via navegador em caso de falha do app |
| *Tipos de Elo* | Desenvolvimento |
| *Código do req* | [RNF19](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf19) |
| *Backward-from* | *NFR:* [RNF19](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem_agil/nfr-framework/#rnf19)<br>*Especificação Suplementar:* [SUP04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/especificacaosuplementar/#sup04)<br>*Requisitos Elicitados:* [INT16](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#int16) |
| *Foward-from* | *Satisfação:* Garante a continuidade do acesso aos serviços em caso de falha do aplicativo nativo.<br>*Agregação:* Informação não disponível |
| *Representação* | --- |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>

### RFN20

<p style="text-align: center"><b>Tabela 54</b> - Cartão Pós Rastreabilidade RNF20</p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| *Descrição* |  Clareza na apresentação de dados fiscais |
| *Tipos de Elo* | Desenvolvimento |
| *Código do req* | [RNF20](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf20) |
| *Backward-from* | [US-13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-13-compartilhamento-de-comprovantes-e-certidoes), [C06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/cenarios/#cenario-06), [L06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/lexicos/#l06-emitir-comprovante-de-rendimentos), [UC-Consultar Recibo](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem/casos-de-uso/#uc-consultar-recibo), [E02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/epicos/#e02-regularizacao-e-pagamentos), [USA06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/especificacao-suplementar/#usa06-clareza-na-apresentacao-de-dados-fiscais) |
| *Foward-from* | Agregação – História de Usuário: US-13 - Compartilhamento de comprovantes e certidões; Feature: F11 - Compartilhamento de comprovantes e certidões<br>Satisfação – Especificação Suplementar: USA06 |
| *Representação* | - |

<font size="3"><p style="text-align: center">Fonte: André Lopes, 2025.</p></font>


### RFN21

<p style="text-align: center"><b>Tabela 55</b> - Tabela 21 - Cartão Pós Rastreabilidade RNF21 </p>

| Artefato Analisado | Classificação do Artefato Analisado |
|--------------------|--------------------------------------|
| **Descrição** | Integração confiável com serviços externos (Gov.br, instituições financeiras) |
| **Tipos de Elo** | Organizacional / Desenvolvimento |
| **Código do req** | [RNF21](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/#rnf21) |
| **Backward-from** | [ST13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/), [ENT05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/entrevista/), [US39](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/modelagem-agil/historias-usuario/#us-39-conectar-com-servicos-externos) |
| **Foward-from** | Agregação – Interoperabilidade entre Receita Federal e serviços federais |
| **Representação** | - |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz)</p></font>

---

## Referências 

> <a>1.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf.
>
> <a>2.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 26. Universidade de Brasília, Campus Gama (UnB Gama). Material de aula. 
>


## Histórico de Versões

| Versão | Data       | Descrição                                      | Autor(es)                                      | Revisor(es)                                    |
| ------ | ---------- | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- |
| `1.0`  | 05/06/2025 | Criação do documento de pós rastreabilidade    | [José Eduardo](https://github.com/jevprado)    | [Diassis](https://github.com/Diaxiz) |
| `1.1`  | 08/06/2025 | Criação do cartão de referencia | [José Eduardo](https://github.com/jevprado)  | [Diassis](https://github.com/Diaxiz) |
| `1.2`  | 08/06/2025 | Criação dos cartões RF02, RF12, RF13, RF15, RF16, RF20 e RNF01, RNF06, RNF11, RNF16 e RNF21 | [Diassis](https://github.com/Diaxiz)   | [José Eduardo](https://github.com/jevprado) |
| `1.3`  | 08/06/2025 | Criação dos cartões RF03, RF05, RF10, RF11, RF14 e  RF17 e RNF01, RNF06, RNF11, RNF16 e RNF21 | [José Eduardo](https://github.com/jevprado)   | [Diassis](https://github.com/Diaxiz)  |
| `1.4`  | 08/06/2025 | Criação dos cartões RF03, RF05, RF10, RF11, RF14 e  RF17 e RNF01, RNF06, RNF11, RNF16 e RNF21 | [Diassis](https://github.com/Diaxiz)   |  [José Eduardo](https://github.com/jevprado)  |
| `1.5`  | 08/06/2025 | Criação dos cartões RF23, RF24, RF26, RF27, RF19, RNF03, RNF08, RNF13 e RNF18  | [Julia Massuda](https://github.com/JuliaReis18)  | [Diassis](https://github.com/Diaxiz) |
| `1.6`  | 08/06/2025 | Criação introdução e metodologia da pos-rastreabilidade | [José Eduardo](https://github.com/jevprado)  | [Diassis](https://github.com/Diaxiz) |
| `1.7`  | 08/06/2025 | Criação dos cartões RF18, RF22, RF22, RF29, RF30, RNF04, RNF09, RNF14 e RNF19  | [João Pedro](https://github.com/JpRodrigues2)  | [José Eduardo](https://github.com/jevprado) |
| `1.8`  | 08/06/2025 | Adicionando as referências  | [José Eduardo](https://github.com/jevprado)   | [Diassis](https://github.com/Diaxiz)  |
| `1.9`  | 08/06/2025 | Criação dos cartões RNF02, RNF07, RNF12 e RNF17 | [Marco Marques](https://github.com/marcomarquesdc) | [José Eduardo](https://github.com/jevprado) |
| `2.0`  | 20/06/2025 | Adicionando hyperlinks que faltaram | [José Eduardo](https://github.com/jevprado) | [João Pedro](https://github.com/JpRodrigues2)  |


