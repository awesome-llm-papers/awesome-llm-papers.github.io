---
layout: publication
title: 'Saffron-1: Towards An Inference Scaling Paradigm For LLM Safety Assurance'
authors: Ruizhong Qiu, Gaotang Li, Tianxin Wei, Jingrui He, Hanghang Tong
conference: No Venue
year: 2025
bibkey: qiu2025saffron
additional_links: [{name: Code, url: 'https://github.com/q-rz/saffron'}, {name: Code,
    url: 'https://q-rz.github.io/p/saffron'}, {name: Code, url: 'https://huggingface.co/discussions/paper/68479c1e3ec10bdd8ab4dea2'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.06444'}]
tags: ["Datasets", "Efficiency", "Ethics & Fairness", "Has Code", "Memory & Context", "Reinforcement Learning", "Training Techniques"]
short_authors: Qiu et al.
---
Existing safety assurance research has primarily focused on training-phase alignment to instill safe behaviors into LLMs. However, recent studies have exposed these methods' susceptibility to diverse jailbreak attacks. Concurrently, inference scaling has significantly advanced LLM reasoning capabilities but remains unexplored in the context of safety assurance. Addressing this gap, our work pioneers inference scaling for robust and effective LLM safety against emerging threats. We reveal that conventional inference scaling techniques, despite their success in reasoning tasks, perform poorly in safety contexts, even falling short of basic approaches like Best-of-N Sampling. We attribute this inefficiency to a newly identified challenge, the exploration--efficiency dilemma, arising from the high computational overhead associated with frequent process reward model (PRM) evaluations. To overcome this dilemma, we propose SAFFRON, a novel inference scaling paradigm tailored explicitly for safety assurance. Central to our approach is the introduction of a multifurcation reward model (MRM) that significantly reduces the required number of reward model evaluations. To operationalize this paradigm, we further propose: (i) a partial supervision training objective for MRM, (ii) a conservative exploration constraint to prevent out-of-distribution explorations, and (iii) a Trie-based key--value caching strategy that facilitates cache sharing across sequences during tree search. Extensive experiments validate the effectiveness of our method. Additionally, we publicly release our trained multifurcation reward model (Saffron-1) and the accompanying token-level safety reward dataset (Safety4M) to accelerate future research in LLM safety. Our code, model, and data are publicly available at https://github.com/q-rz/saffron , and our project homepage is at https://q-rz.github.io/p/saffron .

https://huggingface.co/discussions/paper/68479c1e3ec10bdd8ab4dea2