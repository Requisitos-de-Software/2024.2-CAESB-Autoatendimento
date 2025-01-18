# Forward-From

## Introdução

<p align="justify">&emsp;&emsp; O conceito de Forward From pode ser visto como o processo de levar os requisitos iniciais de um projeto para as fases seguintes de desenvolvimento, como o design, a implementação, os testes e a entrega do sistema. Essa abordagem garante que todas as alterações ou adições feitas ao software ao longo do caminho estejam sempre alinhadas com os requisitos definidos no começo do projeto.</p>

## Metodologia

<p align="justify">&emsp;&emsp; A metodologia utilizada para estabelecer a rastreabilidade entre os requisitos e os artefatos foi o "forward-from" (para frente, a partir de). A técnica "forward-from" consiste em relacionar os requisitos com os artefatos de implementação. Os requisitos estão contidos no artefato de <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/"> Requisitos Elicitados</a>.</p>

<p align="justify">&emsp;&emsp; A Tabela 1 apresenta a legenda utilizada para identificar os diferentes tipos de artefatos.</p>

<center>
<figcaption>Tabela 1 - tipos de artefato</figcaption>


| Legenda | Artefato                  |
|:-------:|:-------------------------:|
| RQ      | Requisito                 |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos Não Funcionais |
| ADD     | Análise de documentos     |
| INT     | Introspecção              |
| OBS     | Observação                |
| ENT     | Entrevista                |
| BS      | Brainstorm                |
| C       | Cenários                  |
| L       | Léxico                    |
| ES      | Especificação Suplementar |
| UC      | Caso de Uso               |

</center>

<p align="justify">&emsp;&emsp; A Tabela 2 apresenta as relações entre os requisitos e os artefatos correspondentes, com ela é possível visualizar quais artefatos estão associados a cada requisito, fornecendo uma visão clara das dependências e do contexto de implementação.</p>

<center>
<figcaption>Tabela 2 - modelo</figcaption>

| ID do requisito | Descrição do requisito |
| :-: | :-: |
| Épico | Épico de referência |
| Feature | Feature do Backlog |
| História de Usuário | História de usuário |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | Softgoals relacionado |
| Especificação Suplementar | Categoria | 

</center>

## Requisitos Funcionais

<center>
<figcaption>Tabela 3 - RF01 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ09</a> | O sistema deve permitir a configuração de um pagamento mensal recorrente |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-2-interatividade-e-suporte-ao-cliente">Épico 2 - Interatividade e Suporte ao Cliente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 2 - Formas de Pagamento </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us09-permitir-pagamento-mensal-recorrente">US09 - Permitir pagamento mensal recorrente</a> |
| Léxico  | -- |
| Casos de uso | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">Casos de Uso(UC02)</a> |
| Cenários | -- |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

<center>
<figcaption>Tabela 4 - RF02 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ12</a> | O aplicativo deve oferecer notificações para lembrar vencimento de contas e ações pendentes. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-2-interatividade-e-suporte-ao-cliente">Épico 2 - Interatividade e Suporte ao Cliente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 9 - Notificação de Vencimento</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us11-notificar-o-usuario-para-lembrar-vencimento-de-contas-e-acoes-pendentes">US11 - Notificar o usuário para lembrar vencimento de contas e ações pendentes.</a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l09-notificacoes-de-vencimento">Léxicos(L09)</a> |
| Casos de uso | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">Casos de Uso(UC01)</a> |
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-9-notificacoes-de-vencimento">Cenários(C9)</a> |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

<center>
<figcaption>Tabela 5 - RF03 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ19</a> | O aplicativo deve permitir ao usuário informar vazamentos na rua ou no hidrômetro |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-3-sustentabilidade-e-consumo-consciente">Épico 3 - Sustentabilidade e Consumo Consciente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 1 - Segunda Via de Conta</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us12-permitir-ao-usuario-informar-vazamentos-na-rua-ou-no-hidrometro">US12 - Permitir ao usuário informar vazamentos na rua ou no hidrômetro.</a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l04-informar-vazamento-na-rua">Léxicos(L04)</a> |
| Casos de uso | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">Casos de Uso(UC01)</a>|
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-4-informar-vazamento-na-rua">Cenários(C4)</a> |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

