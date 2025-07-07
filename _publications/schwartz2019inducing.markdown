---
layout: publication
title: Inducing Brain-relevant Bias In Natural Language Processing Models
authors: Dan Schwartz, Mariya Toneva, Leila Wehbe
conference: Arxiv
year: 2019
citations: 22
bibkey: schwartz2019inducing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03268'}]
tags: [Ethics and Bias, Training Techniques, RAG, Fine-Tuning, BERT, Model Architecture]
---
Progress in natural language processing (NLP) models that estimate
representations of word sequences has recently been leveraged to improve the
understanding of language processing in the brain. However, these models have
not been specifically designed to capture the way the brain represents language
meaning. We hypothesize that fine-tuning these models to predict recordings of
brain activity of people reading text will lead to representations that encode
more brain-activity-relevant language information. We demonstrate that a
version of BERT, a recently introduced and powerful language model, can improve
the prediction of brain activity after fine-tuning. We show that the
relationship between language and brain activity learned by BERT during this
fine-tuning transfers across multiple participants. We also show that, for some
participants, the fine-tuned representations learned from both
magnetoencephalography (MEG) and functional magnetic resonance imaging (fMRI)
are better for predicting fMRI than the representations learned from fMRI
alone, indicating that the learned representations capture
brain-activity-relevant information that is not simply an artifact of the
modality. While changes to language representations help the model predict
brain activity, they also do not harm the model's ability to perform downstream
NLP tasks. Our findings are notable for research on language understanding in
the brain.