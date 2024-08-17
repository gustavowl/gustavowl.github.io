---
layout: post
title: Quantum counting on the complete bipartite graph
tags: [Paper, Quantum Computing, Quantum Algorithm, Quantum Walk, Quantum Search, Quantum Counting, Graphs, Journal, International Journal of Quantum Information]
date: 2024-06-19
excerpt_separator: <!--excerpt-->
---
<!--TODO: ADD RESEARCH TAG-->

This paper was a colaboration between me,
<a href="https://scholar.google.com/citations?user=LZib3CQAAAAJ&hl=pt-BR&oi=ao" target="_blank">
Raqueline Santos</a>, and
<a href="https://www.lncc.br/~portugal/" target="_blank">
Renato Portugal</a>.
In this paper, we proposed to count the number of marked vertices in a complete bipartite graph
using the coined quantum walk model.
Previous works showed how to count the number of marked vertices in an unsorted database,
which can be interpreted as a complete graph with self-loops.

The paper was published in the
<a href="https://doi.org/10.1142/S0219749924500278">International Journal of Quantum Information</a>.
The results presented in this paper are the extension of my Master's Thesis
available at
<a href="https://tede.lncc.br/handle/tede/341?locale=en">LNCC's database</a> and
<a href="https://arxiv.org/abs/2312.03768">arXiv</a>.

<!--excerpt-->

The abstract is as follows.
*"Quantum counting is a key quantum algorithm that aims to
determine the number of marked elements in a database.
This algorithm is based on the quantum phase estimation algorithm and
uses the evolution operator of Grover’s algorithm because
its nontrivial eigenvalues are dependent on the number of marked elements.
Since Grover’s algorithm can be viewed as a quantum walk on a complete graph,
a natural way to extend quantum counting is to use the
evolution operator of quantum-walk-based search on noncomplete graphs instead of Grover’s operator.
In this paper,
we explore this extension by analyzing the coined quantum walk on
the complete bipartite graph with an arbitrary number of marked vertices.
We show that some eigenvalues of the evolution operator depend on the number of marked vertices and
using this fact we show that the quantum phase estimation can be used to
obtain the number of marked vertices.
The time complexity for estimating the number of marked vertices in the bipartite graph with
our algorithm equates closely with that of the original quantum counting algorithm."*
