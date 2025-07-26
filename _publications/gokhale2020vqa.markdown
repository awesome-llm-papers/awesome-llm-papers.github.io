---
layout: publication
title: 'VQA-LOL: Visual Question Answering Under The Lens Of Logic'
authors: Tejas Gokhale, Pratyay Banerjee, Chitta Baral, Yezhou Yang
conference: Lecture Notes in Computer Science
year: 2020
bibkey: gokhale2020vqa
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.08325'}]
tags: ["Datasets", "Evaluation"]
short_authors: Gokhale et al.
---
Logical connectives and their implications on the meaning of a natural
language sentence are a fundamental aspect of understanding. In this paper, we
investigate whether visual question answering (VQA) systems trained to answer a
question about an image, are able to answer the logical composition of multiple
such questions. When put under this \textit\{Lens of Logic\}, state-of-the-art
VQA models have difficulty in correctly answering these logically composed
questions. We construct an augmentation of the VQA dataset as a benchmark, with
questions containing logical compositions and linguistic transformations
(negation, disjunction, conjunction, and antonyms). We propose our \{Lens of
Logic (LOL)\} model which uses question-attention and logic-attention to
understand logical connectives in the question, and a novel
Fr\'echet-Compatibility Loss, which ensures that the answers of the component
questions and the composed question are consistent with the inferred logical
operation. Our model shows substantial improvement in learning logical
compositions while retaining performance on VQA. We suggest this work as a move
towards robustness by embedding logical connectives in visual understanding.