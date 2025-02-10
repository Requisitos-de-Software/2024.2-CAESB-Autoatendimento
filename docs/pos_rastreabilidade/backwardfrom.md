# Backward-From

## Introdução

<p align="justify">&emsp;&emsp;A Matriz Backward From é uma ferramenta usada na engenharia de requisitos para identificar a origem dos requisitos de um sistema. Ela contribui para assegurar que cada exigência possua uma justificação explícita e possa ser vinculada diretamente às necessidades, metas ou partes interessadas que a motivaram. Isso é crucial para prevenir falhas ou equívocos durante a elaboração do sistema.</p>

## Metodologia

<p align="justify">
    &emsp;&emsp;Baseando-se no meta-modelo de Toranzo, disponível no Aprender3, nos slides 19 e 23 da aula 26, os requisitos foram classificados pelo grupo em níveis e elos.
</p>

### Níveis

- <b>Ambiental</b>: informações oriundas do ambiente e do contexto ao qual a organização está inserida.
- <b>Organizacional</b>: informações relacionadas à organização.
- <b>Gerencial</b>: informações que auxiliam na gerencia do projeto.
- <b>Desenvolvimento</b>: informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento.

### Elos

- <b>Satisfação</b>: classe origem tem dependência de satisfação com a classe destino.
- <b>Recurso</b>: classe origem tem dependência de recurso com a classe destino.
- <b>Responsabilidade</b>: registra a participação, responsabilidade e ação de pessoas sobre artefatos.
- <b>Representação</b>: captura a representação ou modelagem dos requisitos em outras linguagens.
- <b>Alocado</b>: classe origem está relacionada à classe destino, que representa um subsistema.
- <b>Agregação</b>: indica “composição” de elementos

## Técnica de Elicitação

</p>&emsp;&emsp;A tabela abaixo contém as abreviações das técnicas de elicitação referenciadas.</p>  

<br>

<center>

Tabela 01: Abreviações das técnicas de elicitação

|  **Sigla** | **Técnica de Elicitação**      |
|------------|--------------------------------|
|     ADD    | Análide de Documentos          |
| OBS        | Observação                     |
| B          | Brainstorm                     |
| INT        | Introspecção                   |
| ENT        | Entrevista                     |

<center>
 Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a> e <a href="https://github.com/Ninja-Haiyai" target = "_blank">Matheus Barros</a></h6>
</center>

</center>

<br>

## Requisitos Funcionais



<center>Tabela 02: Requisitos Funcionais</center>

