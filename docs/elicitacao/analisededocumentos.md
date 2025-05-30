# Análise de Documentos

## Introdução

Este documento tem como objetivo elicitar e documentar os requisitos de software para o aplicativo móvel da Receita Federal, utilizando a técnica de análise de documentos. O aplicativo é uma plataforma oficial que fornece acesso a serviços fiscais, tributários e aduaneiros diretamente em dispositivos Android e iOS, atendendo cidadãos e empresas por meio da integração com o gov.br.

## Metodologia

A técnica utilizada neste documento é a análise de documentos. Essa técnica é particularmente útil quando os requisitos do software estão implícitos em documentos existentes e podem ser extraídos por meio de uma análise cuidadosa do conteúdo. A análise de documentos é uma técnica complementar a outras técnicas de elicitação de requisitos, para obter uma visão abrangente dos requisitos do software.

## Elicitação de Requisitos do App da Receita Federal

### Funcionalidades e Recursos

O aplicativo da Receita Federal tem como objetivo centralizar, de forma digital e acessível, a prestação de serviços fiscais, tributários e aduaneiros a cidadãos, empresas e órgãos públicos. A plataforma permite:

- Autenticação via conta gov.br
- Inscrição e regularização de cadastros de CPF e CNPJ, inclusive emissão de comprovantes
- Entrega, retificação e acompanhamento da declaração de Imposto de Renda
- Emissão de DARF e outros documentos de arrecadação, com pagamento via Pix ou código de barras
- Solicitação de certidões negativas
- Acompanhamento de processos eletrônicos (e‑Processo) e atendimento virtual por chat
- Recebimento de notificações sobre restituições, pendências e prazos
- Leitura de QR Code para verificação de autenticidade de documentos
- Armazenamento local criptografado de rascunhos, com sincronização automática quando on‑line

