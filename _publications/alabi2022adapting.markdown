---
layout: publication
title: Adapting Pre-trained Language Models To African Languages Via Multilingual
  Adaptive Fine-tuning
authors: Jesujoba O. Alabi, David Ifeoluwa Adelani, Marius Mosbach, Dietrich Klakow
conference: Arxiv
year: 2022
citations: 47
bibkey: alabi2022adapting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.06487'}]
tags: [Model Architecture, Fine-Tuning, RAG, Pre-Training, BERT, Training Techniques,
  Evaluation]
---
Multilingual pre-trained language models (PLMs) have demonstrated impressive
performance on several downstream tasks for both high-resourced and
low-resourced languages. However, there is still a large performance drop for
languages unseen during pre-training, especially African languages. One of the
most effective approaches to adapt to a new language is \textit\{language
adaptive fine-tuning\} (LAFT) -- fine-tuning a multilingual PLM on monolingual
texts of a language using the pre-training objective. However, adapting to a
target language individually takes a large disk space and limits the
cross-lingual transfer abilities of the resulting models because they have been
specialized for a single language. In this paper, we perform
\textit\{multilingual adaptive fine-tuning\} on 17 most-resourced African
languages and three other high-resource languages widely spoken on the African
continent to encourage cross-lingual transfer learning. To further specialize
the multilingual PLM, we removed vocabulary tokens from the embedding layer
that corresponds to non-African writing scripts before MAFT, thus reducing the
model size by around 50%. Our evaluation on two multilingual PLMs (AfriBERTa
and XLM-R) and three NLP tasks (NER, news topic classification, and sentiment
classification) shows that our approach is competitive to applying LAFT on
individual languages while requiring significantly less disk space.
Additionally, we show that our adapted PLM also improves the zero-shot
cross-lingual transfer abilities of parameter efficient fine-tuning methods.