---
layout: publication
title: 'ACUTE-EVAL: Improved Dialogue Evaluation With Optimized Questions And Multi-turn
  Comparisons'
authors: Margaret Li, Jason Weston, Stephen Roller
conference: Arxiv
year: 2019
bibkey: li2019acute
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.03087'}]
tags: ["Evaluation"]
short_authors: Margaret Li, Jason Weston, Stephen Roller
---
While dialogue remains an important end-goal of natural language research,
the difficulty of evaluation is an oft-quoted reason why it remains troublesome
to make real progress towards its solution. Evaluation difficulties are
actually two-fold: not only do automatic metrics not correlate well with human
judgments, but also human judgments themselves are in fact difficult to
measure. The two most used human judgment tests, single-turn pairwise
evaluation and multi-turn Likert scores, both have serious flaws as we discuss
in this work.
  We instead provide a novel procedure involving comparing two full dialogues,
where a human judge is asked to pay attention to only one speaker within each,
and make a pairwise judgment. The questions themselves are optimized to
maximize the robustness of judgments across different annotators, resulting in
better tests. We also show how these tests work in self-play model chat setups,
resulting in faster, cheaper tests. We hope these tests become the de facto
standard, and will release open-source code to that end.