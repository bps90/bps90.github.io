---
title: "Matrix: Multihop Address Allocation and Dynamic Any-to-Any Routing for 6LoWPAN"
header:
  teaser: "/assets/images/matrix-mswin-2016.png"
author_profile: false
comments: true
categories:
  - papers
tags:
  - LLNs
  - WSN
  - 6LoWPAN
  - Routing
  - IP allocation
  - Any-to-any
sidebar:
  - title: "Files"
    text: "[PDF](/assets/files/2016-11-13-mswim-2016.pdf){: .btn .btn--success} [ACM-DL](https://doi.org/10.1145/2988287.2989139){: .btn} [Talk](/assets/files/2016-11-13-talk-Matrix-MSWiM.pptx){: .btn .btn--info}"
    image: /assets/images/matrix-mswin-2016.png

---

Standard routing protocols for IPv6 over Low power Wireless Personal Area Networks (6LoWPAN) are mainly designed for data collection applications and work by establishing a tree-based network topology, which enables packets to be sent upwards, from the leaves to the root, adapting to dynamics of low-power communication links. The routing tables in such unidirectional networks are very simple and small since each node just needs to maintain the address of its parent in the tree, providing the best-quality route at every moment. In this work, we propose Matrix, a platform-independent routing protocol that utilizes the existing tree structure of the network to enable reliable and efficient any-to-any data traffic. Matrix uses hierarchical IPv6 address assignment in order to optimize routing table size, while preserving bidirectional routing. Moreover, it uses a local broadcast mechanism to forward messages to the right subtree when persistent node or link failures occur. We implemented Matrix on TinyOS and evaluated its performance both analytically and through simulations on TOSSIM. Our results show that the proposed protocol is superior to available protocols for 6LoWPAN, when it comes to any-to-any data communication, in terms of reliability, message efficiency, and memory footprint.
{: style="text-align: justify;"}

### Authors
> Bruna S. Peres,Otavio A. de O. Souza, Bruno P. Santos, Edson R. A. Junior, Olga Goussevskaia, Marcos A. M. Vieira, Luiz F. M. Vieira, and Antonio A.F. Loureiro.

#### Contatcs: {bperes, oaugusto, bruno.ps, edsonroteia, olga, mmvieira, lfvieira, loureiro}@dcc.ufmg.br

###### **Founding agency**: CNPq.
