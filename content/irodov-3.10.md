---
titulo: Campo eléctrico aro + carga puntual
autor: Irodov
dificultad: media
tags:
  - fisica
  - desarrollo en serie de potencias
  - campo eléctrico
  - cargas puntuales
  - binomio de newton
---

# Campo eléctrico aro + carga puntual

**Fuente/Autor:**  *I.E. Irodov - Problemas de Fisica General*

## Enunciado
En el centro de un anillo fino de radio $R$, en el cual está distribuida uniformemente una carga $-q$, se encuentra una carga puntual $q$. Hallar el módulo del vector de la intensidad del campo eléctrico en un punto del eje del anillo, distante $x$ de su centro, si $x>>R$

## Solucion

### 1. Estrategia
Tenemos fórmulas para el campo eléctrico causado por una carga puntual y por un aro con carga uniformemente distribuida. Sumamos y examinamos que pasa cuando la distancia $x$ es muy larga en comparación con el radio del aro.

### 2. Ecuaciones de Campo Eléctrico

Carga puntual
$$
E = k \frac{q}{r^2}
$$

Aro
$$
E = k \frac{qx}{R^2 + x^2}
$$

Por lo tanto el campo eléctrico neto es
$$
E = kq \left[ \frac{1}{x^2} -\frac{x}{(R^2 + x^2)^{3/2}} \right]
$$

### 3. Aproximación cuando $x>>R$
Desarrollamos el binomio y tomamos solo los términos más significativos

$$
(R^2 + x^2)^{3/2} = x^3 + \frac{3}{2}(x^2)^{1/2}R^2 + ... = x^3 + \frac{3}{2}xR^2
$$

Reemplazando obtenemos 

$$
E = kq \left[ \frac{1}{x^2} - \frac{x}{x^3 + \frac{3}{2}xR^2} \right]
$$

Simplificando

$$
E = \frac{3}{2}k \frac{qR^2}{x^4 + \frac{3}{2}x^2}
$$

Desechando las potencias menores de $x$ y sustituyendo $k=\frac{1}{4\pi \epsilon_0}$ obtenemos

$$
E = \frac{3q}{8\pi \epsilon_0 x^4}
$$

### 4. Comprobación numérica
Si usamos $q = 1\,\mu C, R = 0.1 m, x = 5 m$ obtenemos

$E = 0.2158 \frac{N}{C}$ para la aproximación

Lo que difiere apenas en 0.05% del valor exacto 

---

## Problemas relacionados
- [[sears-zemansky-21.84| Esferas cargadas colgadas en presencia de campo eléctrico]]
- [[savchenko-6.1.8| Cuatro cargas formando un rombo]]