---
layout: publication
title: 'Selfcheckagent: Zero-resource Hallucination Detection In Generative Large
  Language Models'
authors: "Muhammed Diyana, Rabby Gollam, Auer S\xF6ren"
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: muhammed2025selfcheckagent
citations: 109
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.01812'}]
tags: [RAG, EMNLP, GPT, Agentic, Tools, Model Architecture, Reinforcement Learning,
  Applications, Datasets]
---
Detecting hallucinations in Large Language Models (LLMs) remains a critical
challenge for their reliable deployment in real-world applications. To address
this, we introduce SelfCheckAgent, a novel framework integrating three
different agents: the Symbolic Agent, the Specialized Detection Agent, and the
Contextual Consistency Agent. These agents provide a robust multi-dimensional
approach to hallucination detection. Notable results include the Contextual
Consistency Agent leveraging Llama 3.1 with Chain-of-Thought (CoT) to achieve
outstanding performance on the WikiBio dataset, with NonFactual hallucination
detection scoring 93.64%, Factual 70.26%, and Ranking 78.48% respectively. On
the AIME dataset, GPT-4o with CoT excels in NonFactual detection with 94.89%
but reveals trade-offs in Factual with 30.58% and Ranking with 30.68%,
underscoring the complexity of hallucination detection in the complex
mathematical domains. The framework also incorporates a triangulation strategy,
which increases the strengths of the SelfCheckAgent, yielding significant
improvements in real-world hallucination identification. The comparative
analysis demonstrates SelfCheckAgent's applicability across diverse domains,
positioning it as a crucial advancement for trustworthy LLMs. These findings
highlight the potentiality of consistency-driven methodologies in detecting
hallucinations in LLMs.