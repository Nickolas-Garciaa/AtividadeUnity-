# AtividadeUnity-
<h1>Link do trabalho no drive</h1> 
https://drive.google.com/file/d/1ti4cCJWortQaetwWwzlzohAWbCc1vp4n/view?usp=sharing
https://drive.google.com/file/d/1IVZ4vNOZE46wAHTKM-HahZSHYY_MfG5L/view?usp=sharing
<H1>Como fizemos esse trabalho?</H1>
Com o programa unity, o 2D.  Pegamos na asset store algo que combinaria com a nossa ideia.<br>
Apos isso, fizemos com paletts o cenario e com as coisas que vinham juntos com o asset o fundo e ambientação do cenario<br>
Ainda com oque veio com esse asset,  pegamos o personagem e programamos ele para andar pela nossa cena e tranformar isso jogavel<br> 
para qualquer pessoa que quiser.<br>
Alem disso com outros game objects, pegamos formas e tranformamos em inimigos "dark", para combater o protagonista nesse mundo tao fofo.<br> 
São progamados para se mexerem sozinho, porem são facilmente derrotados ao serem jogados para baixo do cenario

![download](https://github.com/Nickolas-Garciaa/AtividadeUnity-/assets/128262640/08975ea0-6ea3-4212-a934-f1d37bab14f4)


<h1>Sobre oque é esssa cena?</h1>
Essa cena  é bem simples, voce controlara um personagen fofo rosa que deve seguir as setas ate o final nas nuvens com uma recompensa, 2 baus do tesouro<br>
<h1>Comandos Ultilizados</h1>
<h2>Movimento do personagem</h2>
Ele utiliza um componente Rigidbody2D para controlar a física do movimento. A velocidade do objeto é definida pela variável "speed". No método Start, o script obtém uma referência ao componente Rigidbody2D do objeto. No método Update, o código obtém a entrada do jogador nos eixos horizontal e vertical. Esses valores são usados para criar um vetor de movimento, que é multiplicado pela velocidade e atribuído à propriedade "velocity" do Rigidbody2D. Isso faz com que o objeto se mova na direção e velocidade especificadas

![Script](https://github.com/Nickolas-Garciaa/AtividadeUnity-/assets/128262640/2706835c-c02f-4496-97dc-c0dfae687019)


<h2>Movimento dos inimigos "Dark"</h2>
Ele utiliza um componente Rigidbody2D para controlar a física do movimento. A força de movimento é definida pela variável "moveForce". No método Start, o script obtém uma referência ao componente Rigidbody2D do objeto. No método Update, o código gera um vetor de movimento aleatório usando valores entre -1 e 1 para os eixos horizontal e vertical. Esse vetor de movimento é multiplicado pela força de movimento e adicionado ao objeto usando o método "AddForce" do Rigidbody2D. Isso faz com que o objeto inimigo se mova em direções aleatórias com a força especificada.

![Script2](https://github.com/Nickolas-Garciaa/AtividadeUnity-/assets/128262640/d5943a6e-1ffc-476f-b619-fe26e3965eb3)

<h1>Cinemachine</h1>
Ultilizamos esse Gameobjects que instalamos para fazer a camera seguir o personagem, assim nao precisando usar codigos e de um jeito mais simples e funcional.

![Cinemachine](https://github.com/Nickolas-Garciaa/AtividadeUnity-/assets/128262640/de029af0-a567-41be-8f49-17680972b38b)

<H1>Asset usado</H1>
Pegamos um asset na store que combinava, um chamado Bayat Games 

![Bayatgames](https://github.com/Nickolas-Garciaa/AtividadeUnity-/assets/128262640/a3d25ca1-bb66-48c5-abd8-57396b3a083e)
