# Differentiation and derivatives
---

### 1. Tangent line equation and its slope

If there is a smooth function $y=f(x)$, let's draw a line from a point on this function
curve $(x_1,\;y_1=f(x_1))$ to $(x_2,\;y_2=f(x_2))$, where $x_2>x_1$. Since the line obeys the 
equation $y=k\cdot x+b$, we can find unknown parameters $k$ and $b$ from the next set of equations.
$$y_1=k\cdot x_1+b\;,\;\;y_2=k\cdot x_2+b\;.$$
Solving these equations, we have
$$k = \frac{y_2-y_1}{x_2-x_1}=\frac{f(x_2)-f(x_1)}{x_2-x_1}\;,$$
and 
$$b = \frac{y_1\cdot x_2-y_2\cdot x_1}{x_2-x_1}=\frac{x_2\cdot f(x_1)-x_1\cdot f(x_2)}{x_2-x_1}\;.$$
If $x_1=c$ and $x_2=x_1+h=c+h$, with very small and positive $h$, we can write
$$k=\frac{f(c+h)-f(c)}{h}\;,$$
and
$$b=\frac{(c+h)\cdot f(c)-c\cdot f(c+h)}{h}\;.$$
For very small $h$, we have the slope of the tangent line being approximately the derivative of the 
function at the given point $c$.
$$f'(x)=\lim\limits_{h\to0}\frac{f(c+h)-f(c)}{h}\;.$$

### 2. Simple case

Let us consider a very simple case of $f(x)=x^2$. In this case, the slope of the tangent line becomes
$$k=\frac{(c+h)^2-c^2}{h}=\frac{c^2+2ch+h^2-c^2}{h}=\frac{2ch+h^2}{h}=2c+h\;.$$
Hence, in the limiting case
$$(x^2)'=2x\;.$$

### 3. Derivatives of standard functions

1. $(x^n)'=nx^{n-1}$
2. $(e^x)'=e^x$
3. $(a^x)'=a^x\cdot\ln a$
4. $(\sin x)' = \cos x$
5. $(\cos x)' = -\sin x$
6. $(\ln x)'=1/x$
7. $(\log_ax)'=1/(x\ln a)$

### 4. Derivative rules

1. $(a)'=0$
2. $(f(x)\cdot g(x))'=f'(x)\cdot g(x)+f(x)\cdot g'(x)$
3. $(a\cdot f(x)+b\cdot g(x))'=a\cdot f'(x)+b\cdot g'(x)$
4. $f(g(x))'=g'(x)\cdot f'(g(x))$

### 5. Problems

1. $f(x)=x^2-5x+6\;,$ find $f'(x)$
2. $f(x)=x^2e^x\;,$ find $f'(x)$
3. $f(x)=\sin(3x)\;,$ find $f'(x)$
4. $f(x)=e^{2x}\cdot\cos(3x)\;,$ find $f'(x)$
5. $f(x)=(x^2-1)/(2x)\;,$ find $f'(x)$