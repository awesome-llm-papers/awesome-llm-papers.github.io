---
layout: publication
title: 'Neural Path Hunter: Reducing Hallucination In Dialogue Systems Via Path Grounding'
authors: Nouha Dziri, Andrea Madotto, Osmar Zaiane, Avishek Joey Bose
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
citations: 25
bibkey: dziri2021neural
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.08455'}]
tags: [Training Techniques, RAG, Evaluation]
---
Dialogue systems powered by large pre-trained language models (LM) exhibit an
innate ability to deliver fluent and natural-looking responses. Despite their
impressive generation performance, these models can often generate factually
incorrect statements impeding their widespread adoption. In this paper, we
focus on the task of improving the faithfulness -- and thus reduce
hallucination -- of Neural Dialogue Systems to known facts supplied by a
Knowledge Graph (KG). We propose Neural Path Hunter which follows a
generate-then-refine strategy whereby a generated response is amended using the
k-hop subgraph of a KG. Neural Path Hunter leverages a separate token-level
fact critic to identify plausible sources of hallucination followed by a
refinement stage consisting of a chain of two neural LM's that retrieves
correct entities by crafting a query signal that is propagated over the k-hop
subgraph. Our proposed model can easily be applied to any dialogue generated
responses without retraining the model. We empirically validate our proposed
approach on the OpenDialKG dataset against a suite of metrics and report a
relative improvement of faithfulness over dialogue responses by 20.35% based on
FeQA (Durmus et al., 2020).