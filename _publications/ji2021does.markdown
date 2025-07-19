---
layout: publication
title: Does The Magic Of BERT Apply To Medical Code Assignment? A Quantitative Study
authors: "Ji Shaoxiong, H\xF6ltt\xE4 Matti, Marttinen Pekka"
conference: Computers in Biology and Medicine
year: 2021
bibkey: ji2021does
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.06511'}]
tags: [Training Techniques, Attention Mechanism, BERT, Model Architecture, Fine Tuning]
---
Unsupervised pretraining is an integral part of many natural language
processing systems, and transfer learning with language models has achieved
remarkable results in many downstream tasks. In the clinical application of
medical code assignment, diagnosis and procedure codes are inferred from
lengthy clinical notes such as hospital discharge summaries. However, it is not
clear if pretrained models are useful for medical code prediction without
further architecture engineering. This paper conducts a comprehensive
quantitative analysis of various contextualized language models' performance,
pretrained in different domains, for medical code assignment from clinical
notes. We propose a hierarchical fine-tuning architecture to capture
interactions between distant words and adopt label-wise attention to exploit
label information. Contrary to current trends, we demonstrate that a carefully
trained classical CNN outperforms attention-based models on a MIMIC-III subset
with frequent codes. Our empirical findings suggest directions for improving
the medical code assignment application.