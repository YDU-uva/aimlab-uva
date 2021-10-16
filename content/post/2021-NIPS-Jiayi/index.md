---
title: One paper accepted at NeurIPS 2021.
date: 2021-10-01
---

Congratulations on Jiayi Shen's paper "Variational Multi-Task Learning with Gumbel-Softmax Priors" being accepted by NeurIPS 2021.

<!--more-->

Multi-task learning aims to explore task relatedness to improve individual tasks, which is of particular signiﬁcance in the challenging scenario that only limited data is available for each task. To tackle this challenge, we propose variational multi-task learning (VMTL), a general probabilistic inference framework in which we cast multi-task learning as a variational Bayesian inference problem. In this way, task relatedness can be explored in a uniﬁed manner by specifying priors. To leverage the knowledge shared among tasks, we design the prior of a task to be a learnable mixture of the variational posteriors of other tasks, which is learned by the Gumbel-Softmax technique. In contrast to previous methods, our VMTL can exploit task relatedness for both representations and classiﬁers in a single uniﬁed framework by jointly inferring their posteriors. This enables individual tasks to fully leverage inductive biases provided by related tasks, therefore improving the overall performance of all tasks. Experimental results demonstrate that the proposed VMTL is able to effectively tackle a variety of challenging multi-task learning problems with limited training data for both classiﬁcation and regression. Our method consistently surpasses previous methods, including strong Bayesian approaches, and achieves state-of-the-art performance on ﬁve benchmark datasets.