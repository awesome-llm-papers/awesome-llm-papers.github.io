---
layout: publication
title: Semi-autoregressive Training Improves Mask-predict Decoding
authors: Ghazvininejad Marjan, Levy Omer, Zettlemoyer Luke
conference: Arxiv
year: 2020
bibkey: ghazvininejad2020semi
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2001.08785'}]
tags: [Training Techniques, GPT, Masked Language Model, BERT, Language Modeling]
---
The recently proposed mask-predict decoding algorithm has narrowed the
performance gap between semi-autoregressive machine translation models and the
traditional left-to-right approach. We introduce a new training method for
conditional masked language models, SMART, which mimics the semi-autoregressive
behavior of mask-predict, producing training examples that contain model
predictions as part of their inputs. Models trained with SMART produce
higher-quality translations when using mask-predict decoding, effectively
closing the remaining performance gap with fully autoregressive models.