---
layout: publication
title: 'A Survey Of Efficient Reasoning For Large Reasoning Models: Language, Multimodality,
  And Beyond'
authors: Qu et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2023'
year: 2025
bibkey: qu2025survey
citations: 153
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.21614'}]
tags: [Tools, Training Techniques, Efficiency And Optimization, Survey Paper, Fine
    Tuning, ACL, Agentic, Multimodal Models, Reinforcement Learning]
---
Recent Large Reasoning Models (LRMs), such as DeepSeek-R1 and OpenAI o1, have
demonstrated strong performance gains by scaling up the length of
Chain-of-Thought (CoT) reasoning during inference. However, a growing concern
lies in their tendency to produce excessively long reasoning traces, which are
often filled with redundant content (e.g., repeated definitions), over-analysis
of simple problems, and superficial exploration of multiple reasoning paths for
harder tasks. This inefficiency introduces significant challenges for training,
inference, and real-world deployment (e.g., in agent-based systems), where
token economy is critical. In this survey, we provide a comprehensive overview
of recent efforts aimed at improving reasoning efficiency in LRMs, with a
particular focus on the unique challenges that arise in this new paradigm. We
identify common patterns of inefficiency, examine methods proposed across the
LRM lifecycle, i.e., from pretraining to inference, and discuss promising
future directions for research. To support ongoing development, we also
maintain a real-time GitHub repository tracking recent progress in the field.
We hope this survey serves as a foundation for further exploration and inspires
innovation in this rapidly evolving area.