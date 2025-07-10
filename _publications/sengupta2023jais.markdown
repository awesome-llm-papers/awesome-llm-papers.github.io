---
layout: publication
title: 'Jais And Jais-chat: Arabic-centric Foundation And Instruction-tuned Open Generative
  Large Language Models'
authors: Neha Sengupta et al.
conference: Arxiv
year: 2023
citations: 15
bibkey: sengupta2023jais
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.16149'}, {name: Code,
    url: 'https://huggingface.co/inception-mbzuai/jais-13b-chat'}]
tags: [Responsible AI, Has Code, Model Architecture, GPT, Training Techniques, Evaluation]
---
We introduce Jais and Jais-chat, new state-of-the-art Arabic-centric
foundation and instruction-tuned open generative large language models (LLMs).
The models are based on the GPT-3 decoder-only architecture and are pretrained
on a mixture of Arabic and English texts, including source code in various
programming languages. With 13 billion parameters, they demonstrate better
knowledge and reasoning capabilities in Arabic than any existing open Arabic
and multilingual models by a sizable margin, based on extensive evaluation.
Moreover, the models are competitive in English compared to English-centric
open models of similar size, despite being trained on much less English data.
We provide a detailed description of the training, the tuning, the safety
alignment, and the evaluation of the models. We release two open versions of
the model -- the foundation Jais model, and an instruction-tuned Jais-chat
variant -- with the aim of promoting research on Arabic LLMs. Available at
https://huggingface.co/inception-mbzuai/jais-13b-chat