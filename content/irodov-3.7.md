---
titulo: Campo eléctrico cerca del centro de un cuadrado
autor: Irodov
dificultad: media
tags:
  - fisica
  - vectores
  - campo eléctrico
  - cargas puntuales
---

# Campo eléctrico cerca del centro de un cuadrado

**Fuente/Autor:**  *I.E. Irodov - Problemas de Fisica General*

## Enunciado
En los vértices de un cuadrado, cuya diagonal es $2l$, se encuentran las cargas puntuales $+q$ y $-q$, como se muestra en la figura. Determinar el módulo del vector de la intensidad del campo eléctrico en un punto que está a la distancia $x$ del centro del cuadrado y se sitúa simétricamente respecto a los vértices del mismo.

<p align="center">
  <img src="assets/irodov 3-7.jpg" alt="Cuatro cargas eléctricas en cuadrado"  width="250">
</p>


## Solucion

### 1. Estrategia
Con diagramas vistos desde varias perspectivas, superior, frontal y lateral, se aprecia mejor las relaciones geométricas entre las diagonales, las aristas $l$, la distancia $x$, el campo $E$ y sus componentes.

### 2. Magnitud de $E$ causado por una sola carga $q$
El campo eléctrico de una carga puntual se calcula mediante

$$
E_1 = k\frac{q}{x^2 + l^2}
$$

Este valor se debe multiplicar por $\sqrt{2}/2$ para tomar la componente adecuada y se debe multiplicar por el coseno del ángulo formado por el vector $E_1$ y el plano del cuadrado, y esto por la contribución de las 4 cargas

$$
E = 4k \frac{q}{x^2 + l^2}\frac{\sqrt{2}}{2}cos\theta
$$

Sustituyendo y Simplificando

$$
E = 4k \frac{q}{x^2 + l^2}\frac{\sqrt{2}}{2} \frac{l}{r}
$$

$$
E = \frac{q}{\sqrt{2}\pi \epsilon_0}\frac{l}{(x^2 + l^2)^{3/2}}
$$

---

## Solución en GeoGebra
En 3D se aprecian todas las vistas que en 2D son difíciles de ver.

<iframe src="https://www.geogebra.org/calculator/e4j9zfgx?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>


## Problemas relacionados
- [[sears-zemansky-21.84| Esferas cargadas colgadas en presencia de campo eléctrico]]
- [[savchenko-6.1.8| Cuatro cargas formando un rombo]]