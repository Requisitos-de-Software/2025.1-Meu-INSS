# Requisitos elicitados 

## Introdução 

Esta página tem como objetivo compilar todos os requisitos elicitados para o aplicativo da Receita Federal, com base em diversas técnicas utilizadas na etapa 02 do projeto. Foram aplicadas abordagens como **personas**, **storytelling**, **grupo de foco** e **analise de documentos**, que permitiram uma compreensão mais ampla e detalhada das necessidades dos usuários e dos processos envolvidos.

Os requisitos identificados estão organizados em duas categorias principais:

Requisitos Funcionais, que descrevem as funcionalidades que o sistema deve oferecer.

Requisitos Não Funcionais, que especificam restrições e qualidades esperadas do sistema, como desempenho, usabilidade e segurança.


## Tabela de requisitos elicitados 

### Tabela 01 - Requisitos Funcionais
| ID   | Descrição                                                                                 | Categoria | Status           | Fonte |
| ---- | ----------------------------------------------------------------------------------------- | --------- | ---------------- | ----- |
| RE1  | Acesso rápido e simultâneo a múltiplos CPFs/CNPJs                                         | RF        | NÃO IMPLEMENTADO | -     |
| RE2  | Cadastro de CPF via app (totalmente remoto)                                               | RF        | NÃO IMPLEMENTADO | -     |
| RE3  | Acompanhamento de status da restituição (precisão quanto aos lotes)                       | RF        | NÃO IMPLEMENTADO | -     |
| RE4  | Notificação de vencimento próximo                                                         | RF        | NÃO IMPLEMENTADO | -     |
| RE5  | Agendar no próprio aplicativo atendimentos presenciais em unidades da Receita Federal     | RF        | NÃO IMPLEMENTADO | -     |
| RE6  | Acesso offline a serviços essenciais do app (históricos de contribuições, DARFs)          | RF        | NÃO IMPLEMENTADO | -     |
| RE7  | Alteração de dados via app                                                                | RF        | NÃO IMPLEMENTADO | -     |
| RE8  | Funcionalidade de histórico e acompanhamento de restituições e de declarações             | RF        | IMPLEMENTADO     | -     |
| RE9  | Declaração simplificada do IR                                                             | RF        | IMPLEMENTADO     | -     |
| RE10 | Geração de guias de pagamento                                                             | RF        | IMPLEMENTADO     | -     |
| RE11 | Consultar o status do CPF (ativo ou não)                                                  | RF        | IMPLEMENTADO     | -     |
| RE12 | Integração com conta Gov.br                                                               | RF        | IMPLEMENTADO     | -     |
| RE13 | Envio de documentos para instrução de processos                                           | RF        | IMPLEMENTADO     | -     |
| RE14 | O usuário deve poder acessar sua declaração de imposto de renda dos últimos anos          | RF        | IMPLEMENTADO     | -     |
| RE15 | O aplicativo deve permitir o envio da declaração do Imposto de Renda diretamente pelo app | RF        | IMPLEMENTADO     | -     |
| RE16 | O aplicativo deve mostrar um histórico das declarações entregues pelo usuário             | RF        | IMPLEMENTADO     | -     |
| RE17 | Emissão de certidão negativa via aplicativo                                               | RF        | IMPLEMENTADO     | -     |
| RE18 | Consultar pendências de Malha                                                             | RF        | IMPLEMENTADO     | -     |
| RE19 | Dashboard para profissionais contábeis de múltiplos CPFs/CNPJs                            | RF        | NÃO IMPLEMENTADO | -     |
| RE20 | Acesso offline a serviços essenciais do app (históricos de contribuições, DARFs)          | RF        | NÃO IMPLEMENTADO | -     |
| RE21 | Acompanhar processos no próprio aplicativo                                                | RF        | NÃO IMPLEMENTADO | -     |
| RE22 | Integração com o App Esocial dentro do próprio                                            | RF        | NÃO IMPLEMENTADO | -     |
| RE23 | Permitir via App autorização de acesso à terceiros                                        | RF        | IMPLEMENTADO     | -     |
| RE24 | Compartilhamento de comprovantes e certidões por WhatsApp, e-mail ou Drive                | RF        | NÃO IMPLEMENTADO | -     |
| RE25 | Reenvio de notificações perdidas via e-mail ou mensagem no app                            | RF        | NÃO IMPLEMENTADO | -     |
| RE26 | Comparativo automático entre declarações de anos anteriores                               | RF        | NÃO IMPLEMENTADO | -     |
| RE27 | FAQ interativo com busca inteligente (filtrado por tema: CPF, IRPF, Certidões etc.)       | RF        | NÃO IMPLEMENTADO | -     |
| RE28 | Integração com calendário do dispositivo para lembretes de obrigações fiscais             | RF        | NÃO IMPLEMENTADO | -     |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado), [Thales Germano](https://github.com/thalesgvl), 2025.</p></font>

### Tabela 02 - Requisitos Não-Funcionais
| ID   | Descrição                                                                                  | Categoria | Status           | Fonte |
| ---- | ------------------------------------------------------------------------------------------ | --------- | ---------------- | ----- |
| RE29 | Acessibilidade (chatbot, imagens, vídeos) — melhorias no chatbot sugeridas                 | RNF       | NÃO IMPLEMENTADO | -     |
| RE30 | Conteúdo educativo para iniciantes                                                         | RNF       | NÃO IMPLEMENTADO | -     |
| RE31 | Testes de desempenho para suportar alta demanda de usuários simultâneos                    | RNF       | IMPLEMENTADO     | -     |
| RE32 | Proteção de dados pessoais conforme a LGPD                                                 | RNF       | IMPLEMENTADO     | -     |
| RE33 | Interface responsiva e acessível                                                           | RNF       | IMPLEMENTADO     | -     |
| RE34 | Interface com a possibilidade de uso do modo escuro                                        | RNF       | NÃO IMPLEMENTADO | -     |
| RE35 | Testes de segurança para garantir a integridade dos dados e autenticação segura            | RNF       | IMPLEMENTADO     | -     |
| RE36 | Compatível com Android 8+ e iOS 14+                                                        | RNF       | IMPLEMENTADO     | -     |
| RE37 | Testes de usabilidade semestrais com público 60+                                           | RNF       | IMPLEMENTADO     | -     |
| RE38 | O aplicativo deve ter tempo de resposta inferior a 3 segundos para ações comuns            | RNF       | IMPLEMENTADO     | -     |
| RE39 | A interface deve manter legibilidade com contraste mínimo de 4,5:1                         | RNF       | IMPLEMENTADO     | -     |
| RE40 | O aplicativo deve funcionar em smartphones com telas de 4.5" a 7" sem perda de usabilidade | RNF       | IMPLEMENTADO     | -     |
| RE41 | Linguagem da interface deve seguir padrão A2 do CEFR, evitando jargões técnicos            | RNF       | IMPLEMENTADO     | -     |
| RE42 | O app deve suportar modo de operação em baixa conectividade, com cache de dados essenciais | RNF       | NÃO IMPLEMENTADO | -     |
| RE43 | Atualizações do app não devem causar perda de dados armazenados localmente                 | RNF       | IMPLEMENTADO     | -     |
| RE44 | Tempo de inatividade programada máximo de 2h por mês, com aviso prévio                     | RNF       | IMPLEMENTADO     | -     |
| RE45 | Tempo de carregamento inicial do app não deve ultrapassar 5 segundos em conexão móvel      | RNF       | IMPLEMENTADO     | -     |
| RE46 | Suporte a leitores de tela (TalkBack, VoiceOver) em todas as funcionalidades               | RNF       | IMPLEMENTADO     | -     |
| RE47 | Armazenamento anônimo de logs de erro respeitando a LGPD                                   | RNF       | IMPLEMENTADO     | -     |
| RE48 | Versão mínima em HTML5 responsiva para acesso via navegador em caso de falha do app        | RNF       | NÃO IMPLEMENTADO | -     |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado), 2025.</p></font>

## Referências


> <a>1.</a> PRESSMAN, Roger S.; MAXIM, Bruce R. *Engenharia de Software*. McGraw-Hill, 2016.  
>
> <a>2.</a>REIS, Carla Silva dos et al. Técnicas de elicitação de requisitos. *Revista de Informática Teórica e Aplicada*, 2014 
>
> <a>3.</a>SOMMERVILLE, Ian. *Engenharia de Software*. Pearson, 2019.  
>


## Historico de versões

| Versão | Data       | Descrição                                      | Autor(es)                                      | Revisor(es)                                    |
| ------ | ---------- | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- |
| 1.0    | 18/05/2025 | Criação do documento                           | [José Eduardo](https://github.com/jevprado)    | [Thales Germano](https://github.com/thalesgvl) |
| 2.0    | 28/05/2025 | Corrigindo tabela de requisitos elicitados     | [José Eduardo](https://github.com/jevprado)    | [Diassis](https://github.com/Diaxiz)           |
| 2.1    | 29/05/2025 | Corrigindo e adicionando requisitos elicitados | [Thales Germano](https://github.com/thalesgvl) | [José Eduardo](https://github.com/jevprado)    |
