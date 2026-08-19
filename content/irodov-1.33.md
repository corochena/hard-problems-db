---
titulo: Tiempo de retraso
autor: Irodov
dificultad: media
tags:
  - fisica
  - movimiento parabolico
  - cinematica
  - trigonometria
---

# Tiempo de retraso

**Fuente/Autor:**  *I.E. Irodov - Problemas de Fisica General*

## Enunciado
De un cañon fueron disparados dos proyectiles seguidos con una velocidad $v_0 = 250\; m/s$ el primero a un angulo de $\theta_1 = 60°$ hacia el horizonte; el segundo, a un angulo $\theta_2 = 45°$ (el azimut es el mismo). Despreciando la resistencia del aire, hallar el intervalo de tiempo entre los disparos que asegure que los proyectiles choquen. 

## Solucion

### 1. Estrategia
Usaremos ecuaciones paramétricas de $x$ y $y$ y a partir de ellas encontraremos el tiempo de retraso $\tau$ y el tiempo de vuelo $t$

### 2. Ecuaciones paramétricas
Sea $\theta_1 = \alpha$ , $\theta_2 = \beta$

Entonces
$$
x_1 = (v_0cos\alpha)t, \quad y_1 = (v_0sen\alpha)t - \frac{1}{2}gt^2
$$

$$
x_2 = (v_0cos\beta)(t-\tau), \quad y_2 = (v_0sen\beta)(t-\tau) - \frac{1}{2}g(t-\tau)^2
$$

### 3. Condición de choque
Para que las partículas choquen deben estar en la misma posición en el mismo tiempo, es decir para un tiempo $t$ se debe cumplir que $x_1 = x_2$ y $y_1 = y_2$

$$
(v_0cos\alpha)t = (v_0cos\beta)(t-\tau)
$$

Resolviendo para $t$
$$
t = \frac{\tau \, cos\beta}{cos\beta - cos\alpha}
$$

Con la segunda ecuación obtendremos $\tau$

$$
(v_0sen\alpha)t - \frac{1}{2}gt^2 = (v_0sen\beta)(t-\tau) - \frac{1}{2}g(t-\tau)^2
$$

### 4. Desarrollo algebraico
Expandimos el binomio
$$
v_0 sen\alpha \; t = v_0 sen\beta \; t - v_0 sen\beta \; \tau + gt\tau - \frac{1}{2}g\tau^2 
$$

Sustituimos $t$
$$
\frac{v_0 sen\alpha cos\beta}{cos\beta - cos\alpha}\tau = \frac{v_0 sen\beta cos\beta}{cos\beta - cos\alpha}\tau - v_0 sen\beta \; \tau + \frac{gcos\beta}{cos\beta-cos\alpha}\tau^2 - \frac{1}{2}g\tau^2
$$

Dividiendo entre $\tau$ y despejando
$$
\tau = \frac{2v_0}{g} \frac{sen\alpha cos\beta - cos\alpha sen\beta}{cos\alpha + cos\beta}
$$

Usando la identidad trigonométrica
$$
sen(\alpha - \beta) = sen\alpha cos\beta - cos\alpha sen\beta
$$

Llegamos a la respuesta

$$
\tau = \frac{2v_0}{g} \frac{sen(\alpha - \beta)}{cos\alpha + cos\beta}
$$

### 6. Geogebra
<iframe src="https://www.geogebra.org/calculator/mpunxerz?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

### 7. Problemas relacionados
- [[irodov-1.31| Rebote en plano inclinado]]
- [[irodov-1.11| Distancia en movimiento parabolico]]
- [[irodov-1.32| Tiempo de vuelo]]