---
layout: publication
title: 'Ctrlsum: Towards Generic Controllable Text Summarization'
authors: He et al.
conference: Arxiv
year: 2020
bibkey: he2020ctrlsum
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.04281'}]
tags: [Training Techniques, Prompting, Tools, Reinforcement Learning, Datasets]
---
Current summarization systems yield generic summaries that are disconnected
from users' preferences and expectations. To address this limitation, we
present CTRLsum, a novel framework for controllable summarization. Our approach
enables users to control multiple aspects of generated summaries by interacting
with the summarization system through textual input in the form of a set of
keywords or descriptive prompts. Using a single unified model, CTRLsum is able
to achieve a broad scope of summary manipulation at inference time without
requiring additional human annotations or pre-defining a set of control aspects
during training. We quantitatively demonstrate the effectiveness of our
approach on three domains of summarization datasets and five control aspects:
1) entity-centric and 2) length-controllable summarization, 3) contribution
summarization on scientific papers, 4) invention purpose summarization on
patent filings, and 5) question-guided summarization on news articles in a
reading comprehension setting. Moreover, when used in a standard, uncontrolled
summarization setting, CTRLsum achieves state-of-the-art results on the
CNN/DailyMail dataset. Code and model checkpoints are available at
https://github.com/salesforce/ctrl-sum