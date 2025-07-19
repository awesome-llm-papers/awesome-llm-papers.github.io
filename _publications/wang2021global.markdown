---
layout: publication
title: Global Context Enhanced Graph Neural Networks For Session-based Recommendation
authors: Wang et al.
conference: Proceedings of the 43rd International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2021
bibkey: wang2021global
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.05081'}]
tags: [Attention Mechanism, Evaluation, Transformer, Model Architecture, SIGIR, Datasets]
---
Session-based recommendation (SBR) is a challenging task, which aims at
recommending items based on anonymous behavior sequences. Almost all the
existing solutions for SBR model user preference only based on the current
session without exploiting the other sessions, which may contain both relevant
and irrelevant item-transitions to the current session. This paper proposes a
novel approach, called Global Context Enhanced Graph Neural Networks (GCE-GNN)
to exploit item transitions over all sessions in a more subtle manner for
better inferring the user preference of the current session. Specifically,
GCE-GNN learns two levels of item embeddings from session graph and global
graph, respectively: (i) Session graph, which is to learn the session-level
item embedding by modeling pairwise item-transitions within the current
session; and (ii) Global graph, which is to learn the global-level item
embedding by modeling pairwise item-transitions over all sessions. In GCE-GNN,
we propose a novel global-level item representation learning layer, which
employs a session-aware attention mechanism to recursively incorporate the
neighbors' embeddings of each node on the global graph. We also design a
session-level item representation learning layer, which employs a GNN on the
session graph to learn session-level item embeddings within the current
session. Moreover, GCE-GNN aggregates the learnt item representations in the
two levels with a soft attention mechanism. Experiments on three benchmark
datasets demonstrate that GCE-GNN outperforms the state-of-the-art methods
consistently.