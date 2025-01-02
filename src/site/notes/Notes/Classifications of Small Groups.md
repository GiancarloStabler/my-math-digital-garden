---
{"dg-publish":true,"permalink":"/notes/classifications-of-small-groups/"}
---

#abstract-algebra/group-theory #note

### Groups with one element
Since all [[Notes/Group\|groups]] must contain $e$, this is the trivial group,
$$
G=\{g\} \rightarrow G = \{e\}.
$$

### Groups with two elements
Must contain $e$ and one more element $g$. Therefore, $g=g^{-1}$,
$$
G = \{ e,g \}\quad e\neq g, g=g^{-1}.
$$
###### Example
$(\mathbb{Z}_{2},+)$ is a group with two elements.
###### Related Theorem
[[Notes/Theorem - The inverse of the identity element is itself\|Theorem - The inverse of the identity element is itself]]

### Groups with three elements
$$
G = \{ e,g,g^{-1} \}.
$$

### Groups with four elements
There are two types of groups with 4 elements.
##### Isomorphic to $(\mathbb{Z}_4,+)$ 
$$
\begin{array}{c | c c c c}
+ & 0 & 1 & 2 & 3 \\
\hline
0 & 0 & 1 & 2 & 3 \\
1 & 1 & 2 & 3 & 0 \\
2 & 2 & 3 & 0 & 1 \\
3 & 3 & 0 & 1 & 2
\end{array}
$$


##### Isomorphic to $(\mathbb{Z}_{2}\times \mathbb{Z}_{2},+)$
- Also called the Klein four-group.
- Every element is its own inverse.
$$
\begin{array}{c | c c c c}
+ & (0,0) & (0,1) & (1,0) & (1,1) \\
\hline
(0,0) & (0,0) & (0,1) & (1,0) & (1,1) \\
(0,1) & (0,1) & (0,0) & (1,1) & (1,0) \\
(1,0) & (1,0) & (1,1) & (0,0) & (0,1) \\
(1,1) & (1,1) & (1,0) & (0,1) & (0,0)
\end{array}
$$

### Commutativity
[[Notes/Theorem - The smallest non-abelian group has order 6.\|Theorem - The smallest non-abelian group has order 6.]]
