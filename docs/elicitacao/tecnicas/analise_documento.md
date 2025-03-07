# Análise de Documento

## Introdução

<p align="justify">&emsp;&emsp;Este documento tem como objetivo identificar e documentar os requisitos de software para o aplicativo CAESB Autoatendimento, utilizando a técnica de análise de documentos. O CAESB Autoatendimento é um aplicativo gratuito desenvolvido para facilitar o acesso e a gestão de serviços de saneamento. Ele permite ao usuário realizar funcionalidades como revisão de conta, alteração de titularidade e vencimento, além de auto leitura do hidrômetro, promovendo maior controle e transparência no consumo de água. O aplicativo está disponível para os sistemas operacionais Android e iOS.</p>

## Metodologia

<p align="justify">&emsp;&emsp;A técnica empregada neste documento é a análise de documentos, que se destaca por sua utilidade na identificação de requisitos de software implícitos em materiais já existentes. Esses requisitos podem ser extraídos por meio de uma avaliação detalhada do conteúdo. A análise de documentos complementa outras abordagens de elicitação de requisitos, como entrevistas e observação de usuários. Além disso, ela pode ser combinada com técnicas como prototipagem e modelagem de processos, contribuindo para uma compreensão mais completa dos requisitos do software.</p>

## Requisitos

Os requisitos levantados durante a análise de documentos, identificados com 'ADD' + número do requisito, e com a seguinte legenda de categoria:

- RF: Requisitos Funcionais - Descrevem o comportamento ou a funcionalidade que o software deve ter para atender às necessidades do usuário.

- RNF: Requisitos Não-Funcionais - Descrevem os atributos que o software deve ter, como desempenho, segurança e usabilidade, mas não descrevem o comportamento do software em si.

<center>
<figcaption>Tabela 01 - Requisitos </figcaption>

| Rastreabilidade   | Descrição                                                          | Categoria |
| :-: | :-------------------------------------------------------------------: | :-------: 
| ADD01| O usuário deve poder enviar documentos diretamente pelo aplicativo. | RF |
| ADD02| O aplicativo deve oferecer notificações para lembrar vencimento de contas e ações pendentes.    | RF |
| ADD03| O aplicativo deve incluir suporte a chat ou atendimento virtual para resolver dúvidas dos usuários.   | RF |
| ADD04| O aplicativo deve oferecer suporte a múltiplos idiomas para atender usuários diversificados.| RNF |
| ADD05| O aplicativo deve ser eficiente em dispositivos com recursos limitados.| RNF |
| ADD06| O aplicativo deve minimizar riscos de vulnerabilidades e proteger contra ataques conhecidos.| RNF |
| ADD07| O aplicativo deve evitar riscos relacionados à violação de privacidade e coleta invasiva de dados dos usuários.| RNF |
| ADD08| O aplicativo deve passar por testes de desempenho para assegurar eficiência em dispositivos diversos.| RNF |
| ADD09| O aplicativo deve ser testado para evitar vulnerabilidades e proteger os dados dos usuários.| RNF |
| ADD10| O aplicativo deve incluir um tutorial inicial para ajudar novos usuários a se familiarizarem.| RNF |
| ADD11| O usuário deve poder personalizar notificações de acordo com suas preferências.| RNF |
| ADD12| O aplicativo deve permitir que o usuário realize pagamentos de contas diretamente pelo aplicativo.| RF |
| ADD13| O aplicativo deve estar em conformidade com padrões de acessibilidade, como WCAG.| RNF |
| ADD14| O aplicativo deve permitir suporte offline para funcionalidades básicas, como visualização de contas armazenadas.| RNF |

Autor(a): <a href="https://github.com/LeticiaResende233" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<figcaption>Tabela 01 - Requisitos Implementados </figcaption>


| Rastreabilidade  | Descrição                                                            | Categoria |  Implementado
| :-: | :-------------------------------------------------------------------: | :-------: |  :-----------:
| ADD15| Permitir a revisão de contas diretamente pelo aplicativo. | RF | Sim | 
| ADD16| Possibilitar a alteração de titularidade e vencimento de contas.      | RF | Sim |
| ADD17| O aplicativo deve permitir que o usuário realize a auto leitura do hidrômetro. | RF | Sim |
| ADD18| O aplicativo deve permitir que o usuário relate vazamentos de água.    | RF | Sim |
| ADD19| O aplicativo deve permitir que o usuário solicite desobstrução de esgoto e acompanhe os atendimentos.  | RF  | Sim |
| ADD20| O aplicativo deve permitir o acesso ao histórico detalhado de consumo e faturas anteriores.   | RF | Sim |
| ADD21| O aplicativo deve ser compatível com sistemas operacionais Android e iOS.| RNF | Sim |
| ADD22| O aplicativo deve garantir uma interface do usuário acessível e fácil de navegar.| RNF | Sim |
| ADD23| O aplicativo deve permitir a realização de testes para validar a funcionalidade de revisão de contas e alterações.| RNF | Sim |
| ADD24| O aplicativo deve ser testado para garantir uma navegação intuitiva e acessível a todos os usuários.| RNF | Sim |
| ADD25| O aplicativo deve garantir que os dados dos usuários sejam tratados com respeito à privacidade.| RNF | Sim |
| ADD26| O aplicativo deve permitir que o usuário emita segundas vias de contas e comprovantes.| RF | Sim |
| ADD27| O aplicativo deve implementar autenticação multifator para aumentar a segurança do acesso.| RNF | Sim |
| ADD28| O usuário deve poder localizar postos de atendimento da CAESB no mapa.| RF | Sim |
| ADD29| O aplicativo deve exibir informações em tempo real sobre interrupções no fornecimento de água.| RF | Sim |
| ADD30| O aplicativo deve oferecer estatísticas de consumo mensal para ajudar o usuário a monitorar o uso de água.| RF | Sim |

Autor(a): <a href="https://github.com/LeticiaResende233" target = "_blank">Letícia Resende</a>
</center>
<br>

## Referências Bibliográficas

> <p>1. VAZQUEZ, Carlos Eduardo; SIQUEIRA, Guilherme. Engenharia de requisitos. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972448/mod_resource/content/4/Elicitacao%20de%20Req%202.pdf>. Acesso em: 23 nov. 2024.</p>
> <p>2.WIEGERS, Karl; BEATTY, Joy. Software requirements. 3. ed. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972451/mod_resource/content/1/Elicitacao%20de%20Req.pdf>. Acesso em: 23 nov. 2024.

<br>

## Histórico de Versão

<center>

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :-----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 21/11/2024 | Criação do artefato |[Letícia Resende](https://github.com/LeticiaResende23) | [Leandro de Almeida](https://github.com/leomitx10)  |
|  1.1   | 26/11/2024 | Adicionando tabela de implementados |[Letícia Resende](https://github.com/LeticiaResende23) | [Leandro de Almeida](https://github.com/leomitx10)  |
|  1.2   | 08/02/2025 | Correção do histórico de versão | [Leandro de Almeida](https://github.com/leomitx10)  | [Letícia Resende](https://github.com/LeticiaResende23) | 

</center>




