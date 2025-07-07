---
layout: publication
title: 'DIN-SQL: Decomposed In-context Learning Of Text-to-sql With Self-correction'
authors: Mohammadreza Pourreza, Davood Rafiei
conference: Arxiv
year: 2023
citations: 36
bibkey: pourreza2023din
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.11015'}]
tags: [Few-Shot, In-Context Learning, Prompting]
---
There is currently a significant gap between the performance of fine-tuned
models and prompting approaches using Large Language Models (LLMs) on the
challenging task of text-to-SQL, as evaluated on datasets such as Spider. To
improve the performance of LLMs in the reasoning process, we study how
decomposing the task into smaller sub-tasks can be effective. In particular, we
show that breaking down the generation problem into sub-problems and feeding
the solutions of those sub-problems into LLMs can be an effective approach for
significantly improving their performance. Our experiments with three LLMs show
that this approach consistently improves their simple few-shot performance by
roughly 10%, pushing the accuracy of LLMs towards SOTA or surpassing it. On the
holdout test set of Spider, the SOTA, in terms of execution accuracy, was 79.9
and the new SOTA at the time of this writing using our approach is 85.3. Our
approach with in-context learning beats many heavily fine-tuned models by at
least 5%. Additionally, when evaluated on the BIRD benchmark, our approach
achieved an execution accuracy of 55.9%, setting a new SOTA on its holdout test
set.