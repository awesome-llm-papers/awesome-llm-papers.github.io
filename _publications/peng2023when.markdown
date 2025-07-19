---
layout: publication
title: When Does In-context Learning Fall Short And Why? A Study On Specification-heavy
  Tasks
authors: Peng et al.
conference: The Journal of Chemical Physics
year: 2023
bibkey: peng2023when
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.08993'}]
tags: [Fine Tuning, Reinforcement Learning, Training Techniques, In Context Learning]
---
In-context learning (ICL) has become the default method for using large
language models (LLMs), making the exploration of its limitations and
understanding the underlying causes crucial. In this paper, we find that ICL
falls short of handling specification-heavy tasks, which are tasks with
complicated and extensive task specifications, requiring several hours for
ordinary humans to master, such as traditional information extraction tasks.
The performance of ICL on these tasks mostly cannot reach half of the
state-of-the-art results. To explore the reasons behind this failure, we
conduct comprehensive experiments on 18 specification-heavy tasks with various
LLMs and identify three primary reasons: inability to specifically understand
context, misalignment in task schema comprehension with humans, and inadequate
long-text understanding ability. Furthermore, we demonstrate that through
fine-tuning, LLMs can achieve decent performance on these tasks, indicating
that the failure of ICL is not an inherent flaw of LLMs, but rather a drawback
of existing alignment methods that renders LLMs incapable of handling
complicated specification-heavy tasks via ICL. To substantiate this, we perform
dedicated instruction tuning on LLMs for these tasks and observe a notable
improvement. We hope the analyses in this paper could facilitate advancements
in alignment methods enabling LLMs to meet more sophisticated human demands.