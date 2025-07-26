---
layout: publication
title: 'Factual Probing Is [MASK]: Learning Vs. Learning To Recall'
authors: Zexuan Zhong, Dan Friedman, Danqi Chen
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: zhong2021factual
citations: 216
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.05240'}]
tags: ["NAACL"]
short_authors: Zexuan Zhong, Dan Friedman, Danqi Chen
---
Petroni et al. (2019) demonstrated that it is possible to retrieve world
facts from a pre-trained language model by expressing them as cloze-style
prompts and interpret the model's prediction accuracy as a lower bound on the
amount of factual information it encodes. Subsequent work has attempted to
tighten the estimate by searching for better prompts, using a disjoint set of
facts as training data. In this work, we make two complementary contributions
to better understand these factual probing techniques. First, we propose
OptiPrompt, a novel and efficient method which directly optimizes in continuous
embedding space. We find this simple method is able to predict an additional
6.4% of facts in the LAMA benchmark. Second, we raise a more important
question: Can we really interpret these probing results as a lower bound? Is it
possible that these prompt-search methods learn from the training data too? We
find, somewhat surprisingly, that the training data used by these methods
contains certain regularities of the underlying fact distribution, and all the
existing prompt methods, including ours, are able to exploit them for better
fact prediction. We conduct a set of control experiments to disentangle
"learning" from "learning to recall", providing a more detailed picture of what
different prompts can reveal about pre-trained language models.