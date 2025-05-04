## Priorização de Requisitos com a Técnica QFD (Quality Function Deployment)

### Introdução ao QFD

O **QFD (Quality Function Deployment)**, ou Desdobramento da Função Qualidade, é uma técnica estruturada que visa transformar as **necessidades e desejos dos clientes** (VOC – *Voice of the Customer*) em **características técnicas e funcionais** do produto. É amplamente utilizada em projetos de engenharia e desenvolvimento de software para garantir que o sistema entregue valor real ao usuário final.

A principal ferramenta do QFD é a **Casa da Qualidade**, uma matriz que relaciona os **requisitos do cliente** com os **requisitos técnicos**, atribuindo pesos que indicam a **importância relativa de cada função técnica** para atender as expectativas do usuário.

### Aplicação da Matriz QFD (simplificada)

#### Necessidades dos usuários (VOC):

| Código | Necessidade do Usuário                                        | Peso |
|--------|---------------------------------------------------------------|------|
| N1     | Facilidade no acesso aos serviços da Receita Federal         | 5    |
| N2     | Agilidade no acompanhamento da restituição                   | 4    |
| N3     | Segurança e proteção de dados                                 | 5    |
| N4     | Mobilidade e acesso por celular                               | 4    |
| N5     | Atendimento a iniciantes com conteúdo educativo               | 2    |

#### Requisitos Técnicos (RT):

| Código | Requisito Técnico (vinculado ao projeto)                                    |
|--------|----------------------------------------------------------------------------|
| R1     | Cadastro de CPF via app                                                   |
| R2     | Acompanhamento da restituição                                             |
| R3     | Integração com Gov.br                                                     |
| R4     | Proteção de dados (LGPD)                                                  |
| R5     | Interface responsiva                                                      |
| R6     | Conteúdo educativo para iniciantes                                        |

#### Matriz QFD

| Requisito Técnico \ Necessidade do Usuário | N1 | N2 | N3 | N4 | N5 | Total (Peso × Relação) |
|-------------------------------------------|----|----|----|----|----|--------------------------|
| R1 – Cadastro de CPF via app              | 9  | 3  | 3  | 9  | 1  | 5×9 + 4×3 + 5×3 + 4×9 + 2×1 = **128** |
| R2 – Acompanhamento da restituição        | 3  | 9  | 3  | 3  | 1  | 5×3 + 4×9 + 5×3 + 4×3 + 2×1 = **98**  |
| R3 – Integração com Gov.br                | 9  | 3  | 9  | 9  | 1  | 5×9 + 4×3 + 5×9 + 4×9 + 2×1 = **157** |
| R4 – Proteção de dados (LGPD)             | 1  | 1  | 9  | 1  | 1  | 5×1 + 4×1 + 5×9 + 4×1 + 2×1 = **66**  |
| R5 – Interface responsiva                 | 3  | 1  | 3  | 9  | 1  | 5×3 + 4×1 + 5×3 + 4×9 + 2×1 = **100** |
| R6 – Conteúdo educativo                   | 1  | 1  | 1  | 1  | 9  | 5×1 + 4×1 + 5×1 + 4×1 + 2×9 = **45**  |

> **Legenda dos valores de relacionamento:**  
> 9 = Forte relação | 3 = Média relação | 1 = Fraca relação | 0 = Nenhuma relação

---

### Conclusão da Análise

Com base nos pesos calculados, os requisitos que mais contribuem para satisfazer as principais necessidades dos usuários são:

1. **R3 – Integração com Gov.br** (157 pontos)  
2. **R1 – Cadastro de CPF via app** (128 pontos)  
3. **R5 – Interface responsiva** (100 pontos)  
4. **R2 – Acompanhamento da restituição** (98 pontos)  
5. **R4 – Proteção de dados (LGPD)** (66 pontos)  
6. **R6 – Conteúdo educativo para iniciantes** (45 pontos)

Essa priorização orienta os desenvolvedores a focarem nas funcionalidades de maior impacto e alinhamento com os desejos do público-alvo.

---

### Referências Bibliográficas

- AKAO, Y. *Quality Function Deployment: Integrating Customer Requirements into Product Design*. Productivity Press, 1990.  
- CAMPOS, V. F. *TQC - Controle da Qualidade Total (no estilo japonês)*. 11. ed. Belo Horizonte: Fundação Christiano Ottoni, 2004.  
- PRESSMAN, R. S.; MAXIM, B. R. *Engenharia de Software*. 8. ed. Porto Alegre: AMGH, 2016.  
- SOMMERVILLE, I. *Engenharia de Software*. 10. ed. São Paulo: Pearson, 2019.

 ---
 ## Historico de versões

Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
1.0 | 04/05/2025 | Criação QFD |[Júlia Massuda](https://github.com/JuliaReis18) e [João Pedro](https://github.com/JpRodrigues2)  |



