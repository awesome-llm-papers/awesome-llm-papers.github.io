---
layout: publication
title: 'Biomedlm: A 2.7B Parameter Language Model Trained On Biomedical Text'
authors: Bolton et al.
conference: Bioinformatics
year: 2024
bibkey: bolton2024biomedlm
citations: 3737
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.18421'}]
tags: [Model Architecture, Applications, GPT]
---
Models such as GPT-4 and Med-PaLM 2 have demonstrated impressive performance
on a wide variety of biomedical NLP tasks. However, these models have hundreds
of billions of parameters, are computationally expensive to run, require users
to send their input data over the internet, and are trained on unknown data
sources. Can smaller, more targeted models compete? To address this question,
we build and release BioMedLM, a 2.7 billion parameter GPT-style autoregressive
model trained exclusively on PubMed abstracts and full articles. When
fine-tuned, BioMedLM can produce strong multiple-choice biomedical
question-answering results competitive with much larger models, such as
achieving a score of 57.3% on MedMCQA (dev) and 69.0% on the MMLU Medical
Genetics exam. BioMedLM can also be fine-tuned to produce useful answers to
patient questions on medical topics. This demonstrates that smaller models can
potentially serve as transparent, privacy-preserving, economical and
environmentally friendly foundations for particular NLP applications, such as
in biomedicine. The model is available on the Hugging Face Hub:
https://huggingface.co/stanford-crfm/BioMedLM.