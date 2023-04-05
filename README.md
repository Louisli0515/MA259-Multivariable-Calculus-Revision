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
* The ***second step*** is to find the discontinuity point, in most cases are $(0,0)$. Then try to prove it is continuous at (0,0). (Check Question 3)

#### Seperate continuity

* A function $f:\mathbb{R}^{2}\to\mathbb{R}$ is ***separately continuous*** at $(x_{0},y_{0})$ if $g^{y_{0}}$ is continuous at $x_{0}$ as a function of $x$ and $h^{x_{0}}$ is continuous at $y_{0}$ as a function of $y$.
* Continuity implies separate continuity, but not vice versa.
