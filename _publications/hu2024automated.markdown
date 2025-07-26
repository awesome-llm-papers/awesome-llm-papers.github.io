---
layout: publication
title: Automated Design Of Agentic Systems
authors: Shengran Hu, Cong Lu, Jeff Clune
conference: No Venue
year: 2024
bibkey: hu2024automated
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66c2a6dc198f9d79f2096118'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2408.08435'}]
tags: ["Agentic"]
short_authors: Shengran Hu, Cong Lu, Jeff Clune
---
Researchers are investing substantial effort in developing powerful general-purpose agents, wherein Foundation Models are used as modules within agentic systems (e.g. Chain-of-Thought, Self-Reflection, Toolformer). However, the history of machine learning teaches us that hand-designed solutions are eventually replaced by learned solutions. We formulate a new research area, Automated Design of Agentic Systems (ADAS), which aims to automatically create powerful agentic system designs, including inventing novel building blocks and/or combining them in new ways. We further demonstrate that there is an unexplored yet promising approach within ADAS where agents can be defined in code and new agents can be automatically discovered by a meta agent programming ever better ones in code. Given that programming languages are Turing Complete, this approach theoretically enables the learning of any possible agentic system: including novel prompts, tool use, control flows, and combinations thereof. We present a simple yet effective algorithm named Meta Agent Search to demonstrate this idea, where a meta agent iteratively programs interesting new agents based on an ever-growing archive of previous discoveries. Through extensive experiments across multiple domains including coding, science, and math, we show that our algorithm can progressively invent agents with novel designs that greatly outperform state-of-the-art hand-designed agents. Importantly, we consistently observe the surprising result that agents invented by Meta Agent Search maintain superior performance even when transferred across domains and models, demonstrating their robustness and generality. Provided we develop it safely, our work illustrates the potential of an exciting new research direction toward automatically designing ever-more powerful agentic systems to benefit humanity.

https://huggingface.co/discussions/paper/66c2a6dc198f9d79f2096118