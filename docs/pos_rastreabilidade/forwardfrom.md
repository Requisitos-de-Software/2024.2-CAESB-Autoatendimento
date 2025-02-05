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
| C       | Cenários                  |
| L       | Léxico                    |
| ES      | Especificação Suplementar |
| UC      | Caso de Uso               |

</center>

<p align="justify">&emsp;&emsp; A Tabela 2 e 3 apresenta as relações entre os requisitos e os artefatos correspondentes, com ela é possível visualizar quais artefatos estão associados a cada requisito, fornecendo uma visão clara das dependências e do contexto de implementação.</p>

<center>
<figcaption>Tabela 2 - modelo requisito funcional</figcaption>

| ID do requisito | Descrição do requisito |
| :-: | :-: |
| Épico | Épico de referência |
| Feature | Feature do Backlog |
| História de Usuário | História de usuário |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| Critério de aceitação | Critério |
| Elo | Elo relacionado |
| Implementado | Requisito implementado |

</center>

<center>
<figcaption>Tabela 3 - modelo requisito não funcional</figcaption>

| ID do requisito | Descrição do requisito |
| :-: | :-: |
| Épico | Épico de referência |
| Feature | Feature do Backlog |
| Léxico  | Léxico relacionado |
| Cenários | Cenário relacionado |
| NFR | Softgoals relacionado |
| Especificação Suplementar | Categoria | 
| Elo | Elo relacionado |
| Implementado | Requisito implementado |

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
| Critério de aceitação |  Deve haver opção de cadastrar um cartão de crédito para para pagamento recorrente. |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO17</a> |
| Implementado | Não |
| Versionamento| Requisito não foi modificado|

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
| Critério de aceitação | - Deve haver opção de ativar notificações. - O aplicativo envia uma notificação quando estiver perto do vencimento da conta ou com ações pendentes. |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO18</a> |
| Implementado | Não |
| Versionamento| Requisito não foi modificado|

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
| Critério de aceitação | - O sistema deve permitir que o usuário informe o local e a natureza do vazamento (rua ou hidrômetro). - Deve haver um campo para anexar fotos e uma descrição do problema. - O sistema deve confirmar o recebimento da solicitação. |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO19</a> |
| Implementado | sim <br> <img src="https://i.ibb.co/71gk2Jt/qqq.jpg" style="height:200px;">|
| Versionamento| Requisito não foi modificado|

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
| Critério de aceitação | - Deve haver opção de atualizar dados como nome, sexo, email e telefone. |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO20</a> |
| Implementado | Sim |
| Versionamento| Requisito não foi modificado|

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
| Critério de aceitação | - O sistema deve exibir as unidades disponíveis com base na localização do usuário. - Deve ser possível escolher data e horário entre as opções disponíveis. - O sistema deve enviar uma confirmação do agendamento. |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO21</a> |
| Implementado | Não |
| Versionamento| Requisito não foi modificado|

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
| Critério de aceitação |<p align="justify"> - Na página principal do aplicativo, deve haver uma barra de busca visível no topo ou em local destacado <br> - Ao digitar na barra de busca, os eventos listados devem ser filtrados em tempo real para corresponder aos termos inseridos. <br> - A busca deve suportar diferentes critérios, como nome do evento e palavras-chave.</p> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO9</a> |
| Implementado | Não |
| Versionamento| Requisito não foi modificado|

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>
<br>

