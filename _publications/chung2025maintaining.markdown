---
layout: publication
title: 'Maintaining MTEB: Towards Long Term Usability And Reproducibility Of Embedding
  Benchmarks'
authors: Chung et al.
conference: Proceedings of the 17th Conference of the European Chapter of the Association
  for Computational Linguistics
year: 2025
bibkey: chung2025maintaining
citations: 134
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.21182'}]
tags: [Tools, Datasets, Evaluation, ACL, EACL]
---
The Massive Text Embedding Benchmark (MTEB) has become a standard evaluation platform for text embedding models. While previous work has established the core benchmark methodology, this paper focuses on the engineering aspects that ensure MTEB's continued reproducibility and extensibility. We present our approach to maintaining robust continuous integration pipelines that validate dataset integrity, automate test execution, and assess benchmark results' generalizability. We detail the design choices that collectively enhance reproducibility and usability. Furthermore, we discuss our strategies for handling community contributions and extending the benchmark with new tasks and datasets. These engineering practices have been instrumental in scaling MTEB to become more comprehensive while maintaining quality and, ultimately, relevance to the field. Our experiences offer valuable insights for benchmark maintainers facing similar challenges in ensuring reproducibility and usability in machine learning evaluation frameworks. The MTEB repository is available at: https://github.com/embeddings-benchmark/mteb