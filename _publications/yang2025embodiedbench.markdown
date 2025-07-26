---
layout: publication
title: 'Embodiedbench: Comprehensive Benchmarking Multi-modal Large Language Models
  For Vision-driven Embodied Agents'
authors: Rui Yang, Hanyang Chen, Junyu Zhang, Mark Zhao, Cheng Qian, Kangrui Wang,
  Qineng Wang, Teja Venkat Koripella, Marziyeh Movahedi, Manling Li, Heng Ji, Huan
  Zhang, Tong Zhang
conference: No Venue
year: 2025
bibkey: yang2025embodiedbench
additional_links: [{name: Code, url: 'https://embodiedbench.github.io'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67aec42b5b9801b819449bf5'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2502.09560'}]
tags: ["Datasets", "Evaluation Frameworks", "Evaluation", "Has Code", "Model Architecture", "Tools"]
short_authors: Yang et al.
---
Leveraging Multi-modal Large Language Models (MLLMs) to create embodied agents offers a promising avenue for tackling real-world tasks. While language-centric embodied agents have garnered substantial attention, MLLM-based embodied agents remain underexplored due to the lack of comprehensive evaluation frameworks. To bridge this gap, we introduce EmbodiedBench, an extensive benchmark designed to evaluate vision-driven embodied agents. EmbodiedBench features: (1) a diverse set of 1,128 testing tasks across four environments, ranging from high-level semantic tasks (e.g., household) to low-level tasks involving atomic actions (e.g., navigation and manipulation); and (2) six meticulously curated subsets evaluating essential agent capabilities like commonsense reasoning, complex instruction understanding, spatial awareness, visual perception, and long-term planning. Through extensive experiments, we evaluated 13 leading proprietary and open-source MLLMs within EmbodiedBench. Our findings reveal that: MLLMs excel at high-level tasks but struggle with low-level manipulation, with the best model, GPT-4o, scoring only 28.9% on average. EmbodiedBench provides a multifaceted standardized evaluation platform that not only highlights existing challenges but also offers valuable insights to advance MLLM-based embodied agents. Our code is available at https://embodiedbench.github.io.

https://huggingface.co/discussions/paper/67aec42b5b9801b819449bf5