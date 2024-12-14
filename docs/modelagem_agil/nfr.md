# NFR Framework

## Introdução

<p align="justify">&emsp;&emsp;O Framework de Requisitos Não Funcionais (NFR) é um método estruturado para lidar com requisitos não funcionais no desenvolvimento de software. Foi criado com o objetivo de auxiliar engenheiros e analistas de sistemas na identificação, representação, análise e monitoramento da satisfação de requisitos não funcionais (como desempenho, segurança, confiabilidade, manutenibilidade, entre outros) ao longo da vida útil do software.</p>

## Metodologia  

<p align="justify">&emsp;&emsp;Para que este documento possa ser produzido, foram utilizados os requisitos não funcionais presentes no nosso projeto e elicitados no artefato de <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados.md/">de requisitos elicitados</a>, que trata dos requisitos elicitados em relação ao  aplicativo <a href="https://play.google.com/store/apps/details?id=br.gov.df.caesb.mobile&hl=pt_BR">Caesb Autoatendimento</a>.</p>

<p align="justify">&emsp;&emsp;Esse framework leva em consideração o conceito de "softgoal", eles se referem a um objeto desprovido de definição clara e critérios de satisfação sólidos, esses softgoals são utilizados para representar Requisitos não-funcionais e podem estar conectados entre si, refletindo as influências que eles exercem entre si.</p>


<p align="justify">&emsp;&emsp; Existem três categorias de softgoals, abaixo segue (Tabela 1)  uma explicação sobre cada tipo:</p>

<center>Tabela 1: Tipos de Softgoals

| **Tipo de Softgoal**         | **Descrição**                                                                                                                                 |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| **Softgoals NFR**            | Representam os requisitos não funcionais e podem ser organizados hierarquicamente no desenvolvimento do projeto.                           |
| **Softgoals de Operacionalização** | Representam as soluções de implementação para atender aos softgoals NFR ou outros softgoals de operacionalização. Incluem operações, processos, estruturas de dados e restrições no sistema para cumprir as necessidades indicadas. |
| **Softgoals de Afirmação ( CLAIM )**   | Consideram as características do domínio, como prioridades e carga de trabalho, no processo de tomada de decisão. Servem como justificativa para apoiar ou negar a priorização e seleção de componentes, facilitando a revisão, justificativa, melhoria do sistema e rastreamento das decisões de desenvolvimento. |

</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target = "_blank">Matheus Barros</a>
</center>

<br>

<center> Figura 1: Tipos de Softgoals

![alt text](../assets/softgoals/tipos.png)

<p> Autor: (CHUNG et al., 2000). </p>

</center>
<br>

<p align="justify">&emsp;&emsp;Após determinarmos o tipo de softgoal, devemos fazer uma avaliação, esse processo de avaliação determina o quanto os requisitos não funcionais são satisfatórios por meio de um conjunto de decisões. Para tal atribuimos os rótulos de "satisfeito", "parcialmente satisfeito", "não atendido", "parcialmente não atendido", "conflitante" e "indeterminado"</p>

<br>

<center> Figura 2: Rótulos de propagação de impacto

![alt text](../assets/softgoals/propagaçao_impacto.png)

<p> Autor: (CHUNG et al., 2000). </p>

</center>

<p align="justify">&emsp;&emsp; Depois de fazermos a identificação deles e relacionarmos devemos atribuir a eles as contribuições e decomposições, que serão explicadas na Tabela 2: </p>

<center> Tabela 2: Tipos de contribuições e decomposições

| **Tipo de Contribuição**           | **Descrição**                                                                                          |
|------------------------------------|------------------------------------------------------------------------------------------------------|
| **Contribuições Positivas (`+`)**  | Indicadores de que uma decisão ou elemento contribui para a satisfação de um softgoal.               |
| **`++` (Forte Positiva)**          | Uma contribuição muito significativa e positiva.                                                    |
| **`+` (Fraca Positiva)**           | Uma contribuição positiva moderada.                                                                 |
| **Contribuições Negativas (`-`)**  | Indicadores de que uma decisão ou elemento dificulta a satisfação de um softgoal.                   |
| **`--` (Forte Negativa)**          | Um impacto muito significativo e prejudicial.                                                      |
| **`-` (Fraca Negativa)**           | Um impacto negativo moderado.                                                                       |
| **Decomposição AND**               | Todos os sub-softgoals precisam ser atendidos para que o softgoal pai seja satisfeito.              |
| **Decomposição OR**                | Apenas um ou mais sub-softgoals precisam ser atendidos para que o softgoal pai seja satisfeito.     |

</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target = "_blank">Matheus Barros</a>
</center>

<br>


## Requisitos Não-Funcionais:
<center>
<figcaption>Tabela 03 - Requisitos Não Funcionais (RNF) utilizados para elabaoração do documento, retirado do artefato <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/requisitos_elicitados.md/">de requisitos elicitados</a> :</figcaption>

