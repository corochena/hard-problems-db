\---

title: Simple Harmonic Oscillator

date: 2026-08-09

tags:

&#x20; - physics

&#x20; - mechanics

&#x20; - differential-equations

draft: false

enableToc: true

\---



\## 📌 Problem Statement



A block of mass $m$ is attached to an ideal spring with spring constant $k$ on a frictionless horizontal surface.



1\. Write down the \*\*Hooke's Law\*\* restoring force.



2\. Formulate the equation of motion using Newton's Second Law.



3\. Solve for the position $x(t)$ given the initial conditions $x(0) = A$ and $\\dot{x}(0) = 0$.



\---



\## 📐 Derivation \& Solution



\### 1. Differential Equation



The restoring force acting on the mass is given by Hooke's Law:



$$

F = -kx

$$



Applying Newton's Second Law ($F = m\\ddot{x}$):



$$

m \\frac{d^2x}{dt^2} = -kx

\\implies

\\frac{d^2x}{dt^2} + \\omega\_0^2 x = 0

$$



where the natural angular frequency is defined as:



$$

\\omega\_0 = \\sqrt{\\frac{k}{m}}

$$



\### 2. General Solution



The general solution to this second-order linear differential equation is:



$$

x(t) = C\_1 \\cos(\\omega\_0 t) + C\_2 \\sin(\\omega\_0 t)

$$



Applying the initial conditions:



\- $x(0) = A \\implies C\_1 = A$

\- $\\dot{x}(0) = 0 \\implies C\_2 = 0$



Thus, the position of the mass as a function of time is:



$$

x(t) = A \\cos\\left(\\sqrt{\\frac{k}{m}}t\\right)

$$



\---



\## 📊 Energy Flow Diagram



```mermaid

graph LR

&#x20;   A\[Max Displacement: x = A] -->|Potential to Kinetic| B\[Equilibrium: x = 0]

&#x20;   B -->|Kinetic to Potential| C\[Max Displacement: x = -A]

&#x20;   C -->|Potential to Kinetic| B

&#x20;   B -->|Kinetic to Potential| A

