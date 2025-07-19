---
layout: publication
title: 'YODA: Teacher-student Progressive Learning For Language Models'
authors: Lu et al.
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: lu2024yoda
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.15670'}]
tags: [Training Techniques, Alt, Agentic, Tools, CVPR, Efficiency And Optimization,
  Security, Fine Tuning]
---
Although large language models (LLMs) have demonstrated adeptness in a range
of tasks, they still lag behind human learning efficiency. This disparity is
often linked to the inherent human capacity to learn from basic examples,
gradually generalize and handle more complex problems, and refine their skills
with continuous feedback. Inspired by this, this paper introduces YODA, a novel
teacher-student progressive learning framework that emulates the
teacher-student education process to improve the efficacy of model fine-tuning.
The framework operates on an interactive \textit\{basic-generalized-harder\}
loop. The teacher agent provides tailored feedback on the student's answers,
and systematically organizes the education process. This process unfolds by
teaching the student basic examples, reinforcing understanding through
generalized questions, and then enhancing learning by posing questions with
progressively enhanced complexity. With the teacher's guidance, the student
learns to iteratively refine its answer with feedback, and forms a robust and
comprehensive understanding of the posed questions. The systematic procedural
data, which reflects the progressive learning process of humans, is then
utilized for model training. Taking math reasoning as a testbed, experiments
show that training LLaMA2 with data from YODA improves SFT with significant
performance gain (+17.01% on GSM8K and +9.98% on MATH). In addition, we find
that training with curriculum learning further improves learning robustness.