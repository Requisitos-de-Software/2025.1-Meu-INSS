## Introdução 

A elicitação de requisitos é uma etapa fundamental no desenvolvimento de sistemas, pois permite identificar e compreender as necessidades que o software deve atender. Entre as diversas técnicas de levantamento de requisitos, como entrevistas, questionários e observação, existe uma abordagem menos formal e mais subjetiva: a introspecção. A introspecção pode ser útil em projetos em fases iniciais, quando ainda não há acesso direto aos usuários finais ou stakeholders.

A introspecção consiste em um processo reflexivo individual, no qual o analista ou desenvolvedor examina suas próprias ideias, experiências e expectativas para identificar possíveis funcionalidades, restrições e objetivos do sistema. Essa abordagem pode ser especialmente relevante em projetos pessoais, acadêmicos ou em situações onde o próprio analista desempenha também o papel de usuário.


## Metodologia 

A metodologia adotada baseia-se na introspecção estruturada, conduzida de forma solitária, com o objetivo de levantar requisitos iniciais para o desenvolvimento do sistema proposto, a partir do uso do mesmo. O processo foi dividido em três etapas principais:

1 -  **Reflexão inicial sobre o problema:**

Nesta fase, foram descritos o contexto geral do problema, os objetivos do sistema e os possíveis usuários (com bases nas personas). Foi utilizado anotações livres e reflexões para explorar ideias iniciais sem julgamento crítico, permitindo o surgimento de insights espontâneos.

2 - **Formulação de perguntas orientadoras:**

Com base em técnicas comuns de elicitação, foram definidas perguntas reflexivas para guiar a introspecção, tais como:

“O que eu esperaria de um sistema que resolva esse problema?”

“Que funcionalidades seriam indispensáveis para o uso diário?”

“Quais limitações ou dificuldades já enfrentei em soluções similares?”
As respostas a essas perguntas foram registradas e organizadas em categorias: *requisitos funcionais* e *requisitos não funcionais*

3 - **Análise e documentação dos requisitos levantados:**
Os requisitos obtidos foram analisados criticamente quanto à sua viabilidade e clareza. Foram então documentados utilizando uma estrutura padrão de especificação de requisitos, servindo como base para etapas posteriores do projeto.

## Tabela de requisitos 

<p style="text-align: center"><b>Tabela 1</b> - Tabela de requisitos obtidos atráves da introspecção </p>

| ID    | Descrição                                                            | Categoria |Status |
| ----- | -----------------------------------------------------------------------| --------- |--------- |
| INT1  | O usuário deve poder acessar sua declaração de imposto de renda dos últimos anos.| RF        |Implementado|
| INT2  | O aplicativo deve permitir o envio da declaração do Imposto de Renda diretamente pelo app.| RF        |Implementado|
| INT3  | Agendar no próprio aplicativo atendimentos presenciais em unidades da Receita Federal.| RF        |Não Implementado|
| INT4  | O usuário pode fixar mais de 3 itens do aplicativo na sua página de favoritos| RF        |Não Implementado|
| INT5  | O aplicativo deve mostrar um histórico das declarações entregues pelo usuário.| RF        |Implementado|
| INT6  | Emissão de certidão negativa via aplicativo.  | RF        |Implementado|
| INT7  | Consultar pendências de Malha| RF        |Implementado|
| INT8  | Dashboard para profissionais contábeis de múltiplos CPFs/CNPJs | RF        |Não Implementado|
| INT9  | O aplicativo deve ter tempo de resposta inferior a 3 segundos para ações comuns| RNF        |Implementado|
| INT10  | O aplicativo deve funcionar em smartphones com telas de 4.5" a 7" sem perda de usabilidade| RNF        |Implementado|
| INT11 | O aplicativo deve funcionar em smartphones com telas de 4.5" a 7" sem perda de usabilidade| RNF        |Implementado|
| INT12 | O app deve suportar modo de operação em baixa conectividade, com cache de dados essenciais| RNF        |Implementado|
| INT13 | O aplicativo deve funcionar em smartphones com telas de 4.5" a 7" sem perda de usabilidade| RNF        |Implementado|
| INT14 | Atualizações do app não devem causar perda de dados armazenados localmente | RNF        |Não Implementado|
| INT15 | Tempo de inatividade programada máximo de 2h por mês, com aviso prévio | RNF        | - |
| INT16 | Suporte a leitores de tela (TalkBack, VoiceOver) em todas as funcionalidades | RNF        | Implementado |
| INT17 | SArmazenamento anônimo de logs de erro respeitando a LGPD | RNF        | Implementado |
| INT18 | Versão mínima em HTML5 responsiva para acesso via navegador em caso de falha do app | RNF        | Implementado |

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>


## Bibliografia
> <a>1.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. Disponível em: [https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf](https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf)
>


## Histórico de versão
Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
`1.0` | 28/05/2025 | Criação do documento da instrospecção | [Jose Eduardo](https://github.com/jevprado) | [Thales Germano](https://github.com/thalesgvl) |