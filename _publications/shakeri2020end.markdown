---
layout: publication
title: End-to-end Synthetic Data Generation For Domain Adaptation Of Question Answering
  Systems
authors: Siamak Shakeri et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
citations: 23
bibkey: shakeri2020end
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.06028'}]
tags: [Transformer, Training Techniques, Fine-Tuning, Model Architecture]
---
We propose an end-to-end approach for synthetic QA data generation. Our model
comprises a single transformer-based encoder-decoder network that is trained
end-to-end to generate both answers and questions. In a nutshell, we feed a
passage to the encoder and ask the decoder to generate a question and an answer
token-by-token. The likelihood produced in the generation process is used as a
filtering score, which avoids the need for a separate filtering model. Our
generator is trained by fine-tuning a pretrained LM using maximum likelihood
estimation. The experimental results indicate significant improvements in the
domain adaptation of QA models outperforming current state-of-the-art methods.