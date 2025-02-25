# Especificações do Projeto
## Personas

| Nome: Lucas                           | Idade: 19 anos                   | Persona 1                             |
| ------------------------------------- | -------------------------------- | ------------------------------------- |
|![Persona Lucas](img/Lucas.jpeg)| Ocupação: Estudante  | Aplicativos: TikTok, WhatsApp, YouTube, Instagram, SnapChat |
| Motivações:                           | Frustrações:                     | Hobbies:                              |
| Lucas é um estudante universitário que compartilha um apartamento com três colegas de quarto. Ele costuma fazer diversas festas. | Com uma grande festa se aproximando, os amigos de Lucas percebem que a coordenação das compras está ficando complicada. | Escutar Músicas. |


| Nome: Maria | Idade: 40 anos | Persona 2 |
| ----------- | -------------- | --------- |
| ![Persona Maria](img/Maria.jpg)| Ocupação: Faxineira | Aplicativos: WhatsApp, YouTube, Facebook. |
| Motivações: | Frustrações: | Hobbies: |
| Maria é uma mãe ocupada com três filhos e um marido que trabalha em tempo integral. Ela está constantemente fazendo compras para a casa. | Ela nota que às vezes compra coisas que já foram compradas por outros membros da família. | Sair com os filhos e marido para jantar fora. |


| Nome: Ana                          | Idade: 30 anos                 | Persona 3                  |
| ---------------------------------- | ------------------------------ | --------------------------- |
| ![Persona Ana](img/Ana.jpg)| Ocupação: Tech Lead           | Aplicativos: WhatsApp, YouTube, Facebook, Instagram, Teams |
| Motivações:                        | Frustrações:                   | Hobbies:                   |
| Ana é a líder de uma equipe de projeto em uma empresa de tecnologia. Responsável por organizar as comemorações para a sua equipe. | Ela frequentemente precisa da ajuda de todos para definir o que será levado por cada um, mas não consegue compartilhar isso de uma maneira fácil. | Tocar guitarra |

| Nome: Carlos | Idade: 25 anos | Persona 4 |
| ------------ | -------------- | --------- |
|![Persona Carlos](img/Carlos.jpg) | Ocupação: Atleta | Aplicativos: WhatsApp, YouTube, Facebook, Instagram |
| Motivações: | Frustrações: | Hobbies: |
| Carlos é um atleta amador e segue uma dieta específica. Ele precisa se certificar de que tem os alimentos certos em casa para atender às suas necessidades nutricionais. | Muitas vezes encontra dificuldades em se comunicar sobre o que precisa ser comprado, com seus familiares. | Ler livros de aventura. |


## Histórias de Usuários

Registramos as narrativas das personas identificadas no projeto e realizamos uma análise aprofundada de suas histórias.

| EU COMO...  PERSONA | QUERO/PRECISO ... FUNCIONALIDADE                                                                                                                          | PARA ... MOTIVO/VALOR                                                                                                                                                                  |
|:-------------------:| --------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Lucas               | Possiblidade de criar uma lista eficiente e rápida para as compras das festas que faço.                                                                   | À medida que a festa se aproxima, o tempo é essencial. A capacidade de criar uma lista rapidamente permite que o grupo de amigos se concentre em outros aspectos importantes da festa. |
| Maria               | Ter uma lista compartilhada com marcação para os itens que já foram comprados.                                                                            | A marcação dos itens já comprados pelos ouros membros da família assegura que nenhum item seja adquirido duas vezes, economizando dinheiro e evitando o excesso de estoque.            |
| Ana                 | A possibilidade de compartilhar a lista de compras com todos os colegas de trabalho e permitir que eles adicionem, apaguem e editem os itens necessários. | A inclusão de todos os colegas ajuda a maximizar os recursos disponíveis, assegurando que todas as necessidades sejam atendidas de maneira eficaz.                                     |
| Carlos              | Compartilhamento de uma lista de compras que atualiza em tempo real.                                                                                      | O compartilhamento em tempo real permite saber quais itens são necessários no momento exato. Isso simplifica a coordenação das compras com meus familiares.                            |


## Modelagem do Processo de Negócio 

### Análise da Situação Atual

O método manual de criação de listas de compras é um dos mais tradicionais e simples. Nele, as pessoas escrevem os itens que precisam comprar em papel, bloco de notas ou até mesmo em um quadro de avisos na cozinha. Cada membro da família anota manualmente o que percebe que está faltando.

Alguns usam apps de mensagens, como WhatsApp, para compartilhar listas. Os itens são discutidos e adicionados às conversas, podendo ser marcados quando comprados.

