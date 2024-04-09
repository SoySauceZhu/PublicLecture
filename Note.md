# 1. Vector Algebra and Spatial Geometry

## 1.2 Dot Product

### 1. Definition of Dot Product
</br>

### 2. Length of Vector
Rigorous definition
Notation
Unit Vector $(i, j, k)$
Vector Composition
</br>

### 3. Angle between Vectors
Convention 'angle'
Notation
Properties of zero vector (5 properties)
General formula
</br>

### 4. Direction Angle and Direction Cosine
Definition in 2D, 3D:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Angle between two arrow
</br>

### 5. Projection
Definition (it's a scalar)
Notation
</br>

### 6. Arithmetic Rules
Dot product rules
Projection rules
</br>

### 7. Parallel and Orthogonal
Definition
Equivalent definitions
</br>

## 1.3 Cross Product

### 1. Determinant and Geometry Semantic
Area of parallelogram with direction
</br>

### 2. Vector Product
Definition: by determinant
Geometry meaning of cross product
</br>

### 3. Arithmetic Properties
3 properties
</br>

### 4. Triple Product
Rule
Meaning
</br>

### 5. Properties of Triple Product
</br>

## 1.4 Spatial Plane and Equation

### 1. Directional and Normal Vector
Definition of Direction Vector of a Line
Definition of Normal Vector of a Plane
</br>

### 2. Point-normal equation of a plane
> $A(x-x_0)+B(y-y_0)+C(z-z_0)=0$ , 
> where $M=(x_0,y_0,z_0)$ is a point on the plane, $n=(A,B,C)$ is the normal vector  

Geometry meaning

Derivation: M and M0 are orthogonal 
</br>

### 3. General equation of a plane
> $Ax+By+Cz+D=0$, where $n=(A,B,C)$ is a normal vector
> $-D=Ax_0+By_0+Cz_0$

Special planes:
Plane through origin
Plane parallel to axis
Plane parallel to axis plane
</br>

### 4. Intercept form equation
> $\displaystyle\frac{x}{a}+\frac{y}{b}+\frac{z}{c}=1,\quad a\neq0,b\neq0,c\neq0$

Geometry meaning

</br>

### 5. Parametric Equation of Spatial Plane
Given three non-colinear points $A=(a_1,a_2,a_3)$, $B=(b_1,b_2,b_3)$, $C=(c_1,c_2,c_3)$ on a same plane. The equation of the plane is 
$\begin{cases}
x=a_1+k_1(b_1-a_1)+k_2(c_1-a_1)\\
y=a_2+k_1(b_2-a_2)+k_2(c_2-a_2)\\
z=a_3+k_1(b_3-a_3)+k_2(c_3-a_3)
\end{cases},\quad k_1,k_2\in\mathbb{R}$

Further, let
$\boldsymbol{x}=\begin{pmatrix}x\\y\\z\end{pmatrix},\quad\overrightarrow{AB}=B-A=\begin{pmatrix}b_1-a_1\\b_2-a_2\\b_3-a_3\end{pmatrix},\quad\overrightarrow{AC}=C-A=\begin{pmatrix}c_1-a_1\\c_2-a_2\\c_3-a_3\end{pmatrix}$
the equation could be written as
$\boldsymbol{x}=\boldsymbol{A}+k_1\overrightarrow{AB}+k_2\overrightarrow{AC},\quad k_1,k_2\in\mathbb{R}$

* Normal vector of plane given by parametric equation
</br>

### 6. Angle between Planes
Definition and theorem
$0\leq\theta\leq\frac{\pi}{2}$

</br>

### 7. Distance from Point to Plane
> $\displaystyle d=\frac{|Ax_0+By_0+Cz_0+D|}{\sqrt{A^2+B^2+C^2}}$

Geometry meaning
Derivation
</br>

### 8. Exercise
Q: $M(1,1,1)$ and $M(0,1,-1)$ on plane P. P and $x+y+z=0$ are orthogonal. Find P

## 1.5 Spatial Line and Equation

### 1. General Equation
Definition
$\begin{cases}
A_1x+B_1y+C_1z+D_1=0\\
A_2x+B_2y+C_2z+D_2=0
\end{cases}$

Geometry meaning
General equation of $l$ is not unique
Direction vector of line $l$
</br>

### 2. Point-direction equation
$\begin{cases}x-x_0=km\\y-y_0=kn\\z-z_0=kp\end{cases},\quad k\in\mathbb{R}$

$\displaystyle\frac{x-x_0}{m}=\frac{y-y_0}{n}=\frac{z-z_0}{p},\quad m\ne 0, n\ne 0, p\ne 0$

* What if $m=0$

### 3. Parametric Equation
$\boldsymbol{M}=\begin{pmatrix}x_0\\y_0\\z_0\end{pmatrix}, \boldsymbol{s}=\begin{pmatrix}m\\n\\p\end{pmatrix}$

$\begin{cases}x=x_0+km\\y=y_0+kn\\z=z_0+kp\end{cases},\quad k\in\mathbb{R}$

Let $x=(x,y,z)$, it could be written as $\boldsymbol{x}=\boldsymbol{M}+k\boldsymbol{s},\quad k\in\mathbb{R}$

</br>

### 4. Exercise
Find point-direction form and parametric form of $\begin{cases}
    x+y+z+1=0\\
    2x-y+3z+4=0
\end{cases}$

### 5. Angle between spatial lines
Definition of two lines

Theorem
> $s_1, s_2$ are direction vector of $l_1, l_2$ respectively
>
> $\cos\theta=\displaystyle\frac{|\boldsymbol{s}_{1}\cdot\boldsymbol{s}_{2}|}{\|\boldsymbol{s}_{1}\|\|\boldsymbol{s}_{2}\|}=\frac{|m_1m_2+n_1n_2+p_1p_2|}{\sqrt{m_1^2+n_1^2+p_1^2}\sqrt{m_2^2+n_2^2+p_2^2}},\quad 0\le\theta\le\frac{\pi}{2}$
>
> Note that $\theta \space (\displaystyle 0\le\theta\le\frac{\pi}{2})$

Ex. Find the angle between $\displaystyle l_1:\frac{x-1}{1}=\frac{y}{-4}=\frac{z+3}{1}$ and $\displaystyle l_2:\frac{x}{2}=\frac{y+2}{-2}=\frac{z}{-1}$

</br>

### 6. Angle between line and plane
Definition
Theorem
</br>

### 7. Plane cluster of spatial line
Definition

$\text{直线}\ l\ \text{的平面束方程}：
\begin{cases}
    \text{这是一个平面}\\
    \text{该平面始终包含直线}\ l\ \text{，不论}\ \lambda\ \text{如何变化}\\
    \text{该平面代表了所有包含直线}\ l\ \text{的平面，除平面}\ A_2x+B_2y+C_2z+D_2=0\\
\end{cases}$

Theorem
> Given $l : \begin{cases}
A_1x+B_1y+C_1z+D_1=0\\
A_2x+B_2y+C_2z+D_2=0
\end{cases}$
>
> Then $p : A_1x+B_1y+C_1z+D_1+\lambda(A_2x+B_2y+C_2z+D_2)=0,\quad \lambda\in\mathbb{R}$ is the plane cluster 

Geometry meaning

* Ex. $l : \begin{cases}x+y-z-1=0\\x-y+z+1=0\end{cases}$, find the projection on $x+y+z=0$

    Ans: line <- intersection <- plane <- cluster
</br>

### 8. Distance from Point to Line
</br>

## 1.6 Curve Surface and Equation

### 1. Sphere Equation
$\sqrt{(x-x_0)^2+(y-y_0)^2+(z-z_0)^2}=R\quad\text{or}\quad (x-x_0)^2+(y-y_0)^2+(z-z_0)^2=R^2$

### 2. Rotational Surface
Generating line
Axis of rotational surface
</br>

### 3. Instances of Rotational Surface
Find generation line $\rArr$ Substitute
* Cone surface
* Hyperboloid of one sheet
* Hyperboloid of two sheet
* Rotational paraboloid
</br>

### 4. Cylindrical Surface
Definition of generating line, base line
Different type (direction) of cylinder
</br>

### 5. Quadratic Surface
</br>

## 1.6 Spatial Curves and Equation

### 1. General Equation
Definition by intersection
$\begin{cases}
F(x,y,z)=0\\
G(x,y,z)=0
\end{cases}$

### 2. Parametric Equation of Spatial Curve
Definition by trajectory
$\Big(f(t),g(t),h(t)\Big)
\implies \begin{cases}x=f(t)\\y=g(t)\\z=h(t)\end{cases}
\implies\begin{pmatrix}f(t)\\g(t)\\h(t)\end{pmatrix},\quad t\in T$

</br>

### 3. Parametric Equation fo Curve Surface
Vector valued function

$x(t)=f(t)\vec{i}+g(t)\vec{j}+h(t)\vec{h}$
* Ex. rotate $x(t)=(1,t,2t)$ with respect of $z$ axis
    Ans: $(\sqrt{1+t^2}\cos\theta,\sqrt{1+t^2}\sin\theta,2t),\quad t\in\mathbb{R},\theta\in[0,2\pi]$
* Ex. find the equation of a sphere 
    Ans: $\begin{cases}x=r\sin\varphi\cos\theta\\y=r\sin\varphi\sin\theta\\z=r\cos\varphi\end{cases},\quad 0\le\varphi\le\pi,0\le\theta\le 2\pi$

</br>

### 4. Projection to Coordinate Plane
Ex. $z=\sqrt{4-x^2-y^2}$ and $z=\sqrt{3(x^2+y^2)}$ compose a object, find its projection on $xOy$

Ans: $\begin{cases}x^2+y^2\le 1\\z=0\end{cases}$

Ex. Find the projection of $\begin{cases}x^2+y^2+z^2=1\\x^2+(y-1)^2+(z-1)^2=1\end{cases}$ on $xOy$

Ans: $\begin{cases}x^2+2y^2-2y=0\\z=0\end{cases} \text{or} \quad(t, \displaystyle\frac{1}{2}\pm\sqrt{-\frac{t^2}{2}+\frac{1}{2},0})$


# 2. Derivative of Multivariable Function  

## 2.1 Intro of Multivariable Function

### 1. Set of Real Numbers
</br>

### 2. Bivariable Function and Multivariable Function
Definition
Domain, Range 
</br>

### 3. Neighborhood
Definition
Notation
</br>

### 4. Boundary and Boundary Point
Interior, exterior, boundary
</br>

### 5. Open Set and Close Set
</br>

### 6. Connected Set, Open Region and Closed Region
</br>

### 7. Bounded Set and Unbounded Set
</br>

## 2.2 Limit and Continuity

### 1. Definition of Limit
Definition:
Let $(x_0, y_0)$ be a point in the domain of $f$. Then, we say that the limit of $f(x, y)$ as $(x, y)$ approaches $(x_0, y_0)$ is $L$, denoted by:

\[
\lim_{(x,y) \to (x_0, y_0)} f(x, y) = L
\]

if for any number $\varepsilon > 0$, there exists a number $\delta > 0$ that if $0 < \sqrt{(x - x_0)^2 + (y - y_0)^2} < \delta$ (deleted neighborhood), then $|f(x, y) - L| < \varepsilon$.

* Geometry meaning
</br>

* Properties
$\lim\Big[f(x)\pm g(x)\Big]=\lim f(x)\pm \lim g(x)=A\pm B$
$\lim\Big[f(x)\cdot g(x)\Big]=\lim f(x)\cdot \lim g(x)=A\cdot B$
$\displaystyle\lim\frac{f(x)}{g(x)}=\frac{\lim f(x)}{\lim g(x)}=\frac{A}{B}, B\neq 0$
</br>

* Additional statement: 
1. The *path* is irrelevant to the limit 
2. $f(x,y)$ does **NOT** need to be defined on $P(a,b)$ 
</br>

* Theorem:
1. If $f(x,y)$ is polynomial, then its limit always exists and $\lim \rArr f(a,b)$
2. If $f(x,y)\displaystyle = \frac{p(x,y)}{q(x,y)}$ is rational, then its limit exist exists when $q(x,y)\neq 0$, and $\lim = \displaystyle\frac{p(a,b)}{q(a,b)}$. Moreover if $\lim p(x,y)=L\neq0 \space\text{while} \lim q(x,y)=0$, the limit does not exist.
</br>

* Techniques
1. Different Path : $\displaystyle f(x,y) = \frac{x^2-y^2}{x^2+y^2}$ (2 ways)
2. Substitute (polar coordinate)
</br>

### 2. Exercise
1. $\displaystyle\lim_{(x,y)\to (0,0)}(x^2+y^2)\sin\frac{1}{x^2+y^2}=0$

2. $\displaystyle\lim_{(x,y)\to (0,0)}\frac{xy}{x^2+y^2}\quad \text{Does not exist}$

3. $\displaystyle\lim_{(x,y)\to (0,2)}\frac{\sin(xy)}{x}$

4. $\displaystyle\lim_{(x,y)\to (0,0)}\frac{xy}{\sqrt{2-e^{xy}}-1}$
</br>

### 3. Continuity
Definition

A function $f(x, y)$ of two variables is said to be continuous at a point $(x_0, y_0)$ in its domain if the following conditions are met:

1. $\lim_{(x,y) \to (x_0, y_0)} f(x, y)$ exists.
2. $f(x, y)$ is defined at $(x_0, y_0)$.
3. $\lim_{(x,y) \to (x_0, y_0)} f(x, y) = f(x_0, y_0)$.

In other words, $f(x, y)$ is continuous at $(x_0, y_0)$ if the limit of $f(x, y)$ as $(x, y)$ approaches $(x_0, y_0)$ is equal to the value of $f(x, y)$ at $(x_0, y_0)$.

* Theorem
1. If $f, g$ both continuos on domain, then $(f\odot g) \space\text{or} f(g(x,y))$ is continuous as well
2. If $f_{xy} and f_{yx} are continuous on an open set S, then $f_{xy}=f_{yx}$ at each point of S.
</br>

### 4. Properties of Continuity
Boundedness and Extreme Value Theorem
Intermediate Value Theorem
</br>


## 2.3 Partial Derivative, total Derivative

### 1. Partial Derivative
Definition
$\displaystyle\frac{\partial f}{\partial x}_{y=y_0} = \lim_{\Delta x \to 0} \frac{f(x + \Delta x, y_0) - f(x, y_0)}{\Delta x}$

$\displaystyle\frac{\partial f}{\partial y}_{x=x_0} = \lim_{\Delta y \to 0} \frac{f(x_0, y + \Delta y) - f(x_0, y)}{\Delta y}$

* Geometry Meaning
</br>

### 2. Differentiability of a function
Differential is linear asymptote

Definition: partial derivative
We say $f(x,Y)$ is locally linear at $(a,b)$ 
if $f(a+h_1,b+h_2) = f(a,b)+h_1f_x(a,b)+h_2f_y(a,b)+\varepsilon$ 
where $\varepsilon_2(h_1,h_2)\rArr0, \varepsilon_1(h_1,h_2)\rArr0$

* Question : show the direction vector of two partial derivatives of $f(x,y)$

* The normal vector of total derivative

* Further, the tangent plane could be represented
</br>

### 3. Exercise
* Find partial derivative of $x^2sin2y$
</br>

### 4. Higher order derivative and Mixed partial derivative
$
\begin{array}{l}{\displaystyle\frac{\partial}{\partial x}\left(\frac{\partial z}{\partial x}\right)=\frac{\partial^{2} z}{\partial x^{2}}=f_{x x}(x, y), \quad \frac{\partial}{\partial y}\left(\frac{\partial z}{\partial x}\right)=\frac{\partial^{2} z}{\partial x \partial y}=f_{x y}(x, y)} \\ {\displaystyle\frac{\partial}{\partial x}\left(\frac{\partial z}{\partial y}\right)=\frac{\partial^{2} z}{\partial y \partial x}=f_{y x}(x, y), \quad \frac{\partial}{\partial y}\left(\frac{\partial z}{\partial y}\right)=\frac{\partial^{2} z}{\partial y^{2}}=f_{yy}(x, y)}\end{array}
$

Theorem
If two mixed partial derivatives of $f(x,y)$ continuous in D, 
then $f_{x y}(x, y)=f_{y x}(x, y),\quad (x,y)\in D$

## 2.4 Total Differentiability

### 1. Total differential
Partial differential -> total differential

$\mathrm{dz}=A\mathrm{dx}+B\mathrm{dy}$
$z-f(x_0,y_0)=A(x-x_0)+B(y-y_0)$

$A=f_x(x_0,y_0), B=f_y(x_0,y_0)$

* Theorem:
if $f(x,y)$ is differentiable, then $f_x(x_0,y_0), f_y(x_0,y_0)$ exist, and &z=f(x,y)$ has total differential $\mathrm{d}z=f_x(x_0,y_0)\mathrm{d}x+f_y(x_0,y_0)\mathrm{d}y$ at $(x_0,y_0)$

### 2. Exercise
1. Find differential of $z=e^{xy}$ $(2,1)$
Ans: $\left.\mathrm{d}z\right|_{(x,y)=(2,1)}=e^2\mathrm{d}x+2e^2\mathrm{d}y$

2. $\displaystyle u=x+\sin\frac{y}{2}+e^{yz}$
Ans: $\mathrm{d}u=\mathrm{d}x+\left(\frac{1}{2}\cos\frac{y}{2}+ze^{yz}\right)\mathrm{d}y+ye^{yz}\mathrm{d}z$

3. if both two partial differential of $f(x,y)$ exist, does $f(x,y)$ differentiable

4. Asymptote
</br>

### 3. Relation with continuity
$f(x,y)$ differentiable at $(x_0,y_0)$ $\rArr$ $f(x,y)$ continuous
$\displaystyle\frac{\partial f}{\partial x}\text{,}\frac{\partial f}{\partial y}\ \text{continuous at} (x_0,y_0)\ \implies f(x,y)\ \text{differentiable at}\ (x_0,y_0)$
$\displaystyle\frac{\partial f}{\partial x}\text{,}\frac{\partial f}{\partial y}\ \text{continuous at} (x_0,y_0) \mathrel{\rlap{\hskip .5em/}}\Longleftarrow f(x,y)\ \text{differentiable at}\ (x_0,y_0)$

## 2.5 Higher Order and Composition of Multivariable Function 

### 1. $z=f(\phi(t), \psi(t))$
If $x=\phi(t), y=\psi(t)$ have derivative at $t_0$, and $z=f(x,y)$ has continuous partial derivative, then $f$ is differentiable
$\displaystyle\frac{\mathrm{d}z}{\mathrm{d}t}=\frac{\partial z}{\partial x}\frac{\mathrm{d}x}{\mathrm{d}t}+\frac{\partial z}{\partial y}\frac{\mathrm{d}y}{\mathrm{d}t}$
$\frac{dz}{dt}$ is total differential

Ex. $x=\cos t, y=\sin t, z=xy$, find $\frac{dz}{dt}$
Ans: $cos(2t)$
</br>

### 2. Chain rule
$w=f(x,y,z)=f[\varphi(t),\psi(t),\omega(t)]$
$\displaystyle\frac{\mathrm{d}w}{\mathrm{d}t}=\frac{\partial w}{\partial x}\frac{\mathrm{d}x}{\mathrm{d}t}+\frac{\partial w}{\partial y}\frac{\mathrm{d}y}{\mathrm{d}t}+\frac{\partial w}{\partial z}\frac{\mathrm{d}z}{\mathrm{d}t}$

Ex.$w=xy+z, x=\cos t, y=\sin t, z=t$, find $\displaystyle\frac{dw}{dt}$
Ans: $1+\cos 2t$
</br>

Ex. $w=e^{x^2+y^2+z^2}, z=x^2\sin y$, find $\displaystyle\frac{\partial w}{\partial x}$

Ans: $\begin{aligned} 
    \frac{\partial w}{\partial x} 
        &=\frac{\partial f}{\partial x}+\frac{\partial f}{\partial z}\frac{\partial z}{\partial x}=2xe^{x^2+y^2+z^2}+2ze^{x^2+y^2+z^2}\cdot 2x\sin y\\
        &=2x(1+2x^2\sin^2 y)e^{x^2+y^2+x^4\sin^2 y}
\end{aligned}$

## 2.6 Derivative of Implicit Function 
### 1. Existence Theorem
If implicit function $F(x,y)=0$ has continuous partial derivative at $(x_0,y_0)$
Then $\displaystyle \frac{\mathrm{d}y}{\mathrm{d}x}=-\frac{F_x}{F_y}$
</br>

### 2. Existence Theorem 2
$\displaystyle F(x_0,y_0,z_0)=0,\quad F_z(x_0,y_0,z_0)\ne 0$
$\displaystyle \frac{\partial z}{\partial x}=-\frac{F_x}{F_z},\quad \frac{\partial z}{\partial y}=-\frac{F_y}{F_z}$
Ex. $x^2+y^2+z^2-4z=0$，find$\displaystyle\frac{\partial^2 z}{\partial x^2}$
Ans: $\frac{\partial z}{\partial x}=-\frac{F_x}{F_z}=\frac{x}{2-z}$
$\frac{\partial^2 z}{\partial x^2}=\frac{\displaystyle(2-z)+x\frac{\partial z}{\partial x}}{(2-z)^2}=\frac{\displaystyle(2-z)+x\frac{x}{2-z}}{(2-z)^2}=\frac{(2-z)^2+x^2}{(2-z)^3}$

## 2.7 Direction Derivative and Gradient
### 1. Direction derivative
Say the unit direction vector is $\boldsymbol{e}_{\boldsymbol{u}}=\begin{pmatrix}\cos\alpha\\\cos\beta\end{pmatrix}$. If the following limit exist, then the direction derivative is $\displaystyle\left.\frac{\partial f}{\partial \boldsymbol{u}}\right|_{\begin{aligned}x=x_0\\y=y_0\end{aligned}}=\lim_{t\to 0^+}\frac{f(x_0+t\cos\alpha, y_0+t\cos\beta)-f(x_0,y_0)}{t}$

### 2. Exercise
$f(x,y)=xy$ find $\displaystyle\left.\frac{\partial f}{\partial \boldsymbol{u}}\right|_{(x,y)\rArr(1,2)}$ where $\vec{u}=(1,1)$

### 3. Find direction derivative when differentiable
$u=(u_1,u_2)$ is a unit vector
$\left.\frac{\partial f}{\partial \boldsymbol{u}}\right|_{\begin{aligned}x=x_0\\y=y_0\end{aligned}}=f_x(x_0,y_0)u_1+f_y(x_0,y_0)u_2$

### 4. Gradient
$\nabla f = f_x(x,y)\boldsymbol{i}+f_y(x,y)\boldsymbol{j}$

Geometry Meaning

### 5. Exercise
$\displaystyle f(x,y)=\frac{1}{2}(x^2+y^2)$, find:
1. the direction where decrease most quickly at (1,1), and its direction derivative

### 6. Gradient and Contour Lines

## 2.8 Extreme Values

### 1. Definition

### 2. Conditions
extreme value $(x_0,y_0) \rArr f_x(x_0,y_0)=f_y(x_0,y_0)=0$ 

* Stationary point

Hessian Matrix
$H=\frac{\partial^2 z}{\partial(x,y)^2}=\begin{pmatrix}f_{xx}&f_{xy}\\f_{yx}&f_{yy}\end{pmatrix}$
If $|H|>0$, we can determine the concavity or convexity. $f_{xx}>0$ concave, $f_{xx}<0$ convex.

Given point $p(x_0,y_0)$, if $f$ is continuous and its Hessian Matrix on p's neighbor, and $f_x(x_0,y_0)=f_y(x_0,y_0)=0$ (stationary point).
Then
1. $|H|>0, f_{xx}>0$
2. $|H|>0, f_{xx}<0$
3. $|H|<0$
4. $|H|=0

Ex. Find the extreme value of $f(x,y)=x^3-y$3+3x^2+3y^2-9x$

Ans:
$f_x=3x^2+6x-9,\quad f_y=-3y^2+6y$
$\begin{cases}
f_x=3x^2+6x-9=0\implies x=1,-3\\
f_y=-3y^2+6y=0\implies y=0,2
\end{cases}$
$f_{xx}=6x+6,\quad f_{xy}=f_{yx}=0,\quad f_{yy}=-6y+6$
$H=\begin{pmatrix}f_{xx}&f_{xy}\\f_{yx}&f_{yy}\end{pmatrix}=\begin{pmatrix}6x+6&0\\0&-6y+6\end{pmatrix}\implies |H|=36(-xy+x-y+1)$


## 2.9 Conditional Extreme
Ex. The minimum of distance from point on $x^2y=3$ to origin

$\nabla h=\begin{pmatrix}h_x\\h_y\end{pmatrix}=\begin{pmatrix}\displaystyle\frac{x}{\sqrt{x^2+y^2}}\\\displaystyle\frac{y}{\sqrt{x^2+y^2}}\end{pmatrix},\quad \nabla g=\begin{pmatrix}g_x\\g_y\end{pmatrix}=\begin{pmatrix}2xy\\x^2\end{pmatrix}$
$
\begin{aligned}
    \begin{cases}
    g(x_0,y_0)=3\\
    \nabla h(x_0,y_0)=\lambda \nabla g(x_0,y_0)
    \end{cases}
        &\implies
        \begin{cases}
        x_0^2y_0=3\\
        \begin{pmatrix}\displaystyle\frac{x_0}{\sqrt{x_0^2+y_0^2}}\\\displaystyle\frac{y_0}{\sqrt{x_0^2+y_0^2}}\end{pmatrix}=\lambda \begin{pmatrix}2x_0y_0\\x_0^2\end{pmatrix}
        \end{cases}
        \implies
        \begin{cases}
        x_0^2y_0=3\\
        \displaystyle\frac{x_0}{\sqrt{x_0^2+y_0^2}}=\lambda 2x_0y_0\\
        \displaystyle\frac{y_0}{\sqrt{x_0^2+y_0^2}}=\lambda x_0^2
        \end{cases}\\
        &\implies x_0=\pm\sqrt[6]{18},\quad y_0=\frac{3}{\sqrt[3]{18}},\quad\lambda\approx 0.22
\end{aligned}
$