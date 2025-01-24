---
layout: project
title: Non-myopic Generation of Language Models for Reasoning and Planning
subtitle: Talk at Huawei HK, 2024/10/31
---

**Abstract** Large Language Models have demonstrated remarkable abilities in reasoning and planning by breaking down complex problems into sequential steps. Despite their success in various domains like mathematical problem-solving and coding, LLMs face challenges in ensuring reliable and optimal planning due to their inherent myopic nature of autoregressive decoding. 

This work revisits LLM reasoning from an optimal-control perspective, proposing a novel method, **Predictive-Decoding**, that leverages Model Predictive Control to enhance planning accuracy. By re-weighting LLM distributions based on foresight trajectories, Predictive-Decoding aims to mitigate early errors and promote non-myopic planning. Our experiments show significant improvements in a wide range of tasks for math, coding, and agents. Furthermore, Predictive-Decoding demonstrates computational efficiency, outperforming search baselines with reduced computational resources. This study provides insights into optimizing LLM planning capabilities.


<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQrfyDSyW9q7v6gJpj08N6LywYoF6PsubU3Ev_ZjtD77js7kBkRQwsKd-6W9B2XDoYRG88u0a_KUQqm/embed?start=false&loop=false&delayms=60000" frameborder="0" width="800" height="491.7" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>