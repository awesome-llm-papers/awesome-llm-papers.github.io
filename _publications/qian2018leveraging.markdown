---
layout: publication
title: Leveraging Intra-user And Inter-user Representation Learning For Automated
  Hate Speech Detection
authors: Jing Qian, Mai Elsherief, Elizabeth M. Belding, William Yang Wang
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 2
  (Short Papers)'
year: 2018
bibkey: qian2018leveraging
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.03124'}]
tags: ["Model Architecture"]
short_authors: Qian et al.
---
Hate speech detection is a critical, yet challenging problem in Natural
Language Processing (NLP). Despite the existence of numerous studies dedicated
to the development of NLP hate speech detection approaches, the accuracy is
still poor. The central problem is that social media posts are short and noisy,
and most existing hate speech detection solutions take each post as an isolated
input instance, which is likely to yield high false positive and negative
rates. In this paper, we radically improve automated hate speech detection by
presenting a novel model that leverages intra-user and inter-user
representation learning for robust hate speech detection on Twitter. In
addition to the target Tweet, we collect and analyze the user's historical
posts to model intra-user Tweet representations. To suppress the noise in a
single Tweet, we also model the similar Tweets posted by all other users with
reinforced inter-user representation learning techniques. Experimentally, we
show that leveraging these two representations can significantly improve the
f-score of a strong bidirectional LSTM baseline model by 10.1%.