|  ID  |                      DESCRIÇÃO                       |                 RASTREABILIDADE                  | IMPLEMENTADO |
| :--: | :--------------------------------------------------: | :----------------------------------------------: | :----------: |
| **RQ31** | O aplicativo deve incluir um tutorial inicial para ajudar novos usuários a se familiarizarem.| <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD10</a> | Não |
| **RQ32** | O aplicativo deve oferecer suporte a múltiplos idiomas para atender usuários diversificados. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD04</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT25</a> | Não |
| **RQ33** | O aplicativo deve ser compatível com as versões mais recentes do Android e iOS. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT07</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS16</a> | Sim |
| **RQ34** | O aplicativo deve garantir segurança com os dados dos usuários. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD06</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD07</a> | Sim |
| **RQ35** | O aplicativo deve estar em conformidade com os padrões de acessibilidade da última versão da WCAG. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD13</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT26</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS18</a> | Não |
| **RQ36** | O aplicativo deve ter uma interface intuitiva, organizada e fácil de usar. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT08</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT02</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B15</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B13</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/entrevista/">ENT10</a> | Sim |
| **RQ37** | O sistema deve minimizar o número de cliques necessários para interações. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/">B14</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS19</a> | Sim |
| **RQ38** | O aplicativo deve se adaptar a diferentes tamanhos de tela. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/">OBS17</a>, <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT10</a> | Não |
| **RQ39** | O aplicativo deve permitir suporte offline para funcionalidades básicas, como visualização de contas armazenadas. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/">ADD14</a> | Não | NAO |
| **RQ40** | O aplicativo deve ter tempos de resposta inferiores a 2 segundos para a maioria das funcionalidades. | <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/">INT22</a> | Não |

</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target = "_blank">Matheus Barros</a>
</center>


## NFR Framework - NFR01: Usabilidade
<p align="justify">&emsp;&emsp; De acordo com Jakob Nielsen usabilidade é um atributo de qualidade que avalia a facilidade de uso das interfaces de usuário. Nielsen define usabilidade como um conjunto de componentes que determinam o quão eficaz, eficiente e satisfatória é a interação do usuário com um sistema. Os requisitos utilizdos para esse NFR foram: </p>

- RQ31: O aplicativo deve incluir um tutorial inicial para ajudar novos usuários a se familiarizarem.
- RQ32: O aplicativo deve oferecer suporte a múltiplos idiomas para atender usuários diversificados.
- RQ36: O aplicativo deve ter uma interface intuitiva, organizada e fácil de usar.
- RQ38: O aplicativo deve se adaptar a diferentes tamanhos de tela.

<p align = "justify" >Com isso em mente, segue a Figura número 3 com o NFR relativo a usabilidade:</p>

<center> FIgura 3: SIG usabilidade

![alt text](../assets/softgoals/nfr_usabilidade.jpg)

</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target = "_blank">Matheus Barros</a>

</center>

### Propagação de impactos - NFR01

<center> Tabela 04: Propagação de impactos NF01

|          NFR                          |         Impacto           |              Avaliador               |
| :-----------------------------------: | :-----------------------: | :----------------------------------: |
| Usabilidade                          | ✓ (satisfeito)           | <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a> |
| Interface intuitiva                 | ✓ (satisfeito)           | <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a> |
| Tutorial                             | 𝒲+ (fracamente satisfeito) | <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a> |
| Adaptar a diferentes tamanhos de tela| ✓ (satisfeito)           | <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a> |
| Interface padronizada                | ✓ (satisfeito)           | <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a> |
| Funcionalidades fáceis de encontrar   | 𝒲+ (fracamente satisfeito) | <a href="https://github.com/Ninja-Haiyai" target="_blank">Matheus Barros</a> |
</p>Autor(a): <a href="https://github.com/Ninja-Haiyai" target = "_blank">Matheus Barros</a>
</center>

## Referências

> <p id="1">[1] Chung, Lawrence; A. Nixon, Brian; Mylopoulos, John. Non-Functional Requirements in Software Engineering. Acesso em 13 de Dezembro de 2024.</p>
> <p id="2">[2] SILVA, R. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Tese (Mestrado em Engenharia de Software) - Centro de Informática, Universidade Federal de Pernambuco. Recife, p. 155. 2019. Acesso em: 13 de Dezembro de 2022
> <p id="3"> [3]NIELSEN, Jakob. Usability Engineering. San Francisco: Morgan Kaufmann, 1994.

</p>

## Histórico de versão

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :-----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 13/12/2024 | Criação da introdução, metodologia e NFR de usabilidade| [Matheus Barros](https://github.com/Ninja-Haiyai) |[Natan Almeida](https://github.com/natanalmeida03) |