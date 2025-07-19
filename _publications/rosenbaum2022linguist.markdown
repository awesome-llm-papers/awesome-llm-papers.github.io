---
layout: publication
title: 'LINGUIST: Language Model Instruction Tuning To Generate Annotated Utterances
  For Intent Classification And Slot Tagging'
authors: Rosenbaum et al.
conference: IEEE Intelligent Systems
year: 2022
bibkey: rosenbaum2022linguist
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.09900'}]
tags: [Training Techniques, Prompting, Agentic, Fine Tuning, NEURIPS, Datasets]
---
We present LINGUIST, a method for generating annotated data for Intent
Classification and Slot Tagging (IC+ST), via fine-tuning AlexaTM 5B, a
5-billion-parameter multilingual sequence-to-sequence (seq2seq) model, on a
flexible instruction prompt. In a 10-shot novel intent setting for the SNIPS
dataset, LINGUIST surpasses state-of-the-art approaches (Back-Translation and
Example Extrapolation) by a wide margin, showing absolute improvement for the
target intents of +1.9 points on IC Recall and +2.5 points on ST F1 Score. In
the zero-shot cross-lingual setting of the mATIS++ dataset, LINGUIST
out-performs a strong baseline of Machine Translation with Slot Alignment by
+4.14 points absolute on ST F1 Score across 6 languages, while matching
performance on IC. Finally, we verify our results on an internal large-scale
multilingual dataset for conversational agent IC+ST and show significant
improvements over a baseline which uses Back-Translation, Paraphrasing and Slot
Catalog Resampling. To our knowledge, we are the first to demonstrate
instruction fine-tuning of a large-scale seq2seq model to control the outputs
of multilingual intent- and slot-labeled data generation.