# Léxicos

## Introdução

Léxicos são conjuntos de termos específicos usados em uma área particular, para descrever conceitos. Eles incluem vocabulário técnico e especializado que é essencial para a comunicação eficaz dentro desses contextos específicos, estabelecendo uma linguagem compartilhada entre os profissionais e membros da comunidade. O léxico é uma forma controlada e organizada de definir todos os termos do domínio que o software precisa tratar. Ele é muito útil para documentar requisitos de forma clara e consistente.

## Metodologia

Para criar os léxicos, empregamos a metodologia do **Léxico Ampliado da Linguagem (LAL)**. Os símbolos da Receita Federal foram identificados a partir do uso do aplicativo e dos requisitos elicitados na etapa anterior. Após identificados eles foram ordenados e descritos como: noção e impacto.

### Tabela 1 – Léxicos do tipo LAL

| Tipo do símbolo | Noção                                                                       | Impacto                                                                         |
| --------------- | --------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| **Sujeito**     | Quem é o sujeito                                                            | Ações que executa                                                               |
| **Verbo**       | Quem realiza, quando acontece e quais os procedimentos                      | Quais os reflexos das ações no ambiente e novos estados decorrentes             |
| **Objeto**      | Definir o objeto e identificar outros objetos com os quais ele se relaciona | Ações que podem ser aplicadas ao objeto                                         |
| **Estado**      | O que indica e ações que levaram a esse estado                              | Identificar outros estados que podem ocorrer a partir do estado que se descreve |

<font size="3"><p style="text-align:center">Fonte: SAYÃO e CARVALHO.</p></font>

### Tabela 2 – Exemplo de símbolo de um léxico do tipo LAL

| Tipo do Símbolo | Noção                                                         | Impactos                                                                                                     |
| --------------- | ------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| **Sujeito**     | Contribuinte que interage com o aplicativo da Receita Federal | Contribuinte consulta seu CPF, verifica pendências fiscais, gera DARF, declara IR e acompanha restituições |

<font size="3"><p style="text-align:center">Fonte: SAYÃO e CARVALHO.</p></font>


### Tabela 3 – Template Léxicos

| Léxico            | Descrição                            |
| ----------------- | ------------------------------------ |
| **Classificação** | Estado / Objeto / Verbo              |
| **Impacto**       | Descrição de ações e de seus efeitos |
| **Noção**         | Símbolo                              |
| **Sinônimos**     | Dicionário de palavras               |

<font size="3"><p style="text-align:center">Fonte: SAYÃO e CARVALHO.</p></font>

---

## Léxicos


### <a id="L01" href="#anchor_L01" style="color:inherit;">L01 – Consultar CPF</a>

O contribuinte consulta a situação cadastral do CPF pelo aplicativo da Receita Federal, relacionado ao seguinte requisito não implementado: Consultar o status do CPF (ativo ou não) - ([ADC11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) e [ST06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/))

| L01               | Descrição                                                                                                                 |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------- |
| **Classificação** | Verbo                                                                                                                     |
| **Impacto**       | O contribuinte acessa informações como status *Regular* ou *Pendente de Regularização*.                                   |
| **Noção**         | 1. O usuário acessa **Consultar CPF**.<br>2. O sistema retorna o status atual, pendências e orientações de regularização. |
| **Sinônimos**     | Verificar CPF; Consultar Situação Cadastral                                                                               |

---

### <a id="L02" href="#anchor_L02" style="color:inherit;">L02 – Gerar DARF</a>

Geração de Documento de Arrecadação de Receitas Federais (DARF) para pagamento de tributos. Relacionado ao seguinte requisitos: Consultar débitos pendentes (DARFs) - [ST04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/) e Geração de guias de pagamento - ([ADC10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) e [ST03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)) 

| L02               | Descrição                                                                                                                                     |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| **Classificação** | Verbo                                                                                                                                         |
| **Impacto**       | O contribuinte gera um DARF para pagar tributos devidos à Receita Federal.                                                                    |
| **Noção**         | 1. O usuário seleciona **Gerar DARF**.<br>2. Preenche código da receita, valor e vencimento.<br>3. O sistema gera o documento para pagamento. |
| **Sinônimos**     | Emitir DARF; Criar Guia de Pagamento                                                                                                          |

---

### <a id="L03" href="#anchor_L03" style="color:inherit;">L03 – Declarar Imposto de Renda</a>

