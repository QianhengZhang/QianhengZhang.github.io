---
title: "ScienceAgentBench: Toward rigorous assessment of language agents for data-driven scientific discovery"
collection: publications
category: conferences
permalink: /publication/2025-04-28-scienceagentbench
excerpt: "We present ScienceAgentBench, a new benchmark for evaluating language agents for data-driven scientific discovery. ScienceAgentBench consists of 102 tasks extracted from 44 peer-reviewed publications across four disciplines, validated by nine subject matter experts. Each task requires generating a self-contained Python program, and is evaluated using multiple metrics on program correctness, execution, and cost. We assess five open-weight and proprietary LLMs with three frameworks, finding that the best-performing agent solves only 32.4% of tasks independently and 34.3% with expert knowledge. Our results highlight the need for rigorous, task-level assessment before making claims about end-to-end scientific automation."
date: 2025-04-28
venue: 'ICLR 2025'
paperurl: 'https://arxiv.org/abs/2410.05080'

authors:
  - Ziru Chen
  - Shijie Chen
  - Yuting Ning
  - Qianheng Zhang
  - Boshi Wang
  - Botao Yu
  - Yifei Li
  - Zeyi Liao
  - Chen Wei
  - Zitong Lu
  - Vishal Dey
  - Mingyi Xue
  - Frazier N Baker
  - Benjamin Burns
  - Daniel Adu-Ampratwum
  - Xuhui Huang
  - Xia Ning
  - Song Gao
  - Yu Su
  - Huan Sun
---

**Authors:**
Ziru Chen, Shijie Chen, Yuting Ning, Qianheng Zhang, Boshi Wang, Botao Yu, Yifei Li, Zeyi Liao, Chen Wei, Zitong Lu, Vishal Dey, Mingyi Xue, Frazier N Baker, Benjamin Burns, Daniel Adu-Ampratwum, Xuhui Huang, Xia Ning, Song Gao, Yu Su, Huan Sun

**Publication date:** 2025/4/28
**Journal:** ICLR 2025

**Description:**
The advancements of large language models (LLMs) have piqued growing interest in developing LLM-based language agents to automate scientific discovery end-to-end, which has sparked both excitement and skepticism about their true capabilities. In this work, we call for rigorous assessment of agents on individual tasks in a scientific workflow before making bold claims on end-to-end automation. To this end, we present ScienceAgentBench, a new benchmark for evaluating language agents for data-driven scientific discovery. To ensure the scientific authenticity and real-world relevance of our benchmark, we extract 102 tasks from 44 peer-reviewed publications in four disciplines and engage nine subject matter experts to validate them. We unify the target output for every task to a self-contained Python program file and employ an array of evaluation metrics to examine the generated programs, execution results, and costs. Each task goes through multiple rounds of manual validation by annotators and subject matter experts to ensure its annotation quality and scientific plausibility. We also propose two effective strategies to mitigate data contamination concerns. Using ScienceAgentBench, we evaluate five open-weight and proprietary LLMs, each with three frameworks: direct prompting, OpenHands CodeAct, and self-debug. Given three attempts for each task, the best-performing agent can only solve 32.4% of the tasks independently and 34.3% with expert-provided knowledge. In addition, we evaluate OpenAI o1-preview with direct prompting and self-debug, which can boost the performance to 42.2%, demonstrating the effectiveness of the approach.

