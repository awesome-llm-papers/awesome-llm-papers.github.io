---
layout: publication
title: Generating Sentiment-preserving Fake Online Reviews Using Neural Language Models
  And Their Human- And Machine-based Detection
authors: David Ifeoluwa Adelani, Haotian Mai, Fuming Fang, Huy H. Nguyen, Junichi
  Yamagishi, Isao Echizen
conference: Advances in Intelligent Systems and Computing
year: 2020
bibkey: adelani2019generating
citations: 87
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.09177'}]
tags: ["Evaluation", "Model Architecture", "Training Techniques"]
short_authors: Adelani et al.
---
Advanced neural language models (NLMs) are widely used in sequence generation
tasks because they are able to produce fluent and meaningful sentences. They
can also be used to generate fake reviews, which can then be used to attack
online review systems and influence the buying decisions of online shoppers. To
perform such attacks, it is necessary for experts to train a tailored LM for a
specific topic. In this work, we show that a low-skilled threat model can be
built just by combining publicly available LMs and show that the produced fake
reviews can fool both humans and machines. In particular, we use the GPT-2 NLM
to generate a large number of high-quality reviews based on a review with the
desired sentiment and then using a BERT based text classifier (with accuracy of
96%) to filter out reviews with undesired sentiments. Because none of the words
in the review are modified, fluent samples like the training data can be
generated from the learned distribution. A subjective evaluation with 80
participants demonstrated that this simple method can produce reviews that are
as fluent as those written by people. It also showed that the participants
tended to distinguish fake reviews randomly. Three countermeasures, Grover,
GLTR, and OpenAI GPT-2 detector, were found to be difficult to accurately
detect fake review.