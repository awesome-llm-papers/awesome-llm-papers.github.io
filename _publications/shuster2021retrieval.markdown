---
layout: publication
title: Retrieval Augmentation Reduces Hallucination In Conversation
authors: Kurt Shuster, Spencer Poff, Moya Chen, Douwe Kiela, Jason Weston
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2021'
year: 2021
bibkey: shuster2021retrieval
citations: 286
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.07567'}]
tags: ["EMNLP"]
short_authors: Shuster et al.
---
Despite showing increasingly human-like conversational abilities,
state-of-the-art dialogue models often suffer from factual incorrectness and
hallucination of knowledge (Roller et al., 2020). In this work we explore the
use of neural-retrieval-in-the-loop architectures - recently shown to be
effective in open-domain QA (Lewis et al., 2020b; Izacard and Grave, 2020) -
for knowledge-grounded dialogue, a task that is arguably more challenging as it
requires querying based on complex multi-turn dialogue context and generating
conversationally coherent responses. We study various types of architectures
with multiple components - retrievers, rankers, and encoder-decoders - with the
goal of maximizing knowledgeability while retaining conversational ability. We
demonstrate that our best models obtain state-of-the-art performance on two
knowledge-grounded conversational tasks. The models exhibit open-domain
conversational capabilities, generalize effectively to scenarios not within the
training data, and, as verified by human evaluations, substantially reduce the
well-known problem of knowledge hallucination in state-of-the-art chatbots.