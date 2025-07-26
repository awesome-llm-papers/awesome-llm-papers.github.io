---
layout: publication
title: 'Learning To Reason: End-to-end Module Networks For Visual Question Answering'
authors: Ronghang Hu, Jacob Andreas, Marcus Rohrbach, Trevor Darrell, Kate Saenko
conference: 2017 IEEE International Conference on Computer Vision (ICCV)
year: 2017
bibkey: hu2017learning
citations: 509
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.05526'}]
tags: ["ICCV", "Model Architecture"]
short_authors: Hu et al.
---
Natural language questions are inherently compositional, and many are most
easily answered by reasoning about their decomposition into modular
sub-problems. For example, to answer "is there an equal number of balls and
boxes?" we can look for balls, look for boxes, count them, and compare the
results. The recently proposed Neural Module Network (NMN) architecture
implements this approach to question answering by parsing questions into
linguistic substructures and assembling question-specific deep networks from
smaller modules that each solve one subtask. However, existing NMN
implementations rely on brittle off-the-shelf parsers, and are restricted to
the module configurations proposed by these parsers rather than learning them
from data. In this paper, we propose End-to-End Module Networks (N2NMNs), which
learn to reason by directly predicting instance-specific network layouts
without the aid of a parser. Our model learns to generate network structures
(by imitating expert demonstrations) while simultaneously learning network
parameters (using the downstream task loss). Experimental results on the new
CLEVR dataset targeted at compositional question answering show that N2NMNs
achieve an error reduction of nearly 50% relative to state-of-the-art
attentional approaches, while discovering interpretable network architectures
specialized for each question.