|  ID  |        DESCRIÇÃO          | RASTREABILIDADE | CATEGORIA | IMPLEMENTADO |
| :--: | :-----------------------: | :-------------: | :-------: | :----------: |
| **RQ01**  | O sistema deve ter uma barra de busca.| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B01</a> | RF | Não |
| **RQ02**  | O sistema deve ter as funções mais utilizadas/mais buscadas em uma barra | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B02</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT08</a> | RF | Não |
| **RQ03**  | O sistema deve permitir acessar/pagar contas passadas | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B03</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT12</a> | RF | Não |
| **RQ04**  | O sistema deve permitir emitir/vizualizar segunda via de conta | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B04</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT03</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT11</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS03</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS02</a> | RF | Sim |
| **RQ05** | O sistema deve permitir consultar consumo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B05</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT04</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT03</a> | RF | Sim |
| **RQ06** | O sistema deve permitir bloqueio, reativação ou solicitação de reparo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B06</a> | RF | Sim |
| **RQ07** | O sistema deve exibir pequenas descrições ao lado dos serviços para mostrar seu estado atual | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B07</a> | RF | Não |
| **RQ08** | O sistema deve oferecer várias formas de pagamento | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B08</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B09</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT24</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD12</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT02</a> | RF | Não |
| **RQ09** | O sistema deve permitir a configuração de um pagamento mensal recorrente | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B10</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT13</a> | RF | Não |
| **RQ10** | O sistema deve possibilitar o adiantamento de processos via aplicativo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B11</a> | RF | Não |
| **RQ11** | O usuário deve poder enviar documentos diretamente pelo aplicativo. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD01</a> | RF | Não |
| **RQ12** | O aplicativo deve oferecer notificações para lembrar vencimento de contas e ações pendentes. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD02</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT05</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT27</a> | RF | Não |
| **RQ13** | O aplicativo deve incluir suporte a chat ou atendimento virtual para resolver dúvidas dos usuários. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD03</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT29</a> | RF | Não |
| **RQ14** | A funcionalidade "Informar vazamento na rua" deve mostrar apenas o mapa das regiões em que a Caesb atua. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT01</a> | RF | Sim |
| **RQ15** | O usuário deve poder informar e vizualizar informações sobre a falta de água. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT05</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT06</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS06</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT14</a> | RF | Sim |
| **RQ16** | O sistema deve permitir ao usuário corrigir erros retornando à tela anterior e atualizando os dados. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT06</a> | RF | Sim |
| **RQ17** | A funcionalidade "Atendimentos" deve permitir filtros por ano, mês, status (finalizado ou em andamento). | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT07</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS09</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS10</a> | RF | Não | 
| **RQ18** | A funcionalidade "Simulação de tarifa" deve ser nativa do aplicativo e não redirecionar ao site da Caesb. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT09</a> | RF | Sim |
| **RQ19** | O aplicativo deve permitir ao usuário informar vazamentos na rua ou no hidrômetro | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT01</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS07</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS08</a> | RF | Sim |
| **RQ20** | O usuário deve poder atualizar seus dados cadastrais pelo app. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT04</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT20</a> | RF | Sim |
| **RQ21** | O aplicativo deve permitir agendar atendimento presencial na unidade mais próxima. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT15</a> | RF | Não |
| **RQ22** | O aplicativo deve exibir dicas de consumo consciente e economia de água. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT16</a> | RF | Não |
| **RQ23** | O usuário deve poder registrar e acompanhar ordens de serviço. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT17</a> | RF | Não |
| **RQ24** | O aplicativo deve disponibilizar alertas sobre manutenção programada. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT18</a> | RF | Não |
| **RQ25** | O usuário deve poder solicitar alteração na titularidade da conta. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT19</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS14</a> | RF | Sim |
| **RQ26** | O aplicativo deve permitir que o usuário escolha o imóvel desejado.| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS01</a> | RF | Sim |
| **RQ27** | O aplicativo deve reconhecer automaticamente os imóveis associados ao cliente da Caesb. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS04</a> | RF | Sim |
| **RQ28** | O aplicativo deve considerar o número de pessoas no imóvel para calcular a média do consumo. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS05</a> | RF | Não |
| **RQ29** | O aplicativo deve permitir que o usuário altere o vencimento da conta. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS13</a> | RF | Não |
| **RQ30** | O aplicativo deve permitir que o usuário busque um atendimento pelo protocolo. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS11</a> | RF |Não |

<center>
 Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida e Matheus Barros<a href="https://github.com/Ninja-Haiyai" target = "_blank"></a></h6>
</center>

<br>

## Requisitos Não Funcionais



<center>Tabela 03: Requisitos Não Funcionais</center>

