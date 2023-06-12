---
layout: post
title: Hiperwalk 2.0
tags: [Project, Quantum Computing, Quantum Walk, Simulation]
date: 2023-06-12
excerpt_separator: <!--excerpt-->
---

Hiperwalk (High-performance Quantum Walk Simulator) is a
freeware open-source program that allows
the user to perform simulations of quantum walks on graphs using HPC.
The user can use the parallel resources of the computer,
such as accelerator cards, multicore CPU and GPGPU to
speedup the overall process without knowing parallel programming.

Visit the
<a href="https://hiperwalk.org/" target="_blank">Hiperwalk website</a>
for more information such as
installation, documentation and examples.

![Coined Quantum Walk simulation on diagonal lattice.](/assets/img/projects/hiperwalk-coined-diagonal-lattice.png)

<!--excerpt-->

Hiperwalk is being upgraded to version 2.0.
Hiperwalk 2.0 represents a significant upgrade to its predecessor,
offering a comprehensive solution for the simulation of quantum walks
on graphs using heterogeneous high-performance computing (HPC).
Its architecture, fundamentally redesigned,
now encompasses the simulation of both
coined and continuous-time quantum walk models,
seamlessly integrated into a Python session.
Comprising two primary components, the user frontend API,
developed in Python, and an inner core, written in C,
Hiperwalk 2.0 provides an accessible interface and
efficient computational capabilities.
With the capacity to fully utilize all
parallel devices on a user's machine,
it offers scalability and robust performance for complex,
large-scale simulations,
making it an invaluable asset for researchers in quantum walks and
quantum algorithms.

The source code is available on the
<a href="https://github.com/hiperwalk/hiperwalk/" target="_blank">
Hiperwalk GitHub</a>.
