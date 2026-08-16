---
title: Tiempo de Vuelo
author: Irodov
difficulty: medium
tags:
  - fisica
  - movimiento parabolico
  - cinematica
  - trigonometia
---

# Tiempo de vuelo

**Fuente/Autor:**  *I.E. Irodov - Problemas de Fisica General*

## Enunciado
Un cañon y un blanco se encuentran al mismo nivel y a 5.1 km de distancia el uno del otro. En ausencia de la resistencia del aire ¿al cabo de que tiempo el proyectil dará en el blanco, si su velocidad inicial es de 240 m/s?

## Solucion

### 1. Estrategia
Usaremos la ecuación de la trayectoria parabólica para encontrar el ángulo de disparo con el que calcularemos la componente horizontal de la velocidad y con ella el tiempo de vuelo.

### 2. Ecuación de la trayectoria y ecuación trigonométrica
Ya que el cañón y el blanco se encuentran al mismo nivel, diremos que el cañon está en $(0,0)$ y el blanco en $(L,0)$ , donde $L=5100\;m$

La trayectoria del movimiento parabólico está dada por:

$$
y = xtan\theta - \frac{g}{2(v_0cos\theta)^2}x^2
$$

donde $v_0 = 240\; m/s$ y $g=9.8\;m/s^2$.

Sabemos que debe cumplirse que $y=0$ cuando $x=L$ asi que:

$$
0 = Ltan\theta - \frac{g}{2(v_0cos\theta)^2}L^2
$$

De esta ecuación debemos encontrar el ángulo de disparo $\theta$ siendo $L, v, g$ conocidos. Eliminando $L$ y ordenando obtenemos:

$$
cos^2\theta\, tan\theta = \frac{gL}{2v_0^2}
$$

### 3. Resolviendo la ecuación trigonométrica
Usaremos identidades trigonométricas para resolver la ecuación y encontrar $\theta$:

$$
cos^2\theta \, \frac{sen\theta}{cos\theta} = \frac{gL}{2v_0^2}
$$

$$
2 sen\theta \, {cos\theta} = \frac{gL}{v_0^2}
$$

$$
sen2\theta = \frac{gL}{v_0^2}
$$

$$
2\theta = sen^{-1}\left(\frac{gL}{v_0^2}\right)
$$

Lo cual entrega dos soluciones:

$$
\theta_1 = \frac{1}{2}\,sen^{-1}\left(\frac{gL}{v_0^2}\right) \approx 30.1°
$$

$$
\theta_2 = \frac{\pi}{2}-\theta_1 \approx 59.9°
$$

### 5. Encontrando el tiempo de vuelo
Para encontrarlo dividimos la distancia horizontal recorrida $L$ entre la componente horizontal de la velocidad $v_x$

$$
T = \frac{L}{v_x} = \frac{L}{v_0 \; cos\theta}
$$

Dependiendo del ángulo de disparo obtenemos 

$$
T_1 \approx 24.56 \, seg, \quad T_2 \approx 42.38 \, seg
$$

### 6. Solución alterna (cerrada)
Nuevamente recurrimos a identidades trigonométricas específicamente:

$$
sen^2\theta + cos^2\theta = 1, \quad cos^2\theta = \frac{1+cos2\theta}{2}
$$

Usando la identidad Pitagórica 
$$
cos2\theta = \sqrt{1-\frac{g^2\,L^2}{v_0^4}}
$$

Usando la identidad de ángulo doble
$$
cos^2\theta = \frac{1+\sqrt{1-\frac{g^2\,L^2}{v_0^4}}}{2}
$$

$$
cos^2\theta = \frac{v_0^2+\sqrt{v_0^4-g^2L^2}}{2v_0^2}
$$

$$
cos\theta = \frac{1}{v_0}\sqrt{\frac{v_0^2+\sqrt{v_0^4-g^2L^2}}{2}}
$$

Calculando el tiempo

$$
T = \frac{L}{v_0 \; cos\theta} = L\sqrt{\frac{2}{v_0^2+\sqrt{v_0^4-g^2L^2}}}
$$

$$
T_1 \approx 24.56 \; seg
$$

Sorprendentemente si cambiamos el signo del radical interno obtenemos la otra solución

$$
T_2 = L\sqrt{\frac{2}{v_0^2-\sqrt{v_0^4-g^2L^2}}} \approx 42.38 \; seg
$$


## Geogebra
<iframe src="https://www.geogebra.org/calculator/hf9v6bgd?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

## Problemas relacionados
- [[irodov-1.31| Rebote en plano inclinado]]
- [[irodov-1.11| Distancia en movimiento parabolico]]
- [[irodov-1.33| Tiempo de retraso]]