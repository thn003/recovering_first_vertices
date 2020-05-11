# Recovering the first vertices in a *preferential attachment* model


###### Background Information

> This repository summarizes the main results and findings from my work for the Honors Thesis in Mathematics at University of California, San Diego, under the guidance of Professor Ery Arias-Castro. I have successfully presented the work in Spring 2020 and am now putting the final touches to the thesis.

***

### Abstract

We study the problem of recovering the first vertices in a graph grown under the preferential attachment rules. We focus on tree graphs. We introduce the familiar algorithm of looking at the largest connected component after removing any one vertex.

We first consider recovering only vertex 1. We provide a detailed proof of the accuracy of the algorithm. We then test the algorithm with simulations over a wide range of graph sizes. Given the computation cost, we propose a two-step procedure which
combine that with using the vertex degree.

We then consider recovering more than just vertex 1. We propose a sequential algorithm where at each stage we do a local search conditioned on what already know. We conjecture on the expectation of that algorithm and then test the algorithm on simulations.

We find that we can get both significantly accurate and significantly precise when recovering vertex 1. However, the problem starts becoming much harder once we want to recover more vertices. In particular, once we look for the fifth vertex and beyond, the accuracy drops considerably. Nonetheless, it appears that we can increase the accuracy if we are willing to trade that with being precise.

We also propose some measures to reduce the complexity of the main method (introduced in the first paragraph) such as combining with using the vertex degree and focusing only into certain subsets of vertices.

***

### Introduction and Problem statements




***

### Main Findings

#### Recovering Vertex $1$

#### Recovering the First $L$ Vertices


