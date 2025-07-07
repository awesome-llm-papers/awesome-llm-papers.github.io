---
layout: publication
title: 'Mindmap: Knowledge Graph Prompting Sparks Graph Of Thoughts In Large Language
  Models'
authors: Yilin Wen, Zifeng Wang, Jimeng Sun
conference: Arxiv
year: 2023
citations: 31
bibkey: wen2023knowledge
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.09729'}, {name: Code,
    url: 'https://github.com/wyl-willing/MindMap'}]
tags: [Ethics and Bias, Merging, RAG, Tools, Has Code, Security, Prompting]
---
Large language models (LLMs) have achieved remarkable performance in natural
language understanding and generation tasks. However, they often suffer from
limitations such as difficulty in incorporating new knowledge, generating
hallucinations, and explaining their reasoning process. To address these
challenges, we propose a novel prompting pipeline, named \method, that
leverages knowledge graphs (KGs) to enhance LLMs' inference and transparency.
Our method enables LLMs to comprehend KG inputs and infer with a combination of
implicit and external knowledge. Moreover, our method elicits the mind map of
LLMs, which reveals their reasoning pathways based on the ontology of
knowledge. We evaluate our method on diverse question \& answering tasks,
especially in medical domains, and show significant improvements over
baselines. We also introduce a new hallucination evaluation benchmark and
analyze the effects of different components of our method. Our results
demonstrate the effectiveness and robustness of our method in merging knowledge
from LLMs and KGs for combined inference. To reproduce our results and extend
the framework further, we make our codebase available at
https://github.com/wyl-willing/MindMap.