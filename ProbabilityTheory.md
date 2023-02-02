
## Introduction to Probability Models by Ross - elementary probability theory and stochastic processes.
## Chapter 1, Introduction of probability theory
1.2) The definition of sample space and event:  

Any subset $E$ of the sample space $S$ is known as an event,

The definition of event occurs: the event E occurs when the outcome of the experiment lies in E,

The definition of mutually exclusive: the intersection of sets is zero,
The definition of the complement of $E$,

1.3) Probability defined as events:
For events $E_1$ $E_2$ $E_3$... that are mutually exclusive,  

$P(E_1\cup E_2...\cup E_N)=\sum P(E_i)$, for all i,

The intuition behind the probability: Namely, if our experiment is repeated over and over again then (with probability 1) the proportion of time that event E occurs will just be $P(E)$.

1.4 demonstrates a general formula of $P((E_1\cup E_2...\cup E_N)$, known as inclusion-exclusion identity.

1.4) Conidtional probability general formula:

$$P(E|F)= \frac{P(EF)}{P(F)}$$, and this is only well defined when $P(F)>0$,

1.6) Bayes' Formula:
$P(E)=P(EF)+P(EF^{c})$

$P(E)= P(E|F)P(F)+P(E|F^{c})P(F^{c})$

$P(E)= P(E|F)P(F)+P(E|F^{c})(1-P(F))$

which states that the probability of the event E is a weighted average of the conditional probability of E given that F has occurred and the conditional probability
of E given that F has not occurred, each conditional probability being given as much weight as the event on which it is conditioned has of occurring.

A more general of Bayes's formula can be written as:

$P(F_j|E)= \frac{P(EF_J)}{P(E)} $,

$P(F_j|E)= \frac{P(E|F_J) P(F_J)}{ \sum P(E|F_i) P(F_i)} $,

## Random Variables,











1) The Probability Distribution of Functions of Random Variables- and Jacobian determinant- refer to page 56
2) Moment generating functions of Random Variable - refer to page 58- Also with important charateristics of the sum of independent random variables.

3) Markov Identity: $P[X\geq a] \leq \frac{E[x]}{a}$ Proof in page 72
4) Chebyshev’s Inequality in page 72
5) Strong law of large numbers, page 73,
6) Central limit theorem, page 74 and Normal Approximation to the Binomial distribution 
7) heuristic proof of the central limit theorem，page 76,
8) STOCHASTIC PROCESS- page 84, stochastic process is a collection of random variable, definition of the state space, 
A stochastic process is a family of random variables that describes the evolution through time of some (physical) process.


## Chapter 3: Conditional Probability and Conditional expectation,

conditional expectation property,
