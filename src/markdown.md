---
title: Laplace equation and Poisson equation
subtitle: Some expository on basic linear elliptic equations, this note is served as a road map to identify similar patterns for general linear elliptic equations later.
date: 2022-11-03
---


---
The basic properties of solution to a Laplace equation $`\Delta u = 0`$, i.e., a harmonic function can be summarized as follows.

* [Mean value properties](#mean-value-properties)
* [Strong max/min principles (using mean value properties)](#strong-max/min-principles)
* [Harnack inequality (using mean value properties)](#harnack-inequality)

## Mean value properties

Let $`\Omega`$ be a domain in $`\mathbb{R}^n`$ and $`u\in \mathrm{C}^2(\Omega)`$ be a function. 

> A function $`u\in \mathrm{C}^2(\Omega)`$ is called *harmonic, subharmonic, superharmonic* in $`\Omega`$ if there holds, $`-\Delta u = 0, -\Delta u \leq 0, -\Delta u \geq 0`$ in $`\Omega`$, respectively.

Harmonic function satisfies the mean-value property, in the sense that 
<p>
    \begin{equation}
        u(x_0) = \frac{1}{n\alpha(n)r^{n-1}}\int_{\partial B(x_0,r)} u(x)\,dS(x) \nonumber
    \end{equation}
</p>
for all $`B(x_0,r)\subset \Omega`$, where $`\alpha(n)`$ is the volume of the unit ball in $`\mathbb{R}^n`$, thus $`n\alpha(n)`$ is the surface area of the unit sphere in \\( \mathbb{R}^n \\). By integration we can see that the mean value integral can be taken on the ball instead of the surface as 
<p>
    \begin{equation}
    \begin{aligned}
    \frac{1}{\alpha(n)r^n}\int_{B(x_0,r)} u(x)\,dx &=  \frac{1}{\alpha(n)r^n}\int_0^r \left(\int_{\partial B(x_0,s)} u(x)\,dS(x) \right)ds\\
                                &=  \frac{1}{\alpha(n)r^n}\int_0^r \Big( n\alpha(n)r^{n-1}u(x_0) \Big)ds =  u(x_0).
    \end{aligned} \nonumber
    \end{equation}
</p>

## Strong max/min principles

## Harnack inequality


