---
layout: publication
title: 'Seqafford: Sequential 3D Affordance Reasoning Via Multimodal Large Language
  Model'
authors: Yu et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: yu2024seqafford
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.01550'}]
tags: [Tools, Evaluation, CVPR, Reinforcement Learning, Multimodal Models, Datasets]
---
3D affordance segmentation aims to link human instructions to touchable
regions of 3D objects for embodied manipulations. Existing efforts typically
adhere to single-object, single-affordance paradigms, where each affordance
type or explicit instruction strictly corresponds to a specific affordance
region and are unable to handle long-horizon tasks. Such a paradigm cannot
actively reason about complex user intentions that often imply sequential
affordances. In this paper, we introduce the Sequential 3D Affordance Reasoning
task, which extends the traditional paradigm by reasoning from cumbersome user
intentions and then decomposing them into a series of segmentation maps. Toward
this, we construct the first instruction-based affordance segmentation
benchmark that includes reasoning over both single and sequential affordances,
comprising 180K instruction-point cloud pairs. Based on the benchmark, we
propose our model, SeqAfford, to unlock the 3D multi-modal large language model
with additional affordance segmentation abilities, which ensures reasoning with
world knowledge and fine-grained affordance grounding in a cohesive framework.
We further introduce a multi-granular language-point integration module to
endow 3D dense prediction. Extensive experimental evaluations show that our
model excels over well-established methods and exhibits open-world
generalization with sequential reasoning abilities.