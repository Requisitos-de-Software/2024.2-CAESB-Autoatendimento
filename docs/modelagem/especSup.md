# Especificação Suplementar

## Introdução 
<p align="justify">&emsp;&emsp;A especificação suplementar tem o propósito de identificar requisitos do sistema que não foram detalhados na modelagem dos casos de uso. Assim, ao combiná-las, é possível abranger todos os requisitos necessários para o sistema.</p>

Este método possui os seguintes critérios:

```
- funcionalidade
- usabilidade
- confiabilidade
- desempenho 
- suportabilidade
```

## Metodologia
<p align="justify">&emsp;&emsp;O modelo adotado para este artefato é o FURPS+, uma metodologia que organiza os requisitos de um sistema em cinco pilares principais, mencionados anteriormente:</p>

- **F** - _Functionality_: abrange os aspectos funcionais do sistema, descritos nos casos de uso.  
- **U** - _Usability_: refere-se à facilidade de uso do software para atender às demandas do usuário.  
- **R** - _Reliability_: trata da confiabilidade com a qual o software foi projetado.  
- **P** - _Performance_: avalia o desempenho do sistema.  
- **S** - _Supportability_: reúne requisitos como manutenibilidade, adaptabilidade, internacionalização, portabilidade, entre outros aspectos relevantes.  
- **+**: simboliza outros requisitos não funcionais que não se enquadram nos pilares mencionados, como design, implementação, interface e aspectos físicos.

## Especificação Suplementar
### Funcionalidade
<p align="justify">&emsp;&emsp;Os requisitos funcionais estão contidos no <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/modelagem/caso_uso/">Caso de Uso </a>.</p>

### Usabilidade
<p align="justify">&emsp;&emsp;Refere-se ao quão fácil é para o usuário realizar uma tarefa no aplicativo.</p>
<br>

#### 1. Acessibilidade:
O design do aplicativo deve seguir as diretrizes de acessibilidade da Versão 8.4.1 da WCAG. <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD13</a>

#### 2. Fluxos Simplificados:
O aplicativo deve permitir que o usuário realize tarefas principais em no máximo 3 cliques. <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/observacao/#requisitos">OBS19</a>

#### 3. Navegação Simples:
O aplicativo deve garantir uma interface do usuário acessível e fácil de navegar. <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD22</a>

### Confiabiliade
<p align="justify">&emsp;&emsp;Refere-se a garantias de segurança no sistema.</p>
<br>

#### 1. Suporte Offline:
O aplicativo deve permitir suporte offline para funcionalidades básicas, como visualização de contas armazenadas.
<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD14</a>

### Desempenho
<p align="justify">&emsp;&emsp;Refere-se a performace do aplicativo</p>
<br>

#### 1. Tempo de resposta:
O tempo de resposta para qualquer consulta ao banco de dados deve ser inferior a 2 segundos.
<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT22</a>

#### 2. Responsividade
O aplicativo deve ser otimizado para diferentes tamanhos de tela e dispositivos (responsivo).
<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT10</a>


### Suportabilidade
<p align="justify">&emsp;&emsp;Refere-se ao suporte e manutenção do aplicativo.</p>
<br>

#### 1. Compatibilidade multi-plataforma:
O aplicativo deve ser compatível com a última versão dos sistemas operacionais Android e iOS.
<a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/analise_documento/#requisitos">ADD21</a>

### +
<p align="justify">&emsp;&emsp;Refere-se a outros tipos de requisitos como design, implementação, interface e físicos</p>
<br>

#### 1. Sustentabilidade:
O aplicativo deve exibir dicas de consumo consciente e economia de água. <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/introspeccao/#requisitos">INT16</a>

#### 2. Design limpo e moderno:
O design do aplicativo deve ser simples, com uma interface limpa e moderna. <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/elicitacao/tecnicas/Brainstorm/#requisitos">B13</a>


## Referências
> <p style="word-wrap: break-word; overflow-wrap: break-word;">Especificacao Suplementar. Disponível em: https://aprender3.unb.br/pluginfile.php/2972491/mod_resource/content/2/SiglaProjeto_EspecificacaoSuplementar.pdf .Acesso em: 03 dec. 2024.</p> 

## Histórico de versão

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :-----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 02/12/2024 | Criação do artefato | [Natan Almeida](https://github.com/natanalmeida03) | [Joao Victor Marques](https://github.com/jmarquees) |
|  1.1   | 03/12/2024 | Adição de requisitos | [Natan Almeida](https://github.com/natanalmeida03) | [Joao Victor Marques](https://github.com/jmarquees) |
|  1.2   | 04/12/2024 | Adição de requisito Desempenho | [Joao Victor Marques](https://github.com/jmarquees) | [Natan Almeida](https://github.com/natanalmeida03) |
|  1.3   | 04/12/2024 | Adição de requisito Integração | [Joao Victor Marques](https://github.com/jmarquees) | [Natan Almeida](https://github.com/natanalmeida03) |
|  1.4   | 04/12/2024 | Adição e remoção de requisitos | [Joao Victor Marques](https://github.com/jmarquees) | [Natan Almeida](https://github.com/natanalmeida03) |
|  1.5   | 10/12/2024 | Atualização pós apresentação  | [Natan Almeida](https://github.com/natanalmeida03) | [Joao Victor Marques](https://github.com/jmarquees) |