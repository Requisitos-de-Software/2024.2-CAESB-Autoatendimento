# Histórias de Usuário

## Introdução

<p align="justify">&emsp;&emsp;Uma história de usuário é uma descrição breve e simples de uma funcionalidade do sistema, escrita do ponto de vista do usuário. Usada em métodos ágeis de desenvolvimento, ela foca no valor de negócio para o cliente e representa uma pequena parte da funcionalidade, sem ser uma especificação detalhada. Isso reduz a necessidade de uma documentação extensa.</p>

## Metodologia  

<p align="justify">&emsp;&emsp;Para a produção desse artefato, foi realizada uma entrevista com um usuário, que desempenha o papel de PO (Product Owner) do projeto.</p>

<p align="justify">&emsp;&emsp;Durante a entrevista, o PO descreveu as funcionalidades desejadas para o projeto. Enquanto isso, os desenvolvedores, atuando como entrevistadores, anotaram as informações e fizeram questionamentos para esclarecer pontos específicos.</p>

<p align="justify">&emsp;&emsp;Após a elicitação das histórias de usuário, foram definidos os critérios de aceitação para cada uma delas. Posteriormente, as histórias foram priorizadas pelo PO com base em quatro categorias: Must-Have, Should-Have, Could-Have e Won't-Have. Esse processo utilizou o método <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/priorizacao/moscow/" target="_blank">Moscow</a> de priorização de requisitos.</p>


<center>Tabela 1: Participantes entrevista 1

| Participante   | Função          | Local         | Data       |
|----------------|-----------------|---------------|------------|
| Leandro de Almeida | Desenvolvedor   |   Gama - DF   | 16/12/2024 |
| Leticia Resende | Desenvolvedor   |   Gama - DF   | 16/12/2024 |
| Carolina Barbosa | Product Owner   |   Gama - DF   | 16/12/2024 |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

<center>
    <p>Vídeo 01: Entrevista com o PO</p>
    <iframe width="760" height="515" src="https://www.youtube.com/embed/PsvCjqgs0CE?si=A2h6if1Q1rd4njr6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a> e <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a></h6>
</center>

## Histórias de Usuário

## US01 - Barra de busca

<center>Tabela 2: Barra de Busca

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US01              | O sistema deve ter uma barra de busca.   |
|     Descrição          | Eu, como usuário, desejo que o aplicativo tenha uma barra de busca para facilitar a localização de eventos específicos pelo nome ou palavra-chave. |
| Critérios de Aceitação | - Na página principal do aplicativo, deve haver uma barra de busca visível no topo ou em local destacado.<br>- Ao digitar na barra de busca, os eventos listados devem ser filtrados em tempo real para corresponder aos termos inseridos.<br> - A busca deve suportar diferentes critérios, como nome do evento e palavras-chave. |
|     Prioridade         | Must-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">RQ01</a> |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

## US02 - Registrar e acompanhar ordens de serviço

<center>Tabela 3: Registrar e acompanhar ordens de serviço

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US02              | O usuário deve poder registrar e acompanhar ordens de serviço.   |
|     Descrição          | Eu, como usuário, desejo registrar e acompanhar ordens de serviço para gerenciar eficientemente as atividades relacionadas. |
| Critérios de Aceitação | - Deve haver uma opção clara no aplicativo para registrar uma nova ordem de serviço, incluindo campos como descrição, prioridade, data, e responsável.<br> - O sistema deve permitir visualizar uma lista de ordens de serviço registradas, com informações básicas (ex.: título, status, prioridade).<br> - Deve ser possível atualizar o status de uma ordem de serviço (ex.: Pendente, Em Progresso, Concluído).<br> - O usuário deve poder filtrar ou buscar ordens de serviço com base em critérios como status ou prioridade. |
|     Prioridade         | Must-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">RQ23</a> |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

## US03 - Buscar atendimento pelo protocolo

