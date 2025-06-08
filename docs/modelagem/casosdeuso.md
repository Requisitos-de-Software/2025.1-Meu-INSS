
# Documento de Casos de Uso do Aplicativo da Receita Federal do Brasil

## 1. Introdução
[cite_start]Caso de uso é uma modelagem descritiva de sequência de interações entre atores e um específico sistema que resulta em um resultado que permite compreensões necessárias ao desenvolvimento de uma atividade. [cite_start]No nosso trabalho, o sistema seria o da Receita Federal do Brasil e estabelecemos relações entre atores primário (contribuintes) e secundário (servidor do órgão).

[cite_start]O documento apresenta os diagramas de casos de uso do aplicativo da Receita Federal do Brasil (RFB). [cite_start]O aplicativo é uma ferramenta digital cujo propósito é o de facilitar o acesso dos cidadãos a serviços fiscais, como consulta à situação cadastral, acompanhamento de restituições e entrega de declarações.

[cite_start]Este documento foca em funcionalidades típicas para o cidadão usuário do app. [cite_start]A modelagem descrita visa mapear as interações entre os usuários e o sistema, bem como os requisitos já implementados e os previstos.

## 2. Metodologia Utilizada
[cite_start]A metodologia adotada para a confecção dos diagramas seguiu os princípios da UML (Unified Modeling Language). [cite_start]A equipe utilizou o quadro de modelo de negócios Canvas para alinhar objetivos, atores envolvidos e funcionalidades do sistema.

[cite_start]A validação parcial foi realizada com base em funcionalidades reais do aplicativo e dados públicos disponíveis no site da Receita Federal. [cite_start]A metodologia adotada assegura que os Casos de Uso identifiquem de modo claro e fiel a atuação do sistema.

## 3. Descrição do Diagrama de Caso de Uso
[cite_start]O diagrama de casos de uso é uma representação gráfica das funcionalidades do aplicativo sob a ótica dos usuários. [cite_start]Ele identifica quais ações estão disponíveis para cada ator (pessoas, sistemas externos ou dispositivos que possam interagir com o sistema em estudo), representando a relação entre os serviços oferecidos e os perfis que interagem com o sistema.

[cite_start]Esse diagrama é fundamental para comunicar os requisitos funcionais a desenvolvedores, analistas e demais interessados no projeto. [cite_start]Como componentes do diagrama, utilizou-se para representar os atores, ícones (bonecos-palito). [cite_start]Para o sistema, a representação se deu por meio de um retângulo delimitador do cenário. [cite_start]Para os casos de uso, utilizamos verbos no infinitivo para notação identificando a realização de ações.

[cite_start]Para os casos de uso, foi utilizado a elipse horizontal. [cite_start]Os relacionamentos foram representados por semirretas características caso se tratasse de associação, inclusão (include), extensão (extend) ou generalização.

### Tabela 1: Elementos do Diagrama de Casos de Uso

