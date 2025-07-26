---
layout: publication
title: Evaluating Layers Of Representation In Neural Machine Translation On Part-of-speech
  And Semantic Tagging Tasks
authors: "Yonatan Belinkov, Llu\xEDs M\xE0rquez, Hassan Sajjad, Nadir Durrani, Fahim\
  \ Dalvi, James Glass"
conference: IJCNLP 8 (2017) volume 1 1-10
year: 2017
bibkey: belinkov2017evaluating
citations: 127
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1801.07772'}]
tags: ["Training Techniques"]
short_authors: Belinkov et al.
---
While neural machine translation (NMT) models provide improved translation
quality in an elegant, end-to-end framework, it is less clear what they learn
about language. Recent work has started evaluating the quality of vector
representations learned by NMT models on morphological and syntactic tasks. In
this paper, we investigate the representations learned at different layers of
NMT encoders. We train NMT systems on parallel data and use the trained models
to extract features for training a classifier on two tasks: part-of-speech and
semantic tagging. We then measure the performance of the classifier as a proxy
to the quality of the original NMT model for the given task. Our quantitative
analysis yields interesting insights regarding representation learning in NMT
models. For instance, we find that higher layers are better at learning
semantics while lower layers tend to be better for part-of-speech tagging. We
also observe little effect of the target language on source-side
representations, especially with higher quality NMT models.