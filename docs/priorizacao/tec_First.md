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
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD01</a>     | 9                   | 8                   | 17          | 4.91      | 4              | 2.34      | 3              | 2.14      | 2.43       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD26</a>    | 9                   | 9                   | 18          | 5.20      | 5              | 2.92      | 3              | 2.14      | 2.25       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD05</a>     | 8                   | 7                   | 15          | 4.34      | 4              | 2.34      | 3              | 2.14      | 2.14       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT13</a>     | 8                   | 8                   | 16          | 4.62      | 5              | 2.92      | 3              | 2.14      | 2.00       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD14</a>    | 9                   | 9                   | 18          | 5.20      | 6              | 3.51      | 4              | 2.86      | 1.80       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD09</a>  | 7                   | 7                   | 14          | 4.05      | 5              | 2.92      | 3              | 2.14      | 1.75       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT06</a>      | 7                   | 6                   | 13          | 3.76      | 5              | 2.92      | 3              | 2.14      | 1.63       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT15</a>      | 6                   | 6                   | 12          | 3.47      | 4              | 2.34      | 3              | 2.14      | 1.50       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD23</a>     | 7                   | 5                   | 12          | 3.47      | 5              | 2.92      | 4              | 2.86      | 1.33       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD03</a>     | 6                   | 5                   | 11          | 3.19      | 5              | 2.92      | 4              | 2.86      | 1.22       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT11</a>      | 6                   | 5                   | 11          | 3.19      | 5              | 2.92      | 4              | 2.86      | 1.22       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD29</a>    | 7                   | 5                   | 12          | 3.47      | 6              | 3.51      | 4              | 2.86      | 1.20       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT21</a>     | 9                   | 9                   | 18          | 5.20      | 7              | 4.10      | 6              | 4.29      | 1.15       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD06</a>    | 6                   | 5                   | 11          | 3.19      | 5              | 2.92      | 5              | 3.57      | 1.10       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT03</a>    | 6                   | 4                   | 10          | 2.89      | 5              | 2.92      | 5              | 3.57      | 1.00       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD04</a>    | 6                   | 4                   | 10          | 2.89      | 5              | 2.92      | 5              | 3.57      | 1.00       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD27</a>    | 7                   | 4                   | 11          | 3.19      | 6              | 3.51      | 5              | 3.57      | 0.96       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT16</a>      | 6                   | 4                   | 10          | 2.89      | 5              | 2.92      | 5              | 3.57      | 0.91       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT01</a>      | 6                   | 4                   | 10          | 2.89      | 6              | 3.51      | 4              | 2.86      | 0.91       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD08</a>    | 6                   | 4                   | 10          | 2.89      | 6              | 3.51      | 5              | 3.57      | 0.83       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT17</a>     | 5                   | 4                   | 9           | 2.60      | 6              | 3.51      | 5              | 3.57      | 0.79       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT14</a>     | 5                   | 4                   | 9           | 2.60      | 6              | 3.51      | 5              | 3.57      | 0.79       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD22</a>    | 5                   | 4                   | 9           | 2.60      | 6              | 3.51      | 5              | 3.57      | 0.79       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT22</a>     | 5                   | 5                   | 10          | 2.89      | 7              | 4.10      | 6              | 4.29      | 0.72       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT24</a>     | 5                   | 5                   | 10          | 2.89      | 7              | 4.10      | 6              | 4.29      | 0.72       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD12</a>    | 5                   | 4                   | 9           | 2.60      | 7              | 4.10      | 6              | 4.29      | 0.68       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT19</a>     | 4                   | 4                   | 8           | 2.31      | 6              | 3.51      | 6              | 4.29      | 0.62       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD13</a>   | 5                   | 4                   | 9           | 2.60      | 8              | 4.68      | 6              | 4.29      | 0.60       |
|<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD07</a>    | 4                   | 3                   | 7           | 2.02      | 6              | 3.51      | 6              | 4.29      | 0.54       |
| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD02</a>    | 2                   | 4                   | 6           | 1.73      | 8              | 4.68      | 8              | 5.71      | 0.38       |

Autor(a): <a href="https://github.com/LeticiaResende233" target = "_blank">Letícia Resende</a>
</center>

<br>

## Link da gravação
Pode ser vista no <a href="https://www.youtube.com/watch?v=9oeguWDZlk4" target="_blank">YouTube</a>.
<center>
<p>Vídeo 01: Gravação da entrevista de priorização</p>
<iframe width="760" height="515" src="https://www.youtube.com/embed/V7UapC74zJw?si=lsAxrWglnbdzl-r5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>


<center>

<figcaption>Tabela 02 - Dados da Entrevista</figcaption>


| **Entrevistador** | **Entrevistado** | **Duração** | **Local**                   |Horário| **Data** |
|-------------------|------------------|-------------|-----------------------------|---|-----------|
| Letícia Resende | Sue Ellen   |   5min    |    Casa do entrevistado     | 18:20 | 23/11/2024|


Autor(a): <a href="https://github.com/LeticiaResende233" target = "_blank">Letícia Resende</a>
</center>

<br>

## Referências Bibliográficas

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
|  1.3   | 26/11/2024 | Adicionando cronograma |[Letícia Resende](https://github.com/LeticiaResende23) | [Natan Almeida](https://github.com/natanalmeida03)  |
|  1.4  | 05/02/2025 | correção pós apresentação |[Letícia Resende](https://github.com/LeticiaResende23) | [Leandro de Almeida](https://github.com/leomitx10)  |
