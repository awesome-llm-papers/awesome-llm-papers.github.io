---
layout: publication
title: 'Speechprompt: An Exploration Of Prompt Tuning On Generative Spoken Language
  Model For Speech Processing Tasks'
authors: Kai-wei Chang, Wei-cheng Tseng, Shang-wen Li, Hung-yi Lee
conference: Arxiv
year: 2022
citations: 24
bibkey: chang2022exploration
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.16773'}, {name: Code,
    url: 'https://github.com/ga642381/SpeechPrompt'}]
tags: [Training Techniques, RAG, Fine-Tuning, Efficiency and Optimization, Has Code,
  Prompting]
---
Speech representations learned from Self-supervised learning (SSL) models can
benefit various speech processing tasks. However, utilizing SSL representations
usually requires fine-tuning the pre-trained models or designing task-specific
downstream models and loss functions, causing much memory usage and human
labor. Recently, prompting in Natural Language Processing (NLP) has been found
to be an efficient technique to leverage pre-trained language models (LMs).
Specifically, prompt tuning optimizes a limited number of task-specific
parameters with a fixed pre-trained model; as a result, only a small set of
parameters is needed to be stored for each task. Prompt tuning improves
computation and memory efficiency by leveraging the pre-trained LM's prediction
ability. Nevertheless, such a paradigm is little studied in the speech
community. We report in this paper the first exploration of the prompt tuning
paradigm for speech processing tasks based on Generative Spoken Language Model
(GSLM). Experiment results show that the prompt tuning technique achieves
competitive performance in speech classification tasks with fewer trainable
parameters than fine-tuning specialized downstream models. We further study the
technique in challenging sequence generation tasks. Prompt tuning also
demonstrates its potential, while the limitation and possible research
directions are discussed in this paper. The source code is available on
https://github.com/ga642381/SpeechPrompt.