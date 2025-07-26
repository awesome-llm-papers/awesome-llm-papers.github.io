---
layout: publication
title: 'Tidybot: Personalized Robot Assistance With Large Language Models'
authors: Jimmy Wu, Rika Antonova, Adam Kan, Marion Lepert, Andy Zeng, Shuran Song,
  Jeannette Bohg, Szymon Rusinkiewicz, Thomas Funkhouser
conference: Autonomous Robots
year: 2023
bibkey: wu2023tidybot
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.05658'}]
tags: ["Datasets", "Evaluation", "Few-Shot"]
short_authors: Wu et al.
---
For a robot to personalize physical assistance effectively, it must learn
user preferences that can be generally reapplied to future scenarios. In this
work, we investigate personalization of household cleanup with robots that can
tidy up rooms by picking up objects and putting them away. A key challenge is
determining the proper place to put each object, as people's preferences can
vary greatly depending on personal taste or cultural background. For instance,
one person may prefer storing shirts in the drawer, while another may prefer
them on the shelf. We aim to build systems that can learn such preferences from
just a handful of examples via prior interactions with a particular person. We
show that robots can combine language-based planning and perception with the
few-shot summarization capabilities of large language models (LLMs) to infer
generalized user preferences that are broadly applicable to future
interactions. This approach enables fast adaptation and achieves 91.2% accuracy
on unseen objects in our benchmark dataset. We also demonstrate our approach on
a real-world mobile manipulator called TidyBot, which successfully puts away
85.0% of objects in real-world test scenarios.