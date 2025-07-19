---
layout: publication
title: Improving Zero-shot Multilingual Neural Machine Translation For Low-resource
  Languages
authors: Li Chenyang, Luo Gongxu
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2021
bibkey: li2021improving
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.00712'}]
tags: [Evaluation, ACL, Reinforcement Learning, SLT, Alt]
---
Although the multilingual Neural Machine Translation(NMT), which extends
Google's multilingual NMT, has ability to perform zero-shot translation and the
iterative self-learning algorithm can improve the quality of zero-shot
translation, it confronts with two problems: the multilingual NMT model is
prone to generate wrong target language when implementing zero-shot
translation; the self-learning algorithm, which uses beam search to generate
synthetic parallel data, demolishes the diversity of the generated source
language and amplifies the impact of the same noise during the iterative
learning process. In this paper, we propose the tagged-multilingual NMT model
and improve the self-learning algorithm to handle these two problems. Firstly,
we extend the Google's multilingual NMT model and add target tokens to the
target languages, which associates the start tag with the target language to
ensure that the source language can be translated to the required target
language. Secondly, we improve the self-learning algorithm by replacing beam
search with random sample to increases the diversity of the generated data and
makes it properly cover the true data distribution. Experimental results on
IWSLT show that the adjusted tagged-multilingual NMT separately obtains 9.41
and 7.85 BLEU scores over the multilingual NMT on 2010 and 2017
Romanian-Italian test sets. Similarly, it obtains 9.08 and 7.99 BLEU scores on
Italian-Romanian zero-shot translation. Furthermore, the improved self-learning
algorithm shows its superiorities over the conventional self-learning algorithm
on zero-shot translations.