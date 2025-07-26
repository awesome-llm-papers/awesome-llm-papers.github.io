---
layout: publication
title: 'Baize: An Open-source Chat Model With Parameter-efficient Tuning On Self-chat
  Data'
authors: Canwen Xu, Daya Guo, Nan Duan, Julian Mcauley
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2023
bibkey: xu2023baize
citations: 70
additional_links: [{name: Code, url: 'https://github.com/project-baize/baize-chatbot'},
  {name: Paper, url: 'https://arxiv.org/abs/2304.01196'}]
tags: ["EMNLP", "Has Code", "Tools"]
short_authors: Xu et al.
---
Chat models, such as ChatGPT, have shown impressive capabilities and have
been rapidly adopted across numerous domains. However, these models are only
accessible through a restricted API, creating barriers for new research and
progress in the field. We propose a pipeline that can automatically generate a
high-quality multi-turn chat corpus by leveraging ChatGPT to engage in a
conversation with itself. Subsequently, we employ parameter-efficient tuning to
enhance LLaMA, an open-source large language model. The resulting model, named
Baize, demonstrates good performance in multi-turn dialogues with guardrails
that minimize potential risks. Furthermore, we propose a new technique called
Self-Distill with Feedback, to further improve the performance of the Baize
models with feedback from ChatGPT. The Baize models and data are released for
research purposes only at https://github.com/project-baize/baize-chatbot. An
online demo is also available at
https://huggingface.co/spaces/project-baize/chat-with-baize.