# MoSCoW 

## Introdução  
A técnica MoSCoW é utilizada para **priorizar requisitos** com base em sua importância para o sistema. Ela os categoriza em quatro grupos:

- **Must (Obrigatórios)** – Requisitos essenciais para o funcionamento mínimo do sistema.
- **Should (Importantes)** – Requisitos importantes, mas que podem ser entregues após os "Must".
- **Could (Desejáveis)** – Requisitos desejáveis, entregues se houver tempo/recursos.
- **Won’t (Não serão feitos agora)** – Requisitos que não serão implementados nesta versão.

## Metodologia  
A priorização foi realizada de forma virtual, com a participação de membros da equipe do projeto, considerando os critérios de valor para o usuário, viabilidade técnica e impacto no negócio.

## MoSCoW 

### Must  

<p style="text-align: center"><b>Tabela 1</b> - Tabela Must.</p>

| ID     | Descrição                                                                                    | Categoria |
|--------|----------------------------------------------------------------------------------------------|-----------|
| RFB01  | Login pelo gov.br com suporte a biometria.                                                   | RF        |
| RFB02  | Acesso rápido e simultâneo a múltiplos CPFs/CNPJs.                                           | RF        |
| RFB03  | Consulta, alteração e emissão de comprovante de CPF/CNPJ.                                    | RF        |
| RFB04  | Preenchimento, entrega e acompanhamento do Imposto de Renda.                                 | RF        |
| RFB05  | Geração e pagamento de DARF via Pix ou código de barras.                                     | RF        |
| RFB06  | Envio de notificações sobre restituições e pendências.                                       | RF        |
| RFB09  | Emissão de CPF 100 % remota (fotografia + verificação facial).                               | RF        |
| RFB15  | Proteção de dados pessoais conforme LGPD e biometria local.                                  | RR        |
| RFB21  | Consultar o status do CPF (ativo ou não).                                                    | RF        |


<font size="3"><p style="text-align: center">Fonte: [Grupo 06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/#membros-da-equipe), 2025.</p></font>

### Should  

<p style="text-align: center"><b>Tabela 2</b> - Tabela Should.</p>

| ID     | Descrição                                                                                    | Categoria |
|--------|----------------------------------------------------------------------------------------------|-----------|
| RFB07  | Unificação de serviços no app (agendamento, acompanhamento de processos, certidões etc.).    | RF        |
| RFB08  | Solicitação de certidões negativas dentro do app.                                            | RF        |
| RFB11  | Acesso offline a serviços essenciais do app (históricos de contribuições anteriores, DARFs). | RF e RNF  |
| RFB19  | Funcionalidade de histórico e acompanhamento de restituições e de declarações.               | RF        |
| RFB20  | Declaração simplificada do IR.                                                               | RF        |
| RFB17  | Testes de segurança para garantir a integridade dos dados e autenticação segura.             | RT        |
| RFB23  | Notificação de vencimento próximo.                                                           | RF        |

<font size="3"><p style="text-align: center">Fonte: [Grupo 06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/#membros-da-equipe), 2025.</p></font>

### Could  

<p style="text-align: center"><b>Tabela 3</b> - Tabela Could.</p>


| ID     | Descrição                                                                                    | Categoria |
|--------|----------------------------------------------------------------------------------------------|-----------|
| RFB10  | Envio de documentos para instrução de processos.                                             | RF        |
| RFB12  | Interface responsiva, acessível e com modo escuro.                                           | RI        |
| RFB13  | Acessibilidade (chatbot, imagens, vídeos) — melhorias no chatbot sugeridas.                  | RI        |
| RFB22  | Conteúdo educativo para iniciantes.                                                          | RI        |
| RFB14  | Compatível com Android 8+ e iOS 14+.                                                         | RNF       |

<font size="3"><p style="text-align: center">Fonte: [Grupo 06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/#membros-da-equipe), 2025.</p></font>

### Won't  

<p style="text-align: center"><b>Tabela 4</b> - Tabela Won't.</p>

| ID     | Descrição                                                                                    | Categoria |
|--------|----------------------------------------------------------------------------------------------|-----------|
| RFB16  | Testes de usabilidade semestrais com público 60+.                                            | RT        |
| RFB18  | Testes de desempenho para suportar alta demanda de usuários simultâneos.                     | RT        |


<font size="3"><p style="text-align: center">Fonte: [Grupo 06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/#membros-da-equipe), 2025.</p></font>


### Legenda das Categorias de Requisitos

- **RF**: Requisitos Funcionais - Descrevem o comportamento ou a funcionalidade que o software deve ter para atender às necessidades do usuário.

- **RNF**: Requisitos Não-Funcionais - Descrevem os atributos que o software deve ter, como desempenho, segurança e usabilidade, mas não descrevem o comportamento do software em si.

- **RI**: Requisitos de Interface - Descrevem as características da interface do usuário, como layout, navegação e personalização.

- **RR**: Riscos - São os riscos associados ao desenvolvimento e uso do software.

- **RT**: Testes e Validações - Descrevem as atividades necessárias para testar e validar o software antes de sua implantação.



## Referências 

> <a>1.</a> Wiegers, K., & Beatty, J. (2013). Software Requirements (3rd ed.). Microsoft Press. 
>
> <a>2.</a> Product Plan. Disponível em: [https://www.productplan.com/glossary/moscow-prioritization/](). Acesso em: 03 de maio. de 2025.
>
> <a>3.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. 2025. Disponível em: [https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf]()  Acesso em: 03 de maio. de 2025.
>

## Histórico de versões

Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
`1.0` | 04/05/2025 | Criação do primeiro documento MoSCoW | [Jose Eduardo](https://github.com/jevprado) e [Andre Lopes](https://github.com/andrewslopes) | [Diassis](https://github.com/Diaxiz) |
`1.1` | 04/05/2025 | Ajustando requisitos para o MoSCoW | [Jose Eduardo](https://github.com/jevprado) e [Andre Lopes](https://github.com/andrewslopes) |  [Thales Germano](https://github.com/thalesgvl)  |