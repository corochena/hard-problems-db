---
title: Altura de vuelo
author: Savchenko
difficulty: medium
tags:
  - fisica
  - movimiento parabolico
  - cinematica
  - ecuaciones parametricas
---

# Altura de vuelo

**Fuente/Autor:**  *Savchenko - Problemas de Fisica*

## Enunciado
Un pato volaba por una recta horizontal a la velocidad constante $u$. Un cazador inexperto le lanzó una piedra, con la particularidad de que el lanzamiento fue hecho sin corrección del avance, es decir, en el momento del lanzamiento la dirección de la velocidad de la piedra (el ángulo $\alpha$ respecto al horizonte) estaba orientada precisamente hacia el pato. El módulo de la velocidad inicial de la piedra es igual a $v$ ¿A qué altura volaba el pato, si la piedra, a pesar de todo, dió con él? 

## Solucion

### 1. Estrategia
Usaremos ecuaciones paramétricas de $x$ y $y$ para la piedra y para el pato, además de establecer la relación entre el ángulo de disparo y la altura de vuelo del pato.

### 2. Ecuaciones paramétricas

Ecuaciones paramétricas del pato:

$$
x=L+ut, \quad y=h
$$

Ecuaciones paramétricas de la piedra
$$
x=vcos\alpha\;t, \quad y=vsen\alpha\;t - \frac{1}{2}gt^2
$$

### 3. Condición de choque
Para que la piedra choque contra el pato sus coordenadas $x$ e $y$ deben ser iguales para el mismo valor de $t$, por lo tanto deben cumplirse las siguientes ecuaciones:

$$
(1) \quad L+ut = vcos\alpha\;t
$$

$$
(2) \quad vsen\alpha\;t - \frac{1}{2}gt^2 = h
$$

### 4. Desarrollo algebraico
Despejamos t de la ecuación $(1)$ y reemplazamos en la ecuación $(2)$

$$
t = \frac{h}{tan\alpha(vcos\alpha-u)}
$$

$$
\frac{(vsen\alpha)h}{tan\alpha(vcos\alpha-u)} - \frac{gh^2}{2tan^2\alpha(vcos\alpha-u)^2}=h
$$

<details>
<summary>Clic para ver los pasos intermedios del despeje</summary>

<hr>

$$
\frac{vsen\alpha}{tan\alpha(vcos\alpha-u)}-1=\frac{g}{2tan^2\alpha(vcos\alpha-u)}h
$$

$$
\frac{vsen\alpha-tan\alpha(vcos\alpha-u)}{tan\alpha(vcos\alpha-u)}=\frac{g}{2tan^2\alpha(vcos\alpha-u)}h
$$

$$
h=\frac{2tan\alpha(vcos\alpha-u)\;utan\alpha}{g}
$$

</details>
<hr>
Dividiendo entre h y despejando obtenemos:

$$
h=\frac{2utan^2\alpha(vcos\alpha-u)}{g}
$$

## Solución en Geogebra
<iframe src="https://www.geogebra.org/calculator/byrrhdd7?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

## Problemas relacionados
- [[irodov-1.11| Distancia en movimiento parabólico]]
- [[irodov-1.31| Rebote en plano inclinado]]
- [[irodov-1.32| Tiempo de vuelo]]
- [[irodov-1.33| Tiempo de retraso]]