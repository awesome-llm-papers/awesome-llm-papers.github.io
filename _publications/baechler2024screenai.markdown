---
layout: publication
title: 'Screenai: A Vision-language Model For UI And Infographics Understanding'
authors: "Gilles Baechler, Srinivas Sunkara, Maria Wang, Fedir Zubach, Hassan Mansoor,\
  \ Vincent Etter, Victor C\u0103rbune, Jason Lin, Jindong Chen, Abhanshu Sharma"
conference: No Venue
year: 2024
bibkey: baechler2024screenai
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65c43d0947a0ffffa96804c4'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2402.04615'}]
tags: ["Datasets", "Model Architecture", "Training Techniques"]
short_authors: Baechler et al.
---
Screen user interfaces (UIs) and infographics, sharing similar visual language and design principles, play important roles in human communication and human-machine interaction. We introduce ScreenAI, a vision-language model that specializes in UI and infographics understanding. Our model improves upon the PaLI architecture with the flexible patching strategy of pix2struct and is trained on a unique mixture of datasets. At the heart of this mixture is a novel screen annotation task in which the model has to identify the type and location of UI elements. We use these text annotations to describe screens to Large Language Models and automatically generate question-answering (QA), UI navigation, and summarization training datasets at scale. We run ablation studies to demonstrate the impact of these design choices. At only 5B parameters, ScreenAI achieves new state-of-the-artresults on UI- and infographics-based tasks (Multi-page DocVQA, WebSRC, MoTIF and Widget Captioning), and new best-in-class performance on others (Chart QA, DocVQA, and InfographicVQA) compared to models of similar size. Finally, we release three new datasets: one focused on the screen annotation task and two others focused on question answering.

https://huggingface.co/discussions/paper/65c43d0947a0ffffa96804c4