<center>Tabela 4: Buscar atendimento pelo protocolo

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US04              | 	O aplicativo deve permitir que o usuário busque um atendimento pelo protocolo.   |
|     Descrição          | Eu, como usuário, desejo buscar um atendimento pelo protocolo para acompanhar rapidamente o status de uma solicitação específica. |
| Critérios de Aceitação | - Deve haver um campo de busca na interface do aplicativo, onde o usuário possa inserir o número do protocolo.<br> - Após digitar o protocolo e confirmar a busca, o sistema deve exibir os detalhes do atendimento correspondente, como status, data de registro, e descrição.<br> - Caso o protocolo não seja encontrado, o sistema deve informar ao usuário que não há registros correspondentes.<br> - A busca pelo protocolo deve ser rápida, com retorno dos resultados em até 5 segundos. |
|     Prioridade         | Should-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">REQ30</a> |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

## US04 - Alterar o vencimento da conta

<center>Tabela 5: Alterar vencimento de conta

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US05              | 		O aplicativo deve permitir que o usuário altere o vencimento da conta.   |
|     Descrição          | Eu, como usuário, desejo alterar a data de vencimento da minha conta para adequá-la às minhas necessidades financeiras e evitar atrasos no pagamento. |
| Critérios de Aceitação | - Deve haver uma opção na interface do aplicativo para alterar a data de vencimento da conta, localizada de forma clara e acessível.<br> - O sistema deve permitir que o usuário selecione uma nova data dentro de um intervalo permitido (ex.: do dia 1 ao dia 28 de cada mês).<br> - Após a alteração, o sistema deve confirmar a mudança e informar ao usuário a nova data de vencimento.<br> - Caso a alteração não seja possível (ex.: devido a restrições de contrato), o sistema deve apresentar uma mensagem explicativa ao usuário. |
|     Prioridade         | Could-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">REQ29</a> |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

## US05 - Exibir pequenas descrições ao lado dos serviços

<center>Tabela 6: Descrições de serviços

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US06              | O sistema deve exibir pequenas descrições ao lado dos serviços para mostrar seu estado atual.   |
|     Descrição          | Eu, como usuário, desejo visualizar pequenas descrições ao lado dos serviços para entender rapidamente o estado atual de cada um. |
| Critérios de Aceitação | - O sistema deve exibir uma breve descrição ou rótulo ao lado de cada serviço listado, indicando claramente seu estado atual (ex.: "Em Andamento", "Concluído", "Pendente").<br> - As descrições devem ser dinâmicas e atualizadas automaticamente quando o estado do serviço for alterado.<br> - As informações exibidas devem ser concisas, com no máximo 2-3 palavras para evitar poluição visual.<br> - O design deve ser responsivo, garantindo que as descrições sejam legíveis em dispositivos móveis e telas menores. |
|     Prioridade         | Could-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">REQ07</a> |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

## US06 - Adiantamento de processos via aplicativo

<center>Tabela 7: Adiantamento de processos via aplicativo

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US07              |  	O sistema deve possibilitar o adiantamento de processos via aplicativo.   |
|     Descrição          | Eu, como usuário, desejo poder adiantar processos diretamente pelo aplicativo para reduzir o tempo de espera e agilizar os procedimentos. |
| Critérios de Aceitação | - Deve haver uma opção no aplicativo que permita ao usuário solicitar o adiantamento de um processo, visível em locais relevantes (ex.: detalhes do processo).<br> - O sistema deve apresentar as condições e requisitos para que o adiantamento seja possível, como taxas ou documentos necessários.<br> - Após solicitar o adiantamento, o usuário deve receber uma confirmação com o novo status e um prazo atualizado.<br> - Caso o adiantamento não seja possível, o sistema deve informar os motivos e sugerir alternativas (se aplicável).|
|     Prioridade         | Could-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">REQ10</a> |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

## US07 - Filtrar atendimentos por ano, mês e status

<center>Tabela 8: Filtrar atendimentos por ano, mês e status

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US08              | A funcionalidade "Atendimentos" deve permitir filtros por ano, mês e status |
|     Descrição          | Eu, como usuário, desejo filtrar os atendimentos por ano, mês e status (finalizado ou em andamento) para localizar rapidamente os registros relevantes. |
| Critérios de Aceitação | - Deve haver opções de filtro claras e acessíveis na funcionalidade "Atendimentos".<br> - O sistema deve permitir selecionar um ou mais dos seguintes critérios de filtro: ano, mês e status (finalizado ou em andamento).<br> - Após aplicar os filtros, a lista de atendimentos exibida deve ser atualizada automaticamente para mostrar apenas os registros correspondentes.<br> - O sistema deve permitir combinar filtros (ex.: filtrar por ano e status ao mesmo tempo).<br> - Deve haver uma opção para limpar os filtros aplicados e retornar à lista completa de atendimentos. |
|     Prioridade         | Could-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">REQ17</a> |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