Permite o envio da declaração anual do Imposto de Renda Pessoa Física (IRPF). Relacionado ao seguintes requisitos: Declaração simplificada do IR - [ADC4](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) e O aplicativo deve permitir o envio da declaração do Imposto de Renda diretamente pelo app - [INT3](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)

| L03               | Descrição                                                                                                                        |
| ----------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Classificação** | Verbo                                                                                                                            |
| **Impacto**       | O contribuinte envia a declaração de IR e acompanha o processamento.                                                             |
| **Noção**         | 1. O usuário acessa **Declarar IR**.<br>2. Preenche ou importa informações fiscais.<br>3. O sistema valida e envia a declaração. |
| **Sinônimos**     | Entregar IR; Submeter Declaração de IRPF                                                                                         |

---

### <a id="L04" href="#anchor_L04" style="color:inherit;">L04 – Visualizar Restituição</a>

Permite consultar a situação da restituição do IRPF. Relacionado ao seguinte requisito: Acompanhamento de status da restituição (precisão quanto aos lotes) - [ADC3](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) e [ST02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)

| L04               | Descrição                                                                                                                     |
| ----------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **Classificação** | Verbo                                                                                                                         |
| **Impacto**       | O contribuinte verifica se tem direito à restituição e acompanha o lote de pagamento.                                         |
| **Noção**         | 1. O usuário acessa **Consultar Restituição**.<br>2. O sistema informa o status (*Em Processamento*, *Liberado*, *Pendente*). |
| **Sinônimos**     | Consultar Restituição; Ver Restituição do IR                                                                                  |

---

### <a id="L05" href="#anchor_L05" style="color:inherit;">L05 – Atualizar Cadastro</a>

Atualização de dados cadastrais do contribuinte (endereço, telefone, e‑mail). Relacionado ao seguinte requisito: Alteração de dados via app - [ADC7](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) e [ST02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)

| L05               | Descrição                                                                                                                    |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **Classificação** | Verbo                                                                                                                        |
| **Impacto**       | Garante que as informações cadastrais estejam corretas, evitando pendências fiscais.                                         |
| **Noção**         | 1. O usuário acessa **Atualizar Cadastro**.<br>2. Edita os campos desejados.<br>3. O sistema salva e confirma a atualização. |
| **Sinônimos**     | Alterar Dados; Atualizar Informações Pessoais                                                                                |

---

### <a id="L06" href="#anchor_L06" style="color:inherit;">L06 – Emitir Comprovante de Rendimentos</a>

Gera o comprovante de rendimentos fornecido por fonte pagadora para fins de declaração.

| L06               | Descrição                                                                                                           |
| ----------------- | ------------------------------------------------------------------------------------------------------------------- |
| **Classificação** | Verbo                                                                                                               |
| **Impacto**       | Facilita o preenchimento da declaração e comprovação de renda.                                                      |
| **Noção**         | 1. O usuário seleciona **Emitir Comprovante**.<br>2. Escolhe o ano‑base.<br>3. O sistema gera o PDF do comprovante. |
| **Sinônimos**     | Obter Informe de Rendimentos; Gerar Comprovante                                                                     |

---

### <a id="L07" href="#anchor_L07" style="color:inherit;">L07 – Acompanhar Processamento</a>

Permite acompanhar o processamento da declaração de IRPF. Relacionado ao seguinte requisito: Acessar informações detalhadas a cerca da declaração de imposto de renda de um ano especifico - [INT1](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)

| L07               | Descrição                                                                                                                             |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| **Classificação** | Verbo                                                                                                                                 |
| **Impacto**       | Informa ao contribuinte eventuais inconsistências ou retenções na malha fina.                                                         |
| **Noção**         | 1. O usuário acessa **Acompanhar Declaração**.<br>2. O sistema exibe status (*Em Processamento*, *Em Fila de Restituição*, *Retida*). |
| **Sinônimos**     | Verificar Processamento; Acompanhar Declaração                                                                                        |

---

### <a id="L08" href="#anchor_L08" style="color:inherit;">L08 – Pagar Dívida Ativa</a>

Permite gerar guia para quitação de valores inscritos em Dívida Ativa da União. Relacionado ao seguinte requisitos:Emissão de certidão negativa via aplicativo - [INT6](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)
 e Geração de guias de pagamento - ([ADC10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) e [ST03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)) 

