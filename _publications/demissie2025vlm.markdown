---
layout: publication
title: 'Vlm-fuzz: Vision Language Model Assisted Recursive Depth-first Search Exploration
  For Effective UI Testing Of Android Apps'
authors: Demissie et al.
conference: Proceedings of the 2013 ACM SIGPLAN international conference on Object
  oriented programming systems languages &amp; applications
year: 2025
bibkey: demissie2025vlm
citations: 231
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.11675'}]
tags: [RAG, Evaluation, Applications, Fine Tuning, Datasets, LLM For Code]
---
Testing Android apps effectively requires a systematic exploration of the
app's possible states by simulating user interactions and system events. While
existing approaches have proposed several fuzzing techniques to generate
various text inputs and trigger user and system events for UI state
exploration, achieving high code coverage remains a significant challenge in
Android app testing. The main challenges are (1) reasoning about the complex
and dynamic layout of UI screens; (2) generating required inputs/events to deal
with certain widgets like pop-ups; and (3) coordination between current test
inputs and previous inputs to avoid getting stuck in the same UI screen without
improving test coverage. To address these problems, we propose a novel,
automated fuzzing approach called VLM-Fuzz for effective UI testing of Android
apps. We present a novel heuristic-based depth-first search (DFS) exploration
algorithm, assisted with a vision language model (VLM), to effectively explore
the UI states of the app. We use static analysis to analyze the Android
Manifest file and the runtime UI hierarchy XML to extract the list of
components, intent-filters and interactive UI widgets. VLM is used to reason
about complex UI layout and widgets on an on-demand basis. Based on the inputs
from static analysis, VLM, and the current UI state, we use some heuristics to
deal with the above-mentioned challenges. We evaluated VLM-Fuzz based on a
benchmark containing 59 apps obtained from a recent work and compared it
against two state-of-the-art approaches: APE and DeepGUI. VLM-Fuzz outperforms
the best baseline by 9.0%, 3.7%, and 2.1% in terms of class coverage, method
coverage, and line coverage, respectively. We also ran VLM-Fuzz on 80 recent
Google Play apps (i.e., updated in 2024). VLM-Fuzz detected 208 unique crashes
in 24 apps, which have been reported to respective developers.