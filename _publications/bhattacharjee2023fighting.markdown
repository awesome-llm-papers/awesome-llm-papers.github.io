---
layout: publication
title: 'Fighting Fire With Fire: Can Chatgpt Detect Ai-generated Text?'
authors: Amrita Bhattacharjee, Huan Liu
conference: Arxiv
year: 2023
citations: 27
bibkey: bhattacharjee2023fighting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.01284'}, {name: Code,
    url: 'https://github.com/AmritaBh/ChatGPT-as-Detector'}]
tags: [GPT, RAG, Has Code, Applications, Model Architecture]
---
Large language models (LLMs) such as ChatGPT are increasingly being used for
various use cases, including text content generation at scale. Although
detection methods for such AI-generated text exist already, we investigate
ChatGPT's performance as a detector on such AI-generated text, inspired by
works that use ChatGPT as a data labeler or annotator. We evaluate the
zero-shot performance of ChatGPT in the task of human-written vs. AI-generated
text detection, and perform experiments on publicly available datasets. We
empirically investigate if ChatGPT is symmetrically effective in detecting
AI-generated or human-written text. Our findings provide insight on how ChatGPT
and similar LLMs may be leveraged in automated detection pipelines by simply
focusing on solving a specific aspect of the problem and deriving the rest from
that solution. All code and data is available at
https://github.com/AmritaBh/ChatGPT-as-Detector.