
# Backward From – Receita Federal

## 1. Introdução

O presente documento tem como objetivo demonstrar a rastreabilidade dos requisitos do sistema da Receita Federal utilizando a abordagem **Backward From**. Esta abordagem permite acompanhar a origem e os artefatos associados a cada requisito, promovendo transparência e controle ao processo de engenharia de requisitos.

## 2. Metodologia

Para a construção do Backward From, foram utilizados os requisitos previamente elicitados por meio de técnicas como introspecção, storytelling, análise de documentos, entrevistas e brainstorming. A partir disso, cada requisito foi relacionado aos seus artefatos de modelagem (histórias de usuário, cenários, léxicos e casos de uso), compondo os elos que revelam o encadeamento da engenharia de requisitos.

## 3. Cronograma de Participantes

<font size="3"><p style="text-align: center">Tabela 1: Participantes</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Nome</th>
      <th>Data</th>
      <th>Hora</th>
    </tr>
  </thead>
  <tbody>
    <tr><td> Diassis </td><td> - </td><td> - </td></tr>
    <tr><td> José Eduardo </td><td> - </td><td> - </td></tr>
    <tr><td> Thales Germano </td><td> - </td><td> - </td></tr>
    <tr><td> Julia Massuda </td><td> - </td><td> - </td></tr>
    <tr><td> Andre Lopes </td><td> - </td><td> - </td></tr>
    <tr><td> Marco Marques </td><td> - </td><td> - </td></tr>
    <tr><td> João Pedro </td><td> - </td><td> - </td></tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

## 4. Cartões dos Requisitos

# Backward From – Receita Federal

## 1. Introdução

O presente documento apresenta o rastreamento dos requisitos do sistema desenvolvido para o aplicativo da Receita Federal. Utilizamos a técnica **Backward From** para conectar cada requisito aos artefatos que o originaram e às modelagens relacionadas, garantindo assim rastreabilidade, completude e clareza no processo de engenharia de requisitos.

## 2. Metodologia

A metodologia utilizada baseou-se em uma abordagem centrada no usuário, envolvendo diversas técnicas de elicitação como análise de documentos, introspecção, grupo de foco, storytelling e personas. Os requisitos foram classificados entre funcionais e não funcionais e rastreados com artefatos como histórias de usuário, casos de uso, léxicos, cenários e NFR Framework.

As informações foram estruturadas em cartões, contendo os elementos essenciais de rastreabilidade. Cada cartão indica o requisito, sua origem, categoria, os elementos em que aparece e os elos backward-from correspondentes.

## 3. Legenda

- **RF**: Requisito Funcional
- **RNF**: Requisito Não Funcional
- **US**: História de Usuário
- **UC**: Caso de Uso
- **L**: Léxico
- **C**: Cenário
- **NFR**: Requisito Não Funcional via Framework
- **ESP**: Especificação Suplementar
- **BP**: Backlog Prioritário

## 4. Cartões dos Requisitos

