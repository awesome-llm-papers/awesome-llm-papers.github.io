---
layout: publication
title: 'LERF: Language Embedded Radiance Fields'
authors: Justin Kerr, Chung Min Kim, Ken Goldberg, Angjoo Kanazawa, Matthew Tancik
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2023
bibkey: kerr2023lerf
citations: 122
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.09553'}]
tags: ["Applications", "ICCV"]
short_authors: Kerr et al.
---
Humans describe the physical world using natural language to refer to
specific 3D locations based on a vast range of properties: visual appearance,
semantics, abstract associations, or actionable affordances. In this work we
propose Language Embedded Radiance Fields (LERFs), a method for grounding
language embeddings from off-the-shelf models like CLIP into NeRF, which enable
these types of open-ended language queries in 3D. LERF learns a dense,
multi-scale language field inside NeRF by volume rendering CLIP embeddings
along training rays, supervising these embeddings across training views to
provide multi-view consistency and smooth the underlying language field. After
optimization, LERF can extract 3D relevancy maps for a broad range of language
prompts interactively in real-time, which has potential use cases in robotics,
understanding vision-language models, and interacting with 3D scenes. LERF
enables pixel-aligned, zero-shot queries on the distilled 3D CLIP embeddings
without relying on region proposals or masks, supporting long-tail
open-vocabulary queries hierarchically across the volume. The project website
can be found at https://lerf.io .