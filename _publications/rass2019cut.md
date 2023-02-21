---
title: "Cut-The-Rope: A Game of stealthy intrusion"
abstract: "A major characteristic of Advanced Persistent Threats (APTs) is their stealthiness over a possibly long period, during which the victim system is being penetrated and prepared for the finishing blow. We model an APT as a game played on an attack graph G, and consider the following interaction pattern: the attacker chooses an attack path in G towards its target $𝑣_0$ , and step-by-step works its way towards the goal by repeated penetrations. In each step, it leaves a backdoor for an easy return to learn how to accomplish the next step. We call this return path the “rope”. The defender’s aim is “cutting” this rope by cleaning the system from (even unknown) backdoors, e.g., by patching systems or changing configurations. While the defender is doing so in fixed intervals governed by working hours/shifts, the attacker is allowed to take any number of moves at any point in time. The game is thus repeated, i.e., in discrete time, only for the defender, while the second player (adversary) moves in continuous time. It also has asymmetric information, since the adversary is stealthy at all times, until the damage causing phase of the APT. The payoff in the game is the attacker’s chance to reach this final stage, while the defender’s goal is minimizing this likelihood (risk). We illustrate the model by a numerical example and open access implementation in R."
collection: publications
permalink: /publication/rass2019cut
date: 2019-10-23
venue: '10th Conference on Decision and Game Theory for Security'
paperurl: '/files/pdf/papers/rass2019cut.pdf'
slidesurl: '/files/pdf/papers/rass2019cut-slides.pdf'
code: 'https://www.syssec.at/en/publikationen/description/cuttherope'
link: 'https://link.springer.com/chapter/10.1007/978-3-030-32430-8_24'
citation: 'Stefan Rass, Sandra Konig, Emmanouil Panaousis (2019). 
  &quot;Cut-The-Rope: A Game of stealthy intrusion.&quot;
  <i>10th Conference on Decision and Game Theory for Security (Gamesec)</i>.'
---