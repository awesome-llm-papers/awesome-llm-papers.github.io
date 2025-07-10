---
layout: publication
title: Language Models Can Solve Computer Tasks
authors: Geunwoo Kim, Pierre Baldi, Stephen Mcaleer
conference: Arxiv
year: 2023
citations: 55
bibkey: kim2023language
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.17491'}, {name: Code,
    url: 'https://github.com/posgnu/rci-agent'}]
tags: [Has Code, Model Architecture, Reinforcement Learning, Prompting, Agentic, Efficiency
    and Optimization, GPT, Evaluation]
---
Agents capable of carrying out general tasks on a computer can improve
efficiency and productivity by automating repetitive tasks and assisting in
complex problem-solving. Ideally, such agents should be able to solve new
computer tasks presented to them through natural language commands. However,
previous approaches to this problem require large amounts of expert
demonstrations and task-specific reward functions, both of which are
impractical for new tasks. In this work, we show that a pre-trained large
language model (LLM) agent can execute computer tasks guided by natural
language using a simple prompting scheme where the agent Recursively Criticizes
and Improves its output (RCI). The RCI approach significantly outperforms
existing LLM methods for automating computer tasks and surpasses supervised
learning (SL) and reinforcement learning (RL) approaches on the MiniWoB++
benchmark. We compare multiple LLMs and find that RCI with the
InstructGPT-3+RLHF LLM is state-of-the-art on MiniWoB++, using only a handful
of demonstrations per task rather than tens of thousands, and without a
task-specific reward function. Furthermore, we demonstrate RCI prompting's
effectiveness in enhancing LLMs' reasoning abilities on a suite of natural
language reasoning tasks, outperforming chain of thought (CoT) prompting with
external feedback. We find that RCI combined with CoT performs better than
either separately. Our code can be found here:
https://github.com/posgnu/rci-agent.