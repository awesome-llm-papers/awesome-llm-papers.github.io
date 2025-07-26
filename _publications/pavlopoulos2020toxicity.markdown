---
layout: publication
title: 'Toxicity Detection: Does Context Really Matter?'
authors: John Pavlopoulos, Jeffrey Sorensen, Lucas Dixon, Nithum Thain, Ion Androutsopoulos
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: pavlopoulos2020toxicity
citations: 91
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.00998'}]
tags: ["Datasets"]
short_authors: Pavlopoulos et al.
---
Moderation is crucial to promoting healthy on-line discussions. Although
several `toxicity' detection datasets and models have been published, most of
them ignore the context of the posts, implicitly assuming that comments maybe
judged independently. We investigate this assumption by focusing on two
questions: (a) does context affect the human judgement, and (b) does
conditioning on context improve performance of toxicity detection systems? We
experiment with Wikipedia conversations, limiting the notion of context to the
previous post in the thread and the discussion title. We find that context can
both amplify or mitigate the perceived toxicity of posts. Moreover, a small but
significant subset of manually labeled posts (5% in one of our experiments) end
up having the opposite toxicity labels if the annotators are not provided with
context. Surprisingly, we also find no evidence that context actually improves
the performance of toxicity classifiers, having tried a range of classifiers
and mechanisms to make them context aware. This points to the need for larger
datasets of comments annotated in context. We make our code and data publicly
available.