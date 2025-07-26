---
layout: publication
title: 'Predictive Data Selection: The Data That Predicts Is The Data That Teaches'
authors: Kashun Shum, Yuzhen Huang, Hongjian Zou, Ding Qi, Yixuan Liao, Xiaoxin Chen,
  Qian Liu, Junxian He
conference: No Venue
year: 2025
bibkey: shum2025predictive
additional_links: [{name: Code, url: 'https://github.com/hkust-nlp/PreSelect'}, {
    name: Paper, url: 'https://arxiv.org/abs/hf2503.00808'}]
tags: ["Datasets", "Efficiency", "Evaluation", "Has Code", "Training Techniques"]
short_authors: Shum et al.
---
Language model pretraining involves training on extensive corpora, where data quality plays a pivotal role. In this work, we aim to directly estimate the contribution of data during pretraining and select pretraining data in an efficient manner. Specifically, we draw inspiration from recent findings showing that compression efficiency (i.e., the normalized loss) of diverse models on certain text correlates strongly with their downstream performance, when the text domain aligns with the downstream benchmark (Huang et al., 2024). Building on this observation, we hypothesize that data on which model losses are predictive of downstream abilities also contribute effectively to learning. To leverage this insight, we introduce data selection based on data's Predictive strength (Preselect), a lightweight and efficient data selection method that requires training and deploying only a fastText-based scorer. Through comprehensive experiments with 1B and 3B parameter models, we demonstrate that models trained on 30B tokens selected with PreSelect surpasses the performance of a vanilla baseline trained on 300B tokens, achieving a 10x reduction in compute requirements. Furthermore, PreSelect significantly outperforms other competitive data selection baselines, such as DCLM and FineWeb-Edu on a scale of 3B models trained on 100B tokens. We open-source our trained data selection scorer along with the curated datasets at https://github.com/hkust-nlp/PreSelect.

https://huggingface.co/discussions/paper/67c66383e5394bda7cbd0428