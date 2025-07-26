---
layout: publication
title: 'Talk-to-edit: Fine-grained Facial Editing Via Dialog'
authors: Yuming Jiang, Ziqi Huang, Xingang Pan, Chen Change Loy, Ziwei Liu
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2021
bibkey: jiang2021talk
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.04425'}]
tags: ["Applications", "ICCV"]
short_authors: Jiang et al.
---
Facial editing is an important task in vision and graphics with numerous
applications. However, existing works are incapable to deliver a continuous and
fine-grained editing mode (e.g., editing a slightly smiling face to a big
laughing one) with natural interactions with users. In this work, we propose
Talk-to-Edit, an interactive facial editing framework that performs
fine-grained attribute manipulation through dialog between the user and the
system. Our key insight is to model a continual "semantic field" in the GAN
latent space. 1) Unlike previous works that regard the editing as traversing
straight lines in the latent space, here the fine-grained editing is formulated
as finding a curving trajectory that respects fine-grained attribute landscape
on the semantic field. 2) The curvature at each step is location-specific and
determined by the input image as well as the users' language requests. 3) To
engage the users in a meaningful dialog, our system generates language feedback
by considering both the user request and the current state of the semantic
field.
  We also contribute CelebA-Dialog, a visual-language facial editing dataset to
facilitate large-scale study. Specifically, each image has manually annotated
fine-grained attribute annotations as well as template-based textual
descriptions in natural language. Extensive quantitative and qualitative
experiments demonstrate the superiority of our framework in terms of 1) the
smoothness of fine-grained editing, 2) the identity/attribute preservation, and
3) the visual photorealism and dialog fluency. Notably, user study validates
that our overall system is consistently favored by around 80% of the
participants. Our project page is https://www.mmlab-ntu.com/project/talkedit/.