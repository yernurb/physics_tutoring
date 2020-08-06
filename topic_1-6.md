# Logarithms and exponentials
---

### 1. Euler's number

> **Problem:** You have \$1 in your bank account, and in 1 year, you gain 100\% raise, and get \$2. 
> However, if you decide to split your raise into two parts and increment after consecutive 6 months
> but with half raise percentages, your final gain will be a little higher. Since after 6 month
> you raise your \$1 by 50\% and get \$1,5. After another 6 month, you will get another 50\% raise,
> and finally will have \$2,25. 
> What is the amount of money you get, if you split your raise ticks infinitely many times,
> decrease corresponding raise percentages accordingly?

This is a classic example of a limiting process which converges to the Euler's number $e=2,718281\dots$
If $S_0$ is the initial amount of money in your account, the after a single raise by $p$ percentage,
you will have $S_1=S_0(1+p)$. After the next raise by $p$ percentage, you will have 
$S_2=S_1(1+p)=S_0(1+p)^2$ amount of money. After $n$ times, you will have:
$$S_n=S_0(1+p)^n\;.$$
Since, each time you increase the amount of raises $n$ your percentage increment decreases, we 
can write $p=1/n$, and for infinitely large $n$, we have:
$$S_n=S_0\lim\limits_{n\to\infty}\left(1+\frac{1}{n}\right)^n=S_0\cdot e\;,$$
where we can see that after this process your money increases by the amount of 
$$\frac{S_n}{S_0}=e=2,7182818284\dots$$
This is the famous Euler's number.

### 2. Solving power equations

> **Problem:** Solve this simple equation: $2^x=8$

We can easily say, that the answer is $x=3$. Hence, 2 to the power of 3 is 8. In the language of
mathematics, it is written as:
$$x=\log_2 8=3\;,$$
Generally speaking, $x=\log_b a$ reads as *logarithm of a with base b*. Its meaning is, to what power
we should raise b (the base of logarithm) in order to get a. Hence, these two equations are identical:
$$b^x=a\;\;\;\leftrightarrow\;\;\;x=\log_b a\;.$$
So, the logarithm function is an inverse of the power function.

### 3. Logarithm characteristics

1. $\log_a 1 = 0$
2. $\log_a a = 1$
3. $\log_a(x\cdot y)=\log_ax+\log_ay$
4. $\log_a\frac{x}{y}=\log_ax-\log_ay$
5. $\log_ax^n=n\log_ax$
6. $\frac{\log_cb}{\log_ca}=\log_ab$
7. $\log_ax \ge 0\;, x \ge 1$
8. $\log_ax < 0\;, x < 1$

### 4. Problems

1. $\sqrt{5}\cdot0.2^{1/2x}-0.04^{1-x}=0\;.$
   > $x_1 = 1\;,\;\;x_2=1/4\;.$
2. $35\cdot 3^{x^2}-35\cdot5^{2x}-3^{x^2}+5^{2x}=0\;.$
   > $x_1=0\;,\;\;x_2=2\lg5/\lg3\;.$
3. $4^{\sqrt{x}}-9\cdot2^{\sqrt{x}-1}+2=0\;.$
   > $x = 4\;.$
4. $|x-2|^{x^2-2x}=|x-2|^{5x-10}\;.$
   >$x_1=1\;,\;\;x_2=3\;,\;\;x_3=5\;.$
5. $2(\lg x-\lg6)=\lg x-2\lg(\sqrt{x}-1)\;.$
   >$x=9\;.$
