# Análise de Documentos

## Introdução

Este documento tem como objetivo elicitar e documentar os requisitos de software para o site da Receita Federal, utilizando a técnica de análise de documentos. O site da Receita Federal é uma plataforma online que fornece acesso a serviços fiscais, tributários e aduaneiros, atendendo tanto cidadãos quanto empresas. O site é acessível em múltiplos dispositivos e navegadores, também em sistemas operacionais como Windows, Linux e dispositivos móveis.


## Metodologia

A técnica utilizada neste documento é a análise de documentos. Essa técnica é particularmente útil quando os requisitos do software estão implícitos em documentos existentes e podem ser extraídos por meio de uma análise cuidadosa do conteúdo. A análise de documentos é uma técnica complementar a outras técnicas de elicitação de requisitos, para obter uma visão abrangente dos requisitos do software.

## Elicitação de Requisitos do Portal da Receita Federal

### Funcionalidades e Recursos

O portal da Receita Federal tem como objetivo centralizar, de forma digital e acessível, a prestação de serviços fiscais, tributários e aduaneiros a cidadãos, empresas e órgãos públicos. A plataforma permite a inscrição e regularização de cadastros (CPF, CNPJ), a entrega de declarações obrigatórias, a emissão de documentos de arrecadação, a consulta de restituições, a solicitação de certidões e o acompanhamento de processos eletrônicos. Além disso, o site disponibiliza atendimento virtual, materiais informativos, orientações tributárias e acesso à legislação vigente, promovendo a transparência, a eficiência e o suporte ao cumprimento das obrigações fiscais no Brasil.

[Documentação e listagem da Receita Federal](https://www.gov.br/pt-br/sitemap).

### Requisitos Técnicos
- Compatível com navegadores modernos (Chrome, Firefox, Edge, Safari).

- Acessível em Windows, macOS, Linux, Android e iOS.


[Página de Recursos de Acessibilidade Digital da Receita Federal](https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/acessibilidade-digital/recursos-de-acessibilidade)

### Requisitos de Usabilidade e Acessibilidade

- Consolida a acessibilidade: [Cartilha de Usabilidade](https://epwg.governoeletronico.gov.br/cartilha-usabilidade.html).
- Suporte ao modo escuro e letras maiores

### Requisitos de Segurança e Privacidade

- Respeito à privacidade do usuário e ausência de rastreamento ou coleta de dados invasiva [Política de Privacidade](https://www.gov.br/pt-br/termos-de-uso).

- Proteção contra vulnerabilidades [Política de Privacidade](https://www.gov.br/pt-br/termos-de-uso).

## Tabela de requisitos

| Identificação | Descrição | Categoria |
| --- | --- | --- |
| RFB01 | Acesso aos serviços de CPF, CNPJ e regularização de cadastro. | RF |
| RFB02 | Declaração e acompanhamento do Imposto de Renda. | RF |
| RFB03 | Emissão de certidões e documentos de arrecadação. | RF |
| RFB04 | Agendamento de atendimentos presenciais e atendimento digital. | RF |
| RFB05 | Compatibilidade com navegadores modernos (Chrome, Firefox, Edge). | RNF |
| RFB06 | Interface responsiva para dispositivos móveis e desktops. | RI |
| RFB07 | Suporte a recursos de acessibilidade (leitores de tela, Libras, contraste de cores). | RI |
| RFB08 | Alta disponibilidade e estabilidade de acesso ao portal. | RPR |
| RFB09 | Proteção de dados pessoais conforme a LGPD. | RR |
| RFB10 | Testes de usabilidade para garantir a navegação simples e acessível. | RT |
| RFB11 | Testes de segurança para garantir a integridade dos dados e autenticação segura. | RT |
| RFB12 | Testes de desempenho para suportar alta demanda de usuários simultâneos. | RT |
<div style="text-align: center;"><p>Tabela 1 - Tabela dos requisitos levantados (Autor: Thales. 2025).</p></div>

## Legenda

- RF: Requisitos Funcionais - Descrevem o comportamento ou a funcionalidade que o software deve ter para atender às necessidades do usuário.

- RNF: Requisitos Não-Funcionais - Descrevem os atributos que o software deve ter, como desempenho, segurança e usabilidade, mas não descrevem o comportamento do software em si.

- RI: Requisitos de Interface - Descrevem as características da interface do usuário, como layout, navegação e personalização.

- RPR: Requisitos de Produto - Descrevem as características do produto, como compatibilidade, desempenho e custo.

- RR: Riscos - São os riscos associados ao desenvolvimento e uso do software.

- RT: Testes e Validações - Descrevem as atividades necessárias para testar e validar o software antes de sua implantação.

## Bibliografia

- Receita Federal. *Portal Oficial da Receita Federal*. Disponível em: <https://www.gov.br/receitafederal/pt-br>. Acesso em: 25 abr. 2025.
- Receita Federal. *Serviços disponíveis no portal*. Disponível em: <https://www.gov.br/receitafederal/pt-br/assuntos/servicos>. Acesso em: 25 abr. 2025.
- Governo Digital. *Recursos de Acessibilidade Digital – gov.br*. Disponível em: <https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/acessibilidade-digital/recursos-de-acessibilidade>. Acesso em: 25 abr. 2025.
- Receita Federal. *Meu Imposto de Renda 2024*. Disponível em: <https://www.gov.br/receitafederal/pt-br/assuntos/meu-imposto-de-renda>. Acesso em: 25 abr. 2025.


## Histórico de Versões
| Data | Versão | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 25/04/2025 | `1.0` | Criação do documento | [Thales Germano](https://github.com/thalesgvl) e Marco Marques | 26/04/2025 | José |