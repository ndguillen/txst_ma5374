## TXST MATH 5374. Numerical Linear Algebra. Fall 2022.

## Problem Set 1

Set up Python as well as Jupyter on your computer. Make sure you can run the first notebook (this requires numpy, pyplot, and scipy). 

1. Using scipy, generate three random numbers $A,\omega,$ and $\delta$ (chosen uniformly in the interva $[0,10]$) and plot the function $y = A\cos(\omega x + \delta)$ over the integral $[0,2\pi]$ using 10, 100, and 1000 equidistant points. Submit a Python notebook with the code along with your other solutions in this problem set. 

2. In the vector space of polynomials of degree no greater than $4$, we look at the derivative operator $\tfrac{d}{dx}$, that is, if $$p(x) = a_4x^4 + a_3x^3+a_2x^2+a_1x+a_0$$ 
then
$$\tfrac{d}{dx}p(x) = 4a_4x^3+3a_3x^2+2a_2x+a_1$$
    - Write down the matrix $D$ corresponding to $\tfrac{d}{dx}$ in the basis given by the polynomials $x^4,x^3$,$x^2,x^1,1$
    - Describe the Image and Kernel of $D$
    - Is $D$ an invertible matrix?

3. Show the following norm inequalities hold for every $x \in \mathbb{R}^n$

$$\|x\|_\infty \leq \|x\|_2 \leq \sqrt{n}\|x\|_\infty$$

$$\frac{1}{\sqrt{n}}\|x\|_1 \leq \|x\|_2 \leq \sqrt{n}\|x\|_1$$

(see also the last problem)

4. Find the inverse to the matrix $A$ defined by 

$$ A = \left ( \begin{array}{cc} 1 & 1 \\ 0 & \varepsilon\end{array} \right )$$

(here, $\varepsilon>0$). Then, prove that

$$ \|A\| \|A^{-1}\| \to \infty \text{ as } \varepsilon \to 0 $$

*Hint: Look for a lower estimate for $\|A\|$ and $\|A^{-1}\|$ in terms of the parameter $\varepsilon$* 

5. Let $A$ be a $n\times n$ matrix whose column vectors $a_1,\ldots,a_n$ are such that

$$ \|a_k\|_2 \leq 1 \;\text{ for } k=1,\ldots,n $$

Show that, given any $x \in \mathbb{R}^n$

$$ \|Ax\|_2 \leq \|x\|_1$$

6. Consider the following quadratic polynomial of three variables

$$ p(x_1,x_2,x_3) = x_1^2 + 2x_1x_2-4x_2x_3 + 3x_2^2-5x_3^2$$

Find a $3\times 3$ symmetric matrix $A$ such that if $x^\bot = (x_1,x_2,x_3)$ then
$$ p(x_1,x_2,x_3) = (Ax,x)$$
Can there be more than one such matrix $A$?

7. Given two vectors $x$ and $y$ (say, $x\in\mathbb{R}^n$ and $y\in \mathbb{R}^m$), their **tensor** product $x\otimes y$ is the $n\times m$ matrix determined by the formula $$(x\otimes y)z = (z,x)y$$ 
    - Show that $(x\otimes y)_{ij} = x_jy_i$ for $j=1,\ldots,n$ and $i=1,\ldots,m$.
    - Describe the Kernel and the Image of $x\otimes y$ in terms of the vectors $x$ and $y$.
    - Show that the transpose of $x\otimes y$ is simply $y\otimes x$.
    - Suppose that $x$ is a unit vector ($\|x\|_2 =1$), show that $(x\otimes x)^2 = x\otimes x$.
    - Provide a geometric description of what multiplication by $x\otimes x$ does to a vector.

8. \* Let $V$ be a vector space of dimension $n$. Then
    - Show that the unit sphere of $V$ with respect to any norm is always compact, i.e. any infinite sequence contained in the set $$ \{ x \in V : \|x\|_\alpha = 1 \} $$ always has a convergent subsequence.
    - Then, let $\|\cdot\|_{\alpha}$ and $\|\cdot\|_\beta$ be two different norms in $V$, and show that
$$\inf \limits_{\|x\|_\beta =1} \|x\|_\alpha > 0 \;\text{ and } \sup \limits_{\|x\|_\beta = 1} \|x\|_\alpha <\infty$$
Conclude that for this pair of norms one can find constants $c$ and $C$ such that for any $x \in V$,
$$ c\|x\|_\alpha \leq \|x\|_\beta \leq C \|x\|_\alpha$$  

