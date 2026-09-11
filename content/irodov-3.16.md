---
titulo: Campo eléctrico en centro de cascarón esférico
autor: Irodov
dificultad: alta
tags:
  - fisica
  - integrales
  - campo eléctrico
  - distribución de carga
---

# Campo eléctrico en centro de cascarón esférico

**Fuente/Autor:**  *I.E. Irodov - Problemas de Fisica General*

## Enunciado
Una esfera de radio $r$ tiene una densidad superficial de la carga $\sigma = \vec{a} \cdot \vec{r}$, donde $\vec{a}$ es un vector constante y $\vec{r}$, el radio vector de un punto de la esfera respecto a su centro. Determinar el vector de la intensidad del campo eléctrico en el centro de la esfera.

## Solucion

### 1. Estrategia
Usaremos la fórmula del campo eléctrico para un anillo con carga teniendo cuidado de orientar los aros para que sus ejes coincidan con la direccion del vector $\vec{a}$.

### 2. Densidad superficial
La densidad superficial está expresada como un producto punto entre un vector constante $\vec{a}$ y el radio vector respecto al centro de la esfera, entonces

$$
\sigma = \vec{a} \cdot \vec{r} = arcos\theta
$$

Es decir, la densidad es la misma para un ángulo $\theta$, por esto podemos usar la fórmula de campo eléctrico para un anillo con carga.

### 3. Planteo de la integral

$$
E = \int_{0}^{\pi} k \frac{x}{(x^2 + y^2)^{3/2}} dq
$$

Donde $x$ es la distancia del centro del aro al centro del cascarón esférico y $y$ es el radio del aro. Se cumple que $x^2 + y^2 = r^2$.

$$
E = \int_{0}^{\pi} k \frac{rcos\theta}{r^3} \sigma dA
$$

Simplificando y sustituyendo $\sigma$

$$
E = \frac{k}{r^2} \int_{0}^{\pi} cos\theta \, arcos\theta \, dA
$$

$$
E = \frac{ka}{r} \int_{0}^{\pi} cos^2\theta \, (2\pi y \,ds)
$$

$$
E = \frac{2\pi ka}{r} \int_{0}^{\pi} cos^2 \theta \, (rsen\theta) \, rd\theta
$$

$$
E = 2\pi kar \int_{0}^{\pi} cos^2 \theta sen\theta \, d\theta
$$

Integrando obtenemos

$$
E = \frac{ar}{3\epsilon_0}
$$

---

## Solución en GeoGebra
En 3D se aprecian todas las vistas que en 2D son difíciles de ver.

<iframe src="https://www.geogebra.org/calculator/m8dfxze5?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>


## Problemas relacionados
- [[sears-zemansky-21.84| Esferas cargadas colgadas en presencia de campo eléctrico]]
- [[savchenko-6.1.8| Cuatro cargas formando un rombo]]