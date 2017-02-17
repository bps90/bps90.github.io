---
title: "Aplicação de Processamento Paralelo com GPU a Problemas de Escoamento Monofásico em Meios Porosos"
header:
  teaser: "/assets/images/five-spot-problem.jpg"
author_profile: false
comments: true
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
    text: "[PDF](/assets/files/2012-10-29-SIC_2012.pdf){: .btn .btn--success} [Talk PDF](/assets/files/2012-10-29-Apresentacao-sic-2012.pdf){: .btn .btn--info}"
    image: /assets/images/default-teaser.jpg

---

O fenômeno de escoamento de fluídos em meios porosos é objeto de estudo, modelagem e simulação das ciências e engenharias, pois geralmente conduzem a problemas computacionais de grande porte, ou seja, problemas de alto custo computacional que se faz necessário a emprego de técnicas de Computação de Alto Desempenho (CAD) para serem resolvidos em tempo hábil e em grande escala.Um exemplo clássico destes problemas, é asimulação dos cinco poços (five-spot problem) que surge ao modelarmos asleis que regem a exploração de um reservatório de petróleo, em que énecessário conhecer os parâmetros do fluído (pressão e velocidade) em escalade metros, entretanto o domínio de cálculo é de quilômetros. A adaptaçãomatemática deste regime extração é feita através da equação de mistaPoisson, uma Equação Diferencial Parcial (EDP) do tipo elíptica quecaracteriza bem o escoamento monofásico do fluído, para se resolvernumericamente o problema dos cinco poços em geometria cartesianabidimensional, foi utilizado método de decomposição de domínio de exploraçãoem células quadradas e uma discretização de elementos finitos de Riviart-Thomas, sendo assim obtém-se um elevado número de células espaciais econsequentemente o alto custo computacional. A resolução computacional dofenômeno compreende a utilização do padrão de programação paralela CUDA(Compute Unified Device Architecture) atual paradigma CAD já em evolução deuso pela comunidade científica e acadêmica, este padrão viabiliza a construçãode códigos a serem executados em GPUs (Graphics Processing Units). Oestudo realizado com base no processo metodológico do projeto permitiu comoresultado a construção do código que utiliza CUDA para resolver de formaeficiente o problema five-spot. Com a análise dos tempos e métricas CAD(speedup e eficiência) da execução desta implementação e de equivalentesutilizando técnicas tradicionais de processamento paralelo tais como MPI(Message Passing Interface) e OpenMP (Open Multi-Processing) permite ocomparativo entre as versões empregando diversas configurações de malhasde simulação do domínio de cálculos.
{: style="text-align: justify;"}

**Keywords**: Escoamento monofásico, Equação de Poisson, GPU.

**Founding agency**: PIBIC-CNPq.

### Authors
> Bruno Pereira dos Santos and Dany Sanchez Dominguez.

#### Contatcs: bruno.ps@live.com, dsdominguez@gmail.com





