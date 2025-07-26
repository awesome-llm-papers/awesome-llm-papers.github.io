---
layout: publication
title: 'Taking A HINT: Leveraging Explanations To Make Vision And Language Models
  More Grounded'
authors: Ramprasaath R. Selvaraju, Stefan Lee, Yilin Shen, Hongxia Jin, Shalini Ghosh,
  Larry Heck, Dhruv Batra, Devi Parikh
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2019
bibkey: selvaraju2019taking
citations: 228
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.03751'}]
tags: ["ICCV"]
short_authors: Selvaraju et al.
---
Many vision and language models suffer from poor visual grounding - often
falling back on easy-to-learn language priors rather than basing their
decisions on visual concepts in the image. In this work, we propose a generic
approach called Human Importance-aware Network Tuning (HINT) that effectively
leverages human demonstrations to improve visual grounding. HINT encourages
deep networks to be sensitive to the same input regions as humans. Our approach
optimizes the alignment between human attention maps and gradient-based network
importances - ensuring that models learn not just to look at but rather rely on
visual concepts that humans found relevant for a task when making predictions.
We apply HINT to Visual Question Answering and Image Captioning tasks,
outperforming top approaches on splits that penalize over-reliance on language
priors (VQA-CP and robust captioning) using human attention demonstrations for
just 6% of the training data.