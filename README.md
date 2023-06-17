# AtividadeUnity-
<h1>Link do trabalho no drive</h1> 
https://drive.google.com/file/d/1WyY1zSzmRE7AYAJfloUjNEscwalEQkW3/view?usp=sharing<br>
<H1>Como fizemos esse trabalho?</H1>
Com o programa unity, o 2D.  Pegamos na asset store algo que combinaria com a nossa ideia.<br>
Apos isso, fizemos com paletts o cenario e com as coisas que vinham juntos com o asset o fundo e ambientação do cenario<br>
Ainda com oque veio com esse asset,  pegamos o personagem e programamos ele para andar pela nossa cena e tranformar isso jogavel<br> 
para qualquer pessoa que quiser.<br>
Alem disso com outros game objects, pegamos formas e tranformamos em inimigos "dark", para combater o protagonista nesse mundo tao fofo.<br> 
São progamados para se mexerem sozinho, porem são facilmente derrotados ao serem jogados para baixo do cenario
<h1>Sobre oque é esssa cena?</h1>
Essa cena  é bem simples, voce controlara um personagen fofo rosa que deve seguir as setas ate o final nas nuvens com uma recompensa, 2 baus do tesouro<br>
<h1>Comandos Ultilizados</h1>
<h2>Movimento do personagem</h2>
Ele utiliza um componente Rigidbody2D para controlar a física do movimento. A velocidade do objeto é definida pela variável "speed". No método Start, o script obtém uma referência ao componente Rigidbody2D do objeto. No método Update, o código obtém a entrada do jogador nos eixos horizontal e vertical. Esses valores são usados para criar um vetor de movimento, que é multiplicado pela velocidade e atribuído à propriedade "velocity" do Rigidbody2D. Isso faz com que o objeto se mova na direção e velocidade especificadas.
<h2>Movimento dos inimigos "Dark"</h2>
Ele utiliza um componente Rigidbody2D para controlar a física do movimento. A força de movimento é definida pela variável "moveForce". No método Start, o script obtém uma referência ao componente Rigidbody2D do objeto. No método Update, o código gera um vetor de movimento aleatório usando valores entre -1 e 1 para os eixos horizontal e vertical. Esse vetor de movimento é multiplicado pela força de movimento e adicionado ao objeto usando o método "AddForce" do Rigidbody2D. Isso faz com que o objeto inimigo se mova em direções aleatórias com a força especificada.
