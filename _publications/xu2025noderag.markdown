---
layout: publication
title: 'Noderag: Structuring Graph-based RAG With Heterogeneous Nodes'
authors: Tianyang Xu, Haojie Zheng, Chengze Li, Haoxiang Chen, Yixin Liu, Ruoxi Chen,
  Lichao Sun
conference: No Venue
year: 2025
bibkey: xu2025noderag
additional_links: [{name: Code, url: 'https://github.com/Terry-Xu-666/NodeRAG'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/6804caa0d8538baa1c39cac2'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.11544'}]
tags: ["Has Code", "RAG", "Tools"]
short_authors: Xu et al.
---
Retrieval-augmented generation (RAG) empowers large language models to access external and private corpus, enabling factually consistent responses in specific domains. By exploiting the inherent structure of the corpus, graph-based RAG methods further enrich this process by building a knowledge graph index and leveraging the structural nature of graphs. However, current graph-based RAG approaches seldom prioritize the design of graph structures. Inadequately designed graph not only impede the seamless integration of diverse graph algorithms but also result in workflow inconsistencies and degraded performance. To further unleash the potential of graph for RAG, we propose NodeRAG, a graph-centric framework introducing heterogeneous graph structures that enable the seamless and holistic integration of graph-based methodologies into the RAG workflow. By aligning closely with the capabilities of LLMs, this framework ensures a fully cohesive and efficient end-to-end process. Through extensive experiments, we demonstrate that NodeRAG exhibits performance advantages over previous methods, including GraphRAG and LightRAG, not only in indexing time, query time, and storage efficiency but also in delivering superior question-answering performance on multi-hop benchmarks and open-ended head-to-head evaluations with minimal retrieval tokens. Our GitHub repository could be seen at https://github.com/Terry-Xu-666/NodeRAG.

https://huggingface.co/discussions/paper/6804caa0d8538baa1c39cac2