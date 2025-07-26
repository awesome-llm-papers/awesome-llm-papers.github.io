---
layout: publication
title: 'Transformers Without Tears: Improving The Normalization Of Self-attention'
authors: Toan Q. Nguyen, Julian Salazar
conference: Arxiv
year: 2019
bibkey: nguyen2019transformers
citations: 133
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.05895'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Toan Q. Nguyen, Julian Salazar
---
We evaluate three simple, normalization-centric changes to improve
Transformer training. First, we show that pre-norm residual connections
(PreNorm) and smaller initializations enable warmup-free, validation-based
training with large learning rates. Second, we propose \\(ℓ₂\\) normalization
with a single scale parameter (ScaleNorm) for faster training and better
performance. Finally, we reaffirm the effectiveness of normalizing word
embeddings to a fixed length (FixNorm). On five low-resource translation pairs
from TED Talks-based corpora, these changes always converge, giving an average
+1.1 BLEU over state-of-the-art bilingual baselines and a new 32.8 BLEU on
IWSLT'15 English-Vietnamese. We observe sharper performance curves, more
consistent gradient norms, and a linear relationship between activation scaling
and decoder depth. Surprisingly, in the high-resource setting (WMT'14
English-German), ScaleNorm and FixNorm remain competitive but PreNorm degrades
performance.