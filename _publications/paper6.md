---
title: "GeoAnalystBench: A GeoAI benchmark for assessing large language models for spatial analysis workflow and code generation"
collection: publications
category: manuscripts
permalink: /publication/2025-09-07-geoanalystbench
excerpt: "We introduce GeoAnalystBench, a benchmark of 50 Python-based geoprocessing tasks for evaluating large language models (LLMs) in geospatial analysis and GIS workflow automation. Our results reveal a significant performance gap between proprietary and open-source models, highlighting both the promise and current limitations of LLMs for GeoAI. <br/> <img src='/images/paper6.png' style='width:525px; height:400px;'>"
date: 2025-09-07
venue: 'arXiv, under review for Transaction in GIS'
paperurl: 'https://arxiv.org/pdf/2509.05881.pdf'
authors:
  - Qianheng Zhang
  - Song Gao
  - Chen Wei
  - Yibo Zhao
  - Ying Nie
  - Ziru Chen
  - Shijie Chen
  - Yu Su
  - Huan Sun

---

**Authors:**
Qianheng Zhang, Song Gao, Chen Wei, Yibo Zhao, Ying Nie, Ziru Chen, Shijie Chen, Yu Su, Huan Sun

**Publication date:** 2025/9/7
**Journal:** arXiv preprint arXiv:2509.05881
**PDF:** [Available from arXiv](https://arxiv.org/pdf/2509.05881.pdf)

**Description:**
Recent advances in large language models (LLMs) have fueled growing interest in automating geospatial analysis and GIS workflows, yet their actual capabilities remain uncertain. In this work, we call for rigorous evaluation of LLMs on well-defined geoprocessing tasks before making claims about full GIS automation. To this end, we present GeoAnalystBench, a benchmark of 50 Python-based tasks derived from real-world geospatial problems and carefully validated by GIS experts. Each task is paired with a minimum deliverable product, and evaluation covers workflow validity, structural alignment, semantic similarity, and code quality (CodeBLEU). Using this benchmark, we assess both proprietary and open source models. Results reveal a clear gap: proprietary models such as ChatGPT-4o-mini achieve high validity (95%) and stronger code alignment (CodeBLEU 0.39), while smaller open source models like DeepSeek-R1-7B often generate incomplete or inconsistent workflows (48.5% validity, 0.272 CodeBLEU). Tasks requiring deeper spatial reasoning, such as spatial relationship detection or optimal site selection, remain the most challenging across all models. These findings demonstrate both the promise and limitations of current LLMs in GIS automation and provide a reproducible framework to advance GeoAI research with human-in-the-loop support.
