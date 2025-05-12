# First Things First

## 1. Introdução

O First Things First (FTF) é uma técnica de priorização de requisitos que visa equilibrar, definir, alinhar e estabelecer as tarefas que devem ser feitas, dividindo-as entre mais e menos importantes. A abordagem busca avaliar o valor agregado de cada requisito, sua penalidade em caso de ausência, bem como os custos e riscos de implementação, considerando a complexidade técnica e as incertezas do projeto.

---

## 2. Metodologia

A priorização seguiu uma sequência estruturada de etapas para garantir uma análise objetiva e equilibrada dos requisitos:

1. Inicialmente, todos os requisitos identificados foram avaliados, removendo-se aqueles que eram dependentes diretos de outros — ou seja, se um requisito só poderia ser implementado após outro, apenas o principal foi considerado.

2. Em seguida, o usuário avaliou cada requisito, dando uma nota para os seguintes critérios:

   * **Benefício**: grau de valor agregado ao sistema, variando de 1 (baixo) a 9 (alto).
   * **Penalidade**: impacto negativo da ausência do requisito, também de 1 a 9.

3. Com essas notas, foi calculado um **valor total** para cada requisito, de acordo com a seguinte equação:

   ```
   valor total = (benefício × peso) + (penalidade × peso)
   ```

4. A equipe de desenvolvimento atribuiu notas de 1 a 9 para os seguintes aspectos:

   * **Custo**: nível de esforço necessário para implementação, considerando complexidade, integrações e testes.
   * **Risco**: probabilidade de desafios técnicos, falta de conhecimento, ou inviabilidade no prazo.

5. Após isso, todos os valores foram transformados em percentuais, e a **prioridade final** de cada requisito foi calculada com a fórmula abaixo:

   ```
   prioridade = valor(%) / (custo(%) × peso do custo + risco(%) × peso do risco)
   ```

6. Por fim, os requisitos foram organizados por ordem decrescente de prioridade, o que ajudou a destacar aqueles com maior retorno e menor esforço técnico envolvido.

## 3. First Things First

### 3.1 Descrição dos Requisitos
Tabela 1 - Descrição dos Requisitos coletados.

| ID  | Descrição                                                                                  |
| --- | ------------------------------------------------------------------------------------------ |
| r1  | Acesso rápido e simultâneo a múltiplos CPFs/CNPJs                                          |
| r2  | Cadastro de CPF via app (totalmente remoto)                                                |
| r3  | Acompanhamento de status da restituição (com precisão quanto aos lotes)                    |
| r4  | Notificação de vencimento próximo                                                          |
| r5  | Unificação de serviços no app (agendamento, certidões, acompanhamento de processos etc.)   |
| r6  | Acesso offline a serviços essencial do app (históricos de contribuições anteriores, darfs) |
| r7  | Alteração de dados via app                                                                 |
| r8  | Funcionalidade de histórico e acompanhamento de restituições e de declarações              |
| r9  | Declaração simplificada do IR                                                              |
| r10 | Geração de guias de pagamento                                                              |
| r11 | Consultar o status do CPF (ativo ou não)                                                   |
| r12 | Integração com conta Gov.br                                                                |
| r13 | Acessibilidade (chatbot, imagens, vídeos) — melhorias no chatbot sugeridas                 |
| r14 | Conteúdo educativo para iniciantes                                                         |
| r15 | Testes de desempenho para suportar alta demanda de usuários simultâneos                    |
| r16 | Envio de documentos para instrução de processos                                            |
| r17 | Proteção de dados pessoais conforme a LGPD                                                 |
| r18 | Interface responsiva para dispositivos móveis                                              |
| r19 | Testes de segurança para garantir a integridade dos dados e autenticação segura            |
_Fonte - Autores._


### Resultados da Priorização FTF
Tabela 2 - Resultados da Priorização utilizando First Things First (FTF)

