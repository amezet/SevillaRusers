---
title: 'Programación funcional en tidyverse: introducción a purrr'
author: Francisco Rodriguez-Sanchez
date: '2019-03-06'
slug: programacion-funcional-en-tidyverse-introduccion-a-purrr
categories: 
  - charlas
tags: 
  - purrr
---

**En nuestra reunión de Marzo de 2019, Juan Luis Pérez Carretero, de Genera Games, nos dio una excelente introducción a la programación funcional con purrr.**

[Diapositivas](https://github.com/SevillaR/meetings/blob/gh-pages/2019-03-05_purrr/Purrr_presentation.pdf)

[Vídeo](https://youtu.be/bKJsZl16Ifs)

Juan Luis mostró cómo la consistencia y estructura organizada del *tidyverse* permite realizar operaciones iterativas sobre vectores, listas, o data frames, mediante código relativamente sencillo, breve, y consistente. 

En primer lugar, la función `map` aplica una función a cada elemento del vector: 

![](https://d33wubrfki0l68.cloudfront.net/f0494d020aa517ae7b1011cea4c4a9f21702df8b/2577b/diagrams/functionals/map.png)

Y `map2` trabaja con 2 vectores (o `pmap` con múltiples):

![](https://d33wubrfki0l68.cloudfront.net/f5cddf51ec9c243a7c13732b0ce46b0868bf8a31/501a8/diagrams/functionals/map2.png)

Por último, `walk` se utiliza para ejecutar funciones por sus 'side-effects' (por ejemplo, guardar archivos a disco).

Juan Luis ejecutó varios ejemplos de complejidad creciente, mostrando finalmente el potencial de usar [purrr en combinación con 'list-columns'](https://speakerdeck.com/jennybc/data-rectangling?slide=49).

Todos los detalles en el [vídeo](https://youtu.be/bKJsZl16Ifs) de la charla.


