---
layout: publication
title: Tool Documentation Enables Zero-shot Tool-usage With Large Language Models
authors: Hsieh et al.
conference: Proceedings of the 32nd ACM International Conference on Information and
  Knowledge Management
year: 2023
bibkey: hsieh2023tool
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.00675'}]
tags: [Alt, Prompting, Tools, Evaluation, Ethics And Bias, Few Shot, CIKM, Applications,
  Datasets, Merging]
---
Today, large language models (LLMs) are taught to use new tools by providing
a few demonstrations of the tool's usage. Unfortunately, demonstrations are
hard to acquire, and can result in undesirable biased usage if the wrong
demonstration is chosen. Even in the rare scenario that demonstrations are
readily available, there is no principled selection protocol to determine how
many and which ones to provide. As tasks grow more complex, the selection
search grows combinatorially and invariably becomes intractable. Our work
provides an alternative to demonstrations: tool documentation. We advocate the
use of tool documentation, descriptions for the individual tool usage, over
demonstrations. We substantiate our claim through three main empirical findings
on 6 tasks across both vision and language modalities. First, on existing
benchmarks, zero-shot prompts with only tool documentation are sufficient for
eliciting proper tool usage, achieving performance on par with few-shot
prompts. Second, on a newly collected realistic tool-use dataset with hundreds
of available tool APIs, we show that tool documentation is significantly more
valuable than demonstrations, with zero-shot documentation significantly
outperforming few-shot without documentation. Third, we highlight the benefits
of tool documentations by tackling image generation and video tracking using
just-released unseen state-of-the-art models as tools. Finally, we highlight
the possibility of using tool documentation to automatically enable new
applications: by using nothing more than the documentation of GroundingDino,
Stable Diffusion, XMem, and SAM, LLMs can re-invent the functionalities of the
just-released Grounded-SAM and Track Anything models.