<center>
<figcaption>Tabela 12 - RF10 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ04</a> | O sistema deve permitir emitir/visualizar segunda via de conta |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-1-gestao-de-contas-e-pagamentos">Épico 1 - Gestão de Contas e Pagamentos</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 1 - Segunda Via de Conta</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us14-segunda-via-de-conta">US14 - Segunda Via de Conta</a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l01-emitir-a-segunda-via-de-conta">L01 - Emitir a Segunda Via de Conta</a> |
| Casos de uso | --|
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-1-emitir-a-segunda-via-de-conta">Cenário 1 - Emitir a Segunda Via de Conta</a> |
| Critério de aceitação |<p align="justify"> - Deve haver uma opção visível para emitir ou visualizar a segunda via da conta. <br> - A segunda via deverá estar disponível para download em formato PDF. <br> -  O sistema deve exibir um histórico de contas pagas e em aberto.</p> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO10</a> |
| Implementado | sim <br> <img src="https://github.com/user-attachments/assets/3d813d4b-92e9-4b2e-9070-9d288a3b15db" style="height:200px;"> <img src="https://github.com/user-attachments/assets/66ba9b17-9159-4cbe-b93c-d3ba09bb5e5a" style="height:200px;"> <img src="https://github.com/user-attachments/assets/e1b6d0e8-725c-4373-8418-85aa61a8f26a" style="height:200px;">  |
| Versionamento| Requisito não foi modificado|

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<figcaption>Tabela 13 - RF11 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ08</a> |O sistema deve oferecer várias formas de pagamento |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-1-gestao-de-contas-e-pagamentos">Épico 1 - Gestão de Contas e Pagamentos</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 2 - Formas de Pagamento</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us15-formas-de-pagamento">US15 - Formas de Pagamento.</a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#lexico-l17-formas-de-pagamento">L17 - Formas de Pagamento</a> |
| Casos de uso | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">UC12 - Formas de Pagamento</a>|
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-17-formas-de-pagamento">Cenário 17 - Formas de Pagamento</a> |
| Critério de aceitação |<p align="justify"> - O sistema deve oferecer métodos de pagamento como cartão de crédito, débito, PIX e boleto bancário. <br> - O usuário deverá receber uma confirmação de pagamento imediatamente após o processo ser concluído. <br> - As opções de pagamento devem ser acessíveis em uma área destacada do aplicativo.</p> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO11</a> |
| Implementado | Não |
| Versionamento| Requisito não foi modificado|

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<figcaption>Tabela 14 - RF12 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ11</a> |O usuário deve poder enviar documentos diretamente pelo aplicativo|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-2-interatividade-e-suporte-ao-cliente">Épico 2 - Interatividade e Suporte ao Cliente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 4 - Envio de Documentos</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us16-envio-de-documentos">US16 - Envio de Documentos</a> |
| Léxico  | --|
| Casos de uso | --|
| Cenários | --|
| Critério de aceitação |<p align="justify"> - Deve haver uma funcionalidade para anexar e enviar documentos no formato PDF ou imagem (JPEG/PNG). <br> - O sistema deve confirmar o envio dos documentos com uma notificação ou mensagem no aplicativo. <br> - Os documentos enviados devem ser armazenados com segurança e condicionados ao perfil do usuário.</p> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO12</a> |
| Implementado | Não|
| Versionamento| Requisito não foi modificado|

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<figcaption>Tabela 15 - RF13 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ13</a> |O aplicativo deve incluir suporte a chat ou atendimento virtual para resolver dúvidas dos usuários|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-2-interatividade-e-suporte-ao-cliente">Épico 2 - Interatividade e Suporte ao Cliente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 5 - Suporte por Chat</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us17-chat-ou-atendimento-virtual">US17 - Chat ou Atendimento Virtual</a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l08-suporte-de-chat-ou-atendimento">L08 - Suporte de Chat ou Atendimento</a> |
| Casos de uso |  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">UC08 - Suporte de Chat ou Atendimento</a> |
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-8-suporte-de-chat-ou-atendimento">Cenário 8 - Suporte de Chat ou Atendimento</a>|
| Critério de aceitação |<p align="justify"> - O aplicativo deve incluir um chatbot com respostas automáticas para perguntas frequentes e escalonamento para atendimento humano, se necessário. <br> - O chat deve estar acessível na página principal ou no menu de suporte. <br> - O sistema deve armazenar o histórico de conversas para referência futura.</p> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO13</a> |
| Implementado | Não |
| Versionamento| Requisito não foi modificado|

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<figcaption>Tabela 16 - RF14 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ14</a> |A funcionalidade "Informar vazamento na rua" deve mostrar apenas o mapa das regiões em que a Caesb atua|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-3-sustentabilidade-e-consumo-consciente">Épico 3 - Sustentabilidade e Consumo Consciente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 6 - Informar Vazamentos</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us18-informar-vazamento">US18 - Informar Vazamento</a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l04-informar-vazamento-na-rua">L04 - Informar Vazamento na Rua</a> |
| Casos de uso |  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">UC04 - Informar Vazamento</a> |
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-4-informar-vazamento-na-rua">Cenário 4 - Informar Vazamento na Rua</a>|
| Critério de aceitação |<p align="justify"> - O sistema deve permitir que o usuário informe o local e a natureza do vazamento (rua ou hidrômetro). <br> - Deve haver um campo para anexar fotos e uma descrição do problema. <br> - O sistema deve confirmar o recebimento da solicitação.</p> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO14</a> |
| Implementado | sim <br> <img src="https://github.com/user-attachments/assets/8427e72a-13d7-4291-bfbd-070324e9bd85" style="height:200px;"> <img src="https://github.com/user-attachments/assets/794f2c53-77f8-4dc7-905a-8787394aa8c1" style="height:200px;"> <img src="https://github.com/user-attachments/assets/eb4ceacc-33e2-4d4d-8372-f490802cb193" style="height:200px;"> |
| Versionamento| Requisito não foi modificado|

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>
<br>

