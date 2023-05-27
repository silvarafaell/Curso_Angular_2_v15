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
