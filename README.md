<h1> Desafio: Aprenda na Prática Programação Orientada a Objetos</h1>

<p> Sejam bem-vindos ao desafio: <strong>APRENDENDO NA PRÁTICA O PARADIGMA DE ORIENTAÇÃO A OBJETOS.</strong><br>Desafio este que tive a honra de co-criar com a plataforma de cursos online <strong><a href="https://web.digitalinnovation.one/">DIGITAL INNOVATION ONE</a></strong> 💛🧡 e disponibilizado de forma gratuita para a comunidade dos desenvolvedores Java.<br>
    💎 O objetivo principal é colocar em prática umas das principais ferramentas da OO: <strong>ABSTRAÇÃO, ENCAPSULAMENTO, HERANÇA E POLIMORFISMO,</strong> através de um projeto Java. </p>



<h2>🛑 Pré-Requisitos</h2>

<p>
✅ Conhecer a sintaxe da Java<br>
✅ Java JDK 11<br>
✅ IDE para desenvolvimento Java (usarei IntelliJ)<br>
✅ Git<br>
✅ Conta no GitHub<br>
</p>



<h2> 👣 Passo-a-Passo</h2>

<p>
<strong>	1.</strong> Vamos ABSTRAIR o DOMÍNIO Bootcamp e MODELAR seus ATRIBUTOS E MÉTODOS <br>
<strong>	2.</strong> Criaremos as CLASSES: Bootcamp, Cursos, Mentorias e Devs e vamos relaciona-las <br>
<strong>	3.</strong> As CLASSES Curso, Mentoria e Devs também serão MODELADOS, ou seja, criaremos seus ATRIBUTOS E MÉTODOS <br> 
<strong>	4.</strong> Para que o código fique mais legível e de fácil manutenção, iremos utilizar de algumas das ferramentas que o PARADIGMA DE ORIENTAÇÃO A OBJETOS (POO) nos oferece: ABSTRAÇÃO, ENCAPSULAMENTO, HERANÇA E POLIMORFISMO <br>
<strong>	5.</strong> E para representar CLASSES que foram criadas e relacionadas, iremos transforma-las em OBJETOS<br>
</p><br>


----

<h2> Paradigma de Programação Orientado a Objetos (POO) </h2>

<p>
A visão de Orientação a Objetos (OO) é aquela de um mundo de objetos que interagem.<br>
Este paradigma é um modelo de análise, projeto e programação baseado na aproximação entre o mundo real e o mundo virtual, através da criação e interação entre classes, atributos, métodos, objetos, entre outros.<br>
São 4 os pilares principais do POO: ABSTRAÇÃO, ENCAPSULAMENTO, HERANÇA E POLIMORFISMO. 
</p>


<h3>🔺 ABSTRAÇÃO:</h3>

<p>Habilidade de concentrar-se nos aspectos essenciais de um domínio, ignorando características menos importantes ou acidentais. Nesse contexto, objetos são abstrações de entidades existentes no domínio em questão.</p>

<h3>🔺 ENCAPSULAMENTO:</h3>

<p> Encapsular significa esconder a implementação dos objetos. O encapsulamento favorece principalmente dois aspectos de um sistema: a manutenção e a evolução.</p>

<h3>🔺 HERANÇA:</h3>

<p>Permite que você defina uma classe filha que reutiliza (herda), estende ou modifica o comportamento de uma classe pai. A classe cujos membros são herdados é chamada de classe base. A classe que herda os membros da classe base é chamada de classe derivada.</p>

<h3> 🔺 POLIMORFISMO</h3>

<p>Capacidade de um objeto poder ser referenciado de várias formas. Cuidado, polimorfismo não quer dizer que o objeto fica se transformando, muito pelo contrário, um objeto nasce de um tipo e morre daquele tipo, o que pode mudar é a maneira como nos referimos a ele. A capacidade de tratar objetos criados a partir das classes específicas como objetos de uma classe genérica é chamada de polimorfismo.</p>