<center>
<figcaption>Tabela 6 - RF04 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ20</a> | O usuário deve poder atualizar seus dados cadastrais pelo app. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-1-gestao-de-contas-e-pagamentos">Épico 1 - Gestão de Contas e Pagamentos</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 12 - Atualizar Dados Cadastrais </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us10-atualizar-seus-dados-cadastrais-pelo-app">US10 - Atualizar seus dados cadastrais pelo app</a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l06-alterar-titularidade-e-vencimento">Léxicos(L06)</a>  |
| Casos de uso | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">Casos de Uso(UC01)</a> |
| Cenários | -- |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

<center>
<figcaption>Tabela 7 - RF05 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ21</a> | O aplicativo deve permitir agendar atendimento presencial na unidade mais próxima. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-4-servicos-de-atendimento">Épico 4: Serviços de Atendimento</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 13 - Agendar Atendimento Presencial </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us13-permitir-ao-usuario-agendar-atendimento-presencial-na-unidade-mais-proxima">US13 - Permitir ao usuário agendar atendimento presencial na unidade mais próxima</a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l07-agendar-atendimento-presencial">Léxicos(L07)</a> |
| Casos de uso | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">Casos de Uso(UC01)</a> |
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-7-agenda-atendimento-presencial">Cenários(C7)</a> |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

<center>
<figcaption>Tabela 8 - RF06 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ26</a> | O aplicativo deve permitir que o usuário escolha o imóvel desejado. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5 - Interface e Usabilidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 33 - Escolher imóvel desejado </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us33-permitir-pagamento-mensal-recorrente">US33 - Escolher imóvel desejado </a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#lexico-l10-imovel-selecionado"> L10 - Imóvel Selecionado </a>|
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>
</center>

<br>

<center>
<figcaption>Tabela 9 - RF07 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ27</a> | O aplicativo deve reconhecer automaticamente os imóveis associados ao cliente da Caesb. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5 - Interface e Usabilidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 34 - Reconhecimento Automático de Imóveis </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us34-reconhecimento-automatico-de-imoveis">US34 - Reconhecimento automático de imóveis </a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>
</center>

<br>

<center>
<figcaption>Tabela 10 - RF08 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ28</a> | O aplicativo deve considerar o número de pessoas no imóvel para calcular a média do consumo. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-3-sustentabilidade-e-consumo-consciente">Épico 3 - Sustentabilidade e Consumo Consciente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 35 - Consideração do número de pessoas no imóvel </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us35-consideracao-do-numero-de-pessoas-no-imovel">US35 - Consideração do número de pessoas no imóvel </a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>
</center>

<br>

<center>
<figcaption>Tabela 11 - RF09 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ02</a> | O sistema deve ter as funções mais utilizadas/mais buscadas em uma barra. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-2-interatividade-e-suporte-ao-cliente">Épico 2 - Interatividade e Suporte ao Cliente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 17 - Barra de Busca</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#historias-de-usuario_1"> US01 - Barra de busca</a> |
| Léxico  | --|
| Casos de uso | --|
| Cenários | -- |
| NFR | -- |
| Especificação Suplementar | -- |

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>
<br>

