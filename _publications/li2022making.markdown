---
layout: publication
title: Making Large Language Models Better Reasoners With Step-aware Verifier
authors: Yifei Li et al.
conference: Arxiv
year: 2022
citations: 26
bibkey: li2022making
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2206.02336v3'}]
tags: [Few-Shot, GPT, Model Architecture, Prompting]
---
Few-shot learning is a challenging task that requires language models to
generalize from limited examples. Large language models like GPT-3 and PaLM
have made impressive progress in this area, but they still face difficulties in
reasoning tasks such as GSM8K, a benchmark for arithmetic problems. To improve
their reasoning skills, previous work has proposed to guide the language model
with prompts that elicit a series of reasoning steps before giving the final
answer, achieving a significant improvement on GSM8K from 17.9% to 58.1% in
problem-solving rate. In this paper, we present DIVERSE (Diverse Verifier on
Reasoning Step), a novel approach that further enhances the reasoning
capability of language models. DIVERSE has three main components: first, it
generates diverse prompts to explore different reasoning paths for the same
question; second, it uses a verifier to filter out incorrect answers based on a
weighted voting scheme; and third, it verifies each reasoning step individually
instead of the whole chain. We evaluate DIVERSE on the latest language model
code-davinci-002 and show that it achieves new state-of-the-art results on six
of eight reasoning benchmarks (e.g., GSM8K 74.4% to 83.2%).