---
layout: publication
title: 'SMI: An Information-theoretic Metric For Predicting Model Knowledge Solely
  From Pre-training Signals'
authors: Jiang et al.
conference: Proceedings of the 24th international conference on Machine learning
year: 2025
bibkey: jiang2025smi
citations: 1297
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.04066'}]
tags: [Training Techniques, GPT, Tools, Evaluation, Model Architecture, ICML, Reinforcement
    Learning, Datasets]
---
The GPT-4 technical report highlights the possibility of predicting model performance on downstream tasks using only pre-training signals, though detailed methodologies are absent. Such predictive capabilities are essential for resource-efficient pre-training and the construction of task-aligned datasets. In this paper, we aim to predict performance in closed-book question answering (QA), a vital downstream task indicative of a model's internal knowledge. We address three primary challenges: (1) limited access to and understanding of pre-training corpora, (2) limitations of current evaluation methods for pre-trained models, and (3) limitations of frequency-based metrics in predicting model performance. In response to these challenges, we conduct large-scale retrieval and semantic analysis across the pre-training corpora of 21 publicly available and 3 custom-trained large language models. Subsequently, we develop a multi-template QA evaluation framework incorporating paraphrased question variants. Building on these foundations, we propose Size-dependent Mutual Information (SMI), an information-theoretic metric that linearly correlates pre-training data characteristics, model size, and QA accuracy, without requiring any additional training. The experimental results demonstrate that SMI outperforms co-occurrence-based baselines, achieving \\(R^2\\) > 0.75 on models with over one billion parameters. Theoretical analysis further reveals the marginal benefits of scaling model size and optimizing data, indicating that the upper limit of specific QA task accuracy is approximately 80%. Our project is available at https://github.com/yuhui1038/SMI.