<center>
<figcaption>Tabela 17 - RF15 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ15</a> |O usuário deve poder informar e visualizar informações sobre a falta de água|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-3-sustentabilidade-e-consumo-consciente">Épico 3 - Sustentabilidade e Consumo Consciente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 7 - Informações de Falta de Água</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us19-informar-e-visualizar-falta-de-agua">US19 - Informar e Visualizar Falta de Água</a> |
| Léxico  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l02-informar-falta-dagua">L02 - Informar Falta d'Água</a> |
| Casos de uso |  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso">UC02 - Informar Falta d'Água</a> |
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-2-informar-falta-dagua">Cenário 2 - Informar Falta d'Água</a>|
| Critério de aceitação |<p align="justify"> - O aplicativo deve permitir que o usuário registre falta de água com informações como local, dados e hora. <br> - O sistema deve exibir notificações sobre falta de água em andamento na região do usuário. <br> - As informações devem ser atualizadas em tempo real e apresentar o status da resolução do problema.</p> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO15</a> |
| Implementado | sim <br> <img src="https://github.com/user-attachments/assets/64300815-a12c-4457-9133-e1525a1fe3d0" style="height:200px;"> <img src="https://github.com/user-attachments/assets/cabbffa8-cba4-4dba-b363-b494ceec2262" style="height:200px;"> <img src="https://github.com/user-attachments/assets/a0dbe900-80ec-421e-b500-6493a383787e" style="height:200px;"> |
| Versionamento| Requisito não foi modificado|

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<figcaption>Tabela 18 - RF16 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/" target = "_blank">RQ01</a> |O sistema deve ter uma barra de busca|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-2-interatividade-e-suporte-ao-cliente"target = "_blank">Épico 2 - Interatividade e Suporte ao Cliente</a>  |
| Feature |  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features"target = "_blank">Feature 17 - Barra de Busca</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us01-barra-de-busca"target = "_blank">US01 - Barra de busca</a> |
| Léxico  | -- |
| Casos de uso |  -- |
| Cenários | --|
| Critério de aceitação |<p align="justify">- Na página principal do aplicativo, deve haver uma barra de busca visível no topo ou em local destacado.<br> - Ao digitar na barra de busca, os eventos listados devem ser filtrados em tempo real para corresponder aos termos inseridos. <br>- A busca deve suportar diferentes critérios, como nome do evento e palavras-chave.</p> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO25</a> |
| Implementado | Não|
| Versionamento| Requisito não foi modificado|

 Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

<center>
<figcaption>Tabela 19 - RF17 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/"target = "_blank">RQ23</a> |O usuário deve poder registrar e acompanhar ordens de serviço|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-4-servicos-de-atendimento"target = "_blank">Épico 4: Serviços de Atendimento</a>  |
| Feature |  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features"target = "_blank">Feature 18 - Registro e Acompanhamento de Ordens de Serviço</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us02-registrar-e-acompanhar-ordens-de-servico"target = "_blank">US02 - Registrar e acompanhar ordens de serviço</a> |
| Léxico  | -- |
| Casos de uso |  -- |
| Cenários | --|
| Critério de aceitação |<p align="justify">- Na página principal do aplicativo, deve haver uma barra de busca visível no topo ou em local destacado.<br> - Ao digitar na barra de busca, os eventos listados devem ser filtrados em tempo real para corresponder aos termos inseridos. <br>- A busca deve suportar diferentes critérios, como nome do evento e palavras-chave.</p> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO26</a> |
| Implementado | Não |
| Versionamento| Requisito não foi modificado|

 Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

