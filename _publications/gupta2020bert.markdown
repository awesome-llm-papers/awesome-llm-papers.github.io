---
layout: publication
title: BERT Based Multilingual Machine Comprehension In English And Hindi
authors: Somil Gupta, Nilesh Khade
conference: Arxiv
year: 2020
citations: 15
bibkey: gupta2020bert
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.01432'}]
tags: [Model Architecture, Fine-Tuning, Training Techniques, BERT, Evaluation]
---
Multilingual Machine Comprehension (MMC) is a Question-Answering (QA)
sub-task that involves quoting the answer for a question from a given snippet,
where the question and the snippet can be in different languages. Recently
released multilingual variant of BERT (m-BERT), pre-trained with 104 languages,
has performed well in both zero-shot and fine-tuned settings for multilingual
tasks; however, it has not been used for English-Hindi MMC yet. We, therefore,
present in this article, our experiments with m-BERT for MMC in zero-shot,
mono-lingual (e.g. Hindi Question-Hindi Snippet) and cross-lingual (e.g.
English QuestionHindi Snippet) fine-tune setups. These model variants are
evaluated on all possible multilingual settings and results are compared
against the current state-of-the-art sequential QA system for these languages.
Experiments show that m-BERT, with fine-tuning, improves performance on all
evaluation settings across both the datasets used by the prior model, therefore
establishing m-BERT based MMC as the new state-of-the-art for English and
Hindi. We also publish our results on an extended version of the recently
released XQuAD dataset, which we propose to use as the evaluation benchmark for
future research.