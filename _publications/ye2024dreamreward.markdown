---
layout: publication
title: 'Dreamreward: Text-to-3d Generation With Human Preference'
authors: Junliang Ye, Fangfu Liu, Qixiu Li, Zhengyi Wang, Yikai Wang, Xinzhou Wang,
  Yueqi Duan, Jun Zhu
conference: No Venue
year: 2024
bibkey: ye2024dreamreward
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65fcf1ddc3f470c772d92ec1'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2403.14613'}]
tags: ["Tools"]
short_authors: Ye et al.
---
3D content creation from text prompts has shown remarkable success recently. However, current text-to-3D methods often generate 3D results that do not align well with human preferences. In this paper, we present a comprehensive framework, coined DreamReward, to learn and improve text-to-3D models from human preference feedback. To begin with, we collect 25k expert comparisons based on a systematic annotation pipeline including rating and ranking. Then, we build Reward3D -- the first general-purpose text-to-3D human preference reward model to effectively encode human preferences. Building upon the 3D reward model, we finally perform theoretical analysis and present the Reward3D Feedback Learning (DreamFL), a direct tuning algorithm to optimize the multi-view diffusion models with a redefined scorer. Grounded by theoretical proof and extensive experiment comparisons, our DreamReward successfully generates high-fidelity and 3D consistent results with significant boosts in prompt alignment with human intention. Our results demonstrate the great potential for learning from human feedback to improve text-to-3D models.

https://huggingface.co/discussions/paper/65fcf1ddc3f470c772d92ec1