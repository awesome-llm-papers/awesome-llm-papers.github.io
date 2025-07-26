---
layout: publication
title: A Comparative Study Of Pretrained Language Models For Long Clinical Text
authors: Yikuan Li, Ramsey M. Wehbe, Faraz S. Ahmad, Hanyin Wang, Yuan Luo
conference: Journal of the American Medical Informatics Association
year: 2022
bibkey: li2022comparative
citations: 81
additional_links: [{name: Code, url: 'https://github.com/luoyuanlab/Clinical-Longformer,'},
  {name: Code, url: 'https://huggingface.co/yikuan8/Clinical-Longformer'}, {name: Paper,
    url: 'https://arxiv.org/abs/2301.11847'}]
tags: ["Model Architecture"]
short_authors: Li et al.
---
Objective: Clinical knowledge enriched transformer models (e.g.,
ClinicalBERT) have state-of-the-art results on clinical NLP (natural language
processing) tasks. One of the core limitations of these transformer models is
the substantial memory consumption due to their full self-attention mechanism,
which leads to the performance degradation in long clinical texts. To overcome
this, we propose to leverage long-sequence transformer models (e.g., Longformer
and BigBird), which extend the maximum input sequence length from 512 to 4096,
to enhance the ability to model long-term dependencies in long clinical texts.
  Materials and Methods: Inspired by the success of long sequence transformer
models and the fact that clinical notes are mostly long, we introduce two
domain enriched language models, Clinical-Longformer and Clinical-BigBird,
which are pre-trained on a large-scale clinical corpus. We evaluate both
language models using 10 baseline tasks including named entity recognition,
question answering, natural language inference, and document classification
tasks.
  Results: The results demonstrate that Clinical-Longformer and
Clinical-BigBird consistently and significantly outperform ClinicalBERT and
other short-sequence transformers in all 10 downstream tasks and achieve new
state-of-the-art results.
  Discussion: Our pre-trained language models provide the bedrock for clinical
NLP using long texts. We have made our source code available at
https://github.com/luoyuanlab/Clinical-Longformer, and the pre-trained models
available for public download at:
https://huggingface.co/yikuan8/Clinical-Longformer.
  Conclusion: This study demonstrates that clinical knowledge enriched
long-sequence transformers are able to learn long-term dependencies in long
clinical text. Our methods can also inspire the development of other
domain-enriched long-sequence transformers.