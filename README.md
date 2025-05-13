# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Answer

When we have two complete graphs A and B with the same number of nodes:

Graph A = $(V_1, E_1)$ with $|V_1| = n$
Graph B = $(V_2, E_2)$ with $|V_2| = n$

Since $|V_1| = |V_2| = n$, we can define any bijection f between their vertices.
In a complete graph, every vertex is connected to every other vertex. This means:

For any u, v ∈ V₁ where u ≠ v: (u, v) ∈ E₁, For any x, y ∈ V₂ where x ≠ y: (x, y) ∈ E₂, For any chosen bijection f:

If (u, v) ∈ E₁, then u ≠ v, which means f(u) ≠ f(v), and therefore (f(u), f(v)) ∈ E₂, If (f(u), f(v)) ∈ E₂, then f(u) ≠ f(v), which means u ≠ v, and therefore (u, v) ∈ E₁

This shows that any bijection f still has the edge relationships.

Sooo...
Any two complete graphs with the same # of nodes are isomorphic because any bijection between their vertex sets will preserve the edge relationships.
Note: This property is specific to complete graphs. Non-complete graphs with the same number of nodes are not necessarily isomorphic, as shown in the example with graphs having edges E₁ = {(1,2), (2,3)} and E₂ = {(a,b), (b,c)}. In that case, only certain bijections (like f(1) = a, f(2) = b, f(3) = c) preserve the edge relationships.

I did copy and paste the symbols after googling: "bijective symbols and discrete symbols list"

[GeeksforGeeks](https://www.geeksforgeeks.org/bijective-function/)

"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."
