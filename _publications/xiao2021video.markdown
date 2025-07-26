---
layout: publication
title: Video As Conditional Graph Hierarchy For Multi-granular Question Answering
authors: Junbin Xiao, Angela Yao, Zhiyuan Liu, Yicong Li, Wei Ji, Tat-seng Chua
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2022
bibkey: xiao2021video
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.06197'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Xiao et al.
---
Video question answering requires the models to understand and reason about
both the complex video and language data to correctly derive the answers.
Existing efforts have been focused on designing sophisticated cross-modal
interactions to fuse the information from two modalities, while encoding the
video and question holistically as frame and word sequences. Despite their
success, these methods are essentially revolving around the sequential nature
of video- and question-contents, providing little insight to the problem of
question-answering and lacking interpretability as well. In this work, we argue
that while video is presented in frame sequence, the visual elements (e.g.,
objects, actions, activities and events) are not sequential but rather
hierarchical in semantic space. To align with the multi-granular essence of
linguistic concepts in language queries, we propose to model video as a
conditional graph hierarchy which weaves together visual facts of different
granularity in a level-wise manner, with the guidance of corresponding textual
cues. Despite the simplicity, our extensive experiments demonstrate the
superiority of such conditional hierarchical graph architecture, with clear
performance improvements over prior methods and also better generalization
across different type of questions. Further analyses also demonstrate the
model's reliability as it shows meaningful visual-textual evidences for the
predicted answers.