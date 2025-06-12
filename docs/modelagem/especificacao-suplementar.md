## Introdução 

Este documento apresenta a Especificação Suplementar, que trata-se de um documento em linguagem natural, no qual são 
descritos os requisitos não funcionais do aplicativo da Receita Federal. Dentre as categorias detalhadas estão: Acessibilidade, restrições de design, requisitos de implementação, sistema de ajuda e documentação, requisitos de licenciamento, observações legais, padrões aplicáveis e requisitos físicos. 

## Tabela de atividades feitas - por membro

<p style="text-align: center"><b>Tabela 1</b> - Atividades por membro</p>

|Nome                                                | Atividade entregue                        | 
| -------------------------------------------------- | ----------------------------------------- | 
| [João Pedro](https://github.com/JpRodrigues2)    |    Introdução e Metodologia                                       | 
| [José Eduardo](https://github.com/jevprado) |  Metodologia, criação da tabela 01, 02, 03, 04 e 05 e produção dos tópicos com código (+)        | 


<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>

## Metodologia 

A classificação e organização dos requisitos foi realizada com base na metodologia **FURPS+**, que compreende:

- **Funcionalidade**: segurança, interoperabilidade, regras de negócio.

- **Usabilidade**: acessibilidade, clareza, suporte a idosos, modo escuro.

- **Confiabilidade (Reliability)**: disponibilidade, robustez, recuperação de falhas.

- **Desempenho (Performace)**: tempo de resposta, suporte a alta demanda, desempenho offline.

- **Suportabilidade**: compatibilidade com dispositivos, manutenção, testes.

- **+**: requisitos legais (LGPD), acessibilidade avançada, aspectos técnicos complementares.


## Classificação dos Requisitos Não Funcionais 

Abaixo, a divisão dos Requisitos Não Funcionais, divididos por tabelas, seguindo a classificação da metodologia **FURPS+**. 

### Usabilidade (U):

<p style="text-align: center"><b>Tabela 1</b> - Tabela da usabilidade </p>

| ID    | Descrição                                                                       | Rastreabilidade            | Codigo |
| ----- | ------------------------------------------------------------------------------- | -------------------------- | ------ | 
| RNF1  | Acessibilidade (chatbot, imagens, vídeos) — melhorias no chatbot                |  [ADC13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)                                                                                                  | USA 01 |
| RNF2  | Conteúdo educativo para iniciantes                                              |  [ADC14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) e [ST08](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/) | USA 02 |
| RNF6  | Interface com a possibilidade de uso do modo escuro                             |  [ADC23](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [INT17](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/) e [ST11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)                                                                                                                                                                 | USA 03 |
| RNF9  | Testes de usabilidade semestrais com público 60+                                | [ADC21](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)                                                                                                                                                                                         | USA 04 |
| RNF12 | Linguagem da interface deve seguir padrão A2 do CEFR, evitando jargões técnicos | [ADC25](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)                                                                                                                                                                        | USA 05 |
| RNF20 | Clareza na apresentação de dados fiscais                                        |  [ST12](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)                                                                                                                                                                                            | USA 06 |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado) 2025.</p></font>

### Confiabilidade (R): 

<p style="text-align: center"><b>Tabela 2</b> - Tabela da confiabilidade </p>

| ID    | Descrição                                                                       | Rastreabilidade            | Codigo |
| ----- | ------------------------------------------------------------------------------- | -------------------------- | ------ | 
| RNF4  | Proteção de dados pessoais conforme a LGPD                                      | [ADC17](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) | CON01 |
| RNF7  | Testes de segurança para garantir a integridade dos dados e autenticação segura |  [ADC19](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) | CON02 |
| RNF14 | Atualizações do app não devem causar perda de dados armazenados localmente      |  [INT12](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/) | CON03 |
| RNF18 | Armazenamento anônimo de logs de erro respeitando a LGPD                        |  [INT15](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/) | CON04 |
| RNF21 | Integração confiável com serviços externos (Gov.br, instituições financeiras)   |  [ST13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)      | CON05 |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado) 2025.</p></font>


### Desempenho (P): 

<p style="text-align: center"><b>Tabela 3</b> - Tabela de desempenho </p>

| ID    | Descrição                                                                       | Rastreabilidade            | Codigo |
| ----- | ------------------------------------------------------------------------------- | -------------------------- | ------ | 
| RNF3  | Testes de desempenho para suportar alta demanda de usuários simultâneos | [ADC15](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) | DES01 |
| RNF10 | Tempo de resposta inferior a 3 segundos para ações comuns               | [INT9](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)  | DES02 |
| RNF13 | Suporte offline com cache de dados essenciais em baixa conectividade    |  [INT11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/) | DES03 |
| RNF15 | Tempo de inatividade programada máximo de 2h por mês, com aviso prévio  |  [INT13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)| DES04 |
| RNF16 | Carregamento inicial inferior a 5 segundos em conexão móvel             |  [ADC24](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) | DES05 |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado) 2025.</p></font>