## US08 - Permitir pagamento mensal recorrente

<center>Tabela 9: Permitir pagamento mensal recorrente

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US09              | O Sistema deve permitir pagamento mensal recorrente |
|     Descrição          | Eu, como usuário, desejo cadastrar um cartão para fazer o pagamento das minhas contas de forma recorrente. |
| Critérios de Aceitação | - Deve haver opção de cadastrar um cartão de crédito para para pagamento recorrente.<br> |
|     Prioridade         | Could-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">RQ09 </a> |

</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

## US09 - Atualizar seus dados cadastrais pelo app

<center>Tabela 10: Atualizar seus dados cadastrais pelo app

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US10              | O Sistema deve permitir ao usuário atualizar seus dados cadastrais pelo app |
|     Descrição          | Eu, como usuário, desejo atualizar meus dados cadastrais pelo app para manter meus dados atualizados. |
| Critérios de Aceitação | - Deve haver opção de atualizar dados como nome, sexo, email e telefone.<br> |
|     Prioridade         | Should-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">RQ20 </a> |

</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

## US10 - Notificar o usuário para lembrar vencimento de contas e ações pendentes.

<center>Tabela 11: Notificar o usuário para lembrar vencimento de contas e ações pendentes.

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US11              | O Sistema deve notificar o usuário para lembrar vencimento de contas e ações pendentes. |
|     Descrição          | Eu, como usuário, desejo permitir que o aplicativo me envie notificações para que eu me lembre de vencimentos de contas e ações pendentes. |
| Critérios de Aceitação | - Deve haver opção de ativar notificações.<br> - O aplicativo envia uma notificação quando estiver perto do vencimento da conta ou com ações pendentes.<br> |
|     Prioridade         | Could-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">RQ12 </a> |

</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

## US11 - Permitir ao usuário informar vazamentos na rua ou no hidrômetro

<center>Tabela 12: Permitir ao usuário informar vazamentos na rua ou no hidrômetro

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US12              | O Sistema deve permitir ao usuário informar vazamentos na rua ou no hidrômetro |
|     Descrição          | Eu, como usuário, desejo informar vazamentos na rua ou no hidrômetro para contribuir com a resolução rápida de problemas. |
| Critérios de Aceitação | - O sistema deve permitir que o usuário informe o local e a natureza do vazamento (rua ou hidrômetro).<br> - Deve haver um campo para anexar fotos e uma descrição do problema.<br> - O sistema deve confirmar o recebimento da solicitação.<br> |
|     Prioridade         | Must-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">RQ19 </a> |

</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

## US12 - Permitir ao usuário agendar atendimento presencial na unidade mais próxima

<center>Tabela 13: Permitir ao usuário agendar atendimento presencial na unidade mais próxima

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US13              | O Sistema deve permitir ao usuário agendar atendimento presencial na unidade mais próxima |
|     Descrição          | Eu, como usuário, desejo agendar atendimento presencial na unidade mais próxima para resolver questões pessoalmente. |
| Critérios de Aceitação | - O sistema deve exibir as unidades disponíveis com base na localização do usuário.<br> - Deve ser possível escolher data e horário entre as opções disponíveis.<br> - O sistema deve enviar uma confirmação do agendamento.<br> |
|     Prioridade         | Should-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">RQ21 </a> |

</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

## US13 -  Barra de Funções Mais Utilizadas.

<center>Tabela 14:  Barra de Funções Mais Utilizadas

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US17             | O sistema deve ter uma barra com as funções mais utilizadas. |
|     Descrição          | Eu, como usuário, desejo ter acesso rápido às funções mais utilizadas em uma barra destacada para facilitar anavegação no aplicativo. |
| Critérios de Aceitação | -  Deve haver uma barra fixa ou destacada no topo ou na parte inferior do aplicativo.<br> - A barra deve conter as funções mais utilizadas, como “Segunda Via”, “Pagamento”, “Relatar Falta de Água”, etc. <br> - A ordem das funções deve ser ajustada automaticamente com base no uso do usuário ou definido pelo administrador.|
|     Prioridade         | Must-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">RQ02</a> |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

