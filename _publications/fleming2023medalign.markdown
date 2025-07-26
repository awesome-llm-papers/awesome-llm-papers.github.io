---
layout: publication
title: 'Medalign: A Clinician-generated Dataset For Instruction Following With Electronic
  Medical Records'
authors: Scott L. Fleming, Alejandro Lozano, William J. Haberkorn, Jenelle A. Jindal,
  Eduardo P. Reis, Rahul Thapa, Louis Blankemeier, Julian Z. Genkins, Ethan Steinberg,
  Ashwin Nayak, Birju S. Patel, Chia-chun Chiang, Alison Callahan, Zepeng Huo, Sergios
  Gatidis, Scott J. Adams, Oluseyi Fayanju, Shreya J. Shah, Thomas Savage, Ethan Goh,
  Akshay S. Chaudhari, Nima Aghaeepour, Christopher Sharp, Michael A. Pfeffer, Percy
  Liang, Jonathan H. Chen, Keith E. Morse, Emma P. Brunskill, Jason A. Fries, Nigam
  H. Shah
conference: No Venue
year: 2023
bibkey: fleming2023medalign
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/64eddd370a4f28000c596a34'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2308.14089'}]
tags: ["Datasets", "Instruction Following"]
short_authors: Fleming et al.
---
The ability of large language models (LLMs) to follow natural language instructions with human-level fluency suggests many opportunities in healthcare to reduce administrative burden and improve quality of care. However, evaluating LLMs on realistic text generation tasks for healthcare remains challenging. Existing question answering datasets for electronic health record (EHR) data fail to capture the complexity of information needs and documentation burdens experienced by clinicians. To address these challenges, we introduce MedAlign, a benchmark dataset of 983 natural language instructions for EHR data. MedAlign is curated by 15 clinicians (7 specialities), includes clinician-written reference responses for 303 instructions, and provides 276 longitudinal EHRs for grounding instruction-response pairs. We used MedAlign to evaluate 6 general domain LLMs, having clinicians rank the accuracy and quality of each LLM response. We found high error rates, ranging from 35% (GPT-4) to 68% (MPT-7B-Instruct), and an 8.3% drop in accuracy moving from 32k to 2k context lengths for GPT-4. Finally, we report correlations between clinician rankings and automated natural language generation metrics as a way to rank LLMs without human review. We make MedAlign available under a research data use agreement to enable LLM evaluations on tasks aligned with clinician needs and preferences.

https://huggingface.co/discussions/paper/64eddd370a4f28000c596a34