---
title: "A Collaborative Compression Scheme for Fast
Activity Recognition on Mobile Devices Via
Global Compression Ratio Decision"
collection: publications
date: 2023-4-25
venue: 'April 25th'
Abstract: Despite strong representation ability, deep convolutional neural networks (CNNs) are largely hindered in practical human
activity recognition (HAR) deployment due to high computational cost, which is often unaffordable on resource-limited wearable
devices. In this paper, to bridge the gap between on-device HAR and deep learning, we present a collaborative compression scheme to
reduce the runtime of HAR with an acceptable performance degradation, which combines channel pruning and tensor decomposition
to simultaneously handle sparsity and low-rankness when fully considering mutual interference in one network consisting of efficient
1-dimensional convolutional kernels. Our method includes two main stages. Concretely, given a target compression ratio, a global
compression ratio decision optimization is first performed to automatically decide per-layer compression ratio by measuring
compression sensitivity, without requiring labor-exhaustive human intervention. Then a multi-step collaborative compression is
iteratively implemented to remove the least important compression unit based on an improved importance metric until the per-layer
target compression ratio is attained. Extensive experiments on multiple HAR benchmarks show that our approach considerably
outperforms previous compression strategies. For example, it can achieve around 50% FLOPs reduction with only an accuracy drop of
0.25% and 0.15% on UCI-HAR and PAMAP2, respectively. Actual implementation is evaluated on an embedded platform.
---
[Download paper here](https://l-junjie.github.io/liangjunjie.github.io/files/A_Collaborative_Compression_Scheme_for_Fast_Activity_Recognition_on_Mobile_Devices_Via_Global_Compression_Ratio_Decision.pdf)

Recommended citation: Your Name, You. (2010). "Paper Title Number 2." <i>Journal 1</i>. 1(2).