## US14 - Segunda Via de Conta.

<center>Tabela 15:  Segunda Via de Conta.

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US18              | O sistema deve permitir emitir e visualizar segunda via de conta. |
|     Descrição          | Eu, como usuário, desejo emitir ou visualizar a segunda via da conta diretamente pelo aplicativo, para simplificar o acesso às informações de pagamento. |
| Critérios de Aceitação | -  Deve haver uma opção visível para emitir ou visualizar a segunda via da conta.<br> - A segunda via deverá estar disponível para download em formato PDF. <br> - O sistema deve exibir um histórico de contas pagas e em aberto.|
|     Prioridade         | Must-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">RQ04</a> |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

## US15 - Formas de Pagamento.

<center>Tabela 16: Formas de Pagamento.

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US19              | O sistema deve oferecer várias formas de pagamento. |
|     Descrição          | Eu, como usuário, desejo que o aplicativo ofereça várias formas de pagamento para que eu possa escolher a mais conveniente. |
| Critérios de Aceitação | - O sistema deve oferecer métodos de pagamento como cartão de crédito, débito, PIX e boleto bancário.<br> - O usuário deverá receber uma confirmação de pagamento imediatamente após o processo ser concluído. <br> - As opções de pagamento devem ser acessíveis em uma área destacada do aplicativo.|
|     Prioridade         | must-have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">RQ08</a> |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

## US16 - Envio de Documentos.

<center>Tabela 17: Envio de Documentos.

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US20              | O sistema deve permitir o envio de documentos pelo aplicativo. |
|     Descrição          | Eu, como usuário, desejo enviar documentos diretamente pelo aplicativo para facilitar o envio de comprovantes ou transações. |
| Critérios de Aceitação | - Deve haver uma funcionalidade para anexar e enviar documentos no formato PDF ou imagem (JPEG/PNG).<br> - O sistema deve confirmar o envio dos documentos com uma notificação ou mensagem no aplicativo. <br> - Os documentos enviados devem ser armazenados com segurança e condicionados ao perfil do usuário.|
|     Prioridade         | Must-Have |
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">RQ11</a> |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

## US17 - Chat ou Atendimento Virtual.

<center>Tabela 18: Chat ou Atendimento Virtual.

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US21              | O sistema deve incluir chat ou atendimento virtual. |
|     Descrição          | Eu, como usuário, desejo acessar um chat ou atendimento virtual no aplicativo para resolver dúvidas e problemas de forma rápida. |
| Critérios de Aceitação | - O aplicativo deve incluir um chatbot com respostas automáticas para perguntas frequentes e escalonamento para atendimento humano, se necessário.<br> - O chat deve estar acessível na página principal ou no menu de suporte.<br> - O sistema deve armazenar o histórico de conversas para referência futura.|
|     Prioridade         | Deve-Ter|
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">RQ13</a> |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

## US18 - Informar Vazamento.

<center>Tabela 19: Informar Vazamento.

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US22              | O sistema deve permitir informar vazamentos. |
|     Descrição          | Eu, como usuário, desejo que a funcionalidade "Informar Vazamento na Rua" mostre apenas o mapa das regiões onde a Caesb atua para evitar confusões. |
| Critérios de Aceitação | - O mapa desenhado deve limitar as regiões de atuação da Caesb.<br> - A funcionalidade deve permitir que o usuário marque o local do vazamento no mapa com precisão.<br> - O sistema deve confirmar o envio da solicitação com um número de protocolo.|
|     Prioridade         | Must-Have|
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">RQ14</a> |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

## US19 - Informar e Visualizar Falta de Água.

