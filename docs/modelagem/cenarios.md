# Cenários 

## Introdução 
<p align="justify">
Os cenários de uso são descrições narrativas que representam situações reais nas quais os usuários interagem com um sistema para atingir objetivos específicos. Na engenharia de requisitos, esses cenários são essenciais para compreender o contexto de uso das funcionalidades desejadas, explorando como os diferentes perfis de usuários interagem com o sistema em desenvolvimento.
<br> 
<br> 
Os cenários foram elaborados com base nas personas previamente criadas e nos requisitos identificados previamente do aplicativo da Receita Federal. Eles buscam capturar situações típicas e também exceções que o sistema deve lidar, servindo como ferramenta para validar e refinar os requisitos levantados.
</p>

## Tabela de atividades feitas - por membro

|Nome                                               | Atividade entregue                        | 
| ------------------------------------------------- | ----------------------------------------- | 
| [Jose Eduardo](https://github.com/jevprado)   | Criação dos cenários C01, C02, C03 e C04. Ajustes nos códigos do cenários.                                   | 
| [Diassis](https://github.com/Diaxiz)                 | Criação dos cenários C05, C06 e C07 e revisor das versões `1.1` e `1.2`         | 
| [Thales Germano](https://github.com/thalesgvl)       | Revisor da versão `1.0` |

## Meteodologia 
<p align="justify">
A construção dos cenários foi orientada pela técnica de engenharia de requisitos centrada no usuário, utilizando personas como ponto de partida. Os cenários foram estruturados com os seguintes elementos: <b>título</b>, <b>objetivo</b>, <b>contexto</b>, <b>atores</b>, <b>recursos</b>, <b>episódios</b>, <b>restrições</b> e <b>exceções</b>. Essa estrutura permite uma análise rica do uso do sistema, considerando tanto o comportamento ideal quanto as condições adversas que podem surgir.
<br> 
<br> 
Os requisitos utilizados como base para os cenários foram extraídos da tabela de requisitos previamente definida pelo grupo, incluindo tanto requisitos implementados quanto não implementados. A escolha dos requisitos visou cobrir funcionalidades diversas e relevantes, garantindo representatividade dos diferentes tipos de usuários do sistema.
</p>

## Cenários 

### Cenário 01 (C01)

<p style="text-align: center"><b>Tabela 1</b> - Cenário 01</p>

| Abstração | Descrição |
|----------|-----------|
| Título   | Cadastro de CPF totalmente remoto via aplicativo |
| Objetivo | Permitir que o usuário realize o cadastro de um CPF de forma completamente remota, sem precisar comparecer a uma unidade da Receita Federal. |
| Contexto | Um cidadão que nunca teve CPF deseja se cadastrar utilizando apenas seu celular. Ele deseja evitar deslocamentos e filas, fazendo todo o processo através do aplicativo oficial da Receita Federal. |
| Atores   | Usuário (pessoa física sem CPF). |
| Recursos | Aplicativo da Receita Federal, smartphone com câmera, conexão à internet, documentos digitalizados ou fotografados (RG ou CNH, comprovante de residência), sistema de validação biométrica/facial. |
| Episódios | 1. O usuário instala o app da Receita Federal e seleciona a opção "Cadastrar CPF".<br>2. Informa seus dados pessoais: nome, data de nascimento, nome da mãe, naturalidade etc.<br>3. Anexa foto dos documentos solicitados.<br>4. Realiza verificação facial para validar identidade.<br>5. Confirma os dados e envia a solicitação.<br>6. Recebe notificação com a confirmação do cadastro e número do CPF. |
| Restrição | Disponível apenas para pessoas maiores de 18 anos no primeiro momento; validação de documentos limitada a determinados formatos e legibilidade mínima. |
| Exceção  | Se a verificação facial falhar ou os documentos não forem validados, o sistema solicitará novo envio ou direcionará o usuário a atendimento presencial. |


<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>

### Cenário 02 (C02)
<p style="text-align: center"><b>Tabela 2</b> - Cenário 02</p>
| Abstração | Descrição |
|----------|-----------|
| Título   | Idoso utiliza chatbot acessível para tirar dúvidas sobre a declaração do IR |
| Objetivo | Auxiliar um usuário idoso, com pouca familiaridade com tecnologia, a obter informações claras e acessíveis sobre a declaração do Imposto de Renda por meio de um chatbot intuitivo, com apoio visual e recursos multimodais. |
| Contexto | Um senhor de 72 anos, aposentado, tenta entender se precisa declarar Imposto de Renda este ano. Por não saber usar bem o aplicativo, ele busca ajuda no chatbot, esperando uma navegação simples e orientações visuais e em vídeo. |
| Atores   | Usuário (idoso com dificuldades tecnológicas). |
| Recursos | App da Receita Federal, chatbot com interface simplificada, botões grandes, vídeos explicativos, imagens ilustrativas e linguagem acessível. |
| Episódios | 1. O usuário acessa o app com ajuda de um familiar.<br>2. Ele encontra facilmente o botão “Ajuda” na tela inicial e clica.<br>3. O chatbot é ativado em modo acessível para idosos, com texto em fonte grande e linguagem simples.<br>4. O usuário digita (ou seleciona de uma lista): “Preciso declarar?”<br>5. O chatbot responde com uma explicação clara, seguida de um vídeo curto com locução pausada e legenda explicativa.<br>6. O vídeo mostra exemplos práticos e utiliza linguagem fácil, o que ajuda o usuário a entender sua situação. |
| Restrição | O modo acessível deve ser ativado automaticamente com base em perfil ou manualmente pelo usuário; vídeos explicativos ainda não cobrem todos os temas possíveis. |
| Exceção  | Caso o usuário tenha dificuldades mesmo com os recursos visuais e simples, o app oferece a opção de ser redirecionado a um atendente via chamada por vídeo ou telefone. |



<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>

### Cenário 03 (C03)
<p style="text-align: center"><b>Tabela 3</b> - Cenário 03</p>
| Abstração | Descrição |
|----------|-----------|
| Título   | Consulta e gerenciamento de múltiplos CPFs/CNPJs pelo app |
| Objetivo | Permitir que profissionais contábeis acessem rapidamente as informações fiscais de diversos clientes. |
| Contexto | Durante a temporada do Imposto de Renda, um usuário precisa consultar e acompanhar a situação fiscal de diferentes clientes. |
| Atores   | Usuário profissional (contabilista ou semelhante). |
| Recursos | App da Receita Federal, conexão com a internet, conta Gov.br com permissão de acesso a múltiplos documentos. |
| Episódios | 1. O usuário faz login com sua conta Gov.br.<br>2. Acessa a aba “Meus clientes” e seleciona um CPF.<br>3. Visualiza pendências, gera DARFs e verifica status de restituição.<br>4. Alterna rapidamente entre CPFs/CNPJs para continuar os atendimentos. |
| Restrição | Só é possível acessar dados de terceiros se houver procuração digital registrada. |
| Exceção  | Caso o sistema esteja fora do ar ou com lentidão, o acesso pode ser temporariamente suspenso. |


<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>

### Cenário 04 (C04)
<p style="text-align: center"><b>Tabela 4</b> - Cenário 04</p>
|Abstração| Descrição                                                                                     | 
| -----    | -------------------------------------------------------------------------------------------- | 
| Título   | Acompanhamento detalhado do status de restituição                                            | 
| Objetivo | Permitir que o usuário acompanhe com precisão a situação da restituição, incluindo informações sobre o lote, posição na fila e previsão de depósito.                                                                                   | 
| Contexto | Um contribuinte que enviou sua declaração deseja acompanhar o status da restituição para planejar o uso do valor a ser recebido. Ele precisa de informações claras sobre sua posição e data provável de pagamento.                                                                                  | 
| Atores   | Usuário (contribuinte comum).                                                                                  | 
| Recursos |  App da Receita Federal, login com conta Gov.br, conexão à internet.                                                                                   | 
| Episódios| 1. O usuário acessa o app e entra com seu login Gov.br <br> 2. Vai até a seção “Minha Restituição”. <br> 3.O sistema mostra o status da análise da declaração (ex: “Aprovada”, “Em processamento”, “Na malha fina”). <br> 4. Se a declaração estiver aprovada, o sistema exibe: Lote previsto para pagamento (ex: “3º lote – 28/06/2025”); Situação do crédito bancário (ex: “Agendado” ou “Pendente”); Canal bancário informado para recebimento.| <br> 5. O app apresenta um gráfico de linha do tempo com as fases da restituição: Envio → Análise → Lote atribuído → Pagamento. 6. O usuário ativa notificações push para receber aviso no dia anterior ao depósito.
| Restrição| Os dados sobre lote só são liberados após análise e aprovação da declaração.|
| Exceção  | Caso a declaração esteja com pendências, o app notifica: “Restituição suspensa – verifique pendências na declaração”. <br> Se os dados bancários estiverem incorretos, o sistema alerta e bloqueia o agendamento até correção.|

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>


### Cenário 05 (C05)

<p style="text-align: center"><b>Tabela 5</b> - Cenário 05</p>

| Abstração     | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Título**    | Atualização de dados cadastrais no CPF                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Objetivo**  | Permitir que o usuário atualize informações básicas do CPF, como endereço, telefone e estado civil, diretamente pelo aplicativo.                                                                                                                                                                                                                                                                                                                                                     |
| **Contexto**  | Um contribuinte mudou de residência e precisa atualizar o endereço cadastrado na Receita Federal para evitar problemas no recebimento de correspondências oficiais e garantir que seus dados estejam atualizados no banco de dados da Receita.                                                                                                                                                                                                                                       |
| **Atores**    | Usuário (contribuinte comum).                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Recursos**  | App da Receita Federal, login com conta Gov.br, conexão à internet, comprovante de residência digitalizado.                                                                                                                                                                                                                                                                                                                                                                          |
| **Episódios** | 1. O usuário acessa o app e faz login com a conta Gov.br. <br> 2. Navega até a seção “Meu CPF” e seleciona “Atualizar dados”. <br> 3. O sistema exibe os dados atuais e solicita os novos dados. <br> 4. O usuário insere o novo endereço e anexa o comprovante de residência. <br> 5. O sistema valida os dados inseridos. <br> 6. O app confirma a atualização e emite um protocolo digital de alteração. <br> 7. O usuário recebe uma notificação push confirmando a atualização. |
| **Restrição** | Apenas titulares do CPF podem atualizar os dados; é obrigatório anexar um comprovante de residência válido.                                                                                                                                                                                                                                                                                                                                                                          |
| **Exceção**   | Caso o comprovante enviado não seja válido (ex: ilegível, fora da data), o sistema rejeita a solicitação e solicita um novo envio com mensagem de erro detalhada.                                                                                                                                                                                                                                                                                                                    |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>




### Cenário 06 (C06)

<p style="text-align: center"><b>Tabela 6</b> - Cenário 06</p>

| Abstração     | Descrição                                                                                                                                                                                                                                                                                                                                                                                                              |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**    | Emissão de comprovante de situação cadastral do CPF                                                                                                                                                                                                                                                                                                                                                                    |
| **Objetivo**  | Permitir que o usuário gere e baixe um comprovante oficial de situação cadastral do CPF pelo aplicativo.                                                                                                                                                                                                                                                                                                               |
| **Contexto**  | Um contribuinte precisa apresentar o comprovante de situação cadastral do CPF para abertura de conta bancária e deseja emitir o documento de forma rápida e digital pelo app da Receita.                                                                                                                                                                                                                               |
| **Atores**    | Usuário (contribuinte comum).                                                                                                                                                                                                                                                                                                                                                                                          |
| **Recursos**  | App da Receita Federal, login com conta Gov.br, conexão à internet, PDF Reader.                                                                                                                                                                                                                                                                                                                                        |
| **Episódios** | 1. O usuário acessa o app e faz login com a conta Gov.br. <br> 2. Navega até a seção “Meu CPF” e escolhe “Emitir comprovante”. <br> 3. O sistema processa a solicitação e exibe os dados cadastrais atuais. <br> 4. O usuário confirma as informações e clica em “Gerar PDF”. <br> 5. O sistema disponibiliza o comprovante para download. <br> 6. O app oferece a opção de compartilhar o PDF por e-mail ou WhatsApp. |
| **Restrição** | A emissão só é permitida para o titular do CPF; o comprovante gerado tem validade de 90 dias.                                                                                                                                                                                                                                                                                                                          |
| **Exceção**   | Caso o CPF esteja suspenso ou pendente de regularização, o sistema exibe alerta: “Impossível emitir comprovante – situação cadastral irregular” e orienta o usuário sobre como regularizar.                                                                                                                                                                                                                            |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>

### Cenário 07 (C07)

<p style="text-align: center"><b>Tabela 7</b> - Cenário 07</p>

| Abstração     | Descrição                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**    | Geração de DARF para pagamento de imposto                                                                                                                                                                                                                                                                                                                                                             |
| **Objetivo**  | Permitir que o usuário gere uma Guia de Recolhimento (DARF) para pagamento de impostos devidos diretamente pelo app.                                                                                                                                                                                                                                                                                  |
| **Contexto**  | Um contribuinte precisa pagar imposto de renda complementar após ajuste anual e deseja emitir o DARF pelo aplicativo para efetuar o pagamento via internet banking.                                                                                                                                                                                                                                   |
| **Atores**    | Usuário (contribuinte comum).                                                                                                                                                                                                                                                                                                                                                                         |
| **Recursos**  | App da Receita Federal, login com conta Gov.br, conexão à internet, acesso a internet banking ou PIX.                                                                                                                                                                                                                                                                                                 |
| **Episódios** | 1. O usuário acessa o app e faz login com a conta Gov.br. <br> 2. Vai até a seção “Pagamentos” e seleciona “Gerar DARF”. <br> 3. O sistema apresenta as pendências ou impostos devidos. <br> 4. O usuário seleciona o débito e confirma a geração do DARF. <br> 5. O app gera o documento com código de barras ou QR Code PIX. <br> 6. O usuário pode baixar o PDF ou copiar o código para pagamento. |
| **Restrição** | O DARF gerado tem validade de até 30 dias; após vencimento, será necessário gerar novo documento com atualização de juros e multa.                                                                                                                                                                                                                                                                    |
| **Exceção**   | Caso o usuário não tenha débitos pendentes, o sistema exibe: “Nenhum imposto devido para pagamento no momento”.                                                                                                                                                                                                                                                                                       |

<font size="3"><p style="text-align: center">Fonte: [Diassis](https://github.com/Diaxiz), 2025.</p></font>

## Referências 

> <a>1.</a> Sommerville, Ian. Engenharia de Software. 10ª ed. São Paulo, 2019.
>
> <a>2.</a> Pressman, Roger S.; Maxim, Bruce R. Engenharia de Software: Uma Abordagem Profissional. 8ª ed. Porto Alegre: AMGH, 2016. 
>
> <a>3.</a> Alexander, Ian; Maiden, Neil. Scenarios, Stories, Use Cases: Through the Systems Development Life-Cycle. Wiley, 2004. 
>
> <a>4.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. Disponível em: [https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf)
>

## Histórico de versão
Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
`1.0` | 09/05/2025 | Criação do documento de cenários | [Jose Eduardo](https://github.com/jevprado) e [Diassis](https://github.com/Diaxiz) | [Thales Germano](https://github.com/thalesgvl)  |
`1.1` | 08/06/2025 | Colocando código nos cenários | [Jose Eduardo](https://github.com/jevprado) | [Diassis](https://github.com/Diaxiz)  |
 `1.2`  | 12/06/2025 | Adição da tabela de atividade dos membros | [Jose Eduardo](https://github.com/jevprado) | [Diassis](https://github.com/Diaxiz) |