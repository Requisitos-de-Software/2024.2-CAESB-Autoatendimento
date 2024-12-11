# Casos de Uso

## Introdução
<p align="justify">&emsp;&emsp;O diagrama de casos de uso, também conhecido como diagrama comportamental na notação UML, tem como objetivo registrar como o sistema deve funcionar sob a perspectiva de um usuário externo. Para isso, utiliza os léxicos identificados durante a definição dos casos de uso, descrevendo, assim, um conjunto de ações realizadas pelo sistema.</p>

<p align="justify">&emsp;&emsp;No contexto do diagrama de casos de uso, cada caso deve fornecer um resultado prático para o usuário que interage com ele. Quando determinados casos exigem maior detalhamento, recomenda-se adotar uma abordagem mais descritiva e próxima da linguagem natural. Essa prática, amplamente aceita pela comunidade de desenvolvedores, é conhecida como previsão de casos de uso.</p>

## Metodologia
<p align="justify">&emsp;&emsp;Para a criação dos artistas, foi adotada uma abordagem tradicional, consistindo na elaboração de um diagrama de casos de uso UML. Utilizou-se a ferramenta LucidChart, um software especializado em criação</p>

## Componentes e Símbolos
<p align="justify">&emsp;&emsp;Um diagrama de casos de uso é composto pelos seguintes elementos, os quais serão explicados a seguir para oferecer uma compreensão mais detalhada do diagrama.</p>

## Atores
<p align="justify">&emsp;&emsp;Representamos os usuários e sistemas, ou categorias desses elementos, sendo geralmente ilustrados por ícones que lembram figuras humanas.</p>

<center> <figcaption>Figura 1: Atores do sistema.</figcaption></center>
<center>
<img src="https://github.com/user-attachments/assets/593648c5-62d3-4fb1-81cd-39a4230d6ecf"></img>
 </p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
 </center>

<br>

## Cenário
<p align="justify">&emsp;&emsp;Neste elemento, são descritos os eventos que ocorrem quando um usuário interage com o sistema. Normalmente, é representado por uma caixa.</p>

<p align="justify">&emsp;&emsp;Todos os casos de uso que o sistema descrito devem ser incluídos neste cenário; caso contrário, serão considerados fora do escopo do sistema.</p>

<center> <figcaption>Figura 2: Cenário.</figcaption>
<img src="https://github.com/user-attachments/assets/4773f2c8-40dd-4296-81b6-dcc25b529bdb"></img>
 </p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a></center>

<br>

## Casos de uso
<p align="justify">&emsp;&emsp;O caso de uso é uma ação ou funcionalidade realizada pelo usuário, o ator. Normalmente, é representado por um objeto oval horizontal, sendo que cada representação corresponde a uma interação distinta que o usuário pode ter com o sistema. Para se referir às ações realizadas, é comum usar verbos no infinitivo para descrevê-las.</p>

<center> <figcaption>Figura 3: Casos de uso.</figcaption>
<img src="https://github.com/user-attachments/assets/bbc415ec-a831-4518-b7f4-248823a94e24"></img>
 </p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a></center>

<br>

## Comunicação (ou ação)
Consiste em uma ação que o usuário realizará sobre o caso de uso, conforme ilustrado na imagem 4. A ação pode ser de dois tipos:

Inclusão: Quando a funcionalidade de um caso de uso precisa ser realizada por meio de outro caso de uso. Em outras palavras, um caso de uso A inclui o caso de uso B, de forma que, ao executar o caso de uso A, o caso de uso B será automaticamente executado junto.

 - Notação no diagrama : <>

Extensão: O caso de uso atual será executado normalmente, mas alguns casos de uso podem adicionar etapas extras no caso de uso estendido. Ou seja, se o caso de uso A estende o caso de uso B, ao executar o caso de uso A, o caso de uso B poderá ou não ser executado também.

 - Notação no diagrama : <<>>

 <center> <figcaption>Figura 4: Comunicação.</figcaption>
<img src="https://github.com/user-attachments/assets/aa3de9ad-ebd8-4926-87f9-92d9f1ac5ebc"></img>
 </p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a></center>

 <br>

## Casos de Uso

