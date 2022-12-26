---
title: Deep joint source-channel and encryption coding
description: Secure semantic communications
date: "2022-12-26T19:06:59Z"
publishDate: "2022-08-31T19:06:59Z"
---

In this paper, we propose the **first DeepJSCC scheme for wireless image transmission that is secure against eavesdroppers**, called DeepJSCEC. 
DeepJSCEC not only preserves the favorable properties of DeepJSCC, it also provides security against chosen-plaintext attacks from the eavesdropper, without the need to make assumptions about the eavesdropper's channel condition, or its intended use of the intercepted signal.

<!--more-->

Deep learning driven joint source-channel coding (JSCC) for wireless image or video transmission, also called DeepJSCC, has been a topic of interest recently with very promising results. 
The idea is to map similar source samples to nearby points in the channel input space such that, despite the noise introduced by the channel, the input can be recovered with minimal distortion. 
In DeepJSCC, this is achieved by an autoencoder architecture with a non-trainable channel layer between the encoder and decoder. 
DeepJSCC has many favorable properties, such as better end-to-end distortion performance than its separate source and channel coding counterpart as well as graceful degradation with respect to channel quality. 
However, due to the inherent correlation between the source sample and channel input, DeepJSCC is vulnerable to eavesdropping attacks. 
In this paper, we propose the first DeepJSCC scheme for wireless image transmission that is secure against eavesdroppers, called DeepJSCEC. 
DeepJSCEC not only preserves the favorable properties of DeepJSCC, it also provides security against chosen-plaintext attacks from the eavesdropper, without the need to make assumptions about the eavesdropper's channel condition, or its intended use of the intercepted signal.
Numerical results show that DeepJSCEC achieves similar or better image quality than separate source coding using BPG compression, AES encryption, and LDPC codes for channel coding, while preserving the graceful degradation of image quality with respect to channel quality. 
We also show that the proposed encryption method is problem agnostic, meaning it can be applied to other end-to-end JSCC problems, such as remote classification, without modification. 
Given the importance of security in modern wireless communication systems, we believe this work brings DeepJSCC schemes much closer to adoption in practice. 

[**Arxiv**](https://arxiv.org/abs/2208.09245)
