---
layout: publication
title: 'A Preliminary Study Of O1 In Medicine: Are We Closer To An AI Doctor?'
authors: Yunfei Xie, Juncheng Wu, Haoqin Tu, Siwei Yang, Bingchen Zhao, Yongshuo Zong,
  Qiao Jin, Cihang Xie, Yuyin Zhou
conference: No Venue
year: 2024
bibkey: xie2024preliminary
additional_links: [{name: Code, url: 'https://ucsc-vlaa.github.io/o1_medicine/'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/66f22c153a6d90d35ef1acb5'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2409.15277'}]
tags: ["Datasets", "Evaluation", "Has Code", "Model Architecture", "Prompting", "Reinforcement Learning"]
short_authors: Xie et al.
---
Large language models (LLMs) have exhibited remarkable capabilities across various domains and tasks, pushing the boundaries of our knowledge in learning and cognition. The latest model, OpenAI's o1, stands out as the first LLM with an internalized chain-of-thought technique using reinforcement learning strategies. While it has demonstrated surprisingly strong capabilities on various general language tasks, its performance in specialized fields such as medicine remains unknown. To this end, this report provides a comprehensive exploration of o1 on different medical scenarios, examining 3 key aspects: understanding, reasoning, and multilinguality. Specifically, our evaluation encompasses 6 tasks using data from 37 medical datasets, including two newly constructed and more challenging question-answering (QA) tasks based on professional medical quizzes from the New England Journal of Medicine (NEJM) and The Lancet. These datasets offer greater clinical relevance compared to standard medical QA benchmarks such as MedQA, translating more effectively into real-world clinical utility. Our analysis of o1 suggests that the enhanced reasoning ability of LLMs may (significantly) benefit their capability to understand various medical instructions and reason through complex clinical scenarios. Notably, o1 surpasses the previous GPT-4 in accuracy by an average of 6.2% and 6.6% across 19 datasets and two newly created complex QA scenarios. But meanwhile, we identify several weaknesses in both the model capability and the existing evaluation protocols, including hallucination, inconsistent multilingual ability, and discrepant metrics for evaluation. We release our raw data and model outputs at https://ucsc-vlaa.github.io/o1_medicine/ for future research.

https://huggingface.co/discussions/paper/66f22c153a6d90d35ef1acb5