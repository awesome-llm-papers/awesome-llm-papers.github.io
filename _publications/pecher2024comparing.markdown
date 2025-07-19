---
layout: publication
title: 'Comparing Specialised Small And General Large Language Models On Text Classification:
  100 Labelled Samples To Achieve Break-even Performance'
authors: Pecher Branislav, Srba Ivan, Bielikova Maria
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2024
bibkey: pecher2024comparing
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.12819'}]
tags: [Prompting, Training Techniques, Fine Tuning, ACL, EMNLP, In Context Learning,
  RAG, Datasets]
---
When solving NLP tasks with limited labelled data, researchers typically either use a general large language model without further update, or use a small number of labelled samples to tune a specialised smaller model. In this work, we answer an important question -- how many labelled samples are required for the specialised small models to outperform general large models, while taking the performance variance into consideration. By observing the behaviour of fine-tuning, instruction-tuning, prompting and in-context learning on 8 language models, we identify such performance break-even points across 8 representative text classification tasks of varying characteristics. We show that the specialised models often need only few samples (on average \\(100\\)) to be on par or better than the general ones. At the same time, the number of required labels strongly depends on the dataset or task characteristics, with fine-tuning on binary datasets requiring significantly more samples. When performance variance is taken into consideration, the number of required labels increases on average by \\(100 - 200%\\). Finally, larger models do not consistently lead to better performance and lower variance, with 4-bit quantisation having negligible impact.