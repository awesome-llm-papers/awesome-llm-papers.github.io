---
layout: publication
title: 'Inserf: Text-driven Generative Object Insertion In Neural 3D Scenes'
authors: Mohamad Shahbazi, Liesbeth Claessens, Michael Niemeyer, Edo Collins, Alessio
  Tonioni, Luc van Gool, Federico Tombari
conference: No Venue
year: 2024
bibkey: shahbazi2024inserf
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.05335'}]
tags: ["Has Code"]
short_authors: Shahbazi et al.
---
We introduce InseRF, a novel method for generative object insertion in the NeRF reconstructions of 3D scenes. Based on a user-provided textual description and a 2D bounding box in a reference viewpoint, InseRF generates new objects in 3D scenes. Recently, methods for 3D scene editing have been profoundly transformed, owing to the use of strong priors of text-to-image diffusion models in 3D generative modeling. Existing methods are mostly effective in editing 3D scenes via style and appearance changes or removing existing objects. Generating new objects, however, remains a challenge for such methods, which we address in this study. Specifically, we propose grounding the 3D object insertion to a 2D object insertion in a reference view of the scene. The 2D edit is then lifted to 3D using a single-view object reconstruction method. The reconstructed object is then inserted into the scene, guided by the priors of monocular depth estimation methods. We evaluate our method on various 3D scenes and provide an in-depth analysis of the proposed components. Our experiments with generative insertion of objects in several 3D scenes indicate the effectiveness of our method compared to the existing methods. InseRF is capable of controllable and 3D-consistent object insertion without requiring explicit 3D information as input. Please visit our project page at https://mohamad-shahbazi.github.io/inserf.

https://huggingface.co/discussions/paper/659f66589f682a3147bd7f16