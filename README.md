<h1>DESAFIO: Aprendendo Orientação a Objetos na prática</h1>

<p> Sejam bem-vindos ao desafio: <strong>APRENDENDO O PARADIGMA DE ORIENTAÇÃO A OBJETOS NA PRÁTICA.</strong><br>
Desafio este que tive a honra de co-criar com a plataforma de cursos online <strong><a href="https://web.digitalinnovation.one/">DIGITAL INNOVATION ONE</a></strong> 💛🧡 e disponibilizado de forma gratuita para a comunidade dos desenvolvedores Java.<br> 
💎 O objetivo principal é colocar em prática umas das principais ferramentas da OO: <strong>ABSTRAÇÃO, ENCAPSULAMENTO, HERANÇA E POLIMORFISMO.</strong></p>


<h2> 👣 Passo-a-Passo</h2>
<p>
🔺 <strong>ABSTRAIR</strong> o <strong>DOMÍNIO</strong> Bootcamp criando sua <strong>CLASSE</strong> e direcionando-a como "classe principal" <br>
🔺 Em seguinda, precisaremos também <strong>ABSTRAIR</strong> seus <strong>ATRIBUTOS</strong> relacionando-os com outras <strong>CLASSES</strong>: Curso, Mentoria e Devs, data inicial e data final <br>
🔺 Os <strong>ATRIBUTOS</strong> Curso, Mentoria e Devs também serão <strong>MODELADOS</strong>, ou seja, criaremos seus <strong>ATRIBUTOS</strong> e <strong>MÉTODOS</strong> <br>
🔺 Para que o código fique mais legível e fácil de manutenção, iremos utilizar algumas das ferramentas que o paradigma de Orientação a Objeto nos dá: <strong>ABSTRAÇÃO, ENCAPSULAMENTO, HERANÇA E POLIMORFISMO.</strong><br>
🔺 E para representar as <strong>ABSTRAÇÕES</strong> (que neste momento já são classes) iremos transforma-las em <strong>OBJETOS</strong>
</p>
<br>

----

<h2> 🧮 Linguagem de Programação vs Paradigma de Linguagem de Programação</h2>
<p>
<h3> LINGUAGEM DE PROGRAMAÇÃO:</h3> 
É uma linguagem formal que, através de uma série de instruções, permite que um programador escreva um conjunto de ordens, ações consecutivas, dados e algoritmos para criar programas que controlam o comportamento físico e lógico de uma máquina.<br>
Seguem alguns exemplos de como as linguagens de programação podem ser classificadas:<br>
<br>
🔺 Nível de abstração:<br>
◼️    Baixo Nível: Assembly<br>
◼️    Médio Nível: C, C++, D, Objective C, etc.<br>
◼️    Alto Nível: Java, C#, PHP, Javascript, etc.<br>
◼️    Altíssimo Nível: Python, Ruby, Elixir, etc.<br>
<br>
🔺 Paradigma de programação:<br>
◼️    Programação Estruturada: C, Pascal, Ada, etc.<br>
◼️    Programação Orientada a Objetos: Java, C#, C++, Objective C, D, etc.<br>
◼️    Programação Funcional: Lisp, Scheme, Erlang, Elixir, etc.<br>
<br>
🔺 Linguagens classificadas pela arquitetura da aplicação:<br>
◼️    Desktop: C, C++, Object Pascal, Java, etc.<br>
◼️    Web: PHP, Ruby, Javascript, Java, etc.<br>
<br>
🔺 Tipo de execução:<br>
◼️    Linguagens compiladas: C, C++, Pascal, D, GO, etc.<br>
◼️    Linguagens Interpretadas: Python, Ruby, PHP, Javascript, etc.<br>
◼️    Linguagens Hibridas: Java, Erlang, Elixir, etc.<br>

<h3> PARADIGMA DE LINGUAGEM DE PROGRAMAÇÃO</h3> 
É um conjunto de características que podem ser utilizados para categorizar determinado grupo de linguagens. Um paradigma pode oferecer técnicas apropriadas para uma aplicação específica.<br>

