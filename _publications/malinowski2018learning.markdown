---
layout: publication
title: Learning Visual Question Answering By Bootstrapping Hard Attention
authors: Mateusz Malinowski, Carl Doersch, Adam Santoro, Peter Battaglia
conference: Lecture Notes in Computer Science
year: 2018
bibkey: malinowski2018learning
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.00300'}]
tags: ["Datasets", "Model Architecture"]
short_authors: Malinowski et al.
---
Attention mechanisms in biological perception are thought to select subsets
of perceptual information for more sophisticated processing which would be
prohibitive to perform on all sensory inputs. In computer vision, however,
there has been relatively little exploration of hard attention, where some
information is selectively ignored, in spite of the success of soft attention,
where information is re-weighted and aggregated, but never filtered out. Here,
we introduce a new approach for hard attention and find it achieves very
competitive performance on a recently-released visual question answering
datasets, equalling and in some cases surpassing similar soft attention
architectures while entirely ignoring some features. Even though the hard
attention mechanism is thought to be non-differentiable, we found that the
feature magnitudes correlate with semantic relevance, and provide a useful
signal for our mechanism's attentional selection criterion. Because hard
attention selects important features of the input information, it can also be
more efficient than analogous soft attention mechanisms. This is especially
important for recent approaches that use non-local pairwise operations, whereby
computational and memory costs are quadratic in the size of the set of
features.