# Abhishek Methuku

I work in **probabilistic and extremal combinatorics**.

[Website](https://sites.google.com/view/abhishekmethuku/home) · [Publications](https://sites.google.com/view/abhishekmethuku/research) · [Google Scholar](https://scholar.google.com/citations?user=cJOfkakAAAAJ&hl=en)

## Research projects

### [Nearly linear directed cycles in vertex-transitive digraphs](https://github.com/methuku-git-hub/Nearly-linear-directed-cycles-in-vertex-transitive-digraphs)

**Paper authors:** Bowen Li and Abhishek Methuku.

The repository formalizes the near-linear cycle theorem in Lean; the paper’s construction of examples with a linear gap is outside its scope.

[Lean formalisation (Palomar; registered 27 October 2026)](https://palomar-registry.org/entry?id=PALOMAR-2026-10-27-000007&version=1)

**Paper abstract**

The search for Hamiltonian cycles in vertex-transitive graphs and digraphs is a classical problem at the interface of graph theory and group theory. Trotter and Erdős showed in 1978 that connected vertex-transitive digraphs need not be Hamiltonian. In light of this result, Alspach asked in 1981 whether their longest directed cycles can miss arbitrarily many vertices. Bucić, Hendrey, Mohar, Steiner and Yepremyan recently answered this question by constructing examples in which the longest directed cycle omits $(1-o(1))\log n$ vertices, and conjectured that the number omitted can be linear. We confirm their conjecture by constructing infinitely many connected vertex-transitive digraphs on $n$ vertices whose longest directed cycle omits at least $n/12$ vertices.

We also prove that every connected vertex-transitive digraph on $n$ vertices contains a directed cycle of length $n^{1-o(1)}$. The proof uses a structural theorem of Tessera and Tointon to partition the vertices into equal-sized sets of small undirected diameter. For large parts, we join short directed paths while controlling their intersections. For small parts, we use the group structure of the quotient to construct a long cycle and choose the walks replacing its edges so that the resulting cycle has no repeated vertices.

### [Independent sets in hypergraphs with no loose triangle](https://github.com/methuku-git-hub/Independent-sets-in-hypergraphs-with-no-loose-triangle)

**Paper authors:** Ayush Basu, Abhishek Dhawan and Abhishek Methuku.

The repository formalizes the paper’s independent-set theorem in Lean, assuming the stated Li–Postle coloring theorem.

[Lean formalisation (Palomar; registered 27 October 2026)](https://palomar-registry.org/entry?id=PALOMAR-2026-10-27-000016&version=1)

**Paper abstract**

A loose triangle consists of three edges whose pairwise intersections are distinct single vertices. An independent set in a hypergraph is a set of vertices containing no edge. We prove that, for every fixed $r\ge3$, there is a constant $c_r>0$ such that every sufficiently large $n$-vertex hypergraph with no loose triangle and with edge sizes between $3$ and $r$ has an independent set of size at least $c_r n^{2/3}(\log\log n)^{1/3}$. This implies that the Ramsey number of the $r$-uniform loose triangle versus the complete $r$-uniform hypergraph on $t$ vertices is at most $C_r t^{3/2}/\sqrt{\log\log t}$ for a constant $C_r>0$ and all sufficiently large $t$, proving a conjecture of Kostochka, Mubayi and Verstraëte from 2013. The proof chooses vertices randomly while avoiding pairs that lie in many edges, and then deletes vertices to eliminate all triples of edges for which each pair intersects outside the third edge. A theorem of Li and Postle then yields the required independent set.

### [Sharp Dirac thresholds for the generalized Oberwolfach problem](https://github.com/methuku-git-hub/generalized-oberwolfach-lean)

**Paper authors:** Dong Yeap Kang, Abhishek Methuku and Pablo Oviedo.

The repository formalizes the paper’s main theorem in Lean.

**Paper abstract**

We prove an asymptotically sharp Dirac-type generalization of the
Oberwolfach problem posed by Ringel in 1967, allowing decompositions
into a prescribed list of possibly different spanning $2$-regular graphs.

For $r\ge3$, let $C_r$ denote the cycle of length $r$, and let $\delta_{C_r}$ denote the asymptotic minimum-degree threshold for a $C_r$-decomposition, that is, the infimum of $d\in[0,1]$ such that every sufficiently large $n$-vertex graph $G$ with $\delta(G)\ge dn$, all vertex degrees even and $r\mid e(G)$ has a $C_r$-decomposition.

For any nonempty set $\mathcal S\subseteq\{3,4,\ldots\}$ and $\alpha>0$, we show that every sufficiently large $n$-vertex $D$-regular graph with $D$ even and $D\ge(\sup_{r\in\mathcal S}\delta_{C_r}+\alpha)n$ admits an edge-decomposition into any prescribed list $F_1,\ldots,F_{D/2}$ of $2$-regular $n$-vertex graphs whose cycle lengths belong to $\mathcal S$.
The degree condition is asymptotically best possible.

Results of Barber–Kühn–Lo–Osthus on even cycles and of Delcourt–Postle, Granet–Horsley, Hou–Hu–Wang and Granet–Horsley–Santrio on odd cycles determine the cycle-decomposition thresholds:

$$
 \delta_{C_r} =
 \begin{cases}
  2/3,&r=4,\\
  1/2,&r\ge6\text{ even},\\
  1/2+1/(2r-2),&r\ge3\text{ odd}.
 \end{cases}
$$

In particular, $D\ge(3/4+\alpha)n$ suffices for any prescribed list of spanning $2$-regular graphs.
Our theorem settles, in a stronger form, conjectures of Glock–Joos–Kim–Kühn–Osthus (*J. Eur. Math. Soc.*, 2021) and Glock–Kühn–Osthus (*Surveys in Combinatorics 2021*) on sharp Dirac thresholds for the Oberwolfach problem.
It also determines the sharp asymptotic degree threshold for resolvable cycle decompositions of regular graphs.

[Browse all repositories →](https://github.com/methuku-git-hub?tab=repositories)
