---
title: DeepWiVe
description: Deep-Learning-Aided Wireless Video Transmission
date: "2022-12-26T18:42:30Z"
publishDate: "2022-07-22T18:42:30Z"
---

We present DeepWiVe, the **first-ever** end-to-end joint source-channel coding (JSCC) video transmission scheme that leverages the power of deep neural networks (DNNs) to directly map video signals to channel symbols, combining video compression, channel coding, and modulation steps into a single neural transform. 

<!--more-->

Our DNN decoder predicts residuals without distortion feedback, which improves the video quality by accounting for occlusion/disocclusion and camera movements. 
We simultaneously train different bandwidth allocation networks for the frames to allow variable bandwidth transmission. 
Then, we train a bandwidth allocation network using reinforcement learning (RL) that optimizes the allocation of limited available channel bandwidth among video frames to maximize the overall visual quality. 
Our results show that DeepWiVe can overcome the cliff-effect, which is prevalent in conventional separation-based digital communication schemes, and achieve graceful degradation with the mismatch between the estimated and actual channel qualities. 
DeepWiVe outperforms H.264 video compression followed by low-density parity check (LDPC) codes in all channel conditions by up to 0.0485 in terms of the multi-scale structural similarity index measure (MS-SSIM), and H.265+ LDPC by up to 0.0069 on average. 
We also illustrate the importance of optimizing bandwidth allocation in JSCC video transmission by showing that our optimal bandwidth allocation policy is superior to uniform allocation as well as a heuristic policy benchmark.

[**Arxiv**](https://arxiv.org/abs/2111.13034)

[**IEEE**](https://ieeexplore.ieee.org/document/9837870)
