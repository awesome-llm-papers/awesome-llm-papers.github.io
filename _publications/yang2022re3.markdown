---
layout: publication
title: 'Re3: Generating Longer Stories With Recursive Reprompting And Revision'
authors: Yang et al.
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
bibkey: yang2022re3
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.06774'}]
tags: [Prompting, Tools, EMNLP]
---
We consider the problem of automatically generating longer stories of over
two thousand words. Compared to prior work on shorter stories, long-range plot
coherence and relevance are more central challenges here. We propose the
Recursive Reprompting and Revision framework (Re3) to address these challenges
by (a) prompting a general-purpose language model to construct a structured
overarching plan, and (b) generating story passages by repeatedly injecting
contextual information from both the plan and current story state into a
language model prompt. We then revise by (c) reranking different continuations
for plot coherence and premise relevance, and finally (d) editing the best
continuation for factual consistency. Compared to similar-length stories
generated directly from the same base model, human evaluators judged
substantially more of Re3's stories as having a coherent overarching plot (by
14% absolute increase), and relevant to the given initial premise (by 20%).