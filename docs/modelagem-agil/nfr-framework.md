# NFR Framework

## Introdução

De acordo com a abordagem apresentada por **Reinaldo Antônio da Silva (2019)**, o NFR Framework é um modelo utilizado na modelagem de Requisitos Não-Funcionais (RNFs), baseado em *softgoals*. Esses objetivos não possuem uma definição clara ou critérios de sucesso bem estabelecidos, o que os torna ideais para representar qualidades subjetivas dos sistemas.

Os *softgoals* ajudam desenvolvedores a tomar decisões durante o projeto, considerando aspectos como qualidade, segurança e desempenho. Além disso, podem influenciar uns aos outros, criando uma rede de impactos que afetam o sistema como um todo.

### Tipos de Softgoals

Os *softgoals* podem ser classificados em três grupos principais: 

1. **Softgoals NFR**: Representam diretamente os Requisitos Não-Funcionais e podem ser organizados de forma hierárquica.
2. **Softgoals de Operacionalização**: Apontam para alternativas de implementação dos softgoals NFR, por meio de funções, estruturas ou restrições.
3. **Softgoals de Afirmação**: Representam justificativas baseadas em conhecimento de domínio ou prioridades, servindo como base para apoiar ou refutar decisões de projeto e seleção de alternativas.

<p style="text-align: center"><b>Figura 1</b> - Tipos de Softgoal </p>

![tipos-nfr](../assets/nfr/tipos-nfr.png)


<font size="3"><p style="text-align: center">Fonte: Silva, 2019.</p></font>

O atendimento aos *softgoals* é avaliado qualitativamente por meio de rótulos como **satisfeito**, **parcialmente satisfeito** ou **não satisfeito**, com base nas contribuições positivas ou negativas entre os nós no **Softgoal Interdependency Graph (SIG)**.

> **Nota**: O *Softgoal Interdependency Graph (SIG)* é um grafo que mostra como diferentes objetivos não-funcionais estão inter-relacionados, ajudando a visualizar conflitos e sinergias entre eles.

## Interdependências entre Softgoals

As **interdependências** representam as associações existentes entre os softgoals no NFR Framework. Elas se dividem em dois grandes grupos: **decomposições** e **contribuições**.

### Decomposições

As **decomposições** ocorrem em diferentes níveis de abstração, incluindo softgoals de NFR (requisitos não funcionais), de operacionalização e de afirmação. De acordo com Silva (2019), as três primeiras categorias envolvem a subdivisão de um softgoal em metas mais específicas, facilitando seu entendimento e análise. Há ainda uma decomposição especial voltada à priorização.

Os principais tipos de decomposição são:

- **Decomposição NFR:** utilizada para quebrar metas amplas e complexas em partes menores e mais manejáveis. Essa divisão ajuda a reduzir ambiguidades e a facilitar a definição de prioridades.

- **Decomposição de Operacionalização:** visa transformar uma solução genérica em soluções específicas, mais diretamente implementáveis no sistema.

- **Decomposição de Afirmação:** empregada para justificar ou refutar determinadas escolhas de projeto com base em argumentos técnicos ou estratégicos.

- **Decomposição de Priorização:** trata-se de uma decomposição especial em que um softgoal é refinado em outro do mesmo tipo e tópico, mas com a adição de um critério de prioridade. Essa abordagem permite destacar a relevância relativa de diferentes metas.

Essas decomposições são representadas graficamente nos modelos do NFR Framework por meio de conexões entre nós (softgoals), utilizando-se setas e operadores lógicos (como AND/OR) para indicar a natureza da decomposição.

<p style="text-align: center"><b>Figura 2</b> - Tipos de decomposição </p>

![decomposicao-nfr](../assets/nfr/decomposicao-nfr.png)


<font size="3"><p style="text-align: center">Fonte: Silva, 2019.</p></font>


### Contribuições

No NFR Framework, os softgoals são progressivamente refinados em metas mais específicas. Como resultado, um softgoal derivado pode contribuir de forma total ou parcial — e tanto positiva quanto negativamente — para o softgoal original. A seguir, listam-se os tipos de contribuição:

- AND: se os softgoals derivados forem satisfeitos, o softgoal primordial também será.
- OR: se algum dos softgoals derivados forem satisfeitos, o softgoal primordial também será.
- MAKE(++): um softgoal originado contribui de forma plenamente positiva, logo o softgoal original também será satisfeito.
- BREAK(--): um softgoal originado contribui de forma plenamente negativa, logo o softgoal original será negado.
- HELP(+): um softgoal originado realiza uma contribuição restritamente positiva, o que reflete da mesma forma e na mesma intensidade no softgoal primordial.
- HURT(-): um softgoal originado realiza uma contribuição restritamente negativa, o que reflete da mesma forma e na mesma intensidade no softgoal primordial.
- UNKNOWN(?): contribuição incógnita.
- EQUALS: relação direta entre as satisfações do softgoal derivado e a do primordial.
- SOME: a forma de contribuição é conhecida, no entanto, a intensidade dessa contribuição é desconhecida.

