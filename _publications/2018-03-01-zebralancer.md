---
title: "ZebraLancer: Private and Anonymous Crowdsourcing System atop Open Blockchain"
collection: IEEE ICDCS 2018
permalink: /publication/2018-03-01-zebralancer
excerpt: 'Decentralized application'
date: 2018-03-02
venue: 'IEEE ICDCS'
paperurl: 'https://ieeexplore.ieee.org/document/8416350'
citation: 'Yuan Lu, Qiang Tang, Guiling Wang. &quot;ZebraLancer: Private and Anonymous Crowdsourcing System atop Open Blockchain.&quot; <i>Proc. IEEE ICDCS 2018</i>.'
---
We design and implement the first private and anonymous decentralized crowdsourcing system ZebraLancer, and overcome two fundamental challenges of decentralizing crowdsourcing, i.e. data leakage and identity breach. First, our outsource-then-prove methodology resolves the tension between blockchain transparency and data confidentiality, which is critical in crowdsourcing use-case. ZebraLancer ensures: (i) a requester will not pay more than what data deserve, according to a policy announced when her task is published via the blockchain; (ii) each worker indeed gets a payment based on the policy, if he submits data to the blockchain; (iii) the above properties are realized not only without a central arbiter, but also without leaking the data to the open blockchain. Furthermore, the transparency of blockchain allows one to infer private information about workers and requesters through their participation history. On the other hand, allowing anonymity will enable a malicious worker to submit multiple times to reap rewards. ZebraLancer overcomes this problem by allowing anonymous requests/submissions without sacrificing the accountability. The idea behind is a subtle linkability: if a worker submits twice to a task, anyone can link the submissions, or else he stays anonymous and unlinkable across tasks. To realize this delicate linkability, we put forward a novel cryptographic concept, i.e. the common-prefix-linkable anonymous authentication. We remark the new anonymous authentication scheme might be of independent interest. Finally, we implement our protocol for a common image annotation task and deploy it in a test net of Ethereum. The experiment results show the applicability of our protocol with the existing real-world blockchain.

[Download paper here](https://ieeexplore.ieee.org/document/8416350)

