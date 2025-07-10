---
layout: publication
title: Chatgpt Chemistry Assistant For Text Mining And Prediction Of MOF Synthesis
authors: Zhiling Zheng, Oufan Zhang, Christian Borgs, Jennifer T. Chayes, Omar M.
  Yaghi
conference: Journal of the American Chemical Society
year: 2023
citations: 255
bibkey: zheng2023chatgpt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.11296'}]
tags: [Tools, GPT, Prompting, Model Architecture]
---
We use prompt engineering to guide ChatGPT in the automation of text mining
of metal-organic frameworks (MOFs) synthesis conditions from diverse formats
and styles of the scientific literature. This effectively mitigates ChatGPT's
tendency to hallucinate information -- an issue that previously made the use of
Large Language Models (LLMs) in scientific fields challenging. Our approach
involves the development of a workflow implementing three different processes
for text mining, programmed by ChatGPT itself. All of them enable parsing,
searching, filtering, classification, summarization, and data unification with
different tradeoffs between labor, speed, and accuracy. We deploy this system
to extract 26,257 distinct synthesis parameters pertaining to approximately 800
MOFs sourced from peer-reviewed research articles. This process incorporates
our ChemPrompt Engineering strategy to instruct ChatGPT in text mining,
resulting in impressive precision, recall, and F1 scores of 90-99%.
Furthermore, with the dataset built by text mining, we constructed a
machine-learning model with over 86% accuracy in predicting MOF experimental
crystallization outcomes and preliminarily identifying important factors in MOF
crystallization. We also developed a reliable data-grounded MOF chatbot to
answer questions on chemical reactions and synthesis procedures. Given that the
process of using ChatGPT reliably mines and tabulates diverse MOF synthesis
information in a unified format, while using only narrative language requiring
no coding expertise, we anticipate that our ChatGPT Chemistry Assistant will be
very useful across various other chemistry sub-disciplines.