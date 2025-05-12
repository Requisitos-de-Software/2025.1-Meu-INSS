# Diagrama de Casos de Uso e Lista de Verificação  
## Aplicativo da Receita Federal  

---

## I. Contexto do Aplicativo  

O aplicativo da Receita Federal (como o app Pessoa Física ou o e-CAC) permite que contribuintes acessem serviços fiscais como:  
- Consulta de situação fiscal  
- Entrega de declarações  
- Emissão de comprovantes  
- Pagamento de tributos  

Este documento foca em funcionalidades típicas para o cidadão usuário do app.

---

## II. Elementos do Diagrama  

### 1. Sistema  
**Nome:** Aplicativo da Receita Federal do Brasil  
**Descrição:** Plataforma digital que permite aos usuários realizar operações fiscais, consultar informações tributárias e interagir com a Receita Federal remotamente.  
Representado por um **retângulo** no diagrama.

### 2. Atores  
- **Contribuinte Pessoa Física:** Cidadão que usa o app para declarar IR, consultar restituição, pagar DARF etc.  
- **Contribuinte Pessoa Jurídica:** Empresa que acessa o e-CAC.  
- **Receita Federal (Sistema Interno):** Valida e processa dados.  
- **Bancos (Sistema Externo):** Processam pagamentos.  
- **Administrador:** Funcionário da Receita que gerencia o sistema.  

Para este trabalho, consideramos:  
- **Ator primário:** Contribuinte pessoa física  
- **Ator secundário:** Servidor – auditor fiscal  

### 3. Casos de Uso (Exemplos)
- **Consultar Situação Fiscal**  
- **Enviar Declaração IRPF**  
- **Consultar Restituição**  
- **Pagar DARF**  
- **Agendar Atendimento**  
- **Emitir Certidão Negativa**  
- **Autenticar Usuário**  

### 4. Relacionamentos  
- **Associação:** Ex: Contribuinte → Consultar Situação Fiscal  
- **Inclusão (`<<include>>`)**  
- **Extensão (`<<extend>>`)**  
- **Generalização:** *Não utilizada neste caso*

---

## III. Descrição Geral do Diagrama  

- O **Contribuinte** interage com o sistema para realizar todos os casos de uso.  
- O **Servidor da Receita Federal** valida e processa dados.  
- **Autenticação** é pré-requisito para diversos serviços.  

---

## IV. Lista de Verificação (Checklist)

### SISTEMA  
- [ ] O sistema é representado por um retângulo?  
- [ ] O sistema tem título no topo?  
- [ ] Todas as funcionalidades estão dentro do retângulo?  
- [ ] Tudo fora do retângulo ocorre fora do app?

### ATORES  
- [ ] O ator contribuinte interage com o app?  
- [ ] O ator servidor interage com o app?  
- [ ] O ator primário está à esquerda?  
- [ ] O ator secundário está à direita?

### CASOS DE USO

#### A. Autenticação

##### A.1 Realizar Login  
- [ ] Login com CPF  
- [ ] Login com certificado digital  
- [ ] Login com conta Gov.br  
- [ ] Segurança adequada aos serviços  
- [ ] Bloqueio após tentativas inválidas  
- [ ] Armazenamento seguro de credenciais

##### A.2 Recuperar Senha  
- [ ] Recuperação por e-mail  
- [ ] Recuperação por SMS  
- [ ] Validação de dados pessoais  
- [ ] Link de recuperação com expiração

##### A.3 Validar Acesso via Gov.br  
- [ ] Integração com Gov.br  
- [ ] Reconhecimento de níveis de autenticação  
- [ ] Redirecionamento pós-login  
- [ ] Transmissão segura de dados

---

#### B. Consultas Gerais

##### Consultar Situação Fiscal  
- [ ] Exibição de pendências  
- [ ] Visualização de extrato  
- [ ] Detalhamento de débitos  
- [ ] Status em tempo real  
- [ ] Download de relatório

##### Atualizar Dados Cadastrais  
- [ ] Alterar endereço  
- [ ] Alterar contatos (email/telefone)  
- [ ] Alterar dados bancários  
- [ ] Confirmação por e-mail/SMS  
- [ ] Proteção contra alterações indevidas

