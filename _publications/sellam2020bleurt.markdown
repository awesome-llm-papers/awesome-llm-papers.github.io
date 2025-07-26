---
layout: publication
title: 'BLEURT: Learning Robust Metrics For Text Generation'
authors: Thibault Sellam, Dipanjan Das, Ankur P. Parikh
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: sellam2020bleurt
citations: 804
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.04696'}]
tags: ["Datasets", "Evaluation", "Model Architecture", "Training Techniques"]
short_authors: Thibault Sellam, Dipanjan Das, Ankur P. Parikh
---
Text generation has made significant advances in the last few years. Yet,
evaluation metrics have lagged behind, as the most popular choices (e.g., BLEU
and ROUGE) may correlate poorly with human judgments. We propose BLEURT, a
learned evaluation metric based on BERT that can model human judgments with a
few thousand possibly biased training examples. A key aspect of our approach is
a novel pre-training scheme that uses millions of synthetic examples to help
the model generalize. BLEURT provides state-of-the-art results on the last
three years of the WMT Metrics shared task and the WebNLG Competition dataset.
In contrast to a vanilla BERT-based approach, it yields superior results even
when the training data is scarce and out-of-distribution.