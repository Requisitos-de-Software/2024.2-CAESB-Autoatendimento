# Léxicos

## Introdução
<p align="justify">&emsp;&emsp;Na modelagem de requisitos, o léxico é uma notação empregada para detalhar termos específicos de um campo, com a finalidade de reconhecer e registrar os símbolos pertinentes de uma língua em um contexto social ou técnico. Cada termo no léxico é examinado sob duas perspectivas fundamentais: conceito e efeito. A noção diz respeito ao sentido objetivo do termo, isto é, o que ele simboliza no âmbito. Por outro lado, o impacto descreve o efeito ou resultado prático que o termo causa ao ser aplicado ou realizado no ambiente em análise. Esta estratégia promove a compreensão conjunta entre os envolvidos e contribui para a construção de um alicerce robusto para a formulação e avaliação de requisitos.</p>

## Metodologia
<p align="justify">&emsp;&emsp;Os léxicos que foram elaborados nesse documento foram identificados com a utilização do aplicativo e dos requisitos que já foram elicitados em documentos anteriores</p>

<center><p> Tabela 1: Modelo do Léxico</p></center>

| **Tipo do Símbolo** | **Noção**                                        | **Impacto**                                                                      |
|----------------------|--------------------------------------------------|----------------------------------------------------------------------------------|
| Sujeito             | Quem é o sujeito                                 | Ações que executa                                                               |
| Verbo               | Quem realiza, quando acontece e quais os procedimentos | Quais os reflexos das ações no ambiente e novos estados decorrentes             |
| Objeto              | Definir o objeto e identificar outros objetos com os quais ele se relaciona | Ações que podem ser aplicadas ao objeto                                         |
| Estado              | O que indica e ações que levaram a esse estado   | Identificar outros estados que podem ocorrer a partir do estado que se descreve |


<center>Fonte: SAYÃO e CARVALHO </center>
<br>

<center><p> Tabela 2: Classificações do Léxico</p></center>

<center>

| **ID**            | **Descrição**                          |
|--------------------|----------------------------------------|
| **Classificação**  | Estado, Objeto ou Verbo               |
| **Impacto**        | Descrição de suas consequências e impactos  |
| **Noção**          | Símbolo                               |
| **Dicionário**     | Sinônimos ou termos alternativos      |

</center>

<center>Autor(a): <a href="https://github.com/Ninja-Haiyai" target = "_blank">Matheus Barros</a> </center>



## L01: Pagar a conta
<p align="justify">&emsp;&emsp; Léxico referente ao fato de pagar uma conta, requisito que foi elicitado atráves do Brainstorming (B10) e da Instrospecção(INT02)  </p>

<center><p> Tabela 3: Léxico 01: Pagar conta (L01)</p></center>

| **ID**            | **Descrição**                          |
|--------------------|----------------------------------------|
| **Classificação**  | Verbo                                 |
| **Impacto**        | A conta foi paga. O cliente não tem mais pendências. |
| **Noção**          | Tarefa realizada pelo usuário. Acontece quando o cliente quer pagar uma conta. Ele verifica as opções de pagamento, coloca seus dados e efetua a operação. |
| **Dicionário**     | Pagamento, quitar conta               |
<center>Autor(a): <a href="https://github.com/Ninja-Haiyai" target = "_blank">Matheus Barros</a> </center>

## L02: Atendentes da Caesb
<p align="justify">&emsp;&emsp; Léxico referente aos funcionários que prestam serviços para a Caesb, requisito que foi elicitado atráves da introspecção (INT15) e da análise de documento (ADD28)  </p>

<center><p> Tabela 3: Léxico 02: Atendente da Caesb (L02)</p></center>

| **ID**            | **Descrição**                                                                            |
|--------------------|------------------------------------------------------------------------------------------|
| **Classificação**  | Objeto                                                                                  |
| **Impacto**        | Realiza as tarefas: verifica pendências, passa informações e recebe os pagamentos.      |
| **Noção**          | Pessoa que trabalha no estabelecimento onde é computado o pagamento da Caesb e auxilia em atendimentos que não puderam ser feitos remotamente.          |
|                    | Responsável pela comunicação entre cliente, caixa e empresa.                                    |
| **Dicionário**     | Atendentes, funcionários da Caesb                                                      |
<center>Autor(a): <a href="https://github.com/Ninja-Haiyai" target = "_blank">Matheus Barros</a> </center>

## L03: Emitir segunda via
<p align="justify">&emsp;&emsp; Léxico referente a consulta de contas que já foram pagas , requisito que foi elicitado atráves da Brainstorm (B03), Entrevista (Q15) e da análise de documento (ADD20)  </p>

<center><p> Tabela 3: Léxico 03: Verificar Recibo (L02)</p></center>

| **ID**            | **Descrição**                                                                           |
|--------------------|-----------------------------------------------------------------------------------------|
| **Classificação**  | Estado                                                                                 |
| **Impacto**        | Enquanto está com a conta paga, durante aquele período não deve mais nada e pode emitir a segunda via           |
| **Noção**          | Aquele cliente está com as pendências livres. . |
| **Dicionário**     | Quitado, conta resolvida, conta paga                                                               |

<center>Autor(a): <a href="https://github.com/Ninja-Haiyai" target = "_blank">Matheus Barros</a> </center>

## L04: Usuário
<p align="justify">&emsp;&emsp;O Léxico a seguir diz respeito à interação do aplicativo com o usuário, fundamentada nos requisitos definidos na Análise de Documento (ADD02) e na Introspecção (INT02). Esses critérios envolvem a exigência de que o aplicativo forneça notificações para alertar os usuários sobre o término das contas. Contudo, vale destacar que essas funcionalidades ainda não foram incorporadas à aplicação. Adicionalmente, as necessidades de filtragem de dados, identificadas durante a entrevista (ENT07) e na observação (OBS09 e OBS10), também não foram implementadas. </p>

<center><p> Tabela 4: Léxico 04: Usuário (L02)</p></center>

<center>

| **ID**            | **Descrição**                                                                           |
|--------------------|-----------------------------------------------------------------------------------------|
| **Classificação**  | Objeto                                                                                |
| **Impacto**        |  O usuário pode decidir receber ou não as notificações (ADD02 e INT02)              
|                    |  O usuário pode filtrar a busca por data, horário e categoria (L01). |
|                    |  O usuário pode acessar o histórico de contas                                        |
| **Noção**          | Aquele cliente está com as pendências livres e está ciente das próximas cobranças                                         |
| **Dicionário**     | Quitado, conta resolvida, conta paga                                                   |
</center>


<center>Autor(a): <a href="https://github.com/Ninja-Haiyai" target = "_blank">Matheus Barros</a> </center>


## Referências
> <p id="1">1. SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf. Acesso em: 03/12/2024.
</p>

><p id= '2'> 2. SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf/. Acesso em: 14/05/2023.<p>

<br>

## Histórico de Versão
<center>

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :-----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 20/11/2024 | Criação do Léxico  | [Matheus Barros](https://github.com/Ninja-Haiyai)|[Leandro de Almeida](https://github.com/leomitx10) |

</center>
