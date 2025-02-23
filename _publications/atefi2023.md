---
title: "Principled data-driven decision support for cyber-forensic investigations"
abstract: "In the wake of a cybersecurity incident, it is crucial to promptly discover how the threat actors breached security in order to assess the impact of the incident and to develop and deploy countermeasures that can protect against further attacks. To this end, defenders can launch a cyber-forensic investigation, which discovers the techniques that the threat actors used in the incident. A fundamental challenge in such an investigation is prioritizing the investigation of particular techniques since the investigation of each technique requires time and effort, but forensic analysts cannot know which ones were actually used before investigating them. To ensure prompt discovery, it is imperative to provide decision support that can help forensic analysts with this prioritization. A recent study demonstrated that data-driven decision support, based on a dataset of prior incidents, can provide state- of-the-art prioritization. However, this data-driven approach, called DISCLOSE, is based on a heuristic that utilizes only a subset of the available information and does not approximate optimal decisions. To improve upon this heuristic, we introduce a principled approach for data-driven decision support for cyber-forensic investigations. We formulate the decision-support problem using a Markov decision process, whose states represent the states of a forensic investigation. To solve the decision problem, we propose a Monte Carlo tree search based method, which relies on a k-NN regression over prior incidents to estimate state-transition probabilities. We evaluate our proposed approach on multiple versions of the MITRE ATT&CK dataset, which is a knowledge base of adversarial techniques and tactics based on real-world cyber incidents, and demonstrate that our approach outperforms DISCLOSE in terms of techniques discovered per effort spent."
collection: publications
permalink: /publication/atefi2022principled
date: 2022-11-19
venue: '37th AAAI Conference on Artificial Intelligence (AAAI 23)'
paperurl: '/files/pdf/papers/atefi2022principled.pdf'
link: 'https://arxiv.org/abs/2211.13345'
slidesurl: '/files/pdf/slides/atefi2022principled-slides.pdf'
citation: 'Soodeh Atefi, Sakshyam Panda, Manos Panaousis, Aron Laszka (2023). 
	&quot;Principled data-driven decision support for cyber-forensic investigations.&quot; 
	<i>37th AAAI Conference on Artificial Intelligence (AAAI 23)</i>. <br>
 	<span style="color:#2979ab;">(CORE2021 Ranking: A*)</span>'
---