
# Documento de Casos de Uso do Aplicativo da Receita Federal do Brasil

## 1. Introdução

Caso de uso é uma modelagem descritiva de sequência de interações entre atores e um sistema específico que resulta em um resultado que permite compreensões necessárias ao desenvolvimento de uma atividade. No nosso trabalho, o sistema é o da Receita Federal do Brasil, e estabelecemos relações entre o ator primário (contribuintes) e o secundário (servidor do órgão).

O documento apresenta os diagramas de casos de uso do aplicativo da Receita Federal do Brasil (RFB). O aplicativo é uma ferramenta digital cujo propósito é facilitar o acesso dos cidadãos a serviços fiscais, como consulta à situação cadastral, acompanhamento de restituições e entrega de declarações.

Este documento foca em funcionalidades típicas para o cidadão usuário do app. A modelagem descrita visa mapear as interações entre os usuários e o sistema, bem como os requisitos já implementados e os previstos.

## 2. Metodologia Utilizada

A metodologia adotada para a confecção dos diagramas seguiu os princípios da UML (Unified Modeling Language). A equipe utilizou o quadro de modelo de negócios Canvas para alinhar objetivos, atores envolvidos e funcionalidades do sistema.

A validação parcial foi realizada com base em funcionalidades reais do aplicativo e dados públicos disponíveis no site da Receita Federal. A metodologia adotada assegura que os casos de uso identifiquem de modo claro e fiel a atuação do sistema.

## 3. Descrição do Diagrama de Caso de Uso

O diagrama de casos de uso é uma representação gráfica das funcionalidades do aplicativo sob a ótica dos usuários. Ele identifica quais ações estão disponíveis para cada ator (pessoas, sistemas externos ou dispositivos que possam interagir com o sistema em estudo), representando a relação entre os serviços oferecidos e os perfis que interagem com o sistema.

Esse diagrama é fundamental para comunicar os requisitos funcionais a desenvolvedores, analistas e demais interessados no projeto. Como componentes do diagrama, utilizou-se ícones (bonecos-palito) para representar os atores. Para o sistema, a representação se deu por meio de um retângulo delimitador do cenário. Para os casos de uso, utilizamos verbos no infinitivo em uma elipse horizontal.

Os relacionamentos foram representados por semirretas características, caso se tratasse de associação, inclusão (include), extensão (extend) ou generalização.

### Tabela 1: Elementos do Diagrama de Casos de Uso

