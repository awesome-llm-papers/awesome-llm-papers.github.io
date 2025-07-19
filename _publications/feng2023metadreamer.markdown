---
layout: publication
title: 'Metadreamer: Efficient Text-to-3d Creation With Disentangling Geometry And
  Texture'
authors: Feng et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2023
bibkey: feng2023metadreamer
citations: 185
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.10123'}]
tags: [RAG, ICCV, Training Techniques, Prompting, Tools, Efficiency And Optimization,
  Fine Tuning, Merging]
---
Generative models for 3D object synthesis have seen significant advancements
with the incorporation of prior knowledge distilled from 2D diffusion models.
Nevertheless, challenges persist in the form of multi-view geometric
inconsistencies and slow generation speeds within the existing 3D synthesis
frameworks. This can be attributed to two factors: firstly, the deficiency of
abundant geometric a priori knowledge in optimization, and secondly, the
entanglement issue between geometry and texture in conventional 3D generation
methods.In response, we introduce MetaDreammer, a two-stage optimization
approach that leverages rich 2D and 3D prior knowledge. In the first stage, our
emphasis is on optimizing the geometric representation to ensure multi-view
consistency and accuracy of 3D objects. In the second stage, we concentrate on
fine-tuning the geometry and optimizing the texture, thereby achieving a more
refined 3D object. Through leveraging 2D and 3D prior knowledge in two stages,
respectively, we effectively mitigate the interdependence between geometry and
texture. MetaDreamer establishes clear optimization objectives for each stage,
resulting in significant time savings in the 3D generation process. Ultimately,
MetaDreamer can generate high-quality 3D objects based on textual prompts
within 20 minutes, and to the best of our knowledge, it is the most efficient
text-to-3D generation method. Furthermore, we introduce image control into the
process, enhancing the controllability of 3D generation. Extensive empirical
evidence confirms that our method is not only highly efficient but also
achieves a quality level that is at the forefront of current state-of-the-art
3D generation techniques.