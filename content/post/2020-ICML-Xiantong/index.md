---
title: One paper accepted at ICML 2020.
date: 2020-05-09
---

Congratulations on Xiantong Zhen's paper "Learning to Learn Kernels with Variational Random Features" being accepted by ICML 2020.

<!--more-->

We introduce kernels with random Fourier features in the meta-learning framework for few-shot learning. We propose meta variational random features (MetaVRF) to learn adaptive kernels for the base-learner, which is developed in a latent variable model by treating the random feature basis as the latent variable. We formulate the optimization of MetaVRF as a variational inference problem by deriving an evidence lower bound under the meta-learning framework. To incorporate shared knowledge from related tasks, we propose a context inference of the posterior, which is established by an LSTM architecture. The LSTMbased inference network effectively integrates the context information of previous tasks with taskspecific information, generating informative and adaptive features. The learned MetaVRF is able to produce kernels of high representational power with a relatively low spectral sampling rate and also enables fast adaptation to new tasks. Experimental results on a variety of few-shot regression and classification tasks demonstrate that MetaVRF can deliver much better, or at least competitive, performance compared to existing metalearning alternatives.
