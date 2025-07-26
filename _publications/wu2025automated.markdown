---
layout: publication
title: Automated Movie Generation Via Multi-agent Cot Planning
authors: Weijia Wu, Zeyu Zhu, Mike Zheng Shou
conference: No Venue
year: 2025
bibkey: wu2025automated
additional_links: [{name: Code, url: 'https://github.com/showlab/MovieAgent'}, {name: Code,
    url: 'https://weijiawu.github.io/MovieAgent'}, {name: Code, url: 'https://huggingface.co/discussions/paper/67cfa752c8f2a661dc9799b8'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.07314'}]
tags: ["Has Code", "Tools"]
short_authors: Weijia Wu, Zeyu Zhu, Mike Zheng Shou
---
Existing long-form video generation frameworks lack automated planning, requiring manual input for storylines, scenes, cinematography, and character interactions, resulting in high costs and inefficiencies. To address these challenges, we present MovieAgent, an automated movie generation via multi-agent Chain of Thought (CoT) planning. MovieAgent offers two key advantages: 1) We firstly explore and define the paradigm of automated movie/long-video generation. Given a script and character bank, our MovieAgent can generates multi-scene, multi-shot long-form videos with a coherent narrative, while ensuring character consistency, synchronized subtitles, and stable audio throughout the film. 2) MovieAgent introduces a hierarchical CoT-based reasoning process to automatically structure scenes, camera settings, and cinematography, significantly reducing human effort. By employing multiple LLM agents to simulate the roles of a director, screenwriter, storyboard artist, and location manager, MovieAgent streamlines the production pipeline. Experiments demonstrate that MovieAgent achieves new state-of-the-art results in script faithfulness, character consistency, and narrative coherence. Our hierarchical framework takes a step forward and provides new insights into fully automated movie generation. The code and project website are available at: https://github.com/showlab/MovieAgent and https://weijiawu.github.io/MovieAgent.

https://huggingface.co/discussions/paper/67cfa752c8f2a661dc9799b8