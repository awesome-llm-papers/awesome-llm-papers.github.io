---
layout: publication
title: 'Imagen Editor And Editbench: Advancing And Evaluating Text-guided Image Inpainting'
authors: Wang et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: wang2022imagen
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.06909'}]
tags: [Training Techniques, Prompting, CVPR, Evaluation, Reinforcement Learning, Applications,
  Fine Tuning, Datasets, Merging]
---
Text-guided image editing can have a transformative impact in supporting
creative applications. A key challenge is to generate edits that are faithful
to input text prompts, while consistent with input images. We present Imagen
Editor, a cascaded diffusion model built, by fine-tuning Imagen on text-guided
image inpainting. Imagen Editor's edits are faithful to the text prompts, which
is accomplished by using object detectors to propose inpainting masks during
training. In addition, Imagen Editor captures fine details in the input image
by conditioning the cascaded pipeline on the original high resolution image. To
improve qualitative and quantitative evaluation, we introduce EditBench, a
systematic benchmark for text-guided image inpainting. EditBench evaluates
inpainting edits on natural and generated images exploring objects, attributes,
and scenes. Through extensive human evaluation on EditBench, we find that
object-masking during training leads to across-the-board improvements in
text-image alignment -- such that Imagen Editor is preferred over DALL-E 2 and
Stable Diffusion -- and, as a cohort, these models are better at
object-rendering than text-rendering, and handle material/color/size attributes
better than count/shape attributes.