<p align="justify">&emsp;&emsp;Os principais casos de uso, mais relevantes e frequentemente utilizados no aplicativo, estão ilustrados na imagem 5. Para uma visualização mais detalhada da imagem, consulte os casos de uso na Caesb Autoatendimento.</p>

 <center> <figcaption>Figura 5: Caso de uso 1, do aplicativo da Caesb Autoatendimento.</figcaption>
<img src="https://github.com/user-attachments/assets/2f489c98-7246-4f38-8687-24cd16ba5032"></img>
</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a></center>

<br>

 <center> <figcaption>Figura 6: Diagrama de caso de uso 2, do aplicativo da Caesb Autoatendimento.</figcaption>
<img src="https://github.com/Requisitos-de-Software/2024.2-CAESB-Autoatendimento/blob/main/docs/assets/uc2.png?raw=true"></img>
</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a></center>

<br>

## Requisitos Utilizados

<center>
<font size="3"><p style="text-align: center">Tabela 1: Informa os Requisitos utilizados no diagrama de caso de uso 1. </p></font>

| Id | Descrição | Implementado |
| ----- | ---------- | -------------- |
| OBS3 |Visualizar Segunda Via de Conta | Sim |
| INT06| Informar Falta d'Água | Sim |
| ADD03| Realizar Auto Leitura do Hidrômetro | Sim |
| INT01| Informar Vazamento | Sim |
| INT03| Consultor Histórico de Consumo| Sim |
| ADD02| Alterar Titularidade e Vencimento| Sim |
| INT15| Agenda Atendimento Presencial | Não |
| ADD09| Suporte de Chat ou Atendimento | Não |
| ADD08| Notificações de Vencimento | Não |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<center>
<font size="3"><p style="text-align: center">Tabela 2: Informa os Requisitos utilizados no diagrama de caso de uso 2. </p></font>

| Id | Descrição | Implementado |
| ----- | ---------- | -------------- |
| B10	| O sistema deve permitir a configuração de um pagamento mensal recorrente | |
| INT14	| O usuário deve poder consultar o mapa de interrupções de fornecimento. | |
| INT18	| O aplicativo deve disponibilizar alertas sobre manutenção programada. | |

</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

## Especialização dos casos de uso

As tabelas de 3 a 10 mostram a especialização dos casos de uso.

<center>
<font size="3"><p style="text-align: center">Tabela 3: Visualizar Segunda Via de Conta </p></font>

| UC01 | Informações |
| ----- | ---------- |
| Descrição |O usuário pode acessar e visualizar a segunda via de sua conta para pagamento |
| Ator | Usuário |
| Pré-condições | Acesso à internet, conta ativa no sistema |
| Ação | O usuário acessou o aplicativo e obteve a segunda via da conta |
| Fluxo principal |1. O usuário acessa o aplicativo. </br>2. O usuário seleciona "Segunda Via de Conta" </br> 3. O sistema exibe a segunda via em formato PDF para download ou impressão </br> |
| Fluxo alternativo | O usuário não encontra a segunda via no app e acessa o suporte |
| Fluxo de exceção | O sistema é indisponível, e o usuário tenta novamente mais tarde |
| Pós-condições | A segunda via da conta é gerada e enviada ao usuário |
| Data de Criação | 05/12/2024 |
| Rastreabilidade |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/priorizacao/tec_In/" target="_blank">OBS3</a> |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 11: Informar Falta d'Água </p></font>

| UC02 | Informações |
| ----- | ---------- |
| Descrição |O usuário pode relatar falta de água em sua localidade para a entrega |
| Ator | Usuário |
| Pré-condições |Acesso à internet, localização conhecida |
| Ação | O usuário relatou falta de água com detalhes de endereço |
| Fluxo principal |1. O usuário acessa o aplicativo </br>2. O usuário seleciona "Informar Falta d'Água" </br> 3. O sistema solicita o endereço ou usa localização automaticamente </br> 4. O usuário confirma as informações e envia o relatório |
| Fluxo alternativo | O sistema não registra a localização automaticamente e o usuário insere manualmente o endereço |
| Fluxo de exceção | O sistema é indisponível, e o usuário tenta novamente mais tarde|
| Pós-condições | A falta d'água é registrada para análise e resposta |
| Data de Criação | 05/12/2024 |
| Rastreabilidade |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/priorizacao/tec_In/" target="_blank">INT06</a>  |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 11: Realizar Auto Leitura do Hidrômetro </p></font>

