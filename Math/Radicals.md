# Radicals

## Definition
If $a$ is a positive integer that is greater than 1 and a is a real number then,

$$ x = \sqrt{a} \Leftrightarrow x \geq 0 \land x^2 = a $$
$$\sqrt[n]{a} = a^{\frac{1}{n}} $$
where $n$ in called the **index** and the sumbol $\sqrt{\phantom{x}}$ is called the **radical**

The evaluation of a square root always result in a positive answare as a general rule. Considering for example $\sqrt{16}$ the result could be (-4) and 4 but the correct answare is 4 because -4 is obtained with $-\sqrt{16}$

It is possible to write the general rational exponent it terms of radicals as follows:
$$a^{\frac{m}{n}} = (a^{\frac{1}{n}})^m = (\sqrt[n]{a}) ^ m$$
Two radicals are equals when they represent the same number, in general, in order to obtain an equivalent radical it is sufficient to multiply the exponent of the number under the radical and the index of the radical for the same number $p$ greater than 0.
$$\sqrt[n]{a^m} = \sqrt[n \cdot p]{a ^ {m\cdot p}}$$
$$\sqrt[n]{a^m} = \sqrt[\frac{n}{p}]{a^\frac{m}{p}}$$

## Properties
### Main Properties
For appropriate values of (a), (b), (m), and (n):

$$
	\begin{gather*}
	\sqrt[n]{a^n} = a \\
	\sqrt[n]{ab} = \sqrt[n]{a}\sqrt[n]{b} \longrightarrow \sqrt{a}\sqrt{a} = \sqrt{a^2} = a \\
	\sqrt[n]{\frac{a}{b}} = \frac{\sqrt[n]{a}}{\sqrt[n]{b}} \\
	(\sqrt[n]{a})^m = \sqrt[n]{a^m} \\
	\sqrt[n]{\sqrt[m]{a}} = \sqrt[nm]{a} \\
	\sqrt[n]{a^nb} = a\sqrt[n]{b} \\
	\sqrt[n]{a^{nx}b} = a^x\sqrt[n]{b} \\
	a^{-\frac{m}{n}} = \frac{1}{\sqrt[n]{a^m}} \\
	\sqrt[n]{a^{nx+k}} = a^x\sqrt[n]{a^k} \\
	\end{gather*}
$$

### Sum of Radicals
While we can "break up" products and quotients it is not possible to do the same for sum or differences
$$
	\begin{gather*}
	\sqrt[n]{a+b} \neq \sqrt[n]{a} + \sqrt[n]{b} \\
	AND \\
	\sqrt[n]{a-b} \neq \sqrt[n]{a} - \sqrt[n]{b}    
	\end{gather*}
$$
it is possible to write that
$$\sqrt{a}+\sqrt{b} \geq \sqrt{a+b}$$
and more in general
$$\sqrt[n]{a}+\sqrt[n]{b} \geq \sqrt[n]{a+b}$$
another usefull trick to sum radicals could be the following one:
$$a\sqrt[n]{k} + b\sqrt[n]{k} = (a+b)\sqrt[n]{k} \ \text{with} \ k > 0$$

### Double Quadratic Radicals
$$\sqrt{a \pm \sqrt{b}} = \sqrt{\frac{a+\sqrt{a^2 - b}}{2}} \pm \sqrt{\frac{a-\sqrt{a^2 - b}}{2}}$$

### Irreducible Radical
A radical is considered irreducible when the index and the exponent of the term under the radical
does not have a common divider.
$\sqrt[3]{a^2}$ can't be reduced. 
$\sqrt[6]{a^4}$ can be reduced: $\sqrt[\frac{6}{2}]{a^\frac{4}{2}} = \sqrt[3]{a^2}$

