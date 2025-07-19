---
layout: publication
title: Predict And Use Latent Patterns For Short-text Conversation
authors: Chen et al.
conference: 'Proceedings of the 53rd Annual Meeting of the Association for Computational
  Linguistics and the 7th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2020
bibkey: chen2020predict
citations: 391
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.13982'}]
tags: [ACL]
---
Many neural network models nowadays have achieved promising performances in
Chit-chat settings. The majority of them rely on an encoder for understanding
the post and a decoder for generating the response. Without given assigned
semantics, the models lack the fine-grained control over responses as the
semantic mapping between posts and responses is hidden on the fly within the
end-to-end manners. Some previous works utilize sampled latent words as a
controllable semantic form to drive the generated response around the work, but
few works attempt to use more complex semantic patterns to guide the
generation. In this paper, we propose to use more detailed semantic forms,
including latent responses and part-of-speech sequences sampled from the
corresponding distributions, as the controllable semantics to guide the
generation. Our results show that the richer semantics are not only able to
provide informative and diverse responses, but also increase the overall
performance of response quality, including fluency and coherence.