<center>Tabela 20: Informar e Visualizar Falta de Água.

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US23              | O sistema deve permitir informar e visualizar falta de água. |
|     Descrição          | Eu, como usuário, desejo poder informar e visualizar informações sobre a falta de água para saber o status do problema e planejar meu dia. |
| Critérios de Aceitação | - O aplicativo deve permitir que o usuário registre falta de água com informações como local, dados e hora.<br> - O sistema deve exibir notificações sobre falta de água em andamento na região do usuário.<br> -As informações devem ser atualizadas em tempo real e apresentar o status da resolução do problema.|
|     Prioridade         | Must-Have|
|     Rastreabilidade    | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos" target="_blank">RQ15</a> |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

## US20 - Acesso/Pagamento de Contas Passadas.
<center>Tabela 21: Acesso/Pagamento de Contas Passadas.

| ID                     | Nome                                                                                        |
| ---------------------- | ------------------------------------------------------------------------------------------- |
| US03                   | O sistema deve permitir acessar/pagar contas passadas.                                    |
| Descrição              | Eu, como usuário, desejo poder acessar e pagar contas passadas diretamente pelo aplicativo para facilitar minha gestão financeira. |
| Critérios de Aceitação | - O sistema deve listar todas as contas passadas disponíveis para acesso. <br> - O usuário deve poder selecionar uma conta e visualizar os detalhes. <br> - O usuário deve ter a opção de pagar a conta diretamente pelo aplicativo. |
| Prioridade             | Must-Have                                                                                   |
| Rastreabilidade        | [RQ03](https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos) |

</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a></center>

<br>

## US21 - Consulta de Consumo.
<center>Tabela 22: Consulta de Consumo.

| ID                     | Nome                                                                                        |
| ---------------------- | ------------------------------------------------------------------------------------------- |
| US05                   | O sistema deve permitir consultar consumo.                                                |
| Descrição              | Eu, como usuário, desejo poder consultar meu consumo de água para monitorar minha utilização e economizar. |
| Critérios de Aceitação | - O aplicativo deve mostrar o consumo total do usuário em um período selecionado. <br> - O usuário deve ter a opção de visualizar gráficos comparativos do consumo. |
| Prioridade             | Must-Have                                                                                   |
| Rastreabilidade        | [RQ05](https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos) |

</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a></center>

<br>

## US22 - Bloqueio/Reativação/Solicitação de Reparo.
<center>Tabela 23: Bloqueio/Reativação/Solicitação de Reparo.

| ID                     | Nome                                                                                        |
| ---------------------- | ------------------------------------------------------------------------------------------- |
| US06                   | O sistema deve permitir bloqueio, reativação ou solicitação de reparo.                    |
| Descrição              | Eu, como usuário, desejo poder bloquear minha conta, reativá-la ou solicitar reparo diretamente pelo aplicativo para gerenciar melhor meu serviço. |
| Critérios de Aceitação | - O aplicativo deve fornecer opções para bloquear, reativar ou solicitar reparo. <br> - O usuário deve receber confirmação de cada ação realizada. |
| Prioridade             | Must-Have                                                                                   |
| Rastreabilidade        | [RQ06](https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos) |

</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a></center>

<br>

## US23 - Correção de Erros.
<center>Tabela 24: Correção de Erros.

| ID                     | Nome                                                                                        |
| ---------------------- | ------------------------------------------------------------------------------------------- |
| US16                   | O sistema deve permitir ao usuário corrigir erros retornando à tela anterior e atualizando os dados. |
| Descrição              | Eu, como usuário, desejo que, ao identificar um erro, eu possa corrigir rapidamente e voltar à tela anterior sem perder os dados. |
| Critérios de Aceitação | - O usuário deve ter a opção de voltar à tela anterior. <br> - O sistema deve atualizar os dados após a correção sem perder informações. |
| Prioridade             | Must-Have                                                                                   |
| Rastreabilidade        | [RQ16](https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos) |

</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a></center>

<br>

## US24 - Simulação de Tarifa.
<center>Tabela 25: Simulação de Tarifa.

| ID                     | Nome                                                                                        |
| ---------------------- | ------------------------------------------------------------------------------------------- |
| US18                   | A funcionalidade "Simulação de tarifa" deve ser nativa do aplicativo e não redirecionar ao site da Caesb. |
| Descrição              | Eu, como usuário, desejo poder simular tarifas diretamente no aplicativo, sem necessidade de ser redirecionado a outro site. |
| Critérios de Aceitação | - O aplicativo deve ter uma seção específica para simulação de tarifas. <br> - O usuário deve receber resultados instantâneos da simulação. |
| Prioridade             | Must-Have                                                                                   |
| Rastreabilidade        | [RQ18](https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos) |

