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


## Acessibilidade

<center><p>Tabela 1: Acessibilidade para pessoas com deficiência visual</p> 

| **Categoria**         | **Descrição**                                                                                     | **Requisito** |
|------------------------|---------------------------------------------------------------------------------------------------|---------------|
| Acessibilidade         | O aplicativo deve ser acessível para pessoas com deficiência visual, seguindo a WCAG versão 2.1, nível AA. | OBS18         |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a></center> 

<br>

<center><p>Tabela 2: Design do aplicativo</p> 

| **Categoria**         | **Descrição**                                                                                     | **Requisito** |
|------------------------|---------------------------------------------------------------------------------------------------|---------------|
| Acessibilidade         | O design do aplicativo deve seguir as diretrizes de acessibilidade da Versão 8.4.1 da WCAG.      | ADD13         |

</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a></center> 

<br>

## Usabilidade
<p>Refere-se ao quão fácil é para o usuário realizar uma tarefa no aplicativo.</p>

<center><p>Tabela 3: O aplicativo deve ser responsivo</p>  

| **Categoria**         | **Descrição**                                                                                     | **Requisito** |
|------------------------|---------------------------------------------------------------------------------------------------|---------------|
| Adaptação de Tela      | O aplicativo deve ser responsivo, adaptando-se a diferentes tamanhos de tela e dispositivos móveis. | OBS17         |
| Interface intuitiva e organizada      | O aplicativo deve ter uma interface intuitiva, organizada e fácil de usar. | INT08         |
| Minimização do número de cliques      | O sistema deve minimizar o número de cliques necessários para interações. | B14         |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>, <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a></center>

<br>

<center><p>Tabela 4: O aplicativo deve separar serviços de consultas</p>  

| **Categoria**         | **Descrição**                                                                                     | **Requisito** |
|------------------------|---------------------------------------------------------------------------------------------------|---------------|
| Organização de Tela      | A interface visual deve ser reorganizada, separando serviços e consultas. | ENT10 |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a></center>

<br>

<center><p>Tabela 5: Tarefas em até 3 cliques e Interface acessível e fácil de navegar</p>  

| **Categoria**           | **Descrição**                                                                                   | **Requisito** |
|--------------------------|-----------------------------------------------------------------------------------------------|---------------|
| Fluxos Simplificados     | O aplicativo deve permitir que o usuário realize tarefas principais em no máximo 3 cliques.    | OBS19         |
| Navegação Simples        | O aplicativo deve garantir uma interface do usuário acessível e fácil de navegar.              | ADD22         |

</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a></center> 

<br>

## Disponibilidade
<center><p>Tabela 6: O aplicativo deve estar disponível para download </p>

| **Categoria**         | **Descrição**                                                                                     | **Requisito** |
|------------------------|---------------------------------------------------------------------------------------------------|---------------|
| Disponibilidade        | O aplicativo deve estar disponível para download em lojas oficiais como Google Play e App Store. | INT23         |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a></center>

<br>

<center><p>Tabela 7: Suporte offline para funções básicas </p>

| **Categoria**         | **Descrição**                                                                                     | **Requisito** |
|------------------------|---------------------------------------------------------------------------------------------------|---------------|
| Suporte Offline        | O aplicativo deve permitir suporte offline para funcionalidades básicas, como visualização de contas armazenadas. | ADD14         |

</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a></center> 

<br>

## Desempenho
<p> Refere-se a performace do aplicativo.</p>

<center><p>Tabela 8: Resposta ao banco em menos de 2 segundos e Otimizado para todos os dispositivos. </p>

| **Categoria**         | **Descrição**                                                                                     | **Requisito** |
|------------------------|---------------------------------------------------------------------------------------------------|---------------|
| Tempo de Resposta      | O tempo de resposta para qualquer consulta ao banco de dados deve ser inferior a 2 segundos.      | INT22         |
| Responsividade         | O aplicativo deve ser otimizado para diferentes tamanhos de tela e dispositivos.                 | INT10         |

</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a></center> 

<br>

## Suportabilidade
<p>  Refere-se ao suporte e manutenção do aplicativo.</p>

<center><p>Tabela 9: Compatível com Android e iOS atuais. </p>

| **Categoria**               | **Descrição**                                                                             | **Requisito** |
|------------------------------|-------------------------------------------------------------------------------------------|---------------|
| Compatibilidade Multi-Plataforma | O aplicativo deve ser compatível com a última versão dos sistemas operacionais Android e iOS. | ADD21         |


</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a></center> 

<br>

## +
<p>Refere-se a outros tipos de requisitos como design, implementação, interface e físicos.</p>

<center><p>Tabela 10: Dicas de consumo consciente e Design simples e moderno.</p>

| **Categoria**               | **Descrição**                                                                             | **Requisito** |
|------------------------------|-------------------------------------------------------------------------------------------|---------------|
| Sustentabilidade             | O aplicativo deve exibir dicas de consumo consciente e economia de água.                 | INT16         |
| Design Limpo e Moderno       | O design do aplicativo deve ser simples, com uma interface limpa e moderna.              | B13           |

</p>Autor(a): <a href="https://github.com/natanalmeida03" target = "_blank">Natan Almeida</a></center> 

## Confiabiliade
<p> Refere-se a garantias de segurança no sistema.</p>

<center><p>Tabela 11: Segurança com criptografia de ponta a ponta e autenticação multifator</p>

| **Categoria**               | **Descrição**                                                                             | **Requisito** |
|------------------------------|------------------------------------------------------------------------------------------|---------------|
| Segurança | O aplicativo deve garantir a segurança dos dados do usuário, com criptografia de ponta a ponta              |      INT21    |
| Segurança | O aplicativo deve implementar autenticação multifator para aumentar a segurança do acesso.                  |      ADD27    |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a></center> 
<br>

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
|  1.6   | 10/12/2024 | Adicionando especificações  | [Letícia Resende](https://github.com/LeticiaResende23) |[Natan Almeida](https://github.com/natanalmeida03) |
|  1.7   | 11/12/2024 | Adicionando especificações  | [Leandro de Almeida](https://github.com/leomitx10) |[Natan Almeida](https://github.com/natanalmeida03) |
|  1.8   | 15/01/2025 | Adicionando especificações  | [Joao Victor Marques](https://github.com/jmarquees) |[Letícia Resende](https://github.com/LeticiaResende23) |