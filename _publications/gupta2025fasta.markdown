---
layout: publication
title: 'Fasta^*: Fast-slow Toolpath Agent With Subroutine Mining For Efficient Multi-turn
  Image Editing'
authors: Advait Gupta, Rishie Raj, Dang Nguyen, Tianyi Zhou
conference: No Venue
year: 2025
bibkey: gupta2025fasta
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.20911'}]
tags: ["Agentic", "Tools"]
short_authors: Gupta et al.
---
We develop a cost-efficient neurosymbolic agent to address challenging multi-turn image editing tasks such as "Detect the bench in the image while recoloring it to pink. Also, remove the cat for a clearer view and recolor the wall to yellow.'' It combines the fast, high-level subtask planning by large language models (LLMs) with the slow, accurate, tool-use, and local A^* search per subtask to find a cost-efficient toolpath -- a sequence of calls to AI tools. To save the cost of A^* on similar subtasks, we perform inductive reasoning on previously successful toolpaths via LLMs to continuously extract/refine frequently used subroutines and reuse them as new tools for future tasks in an adaptive fast-slow planning, where the higher-level subroutines are explored first, and only when they fail, the low-level A^* search is activated. The reusable symbolic subroutines considerably save exploration cost on the same types of subtasks applied to similar images, yielding a human-like fast-slow toolpath agent "FaSTA^*'': fast subtask planning followed by rule-based subroutine selection per subtask is attempted by LLMs at first, which is expected to cover most tasks, while slow A^* search is only triggered for novel and challenging subtasks. By comparing with recent image editing approaches, we demonstrate FaSTA^* is significantly more computationally efficient while remaining competitive with the state-of-the-art baseline in terms of success rate.

https://huggingface.co/discussions/paper/685e151d71131fa43be08b02