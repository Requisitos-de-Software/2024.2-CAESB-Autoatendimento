# Moscow
## Introdução
<p align="justify">&emsp;&emsp;Após a coleta de vários requisitos por meio de métodos como introspecção, análise documental e observação, torna-se essencial aplicar técnicas que permitam definir a prioridade desses requisitos, avaliando a relevância de cada um. Assim, nesta seção, a abordagem adotada para a priorização dos requisitos é o Moscow.</p>

## Metodologia

O método MoSCoW é uma abordagem para priorizar requisitos, auxiliando a equipe de desenvolvimento a tomar decisões de maneira mais eficiente. Ele organiza os requisitos em quatro categorias principais:

- M (Must-Have): Itens indispensáveis que o projeto precisa incluir.
- S (Should-Have): Requisitos importantes, mas que não são essenciais para a entrega inicial.
- C (Could-Have): Funcionalidades desejáveis que podem ser incluídas se houver recursos e tempo disponíveis.
- W (Won't-Have ou Would/Won't): Elementos que não serão implementados na versão atual, mas podem ser considerados no futuro.

## Must-Have
<p align="justify">&emsp;&emsp;A categoria Must-Have abrange as tarefas essenciais para a conclusão do projeto, que devem ser tratadas como prioridade máxima. Esses itens possuem um impacto significativo no produto e agregam valor crucial, sendo indispensáveis para evitar problemas que poderiam comprometer a experiência do cliente. As demandas classificadas como Must-Have são as mais urgentes e requerem atenção imediata da equipe.</p>


## Should-Have
<p <p align="justify">&emsp;&emsp;A categoria Should-Have inclui tarefas relevantes para o projeto, mas que não são tão cruciais quanto as classificadas como Must-Have. Embora sejam importantes, sua ausência não inviabiliza o andamento do projeto.</p>

## Could-Have
<p align="justify">&emsp;&emsp;A categoria Could-Have abrange tarefas de menor importância em comparação com as do grupo Should-Have. Esses requisitos adicionam valor ao projeto, mas sua falta não compromete de forma significativa sua execução.</p>

## Would/Want/Won't-Have
<p align="justify">&emsp;&emsp;A categoria Would/Want/Won't-Have reúne tarefas de baixa relevância para o projeto. A inclusão ou exclusão desses itens não impacta de maneira relevante o sucesso do projeto.</p>

## Requisitos
A Tabela 1 a seguir contém a priorização dos Requisitos elicitados. Nem todos os requisitos estão presentes na tabela pois diferentes métodos elicitaram requisitos semelhantes.

### Legenda:
 - INT: Requisitos de Introspecção
 - ADD:  Requisitos da Análise de Documento
 - OBS: Requisitos da Observação

<center>
<figcaption>Tabela 01 - Requisitos </figcaption>

