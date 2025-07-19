---
layout: publication
title: 'Noisy Text Data: Achilles'' Heel Of BERT'
authors: Kumar Ankit, Makhija Piyush, Gupta Anuj
conference: Proceedings of the Sixth Workshop on Noisy User-generated Text (W-NUT
  2020)
year: 2020
bibkey: kumar2020noisy
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.12932'}]
tags: [Training Techniques, Evaluation, BERT, Model Architecture, Applications, Fine
    Tuning, Datasets]
---
Owing to the phenomenal success of BERT on various NLP tasks and benchmark
datasets, industry practitioners are actively experimenting with fine-tuning
BERT to build NLP applications for solving industry use cases. For most
datasets that are used by practitioners to build industrial NLP applications,
it is hard to guarantee absence of any noise in the data. While BERT has
performed exceedingly well for transferring the learnings from one use case to
another, it remains unclear how BERT performs when fine-tuned on noisy text. In
this work, we explore the sensitivity of BERT to noise in the data. We work
with most commonly occurring noise (spelling mistakes, typos) and show that
this results in significant degradation in the performance of BERT. We present
experimental results to show that BERT's performance on fundamental NLP tasks
like sentiment analysis and textual similarity drops significantly in the
presence of (simulated) noise on benchmark datasets viz. IMDB Movie Review,
STS-B, SST-2. Further, we identify shortcomings in the existing BERT pipeline
that are responsible for this drop in performance. Our findings suggest that
practitioners need to be vary of presence of noise in their datasets while
fine-tuning BERT to solve industry use cases.