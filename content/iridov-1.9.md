---
title: Arrastre minimo en rio
author: Irodov
difficulty: low
tags:
  - physics
  - vectors
  - kinematics
---

# Arrastre mínimo en rio

**Fuente/Autor:**  *I.E. Irodov - Problemas de Fisica General*

## Enunciado
Un bote navega por un rio a una velocidad que es $n = 2$ veces menor que la de la corriente de este. Que angulo respecto a la corriente debe mantener el bote, para que esta lo arrastre lo menos posible.

## Solucion

### 1. Vector velocidad resultante
Sumando vectorialmente las velocidades del bote y del rio:
$$
\vec{v}_{bote} = (-v cos\alpha, vsen\alpha),
$$

$$
\vec{v}_{rio} = (2v, 0)
$$

$$
\vec{v}_{resultante} = v(2-cos\alpha, sen\alpha)
$$

### 2. Arrastre del bote
Con la velocidad resultante el bote llegara a la orilla habiendolo arrastrado una distancia $x$.

$$
t = \frac{ancho}{sen\alpha}
$$

$$
x = (2-cos\alpha)vt
$$

$$
x = \frac{(2-cos\alpha)}{sen\alpha}v*ancho
$$

### 3. Funcion del angulo y su valor minimo
$v$ y $ancho$ son constantes, definimos la funcion:

$$
f(\alpha) = \frac{2-cos\alpha}{sen\alpha}
$$

tomando la derivada:

$$
f'(\alpha) = \frac{sen^2\alpha - 2cos\alpha + cos^2\alpha}{sen^2\alpha}
$$

$$
f'(\alpha) = \frac{1 - 2cos\alpha}{sen^2\alpha}
$$

### 4. Punto critico. Resolviendo la ecuacion trigonometrica.

$$
\frac{1 - 2cos\alpha}{sen^2\alpha} = 0
$$

$$
1 - 2cos\alpha = 0
$$


$$
\alpha = \frac{\pi}{3}
$$
---

## Solucion Geogebra
<iframe src="https://www.geogebra.org/calculator/awfbhsmh?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0">
</iframe>


## Problemas relacionados
- [[simple-harmonic-oscillator|Simple Harmonic Oscillator]]
- [[double-pendulum-chaos|Pendulo doble caos]]