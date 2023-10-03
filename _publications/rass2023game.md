---
title: "Game-theoretic APT defense: An experimental study on robotics"
abstract: "This paper proposes a novel game-theoretic framework for defending against Advanced Persistent Threats (APTs). It applies the original Cut-The-Rope model into an experimental study extending the previously studied attacker movements beyond the Poisson distribution to a realistic set of attack actions. More importantly, it demonstrates the value of this framework on an experimental study of an APT defense game on attack graphs, which lets a security officer establish an optimized defense policy against stealthy intrusions. The security model and algorithm under study is designed for practical use with attack graphs as threat models, possibly including vulnerability information if available. The game-theoretic optimization delivers a proactive defense policy under the following assumptions or requirements: first, we do not need to assume that the system is, or has been, clean from adversaries at any time. At the moment when the defender computes the defense policy, the attacker is assumed to already be in the system (also having penetrated it until an unknown depth). Second, the defender does not rely on any signaling or other indicators of adversarial activity, nor is there a reliable feedback mechanism to tell the defender if its actions were successful or not. Third, the model can use information on exploits, such as Common Vulnerabilities and Exposures (CVE) numbers, to refine the defense game, but can also operate without such information. We corroborate our findings on publicly documented attack graphs from the robotics domain; without and with CVE information. We run experiments against two different types of defense regimes, and compare the results against an intuitive baseline defense heuristic. The results show that the optimized defense strongly outperforms simple heuristics, like taking the shortest or easiest attack paths."
collection: publications
permalink: /publication/rass2023game
date: 2023-06-09
venue: 'Computers & Security'
paperurl: '/files/pdf/papers/rass2023game.pdf'
link: 'https://www.sciencedirect.com/science/article/pii/S0167404823002389'
citation: 'Stefan Rass, Sandra König, Jasmin Wachter, Víctor Mayoral-Vilches, Emmanouil Panaousis (2023). 
	&quot;Game-theoretic APT defense: An experimental study on robotics.&quot; 
	<i>Computers & Security (COSE)</i>, 132, 103328. <br>
	<span style="color:#2979ab;">(JCR 2021: 5.105, CiteScore: 10.1)</span>'
---