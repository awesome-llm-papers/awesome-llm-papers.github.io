---
layout: publication
title: Long-context Llms Struggle With Long In-context Learning
authors: Tianle Li, Ge Zhang, Quy Duc Do, Xiang Yue, Wenhu Chen
conference: No Venue
year: 2024
bibkey: li2024long
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.02060'}]
tags: ["In Context Learning", "Memory & Context"]
short_authors: Li et al.
---
Large Language Models (LLMs) have made significant strides in handling long sequences exceeding 32K tokens. However, their performance evaluation has largely been confined to metrics like perplexity and synthetic tasks, which may not fully capture their abilities in more nuanced, real-world scenarios. This study introduces a specialized benchmark (LIConBench) focusing on long in-context learning within the realm of extreme-label classification. We meticulously selected six datasets with a label range spanning 28 to 174 classes covering different input (few-shot demonstration) length from 2K to 50K. Our benchmark requires LLMs to comprehend the entire input to recognize the massive label spaces to make correct prediction. We evaluate 13 long-context LLMs on our benchmarks. We find that the long-context LLMs perform relatively well under the token length of 20K and the performance benefits from utilizing the long context window. However, after the context window exceeds 20K, most LLMs except GPT-4 will dip dramatically. This suggests a notable gap in current LLM capabilities for processing and understanding long, context-rich sequences. Further analysis revealed a tendency among models to favor predictions for labels presented towards the end at the sequence. Their ability to reason over multiple pieces in the long sequence is yet to be improved. Our study reveals that long context understanding and reasoning is still a challenging task for the existing LLMs. We believe LIConBench could serve as a more realistic evaluation for the future long context LLMs.

https://huggingface.co/discussions/paper/660cbbb67411be24fb6116d6