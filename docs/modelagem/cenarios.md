# Cenários

## Introdução
<p align="justify">&emsp;&emsp;Cenários são narrativas detalhadas que descrevem como os usuários interagem com uma aplicação ou sistema, ajudando a capturar requisitos e compreender o comportamento dos usuários. Cada cenário apresenta um ator principal com um objetivo, cujas ações e eventos são descritos de forma sequencial. Os cenários desenvolvidos estão organizados nas tabelas de 1 a 9.</p>

## Metodologia
<p align="justify">&emsp;&emsp;Os cenários neste documento serão apresentados em formato de texto estruturado, usando linguagem natural semi-estruturada para facilitar o entendimento e a validação dos requisitos pelo cliente. Cada cenário foi feito com base nos requisitos coletados na fase da elicitação.</p>

## Cenário 1: Emitir a Segunda Via de Conta 
<center>Tabela 1: Segunda Via de Conta 

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | Visualizar a **Segunda Via de Conta**                                                                 |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia<br> - **Pré-condições**: Acesso à internet, aplicativo instalado na versão Android. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone e internet                                                                           |
| **Episódios**      | 1. O usuário seleciona a opção **Segunda Via de Conta** na tela inicial.<br>2. O usuário seleciona um imóvel cadastrado na Caesb.<br>3. O aplicativo exibe uma lista com todas as contas.<br>4. O usuário filtra as contas de acordo com o ano selecionado e com o tipo de conta escolhido.<br> 5. O usuário clica em uma conta e obtém a segunda via. |
| **Restrições**     | O usuário deve ter o imóvel referente à conta cadastrado na Caesb. Caso contrário, ele deve informar o número de inscrição da conta.   |
| **Exceção**        | - Smartphone descarregado<br>- Perda de conexão com a internet<br>                               |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

## Cenário 2: Informar Falta d'Água

<center>Tabela 2: Informar Falta d'Água

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | Informar **Falta d'Água**                                                                 |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia<br> - **Pré-condições**: Acesso à internet, aplicativo instalado na versão Android. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone e internet                                                                           |
| **Episódios**      | 1. O usuário seleciona a opção **Informar Falta d'Água** na tela inicial.<br> 2. O usuário seleciona um imóvel cadastrado na Caesb.<br> 3. O usuário envia uma observação em formato de texto pelo aplicativo.  |
| **Restrições**     | O usuário deve ter pelo menos um imóvel cadastrado na Caesb.  |
| **Exceção**        | - Smartphone descarregado<br>- Perda de conexão com a internet<br>- Usuário não autenticado                                  |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

## Cenário 3: Auto Leitura do Hidrômetro

<center>Tabela 3: Auto Leitura do Hidrômetro

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | Realizar **Auto Leitura do Hidrômetro**                                                         |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia<br> - **Pré-condições**: Acesso à internet, aplicativo instalado na versão Android. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone e internet                                                                           |
| **Episódios**      | 1. O usuário seleciona a opção **Auto Leitura do Hidrômetro** na tela inicial.<br>2. O usuário seleciona um imóvel cadastrado na Caesb.<br>3. O aplicativo apresenta ao usuário o termo de adesão ao sistema de autoleitura.<br>4. O usuário concorda com o termo. <br>5. O usuário insere os dados de leitura solicitados pelo aplicativo e envia. |
| **Restrições**     | - O usuário deve ter pelo menos um imóvel cadastrado na Caesb.<br>- O usuário deve aceitar o termo de adesão. |
| **Exceção**        | - Smartphone descarregado<br>- Perda de conexão com a internet<br>- Dados de leitura inválidos<br>                                  |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

## Cenário 4: Informar Vazamento na Rua

<center>Tabela 4: Informar Vazamento na Rua

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | Informar um **Vazamento na Rua**                                                                |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia<br> - **Pré-condições**: Acesso à internet, aplicativo instalado na versão Android. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone e internet                                                                           |
| **Episódios**      | 1. O usuário seleciona a opção **Informar Vazamento na Rua** na tela inicial.<br>2. O aplicativo solicita informações como setor, rua, bairro e uma descrição do problema.<br>3. O usuário confirma as informações e envia. |
| **Restrições**     | O dispositivo Android do usuário deve estar com a função de GPS ativada.                        |
| **Exceção**        | - Smartphone descarregado<br>- Perda de conexão com a internet<br>- GPS desativado                                  |                              |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

