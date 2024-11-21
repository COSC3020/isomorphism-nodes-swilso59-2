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
- If we have two graphs $H_{1}$ and $H_{2}$.
  - $H_{1}$ has 3 vertices $(A, B, C)$ and one edge $(A, B)$.
  - $H_{2}$ has 4 vertices $(1, 2, 3, 4)$ and one edge $(1, 2)$.
- There is no one-to-one and onto mapping between $H_{1}$ and $H_{2}$.
- There is no vertex in $H_{1}$ that can correspond to 4 in $H_{2}$.
- This violates the bijection requirement.
  - There are more vertices in $H_{2}$ than in $H_{1}$. This makes it impossible for every vertex in $H_{2}$ to be mapped to by a vertex in $H_{1}$.
  - This breaks the onto condition of bijection.
-  This shows that two graphs that do not have the same number of nodes cannot be isomorphic.

This assignment I adapted the counter example I used to gain understanding of the isomorphism condition. This counter example was an idea I origninally got from https://github.com/COSC3020/isomorphism-connectivity-DJReflexive.

“I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.”
