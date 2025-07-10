---
layout: publication
title: A Survey On Lora Of Large Language Models
authors: Yuren Mao et al.
conference: Frontiers of Computer Science
year: 2024
citations: 16
bibkey: mao2024survey
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.11046'}, {name: Code,
    url: 'https://github.com/ZJU-LLMs/Awesome-LoRAs.git}{https://github.com/ZJU-LLMs/Awesome-LoRAs.git'}]
tags: [Has Code, Model Architecture, Attention Mechanism, Fine-Tuning, Survey Paper,
  Tools, Efficiency and Optimization, Training Techniques]
---
Low-Rank Adaptation~(LoRA), which updates the dense neural network layers
with pluggable low-rank matrices, is one of the best performed parameter
efficient fine-tuning paradigms. Furthermore, it has significant advantages in
cross-task generalization and privacy-preserving. Hence, LoRA has gained much
attention recently, and the number of related literature demonstrates
exponential growth. It is necessary to conduct a comprehensive overview of the
current progress on LoRA. This survey categorizes and reviews the progress from
the perspectives of (1) downstream adaptation improving variants that improve
LoRA's performance on downstream tasks; (2) cross-task generalization methods
that mix multiple LoRA plugins to achieve cross-task generalization; (3)
efficiency-improving methods that boost the computation-efficiency of LoRA; (4)
data privacy-preserving methods that use LoRA in federated learning; (5)
application. Besides, this survey also discusses the future directions in this
field. At last, we provide a Github
page~\footnote\{\href\{https://github.com/ZJU-LLMs/Awesome-LoRAs.git\}\{https://github.com/ZJU-LLMs/Awesome-LoRAs.git\}\}
for readers to check the updates and initiate discussions on this survey paper.