| UC03 | Informações |
| ----- | ---------- |
| Descrição |O usuário pode informar a leitura do hidrômetro manualmente para atualizar o consumo |
| Ator | Usuário |
| Pré-condições |Acesso ao hidrômetro, acesso ao aplicativo |
| Ação | O usuário registra a leitura no sistema |
| Fluxo principal |1. O usuário acessa o aplicativo </br>2. O usuário seleciona "Auto Leitura do Hidrômetro" </br> 3. O sistema solicita os dados da leitura atual </br> 4.  O usuário insira os dados e confirme o envio |
| Fluxo alternativo | O usuário insere um valor incorreto e o sistema solicita uma nova leitura |
| Fluxo de exceção | O hidrômetro está inacessível, e o usuário registra o problema no sistema|
| Pós-condições | A leitura do hidrômetro é atualizada no sistema |
| Data de Criação | 05/12/2024 |
| Rastreabilidade |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/priorizacao/tec_In/" target="_blank">ADD03</a>  |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 11: Informar Vazamento </p></font>

| UC04 | Informações |
| ----- | ---------- |
| Descrição |O usuário pode relatar vazamentos de água observados em residência ou área externa |
| Ator | Usuário |
| Pré-condições |Acesso à internet, informações do local do vazamento |
| Ação |O usuário registra os detalhes do vazamento no sistema |
| Fluxo principal |1. O usuário acessa o aplicativo </br>2. O usuário seleciona "Informar Vazamento" </br> 3. O sistema solicita informações como localização e descrição do problema </br> 4.  O usuário confirma as informações e envia |
| Fluxo alternativo | O sistema sugere campos adicionais para complementação caso as informações estejam incompletas |
| Fluxo de exceção | O sistema é indisponível, e o usuário tenta novamente mais tarde|
| Pós-condições | O vazamento é registrado no sistema para ação da equipe técnica |
| Data de Criação | 05/12/2024 |
| Rastreabilidade |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/priorizacao/tec_In/" target="_blank">INT01</a>  |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 11: Consultor Histórico de Consumo </p></font>

| UC05 | Informações |
| ----- | ---------- |
| Descrição |O usuário pode consultar o histórico de consumo de água ao longo do tempo |
| Ator | Usuário |
| Pré-condições |Acesso à internet, dados disponíveis no sistema|
| Ação |O usuário visualiza os dados históricos no aplicativo |
| Fluxo principal |1. O usuário acessa o aplicativo </br>2. O usuário seleciona "Histórico de Consumo" </br> 3. O sistema exibe os dados de consumo por períodos (mensal, anual) </br> |
| Fluxo alternativo | Não há dados disponíveis para o período selecionado e o sistema de informação ao usuário |
| Fluxo de exceção | O sistema é indisponível, e o usuário tenta novamente mais tarde|
| Pós-condições | O histórico de consumo é mostrado com sucesso |
| Data de Criação | 05/12/2024 |
| Rastreabilidade |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/priorizacao/tec_In/" target="_blank">INT03</a> |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 11: Alterar Titularidade e Vencimento </p></font>

| UC06 | Informações |
| ----- | ---------- |
| Descrição |O usuário pode alterar o titular da conta ou os dados de vencimento da fatura |
| Ator | Usuário |
| Pré-condições |Acesso ao sistema, conta ativa|
| Ação |O usuário realiza a alteração solicitada |
| Fluxo principal |1. O usuário acessa o aplicativo </br>2. O usuário seleciona "Alterar Titularidade e Vencimento" </br> 3. O sistema solicita novos dados </br> 4. O usuário confirma e salva as alterações|
| Fluxo alternativo | Dados incompletos, e o sistema solicita complementação antes de salvar |
| Fluxo de exceção | O sistema é indisponível, e o usuário tenta novamente mais tarde|
| Pós-condições | Os dados são atualizados no sistema |
| Data de Criação | 05/12/2024 |
| Rastreabilidade | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/priorizacao/tec_In/" target="_blank">ADD02</a> |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 11: Agenda Atendimento Presencial </p></font>

