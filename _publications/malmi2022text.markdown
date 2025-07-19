---
layout: publication
title: Text Generation With Text-editing Models
authors: Malmi et al.
conference: Arxiv
year: 2022
bibkey: malmi2022text
citations: 738
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.07043'}]
tags: [Interpretability And Explainability, Alt, Ethics And Bias, Efficiency And Optimization,
  Language Modeling, Reinforcement Learning]
---
Text-editing models have recently become a prominent alternative to seq2seq
models for monolingual text-generation tasks such as grammatical error
correction, simplification, and style transfer. These tasks share a common
trait - they exhibit a large amount of textual overlap between the source and
target texts. Text-editing models take advantage of this observation and learn
to generate the output by predicting edit operations applied to the source
sequence. In contrast, seq2seq models generate outputs word-by-word from
scratch thus making them slow at inference time. Text-editing models provide
several benefits over seq2seq models including faster inference speed, higher
sample efficiency, and better control and interpretability of the outputs. This
tutorial provides a comprehensive overview of text-editing models and current
state-of-the-art approaches, and analyzes their pros and cons. We discuss
challenges related to productionization and how these models can be used to
mitigate hallucination and bias, both pressing challenges in the field of text
generation.