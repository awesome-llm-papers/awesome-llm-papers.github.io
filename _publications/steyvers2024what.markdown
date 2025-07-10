---
layout: publication
title: What Large Language Models Know And What People Think They Know
authors: Mark Steyvers et al.
conference: Nature Machine Intelligence
year: 2024
citations: 16
bibkey: steyvers2024what
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.13835'}, {name: Code,
    url: 'https://osf.io/y7pr6/'}, {name: Code, url: 'https://www.nature.com/articles/s42256-024-00976-7'}]
tags: [Interpretability and Explainability, Reinforcement Learning, Has Code]
---
As artificial intelligence (AI) systems, particularly large language models
(LLMs), become increasingly integrated into decision-making processes, the
ability to trust their outputs is crucial. To earn human trust, LLMs must be
well calibrated such that they can accurately assess and communicate the
likelihood of their predictions being correct. Whereas recent work has focused
on LLMs' internal confidence, less is understood about how effectively they
convey uncertainty to users. Here we explore the calibration gap, which refers
to the difference between human confidence in LLM-generated answers and the
models' actual confidence, and the discrimination gap, which reflects how well
humans and models can distinguish between correct and incorrect answers. Our
experiments with multiple-choice and short-answer questions reveal that users
tend to overestimate the accuracy of LLM responses when provided with default
explanations. Moreover, longer explanations increased user confidence, even
when the extra length did not improve answer accuracy. By adjusting LLM
explanations to better reflect the models' internal confidence, both the
calibration gap and the discrimination gap narrowed, significantly improving
user perception of LLM accuracy. These findings underscore the importance of
accurate uncertainty communication and highlight the effect of explanation
length in influencing user trust in AI-assisted decision-making environments.
Code and Data can be found at https://osf.io/y7pr6/ . Journal publication can
be found on Nature Machine Intelligence at
https://www.nature.com/articles/s42256-024-00976-7 .