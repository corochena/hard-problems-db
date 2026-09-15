---
titulo: Flujo a través de disco
autor: Serway
dificultad: media
tags:
  - física
  - flujo eléctrico
  - integrales
  - sustitución trigonométrica
  - ley de gauss
---

# Flujo a través de disco

**Fuente/Autor:**  *Serway - Física para científicos e ingenieros*

## Enunciado
Una carga puntual $Q$ esta ubicada en el eje de un disco de radio $R$ a una distancia $b$ del plano del disco. Muestre que si un cuarto del flujo eléctrico de la carga pasa a través del disco, entonces $R=\sqrt{3}b$

<p align="center">
  <img src="assets/serway 24-68.jpg" alt="Carga puntual y disco circular"  width="300">
</p>

### 1. Estrategia
Para calcular el flujo a través del disco integraremos mediante sustitución trigonométrica

### 2. Ley de Gauss
El flujo eléctrico a través de una superficie cerrada es igual a la carga neta encerrada dividida entre $\epsilon_{0}$

$$
\Phi = \frac{Q_{enc}}{\epsilon_{0}}
$$

Tomaremos la cuarta parte de ese valor

### 3. Flujo a través del disco
Esta es la parte pesada del problema ya que debemos integrar. El diagrama del problema se vuelve clave ya que a partir de el establecemos las ecuaciones necesarias.

$$
\Phi = \int{\vec{E} \cdot d\vec{A}} = \frac{Q}{4\epsilon_0}
$$


### 4. Campo Eléctrico de una carga puntual
Magnitud del Campo Eléctrico de una carga puntual

$$
E = \frac{1}{4\pi \epsilon_0} \frac{Q}{r^2}
$$

### 5. Simetría
A una distancia $x$ del centro del círculo el campo $E$ tiene la misma magnitud

$$
d\Phi = E_y dA
$$

donde $E_y$ es la componente vertical del campo eléctrico $E$

$$
d\Phi = E_y \; 2\pi x \,dx
$$

$$
d\Phi = E cos\theta \; 2\pi x \,dx
$$

donde 

$$
tan\theta = \frac{x}{b}
$$

### 6. Integral y Ecuación
Conectemos todas las relaciones para obtener la ecuación

$$
\int \frac{1}{4\pi \epsilon_0} \frac{Q}{r^2} \, cos\theta \; 2\pi x \,dx = \frac{Q}{4\epsilon_0}
$$

Simplificando

$$
\int \frac{cos\theta}{r^2} \; x \,dx = \frac{1}{2}
$$

$$
r = b \, sec\theta, \quad x = b \, tan\theta, \quad dx = b \, sec^2\theta d\theta
$$

Sustituyendo

$$
\int \frac{cos\theta}{b^2 sec^2 \theta} \; b \, tan\theta \, b \, sec^2\theta d\theta = \frac{1}{2}
$$

Simplificando 

$$
\int_{0}^{\theta} sen\theta = \frac{1}{2}
$$

$$
\left[ -cos\theta \right]_{0}^{\theta} = \frac{1}{2}
$$

$$
1 - cos\theta = \frac{1}{2}
$$

$$
cos\theta = \frac{1}{2}
$$

### 7. Relación de $b$ y $R$

$$
cos\theta = \frac{b}{\sqrt{b^2 + R^2}} = \frac{1}{2}
$$

Resolviendo esta ecuación obtenemos

$$
R = \sqrt{3}b
$$

## Solución en GeoGebra
En la vista 3D se aprecian bien los vectores, ángulos y dimensiones del problema.

<iframe src="https://www.geogebra.org/calculator/quepcphv?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

