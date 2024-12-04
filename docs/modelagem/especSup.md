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
<p align="justify">&emsp;&emsp;Os requisitos funcionais estão contidos no [caso de uso](link_caso_uso).</p>

### Usabilidade
<p align="justify">&emsp;&emsp;Refere-se ao quão fácil é para o usuário realizar uma tarefa no aplicativo.</p>
<br>

#### 1. Orientações claras:
Orientações claras em cada funcionalidade com mensagens de ajuda contextuais.

#### 2. Fluxos Simplificados:
Redução no número de etapas para concluir tarefas comuns, como consultar faturas ou solicitar serviços.

#### 3. Consistência de Navegação:
Layout padronizado em todas as telas para evitar confusões

### Confiabiliade
<p align="justify">&emsp;&emsp;Refere-se a garantias de segurança no sistema.</p>
<br>

#### 1. Garantia de disponibilidade:
O sistema deve funcionar 24hrs por dia e sete dias na semana.

#### 2. Proteção de dados:
O sistema deve proteger os dados do usuário à ataques.

### Desempenho
<p align="justify">&emsp;&emsp;Refere-se a performace do aplicativo</p>
<br>

#### 1. Tempo de resposta:
Especifica o tempo máximo permitido para o sistema responder a uma requisição.

#### 2. Escalabilidade:
A capacidade do sistema de manter ou melhorar o desempenho à medida que o número de usuários e o volume de dados aumenta.

#### 3. Crescimento de dados:
Define como o sistema deve se comportar quando o volume de dados cresce significativamente.

### Suportabilidade
<p align="justify">&emsp;&emsp;Refere-se ao suporte e manutenção do aplicativo.</p>
<br>

#### 1. Compatibilidade multi-plataforma:
Garantia de suporte para as versões mais recentes dos sistemas operacionais (Android e iOS).

#### 2. Escalabilidade:
Planejamento para suportar aumento no número de usuários sem comprometer a performance.

### +
<p align="justify">&emsp;&emsp;Refere-se a outros tipos de requisitos como design, implementação, interface e físicos</p>
<br>

## Referências
> <p style="word-wrap: break-word; overflow-wrap: break-word;">Especificacao Suplementar. Disponível em: https://aprender3.unb.br/pluginfile.php/2972491/mod_resource/content/2/SiglaProjeto_EspecificacaoSuplementar.pdf .Acesso em: 03 dec. 2024.</p> 

## Histórico de versão

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :-----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 02/12/2024 | Criação do artefato | [Natan Almeida](https://github.com/natanalmeida03) | [Joao Victor Marques](https://github.com/jmarquees) |
|  1.1   | 03/12/2024 | Adição de requisitos | [Natan Almeida](https://github.com/natanalmeida03) | [Joao Victor Marques](https://github.com/jmarquees) |
|  1.2   | 04/12/2024 | Adição de requisitos | [Joao Victor Marques](https://github.com/jmarquees) | [Natan Almeida](https://github.com/natanalmeida03) |