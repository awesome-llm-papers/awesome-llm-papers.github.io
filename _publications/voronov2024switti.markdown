---
layout: publication
title: 'Switti: Designing Scale-wise Transformers For Text-to-image Synthesis'
authors: Anton Voronov, Denis Kuznedelev, Mikhail Khoroshikh, Valentin Khrulkov, Dmitry
  Baranchuk
conference: No Venue
year: 2024
bibkey: voronov2024switti
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.01819'}]
tags: ["Model Architecture"]
short_authors: Voronov et al.
---
This work presents Switti, a scale-wise transformer for text-to-image generation. Starting from existing next-scale prediction AR models, we first explore them for T2I generation and propose architectural modifications to improve their convergence and overall performance. We then observe that self-attention maps of our pretrained scale-wise AR model exhibit weak dependence on preceding scales. Based on this insight, we propose a non-AR counterpart facilitating \{sim\}11% faster sampling and lower memory usage while also achieving slightly better generation quality.Furthermore, we reveal that classifier-free guidance at high-resolution scales is often unnecessary and can even degrade performance. %may be not only unnecessary but potentially detrimental. By disabling guidance at these scales, we achieve an additional sampling acceleration of \{sim\}20% and improve the generation of fine-grained details. Extensive human preference studies and automated evaluations show that Switti outperforms existing T2I AR models and competes with state-of-the-art T2I diffusion models while being up to 7\{times\} faster.

https://huggingface.co/discussions/paper/674eb174236b0a3fa92fdc0c