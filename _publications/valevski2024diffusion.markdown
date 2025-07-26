---
layout: publication
title: Diffusion Models Are Real-time Game Engines
authors: Dani Valevski, Yaniv Leviathan, Moab Arar, Shlomi Fruchter
conference: No Venue
year: 2024
bibkey: valevski2024diffusion
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2408.14837'}]
tags: ["Agentic", "Reinforcement Learning", "Training Techniques"]
short_authors: Valevski et al.
---
We present GameNGen, the first game engine powered entirely by a neural model that enables real-time interaction with a complex environment over long trajectories at high quality. GameNGen can interactively simulate the classic game DOOM at over 20 frames per second on a single TPU. Next frame prediction achieves a PSNR of 29.4, comparable to lossy JPEG compression. Human raters are only slightly better than random chance at distinguishing short clips of the game from clips of the simulation. GameNGen is trained in two phases: (1) an RL-agent learns to play the game and the training sessions are recorded, and (2) a diffusion model is trained to produce the next frame, conditioned on the sequence of past frames and actions. Conditioning augmentations enable stable auto-regressive generation over long trajectories.

https://huggingface.co/discussions/paper/66ce94d4d3d85430b7ce0772