<center>
<figcaption>Tabela 12 - RF10 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ04</a> | O sistema deve permitir emitir/visualizar segunda via de conta |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-1-gestao-de-contas-e-pagamentos">Épico 1 - Gestão de Contas e Pagamentos</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 1 - Segunda Via de Conta</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us18-segunda-via-de-conta">US18 - Segunda Via de Conta</a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l01-emitir-a-segunda-via-de-conta">L01 - Emitir a Segunda Via de Conta</a> |
| Casos de uso | --|
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-1-emitir-a-segunda-via-de-conta">Cenário 1 - Emitir a Segunda Via de Conta</a> |
| NFR | -- |
| Especificação Suplementar | -- |

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<figcaption>Tabela 13 - RF11 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ08</a> |O sistema deve oferecer várias formas de pagamento |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-1-gestao-de-contas-e-pagamentos">Épico 1 - Gestão de Contas e Pagamentos</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 2 - Formas de Pagamento</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us19-formas-de-pagamento">US19 - Formas de Pagamento.</a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#lexico-l17-formas-de-pagamento">L17 - Formas de Pagamento</a> |
| Casos de uso | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">UC12 - Formas de Pagamento</a>|
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-17-formas-de-pagamento">Cenário 17 - Formas de Pagamento</a> |
| NFR | -- |
| Especificação Suplementar | -- |

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<figcaption>Tabela 14 - RF12 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ11</a> |O usuário deve poder enviar documentos diretamente pelo aplicativo|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-2-interatividade-e-suporte-ao-cliente">Épico 2 - Interatividade e Suporte ao Cliente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 4 - Envio de Documentos</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us20-envio-de-documentos">US20 - Envio de Documentos</a> |
| Léxico  | --|
| Casos de uso | --|
| Cenários | --|
| NFR | -- |
| Especificação Suplementar | -- |

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<figcaption>Tabela 15 - RF13 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ13</a> |O aplicativo deve incluir suporte a chat ou atendimento virtual para resolver dúvidas dos usuários|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-2-interatividade-e-suporte-ao-cliente">Épico 2 - Interatividade e Suporte ao Cliente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 5 - Suporte por Chat</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us21-chat-ou-atendimento-virtual">US21 - Chat ou Atendimento Virtual</a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l08-suporte-de-chat-ou-atendimento">L08 - Suporte de Chat ou Atendimento</a> |
| Casos de uso |  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">UC08 - Suporte de Chat ou Atendimento</a> |
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-8-suporte-de-chat-ou-atendimento">Cenário 8 - Suporte de Chat ou Atendimento</a>|
| NFR | -- |
| Especificação Suplementar | -- |

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<figcaption>Tabela 16 - RF14 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ14</a> |A funcionalidade "Informar vazamento na rua" deve mostrar apenas o mapa das regiões em que a Caesb atua|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-3-sustentabilidade-e-consumo-consciente">Épico 3 - Sustentabilidade e Consumo Consciente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 6 - Informar Vazamentos</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us22-informar-vazamento">US22 - Informar Vazamento</a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l04-informar-vazamento-na-rua">L04 - Informar Vazamento na Rua</a> |
| Casos de uso |  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">UC04 - Informar Vazamento</a> |
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-4-informar-vazamento-na-rua">Cenário 4 - Informar Vazamento na Rua</a>|
| NFR | -- |
| Especificação Suplementar | -- |

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>
<br>

<center>
<figcaption>Tabela 17 - RF15 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ15</a> |O usuário deve poder informar e visualizar informações sobre a falta de água|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-3-sustentabilidade-e-consumo-consciente">Épico 3 - Sustentabilidade e Consumo Consciente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 7 - Informações de Falta de Água</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us23-informar-e-visualizar-falta-de-agua">US23 - Informar e Visualizar Falta de Água</a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l02-informar-falta-dagua">L02 - Informar Falta d'Água</a> |
| Casos de uso |  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">UC02 - Informar Falta d'Água</a> |
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-2-informar-falta-dagua">Cenário 2 - Informar Falta d'Água</a>|
| NFR | -- |
| Especificação Suplementar | -- |

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<figcaption>Tabela 18 - RF16 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ01</a> |O sistema deve ter uma barra de busca.|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-3-sustentabilidade-e-consumo-consciente">Épico 2 - Interatividade e Suporte ao Cliente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 17 - Barra de Busca</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us23-informar-e-visualizar-falta-de-agua">US01 - Barra de busca</a> |
| Léxico  | -- |
| Casos de uso | -- |
| Cenários | -- |
| NFR | -- |
| Especificação Suplementar | -- |

 Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

<center>
<figcaption>Tabela 19 - RF17 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ23</a> |O usuário deve poder registrar e acompanhar ordens de serviço.|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-3-sustentabilidade-e-consumo-consciente">Épico 4: Serviços de Atendimento</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 18 - Registro e Acompanhamento de Ordens de Serviço</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us23-informar-e-visualizar-falta-de-agua">US02 - Registrar e acompanhar ordens de serviço.</a> |
| Léxico  | -- |
| Casos de uso | -- |
| Cenários | -- |
| NFR | -- |
| Especificação Suplementar | -- |

 Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

<br>

