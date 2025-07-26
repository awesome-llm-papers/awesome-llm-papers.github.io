---
layout: publication
title: 'Dreambooth3d: Subject-driven Text-to-3d Generation'
authors: Amit Raj, Srinivas Kaza, Ben Poole, Michael Niemeyer, Nataniel Ruiz, Ben
  Mildenhall, Shiran Zada, Kfir Aberman, Michael Rubinstein, Jonathan Barron, Yuanzhen
  Li, Varun Jampani
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2023
bibkey: raj2023dreambooth3d
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.13508'}]
tags: ["ICCV"]
short_authors: Raj et al.
---
We present DreamBooth3D, an approach to personalize text-to-3D generative
models from as few as 3-6 casually captured images of a subject. Our approach
combines recent advances in personalizing text-to-image models (DreamBooth)
with text-to-3D generation (DreamFusion). We find that naively combining these
methods fails to yield satisfactory subject-specific 3D assets due to
personalized text-to-image models overfitting to the input viewpoints of the
subject. We overcome this through a 3-stage optimization strategy where we
jointly leverage the 3D consistency of neural radiance fields together with the
personalization capability of text-to-image models. Our method can produce
high-quality, subject-specific 3D assets with text-driven modifications such as
novel poses, colors and attributes that are not seen in any of the input images
of the subject.