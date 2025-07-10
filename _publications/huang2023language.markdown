---
layout: publication
title: 'Language Is Not All You Need: Aligning Perception With Language Models'
authors: Shaohan Huang et al.
conference: Arxiv
year: 2023
citations: 132
bibkey: huang2023language
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2302.14045v2'}]
tags: [Reinforcement Learning, Multimodal Models, Prompting, Few-Shot]
---
A big convergence of language, multimodal perception, action, and world
modeling is a key step toward artificial general intelligence. In this work, we
introduce Kosmos-1, a Multimodal Large Language Model (MLLM) that can perceive
general modalities, learn in context (i.e., few-shot), and follow instructions
(i.e., zero-shot). Specifically, we train Kosmos-1 from scratch on web-scale
multimodal corpora, including arbitrarily interleaved text and images,
image-caption pairs, and text data. We evaluate various settings, including
zero-shot, few-shot, and multimodal chain-of-thought prompting, on a wide range
of tasks without any gradient updates or finetuning. Experimental results show
that Kosmos-1 achieves impressive performance on (i) language understanding,
generation, and even OCR-free NLP (directly fed with document images), (ii)
perception-language tasks, including multimodal dialogue, image captioning,
visual question answering, and (iii) vision tasks, such as image recognition
with descriptions (specifying classification via text instructions). We also
show that MLLMs can benefit from cross-modal transfer, i.e., transfer knowledge
from language to multimodal, and from multimodal to language. In addition, we
introduce a dataset of Raven IQ test, which diagnoses the nonverbal reasoning
capability of MLLMs.