---
layout: publication
title: 'BLIVA: A Simple Multimodal LLM For Better Handling Of Text-rich Visual Questions'
authors: Wenbo Hu et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2023
citations: 30
bibkey: hu2023simple
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.09936'}, {name: Code,
    url: 'https://github.com/mlpc-ucsd/BLIVA'}]
tags: [Has Code, Applications, Reinforcement Learning, Multimodal Models, Prompting,
  Evaluation]
---
Vision Language Models (VLMs), which extend Large Language Models (LLM) by
incorporating visual understanding capability, have demonstrated significant
advancements in addressing open-ended visual question-answering (VQA) tasks.
However, these models cannot accurately interpret images infused with text, a
common occurrence in real-world scenarios. Standard procedures for extracting
information from images often involve learning a fixed set of query embeddings.
These embeddings are designed to encapsulate image contexts and are later used
as soft prompt inputs in LLMs. Yet, this process is limited to the token count,
potentially curtailing the recognition of scenes with text-rich context. To
improve upon them, the present study introduces BLIVA: an augmented version of
InstructBLIP with Visual Assistant. BLIVA incorporates the query embeddings
from InstructBLIP and also directly projects encoded patch embeddings into the
LLM, a technique inspired by LLaVA. This approach assists the model to capture
intricate details potentially missed during the query decoding process.
Empirical evidence demonstrates that our model, BLIVA, significantly enhances
performance in processing text-rich VQA benchmarks (up to 17.76% in OCR-VQA
benchmark) and in undertaking general (not particularly text-rich) VQA
benchmarks (up to 7.9% in Visual Spatial Reasoning benchmark), and achieved
17.72% overall improvement in a comprehensive multimodal LLM benchmark (MME),
comparing to our baseline InstructBLIP. BLIVA demonstrates significant
capability in decoding real-world images, irrespective of text presence. To
demonstrate the broad industry applications enabled by BLIVA, we evaluate the
model using a new dataset comprising YouTube thumbnails paired with
question-answer sets across 11 diverse categories. Our code and models are
freely accessible at https://github.com/mlpc-ucsd/BLIVA.