| L08               | Descrição                                                                                                              |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------- |
| **Classificação** | Verbo                                                                                                                  |
| **Impacto**       | Regulariza débitos, evitando acréscimos de encargos legais.                                                            |
| **Noção**         | 1. O usuário acessa **Pagar Dívida Ativa**.<br>2. Visualiza débitos.<br>3. Gera guia de pagamento ou parcela a dívida. |
| **Sinônimos**     | Quitar Dívida; Regularizar Débito                                                                                      |


### <a id="L09" href="#anchor_L09" style="color:inherit;">L09 – Contribuinte</a>

| Contribuinte      | Descrição                                                                                                               |
| ----------------- | ----------------------------------------------------------------------------------------------------------------------- |
| **Classificação** | Sujeito                                                                                                                 |
| **Impacto**       | Pessoa física ou jurídica que possui obrigações fiscais junto à Receita Federal e utiliza o aplicativo para cumpri‑las. |
| **Noção**         | Realiza consultas, declarações, pagamentos e atualizações cadastrais.                                                   |
| **Sinônimos**     | Usuário; Pessoa Física; Pessoa Jurídica                                                                                 |
---


## Relacionamento dos Léxicos

### Tabela 4 – Tabela de Relacionamento dos Léxicos

| Léxico                                                                    | Relaciona‑se com                                                                                                           | Descrição do Relacionamento                                              |
| ------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| <a id="anchor_L01" href="#L01">L01</a>: Consultar CPF                     | <a id="anchor_L09" href="#L09">L09</a>: Contribuinte                                                                       | O contribuinte verifica a situação cadastral do CPF.                     |
| <a id="anchor_L02" href="#L02">L02</a>: Gerar DARF                        | <a id="anchor_L09" href="#L09">L09</a>: Contribuinte                                                                       | O contribuinte gera DARFs para pagar tributos.                           |
| <a id="anchor_L03" href="#L03">L03</a>: Declarar Imposto de Renda         | <a id="anchor_L09" href="#L09">L09</a>: Contribuinte                                                                       | O contribuinte submete a declaração anual de IRPF.                       |
| <a id="anchor_L04" href="#L04">L04</a>: Visualizar Restituição            | <a id="anchor_L03" href="#L03">L03</a>: Declarar Imposto de Renda;<br><a id="anchor_L09" href="#L09">L09</a>: Contribuinte | A restituição decorre do processamento da declaração de IRPF.            |
| <a id="anchor_L05" href="#L05">L05</a>: Atualizar Cadastro                | <a id="anchor_L09" href="#L09">L09</a>: Contribuinte                                                                       | O contribuinte mantém seus dados atualizados para evitar pendências.     |
| <a id="anchor_L06" href="#L06">L06</a>: Emitir Comprovante de Rendimentos | <a id="anchor_L03" href="#L03">L03</a>: Declarar Imposto de Renda                                                          | O comprovante é documento usado para preencher a declaração de IRPF.     |
| <a id="anchor_L07" href="#L07">L07</a>: Acompanhar Processamento          | <a id="anchor_L03" href="#L03">L03</a>: Declarar Imposto de Renda                                                          | Permite acompanhar o status da declaração enviada.                       |
| <a id="anchor_L08" href="#L08">L08</a>: Pagar Dívida Ativa                | <a id="anchor_L09" href="#L09">L09</a>: Contribuinte                                                                       | O contribuinte quita débitos inscritos em dívida ativa.                  |
| <a id="anchor_L09" href="#L09">L09</a>: Contribuinte                      | Todos os léxicos de ação (L01–L08)                                                                                         | O contribuinte é o agente central que executa todas as ações no sistema. |

---

## Referências Bibliográficas

> SERRANO, Milene. **Requisitos – Aula 10**. 2017. Apresentação de slides. Acesso em: 08 mai. 2025.

> SAYÃO, Miriam; CARVALHO, Gustavo. *Construção do léxico de aplicações*. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: [http://www-di.inf.puc-rio.br/\~julio/bnncap3.pdf](http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf). Acesso em: 08 mai. 2025.

---

## Histórico de Versões

| Versão | Data       | Descrição                                  | Autor                                     | Revisor                                     |
| ------ | ---------- | ------------------------------------------ | ----------------------------------------- | ------------------------------------------- |
| `1.0`  | 10/05/2025 | Criação dos léxicos do App Receita Federal | [Thales Germano](https://github.com/thalesgvl), [Marco Marques](https://github.com/marcomarquesdc) | [Diassis](https://github.com/Diaxiz) |
| `1.1`  | 08/06/2025 | Ajuste nos léxicos | [Jose Eduardo](https://github.com/jevprado) | [Diassis](https://github.com/Diaxiz) |