##### Consultar Processos  
- [ ] Lista de processos  
- [ ] Detalhes do processo  
- [ ] Notificações de atualizações  
- [ ] Histórico de movimentações  
- [ ] Download de documentos

---

#### C. Agendar Atendimento  
- [ ] Disponibilidade de datas/horários  
- [ ] Escolha de unidades  
- [ ] Confirmação de agendamento  
- [ ] Cancelamento e remarcação  
- [ ] Lembretes automáticos

---

#### D. Pagar Tributos  
- [ ] Lista de tributos pendentes  
- [ ] Integração com bancos  
- [ ] Histórico de pagamentos  
- [ ] Parcelamento de débitos  
- [ ] Emissão de comprovante

---

#### E. Declaração de Imposto de Renda

##### G.1 Preencher Declaração  
- [ ] Importar dados do ano anterior  
- [ ] Dados pré-preenchidos  
- [ ] Importar fontes pagadoras  
- [ ] Bens e direitos  
- [ ] Dependentes  
- [ ] Cálculo de deduções  
- [ ] Verificação de inconsistências

##### G.2 Enviar Declaração  
- [ ] Transmissão segura  
- [ ] Recebimento de protocolo  
- [ ] Confirmação pela Receita  
- [ ] Status de processamento  
- [ ] Desempenho de envio

##### G.3 Consultar Recibo  
- [ ] Visualizar recibo  
- [ ] Baixar em PDF  
- [ ] Compartilhar recibo  
- [ ] Histórico de recibos

---

#### H. Restituição de IR

##### H.1 Consultar Lotes  
- [ ] Cronograma de lotes  
- [ ] Consulta por CPF  
- [ ] Valor e data do pagamento  
- [ ] Status de análise  
- [ ] Notificações de liberação

##### H.2 Atualizar Dados Bancários  
- [ ] Alterar conta para crédito  
- [ ] Validação de dados bancários  
- [ ] Confirmação da alteração  
- [ ] Histórico de alterações

##### H.3 Emitir Comprovante  
- [ ] Geração de comprovante  
- [ ] Baixar PDF  
- [ ] Validação fiscal  
- [ ] Compartilhamento  
- [ ] Histórico de comprovantes

---

#### I. Segurança  
- [ ] Proteção de dados locais  
- [ ] Autenticação biométrica  
- [ ] Conformidade com LGPD

#### J. Usabilidade  
- [ ] Acessibilidade  
- [ ] Compatibilidade com telas  
- [ ] Clareza das instruções  
- [ ] Navegação intuitiva  
- [ ] Ajuda contextual  
- [ ] Busca no app

---

### RELACIONAMENTO  
- [ ] Atores interagem com os casos de uso?  
- [ ] Existe associação entre atores e funcionalidades?  
- [ ] Existe inclusão (`<<include>>`)?  
- [ ] Existe extensão (`<<extend>>`)?  
- [ ] Existe generalização? (não aplicável neste caso)

--- 
---

## Referências

- BRASIL. **Receita Federal do Brasil**. Aplicativos e-CAC e Pessoa Física. Disponível em: [https://www.gov.br/receitafederal](https://www.gov.br/receitafederal). Acesso em: mai. 2025.  
- PRESSMAN, Roger S. **Engenharia de Software**. 8. ed. São Paulo: McGraw-Hill, 2016.  
- SOMMERVILLE, Ian. **Engenharia de Software**. 10. ed. São Paulo: Pearson, 2011.  
- ISO/IEC 29148:2011 – **Systems and software engineering — Life cycle processes — Requirements engineering**.  
- ALMEIDA, M. E. B.; CASTRO, J. M. **UML – Unified Modeling Language**. 3. ed. Rio de Janeiro: LTC, 2013.  
- GOV.BR. **Guia de Serviços da Receita Federal**. Disponível em: [https://www.gov.br/pt-br/servicos](https://www.gov.br/pt-br/servicos). Acesso em: mai. 2025.  
- FUNIFIER. **Documentação da Plataforma de Gamificação**. Disponível em: [https://docs.funifier.com](https://docs.funifier.com). Acesso em: mai. 2025.


## Histórico de versões

Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
1.0 | 11/05/2025 | Criação do documento Casos de uso | [Julia Massuda](https://github.com/JuliaReis18) e  [Andre Lopes](https://github.com/andrewslopes)  | [Jose Eduardo](https://github.com/jevprado) |
