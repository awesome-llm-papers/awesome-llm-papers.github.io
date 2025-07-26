---
layout: publication
title: 'Paint By Inpaint: Learning To Add Image Objects By Removing Them First'
authors: Navve Wasserman, Noam Rotstein, Roy Ganz, Ron Kimmel
conference: No Venue
year: 2024
bibkey: wasserman2024paint
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.18212'}]
tags: ["Datasets"]
short_authors: Wasserman et al.
---
Image editing has advanced significantly with the introduction of text-conditioned diffusion models. Despite this progress, seamlessly adding objects to images based on textual instructions without requiring user-provided input masks remains a challenge. We address this by leveraging the insight that removing objects (Inpaint) is significantly simpler than its inverse process of adding them (Paint), attributed to the utilization of segmentation mask datasets alongside inpainting models that inpaint within these masks. Capitalizing on this realization, by implementing an automated and extensive pipeline, we curate a filtered large-scale image dataset containing pairs of images and their corresponding object-removed versions. Using these pairs, we train a diffusion model to inverse the inpainting process, effectively adding objects into images. Unlike other editing datasets, ours features natural target images instead of synthetic ones; moreover, it maintains consistency between source and target by construction. Additionally, we utilize a large Vision-Language Model to provide detailed descriptions of the removed objects and a Large Language Model to convert these descriptions into diverse, natural-language instructions. We show that the trained model surpasses existing ones both qualitatively and quantitatively, and release the large-scale dataset alongside the trained models for the community.

https://huggingface.co/discussions/paper/66308f0af0879eea6d52ebb9