---
layout: project
title: "Dissecting State-of-the-Art Video Distribution Networks"
tagline: "The use of abstractions to simplify network design and configuration has been a long cherished vision in the networking community. We posit that achieving more fundamental break-throughs requires abstractions that go beyond merely modeling the underlying protocols and mechanisms. We investigate a new class of abstractions that are: (i) task-driven, i.e., capture the intended performance, security, manageability, or resilience of a network design; and (ii) network-wide, i.e., capture the requirements of the network as a whole rather than of individual devices."
handle: enterprise-network-management
image: 
category: past_project
tags: []
---
{% include JB/setup %}

Our focus is on the management of enterprise networks.  Despite their critical importance, and their striking differences and diversity compared to carrier networks, enterprise networks have been largely unexplored by networking researchers. We envision a three-pronged research process that involves:

(i) capturing the goals operators have for their networks, through interactions with operators, and "bottom-up'' studies of actual network designs, (ii) elevating the design patterns we observe into abstractions; and (iii) demonstrating that abstractions can simplify both top-down network design, and validation of network properties.

A distinguishing feature of this research is its "white-box'' methodology to studying network designs. Rather than infer network characteristics with limited support from network operators as is common practice today, we will capitalize on our extensive ties with real network operators, and conduct studies using data such as router configuration files obtained with their support, and iterative interactions with them.

We are currently designing abstractions in two areas that are critically important, and widely prevalent in enterprises. (i) use of virtualization, in particular VLANs, to simplify management goals; and (ii) network evolution through planned maintenance.

