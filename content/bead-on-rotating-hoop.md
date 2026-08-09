\---

title: Bead on a Rotating Hoop

date: 2026-08-09

tags:

&#x20; - physics/classical-mechanics

&#x20; - lagrangian

&#x20; - bifurcation

difficulty: Hard

key\_insight: "The steady-state angle depends on the dimensionless parameter parameter omega^2 \* R / g, exhibiting a pitchfork bifurcation."

\---



\## 📌 Problem Statement



A small bead of mass $m$ is constrained to slide without friction along a wire hoop of radius $R$. The hoop rotates about its vertical diameter with a constant angular velocity $\\omega$. 



1\. Find the Lagrangian of the system in terms of the angle $\\theta$ measured from the bottom vertical.

2\. Determine the equilibrium positions $\\theta\_0$ and analyze their stability.



\---



\## 💡 Key Insights \& Hints



\- Express the position of the bead in cylindrical or Cartesian coordinates before writing kinetic energy $T$.

\- Pay attention to the effective potential $V\_{\\text{eff}}(\\theta)$ when examining stability.



\---



\## 🧮 Complete Derivation \& Solution



\### 1. Kinetic and Potential Energy



The position of the bead relative to the hoop's center is given by:

$$x = R \\sin\\theta \\cos(\\omega t)$$

$$y = R \\sin\\theta \\sin(\\omega t)$$

$$z = -R \\cos\\theta$$



Differentiating with respect to time yields the velocity components, leading to kinetic energy $T$:

$$T = \frac{1}{2}m R^2 \left( \dot{\theta}^2 + \omega^2 \sin^2\theta \right)$$



The potential energy $V$ is purely gravitational:

$$V = -mgR \\cos\\theta$$



\### 2. Lagrangian and Equations of Motion



The Lagrangian $L = T - V$ is:

$$L(\\theta, \\dot{\\theta}) = \\frac{1}{2}m R^2 \\dot{\\theta}^2 + \\frac{1}{2}m R^2 \\omega^2 \\sin^2\\theta + mgR \\cos\\theta$$



Applying the Euler-Lagrange equation $\\frac{d}{dt}\\left(\\frac{\\partial L}{\\partial \\dot{\\theta}}\\right) - \\frac{\\partial L}{\\partial \\theta} = 0$:



$$\\ddot{\\theta} - \\sin\\theta \\left( \\omega^2 \\cos\\theta - \\frac{g}{R} \\right) = 0$$



\---



\## 💻 Simulation Code (Python)



```python

import numpy as np

import matplotlib.pyplot as plt



def effective\_potential(theta, omega, R, g=9.81):

&#x20;   return -m \* g \* R \* np.cos(theta) - 0.5 \* m \* (R \* omega)\*\*2 \* np.sin(theta)\*\*2



\# Parameters

R = 0.5  # meters

g = 9.81

omega\_crit = np.sqrt(g / R)



print(f"Critical Angular Velocity: {omega\_crit:.2f} rad/s")

