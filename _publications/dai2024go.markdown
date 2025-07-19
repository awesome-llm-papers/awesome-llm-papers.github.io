---
layout: publication
title: 'Go-nerf: Generating Objects In Neural Radiance Fields For Virtual Reality
  Content Creation'
authors: Dai et al.
conference: IEEE Transactions on Visualization and Computer Graphics
year: 2024
bibkey: dai2024go
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.05750'}]
tags: [Prompting, RAG, Training Techniques, Efficiency And Optimization]
---
Virtual environments (VEs) are pivotal for virtual, augmented, and mixed
reality systems. Despite advances in 3D generation and reconstruction, the
direct creation of 3D objects within an established 3D scene (represented as
NeRF) for novel VE creation remains a relatively unexplored domain. This
process is complex, requiring not only the generation of high-quality 3D
objects but also their seamless integration into the existing scene. To this
end, we propose a novel pipeline featuring an intuitive interface, dubbed
GO-NeRF. Our approach takes text prompts and user-specified regions as inputs
and leverages the scene context to generate 3D objects within the scene. We
employ a compositional rendering formulation that effectively integrates the
generated 3D objects into the scene, utilizing optimized 3D-aware opacity maps
to avoid unintended modifications to the original scene. Furthermore, we
develop tailored optimization objectives and training strategies to enhance the
model's ability to capture scene context and mitigate artifacts, such as
floaters, that may occur while optimizing 3D objects within the scene.
Extensive experiments conducted on both forward-facing and 360o scenes
demonstrate the superior performance of our proposed method in generating
objects that harmonize with surrounding scenes and synthesizing high-quality
novel view images. We are committed to making our code publicly available.