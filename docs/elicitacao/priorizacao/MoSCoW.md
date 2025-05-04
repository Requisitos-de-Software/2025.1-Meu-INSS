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

| ID   | Descrição                                                                                   | Categoria |
|------|---------------------------------------------------------------------------------------------|-----------|
| R1   | Acesso rápido e simultâneo a múltiplos CPFs/CNPJs                                           | RF        |
| R2   | Cadastro de CPF via app (totalmente remoto)                                                 | RF        |
| R3   | Acompanhamento de status da restituição (precisão quanto aos lotes)                         | RF        |
| R7   | Alteração de dados via app                                                                  | RF        |
| R10  | Geração de guias de pagamento                                                               | RF        |
| R11  | Consultar o status do CPF (ativo ou não)                                                    | RF        |
| R12  | Integração com conta Gov.br                                                                 | RF        |
| R17  | Proteção de dados pessoais conforme a LGPD                                                  | RR        |

<font size="3"><p style="text-align: center">Fonte: [Grupo 06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/#membros-da-equipe), 2025.</p></font>

### Should  

<p style="text-align: center"><b>Tabela 2</b> - Tabela Should.</p>

| ID   | Descrição                                                                                   | Categoria |
|------|---------------------------------------------------------------------------------------------|-----------|
| R4   | Notificação de vencimento próximo                                                           | RF        |
| R5   | Unificação de serviços no app (ex: agendamento, processos, certidões etc.)                  | RF        |
| R6   | Acesso offline a serviços essenciais (históricos, DARFs)                                    | RF, RNF   |
| R8   | Histórico e acompanhamento de restituições e declarações                                   | RF        |
| R9   | Declaração simplificada do IR                                                               | RF        |
| R19  | Testes de segurança para garantir integridade e autenticação segura                         | RT        |

<font size="3"><p style="text-align: center">Fonte: [Grupo 06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/#membros-da-equipe), 2025.</p></font>

### Could  

<p style="text-align: center"><b>Tabela 3</b> - Tabela Could.</p>

| ID   | Descrição                                                                                   | Categoria |
|------|---------------------------------------------------------------------------------------------|-----------|
| R13  | Acessibilidade (chatbot, imagens, vídeos) — melhorias no chatbot                            | RI        |
| R14  | Conteúdo educativo para iniciantes                                                          | RI        |
| R16  | Envio de documentos para instrução de processos                                             | RF        |
| R18  | Interface responsiva para dispositivos móveis                                               | RI        |

<font size="3"><p style="text-align: center">Fonte: [Grupo 06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/#membros-da-equipe), 2025.</p></font>

### Won't  

<p style="text-align: center"><b>Tabela 4</b> - Tabela Won't.</p>

| ID   | Descrição                                                                                   | Categoria |
|------|---------------------------------------------------------------------------------------------|-----------|
| R15  | Testes de desempenho para suportar alta demanda de usuários simultâneos                     | RT        |

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