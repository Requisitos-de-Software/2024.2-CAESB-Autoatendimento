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
| CEN     | Cenários                  |
| LEX     | Léxico                    |
| ES      | Especificação Suplementar |
| US      | Caso de Uso               |

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
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<center>
<figcaption>Tabela 4 - RF02 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ12</a> | O aplicativo deve oferecer notificações para lembrar vencimento de contas e ações pendentes. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-2-interatividade-e-suporte-ao-cliente">Épico 2 - Interatividade e Suporte ao Cliente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 9 - Notificação de Vencimento</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us11-notificar-o-usuario-para-lembrar-vencimento-de-contas-e-acoes-pendentes">US11 - Notificar o usuário para lembrar vencimento de contas e ações pendentes.</a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<center>
<figcaption>Tabela 5 - RF04 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ19</a> | O aplicativo deve permitir ao usuário informar vazamentos na rua ou no hidrômetro |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-3-sustentabilidade-e-consumo-consciente">Épico 3 - Sustentabilidade e Consumo Consciente</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 1 - Segunda Via de Conta</a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us12-permitir-ao-usuario-informar-vazamentos-na-rua-ou-no-hidrometro">US12 - Permitir ao usuário informar vazamentos na rua ou no hidrômetro.</a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<center>
<figcaption>Tabela 6 - RF03 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ20</a> | O usuário deve poder atualizar seus dados cadastrais pelo app. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-1-gestao-de-contas-e-pagamentos">Épico 1 - Gestão de Contas e Pagamentos</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 12 - Atualizar Dados Cadastrais </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us10-atualizar-seus-dados-cadastrais-pelo-app">US10 - Atualizar seus dados cadastrais pelo app</a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<center>
<figcaption>Tabela 7 - RF05 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ21</a> | O aplicativo deve permitir agendar atendimento presencial na unidade mais próxima. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-4-servicos-de-atendimento">Épico 4: Serviços de Atendimento</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 13 - Agendar Atendimento Presencial </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us13-permitir-ao-usuario-agendar-atendimento-presencial-na-unidade-mais-proxima">US13 - Permitir ao usuário agendar atendimento presencial na unidade mais próxima</a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<center>
<figcaption>Tabela 8 - RF06 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ26</a> | O aplicativo deve permitir que o usuário escolha o imóvel desejado. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5 - Interface e Usabilidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 33 - Escolher imóvel desejado </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us33-permitir-pagamento-mensal-recorrente">US33 - Escolher imóvel desejado </a> |
| Léxico  | Léxico relacionado |
| Casos de uso | Caso de uso relacionado |
| Cenários | Cenário relacionado |
| NFR | -- |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>
</center>


## Rquisitos Não-Funcionais

<center>
<figcaption>Tabela 8 - RNF01 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ31</a> | O aplicativo deve incluir um tutorial inicial para ajudar novos usuários a se familiarizarem. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5: Interface e Usabilidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 14 - Tutorial Inicial </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us14-incluir-um-tutorial-inicial-para-ajudar-novos-usuarios-a-se-familiarizarem">US14 - Incluir um tutorial inicial para ajudar novos usuários a se familiarizarem</a> |
| Léxico  | Léxico relacionado |
| Casos de uso | -- |
| Cenários | Cenário relacionado |
| NFR | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/nfr/#nfr-framework-nfr01-usabilidade">NFR Framework - NFR01: Usabilidade</a> |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<center>
<figcaption>Tabela 9 - RNF02 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ32</a> | O aplicativo deve oferecer suporte a múltiplos idiomas para atender usuários diversificados. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5: Interface e Usabilidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 15 - Suporte a Múltiplos Idiomas </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us15-oferecer-suporte-a-multiplos-idiomas-para-atender-usuarios-diversificados">US15 - Oferecer suporte a múltiplos idiomas para atender usuários diversificados.</a> |
| Léxico  | Léxico relacionado |
| Casos de uso | -- |
| Cenários | Cenário relacionado |
| NFR | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/nfr/#nfr-framework-nfr01-usabilidade">NFR Framework - NFR01: Usabilidade</a> |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<center>
<figcaption>Tabela 10 - RNF03 </figcaption>

| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/">RQ38</a> | O aplicativo deve se adaptar a diferentes tamanhos de tela. |
| :-: | :-: |
| Épico | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#epico-5-interface-e-usabilidade">Épico 5: Interface e Usabilidade</a> |
| Feature | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/backlog/#features">Feature 16 - Responsividade </a> |
| História de Usuário | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/historia_usuario/#us16-adaptar-a-diferentes-tamanhos-de-tela">US16 - Adaptar a diferentes tamanhos de tela.</a> |
| Léxico  | Léxico relacionado |
| Casos de uso | -- |
| Cenários | Cenário relacionado |
| NFR | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem_agil/nfr/#nfr-framework-nfr01-usabilidade">NFR Framework - NFR01: Usabilidade</a> |
| Especificação Suplementar | -- |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>


## Referências

><p> POHL, Klaus. RUPP, Chris. Requirements Engineering Fundamentals. Disponível em: <a href= https://aprender3.unb.br/pluginfile.php/2972562/mod_resource/content/2/Rastreabilidade.pdf> https://aprender3.unb.br/pluginfile.php/2972562/mod_resource/content/2/Rastreabilidade.pdf </a>. Acesso em 14 de Jan. de 2024.</p>

><p> Requisitos - Aula 26 - Profa.Milene e Prof.Mauricio. Disponível em: <a href= https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf> https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf </a>. Acesso em 14 de Jan. de 2024.</p>


## Histórico de Versão

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  `1.0`   | 14/01/2024 | Criação do artefato  | [Natan Almeida](https://github.com/natanalmeida03) <br> [João Victor Marques](https://github.com/jmarquees) | [Leandro de Almeida](https://github.com/leomitx10) |
|  `1.1`   | 15/01/2024 | Adição de requisitos  | [Natan Almeida](https://github.com/natanalmeida03) | [Leandro de Almeida](https://github.com/leomitx10) |