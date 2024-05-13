---
layout: page
title: Research Statement
---
### Research Experiences
---
**2024: Large Language Model, Efficient AI**<br>
> Technologies: pruning, knowledge distillation, quantization, and more for optimizing model size, inference speed, and resource utilization in AI systems.

**2022: Nonlinear convex optimization, Variational analysis**<br>
> Solving real-variable and complex-variable convex problems by using the proximal point algorithm, primal-dual method, and ADMM. These methods can achieve an O(1/t) convergence rate.

**2019: Edge-cloud network and federated learning, Task offloading, and resource allocation**<br>
>Aiming to reduce latency, energy consumption, and training error by optimizing task offloading, transmit power, number of epochs, and data allocation.

**2017: Underwater Wireless sensor network, Clustering algorithm**<br>
>In underwater wireless sensor networks, an energy-efficient clustering algorithm based on the Voronoi diagram is proposed for magnetic induction communications.

**2016: Wireless sensor network, Path planning**<br>
>Reducing latency and energy consumption by designing the optimal path for UAVs.

### Summary of nonlinear optimization
---
**The convex optimization problem with nonlinear inequality constraints**:<br>
$ \min $ $ \{ f(\mathbf{x}) \phi_{i}(\mathbf{x}) \leq 0, \mathbf{x} \in \mathcal{X}, i=1,\cdots,m, \} $
where $\mathcal{X} \in \mathbb{R}^{n}$ is a nonempty closed convex set, $f: \mathbb{R}^{n} \rightarrow \mathbb{R}$ and $\phi_{i}: \mathbb{R}^{n} \rightarrow \mathbb{R} \ (i=1,\ldots,m)$ are proper and closed convex functions, and $\phi_{i} \ (i=1,\ldots,m)$ are continuously differentiable.

**The saddle-point problem with a nonlinear coupling operator**:<br>

$$
\begin{equation}
\begin{aligned}
\min_{\mathbf{x} \in \mathcal{X}} \max_{\mathbf{y} \in \mathcal{Y}} \mathcal{L}(\mathbf{x}, \mathbf{y}) := f(\mathbf{x}) + \langle\mathbf{y}, \boldsymbol{\Phi}(\mathbf{x})\rangle - g(\mathbf{y})
\end{aligned}
\end{equation} $$
where $\mathcal{X} \subseteq \mathbb{R}^{n}$ and $\mathcal{Y} \subseteq \mathbb{R}^{m}$ are two closed convex sets. $f: \mathcal{X} \rightarrow \mathbb{R}$ and $g: \mathcal{Y} \rightarrow \mathbb{R}$ are two proper convex but not necessarily smooth functions. The nonlinear function $\boldsymbol{\Phi}: \mathbb{R}^{n} \rightarrow \mathbb{R}^{m}$ is both convex and continuously differentiable over $\mathcal{X}$.

**The convex complex-variable matrix optimization problem**:<br>

$$
\begin{aligned}
\min{ f(\mathbf{X}) \mid \phi_{i}(\mathbf{X}) \leq 0, \mathbf{X} \in \mathcal{X}, i=1,\cdots,p}
\end{aligned}\tag{3}
$$
where $\mathcal{X} \subseteq \mathbb{C}^{m \times n}$ is a convex set and objective $f: \mathbb{C}^{m \times n} \rightarrow \mathbb{R}$ is convex. Constraint functions $\phi_{i}: \mathbb{C}^{m \times n} \rightarrow \mathbb{R} \ (i=1,\cdots,p)$ are convex and differentiable over $\mathcal{X}$.

**The separable convex optimization problem with nonlinear inequality constraints**:<br>

$$
\begin{aligned}
\min\left{ f(\mathbf{x}) + g(\mathbf{y}) \mid \phi_{i}(\mathbf{x}) + \psi_{i}(\mathbf{y}) \leq 0, \mathbf{x} \in \mathcal{X}, \mathbf{y} \in \mathcal{Y}, i=1,\cdots,p\right}
\end{aligned}\tag{4}
$$
where $\mathcal{X} \in \mathbb{R}^{n}$ and $\mathcal{Y} \in \mathbb{R}^{m}$ are two nonempty closed convex sets, $f: \mathbb{R}^{n} \rightarrow \mathbb{R}$, $\phi_{i}: \mathbb{R}^{n} \rightarrow \mathbb{R} \ (i=1,\ldots,p)$, $g: \mathbb{R}^{m} \rightarrow \mathbb{R}$ and $\psi_{i}: \mathbb{R}^{m} \rightarrow \mathbb{R} \ (i=1,\ldots,p)$ are proper and closed convex functions, and $\phi_{i}, \psi_{i} \ (i=1,\ldots,p)$ are continuously differentiable.


