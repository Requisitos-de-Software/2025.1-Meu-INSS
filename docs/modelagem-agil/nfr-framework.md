# NFR Framework

## Introdução

De acordo com a abordagem apresentada por **Reinaldo Antônio da Silva (2019)**, o NFR Framework é um modelo utilizado na modelagem de Requisitos Não-Funcionais (RNFs), baseado em *softgoals*. Esses objetivos não possuem uma definição clara ou critérios de sucesso bem estabelecidos, o que os torna ideais para representar qualidades subjetivas dos sistemas.

Os *softgoals* ajudam desenvolvedores a tomar decisões durante o projeto, considerando aspectos como qualidade, segurança e desempenho. Além disso, podem influenciar uns aos outros, criando uma rede de impactos que afetam o sistema como um todo.

### Tipos de Softgoals

Os *softgoals* podem ser classificados em três grupos principais, conforme descrito por **Reinaldo Antônio da Silva**:

1. **Softgoals NFR**: Representam diretamente os Requisitos Não-Funcionais e podem ser organizados de forma hierárquica.
2. **Softgoals de Operacionalização**: Apontam para alternativas de implementação dos softgoals NFR, por meio de funções, estruturas ou restrições.
3. **Softgoals de Afirmação**: Representam justificativas baseadas em conhecimento de domínio ou prioridades, servindo como base para apoiar ou refutar decisões de projeto e seleção de alternativas.

O atendimento aos *softgoals* é avaliado qualitativamente por meio de rótulos como **satisfeito**, **parcialmente satisfeito** ou **não satisfeito**, com base nas contribuições positivas ou negativas entre os nós no **Softgoal Interdependency Graph (SIG)**.

> **Nota**: O *Softgoal Interdependency Graph (SIG)* é um grafo que mostra como diferentes objetivos não-funcionais estão inter-relacionados, ajudando a visualizar conflitos e sinergias entre eles.

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
| 1.0    | 29/05/2025 | Criação do documento NRF-framework | [Thales Germano](https://github.com/thalesgvl) | [Jose Eduardo](https://github.com/jevprado) |
| 1.1    | 29/05/2025 | Ajustes no documento | [Thales Germano](https://github.com/thalesgvl) |Revisor aqui |
