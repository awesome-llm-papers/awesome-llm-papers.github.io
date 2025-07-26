---
layout: publication
title: A Copy-augmented Sequence-to-sequence Architecture Gives Good Performance On
  Task-oriented Dialogue
authors: Mihail Eric, Christopher D. Manning
conference: 'Proceedings of the 15th Conference of the European Chapter of the Association
  for Computational Linguistics: Volume 2, Short Papers'
year: 2017
bibkey: eric2017copy
citations: 126
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1701.04024'}]
tags: ["Model Architecture"]
short_authors: Mihail Eric, Christopher D. Manning
---
Task-oriented dialogue focuses on conversational agents that participate in
user-initiated dialogues on domain-specific topics. In contrast to chatbots,
which simply seek to sustain open-ended meaningful discourse, existing
task-oriented agents usually explicitly model user intent and belief states.
This paper examines bypassing such an explicit representation by depending on a
latent neural embedding of state and learning selective attention to dialogue
history together with copying to incorporate relevant prior context. We
complement recent work by showing the effectiveness of simple
sequence-to-sequence neural architectures with a copy mechanism. Our model
outperforms more complex memory-augmented models by 7% in per-response
generation and is on par with the current state-of-the-art on DSTC2.