|  ID  |        DESCRIÇÃO          | RASTREABILIDADE | CATEGORIA | IMPLEMENTADO |
| :--: | :-----------------------: | :-------------: | :-------: | :----------: |
| **RQ31** | O aplicativo deve incluir um tutorial inicial para ajudar novos usuários a se familiarizarem.| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD10</a> | RNF | Não |
| **RQ32** | O aplicativo deve oferecer suporte a múltiplos idiomas para atender usuários diversificados. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD04</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT25</a> | RNF | Não |
| **RQ33** | O aplicativo deve ser compatível com as versões mais recentes do Android e iOS. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT07</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS16</a> | RNF | Sim |
| **RQ34** | O aplicativo deve garantir segurança com os dados dos usuários. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD06</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD07</a> | RNF | Sim |
| **RQ35** | O aplicativo deve estar em conformidade com os padrões de acessibilidade da última versão da WCAG. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD13</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT26</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS18</a> | RNF | Não |
| **RQ36** | O aplicativo deve ter uma interface intuitiva, organizada e fácil de usar. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT08</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT02</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B15</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B13</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT10</a> | RNF | Sim |
| **RQ37** | O sistema deve minimizar o número de cliques necessários para interações. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B14</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS19</a> | RNF | Sim |
| **RQ38** | O aplicativo deve se adaptar a diferentes tamanhos de tela. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS17</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT10</a> | RNF | Não |
| **RQ39** | O aplicativo deve permitir suporte offline para funcionalidades básicas, como visualização de contas armazenadas. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD14</a> | RNF | Não |
| **RQ40** | O aplicativo deve ter tempos de resposta inferiores a 2 segundos para a maioria das funcionalidades. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT22</a> | RNF | Não |

<center>
 Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida e Matheus Barros<a href="https://github.com/Ninja-Haiyai" target = "_blank"></a></h6>
</center>

<br>

## Elos

<p align="justify">&emsp;&emsp;Nessa parte iremos abordar as conexões entre os requisitos que foram mostrados anteriormente nas tabelas 1 e 2, para tal iremos utilizar a metodologia anteriormente apresentada para que possamos classificar os requisitos em qual tipo de elo eles são:</p>



<center>Tabela 04: Requisitos Não Funcionais</center>


