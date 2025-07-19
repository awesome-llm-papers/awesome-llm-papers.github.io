---
layout: publication
title: 'Focuschat: Text-guided Long Video Understanding Via Spatiotemporal Information
  Filtering'
authors: Cheng Zheng, Wang Rendong, Wang Zhicheng
conference: Proceedings of High Performance Graphics
year: 2024
bibkey: cheng2024focuschat
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.12833'}]
tags: [Prompting, Few Shot, Training Techniques]
---
Recently, multi-modal large language models have made significant progress. However, visual information lacking of guidance from the user's intention may lead to redundant computation and involve unnecessary visual noise, especially in long, untrimmed videos. To address this issue, we propose FocusChat, a text-guided multi-modal large language model (LLM) that emphasizes visual information correlated to the user's prompt. In detail, Our model first undergoes the semantic extraction module, which comprises a visual semantic branch and a text semantic branch to extract image and text semantics, respectively. The two branches are combined using the Spatial-Temporal Filtering Module (STFM). STFM enables explicit spatial-level information filtering and implicit temporal-level feature filtering, ensuring that the visual tokens are closely aligned with the user's query. It lowers the essential number of visual tokens inputted into the LLM. FocusChat significantly outperforms Video-LLaMA in zero-shot experiments, using an order of magnitude less training data with only 16 visual tokens occupied. It achieves results comparable to the state-of-the-art in few-shot experiments, with only 0.72M pre-training data.