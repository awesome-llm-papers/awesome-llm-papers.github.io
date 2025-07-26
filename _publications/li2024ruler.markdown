---
layout: publication
title: 'Ruler: A Model-agnostic Method To Control Generated Length For Large Language
  Models'
authors: Jiaming Li, Lei Zhang, Yunshui Li, Ziqiang Liu, Yuelin Bai, Run Luo, Longze
  Chen, Min Yang
conference: No Venue
year: 2024
bibkey: li2024ruler
additional_links: [{name: Code, url: 'https://github.com/Geaming2002/Ruler'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66fb45aa05bf0586e2813af5'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2409.18943'}]
tags: ["Agentic", "Evaluation", "Has Code"]
short_authors: Li et al.
---
The instruction-following ability of large language models enables humans to interact with AI agents in a natural way. However, when required to generate responses of a specific length, large language models often struggle to meet users' needs due to their inherent difficulty in accurately perceiving numerical constraints. To explore the ability of large language models to control the length of generated responses, we propose the Target Length Generation Task (TLG) and design two metrics, Precise Match (PM) and Flexible Match (FM) to evaluate the model's performance in adhering to specified response lengths. Furthermore, we introduce a novel, model-agnostic approach called Ruler, which employs Meta Length Tokens (MLTs) to enhance the instruction-following ability of large language models under length-constrained instructions. Specifically, Ruler equips LLMs with the ability to generate responses of a specified length based on length constraints within the instructions. Moreover, Ruler can automatically generate appropriate MLT when length constraints are not explicitly provided, demonstrating excellent versatility and generalization. Comprehensive experiments show the effectiveness of Ruler across different LLMs on Target Length Generation Task, e.g., at All Level 27.97 average gain on PM, 29.57 average gain on FM. In addition, we conduct extensive ablation experiments to further substantiate the efficacy and generalization of Ruler. Our code and data is available at https://github.com/Geaming2002/Ruler.

https://huggingface.co/discussions/paper/66fb45aa05bf0586e2813af5