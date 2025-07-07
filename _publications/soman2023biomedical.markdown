---
layout: publication
title: Biomedical Knowledge Graph-optimized Prompt Generation For Large Language Models
authors: Karthik Soman et al.
conference: Arxiv
year: 2023
citations: 20
bibkey: soman2023biomedical
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.17330'}]
tags: [Training Techniques, GPT, RAG, Pre-Training, Tools, Fine-Tuning, Efficiency
    and Optimization, Prompting, Pruning, Model Architecture]
---
Large Language Models (LLMs) are being adopted at an unprecedented rate, yet
still face challenges in knowledge-intensive domains like biomedicine.
Solutions such as pre-training and domain-specific fine-tuning add substantial
computational overhead, requiring further domain expertise. Here, we introduce
a token-optimized and robust Knowledge Graph-based Retrieval Augmented
Generation (KG-RAG) framework by leveraging a massive biomedical KG (SPOKE)
with LLMs such as Llama-2-13b, GPT-3.5-Turbo and GPT-4, to generate meaningful
biomedical text rooted in established knowledge. Compared to the existing RAG
technique for Knowledge Graphs, the proposed method utilizes minimal graph
schema for context extraction and uses embedding methods for context pruning.
This optimization in context extraction results in more than 50% reduction in
token consumption without compromising the accuracy, making a cost-effective
and robust RAG implementation on proprietary LLMs. KG-RAG consistently enhanced
the performance of LLMs across diverse biomedical prompts by generating
responses rooted in established knowledge, accompanied by accurate provenance
and statistical evidence (if available) to substantiate the claims. Further
benchmarking on human curated datasets, such as biomedical true/false and
multiple-choice questions (MCQ), showed a remarkable 71% boost in the
performance of the Llama-2 model on the challenging MCQ dataset, demonstrating
the framework's capacity to empower open-source models with fewer parameters
for domain specific questions. Furthermore, KG-RAG enhanced the performance of
proprietary GPT models, such as GPT-3.5 and GPT-4. In summary, the proposed
framework combines explicit and implicit knowledge of KG and LLM in a token
optimized fashion, thus enhancing the adaptability of general-purpose LLMs to
tackle domain-specific questions in a cost-effective fashion.