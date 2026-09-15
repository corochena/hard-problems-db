---
titulo: Esfera cargada con cavidad esférica
autor: Sears/Zemansky
dificultad: media
tags:
  - fisica
  - superposición
  - vectores
  - campo electrico
---

# Esfera cargada con cavidad esférica

**Fuente/Autor:**  *Sears/Zemansky - Fisica Universitaria*

## Enunciado
a) Una esfera aislante con radio $a$ tiene una densidad de carga uniforme $\rho$. La esfera no está centrada en el origen, sino en $\vec{r} = \vec{b}$. Demuestre que el campo eléctrico en el interior de la esfera está dado por $\vec{E} = \rho (\vec{r} - \vec{b}) / 3\epsilon_0$. b) Una esfera aislante de radio R tiene un agujero esférico de radio $a$ ubicado dentro de su volumen y con centro a una distancia $b$ del centro de la esfera, donde $a<b<R$ (en la figura se muestra una sección transversal de la esfera). La parte sólida de la esfera tiene una densidad volumétrica de carga uniforme $\rho$. Obtenga la magnitud y dirección del campo eléctrico $\vec{E}$ dentro del agujero, y demuestre que $\vec{E}$ es uniforme en todo el agujero. [Sugerencia: use el principio de superposición y el resultado del inciso a).]

<p align="center">
  <img src="assets/sears-zemansky 22-61.jpg" alt="Esfera cargada con cavidad esférica"  width="200">
</p>

## Solucion

### 1. Estrategia
El problema nos muestra el camino a seguir para encontrar el interesante resultado del inciso b. Sin la pregunta del inciso a sería mucho más difícil encontrar la parte b.

### 2. Campo eléctrico en el interior de una esfera cargada uniformemente con centro en (0,0)
Usando la Ley de Gauss 

$$
\Phi = \frac{Q_{enc}}{\epsilon_0}
$$

$$
\Phi = EA = E(4\pi r^2)
$$
La dirección de $\vec{E}$ es radial y $r$ es el radio de la superficie gaussiana

$$
Q_{enc} = \rho V = \rho(\frac{4}{3} \pi r^3)
$$

Por lo tanto
$$
E(4\pi r^2) = \rho(\frac{4}{3 \epsilon_0} \pi r^3)
$$

Despejando $E$ obtenemos

$$
\vec{E} = \frac{\rho \vec{r}}{3 \epsilon_0}
$$

### 3. Cuando el centro de la esfera no está en el origen
El campo eléctrico debe estar dirigido de forma radial respecto al centro de la esfera, en un punto definido por el vector $\vec{r}$, $\vec{E}$ debe ser paralelo al vector $\vec{r} - \vec{b}$, por lo tanto 

$$
\vec{E} = \frac{\vec{r} - \vec{b}}{|\vec{r} - \vec{b}|} \frac{\rho |\vec{r} - \vec{b}|}{3 \epsilon_0} = \frac{\rho (\vec{r}-\vec{b})}{3 \epsilon_0}
$$

### 4. Superposición
Aplicando superposición el campo dentro de la cavidad es equivalente al campo de la esfera grande completa con carga positiva más el campo causado por una esfera con carga negativa en la cavidad

$$
\vec{E_{net}} = \frac{\rho \vec{r}}{3 \epsilon_0} - \frac{\rho (\vec{r}-\vec{b})}{3 \epsilon_0}
$$

$$
\vec{E_{net}} = \frac{\rho \vec{b}}{3 \epsilon_0}
$$

El campo eléctrico es uniforme y tiene la dirección de $\vec{b}$

### Solución en Geogebra



### Problemas relacionados
- [[savchenko-6.1.8.md| Cuatro cargas formando un rombo]]