| UC07 | Informações |
| ----- | ---------- |
| Descrição |O usuário pode agendar um horário para atendimento presencial |
| Ator | Usuário |
| Pré-condições |Acesso ao sistema e horários|
| Ação |A agenda do usuário ou atendimento no sistema |
| Fluxo principal |1. O usuário acessa o aplicativo </br>2. O usuário seleciona "Agenda de Atendimento" </br> 3. O sistema exibe os horários disponíveis </br> 4. O usuário escolhe um dado e local e confirma |
| Fluxo alternativo | Horários indisponíveis, e o sistema sugere outros dias |
| Fluxo de exceção | O sistema é indisponível, e o usuário tenta novamente mais tarde|
| Pós-condições | O atendimento é agendado com sucesso |
| Data de Criação | 05/12/2024 |
| Rastreabilidade |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/priorizacao/tec_In/" target="_blank">INT15</a> |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 11: Suporte de Chat ou Atendimento </p></font>

| UC08 | Informações |
| ----- | ---------- |
| Descrição |O usuário pode acessar o suporte via chat ou atendimento telefônico para resolver problemas ou tirar dúvidas |
| Ator | Usuário |
| Pré-condições |Acesso à internet e conta ativa no sistema|
| Ação |O usuário escolhe a forma de suporte desejada e inicia a comunicação |
| Fluxo principal |1. O usuário acessa o aplicativo </br>2. O usuário seleciona "Suporte" </br> 3. O sistema exibe as opções de atendimento: chat ou telefone </br> 4. O usuário escolhe o método e inicia a comunicação |
| Fluxo alternativo | O sistema não oferece suporte por chat, e o usuário opta por atendimento telefônico |
| Fluxo de exceção |O suporte é indisponível, e o sistema informa o horário de funcionamento|
| Pós-condições | Uma dúvida ou problema do usuário é resolvido por meio do suporte |
| Data de Criação | 05/12/2024 |
| Rastreabilidade | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/priorizacao/tec_In/" target="_blank">ADD09</a> |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>


<center>
<font size="3"><p style="text-align: center">Tabela 11: Notificações de Vencimento </p></font>

| UC09 | Informações |
| ----- | ---------- |
| Descrição |O usuário pode receber notificações sobre o vencimento de contas via e-mail, SMS ou aplicativo |
| Ator | Usuário |
| Pré-condições |Conta ativa no sistema e canais de comunicação configurados |
| Ação |O sistema envia notificações automáticas antes do vencimento da fatura|
| Fluxo principal |1. O sistema identifica os dados de vencimento próximo </br>2.O sistema verifica os canais ativados pelo usuário (e-mail, SMS ou aplicativo) </br> 3. O sistema envia uma notificação ao usuário com antecedência definida</br>|
| Fluxo alternativo | O usuário não configurou os canais de notificação e o sistema alerta sobre a necessidade de configuração |
| Fluxo de exceção |O envio da notificação falhou, e o sistema tenta novamente em outro momento|
| Pós-condições | O usuário recebe uma notificação e é informado sobre os dados de vencimento da conta |
| Data de Criação | 05/12/2024 |
| Rastreabilidade |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/priorizacao/tec_In/" target="_blank">ADD08</a> |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>
<center>
<font size="3"><p style="text-align: center">Tabela 11: Configurar Pagamento Mensal Recorrente </p></font>

| UC10 | Informações |
| ----- | ---------- |
| Descrição |O sistema deve permitir a configuração de um pagamento mensal recorrente |
| Ator | Usuário |
| Pré-condições |O usuário deve estar autenticado no sistema; Uma forma de pagamento válida deve estar cadastrada no sistema. |
| Ação |  O sistema permite configurar o pagamento recorrente, incluindo frequência, valor e forma de pagamento. |
| Fluxo principal |1. O usuário seleciona a opção de configurar pagamento recorrente </br>2.O sistema solicita as informações necessárias  </br> 3. O sistema valida as informações e salva a configuração.</br> 4. Uma confirmação é exibida. <br>|
| Fluxo alternativo | Caso o usuário já tenha um pagamento recorrente configurado, o sistema pode exibir a opção de editar ou cancelar a configuração existente. |
| Fluxo de exceção |Caso a forma de pagamento seja inválida, o sistema exibe uma mensagem de erro e solicita a correção.|
| Pós-condições | A configuração do pagamento recorrente é salva no sistema. |
| Data de Criação | 11/12/2024 |
| Rastreabilidade |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/#requisitos" target="_blank">B10</a> |

