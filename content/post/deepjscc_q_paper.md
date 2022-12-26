---
title: DeepJSCC-Q
description: Channel Input Constrained Deep Joint Source-Channel Coding
date: "2022-12-26T18:57:34Z"
publishDate: "2021-11-25T18:57:34Z"
---
We propose DeepJSCC-Q, an end-to-end optimized joint source-channel coding scheme for wireless image transmission, which is able to operate with a fixed channel input alphabet. 
We show that DeepJSCC-Q can achieve similar performance to models that use continuous-valued channel input. 

<!--more-->

Recent works have shown that the task of wireless transmission of images can be learned with the use of machine learning techniques. 
Very promising results in end-to-end image quality, superior to popular digital schemes that utilize source and channel coding separation, have been demonstrated through the training of an autoencoder, with a non-trainable channel layer in the middle. 
However, these methods assume that any complex value can be transmitted over the channel, which can prevent the application of the algorithm in scenarios where the hardware or protocol can only admit certain sets of channel inputs, such as the use of a digital constellation. 
Herein, we propose DeepJSCC-Q, an end-to-end optimized joint source-channel coding scheme for wireless image transmission, which is able to operate with a fixed channel input alphabet. 
We show that DeepJSCC-Q can achieve similar performance to models that use continuous-valued channel input. 
Importantly, it preserves the graceful degradation of image quality observed in prior work when channel conditions worsen, making DeepJSCC-Q much more attractive for deployment in practical systems. 

[**Arxiv**](https://arxiv.org/abs/2111.13042)
