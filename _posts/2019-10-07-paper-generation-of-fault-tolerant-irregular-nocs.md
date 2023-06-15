---
layout: post
title: Generation of Application Specific Fault Tolerant Irregular NoC Topologies Using Tabu Search
tags: [Paper, Network On Chip, NoC, Irregular Topologies, Application-Specific, Fault-Tolerance, Tabu  Search, SBESC, Conference]
date: 2019-10-07
excerpt_separator: <!--excerpt-->
---
<!--TODO: ADD RESEARCH TAG-->

This Full Paper is the result of my Computer Science Bachelor Thesis at
<a href="https://www.ufrn.br" target="_blank">UFRN</a>.
Prof. <a href="http://lattes.cnpq.br/5777010848661813" target="_blank">
Monica Magalhães Pereira</a> was the advisor of
this work about irregular fault-tolerant Network on Chips.
The paper was published in the
<a href="https://sbesc.lisha.ufsc.br/sbesc2019/Home" target="_blank">IX SBESC</a>
(Brazilian Symposium on Computing Systems Engineering),
which occurred in Natal-RN in November 19 to 22, 2019.
It is available at
<a href="https://ieeexplore.ieee.org/abstract/document/9046087" target="_blank">
IX SBESC's proceedings</a>

![Irregular NoCs Performance Analysis - SBESC 2019]({{ site.baseurl }}/assets/img/researches/conferences/2019-sbesc-inocs-performance-analysis.png)


<!--excerpt-->

The abstract is as follows.
*"Initial Network on Chip (NoCs) topologies tended to have a regular structure, aiming flexibility - regular performance for different applications, and multiple paths between routers. However, regular topologies lack in performance if compared to specific application generated topologies, often irregular. On the other hand, irregular topologies may lack flexibility (multiple communication paths). Moreover, in the billion-transistor era, circuit components are more susceptible to faults, transient and permanent. Due to the cost of producing such circuits, it is desirable to increase their lifespan which may be achieved by adding fault tolerance to the circuit, such as through hardware redundancy. This work proposes the generation of irregular topologies considering additional links to provide fault tolerance. The irregular topology with the additional links were generated through a Tabu Search approach. Thus generating intermediate topologies: flexible if compared to most irregular ones (some fault resistance), yet achieving application specific high performance if compared to regular NoCs."*

The original source code is available on
<a href="https://github.com/gustavowl/generation-of-fault-tolerant-irregular-nocs" target="blank">
https://github.com/gustavowl/generation-of-fault-tolerant-irregular-nocs</a>.
