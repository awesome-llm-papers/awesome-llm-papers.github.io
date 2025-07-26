---
layout: publication
title: 'MEDIC: Towards A Comprehensive Framework For Evaluating Llms In Clinical Applications'
authors: "Praveen K Kanithi, Cl\xE9ment Christophe, Marco Af Pimentel, Tathagata Raha,\
  \ Nada Saadi, Hamza Javed, Svetlana Maslenkova, Nasir Hayat, Ronnie Rajan, Shadab\
  \ Khan"
conference: No Venue
year: 2024
bibkey: kanithi2024medic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2409.07314'}]
tags: ["Applications", "Evaluation"]
short_authors: Kanithi et al.
---
The rapid development of Large Language Models (LLMs) for healthcare applications has spurred calls for holistic evaluation beyond frequently-cited benchmarks like USMLE, to better reflect real-world performance. While real-world assessments are valuable indicators of utility, they often lag behind the pace of LLM evolution, likely rendering findings obsolete upon deployment. This temporal disconnect necessitates a comprehensive upfront evaluation that can guide model selection for specific clinical applications. We introduce MEDIC, a framework assessing LLMs across five critical dimensions of clinical competence: medical reasoning, ethics and bias, data and language understanding, in-context learning, and clinical safety. MEDIC features a novel cross-examination framework quantifying LLM performance across areas like coverage and hallucination detection, without requiring reference outputs. We apply MEDIC to evaluate LLMs on medical question-answering, safety, summarization, note generation, and other tasks. Our results show performance disparities across model sizes, baseline vs medically finetuned models, and have implications on model selection for applications requiring specific model strengths, such as low hallucination or lower cost of inference. MEDIC's multifaceted evaluation reveals these performance trade-offs, bridging the gap between theoretical capabilities and practical implementation in healthcare settings, ensuring that the most promising models are identified and adapted for diverse healthcare applications.

https://huggingface.co/discussions/paper/66e263853b7e36b011d0f8d6