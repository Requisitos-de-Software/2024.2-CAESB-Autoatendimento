# First Things First

## Introdução
<p align="justify">&emsp;&emsp;Após a coleta de vários requisitos por meio de métodos como introspecção, análise documental e observação, torna-se essencial aplicar técnicas que permitam definir a prioridade desses requisitos, avaliando a relevância de cada um. Assim, nesta seção, a abordagem adotada para a priorização dos requisitos é a técnica First Things First.</p>

## Metodologia

<p align="justify">&emsp;&emsp;A técnica de priorização chamada "First Things First" baseia-se na coleta de informações sobre os benefícios, custos e riscos associados a cada requisito. Com esses dados, define-se uma sequência de prioridades para sua implementação. Assim como a técnica MoSCoW, seu objetivo é organizar os requisitos em uma lista de prioridades.</p>

<p align="justify">&emsp;&emsp;Para utilizá-la, é necessário montar uma tabela que contenha detalhes sobre os riscos, custos, benefícios e penalidades de cada requisito. Cada um desses critérios deve ser avaliado e pontuado em uma escala de 1 a 9, buscando um equilíbrio entre as perspectivas do cliente e do desenvolvedor. É importante listar todos os requisitos na tabela, determinar os valores relativos de benefício e penalidade para cada um, somar esses valores, e, em seguida, estimar o custo e o grau de risco relacionados. Com essas informações, calcula-se a prioridade de cada requisito. A lista final deve ser organizada em ordem decrescente, partindo dos itens mais prioritários.</p>


## Requisitos
A Figura 1 a seguir contém a priorização dos Requisitos elicitados. Nem todos os requisitos estão presentes na tabela pois diferentes métodos elicitaram requisitos semelhantes.

## Legenda:
 - INT: Requisitos de Introspecção
 - ADD:  Requisitos da Análise de Documento
 - OBS: Requisitos da Observação

<br>
<center>
<figcaption>Tabela 01 - Priorização dos requisitos utilizando método First Things First
 </figcaption>

