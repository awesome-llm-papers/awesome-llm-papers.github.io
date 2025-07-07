---
layout: publication
title: Learning Rich Representation Of Keyphrases From Text
authors: Mayank Kulkarni, Debanjan Mahata, Ravneet Arora, Rajarshi Bhowmik
conference: Arxiv
year: 2021
citations: 26
bibkey: kulkarni2021learning
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.08547'}]
tags: [Pre-Training, Training Techniques, Transformer, Model Architecture]
---
In this work, we explore how to train task-specific language models aimed
towards learning rich representation of keyphrases from text documents. We
experiment with different masking strategies for pre-training transformer
language models (LMs) in discriminative as well as generative settings. In the
discriminative setting, we introduce a new pre-training objective - Keyphrase
Boundary Infilling with Replacement (KBIR), showing large gains in performance
(upto 8.16 points in F1) over SOTA, when the LM pre-trained using KBIR is
fine-tuned for the task of keyphrase extraction. In the generative setting, we
introduce a new pre-training setup for BART - KeyBART, that reproduces the
keyphrases related to the input text in the CatSeq format, instead of the
denoised original input. This also led to gains in performance (upto 4.33
points in F1@M) over SOTA for keyphrase generation. Additionally, we also
fine-tune the pre-trained language models on named entity recognition (NER),
question answering (QA), relation extraction (RE), abstractive summarization
and achieve comparable performance with that of the SOTA, showing that learning
rich representation of keyphrases is indeed beneficial for many other
fundamental NLP tasks.