</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 12: Consultar o Mapa de Interrupções </p></font>

| UC11 | Informações |
| ----- | ---------- |
| Descrição |Permitir que o usuário visualize áreas afetadas por interrupções no fornecimento. |
| Ator | Usuário |
| Pré-condições |O sistema deve ter acesso às informações de interrupções de fornecimento. |
| Ação |  O sistema exibe um mapa com as áreas afetadas. |
| Fluxo principal |1. O usuário seleciona a opção de consultar o mapa de interrupções. </br>2. O sistema recupera os dados atualizados sobre interrupções. </br> 3. O mapa é exibido com áreas destacadas por cores.</br>|
| Fluxo alternativo | O usuário pode selecionar uma área específica no mapa para mais detalhes, como horário estimado de retorno. |
| Fluxo de exceção |Caso os dados de interrupções estejam indisponíveis, o sistema exibe uma mensagem de erro e oferece tentar novamente mais tarde. |
| Pós-condições | O usuário obtém informações sobre as interrupções no fornecimento. |
| Data de Criação | 11/12/2024 |
| Rastreabilidade |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos" target="_blank">INT14</a> |

</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 13: Receber Alertas de Manutenção Programada </p></font>

| UC12 | Informações |
| ----- | ---------- |
| Descrição |Permitir que o usuário receba notificações sobre manutenções programadas. |
| Ator | Usuário |
| Pré-condições |O usuário deve estar registrado no sistema. |
| Ação |  O sistema envia alertas por canais configurados. |
| Fluxo principal |1. O sistema verifica se há manutenções programadas. </br>2. Para cada manutenção programada, o sistema verifica os usuários impactados. </br> 3. Os alertas são enviados conforme as preferências do usuário (horário e canal de envio).</br>|
| Fluxo alternativo | Caso o usuário não tenha configurado preferências, o sistema solicita a configuração antes de enviar alertas. |
| Fluxo de exceção |Caso o envio de alerta falhe (ex.: e-mail inválido), o sistema registra o erro e tenta enviar novamente. |
| Pós-condições | O usuário é notificado sobre manutenções programadas. |
| Data de Criação | 11/12/2024 |
| Rastreabilidade |<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos" target="_blank">INT18</a> |

</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 14: Filtro de Atendimentos </p></font>

| UC10 | Informações |
| ----- | ---------- |
| Descrição |O sistema permite que o usuário filtre os atendimentos cadastrados por ano, mês e status (finalizado ou em andamento). |
| Ator | Usuário |
| Pré-condições |O usuário deve estar autenticado no sistema.<br>Devem existir atendimentos cadastrados para consulta.|
| Ação |O sistema exibe os atendimentos de acordo com os filtros aplicados pelo usuário.|
| Fluxo principal |1. O usuário acessa a funcionalidade de Atendimentos. </br>2.O sistema exibe os filtros disponíveis: ano, mês e status. </br> 3. O usuário seleciona um ou mais filtros. </br> 4. O sistema aplica os filtros e exibe os atendimentos correspondentes.|
| Fluxo alternativo | O usuário não seleciona nenhum filtro: o sistema exibe todos os atendimentos disponíveis. |
| Fluxo de exceção | Não há atendimentos que correspondam aos filtros aplicados: o sistema exibe uma mensagem informando que não há resultados.|
| Pós-condições | O usuário visualiza os atendimentos filtrados conforme os critérios selecionados. |
| Data de Criação | 11/12/2024 |
| Rastreabilidade |<a href="#" target="_blank">ADD08</a> |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 15: Simulação de Tarifas </p></font>

