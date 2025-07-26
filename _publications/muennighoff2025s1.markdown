---
layout: publication
title: 'S1: Simple Test-time Scaling'
authors: "Niklas Muennighoff, Zitong Yang, Weijia Shi, Xiang Lisa Li, Li Fei-fei,\
  \ Hannaneh Hajishirzi, Luke Zettlemoyer, Percy Liang, Emmanuel Cand\xE8s, Tatsunori\
  \ Hashimoto"
conference: No Venue
year: 2025
bibkey: muennighoff2025s1
additional_links: [{name: Code, url: 'https://github.com/simplescaling/s1'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67a02dd90e751b0476a1bd02'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2501.19393'}]
tags: ["Datasets", "Has Code"]
short_authors: Muennighoff et al.
---
Test-time scaling is a promising new approach to language modeling that uses extra test-time compute to improve performance. Recently, OpenAI's o1 model showed this capability but did not publicly share its methodology, leading to many replication efforts. We seek the simplest approach to achieve test-time scaling and strong reasoning performance. First, we curate a small dataset s1K of 1,000 questions paired with reasoning traces relying on three criteria we validate through ablations: difficulty, diversity, and quality. Second, we develop budget forcing to control test-time compute by forcefully terminating the model's thinking process or lengthening it by appending "Wait" multiple times to the model's generation when it tries to end. This can lead the model to double-check its answer, often fixing incorrect reasoning steps. After supervised finetuning the Qwen2.5-32B-Instruct language model on s1K and equipping it with budget forcing, our model s1 exceeds o1-preview on competition math questions by up to 27% (MATH and AIME24). Further, scaling s1 with budget forcing allows extrapolating beyond its performance without test-time intervention: from 50% to 57% on AIME24. Our model, data, and code are open-source at https://github.com/simplescaling/s1.

https://huggingface.co/discussions/paper/67a02dd90e751b0476a1bd02