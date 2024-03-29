---
layout: project
title: "Next Generation Multi-Perspective Video Delivery at Internet Scale"
tagline: "The success of streaming video has generated interest in newer forms of multi-perspective video content, such as those generated by 360-degree cameras, multi-angle camera arrays, or light-field cameras. The immersive experience provided by these cameras can enhance user satisfaction. This project explores architectural enhancements, algorithms, and techniques to deliver multi-perspective video at Internet-scale."
handle: video-at-scale
image: 
category: project
tags: [video, multi-perspective, internet video]
---
{% include JB/setup %}


The success of streaming video has generated interest in newer forms of multi-perspective video content, such as those generated by 360-degree cameras, multi-angle camera arrays, or light-field cameras. The immersive experience provided by these cameras can enhance user satisfaction in domains including sports, training (e.g., construction safety), and virtual exploration (e.g., college walkthroughs, historical sites). With content from these cameras, users do not just passively consume content, but may interactively traverse the content along many different paths from a perspective of their choice, with different users observing different perspectives of the same content. To support this at Internet-scale is challenging; client players must be able to switch perspectives with low latency, the perspectives may need to be generated on demand by video servers, and the infrastructure must support a variety of devices for capture and consumption of this content.

This project explores architectural enhancements, algorithms, and techniques to deliver multi-perspective video at Internet-scale. It couples delivery optimization with video coding and human computer interaction. The project will develop interactivity abstractions by which content publishers can specify the range of perspectives users are permitted to choose from at each point in the video. The interactivity specified in a video will:
 1. Drive perspective coding and novel dynamic perspective generation algorithms
 2. Enable infrastructure provisioning to meet Content Delivery Network (CDN) storage and cost constraints
 3. Will guide adaptive perspective retrieval from CDN servers or from nearby caches. Finally, the project will explore methods to predict and guide user behavior to improve delivery quality based on user studies.

**Team:**

- [Ehab Ghabashneh](https://www.linkedin.com/in/ehab-ghabashneh-397928b3/)
- [Chandan Bothra](https://www.linkedin.com/in/chandan-bothra/)
- [Prof. Alex Quinn](http://alexquinn.org/)
- [Prof. Sanjay Rao](https://engineering.purdue.edu/~sanjay/)

**Collaborators**

- [Prof. Ramesh Govindan](https://nsl.usc.edu/people/ramesh/) (University of Southern California)
- [Prof. Antonio Ortega](https://viterbi.usc.edu/directory/faculty/Ortega/Antonio) (University of Southern California)