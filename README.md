# Awesome-Multimodal-Spatio-Temporal-LLMs
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)
![visitors](https://visitor-badge.laobi.icu/badge?page_id=Hjopsen.Awesome-Multimodal-Spatio-Temporal-LLMs)

## :seedling: How to participate in this awesome

You are welcome to add new multimodal works, fix errors, or make any other modifications that help make this awesome more useful or interesting. Click [here](./CONTRIBUTION.md) to find the contribution tutorial. We promise that your pull requests will be processed within **24 hours**. Thank you for your contributions.

## :star: Table of Content
- [1. Surveys](#1-surveys)
- [2. Analysis](#2-analysis)
- [3. Models](#3-models)
- [4. Datasets](#4-datasets)
- [5. Benchmarks](#5-benchmarks)
- [6. Technologies](#6-technologies)
- [7. Other awesome](#7-other-awesome)

## 1. Surveys

|  Paper  |  Venue  |  Time  |  Link  | Notes |
|  :---:  |  :---:  |  :---: |  :---: | :---: |
| Knowledge Mechanisms in Large Language Models: A Survey and Perspective | Arxiv | 2024.07 | [Arxiv](https://arxiv.org/abs/2407.15017) | categorise the knowledge mechanism of LLMs as knowledge utilization and evolution. Knowledge utilization delves into the mechanism of memorization, comprehension and application, and creation. Knowledge evolution focuses on the dynamic progression of knowledge within individual and group LLMs. |
| When LLMs step into the 3D World: A Survey and Meta-Analysis of 3D Tasks via Multi-modal Large Language Models  | Arxiv | 2024.05 | [Arxiv](https://arxiv.org/abs/2405.10255) | introduce background knowledge of the 3D field and the revolutionary changes that LLM has brought to the field |
| Large Multimodal Agents: A Survey | Arxiv | 2024.02 | [Arxiv](https://arxiv.org/abs/2402.15116) | :clock1: Coming soon... |
| The Revolution of Multimodal Large Language Models: A Survey | ACL 2024 | V1:2024.02 - V2:2024.06 | [Arxiv](https://arxiv.org/abs/2402.12451) | :clock1: Coming soon... |
| MM-LLMs: Recent Advances in MultiModal Large Language Models | ACL 2024 | V1:2024.01 - V5:2024.05 | [Arxiv](https://arxiv.org/abs/2401.13601) | :clock1: Coming soon... |
| Exploring the Reasoning Abilities of Multimodal Large Language Models (MLLMs): A Comprehensive Survey on Emerging Trends in Multimodal Reasoning | Arxiv | 2024.01 | [Arxiv](https://arxiv.org/abs/2401.06805) | :clock1: Coming soon... |
| Visual Instruction Tuning towards General-Purpose Multimodal Model: A Survey | Arxiv | 2023.12 | [Arxiv](https://arxiv.org/abs/2312.16602) | :clock1: Coming soon... |
| Multimodal Large Language Models: A Survey | BigData 2023 | 2023.11 | [Arxiv](https://arxiv.org/abs/2311.13165) | :clock1: Coming soon... |
| A Survey on Multimodal Large Language Models for Autonomous Driving | WACV 2024 | 2023.11 | [Arxiv](https://arxiv.org/abs/2311.12320) | :clock1: Coming soon... |
| Multimodal Foundation Models: From Specialists to General-Purpose Assistants | Arxiv | 2023.09 | [Arxiv](https://arxiv.org/abs/2309.10020) | :clock1: Coming soon... |
| Examining User-Friendly and Open-Sourced Large GPT Models: A Survey on Language, Multimodal, and Scientific GPT Models | Arxiv | 2023.08 | [Arxiv](https://arxiv.org/abs/2308.14149) | :clock1: Coming soon... |
| A Survey on Multimodal Large Language Models | Arxiv | 2023.06 | [Arxiv](https://arxiv.org/abs/2306.13549) | discuss MLLM from four perspectives: Multimodal Instruction Tuning、Multimodal In-Context Learning、Multimodal Chain of Thought、LLM-Aided Visual Reasoning |

## 2. Analysis

|  Title  |  Time   |  Link  | Notes |
|  :---:  |  :---:  |  :---: | :---: |
| Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs | 2024.01 | [Paper](https://arxiv.org/abs/2401.06209) | The authors defined a "CLIP-blind pair" as two images that appear visually dissimilar but have very similar features according to CLIP's output. They also utilized GPT to summarize the characteristics of images that the model finds challenging to recognize. |

## 3. Models

|  Name  |  Time  |  Modal  |  Params |  Link  |  Notes  |
|  :---: |  :---: |     :---:    |  :---:  | :---:  |  :---:  |
| MM1 | 2024.03 | Vision<br>Language | 3B, 7B, 30B | [Paper](https://arxiv.org/abs/2403.09611), [Github](https://github.com/kyegomez/MM1) | Ablation experiments are performed on the model architecture decisions and pre-training data choices to determine the optimal configuration |
| LLaVA | 2023.04 | Vision<br>Language | V1: 7B, 13B<br>V1.5: 7B, 13B<br>V1.6: 7B, 13B, 34B | [Page](https://llava-vl.github.io/), [Paper1](https://arxiv.org/abs/2304.08485), [Paper2](https://arxiv.org/abs/2310.03744), [Github](https://github.com/haotian-liu/LLaVA) | is the first attempt to use language-only GPT-4 to generate multimodal language-image instruction-following data and trains an end-to-end large multimodal model that connects a vision encoder and an LLM for generalpurpose visual and language understanding. |

## 4. Datasets

| Datasets | Time | Modal | Scale | Annotation | Data sources | Link | Notes |
| :---: |  :---: | :---: |  :---:  | :---:  |  :---:  |  :---:  |  :---:  |
| FILIP300M | 2021.11 | Vision<br>Language | 300M image-text pairs | image-text pairs | Internet | [Paper](https://arxiv.org/abs/2111.07783) | Removing the images whose shorter dimension is smaller than 200 pixels and the aspect ratio is larger than 3. Keeping only English texts, and excluding meaningless ones. Discarding image-text pairs whose texts are repeated over 10 times. |


## 5. Benchmarks

|  Name  |  Time  |  Task  | Link |
| :----: | :----: |  :---: | :---:|
| MMVP | 2024.01 | VQA for "CLIP-blind Pairs" | [Page](https://tsb0601.github.io/mmvp_blog/), [Paper](https://arxiv.org/abs/2401.06209), [Github](https://github.com/tsb0601/MMVP) <br> ![Star](https://img.shields.io/github/stars/tsb0601/MMVP.svg?style=social&label=Star) |
| MME | 2023.06 | 14 subtasks: Existence, Count, OCR, Poster, Celebrity, Commonsense Reasoning, Text Translation... | [Paper](https://arxiv.org/abs/2306.13394), [Github](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation) <br> ![Star](https://img.shields.io/github/stars/BradyFU/Awesome-Multimodal-Large-Language-Models.svg?style=social&label=Star) |
| Perception Test | 2023.05 | object tracking, point tracking, temporal action localisation, temporal sound localisation, multiple-choice video question-answering, grounded video question-answering | [Paper](https://arxiv.org/abs/2305.13786), [Github](https://github.com/google-deepmind/perception_test) <br> ![Star](https://img.shields.io/github/stars/google-deepmind/perception_test.svg?style=social&label=Star) |

## 6. Technologies

| Name | Link | Notes |
| :--: | :--: | :--:  |
| LoRA | [Paper](https://arxiv.org/abs/2106.09685) | By transforming the full-parameter optimization into the optimization of two low-rank matrices through low-rank decomposition, the memory usage during training is reduced. |
| Data Filtering Networks(DFN) | [Paper](https://arxiv.org/abs/2309.17425) | A CLIP model with high accuracy on downstream tasks is not necessarily a good data filtering model; a small amount of high-quality pre-training data is more important. |

## 7. Other awesome

|  Name  |  Link  |  Scope |
| :----: | :----: |  :---: |
| Awesome-LLM-Tabular | [Github](https://github.com/johnnyhwu/Awesome-LLM-Tabular) | Tabular, LLM  <br> ![Star](https://img.shields.io/github/stars/johnnyhwu/Awesome-LLM-Tabular.svg?style=social&label=Star) |
| Awesome-LLM-3D | [Github](https://github.com/ActiveVisionLab/Awesome-LLM-3D) | 3D, LLM <br> ![Star](https://img.shields.io/github/stars/ActiveVisionLab/Awesome-LLM-3D.svg?style=social&label=Star) |
| Awesome-Multimodal-Large-Language-Models | [Github](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models) | Multimodal, Dataset, LLM <br> ![Star](https://img.shields.io/github/stars/BradyFU/Awesome-Multimodal-Large-Language-Models.svg?style=social&label=Star) |
| Awesome-Multimodal-Papers | [Github](https://github.com/friedrichor/Awesome-Multimodal-Papers) | LargeModel, Benchmark, Task, Dataset <br> ![Star](https://img.shields.io/github/stars/friedrichor/Awesome-Multimodal-Papers.svg?style=social&label=Star) |