---
layout: publication
title: Stance Detection With Bidirectional Conditional Encoding
authors: Augenstein et al.
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: augenstein2016stance
citations: 348
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.05464'}]
tags: [Datasets, Model Architecture, Training Techniques, EMNLP]
---
Stance detection is the task of classifying the attitude expressed in a text
towards a target such as Hillary Clinton to be "positive", negative" or
"neutral". Previous work has assumed that either the target is mentioned in the
text or that training data for every target is given. This paper considers the
more challenging version of this task, where targets are not always mentioned
and no training data is available for the test targets. We experiment with
conditional LSTM encoding, which builds a representation of the tweet that is
dependent on the target, and demonstrate that it outperforms encoding the tweet
and the target independently. Performance is improved further when the
conditional model is augmented with bidirectional encoding. We evaluate our
approach on the SemEval 2016 Task 6 Twitter Stance Detection corpus achieving
performance second best only to a system trained on semi-automatically labelled
tweets for the test target. When such weak supervision is added, our approach
achieves state-of-the-art results.