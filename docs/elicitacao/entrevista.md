## Introdução 

A técnica de entrevista é amplamente utilizada no processo de elicitação de requisitos. Trata-se de uma abordagem interativa e estruturada que permite investigar necessidades, expectativas, limitações e prioridades dos usuários, promovendo um melhor entendimento sobre o domínio do problema e o contexto de uso do sistema.

No projeto em questão, a entrevista foi conduzida com usuários reais do sistema da Receita Federal, buscando captar percepções, dificuldades e sugestões que nem sempre emergem em análises documentais ou introspectivas. A troca direta com o entrevistado possibilita levantar tanto requisitos funcionais quanto não funcionais.

##  Objetivo da Técnica

- Coletar informações qualitativas e quantitativas sobre o uso atual do sistema da Receita Federal.

- Identificar necessidades e expectativas dos usuários que possam ser traduzidas em requisitos de software.

- Compreender os principais pontos de dor (pain points) enfrentados pelos cidadãos ao interagir com o sistema.

- Explorar casos de uso reais e contextos específicos de operação. 

- Promover uma escuta ativa que favoreça a descoberta de requisitos latentes ou não verbalizados diretamente.

## Tabela de atividades feitas - por membro

<p style="text-align: center"><b>Tabela 1</b> - Atividades por membro</p>

|Nome                                                | Atividade entregue                        | 
| -------------------------------------------------- | ----------------------------------------- | 
| [José Eduardo](https://github.com/jevprado)        | Criação do documento, introdução, objetivos, formulação do questionário, e tabela de requisitos elicitados (tabela 03).       | 
| [Andre Lopes](https://github.com/andrewslopes)     | Formulação do questionário, entrevistador e tabela de requisitos elicitados (tabela 03).         | 
| Revisor aqui     | Revisor do documento        | 


<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>


## Participantes da entrevista 

<p style="text-align: center"><b>Tabela 2</b> - Entrevista</p>

| Participantes                                   | Função           | 
| ----------------------------------------------- | ---------------- | 
| [Andre Lopes](https://github.com/andrewslopes)  | Entrevistador  | 
| Elizabeth                                       | Usuário          | 

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>

##  Roteiro de Perguntas

1 - Abertura e contexto

- "Você já utilizou algum serviço da Receita Federal online? Se sim, com que frequência?"

- "Qual foi a última vez que usou o sistema da Receita e para quê?"

2 - Uso atual e dificuldades

- "Você encontrou alguma dificuldade ao acessar ou usar o sistema?"

- "Em que momentos você se sentiu inseguro ou confuso durante o uso?"

- "Já teve problemas com lentidão, falhas, mensagens de erro?"

3 -  Usabilidade e experiência

- "Você acha fácil encontrar as informações ou serviços que procura no site ou aplicativo?"

- "Que serviços você mais precisa quando usa o aplicativo da Receita?"

4 - Expectativas e sugestões

- "Existe alguma atividade que você gostaria de fazer online e ainda não é possível?"

5 - Segurança e confiança

- "Você sente que seus dados estão seguros ao usar os serviços da Receita?"

- "Já teve algum receio ou problema com login, autenticação ou vazamento de dados?"

## Tabela de requisitos levantados 

<p style="text-align: center"><b>Tabela 3</b> - Tabela de requisitos - Entrevista </p>

| Código | Descrição                                                                               | Categoria | Status        | 
| ------ | --------------------------------------------------------------------------------------- | --------- |-------------- |    
| ENT01  | Declaração do Imposto de Renda diretamente pelo app                                     | RF        | Implementada  |
| ENT02  | Emissão de certidão negativa via aplicativo                                             | RF        | Implementada  |
| ENT03  | Acessar informações detalhadas a cerca da declaração de imposto de renda de um ano especifico                                                                                         | RF        | Implementada  |
| ENT04  | Integração com conta Gov.br                                                       | RF        | Implementada  |
| ENT05  | Integração confiável com serviços externos (Gov.br, instituições financeiras)                                                      | RNF        | Implementada  |


<font size="3"><p style="text-align: center">Fonte: [Andre Lopes](https://github.com/andrewslopes) e [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>

## Vídeo da entrevista 

<iframe width="600" height="315" 
        src="https://www.youtube.com/embed/GHoDEMr5AQw" 
        title="YouTube video player" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
        referrerpolicy="strict-origin-when-cross-origin" 
        allowfullscreen>
</iframe>

##  Referências

1. PRESSMAN, Roger S.; MAXIM, Bruce R. *Engenharia de Software*. McGraw-Hill, 2016.  
- SOMMERVILLE, Ian. *Engenharia de Software*. Pearson, 2019.  
- PREECE, Jenny; ROGERS, Yvonne; SHARP, Helen. *Design de Interação*. Bookman, 2019.  
- REIS, Carla Silva dos et al. Técnicas de elicitação de requisitos. *Revista de Informática Teórica e Aplicada*, 2014.

---
## Histórico de versão
Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
`1.0` | 20/06/2025 | Criação da pagina de entrevista | [André Lopes](https://github.com/andrewslopes) e [Jose Eduardo](https://github.com/jevprado) | revisor aqui |
