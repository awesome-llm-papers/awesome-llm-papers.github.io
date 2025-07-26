---
layout: publication
title: 'Partcrafter: Structured 3D Mesh Generation Via Compositional Latent Diffusion
  Transformers'
authors: Yuchen Lin, Chenguo Lin, Panwang Pan, Honglei Yan, Yiqiang Feng, Yadong Mu,
  Katerina Fragkiadaki
conference: No Venue
year: 2025
bibkey: lin2025partcrafter
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6846902a3ec10bdd8ab4db68'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.05573'}]
tags: ["Model Architecture"]
short_authors: Lin et al.
---
We introduce PartCrafter, the first structured 3D generative model that jointly synthesizes multiple semantically meaningful and geometrically distinct 3D meshes from a single RGB image. Unlike existing methods that either produce monolithic 3D shapes or follow two-stage pipelines, i.e., first segmenting an image and then reconstructing each segment, PartCrafter adopts a unified, compositional generation architecture that does not rely on pre-segmented inputs. Conditioned on a single image, it simultaneously denoises multiple 3D parts, enabling end-to-end part-aware generation of both individual objects and complex multi-object scenes. PartCrafter builds upon a pretrained 3D mesh diffusion transformer (DiT) trained on whole objects, inheriting the pretrained weights, encoder, and decoder, and introduces two key innovations: (1) A compositional latent space, where each 3D part is represented by a set of disentangled latent tokens; (2) A hierarchical attention mechanism that enables structured information flow both within individual parts and across all parts, ensuring global coherence while preserving part-level detail during generation. To support part-level supervision, we curate a new dataset by mining part-level annotations from large-scale 3D object datasets. Experiments show that PartCrafter outperforms existing approaches in generating decomposable 3D meshes, including parts that are not directly visible in input images, demonstrating the strength of part-aware generative priors for 3D understanding and synthesis. Code and training data will be released.

https://huggingface.co/discussions/paper/6846902a3ec10bdd8ab4db68