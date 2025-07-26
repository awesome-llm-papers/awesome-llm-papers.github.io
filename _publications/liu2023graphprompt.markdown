---
layout: publication
title: 'Graphprompt: Unifying Pre-training And Downstream Tasks For Graph Neural Networks'
authors: Zemin Liu, Xingtong Yu, Yuan Fang, Xinming Zhang
conference: Proceedings of the ACM Web Conference 2023
year: 2023
bibkey: liu2023graphprompt
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.08043'}]
tags: ["Applications", "Prompting", "Training Techniques"]
short_authors: Liu et al.
---
Graphs can model complex relationships between objects, enabling a myriad of
Web applications such as online page/article classification and social
recommendation. While graph neural networks(GNNs) have emerged as a powerful
tool for graph representation learning, in an end-to-end supervised setting,
their performance heavily rely on a large amount of task-specific supervision.
To reduce labeling requirement, the "pre-train, fine-tune" and "pre-train,
prompt" paradigms have become increasingly common. In particular, prompting is
a popular alternative to fine-tuning in natural language processing, which is
designed to narrow the gap between pre-training and downstream objectives in a
task-specific manner. However, existing study of prompting on graphs is still
limited, lacking a universal treatment to appeal to different downstream tasks.
In this paper, we propose GraphPrompt, a novel pre-training and prompting
framework on graphs. GraphPrompt not only unifies pre-training and downstream
tasks into a common task template, but also employs a learnable prompt to
assist a downstream task in locating the most relevant knowledge from the
pre-train model in a task-specific manner. Finally, we conduct extensive
experiments on five public datasets to evaluate and analyze GraphPrompt.