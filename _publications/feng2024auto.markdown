---
layout: publication
title: 'Auto-demo Prompting: Leveraging Generated Outputs As Demonstrations For Enhanced
  Batch Prompting'
authors: Feng Longyu, Hong Mengze, Zhang Chen Jason
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2024
bibkey: feng2024auto
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.01724'}]
tags: [Prompting, Efficiency And Optimization, ACL, Few Shot, Applications, In Context
    Learning, RAG, GPT, Reinforcement Learning]
---
Batch prompting is a common technique in large language models (LLMs) used to
process multiple inputs simultaneously, aiming to improve computational
efficiency. However, as batch sizes increase, performance degradation often
occurs due to the model's difficulty in handling lengthy context inputs.
Existing methods that attempt to mitigate these issues rely solely on batch
data arrangement and majority voting rather than improving the design of the
batch prompt itself. In this paper, we address these limitations by proposing
"Auto-Demo Prompting," a novel approach that leverages the question-output
pairs from earlier questions within a batch as demonstrations for subsequent
answer inference. We provide a formal theoretical analysis of how Auto-Demo
Prompting functions within the autoregressive generation process of LLMs,
illustrating how it utilizes prior outputs to optimize the model's internal
representations. Our method effectively bridges the gap between batch prompting
and few-shot prompting, enhancing performance with only a slight compromise in
token usage. Experimental results across five NLP tasks demonstrate its
effectiveness in mitigating performance degradation and occasionally
outperforming single prompts. Furthermore, it opens new avenues for applying
few-shot learning techniques, such as demonstration selection, within batch
prompting, making it a robust solution for real-world applications.