---
title: "Meta ControlNet: Enhancing Task Adaptation via Meta Learning"
category: conferences
collection: publications
permalink: /publications/metecontrolnet
venue: "arXiv"
date: 2023-12-03 
citation: #'J.Zhao, et al. <i>arXiv:2403.17404</i>'
---

[[arXiv2024]](https://arxiv.org/abs/2312.01255)

<!-- ![Teaser image for Meta ControlNet]({{ site.baseurl }}/images/metacontrolnet_teaser.png) -->


## Abstract
Diffusion-based image synthesis has attracted extensive attention recently. In particular, ControlNet that uses image-based prompts exhibits powerful capability in image tasks such as canny edge detection and generates images well aligned with these prompts. However, vanilla ControlNet generally requires extensive training of around 5000 steps to achieve a desirable control for a single task. Recent context-learning approaches have improved its adaptability, but mainly for edge-based tasks, and rely on paired examples. Thus, two important open issues are yet to be addressed to reach the full potential of ControlNet: (i) zero-shot control for certain tasks and (ii) faster adaptation for non-edge-based tasks. In this paper, we introduce a novel Meta ControlNet method, which adopts the task-agnostic meta learning technique and features a new layer freezing design. Meta ControlNet significantly reduces learning steps to attain control ability from 5000 to 1000. Further, Meta ControlNet exhibits direct zero-shot adaptability in edge-based tasks without any finetuning, and achieves control within only 100 finetuning steps in more complex non-edge tasks such as Human Pose.

![Teaser image for Meta ControlNet](/jimz.github.io/images/metacontrolnet_teaser.png)