---
titulo: Lazo en cilindro
autor: Savchenko
dificultad: media
tags:
  - fisica
  - cinemática
  - movimiento parabolico
---

# Lazo en cilindro

**Fuente/Autor:**  *Savchenko - Problemas de Fisica*

## Enunciado
Una bola se lanza por la superficie interior de un cilindro vertical liso de radio $R$ bajo un ángulo $\alpha$ respecto a la vertical. ¿Qué velocidad inicial es necesario comunicar a la bola para que retorne a su punto inicial?

## Solucion

### 1. Estrategia
Calculemos el tiempo que le tarda dar una vuelta completa al cilindro y usemos la condicion que la altura de la bola debe ser cero en ese tiempo.

### 2. Tiempo en completar $n$ vueltas
Sea $\tau$ el tiempo que le tomaría a la bola completar una vuelta

$$
\tau = \frac{2\pi\,R}{v\,sen\alpha}
$$

### 3. Condición de regresar al punto de partida
Si la bola inicio en $y=0$ debe regresar a esa altura en el tiempo $n\tau$

$$
vcos\alpha\;t-\frac{1}{2}gt^2 = 0
$$

Sustituyendo $\tau$

$$
vcos\alpha\, \frac{2\pi n R}{vsen\alpha} - \frac{1}{2}g\,\left( \frac{2\pi n R}{vsen\alpha} \right)^2 = 0
$$

Simplificando

$$
\frac{1}{tan\alpha} = \frac{\pi n R g}{v^2 sen^2\alpha}
$$

Obteniendo

$$
v = \sqrt{\frac{2\pi n Rg}{sen2\alpha}}
$$


## Solución en Geogebra

<iframe src="https://www.geogebra.org/calculator/wj3cwtgn?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

## Problemas relacionados
- [[savchenko-1.3.2| Descenso dentro de círculo]]
- [[savchenko-1.3.10| Altura de vuelo]]
- [[savchenko-1.3.13| Alcance de artillería]]

