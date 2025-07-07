---
layout: publication
title: Multimodal Dialogue Response Generation
authors: Qingfeng Sun et al.
conference: Arxiv
year: 2021
citations: 20
bibkey: sun2021multimodal
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.08515'}]
tags: [Training Techniques, Agentic, Multimodal Models]
---
Responsing with image has been recognized as an important capability for an
intelligent conversational agent. Yet existing works only focus on exploring
the multimodal dialogue models which depend on retrieval-based methods, but
neglecting generation methods. To fill in the gaps, we first present a
multimodal dialogue generation model, which takes the dialogue history as
input, then generates a textual sequence or an image as response. Learning such
a model often requires multimodal dialogues containing both texts and images
which are difficult to obtain. Motivated by the challenge in practice, we
consider multimodal dialogue generation under a natural assumption that only
limited training examples are available. In such a low-resource setting, we
devise a novel conversational agent, Divter, in order to isolate parameters
that depend on multimodal dialogues from the entire generation model. By this
means, the major part of the model can be learned from a large number of
text-only dialogues and text-image pairs respectively, then the whole
parameters can be well fitted using the limited training examples. Extensive
experiments demonstrate our method achieves state-of-the-art results in both
automatic and human evaluation, and can generate informative text and
high-resolution image responses.