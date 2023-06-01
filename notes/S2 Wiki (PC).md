---
Class: Pre-Calculus
Type: Review / study guide
tags: wiki, S2, final, pre-calculus
date: Friday, May 26th 2023, 10:06:05 am
---
[[Final exam schedule]]
# Exam Topics
## Chapter 3
- Change of base formula
- Using logarithms to solve equations
- Fitting data with appropriate linear, power, exponential, or logarithmic functions
- The Gaussian function and normal distribution
## Chapter 4
- Concept of coterminal angles
- Conversion from degrees to radians and vice versa.
- The arc length formula
- The unit circle diagram and defining the trigonometric function by the unit circle
- The domain and range of all the trigonometric functions and their inverses
- Definition of the trigonometric functions by an arbitrary point along the terminal side of an angle
- Even-odd property, cofunction identities, and Pythagorean identities
- Find the values of other trigonometric functions when one trigonometric value is given
- Graphs of trigonometric functions and their transformations
- Inverse trigonometric functions
## Chapter 5
- Sum and difference formulas, double-angle formulas, power-reducing formulas, and half-angle formulas
- Verifying identities
- Solving trigonometric equations
# Exponential, Logarithmic, and Nonlinear Models
## Logistic Models
- Exponential growth with a limiting factor is often represented by the following model: $y=\frac{a}{1+be^{-rx}}$, called a logistic model, where $a$ is the limiting amount
>[!example] Example 1: on a college campus of 5,000 students, one student returns from vacation with a contagious flu virus.  The spread is modeled by $\bf{y=\frac{5,000}{1+4999e^{-0.8t}}}$ where $t\geq 0$ where $y$ is the total number of infected students after $t$ days
> 1. How many students are infected after 5 days?
> 	$$\begin{aligned}
> 	y=\frac{5000}{1+4999e^{(-0.8)(5)}} = 54.019 \space\text{students}
> 	\end{aligned}$$
> 2. After how many days are 250 students infected?
>  $$\begin{aligned}
250=\frac{5000}{1+4999e^{-0.8t}} \\
1+4999e^{-0.8t}=\frac{5000}{250} \\
\frac{{20-1}}{4999}=e^{-0.8t} \\
-0.8t=\ln(\frac{19}{4999}) \\
t\approx 7\space \text{days}
\end{aligned}$$

> [!example] Example 2: a population of rabbits has an initial value of 200. It has an estimated population limit of 2000 and a growth rate of 50%
> 1. Write a logistic model for the growth
> $$\begin{aligned}
> \text{a=2000, r=0.5, b=?} \\
> y=\frac{2000}{1+9e^{-0.5(2)}} \\
> 200 = \frac{2000}{1+be^{(-0.5)(0)}} \\
> 1+b=\frac{2000}{200} \rightarrow b=9 \\
>  y=\frac{2000}{1+9e^{-0.5x}}
\end{aligned}$$
> 2. How many rabbits will there be after 2 years according to the model?
> $$\begin{aligned}
> y=\frac{2000}{1+9e^{(-0.5)(2)}} \approx 464 \space \text{rabbits} 
> \end{aligned}$$
> 3. The local hunter will start being able to make a living off killing rabbits when the population reaches 1,000. After how much time will he be able to achieve this goal?
> $$\begin{aligned}
> 1,000=\frac{2,000}{1+9e^{-0.5x}} \\
> 1+9e^{-0.5x}=\frac{2000}{1000} \\
> \frac{{2-1}}{9}=e^{-0.5x} \\
> \ln{\frac{1}{9}}=-0.5x \\
> x\approx 4.39 \space \text{years}
> \end{aligned}$$
## Gaussian Models
- Parent gaussian function: $f(x)=e^{-x^2}$
- Transformed gaussian function: $g(x)=ae^{-(\frac{x-\mu}{b})^2}$
	- $a$ value controls the maximum
	- $b$ controls the "spread" of the curve
	- $\mu$ controls location of the maximum function value

