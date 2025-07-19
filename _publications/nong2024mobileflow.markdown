---
layout: publication
title: 'Mobileflow: A Multimodal LLM For Mobile GUI Agent'
authors: Nong et al.
conference: IEEE Communications Magazine
year: 2024
bibkey: nong2024mobileflow
citations: 274
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.04346'}]
tags: [Training Techniques, GPT, Agentic, Tools, Evaluation, Model Architecture, Reinforcement
    Learning, Applications, Multimodal Models]
---
Currently, the integration of mobile Graphical User Interfaces (GUIs) is
ubiquitous in most people's daily lives. And the ongoing evolution of
multimodal large-scale models, such as GPT-4v, Qwen-VL-Max, has significantly
bolstered the capabilities of GUI comprehension and user action analysis,
showcasing the potentiality of intelligent GUI assistants. However, current GUI
Agents often need to access page layout information through calling system
APIs, which may pose privacy risks. Fixing GUI (such as mobile interfaces) to a
certain low resolution might result in the loss of fine-grained image details.
At the same time, the multimodal large models built for GUI Agents currently
have poor understanding and decision-making abilities for Chinese GUI
interfaces, making them difficult to apply to a large number of Chinese apps.
This paper introduces MobileFlow, a multimodal large language model
meticulously crafted for mobile GUI agents. Transforming from the open-source
model Qwen-VL-Chat into GUI domain, MobileFlow contains approximately 21
billion parameters and is equipped with novel hybrid visual encoders, making it
possible for variable resolutions of image inputs and good support for
multilingual GUI. By incorporating Mixture of Experts (MoE) expansions and
pioneering alignment training strategies, MobileFlow has the capacity to fully
interpret image data and comprehend user instructions for GUI interaction
tasks. Finally, MobileFlow outperforms Qwen-VL-Max and GPT-4v in terms of task
execution by GUI agents on both public and our proposed evaluation metrics, and
has been successfully deployed in real-world business contexts, proving its
effectiveness for practical applications.