---
titulo: Choque en movimiento acelerado
autor: Resnick
dificultad: media
tags:
  - fisica
  - trigonometría
  - ecuación cuadrática
  - movimiento rectilíneo
  - cinemática
---

# Choque en movimiento acelerado

**Fuente/Autor:**  *Resnick - Fundamentos de Fisica*

## Enunciado
En la figura, la partícula A se mueve a lo largo de la recta $y=30 \, m$ con velocidad constante $\vec{v}$ de magnitud $3.0\, m/s$ y paralelo al eje X. En el instante que la partícula A pasa el eje Y, la partícula B sale del origen velocidad inicial cero y aceleración constante $\vec{a}$ de magnitud $0.40\,m/s^2$. ¿Qué ángulo $\theta$ entre $\vec{a}$ y la dirección positiva del eje Y resultará en una colisión?

<p align="center">
  <img src="assets/resnick-4.20.jpg" alt="Partículas en movimiento"  width="250">
</p>

## Solucion

### 1. Estrategia
Encontraremos cuanto tiempo tarda la partícula B en llegar a la línea $l = 30 \,m$ en funcion del ángulo $\theta$, en ese tiempo ambas partículas deben estar en el mismo valor de X.

### 2. Posición de B
Sea $l=30\,m$ la distancia inicial entre $A$ y $B$ y $R$ la distancia recorrida por $B$ en el tiempo $t$

Como es un movimiento con aceleración constante se cumple

$$
R = \frac{1}{2}at^2
$$

La posición $(x,y)$ de $B$ en el tiempo $t$
$$
x_B = Rsen\theta, \quad y_B = Rcos\theta
$$

### 3. Tiempo en cubrir la distancia $l$
Igualando $y_B = l$

$$
\frac{1}{2}at^2cos\theta = l
$$

Despejando $t$ obtenemos

$$
t = \sqrt{\frac{2l}{acos\theta}}
$$

### 4. Condición de colisión
Para que exista colisión en ese tiempo debe cumplirse que $x_A = x_B$

$$
vt = Rsen\theta
$$

$$
vt = \frac{1}{2}at^2 sen\theta
$$

Reemplazando $t$ y ordenando obtenemos

$$
v = \frac{1}{2}a\sqrt{\frac{2l}{acos\theta}}sen\theta
$$

De donde obtenemos la ecuación cuadrática

$$
alcos^2\theta + 2v^2cos\theta - al = 0
$$

cuya solución es

$$
cos\theta = \frac{\sqrt{v^4 + a^2 l^2} - v^2}{al}
$$

Desechamos la raíz negativa

## Solución en Geogebra
En la animación se puede ver que las particulas colisionan con el ángulo $\theta$ encontrado.

<iframe src="https://www.geogebra.org/calculator/wthjbfgc?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

## Problemas relacionados
- [[savchenko-1.3.2| Descenso dentro de círculo]]