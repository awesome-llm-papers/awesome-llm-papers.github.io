---
layout: publication
title: 'PTR: Prompt Tuning With Rules For Text Classification'
authors: Xu Han, Weilin Zhao, Ning Ding, Zhiyuan Liu, Maosong Sun
conference: Arxiv
year: 2021
citations: 233
bibkey: han2021prompt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.11259'}]
tags: [Few-Shot, Prompting]
---
Fine-tuned pre-trained language models (PLMs) have achieved awesome
performance on almost all NLP tasks. By using additional prompts to fine-tune
PLMs, we can further stimulate the rich knowledge distributed in PLMs to better
serve downstream tasks. Prompt tuning has achieved promising results on some
few-class classification tasks such as sentiment classification and natural
language inference. However, manually designing lots of language prompts is
cumbersome and fallible. For those auto-generated prompts, it is also expensive
and time-consuming to verify their effectiveness in non-few-shot scenarios.
Hence, it is still challenging for prompt tuning to address many-class
classification tasks. To this end, we propose prompt tuning with rules (PTR)
for many-class text classification and apply logic rules to construct prompts
with several sub-prompts. In this way, PTR is able to encode prior knowledge of
each class into prompt tuning. We conduct experiments on relation
classification, a typical and complicated many-class classification task, and
the results show that PTR can significantly and consistently outperform
existing state-of-the-art baselines. This indicates that PTR is a promising
approach to take advantage of both human prior knowledge and PLMs for those
complicated classification tasks.