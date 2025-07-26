---
layout: publication
title: Adaptation Of Deep Bidirectional Multilingual Transformers For Russian Language
authors: Yuri Kuratov, Mikhail Arkhipov
conference: Arxiv
year: 2019
bibkey: kuratov2019adaptation
citations: 252
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.07213'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Yuri Kuratov, Mikhail Arkhipov
---
The paper introduces methods of adaptation of multilingual masked language
models for a specific language. Pre-trained bidirectional language models show
state-of-the-art performance on a wide range of tasks including reading
comprehension, natural language inference, and sentiment analysis. At the
moment there are two alternative approaches to train such models: monolingual
and multilingual. While language specific models show superior performance,
multilingual models allow to perform a transfer from one language to another
and solve tasks for different languages simultaneously. This work shows that
transfer learning from a multilingual model to monolingual model results in
significant growth of performance on such tasks as reading comprehension,
paraphrase detection, and sentiment analysis. Furthermore, multilingual
initialization of monolingual model substantially reduces training time.
Pre-trained models for the Russian language are open sourced.