## Cenário 5: Consultar Histórico de Consumo

<center>Tabela 5: Consultar Histórico de Consumo

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | Consultar **Histórico de Consumo**                                                              |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia<br> - **Pré-condições**: Acesso à internet, aplicativo instalado na versão Android. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone e internet                                                                           |
| **Episódios**      | 1. O usuário seleciona a opção **Meu Histórico de Consumo** na tela inicial.<br>2. O usuário escolhe um imóvel cadastrado na Caesb.<br>3. O sistema exibe os dados de consumo por períodos (mensal, anual). |
| **Restrições**     | O usuário deve ter pelo menos um imóvel cadastrado na Caesb.                                    |
| **Exceção**        | - Smartphone descarregado<br>- Perda de conexão com a internet                                  |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

## Cenário 6: Alterar Titularidade e Vencimento

<center>Tabela 6: Alterar Titularidade e Vencimento

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | Alterar a **Titularidade e Vencimento** do Imóvel                                               |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia<br> - **Pré-condições**: Acesso à internet, aplicativo instalado na versão Android. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone e internet                                                                           |
| **Episódios**      | 1. O usuário seleciona a opção **Alterar Titularidade e Vencimento** na tela inicial.<br>2. O aplicativo pergunta ao usuário se ele sabe ou não o número de inscrição do imóvel.<br>3. Se o usuário escolher **Sim**, ele deve informar o número de inscrição do imóvel. Se escolher **Não sei**, deve informar o número do hidrômetro.<br>4. O aplicativo solicita a inserção de informações como telefone e e-mail.<br>5. O usuário deve anexar a foto de um documento pessoal e de um documento que comprove a titularidade do imóvel. |
| **Restrições**     | O usuário deve ter pelo menos um imóvel cadastrado na Caesb.                                     |
| **Exceção**        | - Smartphone descarregado<br>- Perda de conexão com a internet<br> - Número de inscrição ou hidrômetro inválido                                   |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

## Cenário 7: Agenda Atendimento Presencial

<center>Tabela 7: Agenda Atendimento Presencial

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | Agendar **Atendimento Presencial**                                                    |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia<br> - **Pré-condições**: Acesso à internet, aplicativo instalado na versão Android. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone e internet                                                                           |
| **Episódios**      | 1. O usuário seleciona a opção **Agenda de Atendimento** na tela inicial.<br>2. O sistema exibe os horários, locais e dias disponíveis.<br>3. O usuário escolhe o dia, hora e local e confirma. |
| **Restrições**     | Esta funcionalidade não possui restrições.                                                      |
| **Exceção**        | - Smartphone descarregado<br>- Perda de conexão com a internet<br>- Incompatibilidade de horário                                  |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

## Cenário 8: Suporte de Chat ou Atendimento

<center>Tabela 8: Suporte de Chat ou Atendimento

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | Suporte de **Chat ou Atendimento**                                                              |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia<br> - **Pré-condições**: Acesso à internet, aplicativo instalado na versão Android. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone e internet                                                                           |
| **Episódios**      | 1. O usuário seleciona a opção **Suporte** na tela inicial.<br>2. O sistema exibe as opções de atendimento: chat ou telefone.<br>3. O usuário escolhe uma opção e aguarda o início do atendimento. |
| **Restrições**     | O usuário deve possuir uma conta na Caesb.                                                     |
| **Exceção**        | - Smartphone descarregado<br>- Perda de conexão com a internet<br>- Tempo de espera excedido<br>- Atendente não disponível                                 |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

## Cenário 9: Notificações de Vencimento

<center>Tabela 9: Notificações de Vencimento

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | Notificações  de **Vencimento**                                                              |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia<br> - **Pré-condições**: Acesso à internet, aplicativo instalado na versão Android. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone e internet                                                                           |
| **Episódios**      | 	1. O sistema identifica os dados de vencimento próximo<br> 2. O sistema verifica os canais ativados pelo usuário (e-mail, SMS ou aplicativo)<br> 3. O sistema envia uma notificação ao usuário com antecedência definida|
| **Restrições**     | O usuário deve possuir uma conta na Caesb.<br> O usuário deve possuir pelo menos um imóvel cadastrado na Caesb.                                                     |
| **Exceção**        | - Smartphone descarregado<br>- Perda de conexão com a internet<br>- Permissão de notificação desativada<br>- Falha na entrega da notificação                                 |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

