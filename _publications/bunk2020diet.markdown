---
layout: publication
title: 'DIET: Lightweight Language Understanding For Dialogue Systems'
authors: Tanja Bunk, Daksh Varshneya, Vladimir Vlasov, Alan Nichol
conference: Arxiv
year: 2020
bibkey: bunk2020diet
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.09936'}]
tags: ["Model Architecture"]
short_authors: Bunk et al.
---
Large-scale pre-trained language models have shown impressive results on
language understanding benchmarks like GLUE and SuperGLUE, improving
considerably over other pre-training methods like distributed representations
(GloVe) and purely supervised approaches. We introduce the Dual Intent and
Entity Transformer (DIET) architecture, and study the effectiveness of
different pre-trained representations on intent and entity prediction, two
common dialogue language understanding tasks. DIET advances the state of the
art on a complex multi-domain NLU dataset and achieves similarly high
performance on other simpler datasets. Surprisingly, we show that there is no
clear benefit to using large pre-trained models for this task, and in fact DIET
improves upon the current state of the art even in a purely supervised setup
without any pre-trained embeddings. Our best performing model outperforms
fine-tuning BERT and is about six times faster to train.