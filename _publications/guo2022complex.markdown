---
layout: publication
title: Complex Reading Comprehension Through Question Decomposition
authors: Guo Xiao-yu, Li Yuan-fang, Haffari Gholamreza
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2022
bibkey: guo2022complex
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.03277'}]
tags: [Datasets, ACL, RAG]
---
Multi-hop reading comprehension requires not only the ability to reason over
raw text but also the ability to combine multiple evidence. We propose a novel
learning approach that helps language models better understand difficult
multi-hop questions and perform "complex, compositional" reasoning. Our model
first learns to decompose each multi-hop question into several sub-questions by
a trainable question decomposer. Instead of answering these sub-questions, we
directly concatenate them with the original question and context, and leverage
a reading comprehension model to predict the answer in a sequence-to-sequence
manner. By using the same language model for these two components, our best
seperate/unified t5-base variants outperform the baseline by 7.2/6.1 absolute
F1 points on a hard subset of DROP dataset.