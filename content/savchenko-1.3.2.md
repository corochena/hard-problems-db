---
titulo: Descenso dentro de círculo
autor: Savchenko
dificultad: media
tags:
  - fisica
  - cinemática
  - trigonometria
  - geometría
---

# Descenso dentro de círculo

**Fuente/Autor:**  *Savchenko - Problemas de Fisica*

## Enunciado
a) Una bola empieza a deslizarse sin fricción desde el punto superior de una circunferencia por una canaleta, inclinada bajo un ángulo $\phi$ respecto a la vertical. ¿Dentro de cuanto tiempo la bola alcanzará la circunferencia, si su diámetro es $D$?
b) Del punto A por los radios inclinados de diferente manera empiezan a deslizarse uniformemente sin fricción unos pequeños abalorios. ¿En qué curva se encontrarán  los abalorios en el momento de tiempo $t$?

<p align="center">
  <img src="assets/savchenko 1-3-2.jpg" alt="Descenso dentro de círculo"  width="450">
</p>

## Solucion

### 1. Estrategia
Calcularemos la distancia $L$ que desciende el objeto desde la parte superior del círculo hasta que toca la circunferencia, en función del ángulo $\phi$ formado por $L$ y el diámetro del círculo $D$. A partir de $L$ encontraremos el tiempo $t$ que tarda en caer bajo el efecto de la gravedad $g$.

### 2. Geometría
Sea $A$ el punto más alto de la circunferencia y $D$ el diámetro que pasa por dicho punto. Notemos que el triángulo formado por $L$ y $D$ es rectángulo, por lo tanto

$$
L = Dcos\phi
$$

La aceleración con que cae el cuerpo se ve reducida en función de la inclinación

$$
a = gcos\phi
$$

Ya que es un movimiento con aceleración constante se cumple que

$$
L = \frac{1}{2}at^2
$$

Sustituyendo y simplificando

$$
Dcos\phi = \frac{1}{2}(gcos\phi)\,t^2
$$

$$
D = \frac{1}{2}g\,t^2
$$

$$
t=\sqrt{\frac{2D}{g}}
$$

### 3. Interpretación
Llegamos a la conclusión que el tiempo de descenso es constante! No depende de la inclinación, unicamente depende del diámetro y de la aceleración de la gravedad. Por lo tanto varios abalorios formarán un círculo a medida que desciendan ya que se encontrarán a la misma distancia del punto de partida A.

### 4. Curiosidad del gran rodeo
Traté de encontrar la distancia $L$ encontrando el punto de intersección de la recta que pasa por A y la circunferencia y es posible hacerlo de esa manera pero es mucho más extenso, con mucha álgebra e identidades trigonométricas. 

Ecuaciones del círculo y la recta

$$
x^2 + y^2 = \frac{D^2}{4} , \quad y - \frac{D}{2} = \frac{x}{tan\phi}
$$

Combinando las ecuaciones obtenemos

$$
\left( y - \frac{D}{2}\right)^2 \; tan^2\phi + y^2 = \frac{D^2}{4}
$$

Desarrollando obtenemos la cuadrática

$$
y^2\,sec^2\phi - yD\,tan^2\phi + \frac{D^2}{4}(tan^2\phi - 1) = 0
$$

Resolviendo para $y$, desechando el caso trivial y simplificando obtenemos 

$$
y = D \frac{tan^2\phi-1}{2sec^2\phi}
$$

$$
y = -\frac{D}{2}cos2\phi
$$

Sustituyendo para x obtenemos

$$
x = -\frac{D}{2}sen2\phi
$$

Encontrando $L$

$$
L = \sqrt{\left( -\frac{D}{2} \, sen2\phi \right)^2 + \left( \frac{D}{2} + \frac{D}{2} \, cos2\phi \right)^2}
$$

Despues de más algebra e identidades obtenemos

$$
L = Dcos(\frac{\phi}{2})
$$

## Solución en Geogebra
La solucion en Geogebra usa varias secuencias, la primera $l1$ es una secuencia de valores para los ángulos de inclinación, con esta secuencia graficamos las rectas que pasan por el punto A y cortan a la circunferencia en distintos puntos que graficamos con las secuencias $l2$ y $l3$. Con esos puntos graficamos los segmentos de cuerda y finalmente dibujamos puntos que desciendan bajo la gravedad según las inclinaciones de la secuencia $l1$

<iframe src="https://www.geogebra.org/calculator/x4mpxry7?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

## Problemas relacionados
- [[savchenko-1.3.10| Altura de vuelo]]
- [[savchenko-1.3.13| Alcance de artillería]]
- [[savchenko-1.3.15| Lazo en cilindro]]