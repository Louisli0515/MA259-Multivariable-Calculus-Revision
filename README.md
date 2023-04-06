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
