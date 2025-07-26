---
layout: publication
title: 'Dita: Scaling Diffusion Transformer For Generalist Vision-language-action
  Policy'
authors: Zhi Hou, Tianyi Zhang, Yuwen Xiong, Haonan Duan, Hengjun Pu, Ronglei Tong,
  Chengyang Zhao, Xizhou Zhu, Yu Qiao, Jifeng Dai, Yuntao Chen
conference: No Venue
year: 2025
bibkey: hou2025dita
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.19757'}]
tags: ["Model Architecture", "Tools"]
short_authors: Hou et al.
---
While recent vision-language-action models trained on diverse robot datasets exhibit promising generalization capabilities with limited in-domain data, their reliance on compact action heads to predict discretized or continuous actions constrains adaptability to heterogeneous action spaces. We present Dita, a scalable framework that leverages Transformer architectures to directly denoise continuous action sequences through a unified multimodal diffusion process. Departing from prior methods that condition denoising on fused embeddings via shallow networks, Dita employs in-context conditioning -- enabling fine-grained alignment between denoised actions and raw visual tokens from historical observations. This design explicitly models action deltas and environmental nuances. By scaling the diffusion action denoiser alongside the Transformer's scalability, Dita effectively integrates cross-embodiment datasets across diverse camera perspectives, observation scenes, tasks, and action spaces. Such synergy enhances robustness against various variances and facilitates the successful execution of long-horizon tasks. Evaluations across extensive benchmarks demonstrate state-of-the-art or comparative performance in simulation. Notably, Dita achieves robust real-world adaptation to environmental variances and complex long-horizon tasks through 10-shot finetuning, using only third-person camera inputs. The architecture establishes a versatile, lightweight and open-source baseline for generalist robot policy learning. Project Page: https://robodita.github.io.

https://huggingface.co/discussions/paper/67e3e1e40706b07bfb2714cd