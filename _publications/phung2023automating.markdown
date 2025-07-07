---
layout: publication
title: 'Automating Human Tutor-style Programming Feedback: Leveraging GPT-4 Tutor
  Model For Hint Generation And GPT-3.5 Student Model For Hint Validation'
authors: Tung Phung et al.
conference: Arxiv
year: 2023
citations: 17
bibkey: phung2023automating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.03780'}]
tags: [GPT, RAG, Tools, Reinforcement Learning, Prompting, Model Architecture]
---
Generative AI and large language models hold great promise in enhancing
programming education by automatically generating individualized feedback for
students. We investigate the role of generative AI models in providing human
tutor-style programming hints to help students resolve errors in their buggy
programs. Recent works have benchmarked state-of-the-art models for various
feedback generation scenarios; however, their overall quality is still inferior
to human tutors and not yet ready for real-world deployment. In this paper, we
seek to push the limits of generative AI models toward providing high-quality
programming hints and develop a novel technique, GPT4Hints-GPT3.5Val. As a
first step, our technique leverages GPT-4 as a ``tutor'' model to generate
hints -- it boosts the generative quality by using symbolic information of
failing test cases and fixes in prompts. As a next step, our technique
leverages GPT-3.5, a weaker model, as a ``student'' model to further validate
the hint quality -- it performs an automatic quality validation by simulating
the potential utility of providing this feedback. We show the efficacy of our
technique via extensive evaluation using three real-world datasets of Python
programs covering a variety of concepts ranging from basic algorithms to
regular expressions and data analysis using pandas library.