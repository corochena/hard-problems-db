---
titulo: Dardo lanzado al azar
autor: Larson
dificultad: media
tags:
  - probabilidad
  - integracion
  - calculo
---

**Fuente/Autor:**  *Larson - Calculo*

## Enunciado
Un dardo, lanzado al azar, golpea un objetivo cuadrado. Asumiendo que dos partes cualesquiera de igual area son igualmente probables de ser golpeadas, encuentre la probabilidad que el punto golpeado este mas cerca del centro que de cualquier borde. Escriba su respuesta en la forma $\frac{a\sqrt{b} + c}{d}$ donde $a, b, c$, y $d$ son enteros positivos.

## Solucion

### 1. Probabilidad
Tenemos que definir y calcular el area de la region donde los dardos caen mas cerca del centro que de cualquiera de sus bordes. La probabilidad seria dicha area dividida entre el area total del cuadrado.

### 2. Condicion para que este mas cerca del centro que del borde

Sea $P=(x,y)$ el punto donde cae el dardo, el borde derecho del cuadrado esta en $x=1$ y el cuadrado tiene su centro en $(0,0)$, entonces la distancia al centro seria:

$$
d=\sqrt{x^2+y^2}
$$

La linea que delimita la region donde los dardos caen mas cerca del centro que del borde seria:

$$
1-x=\sqrt{x^2+y^2}
$$

Que simplificada seria:

$$
x = \frac{1-y^2}{2}
$$

### 3. Calculo del area mediante una integral

Aprovechando la simetria, el area cercana al circulo seria:

$$
A = 8\left(\int_{0}^{L}xdy-\frac{1}{2}L^2\right)
$$

### 4. El limite L de la integral
$L$ es el punto en la curva donde $x=y=L$, resolviendo obtenemos

$$
L = \frac{1-L^2}{2}
$$

$$
L=\sqrt{2}-1
$$

### 4. Resolviendo la integral

$$
A = 8\left(\int_{0}^{L}\frac{1-y^2}{2}dy-\frac{1}{2}L^2\right)
$$

$$
A = 8\left(\left[\frac{1}{2}y-\frac{y^3}{6}\right]_0^L-\frac{1}{2}L^2\right)
$$

Sustituyendo $L$

$$
A = 8\left(\frac{\sqrt{2}}{2}-\frac{1}{2}-\frac{(\sqrt{2}-1)^3}{6}-\frac{3}{2}+\sqrt{2}\right)
$$

Simplificando y Calculando la probabilidad

$$
P = \frac{8A}{4} = 2A = \frac{4\sqrt{2}-5}{3}
$$

$$
P \approx 0.21895
$$

### 5. Solucion en Geogebra

<iframe src="https://www.geogebra.org/calculator/fadbxkgt?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

### 6. Problemas relacionados
