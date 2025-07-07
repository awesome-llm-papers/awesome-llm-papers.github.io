---
layout: publication
title: Prompt Tuning For Generative Multimodal Pretrained Models
authors: Hao Yang et al.
conference: Arxiv
year: 2022
citations: 19
bibkey: yang2022prompt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.02532'}, {name: Code,
    url: 'https://github.com/OFA-Sys/OFA'}]
tags: [Training Techniques, Has Code, Security, Prompting, Multimodal Models]
---
Prompt tuning has become a new paradigm for model tuning and it has
demonstrated success in natural language pretraining and even vision
pretraining. In this work, we explore the transfer of prompt tuning to
multimodal pretraining, with a focus on generative multimodal pretrained
models, instead of contrastive ones. Specifically, we implement prompt tuning
on the unified sequence-to-sequence pretrained model adaptive to both
understanding and generation tasks. Experimental results demonstrate that the
light-weight prompt tuning can achieve comparable performance with finetuning
and surpass other light-weight tuning methods. Besides, in comparison with
finetuned models, the prompt-tuned models demonstrate improved robustness
against adversarial attacks. We further figure out that experimental factors,
including the prompt length, prompt depth, and reparameteratization, have great
impacts on the model performance, and thus we empirically provide a
recommendation for the setups of prompt tuning. Despite the observed
advantages, we still find some limitations in prompt tuning, and we
correspondingly point out the directions for future studies. Codes are
available at https://github.com/OFA-Sys/OFA