# Histórias de Usuários

## Introdução

<p align="justify">&emsp;&emsp;Uma história de usuário é uma descrição breve e simples de uma funcionalidade do sistema, escrita do ponto de vista do usuário. Usada em métodos ágeis de desenvolvimento, ela foca no valor de negócio para o cliente e representa uma pequena parte da funcionalidade, sem ser uma especificação detalhada. Isso reduz a necessidade de uma documentação extensa.</p>

## Metodologia  

<p align="justify">&emsp;&emsp;Para a produção desse artefato, foram realizadas duas entrevistas diferentes com dois usuários distintos, ambos desempenhando o papel de POs (Product Owners) do projeto.</p>

<p align="justify">&emsp;&emsp;Durante as entrevistas, cada PO descreveu as funcionalidades desejadas para o projeto. Enquanto isso, os desenvolvedores, atuando como entrevistadores, anotavam as informações e faziam questionamentos para esclarecer pontos específicos.</p>

<p align="justify">&emsp;&emsp;Após a elicitação das histórias de usuário, foram definidos os critérios de aceitação para cada uma delas. Posteriormente, as histórias foram priorizadas pelos POs com base em quatro categorias: Must-Have, Should-Have, Could-Have e Won't-Have. Esse processo utilizou o método <a href="https://requisitos-de-software.github.io/2024.2-CAESB-Autoatendimento/priorizacao/moscow/" target ="_blank">Moscow</a> de priorização de requisitos.</p>

<center>Tabela 1: Participantes entrevista 1

| Participante   | Função          | Local         | Data       |
|----------------|-----------------|---------------|------------|
| João Silva     | Desenvolvedor   |   Gama - DF   | 12/12/2024 |
| Maria Oliveira | Desenvolvedor   |   Gama - DF   | 15/12/2024 |
| Pedro Santos   | Product Owner   |   Gama - DF   | 10/12/2024 |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<center>
    <p>Vídeo 01: Entrevista com o PO</p>
    <iframe width="760" height="515" src="https://www.youtube.com/embed/SpG8wJ3lwyc?si=RsvRbrSLw68c4YGw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a></h6>
</center>

<center>Tabela 2: Participantes entrevista 2

| Participante   | Função          | Local         | Data       |
|----------------|-----------------|---------------|------------|
| João Silva     | Desenvolvedor   |   Gama - DF   | 12/12/2024 |
| Maria Oliveira | Desenvolvedor   |   Gama - DF   | 15/12/2024 |
| Maria Eduarda  | Desenvolvedor   |   Gama - DF   | 15/12/2024 |
| Pedro Santos   | Product Owner   |   Gama - DF   | 10/12/2024 |

</p>Autor(a): <a href="https://github.com/leomitx10" target = "_blank">Leandro de Almeida</a>
</center>

<center>
    <p>Vídeo 02: Entrevista com o PO</p>
    <iframe width="760" height="515" src="https://www.youtube.com/embed/SpG8wJ3lwyc?si=RsvRbrSLw68c4YGw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    Autor(a): <a href="https://github.com/jmarquees" target = "_blank">Joao Victor Marques</a></h6>
</center>

## Histórias de Usuário

<center>Tabela 3: Barra de Busca

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US01              | O sistema deve ter uma barra de busca.   |
|     Descrição          | Eu, como usuário, desejo que o aplicativo tenha uma barra de busca para facilitar a localização de eventos específicos pelo nome ou palavra-chave. |
| Critérios de Aceitação | - Na página principal do aplicativo, deve haver uma barra de busca visível no topo ou em local destacado.<br>- Ao digitar na barra de busca, os eventos listados devem ser filtrados em tempo real para corresponder aos termos inseridos.<br> - A busca deve suportar diferentes critérios, como nome do evento e palavras-chave. |
|     Prioridade         | Alta |
|     Rastreabilidade    | RQ01 |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>
<br>
<center>Tabela 4: Registrar e acompanhar ordens de serviço

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US02              | O usuário deve poder registrar e acompanhar ordens de serviço.   |
|     Descrição          | Eu, como usuário, desejo registrar e acompanhar ordens de serviço para gerenciar eficientemente as atividades relacionadas. |
| Critérios de Aceitação | - Deve haver uma opção clara no aplicativo para registrar uma nova ordem de serviço, incluindo campos como descrição, prioridade, data, e responsável.<br> - O sistema deve permitir visualizar uma lista de ordens de serviço registradas, com informações básicas (ex.: título, status, prioridade).<br> - Deve ser possível atualizar o status de uma ordem de serviço (ex.: Pendente, Em Progresso, Concluído).<br> - O usuário deve poder filtrar ou buscar ordens de serviço com base em critérios como status ou prioridade. |
|     Prioridade         | Alta |
|     Rastreabilidade    | RQ23 |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>
<br>
<center>Tabela 5: Conformidade com os padrões de acessibilidade da WCAG

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US03              | 	O aplicativo deve estar em conformidade com os padrões de acessibilidade da WCAG.   |
|     Descrição          | Eu, como usuário, desejo que o aplicativo esteja em conformidade com os padrões de acessibilidade da última versão da WCAG, para garantir que ele possa ser utilizado por pessoas com diferentes tipos de deficiência. |
| Critérios de Aceitação | - Todos os elementos de interface devem ser compatíveis com leitores de tela e navegáveis por teclado.<br> - As cores, contrastes, e tamanhos de fontes devem atender aos requisitos mínimos estabelecidos pela WCAG.<br> - Deve haver suporte a textos alternativos para imagens e elementos gráficos não textuais.<br> - O sistema deve evitar elementos que possam causar problemas para pessoas com fotosensibilidade, como animações rápidas ou piscantes.<br> - Deve haver testes realizados para validar conformidade com a última versão da WCAG antes da entrega do produto. |
|     Prioridade         | Alta |
|     Rastreabilidade    | RQ35 |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>
<br>
<center>Tabela 6: Buscar atendimento pelo protocolo


