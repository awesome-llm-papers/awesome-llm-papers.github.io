---
layout: publication
title: Controllable Abstractive Dialogue Summarization With Sketch Supervision
authors: Chien-sheng Wu, Linqing Liu, Wenhao Liu, Pontus Stenetorp, Caiming Xiong
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: wu2021controllable
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.14064'}]
tags: ["AAAI", "Evaluation"]
short_authors: Wu et al.
---
In this paper, we aim to improve abstractive dialogue summarization quality
and, at the same time, enable granularity control. Our model has two primary
components and stages: 1) a two-stage generation strategy that generates a
preliminary summary sketch serving as the basis for the final summary. This
summary sketch provides a weakly supervised signal in the form of
pseudo-labeled interrogative pronoun categories and key phrases extracted using
a constituency parser. 2) A simple strategy to control the granularity of the
final summary, in that our model can automatically determine or control the
number of generated summary sentences for a given dialogue by predicting and
highlighting different text spans from the source text. Our model achieves
state-of-the-art performance on the largest dialogue summarization corpus
SAMSum, with as high as 50.79 in ROUGE-L score. In addition, we conduct a case
study and show competitive human evaluation results and controllability to
human-annotated summaries.