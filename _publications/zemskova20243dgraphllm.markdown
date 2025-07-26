---
layout: publication
title: '3dgraphllm: Combining Semantic Graphs And Large Language Models For 3D Scene
  Understanding'
authors: Tatiana Zemskova, Dmitry Yudin
conference: No Venue
year: 2024
bibkey: zemskova20243dgraphllm
additional_links: [{name: Code, url: 'https://github.com/CognitiveAISystems/3DGraphLLM'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/676bbe599484d105b89dbac5'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.18450'}]
tags: ["Agentic", "Datasets", "Has Code"]
short_authors: Tatiana Zemskova, Dmitry Yudin
---
A 3D scene graph represents a compact scene model, storing information about the objects and the semantic relationships between them, making its use promising for robotic tasks. When interacting with a user, an embodied intelligent agent should be capable of responding to various queries about the scene formulated in natural language. Large Language Models (LLMs) are beneficial solutions for user-robot interaction due to their natural language understanding and reasoning abilities. Recent methods for creating learnable representations of 3D scenes have demonstrated the potential to improve the quality of LLMs responses by adapting to the 3D world. However, the existing methods do not explicitly utilize information about the semantic relationships between objects, limiting themselves to information about their coordinates. In this work, we propose a method 3DGraphLLM for constructing a learnable representation of a 3D scene graph. The learnable representation is used as input for LLMs to perform 3D vision-language tasks. In our experiments on popular ScanRefer, RIORefer, Multi3DRefer, ScanQA, Sqa3D, and Scan2cap datasets, we demonstrate the advantage of this approach over baseline methods that do not use information about the semantic relationships between objects. The code is publicly available at https://github.com/CognitiveAISystems/3DGraphLLM.

https://huggingface.co/discussions/paper/676bbe599484d105b89dbac5