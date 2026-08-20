---
titulo: Cuatro cargas formando un rombo
autor: Savchenko
dificultad: media
tags:
  - fisica
  - ley de coulomb
  - trigonometria
  - equilibrio
---

# Cuatro cargas formando un rombo

**Fuente/Autor:**  *Savchenko - Problemas de Fisica*

## Enunciado
Cuatro cargas $Q, q, Q, q$ se unen mediante cuatro hilos de longitud $l$ de la manera expuesta en la figura. Determínense los ángulos $\beta$ entre los hilos.

<p align="center">
  <img src="assets/savchenko-6.1.8.jpg" alt="Cuatro cargas atadas con hilos"  width="250">
</p>

## Solucion

### 1. Estrategia
Haremos un diagrama de cuerpo libre (DCL) para la carga $q$ y otro para la carga $Q$, de esas ecuaciones encontraremos $\beta$

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