<h4>PARADIGMAS PRINCIPAIS:</h4>
🔸 <strong>1. Paradigma Imperativo</strong><br>
Aborda os conceitos da computação relativos às mudanças de estado, ou seja, esse paradigma foca a forma de processamento via computador de determinada funcio-
nalidade/ação, através do uso de variáveis, atribuições etc.<br>
🔹 <strong>2. Paradigma Declarativo</strong><br>
Este paradigma dita que o programador deve modelar um dado problema através de assertivas acerca dos objetos do universo de discurso, ou seja, definindo o relacionamento lógico existente entre a cabeça e o corpo da cláusula, e nunca descrevendo como seus procedimentos funcionam. As soluções declarativas são usualmente mais fáceis de desenvolver e possuem a clareza e limpidez da pura lógica. 

<h4>ALGUNS SUBPARADIGMAS: </h4>

🔸 <strong>1.1 Paradigma estrturado:</strong><br>
Foi bastante usado, principalmente, para melhorar a comunicação com a linguagem de máquina, uma vez que faz uso de desvios e fluxos condicionais que possibilitam o controle da execu-
ção do programa. Tem como ênfase: sequência, decisão e, iteração (sub-rotinas, laços de repetição, condicionais e, estruturas em bloco)<br>
Exemplos de linguagens: ALGOL 58 e ALGOL 60<br>
<br>
🔸 <strong>1.2 Paradigma concorrente:</strong><br>
De caracteriza por executar vários processos compartilhando recursos simultaneamente. Nele, são desenvolvidos sistemas que permitem compartilhar dados ou dispositivos periféricos.
Fazem uso da execução simultânea de várias tarefas computacionais interativas, que podem ser implementadas como programas separados ou como um conjunto de threads criadas por um único programa. <br>
Exemplo de linguagens: Java e Ada <br>
<br>
🔸 <strong>1.3 Paradigma orientado a objetos:</strong><br>
Surgiu com o intuito de trazer mais rapidez ao processo de desenvolvimento de software, devido às suas características de portabilidade e reuso.
No paradigma OO, o foco está na abstração de dados como elementos básicos de programação, baseado na composição e interação entre diversas unidades chamadas de 'objetos'. <br>
Exemplo de linguagens: Smalltalk e Java<br>
<br>
🔹 <strong>2.1 Paradigma funcional: </strong><br>
Ela enfatiza a aplicação de funções tratando a computação como uma avaliação de funções matemáticas e que evita estados ou dados mutáveis.
opera apenas sobre funções, que recebem listas de valores e retornam um determinado valor. Este paradigma “visa definir uma função que retorna um valor como a resposta do proble-
ma”.<br>
Exemplo de linguagens: Lisp e Haskell<br>
</br>
🔹 <strong>2.2 Paradigma lógico: </strong><br>
O sentido da programação lógica é trazer o estilo da lógica matemática à programação de computadores.
os paradigmas definidos como lógicos são baseados em cálculos de predicados. Nesse sentido, ao se desenvolver um pro- grama no paradigma lógico, esse é sempre composto por cláusulas
que definem os predicados e as suas relações. <br>
Exemplo de linguagens: Prolog<br>

</p>
<br>

----
<h1> Paradigma orientado a objetos </h1>

<p>
A visão de Orientação a Objetos (OO) é aquela de um mundo de objetos que interagem. Cada objeto tem resposnabilidade por suas próprias ações. 
São 4 os pilares principais do POO:

<h3>ABSTRAÇÃO:</h3>
É um modelo de um sistema complexo que inclui apenas os detalhes essenciais para o observador. 
Quando estamos programando, abstração é o objetivo e a ocultação de informação é uma técnica para atingir este objetivo.

<h3>HERANÇA:<h3>

<h3>ENCAPSULAMENTO<h3>

<h3>HERANÇA<h3>

<h3>POLIMORFISMO</h3>


</p>

