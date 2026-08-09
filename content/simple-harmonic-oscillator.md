---
title: Simple Harmonic Oscillator
date: 2026-08-09
tags:
  - physics
  - mechanics
  - differential-equations
draft: false
enableToc: true
---

## 📌 Problem Statement

A block of mass $m$ is attached to an ideal spring with spring constant $k$ on a frictionless horizontal surface. 

1. Write down the **Hooke's Law** restoring force.
2. Formulate the equation of motion using Newton's Second Law.
3. Solve for the position $x(t)$ given the initial conditions $x(0) = A$ and $\dot{x}(0) = 0$.

---

## 📐 Derivation & Solution

### 1. Differential Equation

The restoring force acting on the mass is given by Hooke's Law:

$$
F = -kx
$$

Applying Newton's Second Law ($F = m\ddot{x}$):

$$
m \frac{d^2x}{dt^2} = -kx \implies \frac{d^2x}{dt^2} + \omega_0^2 x = 0
$$

where the natural angular frequency is defined as:

$$
\omega_0 = \sqrt{\frac{k}{m}}
$$

### 2. General Solution

The general solution to this second-order linear differential equation is:

$$
x(t) = C_1 \cos(\omega_0 t) + C_2 \sin(\omega_0 t)
$$

Applying the initial conditions:
- $x(0) = A \implies C_1 = A$
- $\dot{x}(0) = 0 \implies C_2 = 0$

Thus, the position of the mass as a function of time is:

$$
x(t) = A \cos\left(\sqrt{\frac{k}{m}}t\right)
$$

---

## 📊 Energy Flow Diagram

```mermaid
graph LR
    A[Max Displacement: x = A] -->|Potential to Kinetic| B[Equilibrium: x = 0]
    B -->|Kinetic to Potential| C[Max Displacement: x = -A]
    C -->|Potential to Kinetic| B
    B -->|Kinetic to Potential| A