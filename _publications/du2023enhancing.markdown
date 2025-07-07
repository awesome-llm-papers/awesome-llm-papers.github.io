---
layout: publication
title: Enhancing Job Recommendation Through Llm-based Generative Adversarial Networks
authors: Yingpeng Du et al.
conference: Arxiv
year: 2023
citations: 23
bibkey: du2023enhancing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.10747'}]
tags: [RAG, Few-Shot, Tools, Reinforcement Learning, Security]
---
Recommending suitable jobs to users is a critical task in online recruitment
platforms, as it can enhance users' satisfaction and the platforms'
profitability. While existing job recommendation methods encounter challenges
such as the low quality of users' resumes, which hampers their accuracy and
practical effectiveness. With the rapid development of large language models
(LLMs), utilizing the rich external knowledge encapsulated within them, as well
as their powerful capabilities of text processing and reasoning, is a promising
way to complete users' resumes for more accurate recommendations. However,
directly leveraging LLMs to enhance recommendation results is not a
one-size-fits-all solution, as LLMs may suffer from fabricated generation and
few-shot problems, which degrade the quality of resume completion. In this
paper, we propose a novel LLM-based approach for job recommendation. To
alleviate the limitation of fabricated generation for LLMs, we extract accurate
and valuable information beyond users' self-description, which helps the LLMs
better profile users for resume completion. Specifically, we not only extract
users' explicit properties (e.g., skills, interests) from their
self-description but also infer users' implicit characteristics from their
behaviors for more accurate and meaningful resume completion. Nevertheless,
some users still suffer from few-shot problems, which arise due to scarce
interaction records, leading to limited guidance for the models in generating
high-quality resumes. To address this issue, we propose aligning unpaired
low-quality with high-quality generated resumes by Generative Adversarial
Networks (GANs), which can refine the resume representations for better
recommendation results. Extensive experiments on three large real-world
recruitment datasets demonstrate the effectiveness of our proposed method.