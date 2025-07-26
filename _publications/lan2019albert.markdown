---
layout: publication
title: 'ALBERT: A Lite BERT For Self-supervised Learning Of Language Representations'
authors: Zhenzhong Lan, Mingda Chen, Sebastian Goodman, Kevin Gimpel, Piyush Sharma,
  Radu Soricut
conference: Arxiv
year: 2019
bibkey: lan2019albert
citations: 4206
additional_links: [{name: Code, url: 'https://github.com/google-research/ALBERT'},
  {name: Paper, url: 'https://arxiv.org/abs/1909.11942'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Lan et al.
---
Increasing model size when pretraining natural language representations often
results in improved performance on downstream tasks. However, at some point
further model increases become harder due to GPU/TPU memory limitations and
longer training times. To address these problems, we present two
parameter-reduction techniques to lower memory consumption and increase the
training speed of BERT. Comprehensive empirical evidence shows that our
proposed methods lead to models that scale much better compared to the original
BERT. We also use a self-supervised loss that focuses on modeling
inter-sentence coherence, and show it consistently helps downstream tasks with
multi-sentence inputs. As a result, our best model establishes new
state-of-the-art results on the GLUE, RACE, and \squad benchmarks while having
fewer parameters compared to BERT-large. The code and the pretrained models are
available at https://github.com/google-research/ALBERT.