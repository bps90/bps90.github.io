---
title: "Mobile Matrix: Routing under Mobility in IoT, IoMT, and Social IoT"
header:
  teaser: "/assets/images/mmatrix-journal.png"
author_profile: false
comments: true
categories:
  - Papers
tags:
  - Mobility
  - LLNs
  - IoT
  - IoMT
  - Social IoT
  - SIoT
  - 6LoWPAN
  - Routing
  - Any-to-any
  - IP allocation
sidebar:
  nav: "mmatrix-journal"
---

#### ToDo

<!---
The explosive growth of “things” connected to the Internet (Internet of Things, IoT) raises the question of whether existingready-to-go networking protocols are enough to cover social and mobile IoT’s demands.  IoT aims to interconnect static devicesattached to some physical infrastructure.  However, mobility is a major factor present in everyday life, and naturally the “things”can move around (Internet of Mobile Things, IoMT) and create social ties (Social IoT, SIoT) in the cyber-physical space.  In thatcontext, we present Mobile Matrix (μMatrix), a routing protocol that uses hierarchical IPv6 address allocation to perform any-to-anyrouting and mobility management without changing a node’s address. In this way, device mobility is transparent to the applicationlevel favoring IoMT and SIoT implementation and broader adoption.  The protocol has low memory footprint, adjustable controlmessage overhead, and it achieves optimal routing path distortion. Moreover, it does not rely on any particular hardware for mobilitydetection (a key open issue), such as an accelerometer.  Instead, it uses a passive mechanism to detect that a device has moved.We present analytic proofs for the computational complexity and efficiency ofμMatrix, as well as an evaluation of the protocolthrough simulations.  We evaluate the protocol performance under human and non-human mobility models.  For human mobility,we generated mobility traces using Group Regularity Mobility (GRM) Model, setting its parameters based on real human mobilitytraces. For the non-human mobility, we propose a new mobility model, to which we refer as Cyclical Random Waypoint (CRWP),where nodes move using a simple Random Waypoint and, eventually, return to their initial position.  We comparedμMatrix withtwo other protocols: Routing Protocol for low-power and lossy networks (RPL) and Ad hoc On-Demand Distance Vector (AODV).The results show thatμMatrix and RPL offer≈99.9% of bottom-up delivery rate, but onlyμMatrix offer≥95% of top-down trafficin highly dynamic and mobile scenarios, while other protocols≤75%.  Moreover,μMatrix uses up to 65% of the routing tablewhile RPL and AODV fulfill theirs in all scenarios, which leads to poor top-down and any-to-any reliability. 
{: style="text-align: justify;"}

Please cite:
```TeX
@inproceedings{santos2017mobile,
 
}
```
> Bruno P. Santos, Olga Goussevskaia, Marcos A. M. Vieira, Luiz F. M. Vieira, and Antonio A.F. Loureiro.
#### Contatcs: {bruno.ps, olga, mmvieira, lfvieira, loureiro}@dcc.ufmg.br
###### **Founding agencies**: CNPq/CAPES/FAPEMIG.
-->