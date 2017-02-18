---
title: "COMPARING PARALLEL TECHNOLOGIES BASED ON GPU AND CPU IN NUMERICALLY SOLVING SINGLE PHASE FLOW PROBLEMS"
header:
  teaser: "/assets/images/speedup-euro.png"
author_profile: false
comments: true
categories:
  - papers
tags:
  - GPU
  - Single Fase Flow
  - GPU
  - CUDA
  - OpenMP
  - Parallel computing
sidebar:
  - title: "Files"
    text: "[PDF](/assets/files/2014-02-29-wccm-eccm-ecfd2014.pdf){: .btn .btn--success}"

---

A numerical solution for a single phase flow in a porous medium problem is relevant in many fields of science and engineering. Due to the high computational cost these problems should be solved using parallel processing techniques. Initially, the MPI and OpenMP models were used for CPU architecture as the main parallel technique. Recently the CUDA model for graphic processing units has settled as the main technique for solving large scientific problems. This work presents a numerical solution for a single phase flow in a porous medium problem using GPU-CUDA technology. The mathematical model uses the Poisson mixed equation. The numerical solution is based in the Raviart-Thomas finite element method and a domain decomposition method. In this work were implemented three parallel codes: the first using the MPI model, the second using an MPI-OPenMP hybrid model and the last one using CUDA. Were made performance tests for various spatial meshes in CPU and GPU architectures and performance metrics were calculated. The applied tests showed that CUDA and GPU are excellent alternatives to solve single phase flow problems in porous medium
{: style="text-align: justify;"}


### Authors
> DANY S. DOMINGUEZ, ESBEL. V. ORELLANA, BRUNO P. SANTOS, AND SUSANA M. IGLESIAS.

#### Contatcs: dsdominguez@gmail.com, evalero@uesc.br, bruno.ps@live.com, smiglesias@uesc.br

###### **Founding agency**: CNPq/FAPESB.




