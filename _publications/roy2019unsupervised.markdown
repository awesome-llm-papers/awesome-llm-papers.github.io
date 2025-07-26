---
layout: publication
title: Unsupervised Paraphrasing Without Translation
authors: Aurko Roy, David Grangier
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: roy2019unsupervised
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.12752'}]
tags: ["Training Techniques"]
short_authors: Aurko Roy, David Grangier
---
Paraphrasing exemplifies the ability to abstract semantic content from
surface forms. Recent work on automatic paraphrasing is dominated by methods
leveraging Machine Translation (MT) as an intermediate step. This contrasts
with humans, who can paraphrase without being bilingual. This work proposes to
learn paraphrasing models from an unlabeled monolingual corpus only. To that
end, we propose a residual variant of vector-quantized variational
auto-encoder.
  We compare with MT-based approaches on paraphrase identification, generation,
and training augmentation. Monolingual paraphrasing outperforms unsupervised
translation in all settings. Comparisons with supervised translation are more
mixed: monolingual paraphrasing is interesting for identification and
augmentation; supervised translation is superior for generation.