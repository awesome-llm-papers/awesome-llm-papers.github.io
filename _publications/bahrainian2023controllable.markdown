---
layout: publication
title: Controllable Topic-focused Abstractive Summarization
authors: Bahrainian Seyed Ali, Jaggi Martin, Eickhoff Carsten
conference: Proceedings of the 2nd Workshop on Neural Machine Translation and Generation
year: 2023
bibkey: bahrainian2023controllable
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.06724'}]
tags: [Training Techniques, Attention Mechanism, Evaluation, Transformer, Model Architecture,
  Fine Tuning, Datasets]
---
Controlled abstractive summarization focuses on producing condensed versions
of a source article to cover specific aspects by shifting the distribution of
generated text towards a desired style, e.g., a set of topics. Subsequently,
the resulting summaries may be tailored to user-defined requirements. This
paper presents a new Transformer-based architecture capable of producing
topic-focused summaries. The architecture modifies the cross-attention
mechanism of the Transformer to bring topic-focus control to the generation
process while not adding any further parameters to the model. We show that our
model sets a new state of the art on the NEWTS dataset in terms of
topic-focused abstractive summarization as well as a topic-prevalence score.
Moreover, we show via extensive experiments that our proposed topical
cross-attention mechanism can be plugged into various Transformer models, such
as BART and T5, improving their performance on the CNN/Dailymail and XSum
benchmark datasets for abstractive summarization. This is achieved via
fine-tuning, without requiring training from scratch. Finally, we show through
human evaluation that our model generates more faithful summaries outperforming
the state-of-the-art Frost model.