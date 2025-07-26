---
layout: publication
title: 'Ost-bench: Evaluating The Capabilities Of Mllms In Online Spatio-temporal
  Scene Understanding'
authors: Jingli Lin, Chenming Zhu, Runsen Xu, Xiaohan Mao, Xihui Liu, Tai Wang, Jiangmiao
  Pang
conference: No Venue
year: 2025
bibkey: lin2025ost
additional_links: [{name: Code, url: 'https://rbler1234.github.io/OSTBench.github.io/'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/687088a6c8391850d609787b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2507.07984'}]
tags: ["Evaluation"]
short_authors: Lin et al.
---
Recent advances in multimodal large language models (MLLMs) have shown remarkable capabilities in integrating vision and language for complex reasoning. While most existing benchmarks evaluate models under offline settings with a fixed set of pre-recorded inputs, we introduce OST-Bench, a benchmark designed to evaluate Online Spatio-Temporal understanding from the perspective of an agent actively exploring a scene. The Online aspect emphasizes the need to process and reason over incrementally acquired observations, while the Spatio-Temporal component requires integrating current visual inputs with historical memory to support dynamic spatial reasoning. OST-Bench better reflects the challenges of real-world embodied perception. Built on an efficient data collection pipeline, OST-Bench consists of 1.4k scenes and 10k question-answer pairs collected from ScanNet, Matterport3D, and ARKitScenes. We evaluate several leading MLLMs on OST-Bench and observe that they fall short on tasks requiring complex spatio-temporal reasoning. Under the online setting, their accuracy declines as the exploration horizon extends and the memory grows. Through further experimental analysis, we identify common error patterns across models and find that both complex clue-based spatial reasoning demands and long-term memory retrieval requirements significantly drop model performance along two separate axes, highlighting the core challenges that must be addressed to improve online embodied reasoning. To foster further research and development in the field, our codes, dataset, and benchmark are available. Our project page is: https://rbler1234.github.io/OSTBench.github.io/

https://huggingface.co/discussions/paper/687088a6c8391850d609787b