| ID    | Requisitos | Tipo de elo  | Descrição do elo                                                                                  | Implementado  | Versionamento |
|-------|------------|--------------|--------------------------------------------------------------------------------------------------| ---|----------|
| ELO1  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ03</a> | Satisfação   | O requisito RQ03 diz que o aplicativo deveria possuir a capacidade de pagar e visualizar contas anteriores. | Não | O requisito não foi modificado
| ELO2  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ05</a> | Satisfação   | O requisito RQ05 diz que o sistema deve permitir consultar consumo.                              |  Sim  | O requisito não foi modificado
| ELO3  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ06</a> | Recurso      | O requisito RQ06 diz que o sistema deve permitir bloqueio, reativação ou solicitação de reparo nos serviços da Caesb. | Sim | O requisito não foi modificado
| ELO4  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ16</a> | Representação| O requisito RQ16 diz que o sistema deve permitir ao usuário corrigir erros retornando à tela anterior e atualizando os dados. | Sim | O requisito não foi modificado
| ELO5  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ18</a> | Alocado      | O requisito RQ18 diz que a funcionalidade "Simulação de tarifa" deve ser nativa do aplicativo e não redirecionar ao site da Caesb. | Não | O requisito não foi modificado
| ELO6  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ22</a> | Agregação    | O requisito RQ22 diz que o aplicativo deve exibir dicas de consumo consciente e economia de água. |  Não | O requisito não foi modificado
| ELO7  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ24</a> | Responsabilidade | O requisito RQ24 diz que o aplicativo deve disponibilizar alertas sobre manutenção programada.   | Não  | O requisito não foi modificado
| ELO8  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ25</a> | Satisfação   | O requisito RQ25 diz que o usuário deve poder solicitar alteração na titularidade da conta.       |  Sim  | O requisito não foi modificado
| ELO9  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ02</a> | Satisfação   | O requisito RQ02 estabelece que o sistema deve ter as funções mais utilizadas/mais buscadas em uma barra. |  Não  | Requisito não foi modificado |
| ELO10  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ04</a>  | Satisfação   | O requisito RQ04 define que o sistema deve permitir emitir/visualizar segunda via de conta.      |  Sim  | Requisito não foi modificado |
| ELO11  |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ08</a> | Recurso   | O requisito RQ08 especifica que o sistema deve oferecer várias formas de pagamento.      |  Não | Requisito não foi modificado |
| ELO12  |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ11</a> | Representação   | O requisito RQ11 determina que o usuário deve poder enviar documentos diretamente pelo aplicativo. | Não | Requisito não foi modificado |
| ELO13  |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ13</a>       |  Alocado    | O requisito RQ13 propõe que o aplicativo deve incluir suporte a chat ou atendimento virtual para dúvidas. | Não | Requisito não foi modificado |
| ELO14  |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ14</a>|  Agregação  | O requisito RQ14 estipula que a funcionalidade "Informar vazamento na rua" deve mostrar apenas o mapa das regiões em que a Caesb atua.| Sim  | Requisito não foi modificado |
| ELO15  |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ15</a>      |  Responsabilidade  | O requisito RQ15 afirma que o usuário deve poder informar e visualizar informações sobre a falta de água.| Sim | Requisito não foi modificado |
| ELO16  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ34</a>      |  Satisfação  | O requisito RQ34 assegura que o aplicativo deve garantir segurança com os dados dos usuários.   | Sim  | Requisito não foi modificado |
| ELO17  |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ09</a>  | Funcionalidade   | O requisito RQ09 estabelece que o sistema deve permitir a configuração de um pagamento mensal recorrente |  |
| ELO18  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ12</a>  | Satisfação   | O requisito RQ12 define que o sistema deve oferecer notificações para lembrar vencimento de contas e ações pendentes.      |   |
| ELO19  |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ19</a> | Satisfação   | O requisito RQ19 especifica que o sistema deve permitir ao usuário informar vazamentos na rua ou no hidrômetro  |   |
| ELO20  |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ20</a> | Satisfação   | O requisito RQ20 determina que o  usuário deve poder atualizar seus dados cadastrais pelo app. |   |
| ELO21  |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ21</a>       |  Satisfação    | O requisito RQ21 determina que o sistema deve permitir agendar atendimento presencial na unidade mais próxima.|  |
| ELO22  |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ31</a>|  Representação  | O requisito RQ31 define que o sistema deve incluir um tutorial inicial para ajudar novos usuários a se familiarizarem.|  |
| ELO23  |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ32</a>      |  Qualidade  | O requisito RQ32 afirma que o aplicativo deve oferecer suporte a múltiplos idiomas para atender usuários diversificados.|    |
| ELO24  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos">RQ38</a>      |  Representação  | O requisito RQ38 assegura que o aplicativo deve se adaptar a diferentes tamanhos de tela.   |   |
| ELO25  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target = "blank">RQ01</a> | Representação | O requisito RQ01 define que o sistema deve ter uma barra de busca.   | Não  |Requisito não foi modificado
| ELO26  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ23</a> | Responsabilidade | O requisito RQ23 determina que usuário deve poder registrar e acompanhar ordens de serviço. | Não | Requisito não foi modificado
| ELO27  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ35</a> | Satisfação | O requisito RQ35 define que o sistema deve estar em conformidade com os padrões de acessibilidade da última versão da WCAG.   | Não  | Requisito não foi modificado
| ELO28  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ30</a> | Representação | O requisito RQ30 estabelece que o sistema deve permitir que o usuário busque um atendimento pelo protocolo.   |  Não  | Requisito não foi modificado
| ELO29  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ29</a> | Recurso | O requisito RQ29 define que o sistema deve permitir que o usuário altere o vencimento da conta. |  Não | Requisito não foi modificado
| ELO30  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ07</a> | Agregação | O requisito RQ07 estabelece que o sistema deve exibir pequenas descrições ao lado dos serviços para mostrar seu estado atual.  | Não  | Requisito não foi modificado
| ELO31  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ10</a> | Recurso | O requisito RQ30 determina que o sistema deve possibilitar o adiantamento de processos via aplicativo.  | Não  | Requisito não foi modificado
| ELO32  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ17</a> | Alocado | O requisito RQ17 determina que a funcionalidade "Atendimentos" deve permitir filtros por ano, mês, status (finalizado ou em andamento).  | Não | Requisito não foi modificado
| ELO33  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ26</a> | Recurso | O requisito RQ26 define que o aplicativo deve permitir que o usuário escolha o imóvel desejado.  |  |
| ELO34  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ27</a> | Recurso | O requisito RQ27 define que o aplicativo deve reconhecer automaticamente os imóveis associados ao cliente da Caesb.  |  |
| ELO35  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ28</a> | Recurso | O requisito RQ28 define que o aplicativo deve considerar o número de pessoas no imóvel para calcular a média do consumo.  |  |
| ELO36  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ33</a> | Satisfação | O requisito RQ33 determina que o aplicativo deve ser compatível com as versões mais recentes do Android e iOS.  |    |
| ELO37  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ36</a> | Representação | O requisito RQ36 determina que o aplicativo deve ter uma interface intuitiva, organizada e fácil de usar.  |   |
| ELO38  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ37</a> | Satisfação | O requisito RQ37 determina que o sistema deve minimizar o número de cliques necessários para interações. | |
| ELO39  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ39</a> | Recurso | O requisito RQ39 determina que o aplicativo deve permitir suporte offline para funcionalidades básicas, como visualização de contas armazenadas.  |  |
| ELO40  | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos"target = "blank">RQ40</a> | Agregação | O requisito RQ40 determina que o aplicativo deve ter tempos de resposta inferiores a 2 segundos para a maioria das funcionalidades.  |  |


