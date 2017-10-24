# JavaScript

1 - O que é JS ?

  Java Script é uma linguagem de programação baseada em scripts e padronizada pela ECMA Internacional (associação especializada na padronização de sistemas de informação).
  
  Java Script foi originalmente desenvolvido por Brendan Eich quando trabalhou na Netscape sob o nome de Mocha, posteriormente teve seu nome mudado para LiveScript e por fim JavaScript. LiveScript foi o nome oficial da linguagem quando foi lançada pela primeira vez na versão beta do navegador Netscape 2.0 em setembro de 1995, mas teve seu nome mudado em um anúncio conjunto com a Sun Microsystems em dezembro de 1995 quando foi implementado no navegador Netscape versão 2.0B3.
  
  A mudança de nome de LiveScript para JavaScript coincidiu com a época em que a Netscape adicionou suporte à tecnologia Java em seu navegador (Applets). A escolha final do nome causou confusão dando a impressão de que a linguagem foi baseada em Java, sendo que tal escolha foi caracterizada por muitos como uma estratégia de marketing da Netscape para aproveitar a popularidade do recém-lançado Java.
 
  Apesar de conter Java no nome, a linguagem Java Script é distinta da linguagem Java e apresenta recursos não disponibilizados em Java ou C++. Os scripts desenvolvidos em Java Script são muito populares e amplamente integrados em páginas web devido à facilidade de interação com o Document Object Model (DOM) da página.
  
  Uma linguagem de script tem a funcionalidade de ser executada no interior de programas ou de outra linguagem de programação. Outras linguagens usadas como script são: ActionScript, PHC, Python, VBScript, entre outras.


2 - O que é Closure?

   Uma closure ocorre normalmente quando uma função é declarada dentro do corpo de outra, e a função interior referência variáveis locais da função exterior. Em tempo de execução, quando a função exterior é executada, então uma closure é formada, que consiste do código da função interior e referências para quaisquer variáveis no escopo da função exterior que a closure necessita.
Se trata de uma função definida dentro de outra função. A função interna utiliza de parâmetros e variáveis da função externa

3 - O que é Hosting?

  Antigamente em linguagens como C, se usavam funções ou procedimentos para dividir um programa, mas havia um problema: as declarações deveriam ficar sempre na frente. O que acontece agora é que os compiladores ou até mesmo linguagens runtime leem todo o programa para saber que funções e variáveis você declarou no código. Após isso, a execução real acontece e ele já sabe onde está cada coisa. JavaScript faz exatamente isso, o que chamamos de Hoisting.
  
O JavaScript não obriga você a declarar variáveis, permite que você defina as funções em qualquer lugar que você queira, o que lhe permite usar uma função antes de sua definição. O nome Hoisting, elevação ou até mesmo içamento, é só um termo especificado, pois ele arranca as declarações até o topo do seu escopo.

4 - O que é ES6/ES7 features?

  O ECMAScript (ES) é a especificação da linguagem de script que o JavaScript implementa, ou seja, é a descrição formal e estruturada de uma linguagem de script, sendo padronizada pela Ecma Internacional – associação criada em 1961 dedicada à padronização de sistemas de informação e comunicação – na especificação ECMA-262. No dia 17 de junho de 2015, foi definida a sexta edição da especificação, a ES6 (também chamada de ECMAScript 2015).
  
O TC39 focou em alguns objetivos no desenvolvimento do ES6: ser uma linguagem melhor para construir aplicações complexas, resolver problemas antigos do JavaScript, facilidade no desenvolvimento de libraries

Diferentemente das edições anteriores, o ES6 trouxe a maior mudança para a linguagem JavaScript desde a sua criação, há 20 anos. O principal objetivo da nova versão especificação foi tornar a linguagem mais flexível, enxuta e fácil de se aprender e trabalhar, tornando-a mais próxima a outras linguagens orientadas a objeto, como Java e Python.
Entre as principais mudanças, temos:

•	Criação de novos tipos de dados (Map, WeakMap, Set, WeakSet);
•	Novas maneiras de iterar objetos e coleções;
•	Declaração de variáveis com let e const;
•	Modularização e estrutura de classes;
•	Geradores e símbolos;
•	Operadores rest e spread.

O interesse na linguagem se refletiu na criação de uma imensa diversidade de bibliotecas e frameworks. Alguns exemplos mais famosos que têm tido grande aceitação na comunidade e no mercado:

•	React: Biblioteca criada pela equipe do Facebook para criação de componentes;
•	React Native: Framework para criação de aplicativos mobile usando o React;
•	Angular 2: Framework MVC mantido pelo Google;
•	Js: Biblioteca para criação de componentes;
•	Meteor: Framework para criação de aplicações web singlepage;
•	Electron: Framework para criação de aplicações desktop multiplataforma.

5 - Instanciação de variaveis?

Hoisting, como já citado antes, é um comportamento do JavaScript de mover declarações para o topo de um escopo (o escopo global ou da função em que se encontra). Em JavaScript, funções e variáveis são hoisted (ou “levados ao topo”). Isso significa que você pode usar variável e função antes mesmo de tê-las declaradas.
	
Uma closure, como já mencionado antes, é o escopo criado quando uma função é declarada que permite à função acessar e manipular variáveis externas a ela. Em outras palavras, clousers permitem quem uma função acesse todas as variáveis, assim como outras funções, que estão em escopo quando ela é declarada.
	
Todas as variáveis ou funções declaradas fora de uma função estarão disponíveis para todo o código JavaScript na página, se esse código é dentro de uma função ou de outra forma, nós chamamos isso de âmbito global. Já Parâmetros de função são semelhantes às variáveis, eles têm um âmbito local, e, portanto, só pode ser acessado de dentro da função.
	
