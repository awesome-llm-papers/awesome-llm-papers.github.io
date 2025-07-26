---
layout: publication
title: 'Lcm-lora: A Universal Stable-diffusion Acceleration Module'
authors: "Simian Luo, Yiqin Tan, Suraj Patil, Daniel Gu, Patrick von Platen, Apolin\xE1\
  rio Passos, Longbo Huang, Jian Li, Hang Zhao"
conference: No Venue
year: 2023
bibkey: luo2023lcm
additional_links: [{name: Code, url: 'https://github.com/luosiallen/latent-consistency-model'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/654d9b6af714720ae27e335f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2311.05556'}]
tags: ["Efficiency", "Has Code"]
short_authors: Luo et al.
---
Latent Consistency Models (LCMs) have achieved impressive performance in accelerating text-to-image generative tasks, producing high-quality images with minimal inference steps. LCMs are distilled from pre-trained latent diffusion models (LDMs), requiring only ~32 A100 GPU training hours. This report further extends LCMs' potential in two aspects: First, by applying LoRA distillation to Stable-Diffusion models including SD-V1.5, SSD-1B, and SDXL, we have expanded LCM's scope to larger models with significantly less memory consumption, achieving superior image generation quality. Second, we identify the LoRA parameters obtained through LCM distillation as a universal Stable-Diffusion acceleration module, named LCM-LoRA. LCM-LoRA can be directly plugged into various Stable-Diffusion fine-tuned models or LoRAs without training, thus representing a universally applicable accelerator for diverse image generation tasks. Compared with previous numerical PF-ODE solvers such as DDIM, DPM-Solver, LCM-LoRA can be viewed as a plug-in neural PF-ODE solver that possesses strong generalization abilities. Project page: https://github.com/luosiallen/latent-consistency-model.

https://huggingface.co/discussions/paper/654d9b6af714720ae27e335f