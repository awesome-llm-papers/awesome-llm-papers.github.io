---
layout: publication
title: 'CASS: Nvidia To AMD Transpilation With Data, Models, And Benchmark'
authors: Ahmed Heakl, Sarim Hashmi, Gustavo Bertolo Stahl, Seung Hun Eddie Han, Salman
  Khan, Abdulrahman Mahmoud
conference: No Venue
year: 2025
bibkey: heakl2025cass
additional_links: [{name: Code, url: 'https://huggingface.co/datasets/MBZUAI/cass\{blue\{HuggingFace\}\},'},
  {name: Code, url: 'https://github.com/GustavoStahl/CASS\{blue\{GitHub\}\'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/683656b0fd55e753bf26edf7'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.16968'}]
tags: ["Tools"]
short_authors: Heakl et al.
---
We introduce CASS, the first large-scale dataset and model suite for cross-architecture GPU code transpilation, targeting both source-level (CUDA leftrightarrow HIP) and assembly-level (Nvidia SASS leftrightarrow AMD RDNA3) translation. The dataset comprises 70k verified code pairs across host and device, addressing a critical gap in low-level GPU code portability. Leveraging this resource, we train the CASS family of domain-specific language models, achieving 95% source translation accuracy and 37.5% assembly translation accuracy, substantially outperforming commercial baselines such as GPT-4o, Claude, and Hipify. Our generated code matches native performance in over 85% of test cases, preserving runtime and memory behavior. To support rigorous evaluation, we introduce CASS-Bench, a curated benchmark spanning 16 GPU domains with ground-truth execution. All data, models, and evaluation tools are released as open source to foster progress in GPU compiler tooling, binary compatibility, and LLM-guided hardware translation. Dataset and benchmark are on https://huggingface.co/datasets/MBZUAI/cass\{blue\{HuggingFace\}\}, with code at https://github.com/GustavoStahl/CASS\{blue\{GitHub\}\}.

https://huggingface.co/discussions/paper/683656b0fd55e753bf26edf7