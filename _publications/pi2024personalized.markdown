---
layout: publication
title: Personalized Visual Instruction Tuning
authors: Renjie Pi, Jianshu Zhang, Tianyang Han, Jipeng Zhang, Rui Pan, Tong Zhang
conference: No Venue
year: 2024
bibkey: pi2024personalized
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.07113'}]
tags: ["Fine-Tuning", "Tools", "Training Techniques"]
short_authors: Pi et al.
---
Recent advancements in multimodal large language models (MLLMs) have demonstrated significant progress; however, these models exhibit a notable limitation, which we refer to as "face blindness". Specifically, they can engage in general conversations but fail to conduct personalized dialogues targeting at specific individuals. This deficiency hinders the application of MLLMs in personalized settings, such as tailored visual assistants on mobile devices, or domestic robots that need to recognize members of the family. In this paper, we introduce Personalized Visual Instruction Tuning (PVIT), a novel data curation and training framework designed to enable MLLMs to identify target individuals within an image and engage in personalized and coherent dialogues. Our approach involves the development of a sophisticated pipeline that autonomously generates training data containing personalized conversations. This pipeline leverages the capabilities of various visual experts, image generation models, and (multi-modal) large language models. To evaluate the personalized potential of MLLMs, we present a benchmark called P-Bench, which encompasses various question types with different levels of difficulty. The experiments demonstrate a substantial personalized performance enhancement after fine-tuning with our curated dataset.

https://huggingface.co/discussions/paper/67075c2c16abdf6976cd07ea