## Requisitos Utilizados

<center>
<font size="3"><p style="text-align: center">Tabela 10: Informa os Requisitos utilizados no caso de uso 1. </p></font>

| Id | Descrição | Implementado |
| ----- | ---------- | -------------- |
| INT13 | O aplicativo deve disponibilizar a opção de cadastro em débito automático. | Não |
| OBS1 |  O aplicativo deve permitir que o usuário escolha o imóvel desejado. | Não |
| OBS2 |  O aplicativo deve permitir que o usuário selecione o ano ou mês da segunda via da conta.| Não |
| INT02 | O usuário deve poder emitir boleto para pagar a conta de água. | Não |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

## Cenário 10: Cadastro em Débito Automático

<center>Tabela 11: Cadastro em Débito Automático

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | Permitir **o cadastro do débito automático para contas de água**                                                              |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia ou a noite<br> - **Pré-condições**: Acesso ao aplicativo e conta ativa. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone, internet, conta bancária                                                                         |
| **Episódios**      | 1. O usuário acessa o aplicativo e navega até a opção de “Débito Automático”.<br> 2. O sistema solicita que o usuário escolha o imóvel desejado.<br> 3. O usuário seleciona o imóvel e confirma.<br> 4. O sistema exibe uma tela para preenchimento dos dados bancários.<br> 5. O usuário insira as informações e conclua o cadastro. |
| **Restrições**     |- O usuário deve possuir pelo menos um imóvel cadastrado <br> - O banco selecionado deve ser compatível com a funcionalidade.                 |                                    |
| **Exceção**        | - Dados bancários inválidos<br> - Perda de conexão com a internet durante o processo.<br> - Imóvel não elegível para subsídio automático.                                 |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

## Cenário 11: Seleção de Imóvel para Segunda Via da Conta

<center>Tabela 12: Seleção de Imóvel para Segunda Via da Conta

| **Item**       | **Descrição**                                                                                                               |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir ao usuário selecionar o imóvel desejado para acessar a segunda via da conta.                                       |
| **Contexto**   | - Local: Em casa ou qualquer lugar com acesso à internet. <br> - Tempo: Durante o dia ou noite. <br> - Pré-condições: Acesso ao aplicativo e conta ativa. |
| **Atores**     | Usuário                                                                                                                    |
| **Recursos**   | Smartphone, internet                                                                                                       |
| **Episódios**  | 1. O usuário acessa o menu "Segunda Via". <br> 2. O sistema exibe uma lista de imóveis cadastrados no nome do usuário. <br> 3. O usuário seleciona o imóvel desejado. <br> 4. O sistema confirma a seleção e exibe os meses e anos disponíveis para consulta. |
| **Restrições** | O usuário deve possuir pelo menos um imóvel cadastrado.                                                                    |
| **Exceção**    | - Nenhum imóvel cadastrado. <br> - Lista de imóveis não carregada corretamente. <br> - Perda de conexão com a internet.     |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

## Cenário 12: Consulta de Segunda Via por Ano ou Mês

<center>Tabela 13: Consulta de Segunda Via por Ano ou Mês

| **Item**       | **Descrição**                                                                                                               |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir ao usuário consultar a segunda via da conta por ano ou mês selecionado.                                            |
| **Contexto**   | - Local: Em casa ou qualquer lugar com acesso à internet. <br> - Tempo: Durante o dia ou noite. <br> - Pré-condições: Acesso ao aplicativo e imóvel selecionado previamente. |
| **Atores**     | Usuário                                                                                                                    |
| **Recursos**   | Smartphone, internet                                                                                                       |
| **Episódios**  | 1. O usuário acessa a opção "Segunda Via" após selecionar o imóvel. <br> 2. O sistema exibe os anos e meses disponíveis para consulta. <br> 3. O usuário escolhe o ano ou mês desejado. <br> 4. O sistema apresenta a segunda via da conta correspondente para download ou visualização. |
| **Restrições** | A conta deve estar registrada no sistema para os períodos consultados.                                                     |
| **Exceção**    | - Ano ou mês não disponível para consulta. <br> - Falha na geração da segunda via. <br> - Perda de conexão com a internet.  |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