<center>
<figcaption>Tabela 20 - RF18 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ35</a> | O aplicativo deve estar em conformidade com os padrões de acessibilidade da última versão da WCAG. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-3-sustentabilidade-e-consumo-consciente">Épico 5: Interface e Usabilidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 19 - Conformidade com Padrões de Acessibilidade</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us23-informar-e-visualizar-falta-de-agua">US03 - Conformidade com os padrões de acessibilidade da WCAG.</a> |
| Léxico  | -- |
| Casos de uso | -- |
| Cenários | -- |
| NFR | NFR Framework - NFR05: Manutenibilidade |
| Especificação Suplementar | -- |

 Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

<center>
<figcaption>Tabela 21 - RF19 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#metodologia">RQ03</a> | O sistema deve permitir acessar/pagar contas anteriores |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-1-gestao-de-contas-e-pagamentos">Épico 1: Gestão de Contas e pagamentos</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 25 - Acesso/Pagamento de contas passadas</a> |
| História de Usuário | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us25-acessopagamento-de-contas-passadas">US25 - Acesso/Pagamento de Contas passadas |
| Léxico  |  <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l01-emitir-a-segunda-via-de-conta"> L01: Emitir segunda via de conta|
| Casos de uso | -- |
| Cenários | -- |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/Ninja-Haiyai">Matheus Barros</a>
</center>

<br>

<center>
<figcaption>Tabela 22 - RF20 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#metodologia">RQ05</a> | O sistema deve permitir consultar consumo |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-1-gestao-de-contas-e-pagamentos">Épico 1: Gestão de Contas e pagamentos</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 26 - Consulta de consumo</a> |
| História de Usuário | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us26-consulta-de-consumo">US26 - Consulta de Consumo|
| Léxico  |  <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l05-consultar-historico-de-consumo"> L05: Consultar Histórico de Consumo |
| Casos de uso | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso"> UC05 -  Consultar histórico de consumo|
| Cenários | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-5-consultar-historico-de-consumo"> Cenário 5 -  Consultar histórico de consumo |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/Ninja-Haiyai">Matheus Barros</a>
</center>

<br>

<center>
<figcaption>Tabela 22 - RF20 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#metodologia">RQ06</a> | O sistema deve permitir bloqueio, reativação ou solicitação de reparo |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-4-servicos-de-atendimento">Épico 4: Serviços de atendimento </a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 31 - Bloqueio e reativação de conta</a> |
| História de Usuário | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us27-bloqueioreativacaosolicitacao-de-reparo">US27 - Bloqueio/Reativação/Solicitação de Reparo|
| Léxico  |  -- |
| Casos de uso | --|
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-18-bloqueio-reativacao-solicitacao-de-reparo">Cenário 18: Bloqueio/Reativação/Solicitação de Reparo</a> |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/Ninja-Haiyai">Matheus Barros</a>
</center>

<br>

<center>
<figcaption>Tabela 23 - RF21 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#metodologia">RQ16</a> | O sistema deve permitir ao usuário corrigir erros retornando à tela anterior e atualizando dados |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-2-interatividade-e-suporte-ao-cliente">Épico 2: Interatividade e Suporte ao Cliente </a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 27 - Correção de dados</a> |
| História de Usuário | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us28-correcao-de-erros">US28 - Correção de Erros|
| Léxico  |  <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#lexico-l16-simulacao-de-tarifas"> L16 - Simulação de Tarifas  |
| Casos de uso | --|
| Cenários |-- |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/Ninja-Haiyai">Matheus Barros</a>
</center>

<br>

<center>
<figcaption>Tabela 24 - RF22 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#metodologia">RQ18</a> | A funcionalidade "Simulação de tarifa" deve ser nativa do aplicativo e não redirecionar ao site da Caesb.|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-1-gestao-de-contas-e-pagamentos">Épico 1: Gestão de contas e pagamentos </a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 29 - Simulação de Tarifa</a> |
| História de Usuário | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us29-simulacao-de-tarifa">US29 - Simulação de Tarifa|
| Léxico  |  -- |
| Casos de uso | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso"> US11 - Simulação de Tarifa|
| Cenários |<a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-16-simulacao-de-tarifa"> Cenário 16: Simulação de Tarifa|
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/Ninja-Haiyai">Matheus Barros</a>
</center>

<br>

