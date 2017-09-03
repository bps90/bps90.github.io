---
title: "Mobile Matrix: A Multihop Address Allocation and Any-To-Any Routing in Mobile 6LoWPAN"
header:
  teaser: "/assets/images/matrix-mswin-2017.png"
author_profile: false
comments: true
categories:
  - papers
tags:
  - Mobility
  - IPv6
  - CTP
  - RPL
  - LLNs
  - WSN
  - 6LoWPAN
  - Routing
  - IP allocation
  - any-to-any routing
sidebar:
  - title: "Files"
    text: "[PDF](/assets/files/2016-11-13-mswim-2016.pdf){: .btn .btn--success} [ACM-DL](https://doi.org/10.1145/2988287.2989139){: .btn} [Talk](/assets/files/2016-11-13-talk-Matrix-MSWiM.pptx){: .btn .btn--info}"
    image: /assets/images/matrix-mswin-2016.png

---

In this work, we present Mobile Matrix, a routing protocol for 6LoWPAN that uses hierarchical IPv6 address allocation to perform any-to-any routing and mobility management without changing a node’s IPv6 address. In this way, device mobility is transparent to the application level. The protocol has low memory footprint, adjustable control message overhead and achieves optimal routing path distortion. Moreover, it does not rely on any particular hardware for mobility detection, such as an accelerometer. Instead, it provides a passive mechanism to detect that a device has moved. We present analytic proofs for the computational complexity and efficiency of Mobile Matrix, as well as an evaluation of the protocol through simulations. Finally, we propose a new mobility model, to which we refer as cyclical random waypoint mobility model, that we use to simulate mobility scenarios, where communication is carried out in environments with limited mobility, such as 6LoWPANs deployed in office buildings, university campuses, concert halls or sports stadiums. Results show that μMatrix deliveries 3x times more packets than RPL for top-down traffic over high mobility scenario.
{: style="text-align: justify;"}

### Authors
> Bruno P. Santos, Olga Goussevskaia, Marcos A. M. Vieira, Luiz F. M. Vieira, and Antonio A.F. Loureiro.

#### Contatcs: {bruno.ps, olga, mmvieira, lfvieira, loureiro}@dcc.ufmg.br

###### **Founding agencies**: CNPq/CAPES/FAPEMIG.
