---
layout: publication
title: 'The Codeinverter Suite: Control-flow And Data-mapping Augmented Binary Decompilation
  With Llms'
authors: Liu et al.
conference: 'Software: Practice and Experience'
year: 2025
bibkey: liu2025codeinverter
citations: 119
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.07215'}]
tags: [RAG, Attention Mechanism, Prompting, Evaluation, Model Architecture, Security,
  Datasets, LLM For Code]
---
Binary decompilation plays a vital role in various cybersecurity and software engineering tasks. Recently, end-to-end decompilation methods powered by large language models (LLMs) have garnered significant attention due to their ability to generate highly readable source code with minimal human intervention. However, existing LLM-based approaches face several critical challenges, including limited capability in reconstructing code structure and logic, low accuracy in data recovery, concerns over data security and privacy, and high computational resource requirements. To address these issues, we develop the CodeInverter Suite, making three contributions: (1) the CodeInverter Workflow (CIW) is a novel prompt engineering workflow that incorporates control flow graphs (CFG) and explicit data mappings to improve LLM-based decompilation. (2) Using CIW on well-known source code datasets, we curate the CodeInverter Dataset (CID), a domain-specific dataset containing 8.69 million samples that contains CFGs and data mapping tables. (3) We train the CoderInverter Models (CIMs) on CID, generating two lightweight LLMs (with 1.3B and 6.7B parameters) intended for efficient inference in privacy-sensitive or resource-constrained environments. Extensive experiments on two benchmarks demonstrate that the CIW substantially enhances the performance of various LLMs across multiple metrics. Our CIM-6.7B can achieve state-of-the-art decompilation performance, outperforming existing LLMs even with over 100x more parameters in decompilation tasks, an average improvement of 11.03% in re-executability, 6.27% in edit similarity.