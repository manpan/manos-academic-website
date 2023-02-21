---
title: "Practical algorithm substitution attack on extractable signatures"
abstract: "An algorithm substitution attack (ASA) can undermine the security of cryptographic primitives by subverting the original implementation. An ASA succeeds when it extracts secrets without being detected. To launch an ASA on signature schemes, existing studies often needed to collect signatures with successive indices to extract the signing key. However, collection with successive indices requires uninterrupted surveillance of the communication channel and a low transmission loss rate in practice. This hinders the practical implementation of current ASAs, thus causing users to misbelieve that the threat incurred by ASA is only theoretical and far from reality. In this study, we first classify a group of schemes called extractable signatures that achieve traditional security (unforgeability) by reductions ending with key extraction, thus demonstrating that there is a generic and practical approach for ASA with this class of signatures. Further, we present the implementation of ASAs in which only two signatures and no further requirements are needed for the extraction of widely used discrete log-based signatures such as DSA, Schnorr, and modified ElGamal signature schemes. Our attack presents a realistic threat to current signature applications, which can also be implemented in open and unstable environments such as vehicular ad hoc networks. Finally, we prove that the proposed ASA is undetectable against polynomial time detectors and physical timing analysis."
collection: publications
permalink: /publication/zhao2022practical
date: 2022-03-05
venue: 'Designs, Codes and Cryptography'
paperurl: '/files/pdf/papers/zhao2022practical.pdf'
link: 'https://link.springer.com/article/10.1007/s10623-022-01019-1'
citation: 'Yi Zhao, Kaitai Liang, Yanqi Zhao, Bo Yang, Yang Ming, Emmanouil Panaousis (2022). 
  &quot;Practical algorithm substitution attack on extractable signatures.&quot;
  <i>Designs, Codes and Cryptography</i>, 90, 921–937.'
---