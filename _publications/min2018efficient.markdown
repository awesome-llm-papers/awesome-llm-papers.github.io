---
layout: publication
title: Efficient And Robust Question Answering From Minimal Context Over Documents
authors: Sewon Min, Victor Zhong, Richard Socher, Caiming Xiong
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: min2018efficient
citations: 150
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.08092'}]
tags: ["Datasets", "Security", "Training Techniques"]
short_authors: Min et al.
---
Neural models for question answering (QA) over documents have achieved
significant performance improvements. Although effective, these models do not
scale to large corpora due to their complex modeling of interactions between
the document and the question. Moreover, recent work has shown that such models
are sensitive to adversarial inputs. In this paper, we study the minimal
context required to answer the question, and find that most questions in
existing datasets can be answered with a small set of sentences. Inspired by
this observation, we propose a simple sentence selector to select the minimal
set of sentences to feed into the QA model. Our overall system achieves
significant reductions in training (up to 15 times) and inference times (up to
13 times), with accuracy comparable to or better than the state-of-the-art on
SQuAD, NewsQA, TriviaQA and SQuAD-Open. Furthermore, our experimental results
and analyses show that our approach is more robust to adversarial inputs.