# Requisitos elicitados 

## Introdução 

Esta página tem como objetivo compilar todos os requisitos elicitados para o aplicativo da Receita Federal, com base em diversas técnicas utilizadas na etapa 02 do projeto. Foram aplicadas abordagens como **personas**, **storytelling**, **grupo de foco** e **analise de documentos**, que permitiram uma compreensão mais ampla e detalhada das necessidades dos usuários e dos processos envolvidos.

Os requisitos identificados estão organizados em duas categorias principais:

Requisitos Funcionais, que descrevem as funcionalidades que o sistema deve oferecer.

Requisitos Não Funcionais, que especificam restrições e qualidades esperadas do sistema, como desempenho, usabilidade e segurança.


## Tabela de requisitos elicitados 

### Tabela 01 - Requisitos Funcionais
<p style="text-align: center"><b>Tabela 1</b> - Requisitos funcionais.</p>

| ID    | Descrição                                                                                    | Categoria |
|-------|----------------------------------------------------------------------------------------------|-----------|
| R1    | Acesso rápido e simultâneo a múltiplos CPFs/CNPJs                                            | RF        |
| R2    | Cadastro de CPF via app (totalmente remoto)                                                  | RF        |
| R3    | Acompanhamento de status da restituição (precisão quanto aos lotes)                          | RF        |
| R4    | Notificação de vencimento próximo                                                            | RF        |
| R5    | Unificação de serviços no app (agendamento, acompanhamento de processos, certidões etc.)     | RF        |
| R6    | Acesso offline a serviços essenciais do app (históricos de contribuições, DARFs)             | RF        |
| R7    | Alteração de dados via app                                                                    | RF        |
| R8    | Funcionalidade de histórico e acompanhamento de restituições e de declarações                | RF        |
| R9    | Declaração simplificada do IR                                                                 | RF        |
| R10   | Geração de guias de pagamento                                                                 | RF        |
| R11   | Consultar o status do CPF (ativo ou não)                                                      | RF        |
| R12   | Integração com conta Gov.br                                                                   | RF        |
| R16   | Envio de documentos para instrução de processos                                               | RF        |

<font size="3"><p style="text-align: center">Fonte: [Grupo 06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/#membros-da-equipe), 2025.</p></font>

### Tabela 02 - Requisitos Não-Funcionais
<p style="text-align: center"><b>Tabela 2</b> - Requisitos Não-Funcionais</p>


| ID    | Descrição                                                                                   | Categoria |
|-------|---------------------------------------------------------------------------------------------|-----------|
| R6    | Acesso offline a serviços essenciais do app (históricos de contribuições, DARFs)           | RF e RNF  |
| R13   | Acessibilidade (chatbot, imagens, vídeos) — melhorias no chatbot sugeridas                  | RI        |
| R14   | Conteúdo educativo para iniciantes                                                          | RI        |
| R15   | Testes de desempenho para suportar alta demanda de usuários simultâneos                     | RT        |
| R17   | Proteção de dados pessoais conforme a LGPD                                                  | RR        |
| R18   | Interface responsiva, acessível e com modo escuro                                           | RI        |
| R19   | Testes de segurança para garantir a integridade dos dados e autenticação segura             | RT        |
| R20   | Compatível com Android 8+ e iOS 14+                                                          | RNF       |
| R21   | Testes de usabilidade semestrais com público 60+                                            | RT        |
| R22   | Testes de desempenho para suportar alta demanda de usuários simultâneos                     | RT        |
| RNF2  | O aplicativo deve ter tempo de resposta inferior a 3 segundos para ações comuns             | RNF       |
| RNF3  | A interface deve manter legibilidade com contraste mínimo de 4,5:1                          | RNF       |
| RNF4  | O aplicativo deve funcionar em smartphones com telas de 5" a 7" sem perda de usabilidade    | RNF       |
| RNF5  | Linguagem da interface deve seguir padrão A2 do CEFR, evitando jargões técnicos             | RNF       |
| RNF6  | O app deve suportar modo de operação em baixa conectividade, com cache de dados essenciais  | RNF       |
| RNF7  | Atualizações do app não devem causar perda de dados armazenados localmente                  | RNF       |
| RNF8  | Tempo de inatividade programada máximo de 2h por mês, com aviso prévio                       | RNF       |
| RNF9  | Tempo de carregamento inicial do app não deve ultrapassar 5 segundos em conexão 4G          | RNF       |
| RNF10 | Suporte a leitores de tela (TalkBack, VoiceOver) em todas as funcionalidades                | RNF       |
| RNF11 | Armazenamento anônimo de logs de erro respeitando a LGPD                                    | RNF       |
| RNF12 | Versão mínima em HTML5 responsiva para acesso via navegador em caso de falha do app         | RNF       |


<font size="3"><p style="text-align: center">Fonte: [Grupo 06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/#membros-da-equipe), 2025.</p></font>

## Referências


> <a>1.</a> PRESSMAN, Roger S.; MAXIM, Bruce R. *Engenharia de Software*. McGraw-Hill, 2016.  
>
> <a>2.</a>REIS, Carla Silva dos et al. Técnicas de elicitação de requisitos. *Revista de Informática Teórica e Aplicada*, 2014 
>
> <a>3.</a>SOMMERVILLE, Ian. *Engenharia de Software*. Pearson, 2019.  
>


## Historico de versões

Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
`1.0` | 18/05/2025 | Criação do documento |[José Eduardo](https://github.com/jevprado)  |[Thales Germano](https://github.com/thalesgvl) |
