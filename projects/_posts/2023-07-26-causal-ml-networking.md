---
layout: project
title: "Causal ML models for Data-Driven Networking"
tagline: "A central theme of data-driven networking is answering what-if questions -- what would be the impact of changing the design of a networked system, given data obtained from a real-world deployment of an existing system. In this project, we are investigating the use of causal reasoning approaches to answer “what-if questions” using data collected from prior deployments of systems."
handle: causal-ml-networking
image: 
category: project
tags: []
---
{% include JB/setup %}


A central theme of data-driven networking is answering what-if questions -- what would be the impact of changing the design of a networked system, given data obtained from a real-world deployment of an existing system. For instance, trace data from past video streaming sessions may be used to analyze the impact on performance if a new bit rate choice were added (e.g., introducing a 8K resolution), an existing bit rate choice were removed (e.g., during the COVID crisis, many video publishers restricted the maximum bitrate), or a new Adaptive Bitrate (ABR) algorithm were used. With the growing interest in Edge Computing, a network designer may seek to understand the benefits of reducing round-trip time by moving servers closer to the end users given performance traces collected from video servers in existing locations. Answering what-if questions of this nature is also known as causal reasoning. Causal reasoning considers the effect of events that did not occur while the data was being recorded, and is often used in fields such as epidemiology.

Several widely used ML tools are inadequate for causal reasoning. Many approaches (e.g., neural networks) merely capture correlations in collected data. While they work well about answering questions about existing systems, they suffer from biases when answering causal questions which pertain to changes in the system design. Other approaches such as Reinforcement Learning and Randomized Control Trials allow reasoning about a redesigned system but require active interventions that involve changing a system, and observing its performance among real users, which could be disruptive to the performance of real users. In this project, we are investigating the use of causal reasoning approaches to answer “what-if questions” using data collected from prior deployments of these systems. We are initially focusing our explorations on video streaming, given the importance of the domain, although we believe the issues are more general across networking.

**Publications**

- **Pitfalls of data-driven networking: A case study of latent causal confounders in video streaming.** P. C. Sruthi, Sanjay Rao, Bruno Ribeiro, in ACM SIGCOMM 2020 Workshop on Network Meets AI & ML (NetAI 2020). [[Paper]](https://engineering.purdue.edu/~isl/papers/sigcomm-netai2020.pdf) [[Slides]](https://engineering.purdue.edu/~isl/slides/sigcomm-netai2020-slides.pdf) [[Video]](https://www.youtube.com/watch?v=jYYmXLEXTjM)

**Team:**

- [Chandan Bothra](https://www.linkedin.com/in/chandan-bothra/)
- Jianfei Gao
- [Prof. Sanjay Rao](https://engineering.purdue.edu/~sanjay/)
- [Prof. Bruno Riberio](https://www.cs.purdue.edu/homes/ribeirob/)