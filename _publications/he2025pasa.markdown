---
layout: publication
title: 'Pasa: An LLM Agent For Comprehensive Academic Paper Search'
authors: Yichen He, Guanhua Huang, Peiyuan Feng, Yuan Lin, Yuchen Zhang, Hang Li,
  Weinan E
conference: No Venue
year: 2025
bibkey: he2025pasa
additional_links: [{name: Code, url: 'https://github.com/bytedance/pasa'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/678dc284d4a7a158a8e5cf48'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2501.10120'}]
tags: ["Agentic", "Has Code", "Tools"]
short_authors: He et al.
---
We introduce PaSa, an advanced Paper Search agent powered by large language models. PaSa can autonomously make a series of decisions, including invoking search tools, reading papers, and selecting relevant references, to ultimately obtain comprehensive and accurate results for complex scholarly queries. We optimize PaSa using reinforcement learning with a synthetic dataset, AutoScholarQuery, which includes 35k fine-grained academic queries and corresponding papers sourced from top-tier AI conference publications. Additionally, we develop RealScholarQuery, a benchmark collecting real-world academic queries to assess PaSa performance in more realistic scenarios. Despite being trained on synthetic data, PaSa significantly outperforms existing baselines on RealScholarQuery, including Google, Google Scholar, Google with GPT-4 for paraphrased queries, chatGPT (search-enabled GPT-4o), GPT-o1, and PaSa-GPT-4o (PaSa implemented by prompting GPT-4o). Notably, PaSa-7B surpasses the best Google-based baseline, Google with GPT-4o, by 37.78% in recall@20 and 39.90% in recall@50. It also exceeds PaSa-GPT-4o by 30.36% in recall and 4.25% in precision. Model, datasets, and code are available at https://github.com/bytedance/pasa.

https://huggingface.co/discussions/paper/678dc284d4a7a158a8e5cf48