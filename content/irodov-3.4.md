---
titulo: Equilibrio de fuerzas en 3 cargas puntuales
autor: Irodov
dificultad: media
tags:
  - fisica
  - vectores
  - ley de coulomb
---

# Equilibrio de fuerzas en 3 cargas puntuales

**Fuente/Autor:**  *I.E. Irodov - Problemas de Fisica General*

## Enunciado
En los puntos que se definen por los radios vectores $\vec{r_1}$ y $\vec{r_2}$ se encuentran dos cargas positivas $q_1$ y $q_2$. Determinar la carga negativa $q_3$ y el radio vector $\vec{r_3}$ del punto en el cual hay que ponerla, para que la fuerza que actúa sobre cada una de estas tres cargas sea igual a cero.

## Solucion

### 1. Estrategia
Deducimos que la carga debe ser negativa y estar colocada en el segmento que une las cargas positivas. Calcularemos las fuerzas que actúan en cada carga y veremos bajo que condición se hacen cero.

### 2. Suma de fuerzas en $q_3$
Sea $d$ la distancia entre las cargas $q_1$ y $q_2$, $x_1$ la distancia entre $q_1$ y $q_3$ y $x_2$ la distancia entre $q_2$ y $q_3$

Se cumple que
$$
1) \quad x_1 + x_2 = d
$$

Para que la suma de fuerzas en $q3$ sea cero, debe cumplirse:

$$
2) \quad k\frac{q_1 q_3}{x_1^2} = k\frac{q_2 q_3}{x_2^2}
$$

Despejando obtenemos

$$
x_1 = \sqrt{\frac{q_1}{q_2}}\,x_2
$$

Sustituyendo en 1) y resolviendo

$$
\left( \sqrt{\frac{q_1}{q_2}} + 1 \right)x_2 = d
$$

$$
x_2 = \frac{\sqrt{q_2}}{\sqrt{q_1} + \sqrt{q_2}}d
$$

Similarmente para $x_1$

$$
x_1 = \frac{\sqrt{q_1}}{\sqrt{q_1} + \sqrt{q_2}}d
$$

### 3. Posición de $q_3$
Para obtener el vector posición de $q_3$

$$
\vec{r_3} = \vec{r_1} + \frac{x_1}{d}(\vec{r_2} - \vec{r_1})
$$

Sustituyendo $x_1$ obtenemos

$$
\vec{r_3} = \frac{\sqrt{q_2}\vec{r_1} + \sqrt{q_1}\vec{r_2}}{\sqrt{q_1} + \sqrt{q_2}}
$$

### 4. Magnitud de $q_3$
Se debe cumplir que sobre las otras dos cargas $q_1$ y $q_2$ la fuerza neta debe ser también cero.

Sobre $q_1$

$$
k\frac{q_1 q_3}{x_1^2} = k\frac{q_1 q_2}{d_2^2}
$$

$$
q_3 = \left( \frac{x_1}{d} \right)^2
$$

Reemplazando $x_1$ obtenemos

$$
q_3 = \frac{q_1 q_2}{(\sqrt{q_1} + \sqrt{q_2})^2}
$$

---

## Solución en GeoGebra
En la solución en GeoGebra se ve claramente que $q_3$ queda ubicado en la recta que une las cargas 1 y 2. Además se comprueba que la fuerza neta en cada carga es cero.

<iframe src="https://www.geogebra.org/calculator/hck83hac?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>


## Problemas relacionados
- [[sears-zemansky-21.84| Esferas cargadas colgadas en presencia de campo eléctrico]]
- [[savchenko-6.1.8| Cuatro cargas formando un rombo]]