<h2 align="center"> ‼️ Conceitos fundamentais POO: ‼️ </h2>


DOMÍNIO

CLASSE

ATRIBUTO

MÉTODO

OBJETO



----

<h2> 🧮 Linguagem de Programação vs Paradigma de Linguagem de Programação</h2>

<p>
<h3> LINGUAGEM DE PROGRAMAÇÃO:</h3> 
É uma linguagem formal que, através de uma série de instruções, permite que um programador escreva um conjunto de ordens, ações consecutivas, dados e algoritmos para criar programas que controlam o comportamento físico e lógico de uma máquina.<br>
Seguem alguns exemplos de como as linguagens de programação podem ser classificadas:<br>
<br>
🔺 Nível de abstração:<br>
Baixo Nível: Assembly<br>
Médio Nível: C, C++, D, Objective C, etc.<br>
Alto Nível: Java, C#, PHP, Javascript, etc.<br>
Altíssimo Nível: Python, Ruby, Elixir, etc.<br>
<br>
🔺 Paradigma de programação:<br>
Programação Estruturada: C, Pascal, Ada, etc.<br>
Programação Orientada a Objetos: Java, C#, C++, Objective C, D, etc.<br>
Programação Funcional: Lisp, Scheme, Erlang, Elixir, etc.<br>
<br>
🔺 Linguagens classificadas pela arquitetura da aplicação:<br>
Desktop: C, C++, Object Pascal, Java, etc.<br>
Web: PHP, Ruby, Javascript, Java, etc.<br>
<br>
🔺 Tipo de execução:<br>
Linguagens compiladas: C, C++, Pascal, D, GO, etc.<br>
Linguagens Interpretadas: Python, Ruby, PHP, Javascript, etc.<br>
Linguagens Hibridas: Java, Erlang, Elixir, etc.<br>


<h3> PARADIGMA DE LINGUAGEM DE PROGRAMAÇÃO</h3> 

É um conjunto de características que podem ser utilizados para categorizar determinado grupo de linguagens. Um paradigma pode oferecer técnicas apropriadas para uma aplicação específica.<br>
<br>
<strong>PARADIGMAS PRINCIPAIS e SEUS SUBPARADIGMAS</strong><br><br>

🔸 <strong>1. Paradigma Imperativo</strong><br>
Neste paradigma, o programa descreve o processamento necessário para solucionar o problema. Assim, o paradigma imperativo é caracterizado por execução sequencial de instruções, pelo uso de variáveis que representam posições de memória e pelo uso de instruções de atribuição que alteram os valores dessas variáveis.<br>
<br>
Vejamos alguns Subparadigmas do Paradigma Imperativo e exemplos linguagens de programação que adotam esses subparadigmas.<br>
1.1 Paradigma estruturado:  ALGOL 58 e ALGOL 60 <br>
1.2 Paradigma concorrente: Java e Ada<br>
1.3 Paradigma Orientado a Objetos: Smalltalk e Java<br>
<br>

🔹 <strong>2. Paradigma Declarativo</strong><br>
Este paradigma é o modelo no qual os resultados são descritos, mas os passos para chegar aos resultados não são estabelecidos.<br>
<br>
Vejamos alguns Subparadigmas do Paradigma Declarativo e exemplos linguagens de programação que adotam esses subparadigmas:<br>
2.1 Paradigma Funcional: Lisp e Haskell<br>
2.2 Paradigma Lógico: Prolog<br>
</p>

<br>

<h2> 🤝 Contribuindo </h2>

<p>
Este repositório foi criado para fins de estudo, então contribua com ele.<br>
Se te ajudei de alguma forma, ficarei feliz em saber. E caso você conheça alguém que se identidique com o conteúdo, não deixe de compatilhar.<br>
<br>
Se possível:<br>
⭐️  Star o projeto<br>
🐛 Encontrar e relatar issues<br>
</p>



------------

Disponibilizado com ♥ por [cami-la](https://www.linkedin.com/in/cami-la/ "cami-la").
