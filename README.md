# Awesome-Multimodal-Spatio-Temporal-LLMs
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)
---
**Table of Content**
- [1. Surveys](#1-surveys)
- [2. Analysis](#2-analysis)
- [3. Models](#3-models)
- [4. Datasets](#4-datasets)
- [5. Benchmarks](#5-benchmarks)
- [6. Technologies](#6-technologies)
- [7. Other awesome](#7-other-awesome)
---

## 1. Surveys

|  Paper  |  Venue  |  Time  |  Link  | Notes |
|  :---:  |  :---:  |  :---: |  :---: | :---: |
| Knowledge Mechanisms in Large Language Models: A Survey and Perspective | Arxiv | 2024.07 | [Arxiv](https://arxiv.org/abs/2407.15017) | categorise the knowledge mechanism of LLMs as knowledge utilization and evolution. Knowledge utilization delves into the mechanism of memorization, comprehension and application, and creation. Knowledge evolution focuses on the dynamic progression of knowledge within individual and group LLMs. |
| When LLMs step into the 3D World: A Survey and Meta-Analysis of 3D Tasks via Multi-modal Large Language Models  | Arxiv | 2024.05 | [Arxiv](https://arxiv.org/abs/2405.10255) | introduce background knowledge of the 3D field and the revolutionary changes that LLM has brought to the field |
| Large Multimodal Agents: A Survey | Arxiv | 2024.02 | [Arxiv](https://arxiv.org/abs/2402.15116) |
| The Revolution of Multimodal Large Language Models: A Survey | ACL 2024 | V1:2024.02 - V2:2024.06 | [Arxiv](https://arxiv.org/abs/2402.12451) |

## 2. Analysis

## 3. Models
|  Name  |  Time  |  Modal  |  Params |  Link  |  Notes  |
|  :---: |  :---: |     :---:    |  :---:  | :---:  |  :---:  |
| MM1 | 2024.03 | V+L | 3B, 7B, 30B | [Paper](https://arxiv.org/abs/2403.09611), [Github](https://github.com/kyegomez/MM1) | Ablation experiments are performed on the model architecture decisions and pre-training data choices to determine the optimal configuration |

## 4. Datasets

| Datasets | Time | Modal | Scale | Annotation | Data sources | Link | Notes |
| :---: |  :---: | :---: |  :---:  | :---:  |  :---:  |  :---:  |  :---:  |
| FILIP300M | 2021.11 | V+L | 300M image-text pairs | image-text pairs | Internet | [Paper](https://arxiv.org/abs/2111.07783) | Removing the images whose shorter dimension is smaller than 200 pixels and the aspect ratio is larger than 3. Keeping only English texts, and excluding meaningless ones. Discarding image-text pairs whose texts are repeated over 10 times. |


## 5. Benchmarks

|  Name  |  Time  |  Task  | Link |
| :----: | :----: |  :---: | :---:|
| MMVP | 2024.01 | VQA for "CLIP-blind Pairs" | [Page](https://tsb0601.github.io/mmvp_blog/), [Paper](https://arxiv.org/abs/2401.06209), [Github](https://github.com/tsb0601/MMVP) <br> ![Star](https://img.shields.io/github/stars/tsb0601/MMVP.svg?style=social&label=Star) |
| MME | 2023.06 | 14 subtasks: Existence, Count, OCR, Poster, Celebrity, Commonsense Reasoning, Text Translation... | [Paper](https://arxiv.org/abs/2306.13394), [Github](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation) <br> ![Star](https://img.shields.io/github/stars/BradyFU/Awesome-Multimodal-Large-Language-Models.svg?style=social&label=Star) |
| Perception Test | 2023.05 | object tracking, point tracking, temporal action localisation, temporal sound localisation, multiple-choice video question-answering, grounded video question-answering | [Paper](https://arxiv.org/abs/2305.13786), [Github](https://github.com/google-deepmind/perception_test) <br> ![Star](https://img.shields.io/github/stars/google-deepmind/perception_test.svg?style=social&label=Star)

## 6. Technologies

## 7. Other awesome

|  Name  |  Link  |  Scope |
| :----: | :----: |  :---: |
| Awesome-LLM-Tabular | [Github](https://github.com/johnnyhwu/Awesome-LLM-Tabular) | Tabular, LLM |
| Awesome-LLM-3D | [Github](https://github.com/ActiveVisionLab/Awesome-LLM-3D) | 3D, LLM |