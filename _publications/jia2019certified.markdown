---
layout: publication
title: Certified Robustness To Adversarial Word Substitutions
authors: "Robin Jia, Aditi Raghunathan, Kerem G\xF6ksel, Percy Liang"
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: jia2019certified
citations: 234
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.00986'}]
tags: ["EMNLP", "Security"]
short_authors: Jia et al.
---
State-of-the-art NLP models can often be fooled by adversaries that apply
seemingly innocuous label-preserving transformations (e.g., paraphrasing) to
input text. The number of possible transformations scales exponentially with
text length, so data augmentation cannot cover all transformations of an input.
This paper considers one exponentially large family of label-preserving
transformations, in which every word in the input can be replaced with a
similar word. We train the first models that are provably robust to all word
substitutions in this family. Our training procedure uses Interval Bound
Propagation (IBP) to minimize an upper bound on the worst-case loss that any
combination of word substitutions can induce. To evaluate models' robustness to
these transformations, we measure accuracy on adversarially chosen word
substitutions applied to test examples. Our IBP-trained models attain \\(75%\\)
adversarial accuracy on both sentiment analysis on IMDB and natural language
inference on SNLI. In comparison, on IMDB, models trained normally and ones
trained with data augmentation achieve adversarial accuracy of only \\(8%\\) and
\\(35%\\), respectively.