<center>
<figcaption>Tabela 25 - RF23 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#metodologia">RQ22</a> |O aplicativo deve exibir dicas de consumo consciente e economia de água.|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-3-sustentabilidade-e-consumo-consciente">Épico 3: Sustentabilidade e Consumo Consciente </a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 30 - Dicas de Consumo Consciente</a> |
| História de Usuário | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us30-dicas-de-consumo-consciente">US30 - Dicas de Consumo Consciente|
| Léxico  |  -- |
| Casos de uso | -- |
| Cenários |-- |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/Ninja-Haiyai">Matheus Barros</a>
</center>

<br>

<center>
<figcaption>Tabela 26 - RF24 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#metodologia">RQ24</a> |O aplicativo deve disponibilizar alertas sobre manutenção programada.|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-3-sustentabilidade-e-consumo-consciente">Épico 2: Interatividade e Suporte ao Cliente </a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 28 - Alertas de Manutenção</a> |
| História de Usuário | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us31-alertas-sobre-manutencao-programada">US31 - Alertas sobre Manutenção Programada|
| Léxico  |  -- |
| Casos de uso | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">UC12 - Alertas sobre Manutenção Programada|
| Cenários |-- |
| NFR | -- |
| Especificação Suplementar | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/especSup/#suportabilidade"> Suportabilidade |

Autor(a): <a href="https://github.com/Ninja-Haiyai">Matheus Barros</a>
</center>

 <br>

<center>
<figcaption>Tabela 27 - RF25 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#metodologia">RQ25</a> |O usuário pode solicitar alteração na titularidade da conta.|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-4-servicos-de-atendimento">Épico 4: Serviços de Atendimento </a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 32 - Permitir ao usuário solicitar alteração na titularidade da conta </a> |
| História de Usuário | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us32-alteracao-na-titularidade-da-conta">US32 - Alteração na titularidade da Conta.|
| Léxico  | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l06-alterar-titularidade-e-vencimento">L06: Alterar Titularidade e Vencimento   |
| Casos de uso | <a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">UC06 - Alterar titularidade e vencimento|
| Cenários |<a href= "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-6-alterar-titularidade-e-vencimento"> Cenário 6: Alterar Titularidade e Vencimento |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/Ninja-Haiyai">Matheus Barros</a>
</center>

## Requisitos Não-Funcionais

<center>
<figcaption>Tabela 18 - RNF01 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ31</a> | O aplicativo deve incluir um tutorial inicial para ajudar novos usuários a se familiarizarem. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5: Interface e Usabilidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 14 - Tutorial Inicial </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us14-incluir-um-tutorial-inicial-para-ajudar-novos-usuarios-a-se-familiarizarem">US14 - Incluir um tutorial inicial para ajudar novos usuários a se familiarizarem</a> |
| Léxico  | -- |
| Casos de uso | -- |
| Cenários | -- |
| NFR | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/nfr/#nfr-framework-nfr01-usabilidade">NFR Framework - NFR01: Usabilidade</a> |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<center>
<figcaption>Tabela 19 - RNF02 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ32</a> | O aplicativo deve oferecer suporte a múltiplos idiomas para atender usuários diversificados. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5: Interface e Usabilidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 15 - Suporte a Múltiplos Idiomas </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us15-oferecer-suporte-a-multiplos-idiomas-para-atender-usuarios-diversificados">US15 - Oferecer suporte a múltiplos idiomas para atender usuários diversificados.</a> |
| Léxico  | -- |
| Casos de uso | -- |
| Cenários | -- |
| NFR | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/nfr/#nfr-framework-nfr01-usabilidade">NFR Framework - NFR01: Usabilidade</a> |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<center>
<figcaption>Tabela 20 - RNF03 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ38</a> | O aplicativo deve se adaptar a diferentes tamanhos de tela. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5: Interface e Usabilidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 16 - Responsividade </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us16-adaptar-a-diferentes-tamanhos-de-tela">US16 - Adaptar a diferentes tamanhos de tela.</a> |
| Léxico  | -- |
| Casos de uso | -- |
| Cenários | -- |
| NFR | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/nfr/#nfr-framework-nfr01-usabilidade">NFR Framework - NFR01: Usabilidade</a> |
| Especificação Suplementar |  href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/especSup/#usabilidade">ES de Usabilidade</a>      |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<center>
<figcaption>Tabela 21 - RNF04 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ33</a> | O aplicativo deve ser compatível com as versões mais recentes do Android e iOS. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5 - Interface e Usabilidade</a>  |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 36 - Compatibilidade com Android e iOS </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us36-compatibilidade-com-android-e-ios">US36 - Compatibilidade com Android e iOS </a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>
</center>

