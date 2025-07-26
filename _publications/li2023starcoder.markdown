---
layout: publication
title: 'Starcoder: May The Source Be With You!'
authors: "Raymond Li, Loubna Ben Allal, Yangtian Zi, Niklas Muennighoff, Denis Kocetkov,\
  \ Chenghao Mou, Marc Marone, Christopher Akiki, Jia Li, Jenny Chim, Qian Liu, Evgenii\
  \ Zheltonozhskii, Terry Yue Zhuo, Thomas Wang, Olivier Dehaene, Mishig Davaadorj,\
  \ Joel Lamy-poirier, Jo\xE3o Monteiro, Oleh Shliazhko, Nicolas Gontier, Nicholas\
  \ Meade, Armel Zebaze, Ming-ho Yee, Logesh Kumar Umapathi, Jian Zhu, Benjamin Lipkin,\
  \ Muhtasham Oblokulov, Zhiruo Wang, Rudra Murthy, Jason Stillerman, Siva Sankalp\
  \ Patel, Dmitry Abulkhanov, Marco Zocca, Manan Dey, Zhihan Zhang, Nour Fahmy, Urvashi\
  \ Bhattacharyya, Wenhao Yu, Swayam Singh, Sasha Luccioni, Paulo Villegas, Maxim\
  \ Kunakov, Fedor Zhdanov, Manuel Romero, Tony Lee, Nadav Timor, Jennifer Ding, Claire\
  \ Schlesinger, Hailey Schoelkopf, Jan Ebert, Tri Dao, Mayank Mishra, Alex Gu, Jennifer\
  \ Robinson, Carolyn Jane Anderson, Brendan Dolan-gavitt, Danish Contractor, Siva\
  \ Reddy, Daniel Fried, Dzmitry Bahdanau, Yacine Jernite, Carlos Mu\xF1oz Ferrandis,\
  \ Sean Hughes, Thomas Wolf, Arjun Guha, Leandro von Werra, Harm de Vries"
conference: No Venue
year: 2023
bibkey: li2023starcoder
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/645c4c147848314a460d179f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2305.06161'}]
tags: ["Ethics & Fairness", "Evaluation", "Has Code", "Memory & Context", "Privacy", "Tools"]
short_authors: Li et al.
---
The BigCode community, an open-scientific collaboration working on the responsible development of Large Language Models for Code (Code LLMs), introduces StarCoder and StarCoderBase: 15.5B parameter models with 8K context length, infilling capabilities and fast large-batch inference enabled by multi-query attention. StarCoderBase is trained on 1 trillion tokens sourced from The Stack, a large collection of permissively licensed GitHub repositories with inspection tools and an opt-out process. We fine-tuned StarCoderBase on 35B Python tokens, resulting in the creation of StarCoder. We perform the most comprehensive evaluation of Code LLMs to date and show that StarCoderBase outperforms every open Code LLM that supports multiple programming languages and matches or outperforms the OpenAI code-cushman-001 model. Furthermore, StarCoder outperforms every model that is fine-tuned on Python, can be prompted to achieve 40% pass@1 on HumanEval, and still retains its performance on other programming languages. We take several important steps towards a safe open-access model release, including an improved PII redaction pipeline and a novel attribution tracing tool, and make the StarCoder models publicly available under a more commercially viable version of the Open Responsible AI Model license.

https://huggingface.co/discussions/paper/645c4c147848314a460d179f