No entanto, o método manual tem suas limitações. Itens devem ser escritos um a um, e a lista pode não ser atualizada em tempo real, podendo levar a esquecimentos. Compartilhar a lista com quem não está presente pode ser difícil. Além disso, papéis e blocos de notas podem ser perdidos ou danificados, causando perda de informação.

No caso de bate-papos, a lista pode se tornar desorganizada com o tempo, à medida que mais itens são adicionados. Apps de mensagens não são projetados especificamente para gerenciar lista de compras, o que pode levar a uma experiência menos eficiente.

### Descrição Geral da Proposta

A proposta busca modernizar e otimizar a coordenação de compras em grupos e famílias. Através de uma abordagem digital, os membros podem compartilhar e atualizar a lista em tempo real, evitando duplicações e desorganização. Isso estimula a colaboração e simplifica o processo de compras, com acesso conveniente por dispositivos móveis ou web. Além disso, ela supera as limitações dos métodos tradicionais, como listas manuais em papel ou desorganização em apps de mensagens.

<!--
### Processo 1 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 1. Em seguida, apresente o modelo do processo 1, descrito no padrão BPMN. 

![Processo 1](img/02-bpmn-proc1.png)

### Processo 2 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 2. Em seguida, apresente o modelo do processo 2, descrito no padrão BPMN.

![Processo 2](img/02-bpmn-proc2.png)
-->

### Processo 1 - Criação do Login

![criacao do login](image.png)

### Processo 2 - Criação de uma lista compartilhada

![cricao de lista](image-1.png)

### Processo 3 - Definição dos privilégios aos usuários da lista

![privilegios de lista](image-3.png)

### Processo 4 - Atualização de uma lista compartilhada

![atualiza de lista](image-4.png)

## Indicadores de Desempenho

Apresente aqui os principais indicadores de desempenho e algumas metas para o processo. Atenção: as informações necessárias para gerar os indicadores devem estar contempladas no diagrama de classe. Colocar no mínimo 5 indicadores. 

Usar o seguinte modelo: 

![Indicadores de Desempenho](img/02-indic-desemp.png)
Obs.: todas as informações para gerar os indicadores devem estar no diagrama de classe a ser apresentado a posteriori. 

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |

Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)

# Matriz de Rastreabilidade

A matriz de rastreabilidade é uma ferramenta usada para facilitar a visualização dos relacionamento entre requisitos e outros artefatos ou objetos, permitindo a rastreabilidade entre os requisitos e os objetivos de negócio. 

A matriz deve contemplar todos os elementos relevantes que fazem parte do sistema, conforme a figura meramente ilustrativa apresentada a seguir.

![Exemplo de matriz de rastreabilidade](img/02-matriz-rastreabilidade.png)

> **Links Úteis**:
> - [Artigo Engenharia de Software 13 - Rastreabilidade](https://www.devmedia.com.br/artigo-engenharia-de-software-13-rastreabilidade/12822/)
> - [Verificação da rastreabilidade de requisitos usando a integração do IBM Rational RequisitePro e do IBM ClearQuest Test Manager](https://developer.ibm.com/br/tutorials/requirementstraceabilityverificationusingrrpandcctm/)
> - [IBM Engineering Lifecycle Optimization – Publishing](https://www.ibm.com/br-pt/products/engineering-lifecycle-optimization/publishing/)


# Gerenciamento de Projeto

De acordo com o PMBoK v6 as dez áreas que constituem os pilares para gerenciar projetos, e que caracterizam a multidisciplinaridade envolvida, são: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições, Partes Interessadas. Para desenvolver projetos um profissional deve se preocupar em gerenciar todas essas dez áreas. Elas se complementam e se relacionam, de tal forma que não se deve apenas examinar uma área de forma estanque. É preciso considerar, por exemplo, que as áreas de Escopo, Cronograma e Custos estão muito relacionadas. Assim, se eu amplio o escopo de um projeto eu posso afetar seu cronograma e seus custos.

## Gerenciamento de Tempo

Com diagramas bem organizados que permitem gerenciar o tempo nos projetos, o gerente de projetos agenda e coordena tarefas dentro de um projeto para estimar o tempo necessário de conclusão.

![Diagrama de rede simplificado notação francesa (método francês)](img/02-diagrama-rede-simplificado.png)

O gráfico de Gantt ou diagrama de Gantt também é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. Com ele, é possível listar tudo que precisa ser feito para colocar o projeto em prática, dividir em atividades e estimar o tempo necessário para executá-las.

![Gráfico de Gantt](img/02-grafico-gantt.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-project-timeline.png)

## Gestão de Orçamento

O processo de determinar o orçamento do projeto é uma tarefa que depende, além dos produtos (saídas) dos processos anteriores do gerenciamento de custos, também de produtos oferecidos por outros processos de gerenciamento, como o escopo e o tempo.

![Orçamento](img/02-orcamento.png)
