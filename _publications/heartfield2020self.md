---
title: "Self-configurable cyber-physical intrusion detection for smart homes using reinforcement learning"
abstract: "The modern Internet of Things (IoT)-based smart home is a challenging environment to secure: devices change, new vulnerabilities are discovered and often remain unpatched, and different users interact with their devices differently and have different cyber risk attitudes. A security breach's impact is not limited to cyberspace, as it can also affect or be facilitated in physical space, for example, via voice. In this environment, intrusion detection cannot rely solely on static models that remain the same over time and are the same for all users. We present MAGPIE, the first smart home intrusion detection system that is able to autonomously adjust the decision function of its underlying anomaly classification models to a smart home's changing conditions (e.g., new devices, new automation rules and user interaction with them). The method achieves this goal by applying a novel probabilistic cluster-based reward mechanism to non-stationary multi-armed bandit reinforcement learning. MAGPIE rewards the sets of hyperparameters of its underlying isolation forest unsupervised anomaly classifiers based on the cluster silhouette scores of their output. Experimental evaluation in a real household shows that MAGPIE exhibits high accuracy because of two further innovations: it takes into account both cyber and physical sources of data; and it detects human presence to utilise models that exhibit the highest accuracy in each case. MAGPIE is available in open-source format, together with its evaluation datasets, so it can benefit from future advances in unsupervised and reinforcement learning and be able to be enriched with further sources of data as smart home environments and attacks evolve."
collection: publications
permalink: /publication/heartfield2020self
date: 2020-11-14
venue: 'IEEE Access'
paperurl: '/files/pdf/papers/heartfield2020self.pdf'
link: 'https://ieeexplore.ieee.org/document/9277640'
github: 'https://github.com/isec-greenwich/magpie'
citation: 'Ryan Heartfield, George Loukas, Anatolij Bezemskij, Emmanouil Panaousis (2020). 
	&quot;Self-configurable cyber-physical intrusion detection for smart homes using reinforcement learning.&quot; 
	<i>IEEE Transactions on Information Forensics and Security (IEEE TIFS)</i>, 16, 1720-1735. 
	<span style="color:#2979ab;">(JCR 2021: 7.231, CiteScore 2020: 15.1)</span>'
---