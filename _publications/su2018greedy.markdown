---
layout: publication
title: "Greedy Hash: Towards Fast Optimization for Accurate Hash Coding in CNN"
authors: Shupeng Su, Chao Zhang, Kai Han, Yonghong Tian
conference: NIPS
year: 2018
bibkey: su2018greedy
additional_links:
   - {name: "PDF", url: "https://papers.nips.cc/paper/7360-greedy-hash-towards-fast-optimization-for-accurate-hash-coding-in-cnn.pdf"}
   - {name: "Code", url: "https://github.com/ssppp/GreedyHash"}
tags: ["Has Code", "CNN", "NIPS"]
---
To convert the input into binary code, hashing algorithm has been widely used for approximate nearest neighbor search on large-scale image sets due to its computation and storage efficiency. Deep hashing further improves the retrieval quality by combining the hash coding with deep neural network. However, a major difficulty in deep hashing lies in the discrete constraints imposed on the network output, which generally makes the optimization NP hard. In this work, we adopt the greedy principle to tackle this NP hard problem by iteratively updating the network toward the probable optimal discrete solution in each iteration. A hash coding layer is designed to implement our approach which strictly uses the sign function in forward propagation to maintain the discrete constraints, while in back propagation the gradients are transmitted intactly to the front layer to avoid the vanishing gradients. In addition to the theoretical derivation, we provide a new perspective to visualize and understand the effectiveness and efficiency of our algorithm. Experiments on benchmark datasets show that our scheme outperforms state-of-the-art hashing methods in both supervised and unsupervised tasks.
