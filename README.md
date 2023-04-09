# MA259-Multivariable-Calculus-Revision
My own notes and revisions about MA259, including example sheets and past papars

This repository will mainly focus on two parts, support class questions and past papers. I will provide the pdf made by myself so there will not be any problems about license.

## Lecture notes

[MA259full2223.pdf](https://github.com/Louisli0515/MA259-Multivariable-Calculus-Revision/files/11159707/MA259full2223.pdf)

Feel free to download the 2022 version of lecture notes for MA259.

## Example sheets

### Week 1

[MA259_Multivariable_Calculus_week_1.pdf](https://github.com/Louisli0515/MA259-Multivariable-Calculus-Revision/files/11163810/MA259_Multivariable_Calculus_week_1.pdf)

In week 1's example sheet, we should be familiar with some of the basic concepts and definitions.

#### Norm comparisons

* For $x = (x_{1},..,x_{n})\in\mathbb{R}^{n}$, where $$\left|x\right| = \sqrt{x_{1}^{2}+...+x_{n}^{2}},$$ recall that $$|x|_{\infty} =  \max\set{|x_1|,...,|x_n|},$$ and $$|x|_1 = |x_1|+...+|x_n|.$$
* The relationship between them are $$|x|_{\infty}\leq|x|\leq\sqrt{n}|x|\infty, \quad\text{and}\quad |x|\leq|x|_1\leq\sqrt{n}|x|.$$ 

#### Cauchy-Schwarz inequality

* Remember again $$|\left<\mathbf{u},\mathbf{v}\right>|\leq\left\|\mathbf{u}\right\|\left\|\mathbf{v}\right\|.$$

#### Convergence definition

* Let's say a sequence $x_{j}$ converges to $x$, that means given $\varepsilon > 0$, there exists $N\in\mathbb{N}$ such that $$j\geq N\implies \left|x_{j}-x\right|<\varepsilon.$$

#### Continuity definition

* Let's say a function is continuous at a, that means for all $\varepsilon > 0$, there exists $\delta > 0$ such that if $\left|x-a\right| < \delta$, then $$\left|f(x)-f(a)\right| < \varepsilon.$$
* If we want to prove the continuity of a multivariable function, the ***first step*** is to define the function separately and use continuity of these separate functions to prove the whole function's continuity.
* The ***second step*** is to find the discontinuity point, in most cases are $(0,0)$. Then try to prove it is continuous at (0,0), limits are the most used one. (Check Question 3)

#### Seperate continuity

* A function $f:\mathbb{R}^{2}\to\mathbb{R}$ is ***separately continuous*** at $(x_{0},y_{0})$ if $g^{y_{0}}$ is continuous at $x_{0}$ as a function of $x$ and $h^{x_{0}}$ is continuous at $y_{0}$ as a function of $y$.
* Continuity implies separate continuity, but not vice versa.

### Week 2

[MA259_Multivariable_Calculus_week_2.pdf](https://github.com/Louisli0515/MA259-Multivariable-Calculus-Revision/files/11172123/MA259_Multivariable_Calculus_week_2.pdf)

In week 2, we mainly focus on closed and open sets or balls.

#### Closed set

* $X\subset\mathbb{R}^{n}$ is defined to be ***closed*** if whenever $x_{j}$ is a sequence of points in $X$ which converges to $x\in\mathbb{R}^{n}$ then the limit $x$ also belongs to $X$.
* $X\subset\mathbb{R}^{n}$ is ***closed*** if $\forall x\in X$, $\exists\varepsilon > 0$ such that $\overline{\mathbb{B}(x,\varepsilon)}\subset X$.
* A closed ball is closed.

#### Open set

* $U\subset\mathbb{R}^{n}$ is defined to be ***open*** if $\forall x\in U$, $\exists\varepsilon > 0$ such that $y\in\mathbb{R}^{n}$ and $\left|y-x\right|<\varepsilon\implies y\in U$.
* $U\subset\mathbb{R}^{n}$ is ***open*** if, $\forall x\in U$, $\exists\varepsilon > 0$ such that $\mathbb{B}(x,\varepsilon)\subset U$.
* An open ball is open.

#### Properties of open and closed sets

* A set is open if and only if its complement is closed.
* The finite intersection of open sets is open.
* An arbitrary ***intersection*** of closed sets is closed and the ***finite union*** of closed sets is closed.
* If $f:\mathbb{R}^{n}\to\mathbb{R}^{k}$ is continuous at all points of $\mathbb{R}^{n}$, then for all open subsets $V$ of $\mathbb{R}^{k}$, $f^{-1}(V)$ is open; for all closed subsets $\mathcal{F}$ of $\mathbb{R}^{k}$, $f^{-1}(\mathcal{F})$ is closed.

### Week 3

[MA259_Multivariable_Calculus_week_3.pdf](https://github.com/Louisli0515/MA259-Multivariable-Calculus-Revision/files/11174816/MA259_Multivariable_Calculus_week_3.pdf)

In week 3's example sheet, we mainly focus on norms.

#### Sequentially compact subset

* $K\subset\mathbb{R}^{n}$ is ***sequentially compact*** if every sequence $x_{j}$ in $K$ has a convergent subsequence $x_{jl}$ whose limit is in $K$.
* $K\subset\mathbb{R}^{n}$ is ***sequentially compact*** if and only if $K$ is closed and bounded.

#### Frobenius norm

* Frobenius norm $\left\|\cdot\right\|_F$ is defined as $$\left\|(a _{ij})\right\|_F = \left(\sum _{i=1}^{k}\sum _{j=1}^{n}  a^{2} _{ij}\right) ^{1/2}.$$

#### Operator norm

* The operator norm is defined by $$\left\|A\right\| = \sup _{x\in\mathbb{R}^{n}\setminus\set{0}} \frac{|Ax|}{|x|}.$$

#### Comparison between Frobenius and Operator norm

* Suppose that $\mu(A) = (a_{ij})$, we have $$\frac{1}{\sqrt{n}}\left\|\mu(a)\right\|_F \leq\left\|A\right\|\leq\left|\mu(A)\right\|_F.$$

#### Cauchy Sequence

* A sequence $x_{1}, x_{2}, x_{3},...$ of real numbers is called Cauchy sequence if for every positive real number $\varepsilon$, there is a positive integer $N$ such that for all natural numbers $m,n > N$, $$\left|x_{m}-x_{n}\right| < \varepsilon.$$

### Week 4

[MA259_Multivariable_Calculus_week_4.pdf](https://github.com/Louisli0515/MA259-Multivariable-Calculus-Revision/files/11179897/MA259_Multivariable_Calculus_week_4.pdf)

In week 4's example sheet, we mainly focus on derivatives.

#### Frechet Derivative

* If we extend the derivative to functions $f:\mathbb{R}^{n}\to\mathbb{R}^{k}$, we can define the Frechet Derivative as if $f$ is differentiable at $x\in U$, if there exists $A\in L(\mathbb{R}^{n},\mathbb{R}^{k})$ such that $$\lim_{h\to 0}\frac{\left|f(x+h)-f(x)-f'(x)h\right|}{\left|h\right|} = 0.$$

#### Directional derivative

* The ***directional derivative*** $\partial_{v}f(x)$ is defined by $$\partial_{v}f(x) = \frac{\mathrm{d}}{\mathrm{d}t}g_{x,v}(t)| _{t=0} = \frac{\mathrm{d}}{\mathrm{d}t}f(x+tv)| _{t=0}.$$
* It is denoted by $Df(x)$.

#### Relation between the derivative and directional derivative

* If $Df(x)$ exists then $\partial_{v}f(x)$ exists for all $v\in\mathbb{R}^{n}$ and $\partial_{v}f(x) = Df(x)v$. In particular, if $f$ is differentiable at $x$, then $\partial_{v}f(x)$ is linear in v, i.e. $$\partial_{av+bw}f(x) = a\partial_{v}f(x)+b\partial_{w}f(x), \forall a,b\in\mathbb{R}, v,w\in\mathbb{R}^{n}.$$

#### Gradient

* The ***gradient*** at $x$, $\nabla f(x)$, of a scalar valued function $f:U\to\mathbb{R}$ is defined to be the column vector 

```math
\nabla f(x) = \begin{bmatrix} \partial_1 f(x) \\ \vdots\\ \partial_n f(x) \end{bmatrix}.
```

* A ***linear functional*** on $\mathbb{R}^{n}$ is identified with the vector $\nabla f(x)$: $$(\partial f(x))(v) = (\nabla f(x))\cdot v.$$
* If $f:U\to\mathbb{R}^{k}$ is ***differentiable*** at $x\in U$ and $h\in\mathbb{R}^{n}$, then $$Df(x)h = \partial f(x)h.$$

### Week 5

[MA259_Multivariable_Calculus_week_5.pdf](https://github.com/Louisli0515/MA259-Multivariable-Calculus-Revision/files/11185175/MA259_Multivariable_Calculus_week_5.pdf)

In week 5's example sheet, we take a look at gradients, Jacobian matrix and revision on MA136 Geometry and Motion.

#### Jacobian matrix

* Suppose $\mathbf{f}: \mathbb{R}^{n}\to\mathbb{R}^{m}$ is a function such that each of its first-order partial derivatives exist on $\mathbb{R}^{n}$. This function takes a point $\mathbf{x}\in\mathbb{R}^{n}$ as input and produces the vector $f(x)\in\mathbb{R}^{m}$ as output. Then the Jacobian matrix of $\mathbf{f}$ is defined to be an $m\times m$ matrix, denoted by $\mathbf{J}$ as follows:

```math
\mathbf{J} = \begin{bmatrix} \frac{\partial f_{1}}{\partial x_{1}} & \cdots & \frac{\partial f_{1}}{\partial x_{n}}\\ \vdots & \ddots & \vdots\\ \frac{\partial f_{m}}{\partial x_{1}} & \cdots & \frac{\partial f_{m}}{\partial x_{n}} \end{bmatrix}.
```

#### Chain Rule

* Let $U$ and $V$ be open subsets of $\mathbb{R}^{n}$ and $\mathbb{R}^{k}$ respectively. Suppose that $f:U\to\mathbb{R}^{k}$ is differentiable at $x\in U$ and that $f(x)\in V$. Suppose that $g:V\to\mathbb{R}^{m}$ is differentiable at $f(x)$. Then $g\circ f:\mathbb{R}^{n}\to\mathbb{R}^{m}$ is differentiable at $x$ and $$D(g \circ  f)(x) = Dg(f(x)) \circ Df(x).$$
* With ***Jacobian matrix***, the chain rule can be written as $$\partial g\circ f(x) = \partial g(f(x))\cdot\partial f(x).$$
* With ***gradient***, the chain rule can be written as $$\nabla g\circ f(x) = g'(f(x))\nabla f(x).$$

#### Inverse of a 2 $\times$ 2 matrix

* Recall that if
 ```math
A = \begin{bmatrix} a & b \\ c & d \end{bmatrix},
```
then its inverse is given by 
 ```math
A^{-1} = \frac{1}{ad-bc}\begin{bmatrix} d & -b \\ -c & a \end{bmatrix}.
```

#### Revision of MA136

* ***Polar Coordinates*** is given by $$x = r\cos\theta, y = r\sin\theta,\,\mathrm{d}A = r\mathrm{d}r\mathrm{d}\theta.$$
* ***Spherical Coordinates*** is given by $$x = r\sin\varphi\cos\theta, y = r\sin\varphi\sin\theta, z= \cos\varphi,\,\mathrm{d}V = r^{2}\sin\varphi\mathrm{d}r\mathrm{d}\theta\mathrm{d}\varphi.$$