| Requisito | Benefício Relativo | Penalidade Relativa | Valor Total | Valor (%) | Custo Relativo | Custo (%) | Risco Relativo | Risco (%) | Prioridade |
|-----------|---------------------|---------------------|-------------|-----------|----------------|-----------|----------------|-----------|------------|
| ADD01     | 9                   | 8                   | 17          | 4.91      | 4              | 2.34      | 3              | 2.14      | 2.43       |
| ADD26     | 9                   | 9                   | 18          | 5.20      | 5              | 2.92      | 3              | 2.14      | 2.25       |
| ADD05     | 8                   | 7                   | 15          | 4.34      | 4              | 2.34      | 3              | 2.14      | 2.14       |
| INT13     | 8                   | 8                   | 16          | 4.62      | 5              | 2.92      | 3              | 2.14      | 2.00       |
| ADD14     | 9                   | 9                   | 18          | 5.20      | 6              | 3.51      | 4              | 2.86      | 1.80       |
| ADD09     | 7                   | 7                   | 14          | 4.05      | 5              | 2.92      | 3              | 2.14      | 1.75       |
| INT06     | 7                   | 6                   | 13          | 3.76      | 5              | 2.92      | 3              | 2.14      | 1.63       |
| INT15     | 6                   | 6                   | 12          | 3.47      | 4              | 2.34      | 3              | 2.14      | 1.50       |
| ADD23     | 7                   | 5                   | 12          | 3.47      | 5              | 2.92      | 4              | 2.86      | 1.33       |
| ADD03     | 6                   | 5                   | 11          | 3.19      | 5              | 2.92      | 4              | 2.86      | 1.22       |
| INT11     | 6                   | 5                   | 11          | 3.19      | 5              | 2.92      | 4              | 2.86      | 1.22       |
| ADD29     | 7                   | 5                   | 12          | 3.47      | 6              | 3.51      | 4              | 2.86      | 1.20       |
| INT21     | 9                   | 9                   | 18          | 5.20      | 7              | 4.10      | 6              | 4.29      | 1.15       |
| ADD06     | 6                   | 5                   | 11          | 3.19      | 5              | 2.92      | 5              | 3.57      | 1.10       |
| INT03     | 6                   | 4                   | 10          | 2.89      | 5              | 2.92      | 5              | 3.57      | 1.00       |
| ADD04     | 6                   | 4                   | 10          | 2.89      | 5              | 2.92      | 5              | 3.57      | 1.00       |
| ADD27     | 7                   | 4                   | 11          | 3.19      | 6              | 3.51      | 5              | 3.57      | 0.96       |
| INT16     | 6                   | 4                   | 10          | 2.89      | 5              | 2.92      | 5              | 3.57      | 0.91       |
| INT01     | 6                   | 4                   | 10          | 2.89      | 6              | 3.51      | 4              | 2.86      | 0.91       |
| ADD08     | 6                   | 4                   | 10          | 2.89      | 6              | 3.51      | 5              | 3.57      | 0.83       |
| INT17     | 5                   | 4                   | 9           | 2.60      | 6              | 3.51      | 5              | 3.57      | 0.79       |
| INT14     | 5                   | 4                   | 9           | 2.60      | 6              | 3.51      | 5              | 3.57      | 0.79       |
| ADD22     | 5                   | 4                   | 9           | 2.60      | 6              | 3.51      | 5              | 3.57      | 0.79       |
| INT22     | 5                   | 5                   | 10          | 2.89      | 7              | 4.10      | 6              | 4.29      | 0.72       |
| INT24     | 5                   | 5                   | 10          | 2.89      | 7              | 4.10      | 6              | 4.29      | 0.72       |
| ADD12     | 5                   | 4                   | 9           | 2.60      | 7              | 4.10      | 6              | 4.29      | 0.68       |
| INT19     | 4                   | 4                   | 8           | 2.31      | 6              | 3.51      | 6              | 4.29      | 0.62       |
| ADD13     | 5                   | 4                   | 9           | 2.60      | 8              | 4.68      | 6              | 4.29      | 0.60       |
| ADD07     | 4                   | 3                   | 7           | 2.02      | 6              | 3.51      | 6              | 4.29      | 0.54       |
| ADD02     | 2                   | 4                   | 6           | 1.73      | 8              | 4.68      | 8              | 5.71      | 0.38       |

Autor(a): <a href="https://github.com/LeticiaResende233" target = "_blank">Letícia Resende</a>
</center>

<br>

## Link da gravação
Pode ser vista no <a href="https://www.youtube.com/watch?v=9oeguWDZlk4" target="_blank">YouTube</a>.
<center>
<p>Vídeo 01: Gravação da entrevista de priorização</p>
<iframe width="760" height="515" src="https://www.youtube.com/embed/V7UapC74zJw?si=lsAxrWglnbdzl-r5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<h6>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a></h6>
</center>

<br>


<center>

<figcaption>Tabela 02 - Dados da Entrevista</figcaption>

| **Entrevistador**     | **Entrevistado**        | **Duração** |
| :-------------------: |:----------------------: |-------------|
| Letícia Resende | Sue Ellen Suzana |     05min 35segundos       |


Autor(a): <a href="https://github.com/LeticiaResende233" target = "_blank">Letícia Resende</a>
</center>

<br>

## Referências

> <p>1. MILENE, Profa.; MAURÍCIO, Prof. Elicitação de requisitos: técnicas - priorização. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972449/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>
Acesso em: 23 nov. 2024.</P>
>  <p> 2. https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/priorizacao/firstThingsfirst/
Acesso em: 23 nov. 2024.</p>

<br>

## Histórico de Versão

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :-----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 21/11/2024 | Criação do artefato |[Letícia Resende](https://github.com/LeticiaResende23) | [Natan Almeida](https://github.com/natanalmeida03)  |
|  1.1   | 23/11/2024 | Adicionando priorização |[Letícia Resende](https://github.com/LeticiaResende23) | [Natan Almeida](https://github.com/natanalmeida03)  |
|  1.2  | 23/11/2024 | Adicionando vídeo |[Letícia Resende](https://github.com/LeticiaResende23) | [Leandro de Almeida](https://github.com/leomitx10)  |