<center>
<figcaption>Tabela 20 - RF18 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/"target = "_blank">RQ30</a> | O aplicativo deve permitir que o usuário busque um atendimento pelo protocolo |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-2-interatividade-e-suporte-ao-cliente"target = "_blank">Épico 2 - Interatividade e Suporte ao Cliente</a>  |
| Feature |  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features"target = "_blank">Feature 20 - Busca de Atendimento por Protocolo</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us04-buscar-atendimento-pelo-protocolo"target = "_blank">US04 - Buscar atendimento pelo protocolo.</a> |
| Léxico  | -- |
| Casos de uso |  -- |
| Cenários | --|
| Critério de aceitação |<p align="justify"> - Deve haver um campo de busca na interface do aplicativo, onde o usuário possa inserir o número do protocolo.<br> - Após digitar o protocolo e confirmar a busca, o sistema deve exibir os detalhes do atendimento correspondente, como status, data de registro, e descrição. <br> - Caso o protocolo não seja encontrado, o sistema deve informar ao usuário que não há registros correspondentes. <br> - A busca pelo protocolo deve ser rápida, com retorno dos resultados em até 5 segundos.</p> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO28</a> |
| Implementado | Não |
| Versionamento| Requisito não foi modificado|

 Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

<center>
<figcaption>Tabela 21 - RF19 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/"target = "_blank">RQ29</a> | O aplicativo deve permitir que o usuário altere o vencimento da conta |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-1-gestao-de-contas-e-pagamentos"target = "_blank">Épico 1 - Gestão de Contas e Pagamentos</a>  |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features"target = "_blank">Feature 21 - Alteração do Vencimento da Conta</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us05-alterar-o-vencimento-da-conta"target = "_blank">US05 - Alterar o vencimento da conta</a> |
| Léxico  | <a href = "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#l06-alterar-titularidade-e-vencimento" target = "_blank">L06 - Alterar Titularidade e Vencimento</a> |
| Casos de uso |  <a href = "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso" target = "_blank">UC06 - Alterar Titularidade e Vencimento</a> |
| Cenários | <a href = "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-6-alterar-titularidade-e-vencimento" target = "_blank">Cenário 6 - Alterar Titularidade e Vencimento</a> |
| Critério de aceitação |<p align="justify"> - Deve haver um campo de busca na interface do aplicativo, onde o usuário possa inserir o número do protocolo.<br> - Deve haver uma opção na interface do aplicativo para alterar a data de vencimento da conta, localizada de forma clara e acessível. <br> - O sistema deve permitir que o usuário selecione uma nova data dentro de um intervalo permitido (ex.: do dia 1 ao dia 28 de cada mês). <br> - Após a alteração, o sistema deve confirmar a mudança e informar ao usuário a nova data de vencimento. <br> - Caso a alteração não seja possível (ex.: devido a restrições de contrato), o sistema deve apresentar uma mensagem explicativa ao usuário.</p> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO29</a> |
| Implementado | Não |
| Versionamento| Requisito não foi modificado|

 Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

