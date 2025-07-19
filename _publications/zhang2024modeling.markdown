---
layout: publication
title: Modeling Domain And Feedback Transitions For Cross-domain Sequential Recommendation
authors: Zhang et al.
conference: Proceedings of the 31st ACM International Conference on Information &amp;
  Knowledge Management
year: 2024
bibkey: zhang2024modeling
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.08209'}]
tags: [Model Architecture, Transformer, Datasets, Reinforcement Learning, Attention
    Mechanism, CIKM]
---
Nowadays, many recommender systems encompass various domains to cater to
users' diverse needs, leading to user behaviors transitioning across different
domains. In fact, user behaviors across different domains reveal changes in
preference toward recommended items. For instance, a shift from negative
feedback to positive feedback indicates improved user satisfaction. However,
existing cross-domain sequential recommendation methods typically model user
interests by focusing solely on information about domain transitions, often
overlooking the valuable insights provided by users' feedback transitions. In
this paper, we propose \\(\text\{Transition\}^2\\), a novel method to model
transitions across both domains and types of user feedback. Specifically,
\\(\text\{Transition\}^2\\) introduces a transition-aware graph encoder based on user
history, assigning different weights to edges according to the feedback type.
This enables the graph encoder to extract historical embeddings that capture
the transition information between different domains and feedback types.
Subsequently, we encode the user history using a cross-transition multi-head
self-attention, incorporating various masks to distinguish different types of
transitions. To further enhance representation learning, we employ contrastive
losses to align transitions across domains and feedback types. Finally, we
integrate these modules to make predictions across different domains.
Experimental results on two public datasets demonstrate the effectiveness of
\\(\text\{Transition\}^2\\).