---
layout: publication
title: 'Brightdreamer: Generic 3D Gaussian Generative Framework For Fast Text-to-3d
  Synthesis'
authors: Jiang et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: jiang2024brightdreamer
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.11273'}]
tags: [Distillation, Prompting, Tools, CVPR, Efficiency And Optimization, TACL]
---
Text-to-3D synthesis has recently seen intriguing advances by combining the
text-to-image priors with 3D representation methods, e.g., 3D Gaussian
Splatting (3D GS), via Score Distillation Sampling (SDS). However, a hurdle of
existing methods is the low efficiency, per-prompt optimization for a single 3D
object. Therefore, it is imperative for a paradigm shift from per-prompt
optimization to feed-forward generation for any unseen text prompts, which yet
remains challenging. An obstacle is how to directly generate a set of millions
of 3D Gaussians to represent a 3D object. This paper presents BrightDreamer, an
end-to-end feed-forward approach that can achieve generalizable and fast (77
ms) text-to-3D generation. Our key idea is to formulate the generation process
as estimating the 3D deformation from an anchor shape with predefined
positions. For this, we first propose a Text-guided Shape Deformation (TSD)
network to predict the deformed shape and its new positions, used as the
centers (one attribute) of 3D Gaussians. To estimate the other four attributes
(i.e., scaling, rotation, opacity, and SH), we then design a novel Text-guided
Triplane Generator (TTG) to generate a triplane representation for a 3D object.
The center of each Gaussian enables us to transform the spatial feature into
the four attributes. The generated 3D Gaussians can be finally rendered at 705
frames per second. Extensive experiments demonstrate the superiority of our
method over existing methods. Also, BrightDreamer possesses a strong semantic
understanding capability even for complex text prompts. The code is available
in the project page.