<center>
<figcaption>Tabela 22 - RF20 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/"target = "_blank">RQ07</a> | O sistema deve exibir pequenas descrições ao lado dos serviços para mostrar seu estado atual |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade" target = "_blank">Épico 5 - Interface e Usabilidade.</a>  |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features" target = "_blank">Feature 22 - Exibição de Estado Atual dos Serviços</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us06-exibir-pequenas-descricoes-ao-lado-dos-servicos" target = "_blank">US06 - Exibir pequenas descrições ao lado dos serviços</a> |
| Léxico  | -- |
| Casos de uso | -- |
| Cenários | -- |
| Critério de aceitação |<p align="justify"> - O sistema deve exibir uma breve descrição ou rótulo ao lado de cada serviço listado, indicando claramente seu estado atual (ex.: "Em Andamento", "Concluído", "Pendente"). <br>- As descrições devem ser dinâmicas e atualizadas automaticamente quando o estado do serviço for alterado.<br>- As informações exibidas devem ser concisas, com no máximo 2-3 palavras para evitar poluição visual.<br>- O design deve ser responsivo, garantindo que as descrições sejam legíveis em dispositivos móveis e telas menores.</p> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO30</a> |
| Implementado | Não |
| Versionamento| Requisito não foi modificado|

 Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

<center>
<figcaption>Tabela 23 - RF21 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/" target = "_blank">RQ10</a> | O sistema deve possibilitar o adiantamento de processos via aplicativo |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-4-servicos-de-atendimento" target = "_blank">Épico 4 - Serviços de Atendimento</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features" target = "_blank">Feature 23 - Adiantamento de Processos</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us07-adiantamento-de-processos-via-aplicativo" target = "_blank">US07 - Adiantamento de processos via aplicativo</a> |
| Léxico  | -- |
| Casos de uso | -- |
| Cenários | -- |
| Critério de aceitação |<p align="justify"> - Deve haver uma opção no aplicativo que permita ao usuário solicitar o adiantamento de um processo, visível em locais relevantes (ex.: detalhes do processo).<br>- O sistema deve apresentar as condições e requisitos para que o adiantamento seja possível, como taxas ou documentos necessários.<br>- Após solicitar o adiantamento, o usuário deve receber uma confirmação com o novo status e um prazo atualizado.<br>- Caso o adiantamento não seja possível, o sistema deve informar os motivos e sugerir alternativas (se aplicável).</p> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO31</a> |
| Implementado | Não |
| Versionamento| Requisito não foi modificado |

 Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

<center>
<figcaption>Tabela 24 - RF22 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/"target = "_blank">RQ17</a> | A funcionalidade "Atendimentos" deve permitir filtros por ano, mês, status (finalizado ou em andamento) |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-4-servicos-de-atendimento"target = "_blank">Épico 4 - Serviços de Atendimento</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features"target = "_blank">Feature 24 - Filtros para Consultar Atendimentos</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us08-filtrar-atendimentos-por-ano-mes-e-status"target = "_blank">US08 - Filtrar atendimentos por ano, mês e status</a> |
| Léxico  | <a href = "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/lexicos/#lexico-l15-filtro-de-atendimentos" target = "_blank">L15 - Filtro de Atendimentos</a> |
| Casos de uso | <a href = "https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/#especializacao-dos-casos-de-uso" target = "_blank">UC10 - Filtro de Atendimentos</a> |
| Cenários | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/cenarios/#cenario-15-filtro-de-atendimentos" target = "_blank">Cenário 15 - Filtro de atendimentos</a> |
| Critério de aceitação |<p align="justify"> - Deve haver opções de filtro claras e acessíveis na funcionalidade "Atendimentos".<br>- O sistema deve permitir selecionar um ou mais dos seguintes critérios de filtro: ano, mês e status (finalizado ou em andamento).<br>- Após aplicar os filtros, a lista de atendimentos exibida deve ser atualizada automaticamente para mostrar apenas os registros correspondentes.<br>- O sistema deve permitir combinar filtros (ex.: filtrar por ano e status ao mesmo tempo).
<br>- Deve haver uma opção para limpar os filtros aplicados e retornar à lista completa de atendimentos.</p> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO32</a> |
| Implementado | Não |
| Versionamento| Requisito não foi modificado |

 Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