|       ID               |      Nome       | 
|------------------------|-----------------|
|      US04              | 	O aplicativo deve permitir que o usuário busque um atendimento pelo protocolo.   |
|     Descrição          | Eu, como usuário, desejo buscar um atendimento pelo protocolo para acompanhar rapidamente o status de uma solicitação específica. |
| Critérios de Aceitação | - Deve haver um campo de busca na interface do aplicativo, onde o usuário possa inserir o número do protocolo.<br> - Após digitar o protocolo e confirmar a busca, o sistema deve exibir os detalhes do atendimento correspondente, como status, data de registro, e descrição.<br> - Caso o protocolo não seja encontrado, o sistema deve informar ao usuário que não há registros correspondentes.<br> - A busca pelo protocolo deve ser rápida, com retorno dos resultados em até 5 segundos. |
|     Prioridade         | Alta |
|     Rastreabilidade    | REQ30 |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>
<br>
<center>Tabela 7: Alterar vencimento de conta


|       ID               |      Nome       | 
|------------------------|-----------------|
|      US05              | 		O aplicativo deve permitir que o usuário altere o vencimento da conta.   |
|     Descrição          | Eu, como usuário, desejo alterar a data de vencimento da minha conta para adequá-la às minhas necessidades financeiras e evitar atrasos no pagamento. |
| Critérios de Aceitação | - Deve haver uma opção na interface do aplicativo para alterar a data de vencimento da conta, localizada de forma clara e acessível.<br> - O sistema deve permitir que o usuário selecione uma nova data dentro de um intervalo permitido (ex.: do dia 1 ao dia 28 de cada mês).<br> - Após a alteração, o sistema deve confirmar a mudança e informar ao usuário a nova data de vencimento.<br> - Caso a alteração não seja possível (ex.: devido a restrições de contrato), o sistema deve apresentar uma mensagem explicativa ao usuário. |
|     Prioridade         | Média |
|     Rastreabilidade    | REQ29 |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>
<br>
<center>Tabela 8: Descrições de serviços

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US06              | O sistema deve exibir pequenas descrições ao lado dos serviços para mostrar seu estado atual.   |
|     Descrição          | Eu, como usuário, desejo visualizar pequenas descrições ao lado dos serviços para entender rapidamente o estado atual de cada um. |
| Critérios de Aceitação | - O sistema deve exibir uma breve descrição ou rótulo ao lado de cada serviço listado, indicando claramente seu estado atual (ex.: "Em Andamento", "Concluído", "Pendente").<br> - As descrições devem ser dinâmicas e atualizadas automaticamente quando o estado do serviço for alterado.<br> - As informações exibidas devem ser concisas, com no máximo 2-3 palavras para evitar poluição visual.<br> - O design deve ser responsivo, garantindo que as descrições sejam legíveis em dispositivos móveis e telas menores. |
|     Prioridade         | Média |
|     Rastreabilidade    | REQ07 |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>
<br>
<center>Tabela 9: Adiantamento de processos via aplicativo

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US07              |  	O sistema deve possibilitar o adiantamento de processos via aplicativo.   |
|     Descrição          | Eu, como usuário, desejo poder adiantar processos diretamente pelo aplicativo para reduzir o tempo de espera e agilizar os procedimentos. |
| Critérios de Aceitação | - Deve haver uma opção no aplicativo que permita ao usuário solicitar o adiantamento de um processo, visível em locais relevantes (ex.: detalhes do processo).<br> - O sistema deve apresentar as condições e requisitos para que o adiantamento seja possível, como taxas ou documentos necessários.<br> - Após solicitar o adiantamento, o usuário deve receber uma confirmação com o novo status e um prazo atualizado.<br> - Caso o adiantamento não seja possível, o sistema deve informar os motivos e sugerir alternativas (se aplicável).|
|     Prioridade         | Média |
|     Rastreabilidade    | REQ10 |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

<center>Tabela 10: Filtrar atendimentos por ano, mês e status

|       ID               |      Nome       | 
|------------------------|-----------------|
|      US08              | A funcionalidade "Atendimentos" deve permitir filtros por ano, mês e status |
|     Descrição          | Eu, como usuário, desejo filtrar os atendimentos por ano, mês e status (finalizado ou em andamento) para localizar rapidamente os registros relevantes. |
| Critérios de Aceitação | - Deve haver opções de filtro claras e acessíveis na funcionalidade "Atendimentos".<br> - O sistema deve permitir selecionar um ou mais dos seguintes critérios de filtro: ano, mês e status (finalizado ou em andamento).<br> - Após aplicar os filtros, a lista de atendimentos exibida deve ser atualizada automaticamente para mostrar apenas os registros correspondentes.<br> - O sistema deve permitir combinar filtros (ex.: filtrar por ano e status ao mesmo tempo).<br> - Deve haver uma opção para limpar os filtros aplicados e retornar à lista completa de atendimentos. |
|     Prioridade         | Média |
|     Rastreabilidade    | REQ17 |

</p>Autor(a): <a href="https://github.com/LeticiaResende23" target = "_blank">Letícia Resende</a>
</center>

<br>

## Histórico de versão

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :-----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 13/12/2024 | Criação da introdução e metodologia| [Leandro de Almeida](https://github.com/leomitx10) |[Natan Almeida](https://github.com/natanalmeida03) |