---
title: "eXtend Collection Tree Protocol"
header:
  teaser: "/assets/images/xctp.png"
author_profile: false
comments: true
categories:
  - papers
tags:
  - WSN
  - LLNs
  - Routing
  - Any-to-any
  - Data-collection
sidebar:
  - title: "Files"
    text: "[PDF](/assets/files/2015-03-09-XCTP.pdf){: .btn .btn--success}{: target=\"_blank\"} [IEEE-DOI](10.1109/WCNC.2015.7127692){: .btn} [Talk PDF](https://www.dropbox.com/s/j42c8hc4uv9jb8j/xctp-presentation-wcnc-rev.pptx?dl=0){: .btn .btn--info}{: target=\"_blank\"}"
    image: /assets/images/xctp.png

---

In this work, we propose eXtend Collection Tree Protocol (XCTP), a routing protocol that is an extension of the Collection Tree Protocol (CTP). CTP is the de-facto standard collection routing protocol for Wireless Sensor Network (WSN). CTP creates a routing tree to transfer data from one or more sensors to a root (sink) node. But, CTP does not create the reverse path between the root node and sensors nodes. This reverse path is important, for example, for feedback commands or acknowledgment packets. XCTP enables communication in both ways: root to node and node to root. XCTP accomplishes this task by exploring the CTP control plane packets. XCTP requires low storage states and very low additional overhead in packets. With the reverse path, it is possible to implement reliable transport layer protocols for Wireless Sensor Network (WSN). Thus, we designed Transport Automatic Piggyback Protocol (TAP2), a transport protocol with Automatic Repeat-reQuest (ARQ) errorcontrol on top of XCTP. We implemented these protocols on TinyOS and evaluated on TOSSIM. We compared XCTP with CTP, Routing Protocol for low-power and lossy networks (RPL), and Ad hoc On Demand Distance Vector (AODV) protocols. We conducted scalability and stress tests, evaluating them with different loads and number of nodes. Our results shows that XCTP is more reliable then CTP, delivering 100% of the packets. XCTP sends fewer control packets than RPL. XCTP is faster to recovery from network failures and also stores fewer states than AODV, thus being efficient and agile.
{: style="text-align: justify;"}

Please cite:
```TeX
@inproceedings{santos2015extend,
  title={eXtend collection tree protocol},
  author={Santos, Bruno P and Vieira, Marcos AM and Vieira, Luiz FM},
  booktitle={Wireless Communications and Networking Conference (WCNC), 2015 IEEE},
  pages={1512--1517},
  year={2015},
  organization={IEEE}
}
```
> Bruno P. Santos, Marcos A. M. Vieira, Luiz F. M. Vieira;
##### Contatcs: {bruno.ps, mmvieira, lfvieira}@dcc.ufmg.br
###### **Founding agency**: CNPq.




