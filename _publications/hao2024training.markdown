---
layout: publication
title: Training Large Language Models To Reason In A Continuous Latent Space
authors: Hao et al.
conference: Computer Speech &amp; Language
year: 2024
bibkey: hao2024training
citations: 217
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.06769'}]
tags: [Alt, Training Techniques]
---
Large language models (LLMs) are restricted to reason in the "language
space", where they typically express the reasoning process with a
chain-of-thought (CoT) to solve a complex reasoning problem. However, we argue
that language space may not always be optimal for reasoning. For example, most
word tokens are primarily for textual coherence and not essential for
reasoning, while some critical tokens require complex planning and pose huge
challenges to LLMs. To explore the potential of LLM reasoning in an
unrestricted latent space instead of using natural language, we introduce a new
paradigm Coconut (Chain of Continuous Thought). We utilize the last hidden
state of the LLM as a representation of the reasoning state (termed "continuous
thought"). Rather than decoding this into a word token, we feed it back to the
LLM as the subsequent input embedding directly in the continuous space.
Experiments show that Coconut can effectively augment the LLM on several
reasoning tasks. This novel latent reasoning paradigm leads to emergent
advanced reasoning patterns: the continuous thought can encode multiple
alternative next reasoning steps, allowing the model to perform a breadth-first
search (BFS) to solve the problem, rather than prematurely committing to a
single deterministic path like CoT. Coconut outperforms CoT in certain logical
reasoning tasks that require substantial backtracking during planning, with
fewer thinking tokens during inference. These findings demonstrate the promise
of latent reasoning and offer valuable insights for future research.