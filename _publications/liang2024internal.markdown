---
layout: publication
title: 'Internal Consistency And Self-feedback In Large Language Models: A Survey'
authors: Xun Liang, Shichao Song, Zifan Zheng, Hanyu Wang, Qingchen Yu, Xunkai Li,
  Rong-hua Li, Feiyu Xiong, Zhiyu Li
conference: No Venue
year: 2024
bibkey: liang2024internal
additional_links: [{name: Code, url: 'https://github.com/IAAR-Shanghai/ICSFSurvey'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/669dc5412dbf53ccd21d3938'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2407.14507'}]
tags: ["Survey Paper"]
short_authors: Liang et al.
---
Large language models (LLMs) are expected to respond accurately but often exhibit deficient reasoning or generate hallucinatory content. To address these, studies prefixed with ``Self-'' such as Self-Consistency, Self-Improve, and Self-Refine have been initiated. They share a commonality: involving LLMs evaluating and updating itself to mitigate the issues. Nonetheless, these efforts lack a unified perspective on summarization, as existing surveys predominantly focus on categorization without examining the motivations behind these works. In this paper, we summarize a theoretical framework, termed Internal Consistency, which offers unified explanations for phenomena such as the lack of reasoning and the presence of hallucinations. Internal Consistency assesses the coherence among LLMs' latent layer, decoding layer, and response layer based on sampling methodologies. Expanding upon the Internal Consistency framework, we introduce a streamlined yet effective theoretical framework capable of mining Internal Consistency, named Self-Feedback. The Self-Feedback framework consists of two modules: Self-Evaluation and Self-Update. This framework has been employed in numerous studies. We systematically classify these studies by tasks and lines of work; summarize relevant evaluation methods and benchmarks; and delve into the concern, ``Does Self-Feedback Really Work?'' We propose several critical viewpoints, including the ``Hourglass Evolution of Internal Consistency'', ``Consistency Is (Almost) Correctness'' hypothesis, and ``The Paradox of Latent and Explicit Reasoning''. Furthermore, we outline promising directions for future research. We have open-sourced the experimental code, reference list, and statistical data, available at https://github.com/IAAR-Shanghai/ICSFSurvey.

https://huggingface.co/discussions/paper/669dc5412dbf53ccd21d3938