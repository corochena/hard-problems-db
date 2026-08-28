---
titulo: Alcance de artillería
autor: Savchenko
dificultad: alta
tags:
  - fisica
  - cinemática
  - trigonometria
  - movimiento parabolico
---

# Alcance de artillería

**Fuente/Autor:**  *Savchenko - Problemas de Fisica*

## Enunciado
De una pieza de artillería es necesario dar en un punto con coordenadas $x$ respecto a la horizontal e $y$, respecto a la vertical. La velocidad inicial del proyectil es $v$.
a) Hállese $tan\alpha$, o sea, la tangente del ángulo, formado por la boca de fuego del cañón y el horizonte.
b) Hállese el límite de la zona donde puede caer el proyectil.
c) ¿A qué valor mínimo de la velocidad $v$ el proyectil puede dar con el punto con coordenadas $x, y$?


## Solucion

### 1. Estrategia
Siendo que la parábola descrita por el proyectil debe impactar en el punto $(x, y)$ entonces usaremos la ecuación de la trayectoria con identidades trigonométricas para encontrar la $tan\alpha$

### 2. Trayectoria parabólica
La ecuación que describe la parábola del proyectil es

$$
y = xtan\phi - \frac{g}{2v^2\,cos^2\phi}x^2
$$

Usando identidades trigonométricas

$$
y = xtan\phi - \frac{g}{2v^2}(1+tan^2\phi)x^2
$$

Ordenando la ecuación obtenemos la cuadrática

$$
\frac{gx^2}{2v^2}tan^2\phi - xtan\phi + y + \frac{gx^2}{2v^2} = 0
$$

### 3. Solución de la cuadrática
Aplicando la fórmula general $ax^2 + bx + c = 0$

$$
tan\phi = \frac{x\pm\sqrt{x^2-\frac{2gx^2}{v^2}\left( y + \frac{gx^2}{2v^2} \right)}}{\frac{gx^2}{v^2}}
$$

Simplificando

$$
tan\phi = \frac{v^2}{gx} \left[ 1 \pm \sqrt{1 - \frac{2g}{v^2} \left( y + \frac{gx^2}{2v^2} \right)} \right]
$$

$$
tan\phi = \frac{v^2 \pm \sqrt{v^4 - g(2yv^2 + gx^2)}}{gx}
$$

### 4. Análisis de la fórmula
Al ser una cuadrática obtenemos 2 soluciones reales diferentes cuando el discriminante es mayor que cero y una solución real única cuando el discriminante es exactamente cero. Esta solución única representa el límite que puede alcanzar el proyectil.

$$
v^4 - g(2yv^2 + gx^2) = 0
$$


De donde obtenemos la frontera 

$$
y = \frac{v^2}{2g} - \frac{g}{2v^2}\,x^2
$$

Donde comprobamos que la frontera también es una parábola!

## Solución en Geogebra


## Problemas relacionados
- [[savchenko-1.3.2| Descenso dentro de círculo]]
- [[savchenko-1.3.10| Altura de vuelo]]
- [[savchenko-1.3.15| Lazo en cilindro]]