| Nome do Elemento | Imagem | Função |
|---|---|---|
| **Ator** | ![Boneco Palito](docs/assets/ChatGPT%20Image%205_06_2025,%2008_51_23.png) | Representam os diferentes tipos de usuários externos que interagem com o sistema. |
| **Elipse (Caso de Uso)** | ![Elipse](https://images.vexels.com/content/139183/preview/ellipse-cba9d3.png) | É usada para representar os casos de uso no diagrama. Um caso de uso descreve uma funcionalidade ou uma ação específica que o sistema pode realizar em resposta às interações dos atores. A elipse contém o nome do caso de uso. |
| **Retângulo (Sistema)** | ![Retângulo](https://images.vexels.com/media/users/3/139257/isolated/svg/b8fa8f291632f8fe68842e4fb100d8e0.svg) | Usado para representar o sistema ou o bloco em análise. Ele envolve os casos de uso e atores relacionados. |
| **Flecha (Relações)** | ![Flecha](docs/assets/Captura%20de%20tela%202025-06-08%20173528.png) | As flechas são usadas para representar as relações ou interações entre atores e casos de uso. |

Fonte: [Julia Massuda](https://github.com/JuliaReis18)

## 4. Atores
[cite_start]Aqui identificaremos os atores a partir da classificação primário e secundário.

### 4.1 Ator Primário: Contribuinte
Usuário principal do aplicativo. Suas ações incluem:
* [cite_start]Consultar situação fiscal.
* [cite_start]Enviar declaração de IRPF.
* [cite_start]Consultar restituições.
* [cite_start]Acompanhar restituições.
* [cite_start]Emitir e pagar guias de pagamento (DARF).
* [cite_start]Atualizar dados cadastrais.
* [cite_start]Receber notificações da Receita.
* [cite_start]Emitir certidões.
* [cite_start]Acessar vídeos e notícias institucionais.

### 4.2 Ator Secundário: Auditor da Receita
Usuário institucional, com acesso ao sistema para:
* [cite_start]Atualizar base de dados.
* [cite_start]Validar informações declaradas.
* [cite_start]Enviar notificações automatizadas.
* [cite_start]Integrar sistemas internos da RFB ao app.

## 5. Descrição geral dos diagramas Realizados
[cite_start]O Contribuinte interage com o sistema para realizar todos os casos de uso. [cite_start]O Servidor da Receita Federal valida e processa dados.

### 5.1 Diagrama de Casos de Uso: Requisitos Implementados
![Diagrama de Casos de Uso](docs/assets/Diagrama%20de%20Casos%20de%20Uso.jpg)
Fonte: [Julia Massuda](https://github.com/JuliaReis18)

### 5.2 Diagrama de Casos de Uso: Requisitos Não Implementados

## 6. Pré-condições
[cite_start]Situações em que o sistema, antes que um caso de Uso possa ser executado, devem ser atendidas.
* [cite_start]O aplicativo da Receita deve estar instalado em dispositivo compatível.
* [cite_start]O contribuinte deve possuir acesso à internet e autenticação por CPF e senha Gov.br.
* [cite_start]O sistema da Receita deve estar operacional para sincronização com o banco de dados.

## 7. Pós-condições
[cite_start]Situações em que após a conclusão dos casos de uso, se descreve o que se altera ou o que permanece como resultado da interação. [cite_start]Identificam que o resultado pretendido foi conquistado.
* [cite_start]Consulta ou serviço solicitado é realizado com sucesso.
* [cite_start]O status do CPF é atualizado ou exibido.
* [cite_start]Declarações e comprovantes são enviados ou baixados.
* [cite_start]Usuário recebe notificação da conclusão do processo.

## 8. Relacionamentos
[cite_start]Identifica as interações entre os atores a partir dos casos de uso. [cite_start]Auxilia na identificação das interdependências e interações necessárias para a compreensão do funcionamento do sistema. [cite_start]Podem ser classificados em associação, generalização, inclusão e extensão.
* [cite_start]Associação: Entre o contribuinte e os casos de uso (ex: “Emitir DARF”).
* [cite_start]Inclusão (<<include>>): Validação de conexão com a internet é incluída em vários casos.
* [cite_start]Extensão (<<extend>>): Compartilhamento de comprovantes ou acesso a vídeos explicativos.

### 8.1 Pontos de Extensão
* [cite_start]PE1: Compartilhar comprovante de declaração via e-mail/WhatsApp.
* [cite_start]PE2: Acessar vídeos sobre como interpretar pendências.
* [cite_start]PE3: Acompanhar histórico de declarações anteriores.

### 8.2 Pontos de Inclusão
* [cite_start]PI1: Validar conexão com internet.
* [cite_start]PI2: Validar CPF com sistema da Receita.
* [cite_start]PI3: Exibir status da declaração após envio.

## 9. Compreensão do Diagrama:

### 9.1 SISTEMA
* [cite_start]O sistema é representado por um retângulo? 
* [cite_start]O sistema tem título no topo? 
* [cite_start]Todas as funcionalidades estão dentro do retângulo? 
* [cite_start]Tudo fora do retângulo ocorre fora do app? 

### 9.2 ATORES
* [cite_start]O ator contribuinte interage com o app? 
* [cite_start]O ator servidor interage com o app? 
* [cite_start]O ator primário está à esquerda? 
* [cite_start]O ator secundário está à direita? 

### 9.3 CASOS DE USO

#### 9.3.1 Autenticação
##### 9.3.1.1 Realizar Login
* [cite_start]Login com CPF 
* [cite_start]Login com certificado digital 
* [cite_start]Login com conta Gov.br 
* [cite_start]Segurança adequada aos serviços 
* [cite_start]Bloqueio após tentativas inválidas 
* [cite_start]Armazenamento seguro de credenciais 

##### 9.3.1.2 Recuperar Senha
* [cite_start]Recuperação por e-mail 
* [cite_start]Recuperação por SMS 
* [cite_start]Validação de dados pessoais 
* [cite_start]Link de recuperação com expiração 

##### 9.3.1.3 Validar Acesso via Gov.br
* [cite_start]Integração com Gov.br 
* [cite_start]Reconhecimento de níveis de autenticação 
* [cite_start]Redirecionamento pós-login 
* [cite_start]Transmissão segura de dados 

#### 9.3.2 Consultas Gerais
##### 9.3.2.1 Consultar Situação Fiscal
* [cite_start]Exibição de pendências 
* [cite_start]Visualização de extrato 
* [cite_start]Detalhamento de débitos 
* [cite_start]Status em tempo real 
* [cite_start]Download de relatório 

##### 9.3.2.2 Atualizar Dados Cadastrais
* [cite_start]Alterar endereço 
* [cite_start]Alterar contatos (email/telefone) 
* [cite_start]Alterar dados bancários 
* [cite_start]Confirmação por e-mail/SMS 
* [cite_start]Proteção contra alterações indevidas 

##### 9.3.2.3 Consultar Processos
* [cite_start]Lista de processos 
* [cite_start]Detalhes do processo 
* [cite_start]Notificações de atualizações 
* [cite_start]Histórico de movimentações 
* [cite_start]Download de documentos 

#### 9.3.3. Agendar Atendimento
* [cite_start]Disponibilidade de datas/horários 
* [cite_start]Escolha de unidades 
* [cite_start]Confirmação de agendamento 
* [cite_start]Cancelamento e remarcação 
* [cite_start]Lembretes automáticos 

#### 9.3.4. Pagar Tributos
* [cite_start]Lista de tributos pendentes 
* [cite_start]Integração com bancos 
* [cite_start]Histórico de pagamentos 
* [cite_start]Parcelamento de débitos 
* [cite_start]Emissão de comprovante 

#### 9.3.5. Declaração de Imposto de Renda
##### 9.3.5.1 Preencher Declaração
* [cite_start]Importar dados do ano anterior 
* [cite_start]Dados pré-preenchidos 
* [cite_start]Importar fontes pagadoras 
* [cite_start]Bens e direitos 
* [cite_start]Dependentes 
* [cite_start]Cálculo de deduções 
* [cite_start]Verificação de inconsistências 

##### 9.3.5.2 Enviar Declaração
* [cite_start]Transmissão segura 
* [cite_start]Recebimento de protocolo 
* [cite_start]Confirmação pela Receita 
* [cite_start]Status de processamento 
* [cite_start]Desempenho de envio 

##### 9.3.5.3 Consultar Recibo
* [cite_start]Visualizar recibo 
* [cite_start]Baixar em PDF 
* [cite_start]Compartilhar recibo 
* [cite_start]Histórico de recibos 

#### 9.3.6. Restituição de IR
##### 9.3.6.1 Consultar Lotes
* [cite_start]Cronograma de lotes 
* [cite_start]Consulta por CPF 
* [cite_start]Valor e data do pagamento 
* [cite_start]Status de análise 
* [cite_start]Notificações de liberação 

##### 9.3.6.2 Atualizar Dados Bancários
* [cite_start]Alterar conta para crédito 
* [cite_start]Validação de dados bancários 
* [cite_start]Confirmação da alteração 
* [cite_start]Histórico de alterações 

##### 9.3.6.3 Emitir Comprovante
* [cite_start]Geração de comprovante 
* [cite_start]Baixar PDF 
* [cite_start]Validação fiscal 
* [cite_start]Compartilhamento 
* [cite_start]Histórico de comprovantes 

#### 9.3.7 Segurança
* [cite_start]Proteção de dados locais 
* [cite_start]Autenticação biométrica 
* [cite_start]Conformidade com LGPD 

#### 9.3.8 Usabilidade
* [cite_start]Acessibilidade 
* [cite_start]Compatibilidade com telas 
* [cite_start]Clareza das instruções 
* [cite_start]Navegação intuitiva 
* [cite_start]Ajuda contextual 
* [cite_start]Busca no app 

### 9.4. RELACIONAMENTO
* [cite_start]Atores interagem com os casos de uso? 
* [cite_start]Existe associação entre atores e funcionalidades? 
* [cite_start]Existe inclusão (<<include>>)? 
* [cite_start]Existe extensão (<<extend>>)? 
* Existe generalização? [cite_start](não aplicável neste caso) 

## 10. Validação
[cite_start]A validação dos diagramas considerou a descrição oficial do aplicativo da Receita Federal, bem como testes simulados por usuários reais. [cite_start]A análise será complementada em nova rodada após entrevista com especialistas da RFB.



## Referências

* DEVMEDIA. O que é UML e diagramas de caso de uso – Introdução prática à UML. Disponível em: https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408. Acesso em: 08 jun. [cite_start]2025. 
* Receita Federal do Brasil. Aplicativo Pessoa Física. Disponível em: https://www.gov.br/receitafederal. Acesso em: 08 jun. [cite_start]2025 
* SOMMERVILLE, Ian. Engenharia de Software. 10. ed. [cite_start]São Paulo: Pearson, 2011. 
* PINTO, Gabriel. Modelagem de Casos de Uso. [cite_start]Brasília, 2025.



## Histórico de versões

Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
1.0 | 11/05/2025 | Criação do documento Casos de uso | [Julia Massuda](https://github.com/JuliaReis18) e  [Andre Lopes](https://github.com/andrewslopes)  | [Jose Eduardo](https://github.com/jevprado) |
1.0 | 08/06/2025 | Alterações no conteúdo + adicionando novo diagrama e tabela de casos de uso | [Julia Massuda](https://github.com/JuliaReis18) e  [Andre Lopes](https://github.com/andrewslopes)  | ADD REVISOR AQUI 
