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

<center> <figcaption>Imagem 1: Apresenta o elemento que representa os atores.</figcaption></center>
<center>
<img src="https://github.com/user-attachments/assets/593648c5-62d3-4fb1-81cd-39a4230d6ecf"></img>
 </p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
 </center>

<br>

## Cenário
<p align="justify">&emsp;&emsp;Neste elemento, são descritos os eventos que ocorrem quando um usuário interage com o sistema. Normalmente, é representado por uma caixa.</p>

<p align="justify">&emsp;&emsp;Todos os casos de uso que o sistema descrito devem ser incluídos neste cenário; caso contrário, serão considerados fora do escopo do sistema.</p>

<center> <figcaption>Imagem 2: Apresenta o elemento que representa os cenários.</figcaption>
<img src="https://github.com/user-attachments/assets/4773f2c8-40dd-4296-81b6-dcc25b529bdb"></img>
 </p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a></center>

<br>

## Casos de uso
<p align="justify">&emsp;&emsp;O caso de uso é uma ação ou funcionalidade realizada pelo usuário, o ator. Normalmente, é representado por um objeto oval horizontal, sendo que cada representação corresponde a uma interação distinta que o usuário pode ter com o sistema. Para se referir às ações realizadas, é comum usar verbos no infinitivo para descrevê-las.</p>

<center> <figcaption>Imagem 3: Apresenta o elemento que representa os casos de uso.</figcaption>
<img src="https://github.com/user-attachments/assets/bbc415ec-a831-4518-b7f4-248823a94e24"></img>
 </p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a></center>

<br>

## Comunicação (ou ação)
Consiste em uma ação que o usuário realizará sobre o caso de uso, conforme ilustrado na imagem 4. A ação pode ser de dois tipos:

Inclusão: Quando a funcionalidade de um caso de uso precisa ser realizada por meio de outro caso de uso. Em outras palavras, um caso de uso A inclui o caso de uso B, de forma que, ao executar o caso de uso A, o caso de uso B será automaticamente executado junto.

 - Notação no diagrama : <>

Extensão: O caso de uso atual será executado normalmente, mas alguns casos de uso podem adicionar etapas extras no caso de uso estendido. Ou seja, se o caso de uso A estende o caso de uso B, ao executar o caso de uso A, o caso de uso B poderá ou não ser executado também.

 - Notação no diagrama : <<>>

 <center> <figcaption>Imagem 4: Apresenta o elemento que representa a comunicação.</figcaption>
<img src="https://github.com/user-attachments/assets/aa3de9ad-ebd8-4926-87f9-92d9f1ac5ebc"></img>
 </p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a></center>

 <br>

## Casos de Uso

<p align="justify">&emsp;&emsp;Os principais casos de uso, mais relevantes e frequentemente utilizados no aplicativo, estão ilustrados na imagem 5. Para uma visualização mais detalhada da imagem, consulte os casos de uso na Caesb Autoatendimento.</p>

 <center> <figcaption>Imagem 5: Apresenta o diagrama de casos de uso do aplicativo da Caesb Autoatendimento.</figcaption>
<img src="https://github.com/user-attachments/assets/941c6c58-cd59-4280-ac82-c5f0f67141f6"></img>
</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a></center>

<br>


## Especialização dos casos de uso

As tabelas de 1 a 9 mostram a especialização dos casos de uso.

<center>
<font size="3"><p style="text-align: center">Tabela 1: Visualizar Segunda Via de Conta </p></font>

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
| Rastreabilidade | [OBS3](http://127.0.0.1:8000/priorizacao/tec_In/#legenda) |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 2: Informar Falta d'Água </p></font>

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
| Rastreabilidade | [INT06](http://127.0.0.1:8000/priorizacao/tec_In/#legenda) |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 3: Realizar Auto Leitura do Hidrômetro </p></font>

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
| Rastreabilidade | [ADD03](http://127.0.0.1:8000/priorizacao/tec_In/#legenda) |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 4: Informar Vazamento </p></font>

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
| Rastreabilidade | [INT01](http://127.0.0.1:8000/priorizacao/tec_In/#legenda) |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 5: Consultor Histórico de Consumo </p></font>

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
| Rastreabilidade | [INT03](http://127.0.0.1:8000/priorizacao/tec_In/#legenda) |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 6: Alterar Titularidade e Vencimento </p></font>

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
| Rastreabilidade | [ADD02](http://127.0.0.1:8000/priorizacao/tec_In/#legenda) |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 7: Agenda Atendimento Presencial </p></font>

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
| Rastreabilidade | [INT15](http://127.0.0.1:8000/priorizacao/tec_In/#legenda) |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>
<font size="3"><p style="text-align: center">Tabela 8: Suporte de Chat ou Atendimento </p></font>

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
| Rastreabilidade | [ADD09](http://127.0.0.1:8000/priorizacao/tec_In/#legenda) |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>


<center>
<font size="3"><p style="text-align: center">Tabela 9: Notificações de Vencimento </p></font>

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
| Rastreabilidade | [ADD08](http://127.0.0.1:8000/priorizacao/tec_In/#legenda) |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
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

