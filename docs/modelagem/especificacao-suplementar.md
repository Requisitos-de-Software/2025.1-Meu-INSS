# Especificação Suplementar

## Introdução

A Especificação Suplementar é um documento textual que detalha requisitos do sistema não contemplados em casos de uso. Entre eles estão requisitos legais, regulatórios, atributos de qualidade, padrões técnicos, desempenho, suportabilidade e restrições de design. Esta especificação utiliza a metodologia FURPS+, adaptada para o escopo do aplicativo da Receita Federal.

## Finalidade

Este documento tem como finalidade detalhar os requisitos suplementares do aplicativo da Receita Federal, que visa facilitar o acesso do cidadão a serviços fiscais e tributários por meio de dispositivos móveis.

## Escopo

O aplicativo da Receita Federal tem como escopo principal permitir que os usuários consultem sua situação fiscal, CPF, restituições, declarações, e autentiquem documentos digitais. O sistema deve integrar-se com bases de dados internas da Receita e seguir diretrizes de segurança da informação.

## Metodologia

Utilizaremos uma versão adaptada do modelo FURPS+, categorizando os requisitos em:

- *F* - Funcionalidade
- *U* - Usabilidade
- *R* - Confiabilidade
- *P* - Desempenho
- *S* - Suportabilidade
- *+* - Outros (restrições de design, requisitos legais, físicos etc.)

---

## Funcionalidade

Os requisitos funcionais estão descritos nos casos de uso e documentos de elicitação, como:

- Consultar CPF e CNPJ
- Acompanhar restituições do IRPF
- Autenticar documentos e gerar comprovantes
- Acessar notificações e pendências fiscais

---

## Usabilidade

| ID     | Descrição |
|--------|-----------|
| USA01 | O app deve possuir suporte a alto contraste, modo escuro e leitura por voz. |
| USA02 | Deve permitir navegação acessível com leitor de tela e teclas de acessibilidade. |
| USA03 | O sistema deve dar feedback imediato sobre validações e erros nos formulários. |
| USA04 | A navegação principal deve ser concluída com no máximo 5 cliques. |
| USA05 | O app deve estar disponível nos idiomas Português e Inglês. |

---

## Confiabilidade

| ID     | Descrição |
|--------|-----------|
| CON01 | O sistema deve estar disponível 99,9% do tempo. |
| CON02 | Deve proteger os dados do usuário conforme a LGPD. |
| CON03 | As informações exibidas devem ser consistentes com os dados armazenados internamente. |
| CON04 | Deve permitir a recuperação da sessão em caso de falha de conexão. |
| CON05 | O sistema deve registrar logs de todas as transações para auditoria. |

---

## Desempenho

| ID     | Descrição |
|--------|-----------|
| DES01 | O tempo de resposta médio do app não deve ultrapassar 300ms. |
| DES02 | O login com autenticação biométrica deve ocorrer em até 2 segundos. |
| DES03 | A consulta ao CPF deve retornar em até 1 segundo. |
| DES04 | O app deve suportar picos de até 500 mil acessos simultâneos. |

---

## Suportabilidade

| ID     | Descrição |
|--------|-----------|
| SUP01 | O sistema deve ter documentação técnica e manual do usuário atualizados. |
| SUP02 | O código deve ser modular e permitir manutenções independentes. |
| SUP03 | Atualizações devem ser feitas sem interromper os serviços principais. |
| SUP04 | O app deve possuir sistema de suporte ao usuário integrado. |
| SUP05 | Deve ser possível rastrear alterações feitas no histórico de declarações. |

---

## Restrições de Design

- A interface deve seguir os padrões da identidade visual do Governo Federal.
- O design deve atender aos padrões de acessibilidade da WCAG 2.1.
- O app deve ser responsivo e funcional em dispositivos móveis Android e iOS.

---

## Requisitos de Implementação

- Linguagens: Kotlin (Android), Swift (iOS), TypeScript (para serviços web).
- Plataformas: Android 8.0+ e iOS 12.0+.
- Armazenamento mínimo: 100MB.
- RAM recomendada: 2GB.

---

## Sistema de Ajuda e Documentação

| ID     | Descrição |
|--------|-----------|
| RAU01 | O app deve conter seção de perguntas frequentes. |
| RAU02 | O tempo de resposta a uma solicitação de suporte deve ser de no máximo 48h. |
| RAU03 | O sistema deve permitir resolução automatizada de problemas comuns, como redefinir senha. |

---

## Requisitos de Licenciamento

O app deve apresentar e exigir a aceitação dos Termos de Uso e da Política de Privacidade antes da primeira utilização.

---

## Observações Legais

- O app deve obedecer à LGPD (Lei Geral de Proteção de Dados).
- Os dados dos contribuintes não devem ser compartilhados com terceiros sem consentimento.
- A Receita Federal é responsável pelo armazenamento e proteção das informações fiscais.

---

## Padrões Aplicáveis

O sistema deve atender aos seguintes padrões:

- WCAG 2.1 (Acessibilidade)
- ISO 27001 (Segurança da Informação)
- ISO/IEC 25010 (Qualidade de Software)
- Padrões da Receita Federal para APIs REST e autenticação digital

---

## Requisitos Físicos

- Compatibilidade com smartphones e tablets.
- Funcionalidade garantida em conexão 3G, 4G, 5G e Wi-Fi.

---

 ---
 ## Historico de versões

Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
1.0 | 11/05/2025 | Criação do documento |[João Pedro](https://github.com/JpRodrigues2)  | [José Eduardo](https://github.com/jevprado) |