<center>
Autor: <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a>, <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>, <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>, <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a> e <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a>

</center>

<br>

## Referências Bibliográficas

><p id="1">[1] SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: <a href="https://www-di.inf.puc-rio.br/~julio/rastre.pdf">https://www-di.inf.puc-rio.br/~julio/rastre.pdf</a>. Acesso em: 14 de Janeiro de 2025.</p>
><p id="2">[2] TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: <a href="http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf">http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf</a>. Acesso em: 14 de Janeiro de 2025.</p>

<br>

## Histórico de versão

<center>

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| ------ | ---------- | -------------------- | --------------------- | ------------------- |
|  1.0   | 14/01/2025 | Escrita da introdução e metodologia |[Matheus Barros ](https://github.com/Ninja-Haiyai)   | [Leandro de Almeida](https://github.com/leomitx10)|
|  1.1   | 14/01/2025 | Adição dos Elos 1 - 8 |[Matheus Barros ](https://github.com/Ninja-Haiyai)   | [Leandro de Almeida](https://github.com/leomitx10)|
|  1.2   | 16/01/2025 | Adição dos Elos 9 - 16 |[Letícia Resende ](https://github.com/LeticiaResende23)  | [Matheus Barros ](https://github.com/Ninja-Haiyai)|
|  1.3   | 16/01/2025 | Adição dos Elos 25 - 32 |[Leandro de Almeida ](https://github.com/leomitx10)  | [Matheus Barros ](https://github.com/Ninja-Haiyai)|
|  1.4   | 17/01/2025 | Adição da rastreabilidade dos Elos 1 - 8 |[Matheus Barros ](https://github.com/Ninja-Haiyai)   | [Leandro de Almeida](https://github.com/leomitx10)|
|  1.5   | 19/01/2025 | Adição da rastreabilidade dos Elos 33 - 40 |[Joao Victor Marques ](https://github.com/jmarquees)   | [Leandro de Almeida](https://github.com/leomitx10)|
|  1.6   | 23/01/2025 | Correção pós - apresentação| [Letícia Resende ](https://github.com/LeticiaResende23) | [Leandro de Almeida](https://github.com/leomitx10)|
|  1.7   | 23/01/2025 | Correção pós - apresentação| [Leandro de Almeida](https://github.com/leomitx10) | [Letícia Resende ](https://github.com/LeticiaResende23) |
|  1.8   | 08/02/2025 | Remoção da tabela de modelagem | [Leandro de Almeida](https://github.com/leomitx10) | [Matheus Barros ](https://github.com/Ninja-Haiyai) |

</center>