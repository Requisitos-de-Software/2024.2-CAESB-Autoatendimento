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

## Requisitos

<center>
<figcaption>Tabela 01 - Requisitos </figcaption>

|  ID  |        DESCRIÇÃO          | RASTREABILIDADE | CATEGORIA | IMPLEMENTADO |
| :--: | :-----------------------: | :-------------: | :-------: | :----------: |
| **RQ01**  | O sistema deve ter uma barra de busca.| B01 | RF | NÃO |
| **RQ02**  | O sistema deve ter as funções mais utilizadas/mais buscadas em uma barra | B02, ENT08 | RF | NÃO |
| **RQ03**  | O sistema deve permitir acessar/pagar contas passadas | B03, INT12 | RF | NÃO |
| **RQ04**  | O sistema deve permitir emitir/vizualizar segunda via de conta | B04, ENT03, INT11, OBS03, OBS02 | RF | NÃO |
| **RQ05** | O sistema deve permitir consultar consumo | B05, ENT04, INT03 | RF | NÃO |
| **RQ06** | O sistema deve permitir bloqueio, reativação ou solicitação de reparo | B06 | RF | NÃO |
| **RQ07** | O sistema deve exibir pequenas descrições ao lado dos serviços para mostrar seu estado atual | B07 | RF | NÃO |
| **RQ08** | O sistema deve oferecer várias formas de pagamento | B08, B09, INT24, ADD12, INT02 | RF | NÃO |
| **RQ09** | O sistema deve permitir a configuração de um pagamento mensal recorrente | B10, INT13 | RF | NÃO |
| **RQ10** | O sistema deve possibilitar o adiantamento de processos via aplicativo | B11 | RF | NAO |
| **RQ11** | O usuário deve poder enviar documentos diretamente pelo aplicativo. | ADD01 | RF | NAO |
| **RQ12** | O aplicativo deve oferecer notificações para lembrar vencimento de contas e ações pendentes. | ADD02, INT05, INT27 | RF | NAO |
| **RQ13** | O aplicativo deve incluir suporte a chat ou atendimento virtual para resolver dúvidas dos usuários. | ADD03, INT29 | RF | NAO |
| **RQ14** | A funcionalidade "Informar vazamento na rua" deve mostrar apenas o mapa das regiões em que a Caesb atua. | ENT01 | RF | NAO |
| **RQ15** | O usuário deve poder informar e vizualizar informações sobre a falta de água. | ENT05, INT06, OBS06, INT14 | RF | NAO |
| **RQ16** | O sistema deve permitir ao usuário corrigir erros retornando à tela anterior e atualizando os dados. | ENT06 | RF | NAO |
| **RQ17** | A funcionalidade "Atendimentos" deve permitir filtros por ano, mês, status (finalizado ou em andamento). | ENT07, OBS09, OBS10 | RF | NAO |
| **RQ18** | A funcionalidade "Simulação de tarifa" deve ser nativa do aplicativo e não redirecionar ao site da Caesb. | ENT09 | RF | NAO |
| **RQ19** | O aplicativo deve permitir ao usuário informar vazamentos na rua ou no hidrômetro | INT01, OBS07, OBS08 | RF | NAO |
| **RQ20** | O usuário deve poder atualizar seus dados cadastrais pelo app. | INT04, INT20 | RF | NAO |
| **RQ21** | O aplicativo deve permitir agendar atendimento presencial na unidade mais próxima. | INT15 | RF | NAO |
| **RQ22** | O aplicativo deve exibir dicas de consumo consciente e economia de água. | INT16 | RF | NAO |
| **RQ23** | O usuário deve poder registrar e acompanhar ordens de serviço. | INT17 | RF | NAO |
| **RQ24** | O aplicativo deve disponibilizar alertas sobre manutenção programada. | INT18 | RF | NAO |
| **RQ25** | O usuário deve poder solicitar alteração na titularidade da conta. | INT19, OBS14 | RF | NAO |
| **RQ26** | O aplicativo deve permitir que o usuário escolha o imóvel desejado.| OBS01 | RF | NAO |
| **RQ27** | O aplicativo deve reconhecer automaticamente os imóveis associados ao cliente da Caesb. | OBS04 | RF | NAO |
| **RQ28** | O aplicativo deve considerar o número de pessoas no imóvel para calcular a média do consumo. | OBS05 | RF | NAO |
| **RQ29** | O aplicativo deve permitir que o usuário altere o vencimento da conta. | OBS13 | RF | NAO |
| **RQ30** | O aplicativo deve permitir que o usuário busque um atendimento pelo protocolo. | OBS11 | RF |NAO |
| **RQ31** | O aplicativo deve incluir um tutorial inicial para ajudar novos usuários a se familiarizarem.| ADD10 | RNF | NAO |
| **RQ32** | O aplicativo deve oferecer suporte a múltiplos idiomas para atender usuários diversificados. | ADD04, INT25 | RNF | NAO |
| **RQ33** | O aplicativo deve ser compatível com as versões mais recentes do Android e iOS. | INT07, OBS16 | RNF | NAO |
| **RQ34** | O aplicativo deve garantir segurança com os dados dos usuários. | ADD06, ADD07 | RNF | NAO |
| **RQ35** | O aplicativo deve estar em conformidade com os padrões de acessibilidade da última versão da WCAG. | ADD13, INT26, OBS18 | RNF | NAO |
| **RQ36** | O aplicativo deve ter uma interface intuitiva, organizada e fácil de usar. | INT08, ENT02, B15, B13, ENT10 | RNF | NAO |
| **RQ37** | O sistema deve minimizar o número de cliques necessários para interações. | B14, OBS19 | RNF | NAO |
| **RQ38** | O aplicativo deve se adaptar a diferentes tamanhos de tela. | OBS17, INT10 | RNF | NAO |
| **RQ39** | O aplicativo deve permitir suporte offline para funcionalidades básicas, como visualização de contas armazenadas. | ADD14 | RNF | NAO |
| **RQ40** | O aplicativo deve ter tempos de resposta inferiores a 2 segundos para a maioria das funcionalidades. | INT22 | RNF | NAO |

Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

## Histórico de Versão

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :-----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 12/12/2024 | Criação do artefato |[Natan Almeida](https://github.com/natanalmeida03) | [Leandro de Almeida](https://github.com/leomitx10)  |