## Cenário 13: Emissão de Boleto para Pagamento da Conta

<center>Tabela 14: Emissão de Boleto para Pagamento da Conta

| **Item**       | **Descrição**                                                                                                               |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir ao usuário emitir um boleto para pagamento de contas de água.                                                     |
| **Contexto**   | - Local: Em casa ou qualquer lugar com acesso à internet. <br> - Tempo: Durante o dia ou noite. <br> - Pré-condições: Acesso ao aplicativo e imóvel com contas pendentes cadastradas. |
| **Atores**     | Usuário                                                                                                                    |
| **Recursos**   | Smartphone, internet                                                                                                       |
| **Episódios**  | 1. O usuário acessa a opção "Emitir Boleto". <br> 2. O sistema solicita que o usuário selecione o imóvel associado à conta. <br> 3. O usuário seleciona o imóvel e confirma. <br> 4. O sistema gera o boleto e disponibiliza para download ou envio por e-mail. |
| **Restrições** | O usuário deve possuir conta pendente para emitir o boleto.                                                                |
| **Exceção**    | - Nenhuma conta pendente associada ao imóvel. <br> - Falha na geração do boleto. <br> - Perda de conexão com a internet.    |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

## Cenário 14: O usuário deve poder consultar o mapa de interrupções de fornecimento.

<center>Tabela 15: O usuário deve poder consultar o mapa de interrupções de fornecimento.

| **Item**       | **Descrição**                                                                                                                 |
|-----------------|-------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir ao usuário visualizar áreas afetadas por interrupções no fornecimento de serviços.                                   |
| **Contexto**   | - Local: Qualquer lugar com acesso ao aplicativo. <br> - Tempo: Durante o dia ou noite. <br> - Pré-condições: O sistema deve ter acesso às informações atualizadas sobre interrupções. |
| **Atores**     | Usuário     |
| **Recursos**   | Smartphone, internet, banco de dados com informações de interrupções                                                        |
| **Episódios**  | 1. O usuário acessa a opção "Mapa de Interrupções". <br> 2. O sistema recupera as informações sobre interrupções ativas. <br> 3. O sistema exibe o mapa com áreas destacadas. <br> 4. O usuário visualiza as áreas afetadas. <br> 5. (Opcional) O usuário seleciona uma área específica para mais detalhes. |
| **Restrições** | Os dados de interrupções devem estar disponíveis e atualizados no banco de dados.                                           |
| **Exceção**    | - Os dados de interrupções estão indisponíveis. <br> - Erro ao carregar o mapa. <br> - Perda de conexão com a internet.       |

</p>Autor(a): <a href="https://github.com/Natanalmeida03" target = "_blank">Natan Almeida</a>
</center>

<br>

## Cenário 15: Filtro de atendimentos.
<center>Tabela 11: Filtro de atendimentos

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | O usuário deve conseguir filtrar os atendimentos cadastrados por ano, mês e status (finalizado ou em andamento).                                                            |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia<br> - **Pré-condições**: Acesso à internet, aplicativo instalado na versão Android. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone e internet                                                                           |
| **Episódios**      | 	1. O usuário seleciona a opção **Meus Atendimentos** na tela inicial.<br>2. O usuário seleciona um imóvel cadastrado na Caesb.<br>3. O aplicativo exibe uma lista com todos os atendimentos com um menu na parte superior possuindo ano, mês e status.<br>4. O usuário filtra os atendimentos de acordo com os filtros que ele escolheu.<br> 5. O usuário clica em um atendimento e visualiza as informações. |
| **Restrições**     | O usuário deve possuir uma conta na Caesb.<br> O usuário deve possuir pelo menos um imóvel cadastrado na Caesb.                                                     |
| **Exceção**        | - Smartphone descarregado<br>- Perda de conexão com a internet<br> |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

