---
layout: post
title: Carrusel para Mobile
categories: wireframe
external-url: http://share.axure.com/2VKE65/
tags:
- axure
- ia
- wireframe
- forms
tipo:
- link
---
Hoy en día los carruseles en la mayoría de las ocaciones se utilizan en galerías de imágenes, dentro de las ventajas que ofrecen son de ir mostrando elementos próximos y navegar entre ellos, los puntos en donde muchas veces se cometen errores es en los indicadores de posición, en un artículo de Andy de UX Movement [5 Big Usability Mistakes Designers Make on Carousels](http://uxmovement.com/navigation/big-usability-mistakes-designers-make-on-carousels/) nos indica los errores más comunes y los cuáles deberíamos de evitar.

Teniendo esto en mente una ocasión me encontré con la tarea de llevar a dispositivos móviles un elemento muy parecido a un carrusel, las desventajas que encontre al empezar a analizar como debería de comportarse fueron los siguientes

+ En portrait existe muy poco espacio para mostrar varios elementos y que estos sean fáciles de interactuar
+ Los indicadores de posición ocupaban espacio que se podía aprovechar por el contenido
+ Si se dejaban dos elementos 100% visibles el rating de visualización de más elementos se podría perder


#### Prueba A

<img src="/images/posts/carousel-mobile-test-a.png" title="Carousel for Mobile test a" alt="Carousel for Mobile test a" class="mobile-element">

##### Pros

+ Muestra dos elementos de primera instancia

##### Cons

+ Los indicadores por puntos no muestran los elementos que realmente estamos viendo
+ Se requieren elementos gráficos que nos indiquen que los elementos visualizados son parte de un solo elemento
+ Posibilidad de que el usuario descubra más elementos bajo

#### Prueba B

<img src="/images/posts/carousel-mobile-test-b.jpg" title="Carousel for Mobile test A" alt="Carousel for Mobile test B" class="mobile-element">

##### Pros

+ No se encontraron detalles adicionales positivos

##### Cons

+ Al eliminar los indicadores se pierde de forma total el descubrimiento de más elementos

#### Prueba C

<img src="/images/posts/carousel-mobile-test-c.jpg" title="Carousel for Mobile test C" alt="Carousel for Mobile test C" class="mobile-element">

##### Pros

+ El indicador de posición es más fácil de leer/entender que un indicador de número de elementos

##### Cons

+ Si el indicador de posición graficamente no esta bien construido puede pasar desapercibido
+ Bajo rating de descubrimiento

#### Prueba D

<img src="/images/posts/carousel-mobile-test-d.jpg" title="Carousel for Mobile test D" alt="Carousel for Mobile test D" class="mobile-element">

##### Pros

+ Al mostrar con los indicadores de puntos los elementos que se están viendo la lectura de elementos adicionales/totales puede llegar a ser más fácil.

##### Cons

+ Debido a que el modelo mental refiere un elemento = un punto, mostrar dos de cada vez puede llegar a confundir al usuario.

#### Prueba E

<img src="/images/posts/carousel-mobile-test-e.jpg" title="Carousel for Mobile test E" alt="Carousel for Mobile test E" class="mobile-element">

##### Pros

+ El descubrimiento de elementos nuevos responde a la naturaleza propia del ser humano de ser curioso
+ El rating de descubrir nuevos elementos tiende a ser alto
+ Más espacio para el elemento visible
+ indicador de posición nativo
+ Fácil de implementar

##### Cons

+ Requiere de elementos visuales bien implementados que ayuden a facilitar la interacción del usuario.

#### Conclusión

La solución para poder encontrar la mejor adaptación de un elemento a su versión móvil requirió de diferentes pruebas desde la concepción hasta el test en dispositivos, por lo que cuando te encuentres en alguna situación como esta trata de obtener la mayor información posible, realiza pruebas y siempre ten a la mano los diferentes escenarios posibles y corrige conforme encuentres información valiosa.