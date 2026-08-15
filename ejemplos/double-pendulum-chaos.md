---
title: Double Pendulum Chaos & Lagrangian Dynamics
date: 2026-08-09
tags:
  - physics
  - mechanics
  - lagrangian
  - chaos
draft: false
enableToc: true
---

📌 Problem Statement

Consider a double pendulum consisting of two point masses $m_1$ and $m_2$ connected by rigid, massless rods of lengths $l_1$ and $l_2$ under uniform gravity $g$.

1. Express the position coordinates $(x_1, y_1)$ and $(x_2, y_2)$ in terms of the angular coordinates $\theta_1$ and $\theta_2$.
2. Formulate the total Kinetic Energy $T$ and Potential Energy $V$.
3. Write down the Lagrangian $\mathcal{L} = T - V$.

---

📐 Derivation & Solution

### 1. Position Coordinates

Taking the pivot point as the origin $(0,0)$:

$$x_1 = l_1 \sin\theta_1, \quad y_1 = -l_1 \cos\theta_1$$

$$x_2 = l_1 \sin\theta_1 + l_2 \sin\theta_2, \quad y_2 = -l_1 \cos\theta_1 - l_2 \cos\theta_2$$

### 2. Kinetic & Potential Energy

Differentiating position with respect to time gives the velocities. The total kinetic energy $T$ of the system is:

$$T = \frac{1}{2} m_1 l_1^2 \dot{\theta}_1^2 + \frac{1}{2} m_2 \left[ l_1^2 \dot{\theta}_1^2 + l_2^2 \dot{\theta}_2^2 + 2 l_1 l_2 \dot{\theta}_1 \dot{\theta}_2 \cos(\theta_1 - \theta_2) \right]$$

The potential energy $V$ relative to the pivot line:

$$V = -(m_1 + m_2) g l_1 \cos\theta_1 - m_2 g l_2 \cos\theta_2$$

### 3. The Lagrangian

Combining both energy terms into $\mathcal{L} = T - V$:

$$\mathcal{L} = \frac{1}{2}(m_1 + m_2)l_1^2\dot{\theta}_1^2 + \frac{1}{2}m_2 l_2^2\dot{\theta}_2^2 + m_2 l_1 l_2 \dot{\theta}_1\dot{\theta}_2\cos(\theta_1-\theta_2) + (m_1+m_2)g l_1\cos\theta_1 + m_2 g l_2\cos\theta_2$$

---

🔗 Related Notes

* [[bead-on-rotating-hoop|Bead on a Rotating Hoop]]
* [[simple-harmonic-oscillator|Simple Harmonic Oscillator]]