| UC11 | Informações |
| ----- | ---------- |
| Descrição | O sistema permite que o usuário realize a simulação de tarifas diretamente no aplicativo, sem redirecionamento para o site da Caesb. |
| Ator | Usuário |
| Pré-condições | O usuário deve estar autenticado no aplicativo.<br> O aplicativo deve estar atualizado e com acesso à funcionalidade de simulação de tarifas.|
| Ação | O sistema realiza a simulação de tarifas com base nos dados fornecidos pelo usuário.|
| Fluxo principal |1. O usuário acessa a funcionalidade Simulação de Tarifa no aplicativo. </br>2.O sistema exibe os campos para entrada de dados, como consumo estimado, tipo de usuário (residencial, comercial, etc.), e outros parâmetros necessários. </br> 3. O usuário preenche os campos e confirma a simulação. </br> 4. O sistema processa as informações e apresenta o resultado da simulação ao usuário.|
| Fluxo alternativo | O usuário não preenche todos os campos obrigatórios: o sistema exibe uma mensagem solicitando o preenchimento dos dados faltantes. |
| Fluxo de exceção | O sistema encontra problemas ao processar a simulação (por exemplo, erro no servidor): o sistema exibe uma mensagem informando a falha e sugere que o usuário tente novamente mais tarde. |
| Pós-condições | O usuário recebe o resultado da simulação de tarifa diretamente no aplicativo, sem necessidade de redirecionamento. |
| Data de Criação | 11/12/2024 |
| Rastreabilidade |<a href="#" target="_blank">ADD08</a> |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 16: Formas de Pagamento </p></font>

| UC12 | Informações |
| ----- | ---------- |
| Descrição | O sistema permite que o usuário escolha entre diferentes formas de pagamento ao realizar uma transação. |
| Ator | Usuário |
| Pré-condições | O usuário deve estar autenticado no aplicativo.<br> Deve haver uma conta disponível para pagamento.|
| Ação | O sistema exibe as opções de pagamento disponíveis e processa a escolha do usuário. |
| Fluxo principal |1. O usuário acessa a funcionalidade de pagamento no sistema. </br> 2.O sistema exibe as formas de pagamento disponíveis, como: cartão de crédito, cartão de débito e pix. </br> 3. O usuário seleciona a forma de pagamento desejada e fornece as informações necessárias (se aplicável). </br> 4. O sistema processa o pagamento e confirma a transação. |
| Fluxo alternativo | O usuário não seleciona nenhuma forma de pagamento: o sistema exibe uma mensagem informando que a seleção é obrigatória para concluir a transação. |
| Fluxo de exceção | O pagamento falha (ex.: cartão recusado, erro de rede): o sistema exibe uma mensagem de erro e orienta o usuário a tentar novamente ou escolher outra forma de pagamento. |
| Pós-condições | A transação é concluída com sucesso e o usuário recebe uma confirmação do pagamento. |
| Data de Criação | 11/12/2024 |
| Rastreabilidade |<a href="#" target="_blank">ADD08</a> |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>


## Referências
> 1. <p style="word-wrap: break-word; overflow-wrap: break-word;">Especificacao de Caso de Uso. Disponível em: https://aprender3.unb.br/pluginfile.php/2972484/mod_resource/content/3/SiglaProjeto_EspecificacaoCasoUso.pdf. Acesso em: 0 dec. 2024.</p> 
> 2. <p style="word-wrap: break-word; overflow-wrap: break-word;"> Casos de Uso. Disponível em: https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf. Acesso em: 05 dec. 2024.</p> 
> 3. <p style="word-wrap: break-word; overflow-wrap: break-word;"> Projeto como exemplo. Disponível em: https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/. Acesso em: 05 dec. 2024.</p> 
> 4. <p style="word-wrap: break-word; overflow-wrap: break-word;"> Ferramenta utilizada para o diagrama de caso de uso: Lucidchart . Disponível em: https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml. Acesso em: 05 dec. 2024.</p> 
<br>

## Histórico de versão

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :-----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 02/12/2024 | Criação do artefato | [Letícia Resende](https://github.com/LeticiaResende23) |[Natan Almeida](https://github.com/natanalmeida03) |
|  1.1   | 05/12/2024 | Inclusão da especificação do caso de uso| [Letícia Resende](https://github.com/LeticiaResende23) |[Leandro de Almeida](https://github.com/leomitx10) |
|  1.2   | 10/12/2024 | Ajustes pós apresentação| [Letícia Resende](https://github.com/LeticiaResende23) |[Leandro de Almeida](https://github.com/leomitx10) |
|  1.3   | 11/12/2024 | Adição de novos requisitos| [Natan Almeida](https://github.com/natanalmeida03) |[Letícia Resende](https://github.com/LeticiaResende23) |
|  1.3   | 11/12/2024 | Inclusão de casos de uso| [Leandro de Almeida](https://github.com/leomitx10) | [Letícia Resende](https://github.com/LeticiaResende23) |

