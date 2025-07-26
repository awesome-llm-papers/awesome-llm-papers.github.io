---
layout: publication
title: 'Design2code: How Far Are We From Automating Front-end Engineering?'
authors: Chenglei Si, Yanzhe Zhang, Zhengyuan Yang, Ruibo Liu, Diyi Yang
conference: No Venue
year: 2024
bibkey: si2024design2code
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65e7d100767bfc7d10ba6d84'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2403.03163'}]
tags: ["Datasets", "Evaluation", "Llm For Code", "Model Architecture", "Prompting"]
short_authors: Si et al.
---
Generative AI has made rapid advancements in recent years, achieving unprecedented capabilities in multimodal understanding and code generation. This can enable a new paradigm of front-end development, in which multimodal LLMs might directly convert visual designs into code implementations. In this work, we formalize this as a Design2Code task and conduct comprehensive benchmarking. Specifically, we manually curate a benchmark of 484 diverse real-world webpages as test cases and develop a set of automatic evaluation metrics to assess how well current multimodal LLMs can generate the code implementations that directly render into the given reference webpages, given the screenshots as input. We also complement automatic metrics with comprehensive human evaluations. We develop a suite of multimodal prompting methods and show their effectiveness on GPT-4V and Gemini Pro Vision. We further finetune an open-source Design2Code-18B model that successfully matches the performance of Gemini Pro Vision. Both human evaluation and automatic metrics show that GPT-4V performs the best on this task compared to other models. Moreover, annotators think GPT-4V generated webpages can replace the original reference webpages in 49% of cases in terms of visual appearance and content; and perhaps surprisingly, in 64% of cases GPT-4V generated webpages are considered better than the original reference webpages. Our fine-grained break-down metrics indicate that open-source models mostly lag in recalling visual elements from the input webpages and in generating correct layout designs, while aspects like text content and coloring can be drastically improved with proper finetuning.

https://huggingface.co/discussions/paper/65e7d100767bfc7d10ba6d84