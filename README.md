### Curso na Udemy - Curso de Angular 2 (v15+) Typescript do Básico ao Avançado


### Componentes
- ng generate c titile

### ngOnInit
- Este evento é inicializado apos o Angular exibir pela primeira vez as propriedades vinculadas aos dados ou quando o componente foi incializado.Este evento é usado principalmente para inicializar dados em um componente.
- chamado uma única vez quando o componente é inicializado (logo após o primeiro ngOnChanges).

### ngOnChanges
- Este evento é executado sempre que um valor de um controle de entrada dentro do componente é alterado.
- chamado uma vez na criação do componente e sempre que houver alteração em uma de suas propriedades de entrada. Ou seja, mudanças no Input() decorator e no property binding.

### ngDoCheck 
- Este evento é disparado sempre que as propriedades de entrada de um componente são verificadas.
- chamado uma vez na criação do componente e sempre que houver alteração em uma de suas propriedades de entrada. Ou seja, mudanças no Input() decorator e no property binding

### ngAfterContentInit
-  Este metodo de ciclo de vida é executado quando o Angular realiza qualquer projeçãode conteúdo nas visualizações do componente. 
-  chamado depois que o conteúdo externo é inserido no componente (por exemplo, vindo do ng-content).

### ngAfterContentChecked 
-  Este método de gancho de ciclo de vida é executado sempre que o conteudo do componente é verificado pelo o mecanismo de detecção de alteração do Angular

### ngOnDestroy
- Chamado antes do Angular destruir o componente

### Data Binding
- É uma forma de exibir dados em seu component HTML, nada mais do que trabalhar com dados
-  invocado após a verificação do conteúdo externo

### ngAfterViewInit
- chamado logo após o conteúdo do próprio componente e de seus filhos ser inicializado

### ngAfterViewChecked
- chamado cada vez que o conteúdo do componente é verificado pelo mecanismo de detecção de alterações do Angular

### Interpolation 
- Caracterizado por duas chaves

### Property Binding
- Forma de associar propriedades entre o template (arquivo html) e o component (arquivo typescript)

### Event Binding
- Associação de eventos

### As diretivas são classes que adicionam comportamento adicional aos elementos em seus aplicativos Angular. Com diretivas integradas do Angular, você pode gerenciar formmulários, listas, estilos eo que os usuários veem.
- Diretivas de atributo: Que alteram a aparência ou comportamento de um elemento, componente ou outra diretiva. Como por exemplo: NgClass, NgStyle e NgModel.
- Diretivas estruturais: Eles moldam ou remodelam a estrutura do DOM, adicionando, removendo e manupulando os elementos do host aos quais estão anexados. Como por exemplo: NgIf, NgFor, NgSwitch
- O ngIf é uma condicional para adicionar ou remover algo do DOM. É muito parecido com o If padrão. Usamos o elemento que queremos adicionar como atributo para o “ngIf” e não devemos esquecer do “*”. Podemos usar expressão que possa retornar “true” ou “false”
- A diretiva ngFor é utilizada para repetir um elemento do Template.
- A diretiva ngSwitch é uma diretiva que exibe um elemento de um possível conjunto de elementos com base em alguma condição. Ela usa as diretivas ngSwitchCase e ngSwitchDefault.
- O ngClass é uma diretiva que permite definir uma classe dinâmicamente a partir do DOM de um elemento.
- A diretiva NgStyle é uma diretiva de atributo usada para alterar o estilo de qualquer elemento do DOM com base em alguma condição
- O ngModel lida com os dois fluxos: ele dispara eventos para atualizar a sua variável no componente, e se a variável for atualizada ele recebe esse valor também
- O ng-template é um elemento de template (em português, modelo) que o Angular usa com as diretivas estruturais ( *ngIf , *ngFor , [ngSwitch] e as diretivas personalizadas). Esses elementos de modelo, ou template, funcionam apenas na presença de diretivas estruturais.
- O <ng-content> é usado para criar componentes configuráveis. Isso significa que os componentes podem ser configurados, dependendo das necessidades do usuário. Essa situação é bem conhecida como projeção de conteúdo
- Pipe nos ajuda a transformar dados que estão em um formato para outro. Eles são chamados assim pois usa o “|” para chamá-lo
  
### Module Angular
- Um module é um mecanismo para agrupar componentes, diretivas, pipes e serviços relacionados, de forma a combinar com outros modulos para criar um aplicativo. O Angular fornece uma boa maneira de organizar esses blocos de forma simples e eficaz usando módulos(também conhecidos com ngModules)
  
### Comunicação entre Componentes
- @Input() é entrada de dados no componente.
- @Output() é saida de dados no componente.
  
### Projeto Pratico 1
- Nessa ferramenta o usuário poderá adicionar tareefas diárias, podendo marcar que completo ou ate mesmo deletar a tarefeas selecionadas.
- ng new app-todo
- ng g m /modules/home
- ng g c /modules/home/components/header
- ng g c /modules/home/components/todoButtonDeleteAll
- ng g c /modules/home/components/todoInputAddItens
- ng g c /modules/home/components/todoList
- ng g c /modules/home/pages/home
- ng g interface /modules/home/model/TaskList
  
 ### Angular - Serviços, http e Observable
- ng g s /services/foodList - Criando service
- ng g c /shared/food-add
- Comunicação de componentes com Service
- Subscribe 
