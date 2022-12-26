---
title: Effective Communications
description: A Joint Learning and Communication Framework for Multi-Agent Reinforcement Learning Over Noisy Channels
date: "2022-12-26T18:51:35Z"
publishDate: "2021-06-28T18:51:35Z"
---

We propose a novel formulation of the **effectiveness problem** in communications, put forth by Shannon and Weaver in their seminal work *The Mathematical Theory of Communication*, by considering multiple agents communicating over a noisy channel in order to achieve better coordination and cooperation in a multi-agent reinforcement learning (MARL) framework.

<!--more-->

Specifically, we consider a multi-agent partially observable Markov decision process (MA-POMDP), in which the agents, in addition to interacting with the environment, can also communicate with each other over a noisy communication channel. 
The noisy communication channel is considered explicitly as part of the dynamics of the environment, and the message each agent sends is part of the action that the agent can take. 
As a result, the agents learn not only to collaborate with each other but also to communicate **effectively** over a noisy channel. 
This framework generalizes both the traditional communication problem, where the main goal is to convey a message reliably over a noisy channel, and the *learning to communicate* framework that has received recent attention in the MARL literature, where the underlying communication channels are assumed to be error-free. 
We show via examples that the joint policy learned using the proposed framework is superior to that where the communication is considered separately from the underlying MA-POMDP. 
This is a very powerful framework, which has many real world applications, from autonomous vehicle planning to drone swarm control, and opens up the rich toolbox of deep reinforcement learning for the design of multi-user communication systems.

[**Arxiv**](https://arxiv.org/abs/2101.10369v2)

[**IEEE**](https://ieeexplore.ieee.org/abstract/document/9466501)
