---
layout: publication
title: Scaling Computer-use Grounding Via User Interface Decomposition And Synthesis
authors: Tianbao Xie, Jiaqi Deng, Xiaochuan Li, Junlin Yang, Haoyuan Wu, Jixuan Chen,
  Wenjing Hu, Xinyuan Wang, Yuhui Xu, Zekun Wang, Yiheng Xu, Junli Wang, Doyen Sahoo,
  Tao Yu, Caiming Xiong
conference: No Venue
year: 2025
bibkey: xie2025scaling
additional_links: [{name: Code, url: 'https://osworld-grounding.github.io'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/682c12ba4040343163ca7fd4'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.13227'}]
tags: ["Agentic", "Datasets", "Evaluation", "Has Code"]
short_authors: Xie et al.
---
Graphical user interface (GUI) grounding, the ability to map natural language instructions to specific actions on graphical user interfaces, remains a critical bottleneck in computer use agent development. Current benchmarks oversimplify grounding tasks as short referring expressions, failing to capture the complexity of real-world interactions that require software commonsense, layout understanding, and fine-grained manipulation capabilities. To address these limitations, we introduce OSWorld-G, a comprehensive benchmark comprising 564 finely annotated samples across diverse task types including text matching, element recognition, layout understanding, and precise manipulation. Additionally, we synthesize and release the largest computer use grounding dataset Jedi, which contains 4 million examples through multi-perspective decoupling of tasks. Our multi-scale models trained on Jedi demonstrate its effectiveness by outperforming existing approaches on ScreenSpot-v2, ScreenSpot-Pro, and our OSWorld-G. Furthermore, we demonstrate that improved grounding with Jedi directly enhances agentic capabilities of general foundation models on complex computer tasks, improving from 5% to 27% on OSWorld. Through detailed ablation studies, we identify key factors contributing to grounding performance and verify that combining specialized data for different interface elements enables compositional generalization to novel interfaces. All benchmark, data, checkpoints, and code are open-sourced and available at https://osworld-grounding.github.io.

https://huggingface.co/discussions/paper/682c12ba4040343163ca7fd4