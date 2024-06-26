---
layout: page
title: For students
icon: fa-solid fa-graduation-cap
math: true
order: 4
---

> We warmly welcome all students participating in BSc and MSc programs, whether from BME or another institution, to prepare their thesis, diploma project, or TDK (Scientific Students' Associations Conference) paper related to quantum algorithms.
{: .prompt-tip }

## Previous work

Check out previous students' work [here]({{ site.baseurl }}/thesises).

## Project proposals

### Quantum algorithms

[https://doktori.hu/index.php?menuid=195&lang=HU&tk_ID=100066](https://doktori.hu/index.php?menuid=195&lang=HU&tk_ID=100066)

In the late 1970s, physicists proposed that since quantum mechanical phenomena could not be efficiently simulated with computers, perhaps a machine that also builds on quantum effects could solve certain problems faster. This idea gave birth to a new mathematical model of computation, the quantum Turing machine.

One of the most interesting capabilities of the quantum Turing machine is its ability to follow exponentially many computational paths simultaneously. However, the difficulty lies in extracting the result (e.g. whether there is an accepting computational path) due to the model's (and physics') rules. This new model requires ideas and techniques different from the usual algorithmic solutions. Its power is demonstrated, for example, by the fact that a quantum Turing machine can find the prime factors of a number in polynomial time (no such algorithm is known for classical Turing machines), and that searching among $n$ unordered elements can be done in $\Theta(\sqrt{n})$ time. The main question in the field is which types of tasks admit to a significantly more efficient quantum algorithmic solution and which are the ones the technique does not help.

The goal of the research is to examine existing algorithmic methods, develop them further, and investigate their applicability. For example to give quantum algorithmic equivalents to classical algorithms for bipartite matching, spanning trees, or network flows, and determining the extent to which they can be accelerated.

### Quadratic optimization on the adiabatic quantum computer

QUBO stands for Quadratic Unconstrained Binary Optimization, which is an optimization technique more general than linear programming as it allows for quadratic terms in the objective function. Adiabatic quantum computers, which perform computations through quantum physical processes, are suitable for solving optimization tasks written in a QUBO format.

An important question in this topic is how to efficiently represent more complex mathematical structures, such as graphs in this way. The difficulty lies in the practical constraint that the objective function cannot be arbitrarily complex, with a strict limitation on the number of allowed interactions (quadratic terms) between variables. These relationships can be represented as a graph, that must be embedded into the graph given by the hardware of the adiabatic quantum computer. Often, this can only be achieved by cleverly reformulating the objective function, introducing new variables and special terms.

### Quantum walks and search algorithms

Classical random walks on graphs are used in numerous applications. They help model random processes and can help solve difficult problems in algorithm theory, that can be formulated as searches. Introducing randomness can provide faster (approximate) results and can be suitable for more efficient processing of larger inputs. For example, the "Boolean satisfiability problem," or SAT for short, is a well-known NP-complete problem, which can be formulated as a search: We can imagine all possible assignments of values to variables as the search space, i.e., the vertices of the graph. Then a possible step (an edge in the graph) could be the negation of a single variable's value. By stepping through this graph based on clever rules, an approximate solution can be found more quickly than with completely randomly generated candidates, and such solvers can perform well in practice.

There are several methods for quantizing classical walks, that can be interesting for further studying as they exhibit properties significantly different from their classical counterparts. Additionally, Grover's quantum search algorithm can also be understood as a special type of quantum walk.
