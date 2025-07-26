---
layout: publication
title: 'Reasoning Model Is Stubborn: Diagnosing Instruction Overriding In Reasoning
  Models'
authors: Doohyuk Jang, Yoonjeon Kim, Chanjae Park, Hyun Ryu, Eunho Yang
conference: No Venue
year: 2025
bibkey: jang2025reasoning
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.17225'}]
tags: ["Datasets"]
short_authors: Jang et al.
---
Large language models have demonstrated remarkable proficiency in long and complex reasoning tasks. However, they frequently exhibit a problematic reliance on familiar reasoning patterns, a phenomenon we term reasoning rigidity. Despite explicit instructions from users, these models often override clearly stated conditions and default to habitual reasoning trajectories, leading to incorrect conclusions. This behavior presents significant challenges, particularly in domains such as mathematics and logic puzzle, where precise adherence to specified constraints is critical. To systematically investigate reasoning rigidity, a behavior largely unexplored in prior work, we introduce a expert-curated diagnostic set, . Our dataset includes specially modified variants of existing mathematical benchmarks, namely AIME and MATH500, as well as well-known puzzles deliberately redesigned to require deviation from familiar reasoning strategies. Using this dataset, we identify recurring contamination patterns that occur when models default to ingrained reasoning. Specifically, we categorize this contamination into three distinctive modes: (i) Interpretation Overload, (ii) Input Distrust, and (iii) Partial Instruction Attention, each causing models to ignore or distort provided instructions. We publicly release our diagnostic set to facilitate future research on mitigating reasoning rigidity in language models.

https://huggingface.co/discussions/paper/6833c65e49b9e903d3ddbd6a