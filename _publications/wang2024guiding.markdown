---
layout: publication
title: Guiding And Diversifying Llm-based Story Generation Via Answer Set Programming
authors: Wang Phoebe J., Kreminski Max
conference: Artificial Intelligence
year: 2024
bibkey: wang2024guiding
citations: 227
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.00554'}]
tags: [IJCAI, AISTATS, UAI, AAAI]
---
Instruction-tuned large language models (LLMs) are capable of generating
stories in response to open-ended user requests, but the resulting stories tend
to be limited in their diversity. Older, symbolic approaches to story
generation (such as planning) can generate substantially more diverse plot
outlines, but are limited to producing stories that recombine a fixed set of
hand-engineered character action templates. Can we combine the strengths of
these approaches while mitigating their weaknesses? We propose to do so by
using a higher-level and more abstract symbolic specification of high-level
story structure -- implemented via answer set programming (ASP) -- to guide and
diversify LLM-based story generation. Via semantic similarity analysis, we
demonstrate that our approach produces more diverse stories than an unguided
LLM, and via code excerpts, we demonstrate the improved compactness and
flexibility of ASP-based outline generation over full-fledged narrative
planning.