[Documentação e listagem da Receita Federal](https://www.gov.br/pt-br/sitemap).

### Requisitos Técnicos

- Compatível com Android 8.0 ou superior e iOS 14 ou superior
- Distribuição oficial pela Google Play e App Store
- Construído em Kotlin (Android) e Swift (iOS), com integração REST/GraphQL ao back‑end da Receita e serviços gov.br
- Atualizações de manutenção pelo menos trimestrais
- Compatível com navegadores modernos (Chrome, Firefox, Edge, Safari), quanto ao site.

[Página de Recursos de Acessibilidade Digital da Receita Federal](https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/acessibilidade-digital/recursos-de-acessibilidade)

### Requisitos de Usabilidade e Acessibilidade

- Conformidade com WCAG para aplicações móveis
- Suporte a modo escuro, ajuste dinâmico de fonte e alto contraste
- Compatibilidade com leitores de tela TalkBack (Android) e (iOS)
- Fluxos simplificados para usuários acima de 60 anos

[Cartilha de Usabilidade](https://epwg.governoeletronico.gov.br/cartilha-usabilidade.html).

### Requisitos de Segurança e Privacidade

- Autenticação forte com biometria (Face ID ou impressão digital) e PIN
- Armazenamento local protegido no iOS e Android 
- Criptografia de dados em trânsito e em repouso
- Conformidade com a LGPD, sem rastreamento de terceiros
- Programa governamental de bug bounty e análise estática de código a cada release

[Política de Privacidade](https://www.gov.br/pt-br/termos-de-uso).

## Tabela de requisitos             

| ID    | Descrição                                                                                    | Categoria |
| ----- | -------------------------------------------------------------------------------------------- | --------- |
| ADC1    | Acesso rápido e simultâneo a múltiplos CPFs/CNPJs                                            | RF        |
| ADC2  | Cadastro de CPF via app (totalmente remoto)                                                  | RF        |
| ADC3| Acompanhamento de status da restituição (precisão quanto aos lotes)                           | RF        |
| ADC4 | Notificação de vencimento próximo                                                               | RF        |
| ADC5| Unificação de serviços no app (ex: agendamento, acompanhamento de processos, certidões etc.)    | RF        |
| ADC6 | Acesso offline a serviços essencial do app (históricos de contribuições anteriores, darfs)      | RF e RNF  |
| ADC7 | Alteração de dados via app  | RF |
| ADC8 | Funcionalidade de histórico e acompanhamento de restituições e de declarações                   | RF        |
| ADC9 | Declaração simplificada do IR                                                                  | RF        |
| ADC10 | Geração de guias de pagamento                                                                | RF        |
| ADC11 | Consultar o status do CPF (ativo ou não)                                                     | RF        |
| ADC12 | Integração com conta Gov.br                                                                  | RF        |
| ADC13 | Acessibilidade (chatbot, imagens, vídeos) — melhorias no chatbot sugeridas                   | RI        |
| ADC14 | Conteúdo educativo para iniciantes                                                           | RI        |
| ADC15 | Testes de desempenho para suportar alta demanda de usuários simultâneos                      | RT        |
| ADC16 | Envio de documentos para instrução de processos                                              | RF        |
| ADC17 | Proteção de dados pessoais conforme a LGPD                                                   | RR        |
| ADC18 | Interface responsiva, acessível               						                      | RI |
| ADC19 | Testes de segurança para garantir a integridade dos dados e autenticação segura.                | RT |
| ADC20 | Compatível com Android 8+ e iOS 14+.                                                         | RNF       |
| ADC21 | Testes de usabilidade semestrais com público 60+.                                            | RT        |
| ADC22 | Suporte a leitores de tela (TalkBack, VoiceOver) em todas as funcionalidades                 | RI        |
| ADC23 | Interface com a possibilidade de uso do modo escuro      | RNF        | 
| ADC24 | Tempo de carregamento inicial do app não deve ultrapassar 5 segundos em conexão móvel       | RNF        |
| ADC25 | Linguagem da interface deve seguir padrão A2 do CEFR, evitando jargões técnicos     | RNF        | 

<div style="text-align: center;"><p>Tabela 1 - Tabela dos requisitos levantados (Autor: Thales. 2025).</p></div>

## Legenda

- RF: Requisitos Funcionais - Descrevem o comportamento ou a funcionalidade que o software deve ter para atender às necessidades do usuário.
- RNF: Requisitos Não-Funcionais - Descrevem os atributos que o software deve ter, como desempenho, segurança e usabilidade, mas não descrevem o comportamento do software em si.
- RI: Requisitos de Interface - Descrevem as características da interface do usuário, como layout, navegação e personalização.
- RPR: Requisitos de Produto - Descrevem as características do produto, como compatibilidade, desempenho e custo.
- RR: Riscos - São os riscos associados ao desenvolvimento e uso do software.
- RT: Testes e Validações - Descrevem as atividades necessárias para testar e validar o software antes de sua implantação.

## Bibliografia

- Receita Federal. Portal Oficial da Receita Federal. Disponível em: <https://www.gov.br/receitafederal/pt-br>. Acesso em: 25 abr. 2025.
- Receita Federal. Aplicativo Receita Federal – Android & iOS. Disponível nas lojas oficiais. Acesso em: 25 abr. 2025.
- Governo Digital. Recursos de Acessibilidade Digital – gov.br. Disponível em: <https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/acessibilidade-digital/recursos-de-acessibilidade>. Acesso em: 25 abr. 2025.

## Histórico de Versões

Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
`1.0` | 25/04/2025 | Criação do documento | [Thales Germano](https://github.com/thalesgvl) e [Marco Marques](https://github.com/marcomarquesdc) | [José Eduardo](https://github.com/jevprado) |
`1.1` | 04/05/2025 | Ajustes do documento | [Thales Germano](https://github.com/thalesgvl) e [Marco Marques](https://github.com/marcomarquesdc) | [José Eduardo](https://github.com/jevprado) |
`1.2` | 30/05/2025 | Correção dos códigos de requisitos | [José Eduardo](https://github.com/jevprado)| [Thales Germano](https://github.com/thalesgvl) |