---
layout: project
title: "A Program Synthesis Approach to Designing Networks with Indeterminate Objectives"
tagline: "Computer networks are difficult to manage since there exists a wide gulf between the high-level goals that operators have for their networks and the low-level decisions that operators should make. This project develops a novel framework that we term comparative synthesis (inspired by program synthesis from the Programming Language community), where a user's design objective, and the synthesis of a network design that optimizes that objective are done in tandem."
handle: program-synthesis-network-design
image: 
category: project
tags: []
---
{% include JB/setup %}


Computer networks are difficult to manage since there exists a wide gulf between the high-level goals that operators have for their networks (e.g., Quality of Service etc.), and the low-level decisions that operators should make (e.g., how to route traffic, allocate bandwidth, configure devices etc.). While the advent of Software-Defined Networking helps, the process of designing networks is still ad-hoc, leading to high operational costs, design faults that account for a large fraction of network downtime, and costly security breaches. This project is motivated by the vision of design automation for networking, inspired by the success of the approach in other domains such as chip design. The project is developing methods for network architects to express their intent at higher levels of abstraction, and techniques to automatically synthesize network designs that realize this intent correctly and efficiently.

As a concrete example, we are tackling a key challenge network architects encounter: how to balance multiple conflicting metrics, and ensure fair allocations to competing traffic while prioritizing critical traffic. The state of practice poses challenges since architects must precisely encode their (somewhat fuzzy) intent into formal optimization models using abstract notions such as utility functions, and ad-hoc manually tuned knobs. We are developing one of the first efforts to synthesize network designs with indeterminate objectives using an interactive program-synthesis-based approach. Specifically, we are developing a novel framework that we term comparative synthesis, where a user's design objective, and the synthesis of a network design that optimizes that objective are done in tandem. Our work is based on the key insight that when a user has difficulty in providing a concrete objective function, it is relatively easy and natural to give preferences between pairs of concrete candidates. The approach may be viewed as a new variant of programming-by-example (PBE) widely studied in the Programming Languages community, where preference pairs are used as "examples" instead of input-output pairs in traditional PBE systems. We are developing Net10Q, a system based on our approach, and evaluating its effectiveness on real-world network case studies, and through pilot user studies comprising network researchers and practitioners.

**Team:**

- Yanjun Wang
- Zixuan Li
- Xiaokang Wang
- [Prof. Sanjay Rao](https://engineering.purdue.edu/~sanjay/)

**Publications**

- **Learning Network Design Objectives Using A Program Synthesis Approach.**, Yanjun Wang, Chuan Jiang, Xiaokang Qiu, Sanjay G. Rao, In Proceedings of the 18th ACM Workshop on Hot Topics in Networks (HotNets '19). [[PDF]](https://engineering.purdue.edu/~isl/papers/HotNets_2019_Paper.pdf)