---
layout: publication
title: In-context Learning And Induction Heads
authors: Catherine Olsson et al.
conference: Arxiv
year: 2022
citations: 57
bibkey: olsson2022learning
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.11895'}]
tags: [Model Architecture, Attention Mechanism, Transformer, In-Context Learning,
  Training Techniques]
---
"Induction heads" are attention heads that implement a simple algorithm to
complete token sequences like [A][B] ... [A] -> [B]. In this work, we present
preliminary and indirect evidence for a hypothesis that induction heads might
constitute the mechanism for the majority of all "in-context learning" in large
transformer models (i.e. decreasing loss at increasing token indices). We find
that induction heads develop at precisely the same point as a sudden sharp
increase in in-context learning ability, visible as a bump in the training
loss. We present six complementary lines of evidence, arguing that induction
heads may be the mechanistic source of general in-context learning in
transformer models of any size. For small attention-only models, we present
strong, causal evidence; for larger models with MLPs, we present correlational
evidence.