<center>
<figcaption>Tabela 25 - RF23 </figcaption>

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
<figcaption>Tabela 26 - RF24 </figcaption>

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
<figcaption>Tabela 27 - RF25 </figcaption>

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
<figcaption>Tabela 28 - RF26 </figcaption>

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
<figcaption>Tabela 29 - RF27 </figcaption>

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
<figcaption>Tabela 30 - RF28 </figcaption>

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
<figcaption>Tabela 31 - RF29 </figcaption>

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
<figcaption>Tabela 32 - RF30 </figcaption>

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
<figcaption>Tabela 33 - RNF01 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ31</a> | O aplicativo deve incluir um tutorial inicial para ajudar novos usuários a se familiarizarem. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5: Interface e Usabilidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 14 - Tutorial Inicial </a> |
| NFR | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/nfr/#nfr-framework-nfr01-usabilidade">NFR Framework - NFR01: Usabilidade</a> |
| Especificação Suplementar | -- |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO22</a> |
| Implementado | Não |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<center>
<figcaption>Tabela 34 - RNF02 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ32</a> | O aplicativo deve oferecer suporte a múltiplos idiomas para atender usuários diversificados. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5: Interface e Usabilidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 15 - Suporte a Múltiplos Idiomas </a> |
| NFR | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/nfr/#nfr-framework-nfr01-usabilidade">NFR Framework - NFR01: Usabilidade</a> |
| Especificação Suplementar | -- |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO23</a> |
| Implementado | Não |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<center>
<figcaption>Tabela 35 - RNF03 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ38</a> | O aplicativo deve se adaptar a diferentes tamanhos de tela. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5: Interface e Usabilidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 16 - Responsividade </a> |
| NFR | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/nfr/#nfr-framework-nfr01-usabilidade">NFR Framework - NFR01: Usabilidade</a> |
| Especificação Suplementar |  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/especSup/#usabilidade">ES de Usabilidade</a>      |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO24</a> |
| Implementado | Não |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<center>
<figcaption>Tabela 36 - RNF04 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ33</a> | O aplicativo deve ser compatível com as versões mais recentes do Android e iOS. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5 - Interface e Usabilidade</a>  |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 36 - Compatibilidade com Android e iOS </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us36-compatibilidade-com-android-e-ios">US36 - Compatibilidade com Android e iOS </a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/especSup/#suportabilidade">Especificação Suplementar - Suportabilidade</a> |

Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>
</center>

<center>
<figcaption>Tabela 37 - RNF05 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ36</a> | O aplicativo deve ter uma interface intuitiva, organizada e fácil de usar. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5 - Interface e Usabilidade</a>  |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 37 - Interface Intuitiva e Organizada </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us37-interface-intuitiva-e-organizada">US37 - Interface intuitiva e organizada </a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/especSup/#usabilidade">Especificação Suplementar - Usabilidade</a> |

Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>
</center>

<center>
<figcaption>Tabela 38 - RNF06 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ37</a> |  	O sistema deve minimizar o número de cliques necessários para interações. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5 - Interface e Usabilidade</a>  |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 38 - Minimizar Número de Cliques </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us38-minimizacao-do-numero-de-cliques-necessarios-para-interacoes">US38 - Minimização do número de cliques necessários para interações </a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/especSup/#usabilidade">Especificação Suplementar - Usabilidade</a> |

Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>
</center>

<center>
<figcaption>Tabela 39 - RNF07 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ39</a> |  	O aplicativo deve permitir suporte offline para funcionalidades básicas, como visualização de contas armazenadas. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-6-desempenho-e-funcionalidades-offline">Épico 6 - Desempenho e Funcionalidades Offline</a>  |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 39 - Suporte Offline </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us39-suporte-offline">US39 - Suporte Offline </a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/especSup/#disponibilidade">Especificação Suplementar - Disponibilidade</a>  |

Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>
</center>

<center>
<figcaption>Tabela 40 - RNF08 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ40</a> |  	O aplicativo deve ter tempos de resposta inferiores a 2 segundos para a maioria das funcionalidades. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-6-desempenho-e-funcionalidades-offline">Épico 6 - Desempenho e Funcionalidades Offline</a>  |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 40 - Tempo de Resposta Inferior a 2 Segundos </a> |
| História de Usuário | <a href="hhttps://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us40-tempos-de-resposta-inferiores-a-2-segundos-para-funcionalidades">US40 - Tempos de resposta inferiores a 2 segundos para funcionalidades </a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/especSup/#desempenho">Especificação Suplementar - Desempenho</a>  |

Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>
</center>

<br>

