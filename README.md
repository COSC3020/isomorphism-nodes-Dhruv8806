[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12767835&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


To prove that if two graphs, $A$ and $B$, with different numbers of nodes that cannot be isomorphic, we can use a proof by contradiction. According to the definition of isomorphism, the condition is the presence of a onto function (bijection) between the nodes of $A$ and $B$. However, this condition cannot be satisfied when the node counts in $A$ and $B$ are not the same. Let's assume that $A$ has more nodes than $B$. In this scenario, the function can map nodes from $A$ to $B$, but there will be nodes in $B$ that don't have matches in $A$, which goes against the bijection requirement. Similarly, if $B$ has more nodes than $A$, not every node in $A$ can have a unique match in $B$. Therefore, the two graphs, $A$ and $B$, have different numbers of nodes.

Sources used: TA
