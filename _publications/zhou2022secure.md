---
title: "Secure genotype imputation using homomorphic encryption"
abstract: "Genotype imputation estimates missing genotypes from the haplotype or genotype reference panel in individual genetic sequences, which boosts the potential of genome-wide association and is essential in genetic data analysis. However, the genetic sequences involve people’s privacy, confirming an individual’s identification and even disease information. This work proposes a secure genotype imputation model, which uses a linear regression model and the homomorphic encryption scheme over ciphertext to impute missing genotypes. The inference model is trained with float plaintext parameters, which are round into integers to avoid high complexity homomorphic evaluation on float number operations without bootstrapping operations. Even though the rounding parameters in the inference model are not the same as those in the trained model, We find that it will no effect on the outcome of the homomorphic prediction. Thus, a high-efficiency genotype imputation inference model over the ciphertext is obtained while keeping the high-security level. The simulation results indicate that the accuracy of the secure inference model is almost the same as the original model trained on float parameters. The secure inference model’s accuracy is 98.6% for a single genotype."
collection: publications
permalink: /publication/zhou2022secure
date: 2023-02-01
venue: 'Journal of Information Security and Applications'
paperurl: '/files/pdf/papers/zhou2022secure.pdf'
link: 'https://www.sciencedirect.com/science/article/abs/pii/S2214212622002307'
citation: 'Junwei Zhou, Botian Lei, Huile Lang, Emmanouil Panaousis, Kaitai Liang, Jianwen Xiang (2022). 
  &quot;Secure genotype imputation using homomorphic encryption.&quot;
  <i>Journal of Information Security and Applications (JISA)</i>, 72, 103386.<br>
  <span style="color:#2979ab;">(JCR 2021: 4.96, CiteScore 2021: 7.6)</span>'
---