| ID  | DESCRIÇÃO                                                             | CATEGORIA |
| :-: | :-------------------------------------------------------------------: | :-------: |
| INT01| O aplicativo deve permitir ao usuário informar vazamentos na rua ou no hidrômetro ||
| INT02| O usuário deve poder emitir boleto para pagar a conta de água.        |       |
| INT03| O aplicativo deve permitir consulta ao histórico de consumo mensal.   |       |
| INT04| O usuário deve poder atualizar seus dados cadastrais pelo app.        |       |
| INT05| O aplicativo deve enviar notificações de vencimento de faturas.       |       |
| INT06| O aplicativo deve permitir que o usuário informe falta d'Água.        |       |
| INT07| O aplicativo deve ser compatível com as versões mais recentes do Android e iOS. ||
| INT08| O aplicativo deve ter uma interface intuitiva e fácil de usar.        ||
| INT09| O sistema deve ser capaz de suportar muitos usuários simultâneos.     ||
| INT10| O aplicativo deve ser otimizado para diferentes tamanhos de tela e dispositivos (responsivo). ||
| INT11 | O aplicativo deve permitir ao usuário solicitar segunda via de faturas.  |       |
| INT12 | O usuário deve poder consultar e pagar débitos anteriores.               |       |
| INT13 | O aplicativo deve disponibilizar a opção de cadastro em débito automático.|       |
| INT14 | O usuário deve poder consultar o mapa de interrupções de fornecimento.   |       |
| INT15 | O aplicativo deve permitir agendar atendimento presencial na unidade mais próxima. |       |
| INT16 | O aplicativo deve exibir dicas de consumo consciente e economia de água. |       |
| INT17 | O usuário deve poder registrar e acompanhar ordens de serviço.           |       |
| INT18 | O aplicativo deve disponibilizar alertas sobre manutenção programada.    |       |
| INT19 | O usuário deve poder solicitar alteração na titularidade da conta.       |       |
| INT20 | O aplicativo deve permitir o envio de documentos para atualização cadastral. |       |
| INT21 | O sistema deve garantir a segurança dos dados do usuário, com criptografia de ponta a ponta. ||
| INT22 | O aplicativo deve ter tempos de resposta inferiores a 2 segundos para a maioria das funcionalidades. ||
| INT23 | O aplicativo deve estar disponível para download em lojas oficiais como Google Play e App Store. ||
| INT24 | O sistema deve possuir integração com serviços de pagamento populares como Pix e cartões de crédito. ||
| INT25 | O aplicativo deve estar disponível em português, inglês e espanhol.      ||
| INT26 | O design do aplicativo deve seguir as diretrizes de acessibilidade (WCAG 2.1). ||
| INT27 | O sistema deve enviar e-mails e SMS transacionais para confirmar ações como pagamentos e atualizações cadastrais. ||
| INT28 | O aplicativo deve ser modular, facilitando atualizações e novas implementações. ||
| INT29 | O aplicativo deve possuir suporte técnico acessível via chat ou e-mail.  ||
| ADD01| Permitir a revisão de contas diretamente pelo aplicativo. ||
| ADD02| Possibilitar a alteração de titularidade e vencimento de contas.      |       |
| ADD03| O aplicativo deve permitir que o usuário realize a auto leitura do hidrômetro. |       |
| ADD04| O aplicativo deve permitir que o usuário relate vazamentos de água    |       |
| ADD05| O aplicativo deve permitir que o usuário solicite desobstrução de esgoto e acompanhe os atendimentos.    |       |
| ADD06| O aplicativo deve permitir o acesso ao histórico detalhado de consumo e faturas anteriores.   |       |
| ADD07| O usuário deve poder enviar documentos diretamente pelo aplicativo. ||
| ADD08| O aplicativo deve oferecer notificações para lembrar vencimento de contas e ações pendentes.    ||
| ADD09| O aplicativo deve incluir suporte a chat ou atendimento virtual para resolver dúvidas dos usuários.   ||
| ADD10| O aplicativo deve ser compatível com sistemas operacionais Android e iOS.||
| ADD11| O aplicativo deve garantir uma interface do usuário acessível e fácil de navegar.||
| ADD12| O aplicativo deve oferecer suporte a múltiplos idiomas para atender usuários diversificados.||
| ADD13| O aplicativo deve ser eficiente em dispositivos com recursos limitados.||
| ADD14| O aplicativo deve minimizar riscos de vulnerabilidades e proteger contra ataques conhecidos.||
| ADD15| O aplicativo deve evitar riscos relacionados à violação de privacidade e coleta invasiva de dados dos usuários.||
| ADD16| O aplicativo deve permitir a realização de testes para validar a funcionalidade de revisão de contas e alterações.||
| ADD17| O aplicativo deve ser testado para garantir uma navegação intuitiva e acessível a todos os usuários.||
| ADD18| O aplicativo deve passar por testes de desempenho para assegurar eficiência em dispositivos diversos.||
| ADD19| O aplicativo deve ser testado para evitar vulnerabilidades e proteger os dados dos usuários.||
| ADD20| O aplicativo deve garantir que os dados dos usuários sejam tratados com respeito à privacidade.||
| ADD21| O aplicativo deve incluir um tutorial inicial para ajudar novos usuários a se familiarizarem.||
| ADD22| O usuário deve poder personalizar notificações de acordo com suas preferências.||
| ADD23| O aplicativo deve permitir que o usuário emita segundas vias de contas e comprovantes.||
| ADD24| O aplicativo deve implementar autenticação multifator para aumentar a segurança do acesso.||
| ADD25| O usuário deve poder localizar postos de atendimento da CAESB no mapa.||
| ADD26| O aplicativo deve permitir que o usuário realize pagamentos de contas diretamente pelo aplicativo.||
| ADD27| O aplicativo deve exibir informações em tempo real sobre interrupções no fornecimento de água.||
| ADD28| O aplicativo deve estar em conformidade com padrões de acessibilidade, como WCAG.||
| ADD29| O aplicativo deve oferecer estatísticas de consumo mensal para ajudar o usuário a monitorar o uso de água.||
| ADD30| O aplicativo deve permitir suporte offline para funcionalidades básicas, como visualização de contas armazenadas.||
| OBS1   | O aplicativo deve permitir que o usuário escolha o imóvel desejado.                           |     |
| OBS2   | O aplicativo deve permitir que o usuário selecione o ano ou mês da segunda via da conta.             |     |
| OBS3   | O aplicativo deve permitir que o usuário escolha vizualizar a segunda via de contas pendentes. |   |
| OBS4   | O aplicativo deve reconhecer automaticamente os imóveis associados ao cliente da Caesb.       |     |
| OBS5   | O aplicativo deve considerar o número de pessoas no imóvel para calcular a média do consumo.  |     |
| OBS6   | O aplicativo deve permitir que o usuário visualize as regiões em que haverá falta de água.    |     |
| OBS7   | O aplicativo deve permitir que o usuário informe o vazamento em uma rua.                      |     |
| OBS8   | O aplicativo não deve permitir que o usuário escolha rua, bairro e cidade para informar o vazamento em uma rua. |  |
| OBS9   | O aplicativo deve permitir filtrar os atendimentos em andamento ou finalizados.           |      |
| OBS10  | O aplicativo deve permitir filtrar os atendimentos por ano ou mês.                        |      |
| OBS11  | O aplicativo deve permitir que o usuário busque um atendimento pelo protocolo.                |     |
| OBS12  | O aplicativo deve permitir que o usuário simule o faturamento pelo aplicativo.            |      |
| OBS13  | O aplicativo deve permitir que o usuário altere o vencimento da conta.                        |     |
| OBS14  | O aplicativo deve permitir que o usuário altere a titularidade da conta.                      |     |
| OBS15  | O aplicativo deve possuir 2 abas separadas, uma para serviços e outra para consultas.         |      |

</center>
<br>

## Histórico de Versão

| Versão |    Data    |      Descrição       |       Autor(es)       |     Revisor(es)     |
| :-----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 21/11/2024 | Criação do artefato |[Letícia Resende](https://github.com/LeticiaResende23) | [Natan Almeida](https://github.com/natanalmeida03)  |