## Cenário 16: Simulação de Tarifa.
<center>Tabela 12: Simulação de Tarifa

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | O aplicativo permite que o usuário realize a simulação de tarifa.                              |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia<br> - **Pré-condições**: Acesso à internet, aplicativo instalado na versão Android. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone e internet                                                                           |
| **Episódios**      | 	1. O usuário seleciona a opção **Simulação de Tarifa** na tela inicial.<br>2. O aplicativo exibe os campos consumo, Unidade de Consumo e Categoria para que o usuário consiga simular.<br>3. O usuário clica no botão calcular após inserir os dados.<br> 4. O aplicativo mostra as informações em formato de tabela separadas por água e esgoto. |
| **Restrições**     | O usuário deve possuir uma conta na Caesb.
| **Exceção**        | - Smartphone descarregado<br>- Perda de conexão com a internet<br> |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

## Cenário 17: Formas de Pagamento.
<center>Tabela 12: Formas de Pagamento.

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | O sistema permite que o usuário escolha entre diferentes formas de pagamento ao realizar uma transação.    |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia<br> - **Pré-condições**: Acesso à internet, aplicativo instalado na versão Android. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone e internet                                                                           |
| **Episódios**      | 	1. O usuário seleciona uma opção de pagamento.<br>2. O aplicativo exibe os campos para inserir os dados do pagamento ou o código no caso do pix.<br>3. Após o pagamento ser realizado uma notificação aparece avisando o usuário que tal conta foi paga. |
| **Restrições**     | O usuário deve possuir uma conta na Caesb.<br> O usuário deve estar na tela de pagamento de conta.|
| **Exceção**        | - Smartphone descarregado<br>- Perda de conexão com a internet<br> |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<br>

## Cenário 18: Bloqueio/Reativação/Solicitação de Reparo

<center>
Tabela 13: Bloqueio/Reativação/Solicitação de Reparo

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | Permitir **bloqueio, reativação ou solicitação de reparo nos serviços da Caesb**             |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia ou a noite<br> - **Pré-condições**: Acesso ao aplicativo e conta ativa. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone, internet                                                                           |
| **Episódios**      | 1. O usuário acessa o aplicativo.<br> 2. O sistema exibe a opção de serviços.<br> 3. O usuário escolhe a ação desejada (bloqueio, reativação ou reparo).<br> 4. O sistema solicita informações adicionais.<br> 5. O usuário fornece as informações e confirma a ação. |
| **Restrições**     | - O usuário deve ter uma conta ativa para solicitar bloqueio ou reativação.                    |
| **Exceção**        | - Dados inválidos.<br> - Serviço não disponível.<br> - Perda de conexão com a internet durante o processo. |

</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a>
</center>

---

## Cenário 19: Correção de Erros

<center>
Tabela 14: Correção de Erros

| **Item**           | **Descrição**                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------|
| **Objetivo**       | Permitir **a correção de erros retornando à tela anterior e atualizando os dados**             |
| **Contexto**       | - **Local**: Em casa<br> - **Tempo**: Durante o dia ou a noite<br> - **Pré-condições**: Acesso ao aplicativo e conta ativa. |
| **Atores**         | Usuário                                                                                         |
| **Recursos**       | Smartphone, internet                                                                           |
| **Episódios**      | 1. O usuário acessa o aplicativo.<br> 2. O sistema exibe a tela atual com dados incorretos.<br> 3. O usuário clica na opção de voltar.<br> 4. O sistema retorna à tela anterior.<br> 5. O usuário atualiza os dados e confirma. |
| **Restrições**     | - O usuário deve ter uma conta ativa.                                                         |
| **Exceção**        | - Dados inválidos.<br> - Perda de conexão com a internet durante o processo.                  |

</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a>
</center>

## Bibliografia

> <p id="1"> 1. Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021)
Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.</p>

<br>

## Histórico de versão

<center>

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :-----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 06/12/2024 | Criação dos cenários | [Leandro de Almeida](https://github.com/leomitx10) |[Natan Almeida](https://github.com/natanalmeida03) |
|  1.1   | 10/12/2024 | Adicionando cenários | [Letícia Resende](https://github.com/LeticiaResende23) |[Leandro de Almeida](https://github.com/leomitx10) |
|  1.2   | 11/12/2024 | Adicionando cenários | [Natan Almeida](https://github.com/natanalmeida03) |[Leandro de Almeida](https://github.com/leomitx10) |
|  1.3   | 15/12/2024 | Adicionando cenários | [Matheus Barros](https://github.com/Ninja-Haiyai) |[Leandro de Almeida](https://github.com/leomitx10) |

</center>