<center>
<figcaption>Tabela 41 - RNF09 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ34</a> |O aplicativo deve garantir segurança com os dados dos usuários|
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-7-seguranca-e-privacidade">Épico 7 - Segurança e Privacidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 8 - Segurança de Dados</a> |
| NFR | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/nfr/#nfr-framework-nfr03-confiabilidade">NFR Framework - NFR03: Confiabilidade</a>  |
| Especificação Suplementar |  <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/especSup/#confiabiliade">Especificação Suplementar - Confiabilidade</a> |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO16</a> |
| Implementado | Sim <br> <img src="https://github.com/user-attachments/assets/2addfda2-c49f-4905-ac62-d008a261e0e3" style="height:200px;"> |
| Versionamento| Requisito não foi modificado|

 Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<figcaption>Tabela 42 - RNF10 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/" target = "_blank">RQ35</a> | O aplicativo deve estar em conformidade com os padrões de acessibilidade da última versão da WCAG |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade"target = "_blank">Épico 5: Interface e Usabilidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features"target = "_blank">Feature 19 - Conformidade com Padrões de Acessibilidade</a> |
| NFR | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/nfr/#nfr-framework-nfr05-manutenibilidade"target="_blank">NFR Framework - NFR05: Manutenibilidade</a>  |
| Especificação Suplementar | -- |
| Elo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/pos_rastreabilidade/backwardfrom/#elos_1">ELO27</a> |
| Implementado | Não |
| Versionamento| Requisito não foi modificado|

 Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

## Referências Bibliográficas

><p> POHL, Klaus. RUPP, Chris. Requirements Engineering Fundamentals. Disponível em: <a href= https://aprender3.unb.br/pluginfile.php/2972562/mod_resource/content/2/Rastreabilidade.pdf> https://aprender3.unb.br/pluginfile.php/2972562/mod_resource/content/2/Rastreabilidade.pdf </a>. Acesso em 14 de Jan. de 2024.</p>

><p> Requisitos - Aula 26 - Profa.Milene e Prof.Mauricio. Disponível em: <a href= https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf> https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf </a>. Acesso em 14 de Jan. de 2024.</p>

<br>

## Histórico de Versão

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 14/01/2025 | Criação do artefato  | [Natan Almeida](https://github.com/natanalmeida03) <br> [João Victor Marques](https://github.com/jmarquees) | [Leandro de Almeida](https://github.com/leomitx10) |
|  1.1   | 15/01/2025 | Adição de requisitos  | [Natan Almeida](https://github.com/natanalmeida03) | [Leandro de Almeida](https://github.com/leomitx10) |
|  1.2   | 16/01/2025 | Adição de requisitos  | [Joao Victor Marques](https://github.com/jmarquees) | [Leandro de Almeida](https://github.com/leomitx10) |
|  1.3   | 16/01/2025 | Adição de requisitos não funcionais  | [Joao Victor Marques](https://github.com/jmarquees) | [Leandro de Almeida](https://github.com/leomitx10) |
|  1.4   | 16/01/2025 | Adição de requisitos funcionais e não funcionais  | [Letícia Resende ](https://github.com/LeticiaResende23) | [Natan Almeida](https://github.com/natanalmeida03) |
|  1.5   | 17/01/2025 | Adição de requisitos funcionais 16 a 22 e do requisito não funcional 10 | [Leandro de Almeida ](https://github.com/leomitx10) | [Natan Almeida](https://github.com/natanalmeida03) |
|  1.6   | 22/01/2025 | Correção pós-apresentação | [Natan Almeida](https://github.com/natanalmeida03) | [Leandro de Almeida ](https://github.com/leomitx10) | 
|  1.7   | 23/01/2025 | Correção pós-apresentação | [Letícia Resende ](https://github.com/LeticiaResende23) | [Leandro de Almeida ](https://github.com/leomitx10) | 
|  1.8   | 24/01/2025 | Correção pós-apresentação |[Leandro de Almeida ](https://github.com/leomitx10) | [Letícia Resende ](https://github.com/LeticiaResende23) |  
|  1.9   | 05/02/2025 | Correção pós-apresentação | [Letícia Resende ](https://github.com/LeticiaResende23) | [Leandro de Almeida ](https://github.com/leomitx10) | 