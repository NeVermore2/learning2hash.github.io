---
layout: publication
title: "Hamming Distance Metric Learning"
authors: M. Norouzi, D. Fleet, R. Salakhutdinov
conference: NIPS
year: 2012
bibkey: norouzi2012hamming
additional_links:
   - {name: "PDF", url: "http://papers.nips.cc/paper/4808-hamming-distance-metric-learning.pdf"}
   - {name: "Code", url: "https://github.com/norouzi/hdml"}
tags: ["Has Code", "Image Retrieval", "NIPS"]
---
Motivated by large-scale multimedia applications we propose to learn mappings
from high-dimensional data to binary codes that preserve semantic similarity.
Binary codes are well suited to large-scale applications as they are storage efficient and permit exact sub-linear kNN search. The framework is applicable
to broad families of mappings, and uses a flexible form of triplet ranking loss.
We overcome discontinuous optimization of the discrete mappings by minimizing
a piecewise-smooth upper bound on empirical loss, inspired by latent structural
SVMs. We develop a new loss-augmented inference algorithm that is quadratic in
the code length. We show strong retrieval performance on CIFAR-10 and MNIST,
with promising classification results using no more than kNN on the binary codes.
