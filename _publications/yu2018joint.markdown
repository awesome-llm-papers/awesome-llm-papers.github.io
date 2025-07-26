---
layout: publication
title: A Joint Sequence Fusion Model For Video Question Answering And Retrieval
authors: Youngjae Yu, Jongseok Kim, Gunhee Kim
conference: Lecture Notes in Computer Science
year: 2018
bibkey: yu2018joint
citations: 323
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.02559'}]
tags: ["Datasets", "Model Architecture"]
short_authors: Youngjae Yu, Jongseok Kim, Gunhee Kim
---
We present an approach named JSFusion (Joint Sequence Fusion) that can
measure semantic similarity between any pairs of multimodal sequence data (e.g.
a video clip and a language sentence). Our multimodal matching network consists
of two key components. First, the Joint Semantic Tensor composes a dense
pairwise representation of two sequence data into a 3D tensor. Then, the
Convolutional Hierarchical Decoder computes their similarity score by
discovering hidden hierarchical matches between the two sequence modalities.
Both modules leverage hierarchical attention mechanisms that learn to promote
well-matched representation patterns while prune out misaligned ones in a
bottom-up manner. Although the JSFusion is a universal model to be applicable
to any multimodal sequence data, this work focuses on video-language tasks
including multimodal retrieval and video QA. We evaluate the JSFusion model in
three retrieval and VQA tasks in LSMDC, for which our model achieves the best
performance reported so far. We also perform multiple-choice and movie
retrieval tasks for the MSR-VTT dataset, on which our approach outperforms many
state-of-the-art methods.