- The area under a bell curve equals 1 one $a=\frac{1}{\sigma \sqrt{ 2\pi }}$ and $b=\sigma \sqrt{ 2 }$
- In statistics, when the bell curve is normal distribution, $g(x)=\frac{1}{\sigma \sqrt{ 2\pi }}e^{-(\frac{x-\mu}{\sigma2\pi})^2}$
	- The $\sigma$ value is the standard deviation of the curve
	- The $\mu$ value is the mean of the standard distribution
- To show standard deviation in gaussian graphs, draw 2 vertical lines around the mean, both $\sigma$ distance away from the mean, then add the 2nd & 3rd standard deviations
	![[Pasted image 20230526143330.png|]]
> [!example] Example Identify the standard deviation ($\sigma$ value) of the function $\bf{f(x)=\frac{1}{\sqrt{ 32\pi }}e^{-(\frac{x}{\sqrt{ 32 }})^2}}$
> $$\begin{aligned}
> \sqrt{32}=\sigma \sqrt{ 2 } \\
> \sqrt{ 16\times 2 }= \sigma \sqrt{ 2 } \\
> =4\sqrt{ 2 } \\
> \sigma =4
> \end{aligned}$$
- To show standard deviation in gaussian graphs, draw 2 vertical lines around the mean, both $\sigma$ distance away from the mean, then add the 2nd & 3rd standard deviations
# Log & Exponential Equations
## Logarithm Rules
1. Product rule: $\ln{xy}=\ln{x}+\ln{y}$
2. Quotient rule: $\ln {\frac{x}{y}}=\ln{x}-\ln{y}$
3. Power rule: $\ln{x^y}=y\ln{x}$
4. Log of $e$: $\ln{e}=1$
5. Log of 1: $\ln{1}=0$
6. Log reciprocal: $\ln{\frac{1}{x}}=-\ln{x}$
## Change of Base Formula
- $\log_{a}b=\frac{{\log_{c}b}}{\log_{c}a}$
- $\log_{5}12=\frac{{\log_{10}12}}{\log_{10}5}$
# ![[Intro 2 trig]]
# ![[Graphing trig functions]]
# Solving Trigonometric Equations
## Sum/difference Formulas
- $\sin(\theta\pm \phi)=\sin \theta \cos \phi \pm \cos \theta \sin \phi$
- $\cos(\theta\pm \phi)=\cos \theta \cos \phi\mp \sin \theta \sin \phi$
- $\tan(\theta\pm \phi)=\frac{{\tan \theta\pm \tan \phi}}{1\mp \tan \theta \tan \phi}$
## Double Angle Identities
- $\sin2\theta=2\sin \theta \cos \theta$
- $\cos{2}\theta=$
	1. $\cos^2\theta-\sin^2\theta$
	2. $2\cos^2\theta-1$
	3. $1-2\sin^2\theta$
- $\tan2\theta=\frac{{2\tan \theta}}{1-\tan^2\theta}$
## Half Angle Identities
- $\sin \frac{\theta}{2} =\pm \sqrt{ \frac{{1-\cos \theta}}{2} }$
- $\cos \frac{\theta}{2}=\pm \sqrt{ \frac{{1+\cos \theta}}{2} }$
- $\tan\frac{\theta}{2}=\frac{{1-\cos \theta}}{\sin \theta}$
## Power Identities
- $\sin^2\theta=\frac{{1-\cos2\theta}}{2}$
- $\cos^2\theta=\frac{{1+\cos2\theta}}{2}$
- $\tan^2\theta=\frac{{1-\cos \theta}}{1+\cos \theta}$
## Cofunction Properties
- $\sin(\frac{\pi}{2}-x)=\cos x$
- $\cos(\frac{\pi}{2}-x)=\sin x$
- $\tan(\frac{\pi}{2}-x)=\cot x$
- $\cot(\frac{\pi}{2}-x)=\tan x$
# Review Packet Solutions
![[pre calc final exam review solutions.pdf]]