---
layout: project
title: "Synthesizing network designs with certifiable performance properties"
tagline: "Network design is ad-hoc today, and validating the design normally comes as an afterthought. Unlike the chip and software industry, where design and verification tools form a multi-billion dollar industry, network design and verification is still at an early stage. We are exploring approaches to synthesizing network designs with formally certifiable performance properties under failures. The work may be viewed as an early step towards verifying quanititative network properties."
handle: verifiable-networks
image: 
category: project
tags: [verifiable networks, network designs]
---
{% include JB/setup %}


With the wide-spread adoption of online and cloud-based services, it is critical that the underlying network infrastructure meet increasingly stringent performance requirements (e.g., sustain throughput for business-critical applications). These requirements must be met despite failures that are the norm given the global scale of ISP and cloud provider networks, and their rapid pace of evolution. Many existing approaches to designing networks for failures (i) only focus on availability, resulting in poor performance on failures; (ii) only consider a small number of failure states, and do not scale as the number of possible failure states increase; or (iii) rely on ad-hoc simulation-based testing. While tools for software and hardware synthesis and testing is a thriving 10 billion dollar industry, the state of practice in certifying and synthesizing network designs is only in its nascent stages.

The project is tackling these challenges by developing novel techniques that enable architects to plan their network designs (e.g., design topology, provision capacity, algorithms for re-routing traffic on failures) so performance is acceptable over a large set of scenarios the network may encounter. The project is distinguished by a focus on performance (not just availability), designing for multiple concurrent failures, and designs with provable performance guarantees for a given set of failure scenarios. This project may be viewed as an early effort aimed at formally verifying quantitative network properties, and synthesizing networks for such performance requirements. This is in contrast to much recent progress in the field of network verification, which has primarily focused on correctness (e.g., ensuring security policies are correctly instantiated).

The project is bringing together expertise in network systems, and optimization theory, and is advancing the state-of-the-art in two key ways. First, the project is developing (i) new mechanisms that may be deployed in the network to respond to failures; and (ii) frameworks that can certify the resulting performance is acceptable over desired failure states. A novelty of the framework is the ability to model rich and flexible network mechanisms. Second, unlike existing methods that only consider worst-case performance, and may be overly conservative, the project is developing novel ways to design for requirements that must be met by a desired percentage of scenarios.

The project has the potential for significant real-world impact by ensuring networks comply with Service Level Objectives in the face of failures, and is leading to networks with lower cost, better performance, and higher reliability. The project is extensively engaging with industry and network operator forums, with results being validated using real data from these networks.

**Publications:**

- **PCF: Provably Resilient Flexible Routing.**, Chuan Jiang, Sanjay Rao, Mohit Tawarmalani, ACM SIGCOMM 2020. [[PDF]](https://engineering.purdue.edu/~isl/papers/SIGCOMM2020_76_final.pdf) [[Slides]](https://engineering.purdue.edu/~isl/slides/PCF_slides.pdf) [[Video]](https://engineering.purdue.edu/~isl/videos/SIGCOMM_76_long.mp4) [[Code]](https://github.com/secretjc/pcf)

- **Lancet: Better network resilience by designing for pruned failure sets.**, Yiyang Chang, Chuan Jiang, Ashish Chandra, Sanjay Rao, Mohit Tawarmalani, ACM SIGMETRICS 2020. [[PDF]](https://engineering.purdue.edu/~isl/papers/Sigmetrics2020_Lancet.pdf) [[Slides]](https://engineering.purdue.edu/~isl/slides/sigmetrics2020_yiyang_v8.pdf) [[Video]](https://engineering.purdue.edu/~isl/videos/sigmetrics2020.mp4)
- **Robust validation of network designs under uncertain demands and failures.**, Yiyang Chang, Sanjay Rao, Mohit Tawarmalani, USENIX NSDI 2017. [[PDF]](https://engineering.purdue.edu/~isl/papers/nsdi17-final59.pdf) [[Slides]](https://engineering.purdue.edu/~isl/papers/nsdi2017_validation_slides.pdf)

**Team:**

- [Yiyang Chang](https://on-the-run.github.io/webpage/)
- Ashish Chandra
- Chuan Jiang
- [Prof. Sanjay Rao](https://engineering.purdue.edu/~sanjay/)
- [Prof. Mohit Tawarmalani](https://web.ics.purdue.edu/~mtawarma/)