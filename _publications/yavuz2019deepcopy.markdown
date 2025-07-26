---
layout: publication
title: 'Deepcopy: Grounded Response Generation With Hierarchical Pointer Networks'
authors: Semih Yavuz, Abhinav Rastogi, Guan-lin Chao, Dilek Hakkani-tur
conference: Proceedings of the 20th Annual SIGdial Meeting on Discourse and Dialogue
year: 2019
bibkey: yavuz2019deepcopy
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.10731'}]
tags: ["Dialogue & Multi Turn"]
short_authors: Yavuz et al.
---
Recent advances in neural sequence-to-sequence models have led to promising
results for several language generation-based tasks, including dialogue
response generation, summarization, and machine translation. However, these
models are known to have several problems, especially in the context of
chit-chat based dialogue systems: they tend to generate short and dull
responses that are often too generic. Furthermore, these models do not ground
conversational responses on knowledge and facts, resulting in turns that are
not accurate, informative and engaging for the users. In this paper, we propose
and experiment with a series of response generation models that aim to serve in
the general scenario where in addition to the dialogue context, relevant
unstructured external knowledge in the form of text is also assumed to be
available for models to harness. Our proposed approach extends
pointer-generator networks (See et al., 2017) by allowing the decoder to
hierarchically attend and copy from external knowledge in addition to the
dialogue context. We empirically show the effectiveness of the proposed model
compared to several baselines including (Ghazvininejad et al., 2018; Zhang et
al., 2018) through both automatic evaluation metrics and human evaluation on
CONVAI2 dataset.