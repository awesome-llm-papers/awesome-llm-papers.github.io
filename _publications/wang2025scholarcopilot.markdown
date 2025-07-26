---
layout: publication
title: 'Scholarcopilot: Training Large Language Models For Academic Writing With Accurate
  Citations'
authors: Yubo Wang, Xueguang Ma, Ping Nie, Huaye Zeng, Zhiheng Lyu, Yuxuan Zhang,
  Benjamin Schneider, Yi Lu, Xiang Yue, Wenhu Chen
conference: No Venue
year: 2025
bibkey: wang2025scholarcopilot
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.00824'}]
tags: ["Tools", "Training Techniques"]
short_authors: Wang et al.
---
Academic writing requires both coherent text generation and precise citation of relevant literature. Although recent Retrieval-Augmented Generation (RAG) systems have significantly improved factual accuracy in general-purpose text generation, their capacity to adequately support professional academic writing remains limited. In this work, we introduce ScholarCopilot, a unified framework designed to enhance existing large language models for generating professional academic articles with accurate and contextually relevant citations. ScholarCopilot dynamically determines when to retrieve scholarly references by generating a retrieval token [RET], and then utilizes its representation to look up relevant citations from a database. The retrieved references are fed into the model to augment the generation process. We jointly optimize both the generation and citation tasks within a single framework to increase efficiency. Trained on 500K papers from arXiv, our model achieves a top-1 retrieval accuracy of 40.1% on our evaluation dataset, outperforming baselines such as E5-Mistral-7B-Instruct (15.0%) and BM25 (9.8%). On a dataset of 1,000 academic writing samples, ScholarCopilot scores 16.2/25 in generation quality (measured across relevance, coherence, academic rigor, completeness, and innovation), surpassing models with 10x more parameters such as Qwen-2.5-72B-Instruct (15.8/25). Human studies also confirm ScholarCopilot's superior performance in citation recall, writing efficiency, and overall user experience, confirming the effectiveness of our approach.

https://huggingface.co/discussions/paper/67ede79e21d7e74ee3e2838c