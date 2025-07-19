---
layout: publication
title: Transformers Are Universal In-context Learners
authors: "Furuya Takashi, de Hoop Maarten V., Peyr\xE9 Gabriel"
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: furuya2024transformers
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.01367'}]
tags: [RAG, Attention Mechanism, Prompting, Transformer, Model Architecture, Applications,
  AAAI]
---
Transformers are deep architectures that define "in-context mappings" which
enable predicting new tokens based on a given set of tokens (such as a prompt
in NLP applications or a set of patches for a vision transformer). In this
work, we study in particular the ability of these architectures to handle an
arbitrarily large number of context tokens. To mathematically, uniformly
address their expressivity, we consider the case that the mappings are
conditioned on a context represented by a probability distribution of tokens
which becomes discrete for a finite number of these. The relevant notion of
smoothness then corresponds to continuity in terms of the Wasserstein distance
between these contexts. We demonstrate that deep transformers are universal and
can approximate continuous in-context mappings to arbitrary precision,
uniformly over compact token domains. A key aspect of our results, compared to
existing findings, is that for a fixed precision, a single transformer can
operate on an arbitrary (even infinite) number of tokens. Additionally, it
operates with a fixed embedding dimension of tokens (this dimension does not
increase with precision) and a fixed number of heads (proportional to the
dimension). The use of MLPs between multi-head attention layers is also
explicitly controlled. We consider both unmasked attentions (as used for the
vision transformer) and masked causal attentions (as used for NLP and time
series applications). We tackle the causal setting leveraging a space-time
lifting to analyze causal attention as a mapping over probability distributions
of tokens.