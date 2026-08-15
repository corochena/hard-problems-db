---
title: Rebote en plano inclinado
author: Irodov
difficulty: medium
tags:
  - physics
  - parabolic motion
  - kinematics
---

# Rebote en plano inclinado

**Fuente/Autor:**  *I.E. Irodov - Problemas de Fisica General*

## Enunciado
Una bola inicia su caida, siendo nula su velocidad inicial, sobre un plano inclinado liso que forma un angulo $\alpha$ con el horizonte. Despues de cubrir la distancia $h$, ella rebota elasticamente del plano. ¿A que distancia del primer lugar rebota la segunda vez?

## Solucion

### 1. Velocidad $v$ y Angulo inicial de disparo $\theta$

Calculamos el angulo $\theta$ respecto a la horizontal con que rebota la bola:
$$
\theta = \frac{\pi}{2} - 2\alpha
$$

Velocidad inicial $v$
$$
v=\sqrt{2gh}
$$

### 2. Ecuacion de la parabola y del plano inclinado

La ecuacion de la parabola es:
$$
y = xtan\theta - \frac{g}{2(vcos\theta)^2}x^2
$$

La ecuacion del plano inclinado es:
$$
y = -xtan\alpha
$$

### 3. Identidades trigonometricas usadas

Usaremos varias identidades trigonometricas para resolver las ecuaciones:
$$
cos\left(\frac{\pi}{2}-\theta\right) = sen\theta
$$

$$
tan\left(\frac{\pi}{2}-\theta\right) = \frac{1}{tan\theta}
$$

$$
cos2\theta = 2cos^2\theta - 1 = 1 - 2sen^2\theta
$$

$$
sen2\theta = 2sen\theta cos\theta
$$


### 4. Punto de interseccion de la parabola y la recta

Resolviendo el sistema de ecuaciones y usando las identidades trigonometricas tenemos:

$$
-xtan\alpha = \frac{x}{tan2\alpha} - \frac{g}{2v^2 sen^2{2\alpha}}x^2
$$

Reemplazando $v$ y ordenando:

$$
x\left(tan\alpha + \frac{1}{tan2\alpha}\right) = \frac{g}{4gh sen^2{2\alpha}}x^2
$$

Simplificando y despejando $x$:

$$
x = 4hsen^2{2\alpha}\left(tan\alpha + \frac{1}{tan{2\alpha}}\right)
$$

### 5. Encontrando la distancia alcanzada

Usando el teorema de Pitagoras y la ecuacion de la recta (plano inclinado)

$$
d^2 = x^2 + y^2 = x^2 + x^2 tan^2\alpha = x^2(1+tan^2\alpha) = x^2 sec^2\alpha
$$

$$
d = \frac{x}{cos\alpha}
$$

Sustituyendo $x$

$$
d = 4h\frac{sen^2{2\alpha}}{cos\alpha}\left(tan\alpha + \frac{1}{tan{2\alpha}}\right)
$$

Simplificando

$$
d = 4h(4sen^2\alpha cos^2\alpha) \left(\frac{sen\alpha}{cos\alpha} + \frac{cos2\alpha}{sen2\alpha}\right)\frac{1}{cos\alpha}
$$

$$
d = 16hsen\alpha\left(sen^2\alpha + \frac{cos2\alpha}{2}\right)
$$

$$
d = 16hsen\alpha\left(sen^2\alpha + \frac{1-2sin^2\alpha}{2}\right)
$$

$$
d = 8hsen\alpha
$$

### 6. Geogebra
<iframe src="https://www.geogebra.org/calculator/fvmh8bqp?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

### 7. Problemas relacionados
- [[irodov-1.9| Arrastre minimo]]
- [[irodov-1.11| Distancia en movimiento parabolico]]