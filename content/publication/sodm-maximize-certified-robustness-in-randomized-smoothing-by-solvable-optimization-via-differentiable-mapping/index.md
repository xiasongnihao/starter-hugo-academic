---
title: SODM Maximize Certified Robustness In Randomized Smoothing By Solvable
  Optimization Via Differentiable Mapping
publication_types:
  - "1"
authors:
  - Song Xia
  - Hao Jiang
  - Haijun Shan
  - Yap Kim Hui
  - Jintao Yang
publication: Unpublished paper. Under revision to submission.
abstract: "Randomized smoothing has been proved efficient to provide certified
  defense to norm based adversarial perturbations for large-scale neural
  networks. However, this certified robustness is achieved by sacrificing
  significant classification accuracies. We find that due to the
  non-differentiable property of 0-1 mapping, the optimization for maximizing
  accuracy and robustness is not solvable by gradient based training. In this
  paper, we propose SODM: a solvable optimization for robustness via
  differentiable mapping in randomized smoothing. We derive the gradient from
  the base classifier’s prediction to the smoothed classifier’s robustness by
  any differentiable mapping, thus achieving the direct robustness optimization.
  Additionally, to reduce the estimation bias and smooth the uneven gradient in
  this optimization, we further propose a dynamic mapping function and maximum
  threshold constraint. Different from Gaussian augmentation and adversarial
  training, our method provides the theoretical proof for maxmizing provable
  robustness. Experiment shows that our method is much more efficient than
  exiting ones: on Cifar10, when compared to adversarial training, our method
  accelerate the training process by 91% to reach the state of the art result.
  When compared with Gaussian augmentation, our method accelerate the training
  process by 47% to get the similar performance on ImageNet."
draft: false
featured: true
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: Certified radius and accuracy curve of different models on Cifar10.
summary: Adversarial examples, Differentiable optimization, Randomized
  smoothing, Certified defense, .
date: 2021-09-25T06:26:00.000Z
---
