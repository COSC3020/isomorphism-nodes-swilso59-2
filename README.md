# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Answer 
Direct Proof:
- If we have two graphs $A$ and $B$.
  - $A$ has a set of vertices $V_{A}$ set of edges $E_{A}$.
  - $B$ has a set of vertices $V_{B}$ set of edges $E_{B}$.
  - $|V_{A}| = m$ and $|V_{B}| = n$, where $m \neq n$.
- If we assome ethat $m < n$, So graph $A$ has fewer vertex then graph $B$.
- our function $f: V_{A} \rightarrow V_{B}$ must satisfy the conditions of bijection. 
  - There are more vertices in $B$ than in $A$. This makes it impossible for every vertex in $B$ to be mapped to by a vertex in $A$.
  - This breaks the onto condition of bijection.
- If the funtion is onto you would need to at least map one vertex from $A$ to multiple vertex in $B$.
  - This would cause a violation of the one-to-one condition of bijecton condition.
-  This shows that two graphs that do not have the same number of nodes cannot be isomorphic.


This assignment I adapted the counter example I used to gain understanding of the isomorphism condition. This counter example was an idea I origninally got from https://github.com/COSC3020/isomorphism-connectivity-DJReflexive.

“I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.”
