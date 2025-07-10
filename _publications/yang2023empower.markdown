---
layout: publication
title: Empower Large Language Model To Perform Better On Industrial Domain-specific
  Question Answering
authors: Fangkai Yang et al.
conference: 'Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing: Industry Track'
year: 2023
citations: 15
bibkey: yang2023empower
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.11541'}, {name: Code,
    url: 'https://aka.ms/Microsoft_QA'}]
tags: [Has Code, Model Architecture, Attention Mechanism, RAG, Evaluation]
---
Large Language Model (LLM) has gained popularity and achieved remarkable
results in open-domain tasks, but its performance in real industrial
domain-specific scenarios is average due to its lack of specific domain
knowledge. This issue has attracted widespread attention, but there are few
relevant benchmarks available. In this paper, we provide a benchmark Question
Answering (QA) dataset named MSQA, centered around Microsoft products and IT
technical problems encountered by customers. This dataset contains industry
cloud-specific QA knowledge, an area not extensively covered in general LLMs,
making it well-suited for evaluating methods aiming to enhance LLMs'
domain-specific capabilities. In addition, we propose a new model interaction
paradigm that can empower LLM to achieve better performance on domain-specific
tasks where it is not proficient. Extensive experiments demonstrate that the
approach following our method outperforms the commonly used LLM with retrieval
methods. We make our source code and sample data available at:
https://aka.ms/Microsoft_QA.