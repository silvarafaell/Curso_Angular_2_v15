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