| Nome do Elemento | Imagem | Função |
|---|---|---|
| **Ator** | ![Boneco Palito](../assets/ChatGPT%20Image%205_06_2025,%2008_51_23.png) | Representa os diferentes tipos de usuários externos que interagem com o sistema. |
| **Elipse (Caso de Uso)** | ![Elipse](https://cdn-icons-png.flaticon.com/512/1014/1014918.png) | Representa uma funcionalidade ou uma ação específica que o sistema pode realizar. A elipse contém o nome do caso de uso. |
| **Retângulo (Sistema)** | ![Retângulo](https://images.vexels.com/media/users/3/139257/isolated/svg/b8fa8f291632f8fe68842e4fb100d8e0.svg) | Representa o sistema ou o bloco em análise. Ele envolve os casos de uso e atores relacionados. |
| **Flecha (Relações)** | ![Flecha](../assets/Captura%20de%20tela%202025-06-08%20173528.png) | Representa as relações ou interações entre atores e casos de uso. |

Fonte: [Julia Massuda](https://github.com/JuliaReis18)

## 4. Atores

### 4.1 Ator Primário: Contribuinte 

Usuário principal do aplicativo. Suas ações incluem:

- Consultar situação fiscal
- Enviar declaração de IRPF
- Consultar e acompanhar restituições
- Emitir e pagar guias de pagamento (DARF)
- Atualizar dados cadastrais
- Receber notificações da Receita
- Emitir certidões
- Acessar vídeos e notícias institucionais

### 4.2 Ator Secundário: Auditor da Receita 

Usuário institucional, com acesso ao sistema para:

- Atualizar base de dados
- Validar informações declaradas
- Enviar notificações automatizadas
- Integrar sistemas internos da RFB ao app

## 5. Descrição Geral dos Diagramas Realizados

- O contribuinte interage com o sistema para realizar todos os casos de uso.
- O servidor da Receita Federal valida e processa os dados.

### 5.1 Diagrama de Casos de Uso: Requisitos Implementados

![Diagrama de Casos de Uso](../assets/Diagrama%20de%20Casos%20de%20Uso.jpg)  
Fonte: [Julia Massuda](https://github.com/JuliaReis18)

### 5.2 Diagrama de Casos de Uso: Requisitos Não Implementados

*Em desenvolvimento.*

## 6. Pré-condições

Situações que devem ser atendidas antes que um caso de uso possa ser executado:
- O aplicativo da Receita deve estar instalado em um dispositivo compatível.
- O contribuinte deve possuir acesso à internet e autenticação por CPF e senha Gov.br.
- O sistema da Receita deve estar operacional para sincronização com o banco de dados.

## 7. Pós-condições

Situações que descrevem o que se altera ou permanece após a execução dos casos de uso:
- Consulta ou serviço solicitado é realizado com sucesso.
- O status do CPF é atualizado ou exibido.
- Declarações e comprovantes são enviados ou baixados.
- O usuário recebe notificação da conclusão do processo.

## 8. Relacionamentos

Identificam as interações entre os atores e os casos de uso, podendo ser:
- **Associação**: Entre o contribuinte e os casos de uso (ex: "Emitir DARF").
- **Inclusão (`<<include>>`)**: Validação de conexão com a internet incluída em vários casos.
- **Extensão (`<<extend>>`)**: Compartilhamento de comprovantes ou acesso a vídeos explicativos.

### 8.1 Pontos de Extensão

- **PE1**: Compartilhar comprovante de declaração via e-mail/WhatsApp
- **PE2**: Acessar vídeos sobre como interpretar pendências
- **PE3**: Acompanhar histórico de declarações anteriores

### 8.2 Pontos de Inclusão

- **PI1**: Validar conexão com internet
- **PI2**: Validar CPF com o sistema da Receita
- **PI3**: Exibir status da declaração após envio

## 9. Compreensão do Diagrama

### 9.1 Sistema
- O sistema é representado por um retângulo?
- O sistema tem título no topo?
- Todas as funcionalidades estão dentro do retângulo?
- Tudo fora do retângulo ocorre fora do app?

### 9.2 Atores
- O ator contribuinte interage com o app?
- O ator servidor interage com o app?
- O ator primário está à esquerda?
- O ator secundário está à direita?

### 9.3 Casos de Uso

#### 9.3.1 Autenticação

##### 9.3.1.1 Realizar Login
- Login com CPF
- Login com certificado digital
- Login com conta Gov.br
- Segurança adequada aos serviços
- Bloqueio após tentativas inválidas
- Armazenamento seguro de credenciais

##### 9.3.1.2 Recuperar Senha
- Recuperação por e-mail
- Recuperação por SMS
- Validação de dados pessoais
- Link de recuperação com expiração

##### 9.3.1.3 Validar Acesso via Gov.br
- Integração com Gov.br
- Reconhecimento de níveis de autenticação
- Redirecionamento pós-login
- Transmissão segura de dados

#### 9.3.2 Consultas Gerais

##### 9.3.2.1 Consultar Situação Fiscal
- Exibição de pendências
- Visualização de extrato
- Detalhamento de débitos
- Status em tempo real
- Download de relatório

##### 9.3.2.2 Atualizar Dados Cadastrais
- Alterar endereço
- Alterar contatos (e-mail/telefone)
- Alterar dados bancários
- Confirmação por e-mail/SMS
- Proteção contra alterações indevidas

##### 9.3.2.3 Consultar Processos
- Lista de processos
- Detalhes do processo
- Notificações de atualizações
- Histórico de movimentações
- Download de documentos

#### 9.3.3 Agendar Atendimento
- Disponibilidade de datas/horários
- Escolha de unidades
- Confirmação de agendamento
- Cancelamento e remarcação
- Lembretes automáticos




#### 9.3.4. Pagar Tributos
* Lista de tributos pendentes 
* Integração com bancos 
* Histórico de pagamentos 
* Parcelamento de débitos 
* Emissão de comprovante 

#### 9.3.5. Declaração de Imposto de Renda
##### 9.3.5.1 Preencher Declaração
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

##### 9.3.5.3 Consultar Recibo
* Visualizar recibo 
* Baixar em PDF 
* Compartilhar recibo 
* Histórico de recibos 

#### 9.3.6. Restituição de IR
##### 9.3.6.1 Consultar Lotes
* Cronograma de lotes 
* Consulta por CPF 
* Valor e data do pagamento 
* Status de análise 
* Notificações de liberação 

##### 9.3.6.2 Atualizar Dados Bancários
* Alterar conta para crédito 
* Validação de dados bancários 
* Confirmação da alteração 
* Histórico de alterações 

##### 9.3.6.3 Emitir Comprovante
* Geração de comprovante 
* Baixar PDF 
* Validação fiscal 
* Compartilhamento 
* Histórico de comprovantes 

#### 9.3.7 Segurança
* Proteção de dados locais 
* Autenticação biométrica 
* Conformidade com LGPD 

#### 9.3.8 Usabilidade
* Acessibilidade 
* Compatibilidade com telas 
* Clareza das instruções 
* Navegação intuitiva 
* Ajuda contextual 
* Busca no app 

### 9.4. RELACIONAMENTO
* Atores interagem com os casos de uso? 
* Existe associação entre atores e funcionalidades? 
* Existe inclusão (<<include>>)? 
* Existe extensão (<<extend>>)? 
* Existe generalização? (não aplicável neste caso) 

## 10. Validação
A validação dos diagramas considerou a descrição oficial do aplicativo da Receita Federal, bem como testes simulados por usuários reais. A análise será complementada em nova rodada após entrevista com especialistas da RFB.



## Referências

* DEVMEDIA. O que é UML e diagramas de caso de uso – Introdução prática à UML. Disponível em: https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408. Acesso em: 08 jun. 2025. 
* Receita Federal do Brasil. Aplicativo Pessoa Física. Disponível em: https://www.gov.br/receitafederal. Acesso em: 08 jun. 2025 
* SOMMERVILLE, Ian. Engenharia de Software. 10. ed. São Paulo: Pearson, 2011. 
* PINTO, Gabriel. Modelagem de Casos de Uso. Brasília, 2025.



## Histórico de versões

Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
1.0 | 11/05/2025 | Criação do documento Casos de uso | [Julia Massuda](https://github.com/JuliaReis18) e  [Andre Lopes](https://github.com/andrewslopes)  | [Jose Eduardo](https://github.com/jevprado) |
1.0 | 08/06/2025 | Alterações no conteúdo + adicionando novo diagrama e tabela de casos de uso | [Julia Massuda](https://github.com/JuliaReis18) e  [Andre Lopes](https://github.com/andrewslopes)  | [Jose Eduardo](https://github.com/jevprado) |
