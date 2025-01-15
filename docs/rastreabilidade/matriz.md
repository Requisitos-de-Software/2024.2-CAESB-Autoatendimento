# Matriz de Rastreabilidade

## Introdução
<p align="justify">&emsp;&emsp;A abordagem utilizada baseia-se em uma matriz (ou tabela) composta por cinco colunas, descritas a seguir, que têm o objetivo de apresentar os dados dos requisitos de forma clara e organizada.</p>

<br>

As colunas incluídas na matriz de rastreabilidade são as seguintes:
<br>

- ID: Identificação única de cada requisito.
- Descrição: Resumo do conteúdo ou objetivo do requisito.
- Elicitação: Método empregado para obter o requisito.
- Artefatos: Documentos produzidos com base no requisito.
- Implementação: Situação do requisito na aplicação, diminuindo se está implementado, parcialmente implementado ou ainda não implementado.

## Rastreamento

<p align="justify">&emsp;&emsp;Na Tabela 1 apresenta o rastreamento dos documentos e sua referência dos artigos apresentados em seguida.</p>

<center>

| **Legenda** | **Descrição**                  |
|-------------|--------------------------------|
| US          | História de Usuário           |
| ADD         | Análise de Documentos         |
| UC          | Casos de Uso                  |
| C           | Cenários                      |
| ES          | Especificação Suplementar     |
| NFR         | NFR Framework                 |
| L - LO, LV  | Léxico - Objeto, Verbo        |
| INT         | Introspecção                  |
| B           | Brainstorming                 |
| RF          | Requisitos Funcionais         |
| RNF         | Requisitos não Funcionais     |


 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a></h6>
</center>

## Matriz Geral

<p align="justify">&emsp;&emsp;A Tabela 2 apresenta todos os requisitos elicitados, juntamente com suas normas e rastreabilidades. Além disso, ela informa o status de cada requisito, deixando se estão implementados, parcialmente implementados ou não implementados, permitindo ao leitor compreender a situação atual do aplicativo.</p>

<center>

| **ID**   | **Descrição**                                                                                          | **Elicitação**                     | **Artefatos Relacionados**                   | **Implementado** |
|----------|--------------------------------------------------------------------------------------------------------|------------------------------------|---------------------------------------------|-------------------|
| RF01     | O sistema deve ter as funções mais utilizadas/mais buscadas em uma barra                               |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/#requisitos">B02</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/#requisitos">ENT08</a>                                                           | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-2-interatividade-e-suporte-ao-cliente">Backlog(Épico 2 - Interatividade e Suporte ao Cliente)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#historias-de-usuario_1">História de Usuário(US01)</a>| Não  
| RF02     | O sistema deve permitir emitir/visualizar segunda via de conta                                         | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/#requisitos">B04</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/#requisitos">ENT03</a> , <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT11</a>,  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/#requisitos">OBS03</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/#requisitos">OBS02</a>   |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#metodologia">Backlog(Épico 1 - Gestão de Contas e Pagamentos)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us17-barra-de-funcoes-mais-utilizadas">História de Usuário(US17)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#metodologia">Cénarios(C01)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#metodologia">Léxicos(L01)</a>                                 | Sim 
| RF03     | O sistema deve oferecer várias formas de pagamento                                                     | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B08</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B09</a>,  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT24</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD12</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT02</a>|  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#metodologia">Backlog(Épico 1 - Gestão de Contas e Pagamentos)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us19-formas-de-pagamento">História de Usuário(US19)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">Casos de Uso(UC12)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-17-formas-de-pagamento">Cenários(C17)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#lexico-l17-formas-de-pagamento">Léxicos(L17)</a>                                 |  Não   
| RF04     | O usuário deve poder enviar documentos diretamente pelo aplicativo.                                    |  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">ADD01</a>                            | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-2-interatividade-e-suporte-ao-cliente">Backlog(Épico 2 - Interatividade e Suporte ao Cliente)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us20-envio-de-documentos">História de Usuário(US20)</a>                                           |  Não   
| RF05     | O aplicativo deve incluir suporte a chat ou atendimento virtual para resolver dúvidas dos usuários.    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">ADD03</a> , <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT29 </a>   | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-2-interatividade-e-suporte-ao-cliente">Backlog(Épico 2 - Interatividade e Suporte ao Cliente)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us21-chat-ou-atendimento-virtual">História de Usuário(US21)</a>,  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">Casos de Uso(UC08)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-8-suporte-de-chat-ou-atendimento">Cenários(C8)</a> , <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l08-suporte-de-chat-ou-atendimento">Léxicos(L08)</a>                                         |   Não  
| RF06     | A funcionalidade "Informar vazamento na rua" deve mostrar apenas o mapa das regiões em que a Caesb atua.| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT01</a>     | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-3-sustentabilidade-e-consumo-consciente">Backlog(Épico 3 - Sustentabilidade e Consumo Consciente)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us12-permitir-ao-usuario-informar-vazamentos-na-rua-ou-no-hidrometro">História de Usuário(US12)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">Casos de Uso(UC04)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-4-informar-vazamento-na-rua">Cenários(C4)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l04-informar-vazamento-na-rua">Léxicos(L04)</a>                                          |    Sim    
| RF07     | O usuário deve poder informar e visualizar informações sobre a falta de água.                          | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT05</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT06</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/"> OBS06</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/"> INT14</a> |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-3-sustentabilidade-e-consumo-consciente">Backlog(Épico 3 - Sustentabilidade e Consumo Consciente)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us22-informar-vazamento">História de Usuário(US22)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">Casos de Uso(UC02)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-2-informar-falta-dagua">Cenários(C2)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l02-informar-falta-dagua">Léxicos(L02)</a>                                     |     Sim  
| RNF01    | O aplicativo deve garantir segurança com os dados dos usuários.                                        |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD06</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD07</a>                     | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/nfr/#nfr-framework-nfr03-confiabilidade">NFR de Desempenho(NFR03)</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/especSup/#confiabiliade">ES de Confiabilidade</a>                                          |   Sim  

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a></h6>
</center>

<br>

## Referências

><p id="1">[1] SERRANO, Milene. Slides da aula 26. Aula 26 da disciplina Requisitos de Software. Universidade de Brasília, Brasília. Acesso em 14 de janeiro de 2025.</p>
><p id="2">[2] POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamentals. 2ª ed. New York: Springer, 2010. Acesso em 14 de janeiro de 2025.</p>
><p id="3">[3] SAYÃO, Miriam; LEITE, Júlio César Sampaio do Prado. Rastreabilidade de Requisitos. Monografias em Ciência da Computação, n. 20/05. Rio de Janeiro: Departamento de Informática, Pontifícia Universidade Católica do Rio de Janeiro, 2005. Disponível em: https://aprender3.unb.br/pluginfile.php/2972563/mod_resource/content/3/05_20_sayao.pdf . Acesso em 14 de janeiro de 2025.</p>

<br>


## Histórico de versão


| Versão | Data       | Descrição                | Autor                                       | Revisor                                      |
| ------ | ---------- | ------------------------ | ------------------------------------------------ | ------------------------------------------------ |
|  1.0   | 14/01/2025 | Criação do artefato e adição dos requisitos |[Letícia Resende ](https://github.com/LeticiaResende23)   | [Leandro de Almeida](https://github.com/leomitx10)|

