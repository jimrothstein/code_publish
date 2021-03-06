
<!--
file <- "500_Bayes_Theorem.md"
This is markdown file.
Using print_pdf.sh %  out.pdf   pandoc will produce .pdf files with appropriate
latex packages.
-->

%	latex comment

\therefore

This classic problem of population where each individual is either  Healthy or
has a Disease.

The overall population is also tested, with some false positives and some false
negatives.

We are asked to calculate the odds that a person with a positive test actually
is healthy (a false positive).


### Counting Problem.

Let N be population.

We are told that 5% of population has the disease.   So probably of being
healthy is:


$$  P(H) = .95 $$

$$  P(D) = .05 $$

So the number healthy 
$$ N_h = N * P(H) $$

$$	P(n \mid H) * N_h = P(n \mid H) * P(H) * N $$

We are told the test has false positive and negative rate of 1%.

Number of people healthy and test - is: 
$$ P(- \mid H) * N_h $$

<!--

$\Pr{A=a} = \Pr{B=b \given C=c}$

\[ \Pr(A{=}a) = \Pr(B{=}b \mid C{=}c) \]





-->	


\newpage
Suppose 3% of population plays decent chess (is 'good' player or better).
And suppose that 1% of the population drives a truck.   We are told that for
every 300 trucker drivers, 1 plays decent chess. 

Now you are asked what percent of descent chess players also drives a truck.

Diagram



$$	
T = set of trucker drivers
C = set of descent chess players

N_T = Number of trucker drivers
N_C = Number of decent chess players

N = entire population

N_T = 1% * N
N_C = 3% * N

N_T,_C = 1/300 * N_T
$$

Solution I

If T is set of truck drivers, the problem tells us that 1 our of 300 will also
play descent chess.   In math terms,  $\intersect{T}{C}$ is 1 out of 300
drivers.

If you think about it, this is the same number as the number of descent chess players who
drive a truck.  This same as 
$$\intersect{C}{T}$$


In other words, 
$$\intersect{C}{T} = \intersect{C}{T}$$

$$\frac{1}{300}*N_T = x * N_C$$





\newpage
$$P(\theta \mid X)$$

Let V be vector space and B be basis.

$$	\vec{p} $$

dot product

    $$ \vec{p}\cdot\vec{q}=|\vec{p}|\vec{q}|cos\theta $$

magnitude
$$ \left| \vec{a} \right| $$

unit vector
$$ \hat{a}=\frac{\vec{a}}{\left | \vec{a} \right |} $$

matrix:

$$
  \begin{matrix}
    a & b\\
    c & d 
  \end{matrix}
$$

matrix with subscripts
$$
  \begin{matrix}
    a_{11} & a_{12}\\ 
    a_{21} & a_{22}
  \end{matrix}
$$

matrix with square brackets (bmatrix)
\begin{equation}
\begin{bmatrix}
     1\\ 
     0\\
     0 
\end{bmatrix}
\end{equation}


matrix with dots ...

\begin{document}
\begin{equation}
 \begin{bmatrix} 
   a_{1} \\ \vdots \\ a_{n} 
\end{bmatrix}
\end{equation}

\begin{equation}
\begin{bmatrix}
     a_{11} & a_{12} & a_{13}\\ 
     a_{21} & a_{22} & a_{23}\\
     a_{31} & a_{32} & a_{33} 
\end{bmatrix}
\end{equation}
