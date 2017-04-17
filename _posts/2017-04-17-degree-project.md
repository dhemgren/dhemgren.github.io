---
layout: post
title: Degree Project @ KTH
cover: graph.png
categories: posts
---

## Implementing SSSP algorithms on GPUs using CUDA

We are currently studying various single source shortest path-algorithms such as Dijkstras algorithm, Delta-Stepping and Bellman-Fords algorithm on single- / multi-core CPUs and GPGPUs. Our final goal for the project is to successfully implement Dijkstra Strip-Mined Relaxation (DSMR) on the CUDA platform and compare our results to running DSMR on many-core data clusters. 

Most of our time so far have been delegated to learning the ropes of the CUDA API and how to utilize parallelization without branching to minimize the overhead of context switching. The final paper will be presented in June.
