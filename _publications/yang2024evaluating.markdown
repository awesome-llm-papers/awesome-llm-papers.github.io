---
layout: publication
title: Evaluating And Aligning Codellms On Human Preference
authors: Jian Yang, Jiaxi Yang, Ke Jin, Yibo Miao, Lei Zhang, Liqun Yang, Zeyu Cui,
  Yichang Zhang, Binyuan Hui, Junyang Lin
conference: No Venue
year: 2024
bibkey: yang2024evaluating
additional_links: [{name: Code, url: 'https://codearenaeval.github.io/'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/6759183aa7adc43651b0d0ec'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2412.05210'}]
tags: ["Evaluation", "Fine-Tuning", "Has Code", "Llm For Code"]
short_authors: Yang et al.
---
Code large language models (codeLLMs) have made significant strides in code generation. Most previous code-related benchmarks, which consist of various programming exercises along with the corresponding test cases, are used as a common measure to evaluate the performance and capabilities of code LLMs. However, the current code LLMs focus on synthesizing the correct code snippet, ignoring the alignment with human preferences, where the query should be sampled from the practical application scenarios and the model-generated responses should satisfy the human preference. To bridge the gap between the model-generated response and human preference, we present a rigorous human-curated benchmark CodeArena to emulate the complexity and diversity of real-world coding tasks, where 397 high-quality samples spanning 40 categories and 44 programming languages, carefully curated from user queries. Further, we propose a diverse synthetic instruction corpus SynCode-Instruct (nearly 20B tokens) by scaling instructions from the website to verify the effectiveness of the large-scale synthetic instruction fine-tuning, where Qwen2.5-SynCoder totally trained on synthetic instruction data can achieve top-tier performance of open-source code LLMs. The results find performance differences between execution-based benchmarks and CodeArena. Our systematic experiments of CodeArena on 40+ LLMs reveal a notable performance gap between open SOTA code LLMs (e.g. Qwen2.5-Coder) and proprietary LLMs (e.g., OpenAI o1), underscoring the importance of the human preference alignment.https://codearenaeval.github.io/ 

https://huggingface.co/discussions/paper/6759183aa7adc43651b0d0ec