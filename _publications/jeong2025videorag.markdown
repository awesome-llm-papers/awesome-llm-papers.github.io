---
layout: publication
title: 'Videorag: Retrieval-augmented Generation Over Video Corpus'
authors: Soyeong Jeong, Kangsan Kim, Jinheon Baek, Sung Ju Hwang
conference: No Venue
year: 2025
bibkey: jeong2025videorag
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.05874'}]
tags: ["RAG", "Tools"]
short_authors: Jeong et al.
---
Retrieval-Augmented Generation (RAG) is a powerful strategy to address the issue of generating factually incorrect outputs in foundation models by retrieving external knowledge relevant to queries and incorporating it into their generation process. However, existing RAG approaches have primarily focused on textual information, with some recent advancements beginning to consider images, and they largely overlook videos, a rich source of multimodal knowledge capable of representing events, processes, and contextual details more effectively than any other modality. While a few recent studies explore the integration of videos in the response generation process, they either predefine query-associated videos without retrieving them according to queries, or convert videos into the textual descriptions without harnessing their multimodal richness. To tackle these, we introduce VideoRAG, a novel framework that not only dynamically retrieves relevant videos based on their relevance with queries but also utilizes both visual and textual information of videos in the output generation. Further, to operationalize this, our method revolves around the recent advance of Large Video Language Models (LVLMs), which enable the direct processing of video content to represent it for retrieval and seamless integration of the retrieved videos jointly with queries. We experimentally validate the effectiveness of VideoRAG, showcasing that it is superior to relevant baselines.

https://huggingface.co/discussions/paper/678474cc65495e16860931f3