# Requisitos Elicitados

## Introdução

<p align="justify">&emsp;&emsp; Esse artefato reúne todos os requisitos funcionais e não funcionais elicitados  usando a técnica de 
<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">análise de documentos</a>, 
<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/#requisitos">brainstorm</a>, 
<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/#requisitos">entrevista</a>, 
<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">introspecção</a> e 
<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/#requisitos">observação</a></p>

## Metodologia

<p align="justify">&emsp;&emsp; A tabela 1 apresenta os requisitos funcionais e não funcionais, sendo que cada linha contém um ID, descrição, a rastreabilidade para os requisitos  referentes, sua categoria e se ele foi implementado ou não.</p>  

Legenda:     

- RQx: Requisito nºx
- RF: Requisito Funcional
- RNF: Requisito não Funcional
- ADDx: Requisito nºx elicitado pela <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">análise de documentos</a>
- Bx: Requisito nºx elicitado pelo <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/#requisitos">brainstorm</a>
- ENTx: Requisito nºx elicitado pela <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/#requisitos">entrevista</a>
- ISx: Requisito nºx elicitado pela <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">introspecção</a>
- OBSx: Requisito nºx elicitado pela <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/#requisitos">observação</a>

<br>

## Requisitos

<center>
<figcaption>Tabela 01 - Requisitos </figcaption>

|  ID  |        DESCRIÇÃO          | RASTREABILIDADE | CATEGORIA | IMPLEMENTADO |
| :--: | :-----------------------: | :-------------: | :-------: | :----------: |
| **RQ01**  | O sistema deve ter uma barra de busca.| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B01</a> | RF | Não |
| **RQ02**  | O sistema deve ter as funções mais utilizadas/mais buscadas em uma barra | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B02</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT08</a> | RF | Não |
| **RQ03**  | O sistema deve permitir acessar/pagar contas passadas | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B03</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT12</a> | RF | Não |
| **RQ04**  | O sistema deve permitir emitir/vizualizar segunda via de conta | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B04</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT03</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT11</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS03</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS02</a> | RF | Sim |
| **RQ05** | O sistema deve permitir consultar consumo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B05</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT04</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT03</a> | RF | Sim |
| **RQ06** | O sistema deve permitir bloqueio, reativação ou solicitação de reparo | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B06</a> | RF | Sim |
| **RQ07** | O sistema deve exibir pequenas descrições ao lado dos serviços para mostrar seu estado atual | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B07</a> | RF | Sim |
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
| **RQ30** | O aplicativo deve permitir que o usuário busque um atendimento pelo protocolo. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS11</a> | RF |Sim |
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

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

## Histórico de Versão

<center>

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :-----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 12/12/2024 | Criação do artefato |[Natan Almeida](https://github.com/natanalmeida03) | [Leandro de Almeida](https://github.com/leomitx10)  |
|  1.1   | 14/12/2024 | Adição de rastreabilidade |[Natan Almeida](https://github.com/natanalmeida03) | [Leandro de Almeida](https://github.com/leomitx10)  |
|  1.2   | 08/02/2025 | Correção do histórico de versão | [Leandro de Almeida](https://github.com/leomitx10) | [Natan Almeida](https://github.com/natanalmeida03) | 

<center>