</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a></center>

<br>

## US25 - Dicas de Consumo Consciente.
<center>Tabela 26: Dicas de Consumo Consciente.

| ID                     | Nome                                                                                        |
| ---------------------- | ------------------------------------------------------------------------------------------- |
| US22                   | O aplicativo deve exibir dicas de consumo consciente e economia de água.                   |
| Descrição              | Eu, como usuário, desejo receber dicas sobre consumo consciente e formas de economizar água para melhorar minha gestão de recursos. |
| Critérios de Aceitação | - O aplicativo deve exibir dicas em uma seção dedicada. <br> - O usuário deve poder visualizar dicas personalizadas com base em seu consumo. |
| Prioridade             | Should-Have                                                                                 |
| Rastreabilidade        | [RQ22](https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos) |

</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a></center>

<br>

## US26 - Alertas sobre Manutenção Programada.
<center>Tabela 27: Alertas sobre Manutenção Programada.

| ID                     | Nome                                                                                        |
| ---------------------- | ------------------------------------------------------------------------------------------- |
| US24                   | O aplicativo deve disponibilizar alertas sobre manutenção programada.                     |
| Descrição              | Eu, como usuário, desejo ser notificado sobre manutenções programadas para evitar interrupções no serviço. |
| Critérios de Aceitação | - O usuário deve receber notificações sobre manutenções com antecedência. <br> - O aplicativo deve permitir que o usuário visualize um histórico de manutenções programadas. |
| Prioridade             | Should-Have                                                                                 |
| Rastreabilidade        | [RQ24](https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos) |

</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a></center>

<br>

## US27 - Alteração na Titularidade da Conta.
<center>Tabela 28: Alteração na Titularidade da Conta.

| ID                     | Nome                                                                                        |
| ---------------------- | ------------------------------------------------------------------------------------------- |
| US25                   | O usuário deve poder solicitar alteração na titularidade da conta.                        |
| Descrição              | Eu, como usuário, desejo ter a opção de solicitar a alteração na titularidade da minha conta para gerenciar melhor minha relação com a Caesb. |
| Critérios de Aceitação | - O aplicativo deve fornecer um formulário para solicitação de alteração. <br> - O usuário deve receber confirmação e status da solicitação. |
| Prioridade             | Must-Have                                                                                   |
| Rastreabilidade        | [RQ25](https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos) |

</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a></center>

<br>

## US28 - Escolher imóvel desejado.
<center>Tabela 29: Escolher imóvel desejado.

| ID                     | Nome                                                                                        |
| ---------------------- | ------------------------------------------------------------------------------------------- |
| US33                   | O aplicativo deve permitir que o usuário escolha o imóvel desejado.                     |
| Descrição              | Eu, como usuário, quero poder escolher o imóvel desejado, para que eu possa consultar e gerenciar os serviços de abastecimento de água e esgoto, verificar o histórico de consumo, fazer solicitações ou consultar débitos relacionados ao imóvel. |
| Critérios de Aceitação | - O aplicativo deve exibir uma lista de imóveis cadastrados ou permitir a busca por endereço para que o usuário possa selecionar o imóvel desejado. <br> - Caso o imóvel não esteja cadastrado, o usuário deve ser orientado a realizar o cadastro ou buscar informações relacionadas. <br> - O usuário pode selecionar o imóvel desejado da lista para consultar ou realizar ações, como verificar o consumo de água, acessar faturas, solicitar serviços, etc. |
| Prioridade             | Must-Have                                                                                 |
| Rastreabilidade        | [RQ26](https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos) |

</p>Autor(a): <a href="https://github.com/jmarquees" target="_blank">Joao Victor Marques</a></center>

<br>

## US29 - Reconhecimento automático de imóveis.
<center>Tabela 30: Reconhecimento automático de imóveis.

