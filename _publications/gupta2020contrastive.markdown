---
layout: publication
title: Contrastive Learning For Weakly Supervised Phrase Grounding
authors: Tanmay Gupta, Arash Vahdat, Gal Chechik, Xiaodong Yang, Jan Kautz, Derek
  Hoiem
conference: Lecture Notes in Computer Science
year: 2020
bibkey: gupta2020contrastive
citations: 114
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.09920'}]
tags: ["Evaluation", "Training Techniques"]
short_authors: Gupta et al.
---
Phrase grounding, the problem of associating image regions to caption words,
is a crucial component of vision-language tasks. We show that phrase grounding
can be learned by optimizing word-region attention to maximize a lower bound on
mutual information between images and caption words. Given pairs of images and
captions, we maximize compatibility of the attention-weighted regions and the
words in the corresponding caption, compared to non-corresponding pairs of
images and captions. A key idea is to construct effective negative captions for
learning through language model guided word substitutions. Training with our
negatives yields a \\(\sim10%\\) absolute gain in accuracy over randomly-sampled
negatives from the training data. Our weakly supervised phrase grounding model
trained on COCO-Captions shows a healthy gain of \\(5.7%\\) to achieve \\(76.7%\\)
accuracy on Flickr30K Entities benchmark.