<font size="3"><p style="text-align: center">Tabela 1: Cartão do Requisito Funcional RF01</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Acesso simultâneo a múltiplos CPFs/CNPJs</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF01, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC1</a>, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/">ST01</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 2: Cartão do Requisito Funcional RF02</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Cadastro de CPF via app (totalmente remoto)</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF02, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC2</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>cenarios.md (C01)</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 3: Cartão do Requisito Funcional RF03</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Acompanhamento de status da restituição (precisão quanto aos lotes)</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF03, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC3</a>, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/">ST02</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 4: Cartão do Requisito Funcional RF04</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Notificação de vencimento próximo</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF04, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC4</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-10</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 5: Cartão do Requisito Funcional RF05</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Agendar no próprio aplicativo atendimentos presenciais em unidades da Receita Federal</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF05, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT3</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 6: Cartão do Requisito Funcional RF06</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Acesso offline a serviços essenciais do app (históricos de contribuições, DARFs)</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF06, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC6</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-09</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 7: Cartão do Requisito Funcional RF07</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Alteração de dados via app</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF07, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC7</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 8: Cartão do Requisito Funcional RF08</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Funcionalidade de histórico e acompanhamento de restituições de anos anteriores</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF08, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC8</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 9: Cartão do Requisito Funcional RF09</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Declaração simplificada do IR</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF09, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC9</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-11</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 10: Cartão do Requisito Funcional RF10</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Geração de guias de pagamento</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF10, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC10</a>, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/">ST03</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-03</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 11: Cartão do Requisito Funcional RF11</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Consultar o status do CPF (ativo ou não)</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF11, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC11</a>, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/">ST06</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-04</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 12: Cartão do Requisito Funcional RF12</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Integração com conta Gov.br</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF12, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC12</a>, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/">ST10</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-27</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 13: Cartão do Requisito Funcional RF13</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Envio de documentos para instrução de processos</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF13, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC16</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-28</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 14: Cartão do Requisito Funcional RF14</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Acessar informações detalhadas a cerca da declaração de imposto de renda de um ano especifico</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF14, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT1</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-05</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 15: Cartão do Requisito Funcional RF15</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>O aplicativo deve permitir o envio da declaração do Imposto de Renda diretamente pelo app</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF15, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT2</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-29</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 16: Cartão do Requisito Funcional RF16</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>O aplicativo deve mostrar um histórico de envio das declarações entregues pelo usuário.</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF16, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT5</a>, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/">ST09</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-30</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 17: Cartão do Requisito Funcional RF17</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Emissão de certidão negativa via aplicativo</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF17, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT6</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-06</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 18: Cartão do Requisito Funcional RF18</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Consultar pendências de Malha</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF18, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT7</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-31</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 19: Cartão do Requisito Funcional RF19</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Dashboard para profissionais contábeis de múltiplos CPFs/CNPJs</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF19, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT8</a>, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/">ST14</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-18</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 20: Cartão do Requisito Funcional RF20</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Acompanhar processos no próprio aplicativo</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF20, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT18</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-07</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 21: Cartão do Requisito Funcional RF21</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Integração com o App Esocial dentro do próprio</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF21, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT19</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-32</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 22: Cartão do Requisito Funcional RF22</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Permitir via App autorização de acesso à terceiros</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF22, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT20</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-33</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 23: Cartão do Requisito Funcional RF23</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Compartilhamento de comprovantes e certidões por WhatsApp, e-mail ou Drive</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF23, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT21</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-34</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 24: Cartão do Requisito Funcional RF24</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Reenvio de notificações perdidas via e-mail ou mensagem no app</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF24, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT22</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-13</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 25: Cartão do Requisito Funcional RF25</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Comparativo automático entre declarações de anos anteriores</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF25, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT23</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-14</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 26: Cartão do Requisito Funcional RF26</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>FAQ interativo com busca inteligente (filtrado por tema: CPF, IRPF, Certidões etc.)</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF26, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT24</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-08, US-15</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 27: Cartão do Requisito Funcional RF27</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Integração com calendário do dispositivo para lembretes de obrigações fiscais</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF27, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT25</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-16</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 28: Cartão do Requisito Funcional RF28</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Consulta de inscrição no CNPJ</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF28, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT26</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-17</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 29: Cartão do Requisito Funcional RF29</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Consulta de tabelas CNAE, NCM e unidades da Receita Federal</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF29, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT27</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-12</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 30: Cartão do Requisito Funcional RF30</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Acesso à Caixa Postal para mensagens oficiais da Receita Federal</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF30, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT28</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-35</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 31: Cartão do Requisito Funcional RF31</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Visualização de notícias e vídeos institucionais da Receita Federal</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF31, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT29</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>US-36</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 32: Cartão do Requisito Funcional RF32</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Consultar débitos pendentes (DARFs)</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF32, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/">ST04</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 33: Cartão do Requisito Funcional RF33</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Pagamento do DARF com cartão de crédito</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF33, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/">ST05</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 34: Cartão do Requisito Funcional RF34</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Emitir comprovante de CPF em PDF</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RF34, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/">ST07</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 35: Cartão do Requisito Não Funcional RNF1</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Acessibilidade (chatbot, imagens, vídeos) — melhorias no chatbot</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF1, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC13</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 36: Cartão do Requisito Não Funcional RNF2</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Conteúdo educativo para iniciantes</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF2, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC14</a>, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/">ST08</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 37: Cartão do Requisito Não Funcional RNF3</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Testes de desempenho para suportar alta demanda de usuários simultâneos</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF3, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC15</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 38: Cartão do Requisito Não Funcional RNF4</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Proteção de dados pessoais conforme a LGPD</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF4, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC17</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 39: Cartão do Requisito Não Funcional RNF5</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Interface responsiva e acessível</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF5, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC18</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 40: Cartão do Requisito Não Funcional RNF6</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Interface com a possibilidade de uso do modo escuro</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF6, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC23</a>, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT17</a>, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/">ST11</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 41: Cartão do Requisito Não Funcional RNF7</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Testes de segurança para garantir a integridade dos dados e autenticação segura</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF7, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC19</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 42: Cartão do Requisito Não Funcional RNF8</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Compatível com Android 8+ e iOS 14+</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF8, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC20</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 43: Cartão do Requisito Não Funcional RNF9</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Testes de usabilidade semestrais com público 60+</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF9, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC21</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 44: Cartão do Requisito Não Funcional RNF10</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>O aplicativo deve ter tempo de resposta inferior a 3 segundos para ações comuns</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF10, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT9</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 45: Cartão do Requisito Não Funcional RNF11</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>O aplicativo deve funcionar em smartphones com telas de 4.5" a 7" sem perda de usabilidade</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF11, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT10</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 46: Cartão do Requisito Não Funcional RNF12</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Linguagem da interface deve seguir padrão A2 do CEFR, evitando jargões técnicos</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF12, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC25</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 47: Cartão do Requisito Não Funcional RNF13</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>O app deve suportar modo de operação em baixa conectividade, com cache de dados essenciais</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF13, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT11</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 48: Cartão do Requisito Não Funcional RNF14</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Atualizações do app não devem causar perda de dados armazenados localmente</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF14, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT12</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 49: Cartão do Requisito Não Funcional RNF15</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Tempo de inatividade programada máximo de 2h por mês, com aviso prévo</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF15, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT13</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 50: Cartão do Requisito Não Funcional RNF16</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Tempo de carregamento inicial do app não deve ultrapassar 5 segundos em conexão móvel</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF16, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC24</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 51: Cartão do Requisito Não Funcional RNF17</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Suporte a leitores de tela (TalkBack, VoiceOver) em todas as funcionalidades</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF17, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT14</a>  <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/">ADC23</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 52: Cartão do Requisito Não Funcional RNF18</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Armazenamento anônimo de logs de erro respeitando a LGPD</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF18, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT15</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 53: Cartão do Requisito Não Funcional RNF19</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Versão mínima em HTML5 responsiva para acesso via navegador em caso de falha do app</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF19, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/">INT16</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 54: Cartão do Requisito Não Funcional RNF20</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Clareza na apresentação de dados fiscais</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF20, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/">ST12</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>

<font size="3"><p style="text-align: center">Tabela 55: Cartão do Requisito Não Funcional RNF21</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Descrição do requisito</td>
      <td>Integração confiável com serviços externos (Gov.br, instituições financeiras)</td>
    </tr>
    <tr>
      <td>Categoria</td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td>Elementos</td>
      <td>RNF21, <a href="https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/">ST13</a></td>
    </tr>
    <tr>
      <td>Elos Backward-from</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>Não implementado</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>


## 5. Histórico de Versão

| Versão | Data       | Descrição                                 | Autor(es) | Revisor(es) |
|--------|------------|--------------------------------------------|-----------|-------------|
| 1.0    | 08/06/2025 | Criada primeira versão do forward from | Diassis | José Eduardo |
