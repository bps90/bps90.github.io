---
title: "Técnicas de Processamento Paralelo na Geração do Fractal de Mandelbrot"
author_profile: false
header:
  teaser: "/assets/images/fractal-mandelbrot.png"
categories:
  - papers
tags:
  - Mandelbrot
  - Fractal
  - GPU
  - CUDA
  - OpenMP
sidebar:
  - title: "Files"
    text: "[PDF](/assets/files/2011-02-28-Resumo_Seminario_IC_FINAL.pdf){: .btn .btn--success}
 [Talk](/assets/files/2011-02-28Apresentacao_Seminariode_IC_2011_UESC.pdf){: .btn .btn--info}" 

---

Frequentemente são encontrados problemas computacionais de grande porte nas áreas da ciência e engenharia, para resolvê-los técnicas de processamento paralelo são utilizadas. As principais técnicas são o paralelismo com memória distribuída MPI (Message Passing Interface) e com memória compartilhada OpenMP (Open Multi-Processing), todas elas utilizando a CPU (Central Processing Unit) como hardware, CPUs podem ser encontradas em diversas máquinas paralelas ou em clusters. O processamento paralelo em placas gráficas GPU (Graphical Processing Unit) é uma alternativa recente para hardware, sendo amplamente pesquisada por diversas empresas e cientistas, visto que seu grande atrativo é baixo custo e alto desempenho. No presente trabalho, aplicaram-se técnicas de GPU no problema computacional gerado ao se tentar plotar o fractal de Mandelbrot, numa resolução suficiente para que seja observável o padrão multi-escala característico. Este problema modelo permitiu comparar o paralelismo com GPU aos paradigmas tradicionais de paralelismos que utilizam a CPU como fonte de processamento. Utilizou-se o speedup, como métrica, para avaliar o desempenho dos programas paralelos desenvolvidos. Para realizar os experimentos foi utilizada uma estação de trabalho, equipada com uma placa Nvidia, com as seguintes características: processador Intel Core i7 CPU 860 2,8GHz, memória RAM 8GB e placa aceleradora gráfica GPU Nvidia GeForce 9800GT com 112 cores, 512MB de RAM, 256bits PCI Express 16x, já para os experimentos numéricos em OpenMP, usou-se um cluster equipado com 8 nós Genuine Intel ia-64, modelo Madison com 9M cachê e 16GB de memória RAM compartilhada. A análise dos dados mostrou que a implementação em GPU é em média 37 vezes mais rápida que a versão serial, bem como 5 vezes mais rápida que a técnica tradicional OpenMP. Podemos inferir que o paralelismo em GPU obteve maior desempenho no processamento do fractal de alta resolução, além de redução significativa do custo pelo hardware e melhoria do espaço físico utilizado. 
{: style="text-align: justify;"}

**Keywords**: Processamento Paralelo, Fractal De Mandelbroot, GPU.

**Founding agency**: FAPESB 2010/2011.

### Authors

> Bruno P. Santos, Marcos A. M. Vieira, and Luiz F. M. Vieira

#### Contacts bruno.ps@live.com, dsdominguez@gmail.com, evalero@uesc.br.






