---
titulo: Esferas cargadas colgadas en presencia de campo eléctrico
autor: Sears/Zemansky
dificultad: media
tags:
  - fisica
  - ley de coulomb
  - vectores
  - trigonometria
---

# Esferas cargadas colgadas en presencia de campo eléctrico

**Fuente/Autor:**  *Sears/Zemansky - Fisica Universitaria*

## Enunciado
Dos esferas diminutas de masa $m$ tienen cargas iguales pero opuestas de magnitud $q$. Se atan al mismo gancho del techo con cuerdas ligeras de longitud $L$. Cuando se activa un campo eléctrico horizontal y uniforme $E$, las esferas cuelgan con un ángulo $\theta$ entre las cuerdas. Encuentre el ángulo $\theta$ entre las cuerdas en términos de $E$, $q$, $m$, $L$ y $g$.

## Solucion

### 1. Estrategia
Establecemos la condición de equilibrio para las cargas tomando en cuenta las fuerzas eléctricas causadas por el campo eléctrico y la otra carga, además del peso y la tensión de la cuerda. 

### 2. Condición de Equilibrio
Cuando las cargas están en equilibrio la fuerza neta que actúa sobre ellas es cero. 
$$
\sum \vec F = 0
$$
La fuerza neta es la suma vectorial de la tensión de la cuerda, el peso de la partícula, la fuerza causada por el campo eléctrico y la fuerza de atracción causada por la otra carga.

Descomponiendo las fuerzas en componentes X e Y obtenemos las ecuaciones:

$$
\sum \vec F_x = 0 \quad, \quad \sum \vec F_y = 0
$$

$$
qE = k \frac{q^2}{R^2} + T_x \quad, \quad T_y = mg
$$

Donde $T_x$, $T_y$ son las componentes horizontal y vertical de la tensión y $R$ es la separación entre las cargas

### 3. Reducir a una sola ecuación
Establecemos $R$ en términos de $L$ y $\theta$, encontramos la tensión $T$ y obtenemos una sola ecuación en función de $\theta$

$$
R = 2L\,sen\frac{\theta}{2}
$$

$$
T = \frac{mg}{cos\frac{\theta}{2}}
$$

Usemos el ángulo $\alpha = \theta/2$
$$
qE = k\frac{q^2}{4L^2sen^2\alpha} + mgtan\alpha
$$

### 4. Conversión a una cúbica
Organicemos la ecuación mediante identidades trigonométricas

Multiplicando por $\tan^2\alpha$
$$
qE\,tan^2\alpha = \frac{k\,q^2}{4L^2cos^2\alpha} + mg\,tan^3\alpha
$$

Cambiando coseno por secante
$$
qE\,tan^2\alpha = \frac{k\,q^2}{4L^2}sec^2\alpha + mg\,tan^3\alpha
$$

Cambiando $sec^2\alpha$ por $tan^2\alpha$ y ordenando
$$
qE\,tan^2\alpha = \frac{k\,q^2}{4L^2}(1 + tan^2\alpha) + mg\,tan^3\alpha
$$

$$
mg\,tan^3\alpha + \left( \frac{kq^2}{4L^2} - qE \right)tan^2\alpha + \frac{kq^2}{4L^2} = 0
$$

Usemos las variables $x=tan\alpha$, $a=mg$, $b=\left( \frac{kq^2}{4L^2} - qE \right)$ y $c=kq^2 / 4L^2$ y obtenemos la cúbica

$$
ax^3 + bx^2 + c = 0
$$

La ecuación anterior la podemos resolver y a partir de $x$ conseguir el ángulo $\theta$ buscado

$$
\theta = 2tan^{-1}x
$$

### Solución en Geogebra
<iframe src="https://www.geogebra.org/calculator/zxbsf2sk?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

### Problemas relacionados
- [[savchenko-6.1.8.md| Cuatro cargas formando un rombo]]
