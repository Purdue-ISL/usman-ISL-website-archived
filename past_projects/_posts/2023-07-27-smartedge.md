---
layout: project
title: "SmartEdge for low-latency Web applications"
tagline: "Reducing end-to-end latencies of Web pages is critical for e-commerce, directly impacting user engagement and revenue. For example, Amazon found that 100ms of latency costs 1% in sales, while Google Search found that a 400ms delay resulted in a 0.59% reduction in searches per user. There are several trends that pose challenges to achieving low latency for Web applications -- Web pages are becoming complex day-by-day with rich interactive content as well as increase in Web activities using small form factor devices such as smartphones and tablets connected over high-latency cellular networks. In this project, we are developing a system to improve Mobile Web performance by achieving the right refactoring of browsing functionality between a proxy (in the edge) and a client, based on their respective strengths and techniques to make the proxy design scale to millions of users by reducing its computational overhead. Further, in a broader context beyond mobile, we seek to achieve low-latency for Web applications by exploring criticality-aware algorithms for Web object placement and caching in Content Delivery Networks (CDNs)."
handle: smartedge
image: 
category: past_project
tags: []
---
{% include JB/setup %}

In recent years, owing to the dramatic increase in cellular users, it has become imperative for service providers to provide better quality of experience for their users. Web download is one of the key activities contributing to a significant fraction of the mobile traffic than any other application, excluding video streaming. Mobile Web experience is still not par with desktops, particularly the page load times are in the order of a few seconds. This is because modern Web pages are complex and feature-rich customized for individual user preferences, with lots of objects fetched (as a result of parsing HTML and/or executing Javascripts) from many domains. Consequently, this results in lots of HTTP request-response interactions in the high latency cellular link. Thus, today's web page download process is ill suited to cellular networks resulting in high page load times. To tackle this challenge, we are developing systems and techniques to improve Mobile Web performance by optimizing the last-mile network delays that dominate page load latencies in cellular settings. Specifically, (1) a proxy based system design that judiciously refactors browsing functionality between a proxy (inside the cellular network) and a client based on their respective strengths (figure below) (2) develop techniques to make the proxy design scale to millions of users by reducing its computational overhead.

Today's Web pages consist of hundreds of objects with complex dependencies, with some objects being more critical to page-load latencies than others (e.g., javascripts may determine which objects are needed). Yet, current Content Delivery Networks (CDNs) are agnostic to object criticality, potentially impacting overall page latencies. We seek to achieve low latency for several tens of thousands of the most popular pages by exploring novel criticality-aware algorithms for object placement and caching.

![](https://engineering.purdue.edu/~isl/parcel_architecture.png)

**Publications:**

- **Reducing latency through page-aware management of web objects by Content Delivery Networks**. Shankaranarayanan P N, Yun Seong Nam, Ashiwan Sivakumar, Balakrishnan Chandrasekaran, Bruce Maggs and Sanjay Rao, ACM SIGMETRICS 2016. [[PDF]](https://engineering.purdue.edu/~isl/papers/sigmetrics16.pdf)

- **PARCEL: Proxy Assisted bRowsing in Cellular networks for Energy and Latency reduction**. Ashiwan Sivakumar, Shankaranarayanan P N, Vijay Gopalakrishnan, Seungjoon Lee, Sanjay Rao and Subhabrata Sen, ACM CoNEXT 2014. [[PDF]](https://engineering.purdue.edu/~isl/papers/paper169_final_CoNEXT14.pdf) [[PPT]](https://engineering.purdue.edu/~isl/papers/conext14_parcel-nov29_3pm.pdf)

- **Cloud is not a silver bullet: A Case Study of Cloud-based Mobile Browsing**. Ashiwan Sivakumar, Vijay Gopalakrishnan, Seungjoon Lee, Sanjay Rao, Subhabrata Sen and Oliver Spatscheck, HotMobile Workshop 2014. [[PDF]](https://engineering.purdue.edu/~isl/hotmobile14-browsing.pdf)

**Collaborators:**

- Subhabrata Sen (AT&T Labs - Research)
- Vijay Gopalakrishnan (AT&T Labs - Research)
- Prof. Mithuna Thottethodi (Purdue University)
- Prof. T.N. Vijaykumar (Purdue University)
- Prof. Bruce Maggs (Duke University and Akamai Technologies)

**Students:**

- Ashiwan Sivakumar (Purdue University)
- Chuan Jiang (Purdue University)
- Yun Seong Nam (Purdue University)
- Shankaranarayanan P.N. (Purdue University)
- Balakrishnan Chandrasekaran (Duke University)