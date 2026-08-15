---
title: Distancia en movimiento parabolico
author: Irodov
difficulty: low
tags:
  - fisica
  - vectores
  - cinematica
  - trigonometria
---

# Distancia en movimiento parabolico

**Fuente/Autor:**  *I.E. Irodov - Problemas de Fisica General*

## Enunciado
Dos particulas se mueven en un campo de gravedad homogeneo con una aceleracion igual a $g$. En el momento inicial ellas se encontraban en un mismo punto y sus velocidades dirigidas horizontalmente y en sentidos opuestos eran $v_1=3\; m/s$ y $v_2=4\;m/s$. Hallar la distancia entre las particulas en el momento, en que los vectores de sus velocidades resulten ser mutuamente perpendiculares.

## Solucion

### 0. Ideas claves
La velocidad $v_y$ es cero para ambas particulas en el momento inicial.
La velocidad $v_x$ se mantiene constante para ambas particulas.
Podemos encontrar la direccion del movimiento con las componentes $v_x$ y $v_y$ y verificar si son perpendiculares con una propiedad trigonometrica.

### 1. Dirección de las velocidades
Usando la función trigonométrica tangente:

$$
tan\alpha_1 = \frac{v_{y1}}{v_{x1}} = \frac{gt}{v_1}
$$

$$
tan\alpha_2 = \frac{v_{y2}}{v_{x2}} = \frac{gt}{v_2}
$$

### 2. Condicion de perpendicularidad
Cuando los vectores velocidad sean mutuamente perpendiculares se cumple:

$$
\alpha_1 + \alpha_2 = 90
$$

$$
\alpha_1 = 90 - \alpha_2
$$

### 3. Propiedad trigonometrica de la tangente
Aplicando tangente a ambos lados obtenemos

$$
tan(\alpha_1) = tan(90 - \alpha_2) = \frac{1}{tan(\alpha_2)}
$$

### 4. Sustituyendo y resolviendo para $t$

$$
\frac{gt}{v_1} = \frac{1}{\frac{gt}{v_2}} = \frac{v_2}{gt}
$$

$$
t = \frac{\sqrt{v_1v_2}}{g}
$$

### 5. Distancia horizontal recorrida
Siendo que la velocidad horizontal es constante solo basta multiplicar velocidad total por tiempo

$$
d = (v_1 + v_2)\frac{\sqrt{v_1v_2}}{g}
$$

### Solucion en Geogebra

<iframe src="https://www.geogebra.org/calculator/d6dtdvks?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

## Problemas relacionados
- [[irodov-1.9| Arrastre minimo en rio]]
- [[irodov-1.31| Rebote en plano inclinado]]