---
title: Arrastre minimo en rio
author: Irodov
difficulty: low
tags:
  - physics
  - vectors
  - kinematics
---

# Arrastre mínimo en rio

**Fuente/Autor:**  *I.E. Irodov - Problemas de Fisica General*

## Enunciado
Un bote navega por un rio a una velocidad que es $n = 2$ veces menor
que la de la corriente de este. Que angulo respecto a la corriente debe 
mantener el bote, para que esta lo arrastre lo menos posible.

## Solucion

### 1. Ecuaciones del movimiento
Aplicando la segunda ley de Newton en los ejes horizontal ($x$) y vertical ($y$):

$$
m \frac{dv_x}{dt} = -b v_x
$$

$$
m \frac{dv_y}{dt} = -mg - b v_y
$$

### 2. Despejando la velocidad x $v_x(t)$
Separando las variables para la componente horizontal

$$
\int_{v_{0x}}^{v_x} \frac{dv_x}{v_x} = -\frac{b}{m} \int_{0}^{t} dt
$$

Tomando exponencial en ambos lados da:

$$
v_x(t) = v_0\cos\theta \cdot e^{-\frac{b}{m}t}
$$

---

## Problemas relacionados
- [[simple-harmonic-oscillator|Simple Harmonic Oscillator]]
- [[double-pendulum-chaos|Pendulo doble caos]]