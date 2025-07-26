---
layout: publication
title: A Controllable Examination For Long-context Language Models
authors: Yijun Yang, Zeyu Huang, Wenhao Zhu, Zihan Qiu, Fei Yuan, Jeff Z. Pan, Ivan
  Titov
conference: No Venue
year: 2025
bibkey: yang2025controllable
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.02921'}]
tags: ["Evaluation", "Memory & Context"]
short_authors: Yang et al.
---
Existing frameworks for evaluating long-context language models (LCLM) can be broadly categorized into real-world and synthetic tasks. Despite their utility, both approaches are accompanied by certain intrinsic limitations. Real-world tasks are too complex to interpret or characterize and are susceptible to data contamination. In contrast, synthetic tasks often adopt the needle-in-the-haystack (NIAH) format, wherein a lack of coherence between the "needle" and the "haystack" compromises their validity as proxies for realistic applications. In response to these challenges, we posit that an ideal long-context evaluation framework should be characterized by three essential features: seamless context, controllable setting, and sound evaluation. This study introduces LongBioBench, a novel benchmark that utilizes artificially generated biographies as a controlled environment for assessing LCLMs across dimensions of understanding, reasoning, and trustworthiness. Our experimental evaluation, which includes 18 LCLMs in total, demonstrates that most models still exhibit deficiencies in semantic understanding and elementary reasoning over retrieved results and are less trustworthy as context length increases. Our further analysis indicates some design choices employed by existing synthetic benchmarks, such as contextual non-coherence, numerical needles, and the absence of distractors, rendering them vulnerable to test the model long-context capabilities. Moreover, we also reveal that long-context continual pretraining primarily adjusts RoPE embedding to accommodate extended context lengths. To sum up, compared to previous synthetic benchmarks, LongBioBench achieves a better trade-off between mirroring authentic language tasks and maintaining controllability, and is highly interpretable and configurable.

https://huggingface.co/discussions/paper/683ff4ddfbc9041ef7274c73