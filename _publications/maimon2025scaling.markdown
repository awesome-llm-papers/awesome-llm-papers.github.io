---
layout: publication
title: Scaling Analysis Of Interleaved Speech-text Language Models
authors: Gallil Maimon, Michael Hassid, Amit Roth, Yossi Adi
conference: No Venue
year: 2025
bibkey: maimon2025scaling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.02398'}]
tags: ["Evaluation", "Training Techniques"]
short_authors: Maimon et al.
---
Existing Speech Language Model (SLM) scaling analysis paints a bleak picture. They predict that SLMs require much more compute and data compared to text, leading some to question the feasibility of training high-quality SLMs. However, modern SLMs are often initialised from pre-trained TextLMs using speech-text interleaving to allow knowledge transfer. This raises the question - Do interleaved SLMs scale more efficiently than textless-SLMs? In this paper we answer a resounding, yes! We conduct scaling analysis of interleaved SLMs by training several dozen and analysing the scaling trends. We see that under this setup SLMs scale more efficiently with compute. Additionally, our results indicate that the scaling-dynamics are significantly different than textless-SLMs, suggesting one should allocate notably more of the compute budget for increasing model size over training tokens. We also study the role of synthetic data and TextLM model families in unlocking this potential. Results suggest, that our scaled up model achieves comparable performance with leading models on speech semantic metrics while using less compute and data than other approaches. We open source models, samples, and data - https://pages.cs.huji.ac.il/adiyoss-lab/sims.

https://huggingface.co/discussions/paper/67ef63b6e8b932ae7a8d306d