IIFE significa uma “Função anônima auto executável” ou “Função Imediatamente Executável”, quando usamos isso queremos criar um escopo no JavaScript para que as variáveis dentro dela não poluam o escopo global, evitando possíveis conflitos de variáveis ou funções com o mesmo nome.
		
6 - Criação de funções (ES5/ES6)?

Uma função JavaScript é um bloco de código projetado para executar uma tarefa específica. Uma função é executada quando "algo" o invoca (chama).
Exemplo função ES5:
	function myFunction(p1, p2) {
    		return p1 * p2;   // A função retorna o produto de p1 e p2
		}
Exemplo função ES6:
	myFunction(p1, p2)=> p1 * p2;

Sintaxe
ES5
Uma função JavaScript é definido com a function como palavra-chave, seguido por um nome, seguido de parênteses ().
Nomes de funções pode conter letras, números, sublinhados e cifrões (mesmas regras variáveis).
Os parênteses podem incluir nomes de parâmetros separados por vírgulas:( parameter1, parameter2, ...)
O código a ser executado, pela função, é colocado dentro de chaves: {}

	function nome(parameter1, parameter2, parameter3) {
 	   código a ser executado
	}

Dentro da função, os argumentos (parâmetros) comportam-se como variáveis locais.
Uma função é o mesmo que um procedimento ou uma sub-rotina, em outras linguagens de programação.
ES6
	([param], [param]) => {
 	  statements
	}	
	param => expression

Invocação da função
O código dentro da função será executado quando "algo" invoca a função:
•	Quando ocorre um evento (quando um usuário clica em um botão)
•	Quando ela é invocada (chamado) a partir do código JavaScript
•	Automaticamente (auto invocado)

7 - Arrays?

Tradicionalmente, um Array reserva uma alocação contínua de memória de tamanho predefinido. No JavaScript, esse não é o caso. Um Array no JavaScript é simplesmente um objeto com um construtor único, com uma sintaxe literal e com um conjunto adicional de propriedades e de métodos herdados de um protótipo de Array. Isso significa fazer um pequeno sacrifício de performance, mais do que compensado pela facilidade de uso e pelo poder de seus utilitários.
No JavaScript, sempre que há uma sintaxe literal para criação de  objetos

	//cria o objeto
	var a = [];
	// existem duas forma para atribuir dados ao Array
	a[0] = "Bob";
	a[1] = "Mary";
	a[2] = "Joe";
	//ou push
	a.push("Jane");
	a.push("Carlos");

também, podemos usar a sintaxe new Constructor. Fora a óbvia desvantagem de 5-9 toques adicionais, há um aspecto mais sério no que diz respeito à ambiguidade: 
	var a = new Array(8);
Um Array pode conter qualquer objeto do tipo primitivo. Dados de tipos diferentes podem coexistir no mesmo Array. 
Elementos Array são simplesmente propriedades de objetos e são acessados da mesma forma que outras propriedades de objetos. 


8 - CommonJS?

A API CommonJS preencherá essa lacuna definindo APIs que atendam muitas necessidades comuns de aplicativos, fornecendo uma biblioteca padrão tão rica quanto a de Python, Ruby e Java. A intenção é que um desenvolvedor de aplicativos possa escrever um aplicativo usando as API CommonJS e, em seguida, executar esse aplicativo em diferentes intérpretes de JavaScript e ambientes de host. Com os sistemas compatíveis com CommonJS, você pode usar o JavaScript para escrever:
	•Aplicativos de JavaScript do lado do servidor
	•Ferramentas de linha de comando
	•Aplicativos baseados em GUI da área de trabalho
	•Aplicações híbridas (Titanium, Adobe AIR)


9 - AngularJS / JQuery

10 - PWA?

   Progressive Web Apps está ligado intimamente a experiência do usuário para um maior e melhor alcance das possibilidades da web. A presença mobile em nossas vidas é cada vez mais comum e acelerada, e no Brasil isso é bem expressivo.
PWA além de ter a experiência do usuário como foco central, é baseada em três pilares:

•	Confiável;
•	Rápido;
•	Atraente.

   Uma aplicação web confiável é aquela em que você sempre pode contar, mesmo quando não há conexão com a internet. Para que tenhamos essa confiança e garantia, é utilizado um proxy escrito em JavaScript que roda do lado do cliente e que é responsável por controlar o cachê e as requisições do seu navegador de internet. Com o PWA recursos chaves são pré-cacheados e isso elimina a dependência de rede disponível para seu carregamento. Com isso seus usuários terão uma experiência de carregamento instantâneo e confiável.

  Usuários de internet são ansiosos, não tem paciência e seu site precisa carregar rápido. Ponto. Mas no conceito de Progressive Web Apps, a questão de ser rápido precisa ir além do carregamento. É necessário, também, uma resposta ágil às interações do usuário como animações e rolagens fluídas.
Ser rápido é ter um carregamento de página em até três segundos – 53% dos usuários abandonam as páginas após esse período – e interações fluídas, inteligentes e objetivas.

   PWA transforma os sites em experiências muito próximas dos aplicativos mobile através de um arquivo chamado Web App Manifest que fica hospedado junto ao seu site. Esse arquivo define como o site será carregado, a aparência que terá, o botão a ser utilizado na tela inicial do celular do usuário e trata as notificações push. Um aplicativo tradicional requer o seu download nas apps stores, com PWA não precisamos dessas lojas e os sites se tornam instaláveis. Além disso, especificamos o ícone e a página a ser carregada quando o ícone for tocado. Com Progressive Web Apps temos o controle da aparência da interface, determinando a exibição em tela normal ou full screen, usar a orientação retrato ou paisagem e outras possibilidades.














