---
layout: publication
title: 'Gigacheck: Detecting Llm-generated Content'
authors: Tolstykh et al.
conference: Communications of the ACM
year: 2024
bibkey: tolstykh2024gigacheck
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.23728'}]
tags: [RAG, Tools, Datasets]
---
With the increasing quality and spread of LLM-based assistants, the amount of
LLM-generated content is growing rapidly. In many cases and tasks, such texts
are already indistinguishable from those written by humans, and the quality of
generation tends to only increase. At the same time, detection methods are
developing more slowly, making it challenging to prevent misuse of generative
AI technologies.
  In this work, we investigate the task of generated text detection by
proposing the GigaCheck. Our research explores two approaches: (i)
distinguishing human-written texts from LLM-generated ones, and (ii) detecting
LLM-generated intervals in Human-Machine collaborative texts. For the first
task, our approach utilizes a general-purpose LLM, leveraging its extensive
language abilities to fine-tune efficiently for the downstream task of
LLM-generated text detection, achieving high performance even with limited
data. For the second task, we propose a novel approach that combines computer
vision and natural language processing techniques. Specifically, we use a
fine-tuned general-purpose LLM in conjunction with a DETR-like detection model,
adapted from computer vision, to localize AI-generated intervals within text.
  We evaluate the GigaCheck on five classification datasets with English texts
and three datasets designed for Human-Machine collaborative text analysis. Our
results demonstrate that GigaCheck outperforms previous methods, even in
out-of-distribution settings, establishing a strong baseline across all
datasets.