| Funcionalidade | Benefício Relativo | Penalidade Relativa | Valor Total | Valor (%) | Custo Relativo | Custo (%) | Risco Relativo | Risco (%) | Prioridade |
|----------------|---------------------|----------------------|-------------|-----------|----------------|-----------|----------------|-----------|------------|
| r1             | 9                   | 9                    | 27          | 6.68      | 2.5            | 2.89      | 2.5            | 3.36      | 2.055      |
| r2             | 8                   | 8                    | 27          | 6.68      | 6.0            | 6.94      | 3.3            | 4.46      | 1.095      |
| r3             | 9                   | 9                    | 27          | 6.68      | 3.0            | 3.47      | 2.5            | 3.36      | 2.009      |
| r4             | 8                   | 8                    | 24          | 5.94      | 3.5            | 4.05      | 3.3            | 4.46      | 1.456      |
| r5             | 8                   | 7                    | 23          | 5.69      | 2.5            | 2.89      | 2.5            | 3.36      | 2.055      |
| r6             | 8                   | 7                    | 23          | 5.69      | 5.0            | 5.79      | 3.3            | 4.46      | 1.062      |
| r7             | 8                   | 6                    | 22          | 5.45      | 5.0            | 5.79      | 3.3            | 4.46      | 1.017      |
| r8             | 9                   | 8                    | 26          | 6.43      | 6.0            | 6.94      | 4.2            | 5.59      | 0.957      |
| r9             | 8                   | 6                    | 22          | 5.45      | 5.5            | 6.37      | 3.3            | 4.46      | 0.973      |
| r10            | 8                   | 7                    | 23          | 5.69      | 2.5            | 2.89      | 3.6            | 4.91      | 1.589      |
| r11            | 6                   | 5                    | 17          | 4.21      | 3.5            | 4.62      | 2.5            | 3.36      | 1.050      |
| r12            | 7                   | 6                    | 20          | 4.95      | 2.5            | 2.89      | 2.5            | 3.36      | 2.055      |
| r13            | 6                   | 5                    | 17          | 4.21      | 5.0            | 5.79      | 3.3            | 4.46      | 0.818      |
| r14            | 7                   | 6                    | 20          | 4.95      | 3.5            | 4.62      | 3.3            | 4.46      | 1.087      |
| r15            | 6                   | 5                    | 17          | 4.21      | 4.0            | 5.21      | 4.2            | 5.59      | 0.777      |
| r16            | 6                   | 5                    | 17          | 4.21      | 6.0            | 6.94      | 4.2            | 5.59      | 0.691      |
| r17            | 5                   | 4                    | 14          | 3.47      | 3.5            | 4.05      | 2.8            | 3.76      | 0.856      |
| r18            | 7                   | 6                    | 20          | 4.95      | 3.5            | 4.05      | 3.3            | 4.46      | 1.170      |
| r19            | 6                   | 5                    | 17          | 4.21      | 4.0            | 5.21      | 4.2            | 5.59      | 0.777      |
| **Total**      |                     |                      | **439**     | **100**   | **86.5**       | **100**    | **74.4**       | **100**    |            |
_Fonte - Autores._


## 4. Referências

> WIEGERS, Karl E.; BEATTY, Joy. *Software Requirements*. 3. ed. Microsoft Press, 2013. cap. 16, p. 313–329.

## 5. Histórico de versões

| Versão | Data       | Autor(es)          | Alterações                                             | Revisor(es) |
| :----: | ---------- | ------------------ | ------------------------------------------------------ | ----------- |
|   1.0  | 03/05/2025 | [Diassis](https://github.com/Diaxiz) e [Marco](https://github.com/marcomarquesdc)  | Primeira Versão do FTF | [José Eduardo](https://github.com/jevprado)   |
|   1.1  | 03/05/2025 | [Diassis](https://github.com/Diaxiz) e [Marco](https://github.com/marcomarquesdc)  | Correção no texto | [José Eduardo](https://github.com/jevprado)   |
|   1.2  | 11/05/2025 | [Diassis](https://github.com/Diaxiz) e [Marco](https://github.com/marcomarquesdc)  | Correção no texto | [José Eduardo](https://github.com/jevprado)   |



