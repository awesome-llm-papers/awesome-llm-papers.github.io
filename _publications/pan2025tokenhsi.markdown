---
layout: publication
title: 'Tokenhsi: Unified Synthesis Of Physical Human-scene Interactions Through Task
  Tokenization'
authors: Liang Pan, Zeshi Yang, Zhiyang Dou, Wenjia Wang, Buzhen Huang, Bo Dai, Taku
  Komura, Jingbo Wang
conference: No Venue
year: 2025
bibkey: pan2025tokenhsi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.19901'}]
tags: ["Has Code", "Model Architecture", "Training Techniques"]
short_authors: Pan et al.
---
Synthesizing diverse and physically plausible Human-Scene Interactions (HSI) is pivotal for both computer animation and embodied AI. Despite encouraging progress, current methods mainly focus on developing separate controllers, each specialized for a specific interaction task. This significantly hinders the ability to tackle a wide variety of challenging HSI tasks that require the integration of multiple skills, e.g., sitting down while carrying an object. To address this issue, we present TokenHSI, a single, unified transformer-based policy capable of multi-skill unification and flexible adaptation. The key insight is to model the humanoid proprioception as a separate shared token and combine it with distinct task tokens via a masking mechanism. Such a unified policy enables effective knowledge sharing across skills, thereby facilitating the multi-task training. Moreover, our policy architecture supports variable length inputs, enabling flexible adaptation of learned skills to new scenarios. By training additional task tokenizers, we can not only modify the geometries of interaction targets but also coordinate multiple skills to address complex tasks. The experiments demonstrate that our approach can significantly improve versatility, adaptability, and extensibility in various HSI tasks. Website: https://liangpan99.github.io/TokenHSI/

https://huggingface.co/discussions/paper/67eac6443755a17e3cbff5cf