In order to transform two or more radicals with different indexes into equivalent radicals
1. Find the Least Common Multiple
2. Transform every radical in an equivalent radical with the index equal to the Least Common Multiple
$\sqrt[4]{a^3} \ \sqrt[6]{b}$
LCM(4,6) = 12 $\sqrt[4*3]{(a^3)^3}\sqrt[6*2]{(b)^2} = \sqrt[12]{9}\sqrt[12]{b^2}=\sqrt[12]{a^9b^12}$
if $a$ and $b$ are equals the expression can be further simplified

### Edge Cases
$$
	\begin{gather*}
	\sqrt[1]{a} = a^1 = a \\
	\sqrt[n]{0} = 0^n = 0 \\
	\sqrt[n]{1} = 1^n = 1 \\
	\sqrt[n]{0} = undefinedd \\
	\sqrt[even]{a<0} = undefined
	\end{gather*}
$$

### Simplified Radical Form
In order to transform any radical in its simples form, there are 4 steps:
1. All exponents in the radical must be less than the index
2. Any exponents in the radical can have no factors in common with the index
3. No fractions appear under a radical
4. No radicals appear in the denominator of a fraction

### Radical as a function
|             If n is odd             	|                      If n is even                     	|
|:-----------------------------------:	|:-----------------------------------------------------:	|
| $\mathbb{R} \rightarrow \mathbb{R}$ 	| $\mathbb{R}_{\geq 0} \rightarrow \mathbb{R}_{\geq 0}$ 	|
|       $x \mapsto \sqrt[n]{x}$       	|                $x \mapsto \sqrt[n]{x}$                	|

The equations with the form $x^n+b = 0$ with an even $n$ and $b>0$ do not have solution in $\mathbb{R}$ but do have solution in $\mathbb{C}$
$x^2 + 4 = 0;\ x^2 = -4;\ x= \pm 2i$

### Graph of a Radical
Square root:
![[Square_root_graph.jpg]]
Cubic root:
![[Cubic_root_graph.jpg]]

### Radical function as opposite to power function

The square root of a number does exist in  $\mathbb{R}$  if and only if the number is non-negative, so it is necessary to define the condition of existance of a square root. The conditions of existance specifies the values for which the radical is defined.  

Considering the polinomyal $P(x)$, $\sqrt{P(x)}$ is defined for each value of $x$ where $P(x) > 0$

### Condition of existance
- $\sqrt{x+3}$ it is defined for  $x+3 \geq 0$
- $\sqrt{x^2+2x+1}$ it is defined for each $x\in\mathbb{R}$
- $\sqrt{3-x}+\sqrt{x+1}$ it is defined is both the radicals are defined so for $-1 \leq x \leq 3$
-  $\sqrt{\frac{x+1}{x-2}} \qquad \frac{x+1}{x-2}$  Numerator and denominator need to have the same sign to make the fraction positive. 
	$
	\begin{cases}
		x+1 \ge 0 \\
		x-2 > 0
	\end{cases}
	\quad \Rightarrow \quad
	\begin{cases}
		x \ge -1 \\
		x > 2
	\end{cases} \\
	$
	
	$
	\begin{cases}
		x+1 < 0 \\
		x-2 < 0
	\end{cases}
	\quad \Rightarrow \quad
	\begin{cases}
		x \le -1 \\
		x < 2 \\
	\end{cases} \\
	$
	
	$x \le -1 \lor x > 2$

### Radical with variable index
$\sqrt[n]{\frac{x+3}{x^3-1}}$
- If the index is even, it is necessary to extract the condition of existance by the disequation 
  $\frac{x+3}{x^3-1} \ge 0 \quad \Rightarrow \quad x > 1 \;\lor\; x \le -3$
- If the index is odd, it is sufficent to extract the condition of existance only from the denominator
  $x^3 - 1 \ne 0 \quad \Rightarrow \quad x \ne 1$ù

### Techniques
- $\sqrt{y^7} = \sqrt{(y^3)^2 \, y} = \sqrt{(y^3)^2}\sqrt{y} = y^3\sqrt{y}$
  This scomposition is usefull if the exponent is odd and larger than the index and we want to obtain a simplified radical form.
