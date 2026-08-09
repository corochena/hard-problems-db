---
title: Movimiento de proyectiles con Linear Drag
author: Irodov
difficulty: Medium
tags:
  - physics
  - classical-mechanics
  - kinematics
---

# Movimiento de proyectil con Linear Drag

**Source / Author: ** Inspirado por *I.E. Irodov - Problemas de Fisica*

## Enunciado
Una particula de masa $m$ se lanza desde el suelo con velocidad inicial $v_0$ con angulo $\theta$ respecto a la horizontal. Ademas de la gravedad $g$, la particula experimenta una fuerza de resistencia del aire lineal $\vec{F}_d = -b\vec{v}$, donde $b$ es una constante de resistencia del aire.

## Solucion

### 1. Ecuaciones del movimiento
Aplicando la segunda ley de Newton en los ejes horizontal ($x$) y vertical ($y$):

$$m \frac{dv_x}{dt} = -b v_x$$
$$m \frac{dv_y}{dt} = -mg - b v_y$$

### 2. Despejando la velocidad x $v_x(t)$
Separando las variables para la componente horizontal

$$\int_{v_{0x}}^{v_x} \frac{dv_x}{v_x} = -\frac{b}{m} \int_{0}^{t} dt$$

Tomando exponencial en ambos lados da:

$$v_x(t) = v_0\cos\theta \cdot e^{-\frac{b}{m}t}$$

---

## Problemas relacionados
- [[simple-harmonic-oscillator|Simple Harmonic Oscillator]]
- [[double-pendulum-chaos|Pendulo doble caos]]