---

## Metodologia

Neste projeto, o NFR Framework é aplicado à modelagem de requisitos não-funcionais de um sistema da Receita Federal, priorizando atributos como segurança, acessibilidade e usabilidade. Os requisitos foram extraídos com base no modelo **FURPS+**.

> **Nota**: O modelo **FURPS+** é uma sigla usada para classificar requisitos de software. Significa: **F**uncionalidade, **U**sabilidade, **R**eliabilidade (confiabilidade), **P**erformance (desempenho), **S**uportabilidade e o **+** para outros requisitos complementares como legais ou de hardware.

Para cada RNF, são apresentados:

* Um **SIG (Softgoal Interdependency Graph)**
* A **propagação de impactos**
* Um **cartão de especificação detalhado**

> **Nota**: A **propagação de impactos** mostra como um requisito pode influenciar outros, positiva ou negativamente. Isso ajuda a evitar conflitos e entender efeitos colaterais.

> **Nota**: O **cartão de especificação** é uma ficha padronizada que documenta cada requisito não-funcional com campos como ID, prioridade, origem e justificativa.

---

## NFR01 - Acessibilidade

A acessibilidade está relacionada à capacidade do sistema de ser utilizado por **usuários idosos**, com possíveis limitações visuais, motoras ou cognitivas.

### Softgoal Interdependency Graph

*(Inserir diagrama SIG específico aqui)*

### Propagação de Impactos

*(Inserir análise de impactos: como a acessibilidade influencia outros requisitos e é influenciada por eles)*

### Cartão de Especificação

| Info          | Detalhes                                                                                                                     |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| ID NFR        | NFR01                                                                                                                        |
| Classificação | Acessibilidade                                                                                                               |
| Descrição     | Refere-se à capacidade do sistema de atender usuários idosos                                                                 |
| Justificativa | Um sistema acessível para idosos promove inclusão digital e garante maior alcance da população atendida pela Receita Federal |
| Origem        | Especificação suplementar e requisitos elicitados                                                                            |
| Dependências  | Usabilidade (interface clara e intuitiva é essencial para acessibilidade)                                                    |
| Prioridade    | Alta                                                                                                                         |
| Conflitos     | Nenhum identificado                                                                                                          |
| História      | 29/05/2025                                                                                                                   |

---

## NFR02 - Segurança

A segurança trata da proteção dos dados dos usuários e da integridade das informações do sistema.

### Softgoal Interdependency Graph

*(Inserir diagrama SIG específico aqui)*

### Propagação de Impactos

*(Inserir análise dos efeitos da segurança em outras áreas, como desempenho ou usabilidade)*

### Cartão de Especificação

| Info          | Detalhes                                                                           |
| ------------- | ---------------------------------------------------------------------------------- |
| ID NFR        | NFR02                                                                              |
| Classificação | Segurança                                                                          |
| Descrição     | Garante que os dados dos usuários estão protegidos contra acessos indevidos.       |
| Justificativa | Sistemas que tratam dados pessoais devem garantir confidencialidade e integridade. |
| Origem        | Especificação suplementar e requisitos elicitados                                  |
| Dependências  | Privacidade (depende da implementação de segurança para proteção de dados)         |
| Prioridade    | Alta                                                                               |
| Conflitos     | Nenhum identificado                                                                |
| História      | 29/05/2025                                                                         |

---

## Referência

SILVA, Reinaldo Antônio da. *NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados*. Recife: Universidade Federal de Pernambuco, 2019.
Disponível em: [https://aprender3.unb.br/pluginfile.php/3096155/mod\_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf](https://aprender3.unb.br/pluginfile.php/3096155/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf)

## Histórico de Versão

| Versão | Data       | Descrição                          | Autor                                          | Revisor                                     |
| ------ | ---------- | ---------------------------------- | ---------------------------------------------- | ------------------------------------------- |
| `1.0`     | 29/05/2025 | Criação do documento NRF-framework | [Thales Germano](https://github.com/thalesgvl) | [Jose Eduardo](https://github.com/jevprado) |
| `1.1`    | 29/05/2025 | Ajustes no documento | [Thales Germano](https://github.com/thalesgvl) |[Jose Eduardo](https://github.com/jevprado)|
| `1.2`    | 01/06/2025 | Adicionando imagens e tópicos decomposição e contribuição | [Jose Eduardo](https://github.com/jevprado) | [Thales Germano](https://github.com/thalesgvl) |