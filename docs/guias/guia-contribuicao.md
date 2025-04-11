# Guia de contribuição 

Guia de contribuição para o projeto 2025.1-Meu INSS, da disciplina de Requisitos de Software. Leia a documentação antes de qualquer contribuição.

## Como contribuir 

Índice:

1. [Como criar uma issue](#politica-de-issues)
2. [Como criar sua branch](#politica-de-branches)
3. [Politica de PRs](#politica-de-pull-requests)

## Politica de issues

As issues devem ser criadas no [repositório do projeto](https://github.com/Requisitos-de-Software/2025.1-Meu-INSS/issues).

As issues devem seguir o template localizado no [repositório do projeto](https://github.com/Requisitos-de-Software/2025.1-Meu-INSS/tree/main/.github/issue_template/issue-template.md).

### Labels

Na criação de uma issue, utilize os seguintes rótulos abaixo para classificá-la e facilitar a identificação:

#### Tipo da issue:
- **Docs**: melhorias ou estruturação da documentação.
- **Feature**: novo requisito funcional.
- **Bug**: erro ou inconsistência na documentação.
- **Non-Functional**: novo requisito não funcional.
- **User Story (US)**: história de usuário.
- **Use Case**: caso de uso.

#### Status:
- **To Review**: pronta para revisão.
- **Approved**: validada.
- **Needs Discussion**: requer alinhamento.
- **Blocked**: impedida por dependência.

#### Dificuldade:
- **Easy**: dificuldade baixa.
- **Medium**: dificuldade média.
- **Hard**: dificuldade alta.

#### Outros:
- **UX**: relacionada à experiência do usuário.


## Politica de branches

### Repositórios de desenvolvimento

#### main

A branch **main** é a branch padrão que está sempre atualizada. Essa branch é protegida de commits e para o desenvolvimento de novas funcionalidades, deve receber Pull Requests (PRs).

#### Novas branches

As branches para o desenvolvimento de novas features devem ser criadas a partir da branch **main** e devem seguir o padrão **docs/x/y**, onde x é o nome da atividade trabalhada, e y a atividade específica.  
Ex: **docs/planejamento/cronograma**

Os Pull Requests das novas branches devem ser feitos para a branch **main**.

Antes de criar uma nova branch, certifique-se de atualizar sua branch **main** local com o comando:

```
git pull origin main
```

## Politica de pull requests

Os Pull Requestem devem ser feitos para a branch **main**.

Os Pull Requests seguir o template localizado no [repositório do projeto](https://github.com/Requisitos-de-Software/2025.1-Meu-INSS/tree/main/.github/pr_template/pr-template.md).


Em PRs em que ainda estão sendo desenvolvidos, adicione **WIP** antes do nome do PR. 


Versão |   Data  | Descrição | Autor(es)
------ | ---- | ------ | ---------- 
1.0 | 11/04/2025 | Criação do documento | [Jose Eduardo](https://github.com/jevprado) 