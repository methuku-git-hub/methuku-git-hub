# Abhishek Methuku

I work in **probabilistic and extremal combinatorics**.

[Website](https://sites.google.com/view/abhishekmethuku/home) · [Publications](https://sites.google.com/view/abhishekmethuku/research) · [Google Scholar](https://scholar.google.com/citations?user=cJOfkakAAAAJ&hl=en)

## Research projects

### [Sharp Dirac thresholds for the generalized Oberwolfach problem](https://github.com/methuku-git-hub/generalized-oberwolfach-lean)

**Paper authors:** Dong Yeap Kang, Abhishek Methuku and Pablo Oviedo.

The repository formalizes the paper’s main theorem in Lean.

[Lean formalisation (Palomar; registered 18 November 2026)](https://palomar-registry.org/entry.html?id=PALOMAR-2026-11-18-000003&version=1)

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

### [Independent sets in hypergraphs with no loose triangle](https://github.com/methuku-git-hub/Independent-sets-in-hypergraphs-with-no-loose-triangle)

**Paper authors:** Ayush Basu, Abhishek Dhawan and Abhishek Methuku.

The repository formalizes the paper’s independent-set theorem in Lean, assuming the stated Li–Postle coloring theorem.

[Lean formalisation (Palomar; registered 27 October 2026)](https://palomar-registry.org/entry?id=PALOMAR-2026-10-27-000016&version=1)

**Paper abstract**

An $r$-uniform loose triangle $C_3$ consists of three edges that intersect pairwise in exactly one vertex and have no vertex common to all three.
For graphs, this is the usual triangle, and the Ramsey number $R(C_3,K_t)$ has order of magnitude $t^2/\log t$ by celebrated results of Ajtai, Komlós, and Szemerédi and of Kim.

Kostochka, Mubayi, and Verstraëte proved that $R(C_3,K_t^{(r)})=O_r(t^{3/2})$ for every fixed $r\ge3$ and showed that this bound is sharp up to a logarithmic factor.
Motivated by the logarithmic saving in the graph case, they conjectured in 2013 that the upper bound could be improved to $o(t^{3/2})$.
This conjecture has since received significant attention and has been reiterated in several papers.
We prove the conjecture by showing that, for every fixed $r\ge3$,

$$
R(C_3,K_t^{(r)}) =O_r\left(\frac{t^{3/2}}{\sqrt{\log\log t}}\right).
$$

### [Nearly linear directed cycles in vertex-transitive digraphs](https://github.com/methuku-git-hub/Nearly-linear-directed-cycles-in-vertex-transitive-digraphs)

**Paper authors:** Bowen Li and Abhishek Methuku.

The repository formalizes the near-linear cycle theorem in Lean; the paper’s construction of examples with a linear gap is outside its scope.

[Lean formalisation (Palomar; registered 27 October 2026)](https://palomar-registry.org/entry?id=PALOMAR-2026-10-27-000007&version=1)

**Paper abstract**

The search for Hamiltonian cycles in vertex-transitive graphs and digraphs is a classical problem at the interface of graph theory and group theory. Trotter and Erdős showed in 1978 that connected vertex-transitive digraphs need not be Hamiltonian. In light of this result, Alspach asked in 1981 whether their longest directed cycles can miss arbitrarily many vertices. Bucić, Hendrey, Mohar, Steiner and Yepremyan recently answered this question by constructing examples in which the longest directed cycle omits $(1-o(1))\log n$ vertices, and conjectured that the number omitted can be linear. We confirm their conjecture by constructing infinitely many connected vertex-transitive digraphs on $n$ vertices whose longest directed cycle omits at least $n/12$ vertices.

We also prove that every connected vertex-transitive digraph on $n$ vertices contains a directed cycle of length $n^{1-o(1)}$. The proof uses a structural theorem of Tessera and Tointon to partition the vertices into equal-sized sets of small undirected diameter. For large parts, we join short directed paths while controlling their intersections. For small parts, we use the group structure of the quotient to construct a long cycle and choose the walks replacing its edges so that the resulting cycle has no repeated vertices.

[Browse all repositories →](https://github.com/methuku-git-hub?tab=repositories)
