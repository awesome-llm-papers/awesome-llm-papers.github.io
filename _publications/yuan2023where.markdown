---
layout: publication
title: Where To Go Next For Recommender Systems? ID- Vs. Modality-based Recommender
  Models Revisited
authors: Zheng Yuan, Fajie Yuan, Yu Song, Youhua Li, Junchen Fu, Fei Yang, Yunzhu
  Pan, Yongxin Ni
conference: Proceedings of the 46th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2023
bibkey: yuan2023where
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.13835'}]
tags: ["Applications", "Model Architecture", "SIGIR"]
short_authors: Yuan et al.
---
Recommendation models that utilize unique identities (IDs) to represent
distinct users and items have been state-of-the-art (SOTA) and dominated the
recommender systems (RS) literature for over a decade. Meanwhile, the
pre-trained modality encoders, such as BERT and ViT, have become increasingly
powerful in modeling the raw modality features of an item, such as text and
images. Given this, a natural question arises: can a purely modality-based
recommendation model (MoRec) outperforms or matches a pure ID-based model
(IDRec) by replacing the itemID embedding with a SOTA modality encoder? In
fact, this question was answered ten years ago when IDRec beats MoRec by a
strong margin in both recommendation accuracy and efficiency. We aim to revisit
this `old' question and systematically study MoRec from several aspects.
Specifically, we study several sub-questions: (i) which recommendation
paradigm, MoRec or IDRec, performs better in practical scenarios, especially in
the general setting and warm item scenarios where IDRec has a strong advantage?
does this hold for items with different modality features? (ii) can the latest
technical advances from other communities (i.e., natural language processing
and computer vision) translate into accuracy improvement for MoRec? (iii) how
to effectively utilize item modality representation, can we use it directly or
do we have to adjust it with new data? (iv) are there some key challenges for
MoRec to be solved in practical applications? To answer them, we conduct
rigorous experiments for item recommendations with two popular modalities,
i.e., text and vision. We provide the first empirical evidence that MoRec is
already comparable to its IDRec counterpart with an expensive end-to-end
training method, even for warm item recommendation. Our results potentially
imply that the dominance of IDRec in the RS field may be greatly challenged in
the future.