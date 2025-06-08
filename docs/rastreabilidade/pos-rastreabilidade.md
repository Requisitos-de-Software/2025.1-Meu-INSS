## Introdução 

## Metodologia 


Tabela 1 - Template do cartão usado na pós-rastreabilidade

| Artefato Analisado| Classificação do Artefato Analisado |
| ------------- | ---------------------------------- |
| Descrição     |       Descrição do requisito                                               |
| Tipos de Elo  | Ambiental/Organizacional/Gerencial/Desenvolvimento                         |
| Código do req    | RF e RNF/  |
| Backward-from | TIPO DE ELO (Origem) - US,C,L,USA, CON, DES, SUP, AC / INT, ADC, GDF, ST / NFRx, US, E        |
| Foward-from   |  TIPO DE ELO (Relação)                - Satisfação/agregação + descrição                  |
| Representação |         Imagem ou vídeo             |

Fonte: 

## Cartão de Rastreabilidade RF23

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| Descrição | O aplicativo permite o compartilhamento de comprovantes e certidões diretamente pelo aplicativo através de WhatsApp, e-mail ou salvamento em nuvem. |
| Tipos de Elo | Desenvolvimento |
| Código do req | RF23 |
| Backward-from | **US:** US-13 - Compartilhamento de comprovantes e certidões<br>**Cenário:** C06 (Emissão de comprovante de situação cadastral do CPF)<br>**Léxico:** L06 (Emitir Comprovante de Rendimentos)<br>**Casos de Uso:** UC: Consultar Recibo<br>**Épico:** E02 - Regularização e Pagamentos<br>**NFR:** RNF1 (Acessibilidade), RNF20 (Clareza na apresentação de dados fiscais)<br>**Especificação Suplementar:** USA01 (Acessibilidade), USA06 (Clareza na apresentação de dados fiscais) |
| Foward-from | **Satisfação:** Especificação Suplementar: USA01, USA06<br>**Agregação:** História de Usuário: US-13 - Compartilhamento de comprovantes e certidões; Feature: F11 - Compartilhamento de comprovantes e certidões |
| Representação | Não aplicável |