1. **Scientific Study of Network Evolution**

    Configuring network devices (e.g. routers and switches) today is difficult due to increases in network scale, complexity of network protocol designs, and the diversity of devices from different vendors (e.g. Cisco and Juniper). One key challenge network operators face is changing configurations of an operational network to accommodate new needs. As a result, to increase the manageability and reliability of configuration changes, there is a strong need to discover and design high-level abstractions network operators could leverage to easily and accurately specify intended changes of various complexity for the network.

    As a first step toward higher-level abstractions, we will conduct a longitudinal study of changes made in enterprise networks today. The goal is to obtain a thorough understanding of the nature of typical changes in enterprise networks during normal operations and develop a set of metrics to capture the complexity of changes.

    **Publications:**

    - **A Systematic Approach for Evolving VLAN Design**, Xin Sun, Yu-Wei Sung, Sunil Krothapalli and Sanjay Rao. To appear in IEEE INFOCOM, 2010.[[PDF]](https://engineering.purdue.edu/~isl/infocom10-vlan.pdf)

    - **Extracting Network-wide Correlated Changes from Longitudinal Configuration Data**, Yu-Wei Eric Sung, Sanjay Rao, Subhabrata Sen, and Stephen Leggett. Proceedings of Passive and Active Measurement Conference, Seoul, Korea, April 2009. [[PDF]](https://engineering.purdue.edu/~isl/pam09-corrchange.pdf)

    - **Towards Automated Auditing for Network Configuration Changes**, Yu-Wei Eric Sung, Sanjay Rao, Subhabrata Sen, and Stephen Leggett. Poster Abstract in ACM SIGCOMM, Seattle, WA, August 2008. [[PDF]](http://web.ics.purdue.edu/~sungy/Paper/sung_sigcomm08p.pdf)

    - **Characterizing VLAN usage in an Operational Network**, Prashant Garimella, Yu-Wei Eric Sung, Nan Zhang, and Sanjay Rao. Technical Report TR-ECE-07-20, Purdue University, August 2007. [[PDF]](https://engineering.purdue.edu/~isl/TR-EE-07-20.pdf)

    - **Characterizing VLAN usage in an Operational Network**, Prashant Garimella, Yu-Wei Eric Sung, Nan Zhang, Sanjay Rao, ACM SIGCOMM workshop on Internet Network Management (INM'07), Kyoto, Japan, August 2007. [[PDF]](https://engineering.purdue.edu/~isl/inm07.pdf). The network configuration dataset used for this paper is available [here](https://engineering.purdue.edu/~isl/network-config).

    **Presentations**

    - **Data Sharing and Repositories to Support Research**, Panel Summary, Sanjay Rao. In Microsoft Edgenet 2006.

    - **A White-Box Approach to Characterizing Network Design in Operational Networks**, Sanjay Rao, In Configuration Validation Workshop, LISA 2006.

    **Collaborators**

    - Subhabrata Sen (AT&T Labs Research)

    **Students**

    - Yu-Wei Eric Sung
    - Prashant Garimella

    **Funding**

    - NSF Award Number: CNF-0721488

1. **Top-Down Enterprise Network Design**

    Despite their critical importance, and their striking differences compared to carrier networks, enterprise networks have been largely unexplored by the research community. In this project, we formulate key tasks facing operators of today's enterprises through abstractions that are task-driven and network-wide. We model the objectives of a task as a set of optimization problems, and derive configurations from solutions to these problems. This approach ensures configurations conform to the operator intent, yet it still allows customization of the configurations by modeling design constraints and strategies as inputs for selecting particular optimization problems to solve. To demonstrate our ideas, we consider two critical areas in enterprise network management that have received little attention to date: VLAN design and reachability control. Our initial success both establishes the feasibility of top-down design in the two areas we studied and gives us hope that our approach will apply to a broad class of problems. More specifically, we aim to develop systems that can generate box level configuration from high-level design requirements, and a pre-selected set of protocols and mechanisms, and it investigates "semantic auditing" techniques for formally verifying that a network's existing box-level configuration produces the intended network behavior.

    ![](https://engineering.purdue.edu/~isl/netmgmt_clip_image002.jpg)

    **Publications**

    - Modeling and Understanding End-to-End Class of Service Policies in Operational Networks, Yu-Wei Eric Sung, Carsten Lund, Mark Lyn, Sanjay Rao, and Subhabrata Sen. Proceedings of ACM SIGCOMM, Barcelona, Spain, August 2009. [[PDF]](https://engineering.purdue.edu/~isl/sigcomm09_cos.pdf)

    - Configuration Management at Massive Scale: System Design and Experience, William Enck, Thomas Moyer, Patrick McDaniel, Shubho Sen, Panagiotis Sebos, Sylke Spoerel, Albert Greenberg, Yu-Wei Sung, Sanjay Rao, and William Aiello. To appear in IEEE Journal on Selected Areas in Communications (JSAC), 2008. [[PDF]](https://engineering.purdue.edu/~isl/jsac_presto.pdf)

    - Towards Systematic Design of Enterprise Networks, Yu-Wei Eric Sung, Sanjay Rao, Geoffrey Xie, and David Maltz. Proceedings of ACM CoNEXT, Madrid, Spain, December, 2008. [[PDF]](https://engineering.purdue.edu/~isl/conext08_sysdesign.pdf). The network configuration dataset used for this paper is available [here](https://engineering.purdue.edu/~isl/network-config). Extended version available as Technical Report [here](https://engineering.purdue.edu/~isl/topdown_tr.pdf).

    - Towards Systematic Design of Enterprise Networks, Yu-Wei Eric Sung, Sanjay Rao, Geoffrey Xie, and David Maltz. Technical Report TR-ECE-08-07, Purdue University, August 2008. [[PDF]]()

    **Presentations**

    - **Case for Task-Driven Network-Wide Abstraction approach to Enterprise Design**. Yu-Wei Eric Sung, In Configuration Workshop, LISA 2007.

    **Collaborators**

    - Geoffrey Xie (CS, Naval Postgraduate School )
    - David Maltz (Microsoft Research)

    **Students**

    - Yu-Wei Eric Sung
    - Sunil Dath Krothapalli

    **Funding**
    - NSF Award Numbers: CNS-0721488, CNS-0520210, and CNS-0721574