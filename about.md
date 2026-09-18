---
layout: default
title: About Me
permalink: /about/
---
&#x1F4E7; liujianhua1000@gmail.com

## Experience

**Tsinghua University**, Research Intern  
Apr 2026 – Jul 2026

**VIVO**, *Image Algorithm Engineer*  A
Jul 2025 – Mar 2026

**University of Chinese Academy of Sciences (US-News Rank:54[2026])**  
Master in Electronic Information  
Sep 2022 – Jun 2025

**Zhengzhou University (US-News Rank:203[2026])**  
Bachelor in Software Engineering  
Sep 2018 – Jun 2022

## Projects

**CER: Compositional Evidence-Guided Ranking for Referring Expression Comprehension**
- Addressed the condition competition bottleneck in visual-language grounding, where multiple constraints are compressed into a single candidate-matching score.
- Proposed a Compositional Evidence-Guided Ranking (CER) framework that builds a compact target-category shortlist and evaluates each candidate region against fine-grained linguistic conditions.
- Encoded candidate–condition matching outcomes as structured evidence features and used a global gradient-boosted decision tree (GBDT) ranker for candidate re-ranking.
- Evaluated the method on FineCops, Cops-Ref, and Ref-Adv; with a 2B grounding backbone, outperformed Qwen3.6-35B-A3B by 4.34–7.27 points and achieved 60.95% accuracy on Ref-Adv.

**TravelPlannerAgent — RL Adaptation of an Open-Source Multi-Tool Planning Agent**
- Built a ReAct-based loop integrating reasoning, tool calling, and environmental feedback. Connected six categories of query tools, including flights, hotels, and restaurants, to support multi-step information gathering and itinerary generation. Evaluated factual consistency and constraint satisfaction through structured parsing and rule-based validation.
- Designed a data-synthesis pipeline consisting of travel-element sampling, feasibility checking, and natural language request generation. Controlled task difficulty based on the number and types of constraints. Used a teacher model (DeepSeek-V4-Pro-Thinking) to generate trajectories, filtered high-quality samples based on task success and format validation, and conducted SFT cold-start training for Qwen3.5-4B.
- Integrated GRPO through rLLM and adopted a staged reward strategy of SUM → MACRO → SUCCESS. Combined this strategy with penalties for formatting errors to improve the effectiveness and stability of long-trajectory training.
- On 1,000 independent test samples, the agentic task success rate (pass@1) improved from 2.7% for the base model and 16.8% after SFT to 51.3% after GRPO training.

**Hierarchical ROI Graph Reasoning for Visual Grounding**
- Built a VLM agent for complex visual referring expressions, formulating grounding as a multi-step workflow: expression understanding, graph-tool invocation, candidate verification, and target localization.
- Constructed a hierarchical ROI graph and graph-query tools to retrieve structured visual context, including
object attributes, spatial relations, and containment relations.
- Implemented intermediate-result-aware candidate backtracking and constraint verification, producing interpretable reasoning traces; integrated and evaluated Groma and Qwen3-VL backbones under a unified
pipeline

**Unsupervised Spectral-Spatial Feature Learning via Deep Residual Conv-Deconv Networks for Medical Applications**

- Learned feature representations in the remote sensing domain using an encoder-decoder architecture
- Added output network layers after the encoder for fine-tuning on downstream medical tasks
- Used ResNet optimization to accelerate training and resolve gradient and overfitting issues

**Hyperspectral Tumor Image Recognition via Feature Fusion**

- Enhanced hyperspectral image classification through multi-dimensional feature fusion (spectral bands, spectral indices, spatial information)
- Demonstrated effectiveness and stability across multiple models and datasets
- Achieved 95% accuracy in few-shot learning scenarios (5-pixel training)

## Publications & Achievements

**Papers:**

- *CER: Compositional Evidence-Guided Ranking for Referring Expression Comprehension* (Submitted to AAAI 2027, co-first author)
- *Hyperspectral imaging for intraoperative brain tumor identification through fusion of spectral, textural, and spectral index features* (JCR Q2, first author)

**Patents:**

- 2 first-author patents, 3 non-first-author patents

**Software Copyrights:**

- 1 first-author copyright
- 1 second-author copyright

## Other

**Skills:**

- Languages & Frameworks: Python, PyTorch, Matlab, Java
- Research Interests: MLLM, Agent, Image Generation

**Internships:**

- Zhengzhou Research Institute of HIT (HarmonyOS)
- Sensus Software Company (Frontend Development)

**Scholarships:**

- UCAS Second-Class Scholarship
- Zhengzhou University Third-Class Scholarship

**Competitions:**

- UCAS HASI Graduate Innovation & Entrepreneurship Competition – Excellence Award
- National College Computer Ability Challenge – Central China Second Prize