### Suportabilidade (S): 

<p style="text-align: center"><b>Tabela 4</b> - Tabela de suportabilidade </p>

| ID    | Descrição                                                                       | Rastreabilidade            | Codigo |
| ----- | ------------------------------------------------------------------------------- | -------------------------- | ------ | 
| RNF5  | Interface responsiva e acessível                              |  [ADC18](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)   | SUP01 |
| RNF8  | Compatível com Android 8+ e iOS 14+                           |  [ADC20](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)  | SUP02 |
| RNF11 | Funciona em smartphones de 4.5" a 7" sem perda de usabilidade |  [INT10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)   | SUP03 |
| RNF19 | Versão mínima em HTML5 responsiva em caso de falha do app     | [INT16](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)  | SUP04 |


<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado) 2025.</p></font>


### Acessibilidade (+): 

<p style="text-align: center"><b>Tabela 5</b> - Tabela de suportabilidade </p>

| ID    | Descrição                                                                       | Rastreabilidade            | Codigo |
| ----- | ------------------------------------------------------------------------------- | -------------------------- | ------ | 
| RNF17 | Suporte a leitores de tela (TalkBack, VoiceOver) em todas as funcionalidades                            |  [INT14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/) e [ADC22](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)   | AC01 |


<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado) 2025.</p></font>


### Restrições de Design (+): 

- A interface deve seguir os padrões da identidade visual do Governo Federal.
- O design deve atender aos padrões de acessibilidade da WCAG 2.1.
- O app deve ser responsivo e funcional em dispositivos móveis Android e iOS.

---

### Requisitos de Implementação (+): 

- Linguagens: Kotlin (Android), Swift (iOS), TypeScript (para serviços web).
- Plataformas: Android 8.0+ e iOS 12.0+.
- Armazenamento mínimo: 100MB.
- RAM recomendada: 2GB.

### Sistema de Ajuda e Documentação (+): 

- O app deve conter seção de perguntas frequentes. |
- O tempo de resposta a uma solicitação de suporte deve ser de no máximo 48h. 
- O sistema deve permitir resolução automatizada de problemas comuns, como redefinir senha. 

### Requisitos de Licenciamento (+): 

- O app deve apresentar e exigir a aceitação dos Termos de Uso e da Política de Privacidade antes da primeira utilização.

### Observações Legais (+): 

- O app deve obedecer à LGPD (Lei Geral de Proteção de Dados).
- Os dados dos contribuintes não devem ser compartilhados com terceiros sem consentimento.
- A Receita Federal é responsável pelo armazenamento e proteção das informações fiscais.


### Padrões Aplicáveis (+): 

O sistema deve atender aos seguintes padrões:

- WCAG 2.1 (Acessibilidade)
- ISO 27001 (Segurança da Informação)
- ISO/IEC 25010 (Qualidade de Software)
- Padrões da Receita Federal para APIs REST e autenticação digital


### Requisitos Físicos (+): 

- Compatibilidade com smartphones e tablets.
- Funcionalidade garantida em conexão 3G, 4G, 5G e Wi-Fi.


## Referencias

> <a>1.</a> Sommerville, Ian. Engenharia de Software. 10ª ed. São Paulo, 2019.  
>
> <a>2.</a> Pressman, Roger S.; Maxim, Bruce R. Engenharia de Software: Uma Abordagem Profissional. 8ª ed. Porto Alegre: AMGH, 2016.  
>
> <a>3.</a> ISO/IEC 25010. Systems and software engineering — Systems and software Quality Requirements and Evaluation (SQuaRE) — System and software quality models. International Organization for Standardization, 2011.  
>
> <a>4.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13. UnB, 2025. Disponível em: [https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf](https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf). Acesso em: 07 de junho 2025.
>
> <a>5.</a> W3C – World Wide Web Consortium. Web Content Accessibility Guidelines (WCAG) 2.1, 2018. Disponível em: [https://www.w3.org/TR/WCAG21/](https://www.w3.org/TR/WCAG21/)  
>
> <a>6.</a> Brasil. Lei nº 13.709, de 14 de agosto de 2018 – Lei Geral de Proteção de Dados Pessoais (LGPD). Disponível em: [https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm)

## Historico de versões

Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
`1.0` | 11/05/2025 | Criação do documento de especificacao suplementar |[João Pedro](https://github.com/JpRodrigues2)  | [José Eduardo](https://github.com/jevprado) |
`2.0` | 07/06/2025 | Correções na especificação suplementar | [José Eduardo](https://github.com/jevprado) | [Diassis](https://github.com/Diaxiz) |
`2.1` | 08/06/2025 | Adicionando códigos individuais | [José Eduardo](https://github.com/jevprado) | [Diassis](https://github.com/Diaxiz) |
| `2.2`  | 12/06/2025 | Adição da tabela de atividade dos membros | [Jose Eduardo](https://github.com/jevprado) | [Diassis](https://github.com/Diaxiz) |

