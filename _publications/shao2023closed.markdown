---
layout: publication
title: 'Lmdrive: Closed-loop End-to-end Driving With Large Language Models'
authors: Hao Shao et al.
conference: Arxiv
year: 2023
citations: 23
bibkey: shao2023closed
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.07488'}, {name: Code,
    url: 'https://github.com/opendilab/LMDrive'}]
tags: [RAG, Has Code, Tools]
---
Despite significant recent progress in the field of autonomous driving,
modern methods still struggle and can incur serious accidents when encountering
long-tail unforeseen events and challenging urban scenarios. On the one hand,
large language models (LLM) have shown impressive reasoning capabilities that
approach "Artificial General Intelligence". On the other hand, previous
autonomous driving methods tend to rely on limited-format inputs (e.g. sensor
data and navigation waypoints), restricting the vehicle's ability to understand
language information and interact with humans. To this end, this paper
introduces LMDrive, a novel language-guided, end-to-end, closed-loop autonomous
driving framework. LMDrive uniquely processes and integrates multi-modal sensor
data with natural language instructions, enabling interaction with humans and
navigation software in realistic instructional settings. To facilitate further
research in language-based closed-loop autonomous driving, we also publicly
release the corresponding dataset which includes approximately 64K
instruction-following data clips, and the LangAuto benchmark that tests the
system's ability to handle complex instructions and challenging driving
scenarios. Extensive closed-loop experiments are conducted to demonstrate
LMDrive's effectiveness. To the best of our knowledge, we're the very first
work to leverage LLMs for closed-loop end-to-end autonomous driving. Codes,
models, and datasets can be found at https://github.com/opendilab/LMDrive