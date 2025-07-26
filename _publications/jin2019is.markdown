---
layout: publication
title: Is BERT Really Robust? A Strong Baseline For Natural Language Attack On Text
  Classification And Entailment
authors: di Jin, Zhijing Jin, Joey Tianyi Zhou, Peter Szolovits
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: jin2019is
citations: 729
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.11932'}]
tags: ["AAAI", "Model Architecture", "Security"]
short_authors: Jin et al.
---
Machine learning algorithms are often vulnerable to adversarial examples that
have imperceptible alterations from the original counterparts but can fool the
state-of-the-art models. It is helpful to evaluate or even improve the
robustness of these models by exposing the maliciously crafted adversarial
examples. In this paper, we present TextFooler, a simple but strong baseline to
generate natural adversarial text. By applying it to two fundamental natural
language tasks, text classification and textual entailment, we successfully
attacked three target models, including the powerful pre-trained BERT, and the
widely used convolutional and recurrent neural networks. We demonstrate the
advantages of this framework in three ways: (1) effective---it outperforms
state-of-the-art attacks in terms of success rate and perturbation rate, (2)
utility-preserving---it preserves semantic content and grammaticality, and
remains correctly classified by humans, and (3) efficient---it generates
adversarial text with computational complexity linear to the text length. *The
code, pre-trained target models, and test examples are available at
https://github.com/jind11/TextFooler.