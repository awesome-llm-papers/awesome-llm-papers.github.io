---
layout: publication
title: 'LAMOL: Language Modeling For Lifelong Language Learning'
authors: Fan-keng Sun, Cheng-hao Ho, Hung-yi Lee
conference: Arxiv
year: 2019
bibkey: sun2019lamol
citations: 78
additional_links: [{name: Code, url: 'https://github.com/jojotenya/LAMOL'}, {name: Paper,
    url: 'https://arxiv.org/abs/1909.03329'}]
tags: ["Has Code", "Training Techniques"]
short_authors: Fan-keng Sun, Cheng-hao Ho, Hung-yi Lee
---
Most research on lifelong learning applies to images or games, but not
language. We present LAMOL, a simple yet effective method for lifelong language
learning (LLL) based on language modeling. LAMOL replays pseudo-samples of
previous tasks while requiring no extra memory or model capacity. Specifically,
LAMOL is a language model that simultaneously learns to solve the tasks and
generate training samples. When the model is trained for a new task, it
generates pseudo-samples of previous tasks for training alongside data for the
new task. The results show that LAMOL prevents catastrophic forgetting without
any sign of intransigence and can perform five very different language tasks
sequentially with only one model. Overall, LAMOL outperforms previous methods
by a considerable margin and is only 2-3% worse than multitasking, which is
usually considered the LLL upper bound. The source code is available at
https://github.com/jojotenya/LAMOL.