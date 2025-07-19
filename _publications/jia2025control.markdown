---
layout: publication
title: 'Control-clip: Decoupling Category And Style Guidance In CLIP For Specific-domain
  Generation'
authors: Jia et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: jia2025control
citations: 170
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.11532'}]
tags: [Training Techniques, Attention Mechanism, Prompting, Tools, Transformer, Model
    Architecture, Reinforcement Learning, Fine Tuning, Merging]
---
Text-to-image diffusion models have shown remarkable capabilities of
generating high-quality images closely aligned with textual inputs. However,
the effectiveness of text guidance heavily relies on the CLIP text encoder,
which is trained to pay more attention to general content but struggles to
capture semantics in specific domains like styles. As a result, generation
models tend to fail on prompts like "a photo of a cat in Pokemon style" in
terms of simply producing images depicting "a photo of a cat". To fill this
gap, we propose Control-CLIP, a novel decoupled CLIP fine-tuning framework that
enables the CLIP model to learn the meaning of category and style in a
complement manner. With specially designed fine-tuning tasks on minimal data
and a modified cross-attention mechanism, Control-CLIP can precisely guide the
diffusion model to a specific domain. Moreover, the parameters of the diffusion
model remain unchanged at all, preserving the original generation performance
and diversity. Experiments across multiple domains confirm the effectiveness of
our approach, particularly highlighting its robust plug-and-play capability in
generating content with various specific styles.