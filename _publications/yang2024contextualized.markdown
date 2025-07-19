---
layout: publication
title: Contextualized Diffusion Models For Text-guided Image And Video Generation
authors: Yang et al.
conference: Special Interest Group on Computer Graphics and Interactive Techniques
  Conference Conference Proceedings
year: 2024
bibkey: yang2024contextualized
citations: 100
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.16627'}]
tags: [Multimodal Models, Evaluation, Merging]
---
Conditional diffusion models have exhibited superior performance in
high-fidelity text-guided visual generation and editing. Nevertheless,
prevailing text-guided visual diffusion models primarily focus on incorporating
text-visual relationships exclusively into the reverse process, often
disregarding their relevance in the forward process. This inconsistency between
forward and reverse processes may limit the precise conveyance of textual
semantics in visual synthesis results. To address this issue, we propose a
novel and general contextualized diffusion model (ContextDiff) by incorporating
the cross-modal context encompassing interactions and alignments between text
condition and visual sample into forward and reverse processes. We propagate
this context to all timesteps in the two processes to adapt their trajectories,
thereby facilitating cross-modal conditional modeling. We generalize our
contextualized diffusion to both DDPMs and DDIMs with theoretical derivations,
and demonstrate the effectiveness of our model in evaluations with two
challenging tasks: text-to-image generation, and text-to-video editing. In each
task, our ContextDiff achieves new state-of-the-art performance, significantly
enhancing the semantic alignment between text condition and generated samples,
as evidenced by quantitative and qualitative evaluations. Our code is available
at https://github.com/YangLing0818/ContextDiff