| ID                     | Nome                                                                                        |
| ---------------------- | ------------------------------------------------------------------------------------------- |
| US34                   | O aplicativo deve reconhecer automaticamente os imóveis associados ao cliente da Caesb.                     |
| Descrição              | Eu, como usuário, quero que o aplicativo reconheça automaticamente os imóveis associados à minha conta, para que eu possa acessar rapidamente as informações e serviços relacionados a esses imóveis, sem precisar fazer o cadastro manualmente. |
| Critérios de Aceitação | - O aplicativo deve identificar e exibir automaticamente todos os imóveis associados à conta do cliente, com base no CPF, CNPJ ou outra informação de identificação fornecida no login. <br> - Após o login, o cliente verá uma lista com todos os imóveis associados à sua conta, incluindo informações básicas como endereço, número de matrícula e status dos serviços (água, esgoto).  <br> - O cliente não precisará inserir dados adicionais para visualizar os imóveis, pois as informações serão recuperadas automaticamente da base de dados da CAESB. <br> - Para cada imóvel listado, o aplicativo deve permitir que o cliente visualize informações detalhadas, como consumo de água, status de pagamentos, débitos, entre outros. |
| Prioridade             | Should-Have                                                                                 |
| Rastreabilidade        | [RQ27](https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos) |

</p>Autor(a): <a href="https://github.com/jmarquees" target="_blank">Joao Victor Marques</a></center>

<br>

## US30 - Consideração do número de pessoas no imóvel.
<center>Tabela 31: Consideração do número de pessoas no imóvel.

| ID                     | Nome                                                                                        |
| ---------------------- | ------------------------------------------------------------------------------------------- |
| US35                   | O aplicativo deve considerar o número de pessoas no imóvel para calcular a média do consumo.                     |
| Descrição              | Eu, como usuário, quero que o aplicativo considere o número de pessoas no meu imóvel ao calcular a média do consumo de água, para que eu tenha uma estimativa mais precisa do consumo baseado na quantidade de moradores. |
| Critérios de Aceitação | - O aplicativo deve permitir que o usuário informe o número de pessoas no imóvel, seja durante o cadastro ou por meio de atualização nas configurações.  <br> - O cálculo da média de consumo de água deve ser ajustado automaticamente com base no número de pessoas informadas.   <br> - O usuário deve poder visualizar a média de consumo de água, levando em consideração o número de pessoas no imóvel, em comparação com o histórico de consumo anterior.  <br> - O sistema deve gerar uma recomendação de consumo com base no número de moradores, mostrando se o consumo está dentro da média ou se há alguma anomalia. |
| Prioridade             | Should-Have                                                                                 |
| Rastreabilidade        | [RQ28](https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados/#requisitos) |

</p>Autor(a): <a href="https://github.com/jmarquees" target="_blank">Joao Victor Marques</a></center>

<br>


## Referências Bibliográficas

> <p id="1">SERRANO, Milene. SERRANO, Maurício. Requisitos – Aula 15 . Disponível em: https://aprender3.unb.br/pluginfile.php/2972504/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf . Acesso em 12 dez 2024.</p>

<br>

## Histórico de versão

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :-----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 13/12/2024 | Criação da introdução, metodologia e adição da US01 a US08| [Leandro de Almeida](https://github.com/leomitx10) |[Natan Almeida](https://github.com/natanalmeida03) |
|  1.1   | 14/12/2024 | Adição de historias de usuario | [Natan Almeida](https://github.com/natanalmeida03) | [Leandro de Almeida](https://github.com/leomitx10) |
|  1.2   | 14/12/2024 | Adição de historias de usuario | [Letícia Resende](https://github.com/LeticiaResende23)| [Leandro de Almeida](https://github.com/leomitx10) |
|  1.3   | 15/12/2024 | Adição das historias de usuario 25 até 32| [Matheus Barros](https://github.com/Ninja-Haiyai)| [Leandro de Almeida](https://github.com/leomitx10)|
|  1.4   | 17/12/2024 | Adição das historias de usuario 33 a 40| [Joao Victor Marques](https://github.com/jmarquees)| [Leandro de Almeida](https://github.com/leomitx10)|
|  1.5   | 05/02/2025 | correção pós apresentação | [Letícia Resende](https://github.com/LeticiaResende23)| [Leandro de Almeida](https://github.com/leomitx10) |