
# Documento de Casos de Uso do Aplicativo da Receita Federal do Brasil

## Introdução

Caso de uso é uma modelagem descritiva de sequência de interações entre atores e um sistema específico que resulta em um resultado que permite compreensões necessárias ao desenvolvimento de uma atividade. No nosso trabalho, o sistema é o da Receita Federal do Brasil, e estabelecemos relações entre o ator primário (contribuintes) e o secundário (servidor do órgão).

O documento apresenta os diagramas de casos de uso do aplicativo da Receita Federal do Brasil (RFB). O aplicativo é uma ferramenta digital cujo propósito é facilitar o acesso dos cidadãos a serviços fiscais, como consulta à situação cadastral, acompanhamento de restituições e entrega de declarações.

Este documento foca em funcionalidades típicas para o cidadão usuário do app. A modelagem descrita visa mapear as interações entre os usuários e o sistema, bem como os requisitos já implementados e os previstos.


## Tabela de atividades feitas - por membro

<p style="text-align: center"><b>Tabela 1</b> - Tabela de atividades feitas - por membro </p>

|Nome                                               | Atividade entregue                        | 
| ------------------------------------------------- | ----------------------------------------- | 
| [Andre Lopes](https://github.com/andrewslopes)    | Criação da documentação geral do artefato                                            | 
| [Julia Massuda](https://github.com/JuliaReis18)   | Criação do diagrama de usos, descrições do diagrama <br> Cartões de casos de uso  (UC09 e UC10) | 
| [Jose Eduardo](https://github.com/jevprado)       | Revisor dos artefatos <br> Cartões de casos de uso (UC 01 e UC02) |
| [João Pedro](https://github.com/JpRodrigues2)     | Cartões de casos de uso  (UC07 e UC08) |
| [Diassis](https://github.com/Diaxiz)     | Cartões de casos de uso  (UC11 e UC12) |


<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo   ](https://github.com/jevprado), 2025.</p></font>


## Metodologia Utilizada

A metodologia adotada para a confecção dos diagramas seguiu os princípios da UML (Unified Modeling Language). A equipe utilizou o quadro de modelo de negócios Canvas para alinhar objetivos, atores envolvidos e funcionalidades do sistema.

A validação parcial foi realizada com base em funcionalidades reais do aplicativo e dados públicos disponíveis no site da Receita Federal. A metodologia adotada assegura que os casos de uso identifiquem de modo claro e fiel a atuação do sistema.

## Descrição do Diagrama de Caso de Uso

O diagrama de casos de uso é uma representação gráfica das funcionalidades do aplicativo sob a ótica dos usuários. Ele identifica quais ações estão disponíveis para cada ator (pessoas, sistemas externos ou dispositivos que possam interagir com o sistema em estudo), representando a relação entre os serviços oferecidos e os perfis que interagem com o sistema.

Esse diagrama é fundamental para comunicar os requisitos funcionais a desenvolvedores, analistas e demais interessados no projeto. Como componentes do diagrama, utilizou-se ícones (bonecos-palito) para representar os atores. Para o sistema, a representação se deu por meio de um retângulo delimitador do cenário. Para os casos de uso, utilizamos verbos no infinitivo em uma elipse horizontal.

Os relacionamentos foram representados por semirretas características, caso se tratasse de associação, inclusão (include), extensão (extend) ou generalização.

### Tabela 1: Elementos do Diagrama de Casos de Uso

<p style="text-align: center"><b>Tabela 2</b> - Tabela de Elementos do Diagrama de Casos de Uso </p>

| Nome do Elemento | Imagem | Função |
|---|---|---|
| **Ator** | ![Boneco Palito](../assets/ChatGPT%20Image%205_06_2025,%2008_51_23.png) | Representa os diferentes tipos de usuários externos que interagem com o sistema. |
| **Elipse (Caso de Uso)** | ![Elipse](https://cdn-icons-png.flaticon.com/512/1014/1014918.png) | Representa uma funcionalidade ou uma ação específica que o sistema pode realizar. A elipse contém o nome do caso de uso. |
| **Retângulo (Sistema)** | ![Retângulo](https://images.vexels.com/media/users/3/139257/isolated/svg/b8fa8f291632f8fe68842e4fb100d8e0.svg) | Representa o sistema ou o bloco em análise. Ele envolve os casos de uso e atores relacionados. |
| **Flecha (Relações)** | ![Flecha](../assets/Captura%20de%20tela%202025-06-08%20173528.png) | Representa as relações ou interações entre atores e casos de uso. |


<font size="3"><p style="text-align: center">Fonte: [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>


## Atores

### Ator Primário: Contribuinte 

Usuário principal do aplicativo. Suas ações incluem:

- Consultar situação fiscal
- Enviar declaração de IRPF
- Consultar e acompanhar restituições
- Emitir e pagar guias de pagamento (DARF)
- Atualizar dados cadastrais
- Receber notificações da Receita
- Emitir certidões
- Acessar vídeos e notícias institucionais

### Ator Secundário: Auditor da Receita 

Usuário institucional, com acesso ao sistema para:

- Atualizar base de dados
- Validar informações declaradas
- Enviar notificações automatizadas
- Integrar sistemas internos da RFB ao app

## Descrição Geral dos Diagramas Realizados

- O contribuinte interage com o sistema para realizar todos os casos de uso.
- O servidor da Receita Federal valida e processa os dados.

### Diagrama de Casos de Uso: Requisitos Implementados

![Diagrama de Casos de Uso](../assets/Diagrama%20de%20Casos%20de%20Uso.jpg)  
Fonte: [Julia Massuda](https://github.com/JuliaReis18)


## CASO DE USO 01 - (UC01)

<p style="text-align: center"><b>Tabela 3</b> - CASO DE USO 01 - (UC01) </p>

| **COLUNA**               | **DESCRIÇÃO**                                                                                         |
|--------------------------|-------------------------------------------------------------------------------------------------------|
| **Nome do caso de uso:** | Consultar Status da Restituição do IRPF                                                              |
| **Rastreabilidade:**     | [ADC3](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) e [ST02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)                           |
| **Pré-condição:**         | - App instalado em dispositivo compatível  <br> - Autenticação via CPF e senha Gov.br <br> - Sistema da Receita operacional e sincronizado |
| **Ator principal:**       | Contribuinte                                                                                        |
| **Atores secundários:**   | Auditor da Receita                                                                                   |
| **Objetivo:**             | Permitir que o contribuinte consulte o status da restituição com informações sobre lote, valor e data prevista |
| **Fluxo principal:**      | 1. Acessa o app da Receita <br> 2. Seleciona “Consultar restituição do IR” <br> 3. Sistema valida conexão com internet (PI1) <br> 4. Valida CPF/autenticação (PI2) <br> 5. Consulta banco de dados <br> 6. Exibe status com: lote, situação, valor, data <br> 7. Permite visualizar/baixar comprovante (PE1) <br> 8. Registra no histórico |
| **Fluxo alternativo:**    | 6a. Se há múltiplas restituições, exibe lista por ano <br> 6b. Usuário seleciona o ano desejado     |
| **Fluxo de exceção:**     | - E1: Sem internet → mostra erro e sugere reconectar (PI1) <br> - E2: CPF inválido → volta para login (PI2) <br> - E3: Nenhum dado encontrado → informa ausência de restituições <br> - E4: Sistema instável → mostra mensagem de indisponibilidade |
| **Pós-condição:**         | - Status da restituição exibido <br> - Informações podem ser salvas ou compartilhadas <br> - Histórico atualizado <br> - Pode haver redirecionamento para vídeos explicativos (PE2) |

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo   ](https://github.com/jevprado), 2025.</p></font>


## CASO DE USO 02 - (UC02)

<p style="text-align: center"><b>Tabela 4</b> - Tabela CASO DE USO 02 - (UC02) </p>

| **COLUNA**               | **DESCRIÇÃO**                                                                                         |
|--------------------------|-------------------------------------------------------------------------------------------------------|
| **Nome do caso de uso:** | Agendar Atendimento Presencial                                                                       |
| **Rastreabilidade:**     | [INT3](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)       |
| **Pré-condição:**         | - Aplicativo instalado em dispositivo compatível <br> - Contribuinte autenticado via CPF e senha Gov.br <br> - Sistema da Receita sincronizado com agenda das unidades |
| **Ator principal:**       | Contribuinte                                                                                        |
| **Atores secundários:**   | Servidor da Receita (responsável por configurar e disponibilizar horários e unidades de atendimento) |
| **Objetivo:**             | Permitir ao contribuinte agendar atendimentos presenciais diretamente pelo aplicativo, escolhendo unidade, data e horário |
| **Fluxo principal:**      | 1. Contribuinte acessa o app da Receita <br> 2. Seleciona a opção "Agendar Atendimento" <br> 3. Sistema valida conexão com a internet (PI1) <br> 4. Valida autenticação do usuário (PI2) <br> 5. Sistema exibe unidades disponíveis e horários <br> 6. Contribuinte seleciona unidade, serviço, data e horário <br> 7. Confirma agendamento <br> 8. Sistema registra o agendamento e envia notificação de confirmação |
| **Fluxo alternativo:**    | 5a. Se o serviço desejado não estiver disponível na unidade escolhida, sistema exibe unidades alternativas <br> 6a. Contribuinte pode alterar data/horário sugerido pelo sistema |
| **Fluxo de exceção:**     | - E1: Falha de conexão → exibe mensagem e orienta reconexão (PI1) <br> - E2: Falha na autenticação → redireciona para login (PI2) <br> - E3: Nenhum horário disponível → sistema exibe mensagem e sugere outras datas ou unidades <br> - E4: Instabilidade no sistema → informa indisponibilidade e recomenda tentar mais tarde |
| **Pós-condição:**         | - Agendamento registrado com sucesso <br> - Contribuinte recebe notificação e pode consultar, cancelar ou remarcar atendimento <br> - Histórico de agendamentos atualizado |

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo   ](https://github.com/jevprado), 2025.</p></font>

## CASO DE USO 07 - (UC07)

<p style="text-align: center"><b>Tabela 7</b> - CASO DE USO 07 - (UC07)</p>

| COLUNA                   | DESCRIÇÃO                                                                                           |
|--------------------------|-----------------------------------------------------------------------------------------------------|
| Nome do caso de uso:     | Consultar Status do CPF                                                                             |
| Rastreabilidade:         | [ST06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/) e [ADC11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) |
| Pré-condição:            | - App instalado em dispositivo compatível  <br> - Autenticação via CPF e senha Gov.br <br> - Sistema da Receita sincronizado com base de dados do CPF |
| Ator principal:          | Contribuinte                                                                                        |
| Atores secundários:      | Servidor da Receita                                                                                 |
| Objetivo:                | Permitir ao contribuinte verificar o status de seu CPF (ativo, pendente ou suspenso)               |
| Fluxo principal:         | 1. Usuário acessa o app <br> 2. Seleciona “Consultar status do CPF” <br> 3. Sistema valida internet (PI1) <br> 4. Valida autenticação (PI2) <br> 5. Sistema consulta base de dados <br> 6. Exibe status do CPF (ativo, suspenso, cancelado) <br> 7. Exibe possíveis instruções para regularização, se aplicável |
| Fluxo alternativo:       | 6a. Se CPF estiver pendente, permite acesso a vídeos e informações sobre regularização (PE2)        |
| Fluxo de exceção:        | - E1: Sem internet → sugere reconectar (PI1) <br> - E2: Erro na autenticação → volta ao login (PI2) <br> - E3: Dados não encontrados → exibe mensagem e instruções para contato |
| Pós-condição:            | - Status do CPF exibido <br> - Histórico de consulta atualizado <br> - Pode haver redirecionamento para regularização online |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>

---

## CASO DE USO 08 - (UC08)

<p style="text-align: center"><b>Tabela 8</b> - CASO DE USO 08 - (UC08)</p>

| COLUNA                   | DESCRIÇÃO                                                                                           |
|--------------------------|-----------------------------------------------------------------------------------------------------|
| Nome do caso de uso:     | Emitir Comprovante de CPF                                                                           |
| Rastreabilidade:         | [ST07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/) e [ADC2](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) |
| Pré-condição:            | - App instalado em dispositivo compatível  <br> - Autenticação via CPF e senha Gov.br <br> - Status do CPF consultado previamente |
| Ator principal:          | Contribuinte                                                                                        |
| Atores secundários:      | Servidor da Receita                                                                                 |
| Objetivo:                | Permitir ao usuário emitir, baixar e compartilhar o comprovante oficial de inscrição no CPF        |
| Fluxo principal:         | 1. Acessa o app da Receita <br> 2. Seleciona “Emitir Comprovante de CPF” <br> 3. Sistema valida internet (PI1) <br> 4. Valida autenticação (PI2) <br> 5. Consulta base de dados <br> 6. Gera comprovante em PDF <br> 7. Exibe opção para salvar ou compartilhar (PE1) |
| Fluxo alternativo:       | 6a. Permite escolher entre comprovante resumido ou completo                                         |
| Fluxo de exceção:        | - E1: Falha de conexão → mostra erro (PI1) <br> - E2: CPF não encontrado ou inválido → exibe aviso <br> - E3: Erro ao gerar PDF → orienta tentativa posterior |
| Pós-condição:            | - Comprovante gerado com sucesso <br> - Pode ser salvo ou enviado <br> - Histórico atualizado com registro da emissão |

<font size="3"><p style="text-align: center">Fonte: [João Pedro](https://github.com/JpRodrigues2), 2025.</p></font>



## CASO DE USO 09 - (UC09)

<p style="text-align: center"><b>Tabela 5</b> - CASO DE USO 09 - (UC09) </p>

| **COLUNA**               | **DESCRIÇÃO**                                                                                         |
|--------------------------|-------------------------------------------------------------------------------------------------------|
| **Nome do caso de uso:** | Consultar Situação Fiscal                                                                            |
| **Rastreabilidade:**     | [ST04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/) e [ADC5](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) |
| **Pré-condição:**         | - App instalado em dispositivo compatível  <br> - Autenticação via CPF e senha Gov.br <br> - Sistema da Receita operacional e sincronizado |
| **Ator principal:**       | Contribuinte                                                                                        |
| **Atores secundários:**   | Auditor da Receita                                                                                   |
| **Objetivo:**             | Permitir ao contribuinte consultar sua situação fiscal, visualizando pendências, débitos e extratos detalhados |
| **Fluxo principal:**      | 1. Acessa o app da Receita <br> 2. Seleciona “Consultar Situação Fiscal” <br> 3. Sistema valida conexão com internet (PI1) <br> 4. Valida autenticação (PI2) <br> 5. Consulta banco de dados <br> 6. Exibe pendências, débitos e extratos detalhados <br> 7. Permite download do relatório <br> 8. Registra consulta no histórico (PE3) |
| **Fluxo alternativo:**    | 6a. Se há múltiplas pendências, exibe lista com filtros por tipo e ano <br> 7a. Permite compartilhar relatório via e-mail/WhatsApp (PE1) |
| **Fluxo de exceção:**     | - E1: Sem internet → mostra erro e sugere reconectar (PI1) <br> - E2: Falha na autenticação → volta para login (PI2) <br> - E3: Nenhum dado encontrado → exibe mensagem “Situação fiscal regular” <br> - E4: Sistema instável → mostra mensagem de indisponibilidade |
| **Pós-condição:**         | - Situação fiscal exibida <br> - Relatório salvo ou compartilhado (se solicitado) <br> - Histórico atualizado |

<font size="3"><p style="text-align: center">Fonte:  [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>

---

## CASO DE USO 10 - (UC10)

<p style="text-align: center"><b>Tabela 6</b> - CASO DE USO 10 - (UC10) </p>

| **COLUNA**               | **DESCRIÇÃO**                                                                                         |
|--------------------------|-------------------------------------------------------------------------------------------------------|
| **Nome do caso de uso:** | Atualizar Dados Cadastrais                                                                           |
| **Rastreabilidade:**     | [ADC7](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) |
| **Pré-condição:**         | - App instalado em dispositivo compatível  <br> - Autenticação via CPF e senha Gov.br <br> - Sistema da Receita operacional e sincronizado |
| **Ator principal:**       | Contribuinte                                                                                        |
| **Atores secundários:**   | Servidor da Receita                                                                                  |
| **Objetivo:**             | Permitir ao contribuinte atualizar dados como endereço, contatos e dados bancários com validação de segurança |
| **Fluxo principal:**      | 1. Acessa o app da Receita <br> 2. Seleciona “Atualizar Dados Cadastrais” <br> 3. Sistema valida conexão com internet (PI1) <br> 4. Valida autenticação (PI2) <br> 5. Exibe dados atuais <br> 6. Contribuinte edita campos desejados <br> 7. Sistema valida alterações <br> 8. Contribuinte confirma atualização <br> 9. Sistema registra atualização e envia confirmação por e-mail/SMS |
| **Fluxo alternativo:**    | 6a. Contribuinte corrige campo com erro após aviso do sistema <br> 9a. Permite salvar comprovante da atualização |
| **Fluxo de exceção:**     | - E1: Sem internet → mostra erro e sugere reconectar (PI1) <br> - E2: Falha na autenticação → volta para login (PI2) <br> - E3: Dados inválidos → exibe erro e orienta correção <br> - E4: Sistema instável → mostra mensagem de indisponibilidade |
| **Pós-condição:**         | - Dados atualizados e salvos <br> - Confirmação enviada ao contribuinte <br> - Histórico de alterações atualizado |

<font size="3"><p style="text-align: center">Fonte:  [Julia Massuda](https://github.com/JuliaReis18), 2025.</p></font>

## CASO DE USO 11 - (UC11)

<p style="text-align: center"><b>Tabela 9</b> - CASO DE USO 11 - (UC11) </p>

| **COLUNA**               | **DESCRIÇÃO**                                                                                         |
|--------------------------|-------------------------------------------------------------------------------------------------------|
| **Nome do caso de uso:** | Visualizar Histórico de Declarações e Restituições Anteriores                                        |
| **Rastreabilidade:**     | [ST09](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/#storytelling-por-persona), [ADC8](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) |
| **Pré-condição:**         | - App instalado <br> - Login autenticado com conta Gov.br <br> - Declarações anteriores enviadas     |
| **Ator principal:**       | Contribuinte                                                                                         |
| **Atores secundários:**   | Servidor da Receita                                                                                  |
| **Objetivo:**             | Permitir que o contribuinte acesse e visualize o histórico de envio de declarações e respectivas restituições dos anos anteriores |
| **Fluxo principal:**      | 1. Nuno acessa o app <br> 2. Vai até a seção “Histórico de Declarações” <br> 3. Sistema valida login e busca os registros <br> 4. Exibe uma lista com os anos e status <br> 5. Nuno seleciona um ano <br> 6. Visualiza dados enviados e situação da restituição <br> 7. Pode baixar recibos ou relatórios |
| **Fluxo alternativo:**    | 4a. Permite filtrar por status da restituição (aguardando, paga, em análise) ou tipo de declaração   |
| **Fluxo de exceção:**     | - E1: Nenhuma declaração encontrada → exibe aviso e sugere preenchimento <br> - E2: Falha na autenticação → retorna ao login <br> - E3: Erro na consulta ao banco de dados → mostra mensagem de instabilidade |
| **Pós-condição:**         | - Histórico visualizado com sucesso <br> - Relatórios podem ser baixados ou compartilhados           |


<font size="3"><p style="text-align: center">Fonte:  [Diassis](https://github.com/Diaxiz), 2025.</p></font>

## CASO DE USO 12 - (UC12)

<p style="text-align: center"><b>Tabela 10</b> - CASO DE USO 12 - (UC12) </p>

| **COLUNA**               | **DESCRIÇÃO**                                                                                         |
|--------------------------|-------------------------------------------------------------------------------------------------------|
| **Nome do caso de uso:** | Acesso simultâneo a múltiplos CPFs/CNPJs                                                              |
| **Rastreabilidade:**     | [ST01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/#storytelling-por-persona), [ADC1](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) |
| **Pré-condição:**         | - App instalado <br> - Autenticação via Gov.br com permissão de contador(a) <br> - Clientes vinculados previamente |
| **Ator principal:**       | Contribuinte (Contadora)                                                                              |
| **Atores secundários:**   | Clientes da contadora                                                                                 |
| **Objetivo:**             | Permitir que profissionais da contabilidade acessem diversos CPFs/CNPJs sob sua responsabilidade com facilidade |
| **Fluxo principal:**      | 1. Fernanda acessa o app <br> 2. Navega até “Área do Contador” <br> 3. Visualiza lista de clientes vinculados <br> 4. Seleciona um CPF/CNPJ <br> 5. Acessa declarações, pendências e status <br> 6. Alterna entre clientes sem precisar sair do app |
| **Fluxo alternativo:**    | 3a. Se cliente ainda não estiver vinculado, app exibe botão para solicitar permissão e envio de token de autorização |
| **Fluxo de exceção:**     | - E1: Acesso não autorizado → app orienta envio de convite ao cliente <br> - E2: Erro ao buscar dados → exibe mensagem de instabilidade <br> - E3: Nenhum cliente vinculado → mostra instruções para adicionar |
| **Pós-condição:**         | - Acesso completo aos dados de cada cliente <br> - Histórico de acessos por CPF atualizado           |

<font size="3"><p style="text-align: center">Fonte:  [Diassis](https://github.com/Diaxiz), 2025.</p></font>



## Pré-condições

Situações que devem ser atendidas antes que um caso de uso possa ser executado:
- O aplicativo da Receita deve estar instalado em um dispositivo compatível.
- O contribuinte deve possuir acesso à internet e autenticação por CPF e senha Gov.br.
- O sistema da Receita deve estar operacional para sincronização com o banco de dados.

## Pós-condições

Situações que descrevem o que se altera ou permanece após a execução dos casos de uso:
- Consulta ou serviço solicitado é realizado com sucesso.
- O status do CPF é atualizado ou exibido.
- Declarações e comprovantes são enviados ou baixados.
- O usuário recebe notificação da conclusão do processo.

## Relacionamentos

Identificam as interações entre os atores e os casos de uso, podendo ser:
- **Associação**: Entre o contribuinte e os casos de uso (ex: "Emitir DARF").
- **Inclusão (`<<include>>`)**: Validação de conexão com a internet incluída em vários casos.
- **Extensão (`<<extend>>`)**: Compartilhamento de comprovantes ou acesso a vídeos explicativos.

### Pontos de Extensão

- **PE1**: Compartilhar comprovante de declaração via e-mail/WhatsApp
- **PE2**: Acessar vídeos sobre como interpretar pendências
- **PE3**: Acompanhar histórico de declarações anteriores

### Pontos de Inclusão

- **PI1**: Validar conexão com internet
- **PI2**: Validar CPF com o sistema da Receita
- **PI3**: Exibir status da declaração após envio

## Compreensão do Diagrama

### Sistema
- O sistema é representado por um retângulo?
- O sistema tem título no topo?
- Todas as funcionalidades estão dentro do retângulo?
- Tudo fora do retângulo ocorre fora do app?

### Atores
- O ator contribuinte interage com o app?
- O ator servidor interage com o app?
- O ator primário está à esquerda?
- O ator secundário está à direita?

### Casos de Uso

#### Autenticação

##### Realizar Login
- Login com CPF
- Login com certificado digital
- Login com conta Gov.br
- Segurança adequada aos serviços
- Bloqueio após tentativas inválidas
- Armazenamento seguro de credenciais

##### Recuperar Senha
- Recuperação por e-mail
- Recuperação por SMS
- Validação de dados pessoais
- Link de recuperação com expiração

##### Validar Acesso via Gov.br
- Integração com Gov.br
- Reconhecimento de níveis de autenticação
- Redirecionamento pós-login
- Transmissão segura de dados

#### Consultas Gerais

##### Consultar Situação Fiscal
- Exibição de pendências
- Visualização de extrato
- Detalhamento de débitos
- Status em tempo real
- Download de relatório

##### Atualizar Dados Cadastrais
- Alterar endereço
- Alterar contatos (e-mail/telefone)
- Alterar dados bancários
- Confirmação por e-mail/SMS
- Proteção contra alterações indevidas

##### Consultar Processos
- Lista de processos
- Detalhes do processo
- Notificações de atualizações
- Histórico de movimentações
- Download de documentos

#### Agendar Atendimento
- Disponibilidade de datas/horários
- Escolha de unidades
- Confirmação de agendamento
- Cancelamento e remarcação
- Lembretes automáticos


####  Pagar Tributos
* Lista de tributos pendentes 
* Integração com bancos 
* Histórico de pagamentos 
* Parcelamento de débitos 
* Emissão de comprovante 

####  Declaração de Imposto de Renda
##### Preencher Declaração
* Importar dados do ano anterior 
* Dados pré-preenchidos 
* Importar fontes pagadoras 
* Bens e direitos 
* Dependentes 
* Cálculo de deduções 
* Verificação de inconsistências 

##### 9.3.5.2 Enviar Declaração
* Transmissão segura 
* Recebimento de protocolo 
* Confirmação pela Receita 
* Status de processamento 
* Desempenho de envio 

##### Consultar Recibo
* Visualizar recibo 
* Baixar em PDF 
* Compartilhar recibo 
* Histórico de recibos 

#### Restituição de IR
##### Consultar Lotes
* Cronograma de lotes 
* Consulta por CPF 
* Valor e data do pagamento 
* Status de análise 
* Notificações de liberação 

##### Atualizar Dados Bancários
* Alterar conta para crédito 
* Validação de dados bancários 
* Confirmação da alteração 
* Histórico de alterações 

##### Emitir Comprovante
* Geração de comprovante 
* Baixar PDF 
* Validação fiscal 
* Compartilhamento 
* Histórico de comprovantes 

#### Segurança
* Proteção de dados locais 
* Autenticação biométrica 
* Conformidade com LGPD 

#### Usabilidade
* Acessibilidade 
* Compatibilidade com telas 
* Clareza das instruções 
* Navegação intuitiva 
* Ajuda contextual 
* Busca no app 

### RELACIONAMENTO
* Atores interagem com os casos de uso? 
* Existe associação entre atores e funcionalidades? 
* Existe inclusão (<<include>>)? 
* Existe extensão (<<extend>>)? 
* Existe generalização? (não aplicável neste caso) 

## Vídeos de validação 

### Validação do Caso de Uso 01 - (UC01) e Caso de Uso 02 - (UC02)

<p style="text-align: center"><b>Vídeo 1</b> - Validação do Caso de Uso 01 - (UC01) e Caso de Uso 02 - (UC02)</p>

<iframe width="700" height="400"
        src="https://www.youtube.com/embed/xZkePEceRRQ"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin"
        allowfullscreen>
</iframe>

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>



## Referências

* DEVMEDIA. O que é UML e diagramas de caso de uso – Introdução prática à UML. Disponível em: https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408. Acesso em: 08 jun. 2025. 
* Receita Federal do Brasil. Aplicativo Pessoa Física. Disponível em: https://www.gov.br/receitafederal. Acesso em: 08 jun. 2025 
* SOMMERVILLE, Ian. Engenharia de Software. 10. ed. São Paulo: Pearson, 2011. 
* PINTO, Gabriel. Modelagem de Casos de Uso. Brasília, 2025.



## Histórico de versões

Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
`1.0`| 11/05/2025 | Criação do documento Casos de uso | [Julia Massuda](https://github.com/JuliaReis18) e  [Andre Lopes](https://github.com/andrewslopes)  | [Jose Eduardo](https://github.com/jevprado) |
`2.0` | 08/06/2025 | Alterações no conteúdo + adicionando novo diagrama e tabela de casos de uso | [Julia Massuda](https://github.com/JuliaReis18) e  [Andre Lopes](https://github.com/andrewslopes)  | [Jose Eduardo](https://github.com/jevprado) |
 `2.1`  | 12/06/2025 | Adição da tabela de atividade dos membros | [Jose Eduardo](https://github.com/jevprado) | [Diassis](https://github.com/Diaxiz) |
 `2.2`  | 21/06/2025 | Adição dos UC01 E UC02 | [Jose Eduardo](https://github.com/jevprado) | [Julia Massuda](https://github.com/JuliaReis18)|
 `2.3`  | 22/06/2025 | Adição dos UC09 E UC10 | [Julia Massuda](https://github.com/JuliaReis18)| [Jose Eduardo](https://github.com/jevprado)|
 `2.4`  | 22/06/2025 | Adição dos UC07 E UC08 | [João Pedro](https://github.com/JpRodrigues2)|[Julia Massuda](https://github.com/JuliaReis18)|
 `2.5`  | 30/06/2025 | Adicionando a validação do UC01 e UC02 | [Jose Eduardo](https://github.com/jevprado)| [Diassis](https://github.com/Diaxiz)|
 `2.6`  | 30/06/2025 | Criação de UC11 E UC12 | [Diassis](https://github.com/Diaxiz) | [Jose Eduardo](https://github.com/jevprado) |
