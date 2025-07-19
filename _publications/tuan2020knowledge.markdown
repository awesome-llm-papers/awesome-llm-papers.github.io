---
layout: publication
title: Knowledge Injection Into Dialogue Generation Via Language Models
authors: Tuan Yi-lin, Wei Wei, Wang William Yang
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: tuan2020knowledge
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14614'}]
tags: [EMNLP]
---
Dialogue generation has been successfully learned from scratch by neural
networks, but tends to produce the same general response, e.g., "what are you
talking about?", in many conversations. To reduce this homogeneity, external
knowledge such as the speaker's profile and domain knowledge is applied as an
additional condition to diversify a model's output. The required knowledge to
develop an effective conversation, however, is not always available, which is
different from prior work's assumption that a model always has acquired
sufficient knowledge before chatting. This problem can be detrimental when
applying a dialogue model like this chatting online with unconstrained people
and topics, because the model does not have the needed knowledge. To address
this problem, we propose InjK, which is a two-stage approach to inject
knowledge into a dialogue generation model. First, we train a large-scale
language model and query it as textual knowledge. Second, we frame a dialogue
generation model to sequentially generate textual knowledge and a corresponding
response. Empirically, when a dialogue generation model can only access limited
knowledge, our method outperforms prior work by producing more coherent and
informative responses.