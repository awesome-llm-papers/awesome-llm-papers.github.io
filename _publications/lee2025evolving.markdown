---
layout: publication
title: Evolving Deeper LLM Thinking
authors: Kuang-huei Lee, Ian Fischer, Yueh-hua Wu, Dave Marwood, Shumeet Baluja, Dale
  Schuurmans, Xinyun Chen
conference: No Venue
year: 2025
bibkey: lee2025evolving
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.09891'}]
tags: []
short_authors: Lee et al.
---
We explore an evolutionary search strategy for scaling inference time compute in Large Language Models. The proposed approach, Mind Evolution, uses a language model to generate, recombine and refine candidate responses. The proposed approach avoids the need to formalize the underlying inference problem whenever a solution evaluator is available. Controlling for inference cost, we find that Mind Evolution significantly outperforms other inference strategies such as Best-of-N and Sequential Revision in natural language planning tasks. In the TravelPlanner and Natural Plan benchmarks, Mind Evolution solves more than 98% of the problem instances using Gemini 1.5 Pro without the use of a formal solver.

https://huggingface.co/discussions/paper/678dc333281a0e32feb5fc2c