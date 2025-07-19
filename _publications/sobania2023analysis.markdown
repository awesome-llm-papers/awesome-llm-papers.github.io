---
layout: publication
title: An Analysis Of The Automatic Bug Fixing Performance Of Chatgpt
authors: Sobania et al.
conference: 2023 IEEE/ACM International Workshop on Automated Program Repair (APR)
year: 2023
bibkey: sobania2023analysis
citations: 218
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.08653'}]
tags: [Model Architecture, Evaluation, LLM For Code, LLM for Code, GPT, Datasets,
  Reinforcement Learning]
---
To support software developers in finding and fixing software bugs, several
automated program repair techniques have been introduced. Given a test suite,
standard methods usually either synthesize a repair, or navigate a search space
of software edits to find test-suite passing variants. Recent program repair
methods are based on deep learning approaches. One of these novel methods,
which is not primarily intended for automated program repair, but is still
suitable for it, is ChatGPT. The bug fixing performance of ChatGPT, however, is
so far unclear. Therefore, in this paper we evaluate ChatGPT on the standard
bug fixing benchmark set, QuixBugs, and compare the performance with the
results of several other approaches reported in the literature. We find that
ChatGPT's bug fixing performance is competitive to the common deep learning
approaches CoCoNut and Codex and notably better than the results reported for
the standard program repair approaches. In contrast to previous approaches,
ChatGPT offers a dialogue system through which further information, e.g., the
expected output for a certain input or an observed error message, can be
entered. By providing such hints to ChatGPT, its success rate can be further
increased, fixing 31 out of 40 bugs, outperforming state-of-the-art.