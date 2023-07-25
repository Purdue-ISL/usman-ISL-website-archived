---
layout: project
title: "ML and Data-Driven Optimization of Internet Video Delivery from the Network Edge"
tagline: "Video dominates the Internet today, accounting for over 80% of Internet traffic by some estimates. A key challenge is delivering high quality Internet video over variable Internet environments. In this project, we are investigating whether high Quality of Experience can be enabled for Internet video by leveraging ML-frameworks at the network edge. Our work extensively uses insights from real-world data sets of Internet video sessions."
handle: ml-video-delivery
image: 
category: project
tags: []
---
{% include JB/setup %}


Video dominates the Internet today, accounting for over 80% of Internet traffic by some estimates. Recently, new forms of live video (e.g., Facebook Live), interactive video (e.g., 360 video), and high resolution video (e.g., 4K and 8K video) have started to emerge. A key challenge is delivering high quality Internet video over variable Internet environments. In this project, we are investigating whether high Quality of Experience can be enabled for Internet video, especially by leveraging ML-frameworks at the network edge.

Some example contributions from the project include (i) Xatu, a system that uses LSTMs to achieve high prediction accuracies for throughput in video streaming systems (a pre-requisite for the design of video streaming algorithms). Xatu achieves prediction accuracies of over 24% relative to state-of-the-art; and (ii) Oboe, a system for auto-tuning a wide range of Adaptive Bit Rate algorithms (a key building block for Internet video) to network conditions. Oboe significantly outperforms state-of-the-art approaches including a reinforcement learning method; and (iii) exploring the benefits of deploying servers at the edge to optimize Internet video, and designing video streaming algorithms that can exploit the same. We have released two large-scale datasets of real video sessions to the research community as part of the project.

**Publications**

- **Xatu: Richer Neural Network Based Prediction for Video Streaming.** Yun Seong Nam, Jianfei Gao, Chandan Bothra, Ehab Ghabashneh, Sanjay Rao, Bruno Ribeiro, Jibin Zhan, Hui Zhang, in ACM Sigmetrics 2022. [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3491056) [[Slides]](https://engineering.purdue.edu/~isl/slides/Xatu-Sigmetrics-2022.pdf) [[Video]](https://engineering.purdue.edu/~isl/videos/Xatu-Sigmetrics-2022.mp4)

- **Pitfalls of data-driven networking: A case study of latent causal confounders in video streaming.** P. C. Sruthi, Sanjay Rao, Bruno Ribeiro, in ACM SIGCOMM 2020 Workshop on Network Meets AI & ML (NetAI 2020). [[Paper]](https://engineering.purdue.edu/~isl/papers/sigcomm-netai2020.pdf) [[Slides]](https://engineering.purdue.edu/~isl/slides/sigcomm-netai2020-slides.pdf) [[Video]](https://www.youtube.com/watch?v=jYYmXLEXTjM)

- **Oboe: Auto-tuning Video ABR Algorithms to Network Conditions.** Zahaib Akhtar, Yun Seong Nam, Ramesh Govindan, Sanjay Rao, Jessica Chen, Ethan Katz Bassett, Bruno Martins Ribeiro, Jibin Zhan, Hui Zhang, ACM SIGCOMM 2018. [[PDF]](https://engineering.purdue.edu/~isl/papers/sigcomm18-final128.pdf) [[Video]](https://www.youtube.com/watch?v=4ehZhvvAA-I&t=16514s)

**Datasets:**

- **[Xatu:](https://github.com/Purdue-ISL/XatuDataset/)** this dataset contains video session data used to evaluate the Xatu system.

- **[Oboe:](https://github.com/USC-NSL/Oboe)** this dataset contains bandwidth traces of real video streaming sessions used to evaluate Oboe.

**Team:**

- [Chandan Bothra](https://www.linkedin.com/in/chandan-bothra/)
- [Ehab Ghabashneh](https://www.linkedin.com/in/ehab-ghabashneh-397928b3/)
- Jianfei Gao
- [Prof. Sanjay Rao](https://engineering.purdue.edu/~sanjay/)
- [Prof. Bruno Riberio](https://www.cs.purdue.edu/homes/ribeirob/)

