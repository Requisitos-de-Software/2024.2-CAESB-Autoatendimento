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
| **Exceção**        | - Smartphone descarregado<br>- Perda de conexão com a internet<br>- Falha na entrega da notificação                                  |

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

## Bibliografia

> <p id="1"> 1. Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021)
Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.</p>

<br>

## Histórico de versão

<center>

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :-----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 06/12/2024 | Criação dos cenários | [Leandro de Almeida](https://github.com/leomitx10) |[Natan Almeida](https://github.com/natanalmeida03) |

</center>