Fonte: [Julia Massuda](https://github.com/JuliaReis18) 

---

## Cartão de Rastreabilidade RF24

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| Descrição | O aplicativo permite o reenvio de notificações importantes que o usuário perdeu ou não recebeu. |
| Tipos de Elo | Desenvolvimento |
| Código do req | RF24 |
| Backward-from | **US:** US-14 - Reenvio de notificações perdidas<br>**Cenário:** Informação não disponível.<br>**Léxico:** Informação não disponível.<br>**Casos de Uso:** UC: Relacionado a "Receber notificações da Receita"<br>**Épico:** E04 - Atendimento e Comunicação<br>**NFR:** Informação não disponível.<br>**Especificação Suplementar:** Informação não disponível explicitamente para esse requisito. |
| Foward-from | **Satisfação:** Especificação Suplementar: Informação não disponível<br>**Agregação:** História de Usuário: US-14 - Reenvio de notificações perdidas; Feature: F17 - Reenvio de notificações perdidas |
| Representação | Não aplicável |

Fonte: [Julia Massuda](https://github.com/JuliaReis18) 

---

## Cartão de Rastreabilidade RF26

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| Descrição | O aplicativo permite acesso a um FAQ interativo com busca inteligente filtrada por temas. |
| Tipos de Elo | Desenvolvimento |
| Código do req | RF26 |
| Backward-from | **US:** US-16 - FAQ interativo com busca inteligente<br>**Cenário:** C02 (Idoso utiliza chatbot acessível para tirar dúvidas sobre a declaração do IR)<br>**Léxico:** Informação não disponível.<br>**Casos de Uso:** UC: Relacionado a "Acessar vídeos e notícias institucionais" e "Sistema de Ajuda e Documentação"<br>**Épico:** E04 - Atendimento e Comunicação<br>**NFR:** RNF1 (Acessibilidade), RNF2 (Conteúdo educativo para iniciantes)<br>**Especificação Suplementar:** USA01 (Acessibilidade), USA02 (Conteúdo educativo para iniciantes) |
| Foward-from | **Satisfação:** Especificação Suplementar: USA01, USA02<br>**Agregação:** História de Usuário: US-16 - FAQ interativo com busca inteligente; Feature: F18 - FAQ interativo com busca inteligente |
| Representação | Não aplicável |

Fonte: [Julia Massuda](https://github.com/JuliaReis18) 

---

## Cartão de Rastreabilidade RF27

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| Descrição | O aplicativo se integra automaticamente com o calendário do dispositivo para criar lembretes de obrigações fiscais. |
| Tipos de Elo | Desenvolvimento |
| Código do req | RF27 |
| Backward-from | **US:** US-17 - Integração com calendário do dispositivo<br>**Cenário:** Informação não disponível.<br>**Léxico:** Informação não disponível.<br>**Casos de Uso:** UC: Relacionado a "Lembretes automáticos" (de Agendar Atendimento)<br>**Épico:** E05 - Experiência do Usuário e Acessibilidade<br>**NFR:** Informação não disponível.<br>**Especificação Suplementar:** Informação não disponível explicitamente para esse requisito. |
| Foward-from | **Satisfação:** Especificação Suplementar: Informação não disponível<br>**Agregação:** História de Usuário: US-17 - Integração com calendário do dispositivo; Feature: F20 - Integração com calendário do dispositivo |
| Representação | Não aplicável |

Fonte: [Julia Massuda](https://github.com/JuliaReis18) 

---

## Cartão de Rastreabilidade RF19

| Artefato Analisado | Classificação do Artefato Analisado |
|---|---|
| Descrição | O aplicativo possui um dashboard especializado que permite gerenciar múltiplos CPFs/CNPJs dos clientes. |
| Tipos de Elo | Desenvolvimento |
| Código do req | RF19 |
| Backward-from | **US:** US-18 - Dashboard para profissionais contábeis<br>**Cenário:** C03 (Consulta e gerenciamento de múltiplos CPFs/CNPJs pelo app)<br>**Léxico:** L09 (Contribuinte)<br>**Casos de Uso:** UC: Relacionado a "Consultar Situação Fiscal", "Pagar Tributos", "Consultar Processos", "Acesso simultâneo a múltiplos CPFs/CNPJs"<br>**Épico:** E05 - Experiência do Usuário e Acessibilidade<br>**NFR:** RNF20 (Clareza na apresentação de dados fiscais), RNF21 (Integração confiável com serviços externos)<br>**Especificação Suplementar:** USA06 (Clareza na apresentação de dados fiscais), CON05 (Integração confiável com serviços externos) |
| Foward-from | **Satisfação:** Especificação Suplementar: USA06, CON05<br>**Agregação:** História de Usuário: US-18 - Dashboard para profissionais contábeis; Feature: F21 - Dashboard para profissionais contábeis |
| Representação | Não aplicável |

Fonte: [Julia Massuda](https://github.com/JuliaReis18) 

## Participação por membro da equipe 

| Nome do membro                             | Elos do membro |
| ------------------------------------------ | ----------------- |
|[José Eduardo](https://github.com/jevprado) | ----------------- |







## Referências 




## Historico de versões

| Versão | Data       | Descrição                                      | Autor(es)                                      | Revisor(es)                                    |
| ------ | ---------- | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- |
| `1.0`   | 05/06/2025 | Criação do documento de pós rastreabilidade   | [José Eduardo](https://github.com/jevprado)    | [Diassis](https://github.com/Diaxiz) |
| `1.1`   | 08/06/2025 | Adicionando os cartões de Rastreabilidade RF19, RF27, RF26, RF24 E RF23.  | [Julia Massuda](https://github.com/JuliaReis18) | add revisor aqui |