- $\sqrt[9]{x^6} = (x^6)^{\frac{1}{9}} = x^{\frac{6}{9}} = x^{\frac{2}{3}}= (x^2)^{\frac{1}{3}} = \sqrt[3]{x^2}$
- $\sqrt{18x^6y^{11}} = \sqrt{(2y)\cdot 9 \cdot (x^3)^2 \cdot (y^5)^2} = \sqrt{2y}\,\sqrt{9}\,\sqrt{(x^3)^2}\,\sqrt{(y^5)^2} = \sqrt{2y}\,3x^3\,y^5$
  If possible, decompose the expression to expose perfect quares or, if the index if different from 2, try to obtain squares that are multiple of the index.
- $\sqrt[3]{9x^2}\,\sqrt[3]{6x^2} = \sqrt[3]{9x^2 \cdot 6x^2}  = \sqrt[3]{54x^4} = \sqrt[3]{27x^3 \cdot 2x} = \sqrt[3]{27x^3}\sqrt[3]{2x} = 3x\sqrt[3]{2x}$
  Sometimes putting together two simplified expression bring to an even simpler one.
- $\frac{4}{\sqrt{x}} = \frac{4}{\sqrt{x}}\cdot\frac{\sqrt{x}}{\sqrt{x}} = \frac{4\sqrt{x}}{x}$
  Rule 4 of simplification
- $\frac{\sqrt[5]{2}}{\sqrt[5]{x^3}} = \frac{\sqrt[5]{2}}{\sqrt[5]{x^3}} \cdot \frac{\sqrt[5]{x^2}}{\sqrt[5]{x^2}} = \frac{\sqrt[5]{2x^2}}{x}$
  In order to respect rule number 2 and 4 for simplification, the exponent of the denominator is matched with the index of the radical and than simplified
- $\frac{1}{3-\sqrt{x}} = \frac{1}{3-\sqrt{x}}\cdot\frac{3+\sqrt{x}}{3+\sqrt{x}}= \frac{3+\sqrt{x}}{9-x}$
  Rule 4 for simplification achieved using sum by difference
- $(\sqrt{a}+\sqrt{b})(\sqrt{a}-\sqrt{b}) = a-b$
- $(\sqrt{a}+\sqrt{b})^{-1} = \frac{1}{\sqrt{a}+\sqrt{b}} = \frac{\sqrt{a}-\sqrt{b}}{a-b}$
  Rationalization used to achieve rule 4 for simplification
- $(\sqrt{a}-\sqrt{b})^2 = a+b-2\sqrt{ab}$
  It is possible to extract a "hidden" binomial from expressio similar to:
 
  $
  \sqrt{5-2\sqrt{6}} \quad
  \begin{cases}
	  a+b=5\\
	  ab=6
  \end{cases}
  \Rightarrow
  \begin{cases}
        a=3\\
        b=2
\end{cases} \quad
\sqrt{5-2\sqrt{6}} = \sqrt{3}-\sqrt{2}
$
- $\frac{1}{\sqrt{2}+\sqrt{3}+\sqrt{5}}$
  Can be solved by grouping the denominator in order to obtain a sum by difference
  $\frac{1}{(\sqrt{2}+\sqrt{3})+\sqrt{5}} \cdot \frac{(\sqrt{2}+\sqrt{3})-\sqrt{5}}{(\sqrt{2}+\sqrt{3})-\sqrt{5}} = \frac{\sqrt{2}+\sqrt{3}-\sqrt{5}}{(\sqrt{2}+\sqrt{3})^2-5} = \frac{\sqrt{2}+\sqrt{3}-\sqrt{5}}{2\sqrt{6}} = \frac{\sqrt{2}+\sqrt{3}-\sqrt{5}}{2\sqrt{6}} \cdot \frac{\sqrt{6}}{\sqrt{6}} \\ \\ = \frac{(\sqrt{2}+\sqrt{3}-\sqrt{5})\sqrt{6}}{12} \, \dotsb$
  
  
  
  


   