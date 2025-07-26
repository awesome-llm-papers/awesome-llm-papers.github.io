---
layout: publication
title: Rationalizing Neural Predictions
authors: Tao Lei, Regina Barzilay, Tommi Jaakkola
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: lei2016rationalizing
citations: 613
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.04155'}]
tags: ["EMNLP"]
short_authors: Tao Lei, Regina Barzilay, Tommi Jaakkola
---
Prediction without justification has limited applicability. As a remedy, we
learn to extract pieces of input text as justifications -- rationales -- that
are tailored to be short and coherent, yet sufficient for making the same
prediction. Our approach combines two modular components, generator and
encoder, which are trained to operate well together. The generator specifies a
distribution over text fragments as candidate rationales and these are passed
through the encoder for prediction. Rationales are never given during training.
Instead, the model is regularized by desiderata for rationales. We evaluate the
approach on multi-aspect sentiment analysis against manually annotated test
cases. Our approach outperforms attention-based baseline by a significant
margin. We also successfully illustrate the method on the question retrieval
task.