<center>
<figcaption>Tabela 22 - RNF05 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ36</a> | O aplicativo deve ter uma interface intuitiva, organizada e fácil de usar. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5 - Interface e Usabilidade</a>  |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 37 - Interface Intuitiva e Organizada </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us37-interface-intuitiva-e-organizada">US37 - Interface intuitiva e organizada </a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>
</center>

<center>
<figcaption>Tabela 23 - RNF06 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ37</a> |  	O sistema deve minimizar o número de cliques necessários para interações. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5 - Interface e Usabilidade</a>  |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 38 - Minimizar Número de Cliques </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us38-minimizacao-do-numero-de-cliques-necessarios-para-interacoes">US38 - Minimização do número de cliques necessários para interações </a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>
</center>

<center>
<figcaption>Tabela 24 - RNF07 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ39</a> |  	O aplicativo deve permitir suporte offline para funcionalidades básicas, como visualização de contas armazenadas. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-6-desempenho-e-funcionalidades-offline">Épico 6 - Desempenho e Funcionalidades Offline</a>  |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 39 - Suporte Offline </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us39-suporte-offline">US39 - Suporte Offline </a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>
</center>

<center>
<figcaption>Tabela 25 - RNF08 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ40</a> |  	O aplicativo deve ter tempos de resposta inferiores a 2 segundos para a maioria das funcionalidades. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-6-desempenho-e-funcionalidades-offline">Épico 6 - Desempenho e Funcionalidades Offline</a>  |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 40 - Tempo de Resposta Inferior a 2 Segundos </a> |
| História de Usuário | <a href="hhttps://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us40-tempos-de-resposta-inferiores-a-2-segundos-para-funcionalidades">US40 - Tempos de resposta inferiores a 2 segundos para funcionalidades </a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>
</center>

<br>

<center>
<figcaption>Tabela 26 - RNF09 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ34</a> |O aplicativo deve garantir segurança com os dados dos usuários|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-7-seguranca-e-privacidade">Épico 7 - Segurança e Privacidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 8 - Segurança de Dados</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us24-seguranca-dos-dados">US24 - Segurança dos Dados</a> |
| Léxico  | -- |
| Casos de uso | --|
| Cenários | --|
| NFR | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/nfr/#nfr-framework-nfr03-confiabilidade">NFR Framework - NFR03: Confiabilidade</a>  |
| Especificação Suplementar |  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/especSup/#confiabiliade">Especificação Suplementar - Confiabilidade</a> |

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>


## Referências

><p> POHL, Klaus. RUPP, Chris. Requirements Engineering Fundamentals. Disponível em: <a href= https://aprender3.unb.br/pluginfile.php/2972562/mod_resource/content/2/Rastreabilidade.pdf> https://aprender3.unb.br/pluginfile.php/2972562/mod_resource/content/2/Rastreabilidade.pdf </a>. Acesso em 14 de Jan. de 2024.</p>

><p> Requisitos - Aula 26 - Profa.Milene e Prof.Mauricio. Disponível em: <a href= https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf> https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf </a>. Acesso em 14 de Jan. de 2024.</p>


## Histórico de Versão

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 14/01/2024 | Criação do artefato  | [Natan Almeida](https://github.com/natanalmeida03) <br> [João Victor Marques](https://github.com/jmarquees) | [Leandro de Almeida](https://github.com/leomitx10) |
|  1.1   | 15/01/2024 | Adição de requisitos  | [Natan Almeida](https://github.com/natanalmeida03) | [Leandro de Almeida](https://github.com/leomitx10) |
|  1.2   | 16/01/2024 | Adição de requisitos  | [Joao Victor Marques](https://github.com/jmarquees) | [Leandro de Almeida](https://github.com/leomitx10) |
|  1.3   | 16/01/2024 | Adição de requisitos não funcionais  | [Joao Victor Marques](https://github.com/jmarquees) | [Leandro de Almeida](https://github.com/leomitx10) |
|  1.4   | 16/01/2024 | Adição de requisitos funcionais e não funcionais  | [Letícia Resende ](https://github.com/LeticiaResende23) | [Natan Almeida](https://github.com/natanalmeida03) |