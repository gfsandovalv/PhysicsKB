Meant to be a test for studying methodology.

## Demuestre que no existe una biyeccion $f:\mathbb C \rightarrow B_1(0)$ tal que $f$ y $f^{-1}$ sean holomorfas.

$\mathbb C$ es el conjunto de los complejos y $B_{1}(0)=\{z \in\mathbb C :|z|<1\}$

La demostración se basa en dos teoremas: el teorema de Liouville y el principio del modulo máximo

Para contexto, el teorema de mapeo de Riemann dice que todo conjunto U propio y abierto de los complejos el cual es simplemente conexo es biholomorfo a B_1(0) (es decir, existe una biyeccion $f:U->B_1(0)$ con $f$ y $f^{-1}$ holomorfas)

El teorema de Liouville dice que toda funcion holomorfa $f:\mathbb C\rightarrow\mathbb C$ la cual es acotada (es decir, existe $M>0$ tal que $|f(z)|\leq M$ para toda z en C) debe ser constante

La parte del principio del modulo máximo util para la demostracion es esta: si U es abierto en C, conexo y acotado, y$f: cl(U)\rightarrow C$ es una funcion continua tal que f es holomorfa en U (cl(U) es la cerradura de U), entonces |f(z)| obtiene su valor maximo en un punto z en el borde de U

## Sketch of proof

Por contradicción, supongamos que existe un biholomorfismo $f:C->B_1(0)$. 
Sea $g: cl(B_1(0))->C$ una funcion continua y no constante tal que la restriccion de $g$ a la bola abierta $B_1(0)$ es holomorfa (por qué existe esta funcion?). 
Entonces $gf:C->C$ es holomorfa, no constante y acotada (por que?). El teorema de Liouville nos dice entonces que $gf$ es constante, lo cual contradice lo anterior.

cl 

La cerradura
En el caso de B_1(0)={z en C : |z|<1} y cl(B_1(0))={z en C : |z|<=1}
La topologia en C es bastante buena que las cerraduras se comportan bien con las desigualdades
Pero generalmente en un espacio metrico M no es cierto que cl(B_1(x))={y en M : |x-y|<=1}



[22:38, 23/11/2022] +1 (819) 329-5401: Esta es la demostracion original que tenia en mente, pero al escribirla me di cuenta que puede ser simplificada en el contexto del analisis complejo: supongamos que existe un biholomorfismo f:C->B_1(0). Entonces f es acotada y no-constante (por que?) y ya que B_1(0) es un subconjunto de C, el teorema de Liouville aplica en este caso y obtenemos que f es constante. Esto contradice el hecho que f no es constante
[22:39, 23/11/2022] +1 (819) 329-5401: En mi comentario anterior donde escribi "(por que existe esta funcion?)" hay una respuesta simple que yo tenia en mente pero justamente esa respuesta es la que simplifica el paso extra que hice xd


## To check
Definición de función holónoma 
