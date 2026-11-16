# Large Foundation Models for Question Answering in Autonomous Driving: A Review

## 🚗 Introduction

This repository is associated with the survey paper **"Large Foundation Models for Question Answering in Autonomous Driving: A Review"**, which provides a systematic review of recent advances in question answering (QA) powered by large foundation models (LFMs) for autonomous driving (AD).

Question answering has emerged as a powerful paradigm for bridging perception, reasoning, and human interaction in autonomous driving. With the development of large foundation models—including large language models (LLMs), vision-language models (VLMs), and multimodal large language models (MLLMs)—QA is becoming an increasingly important interface for interpreting driving scenes, explaining decisions, and enabling human-AI and multi-agent collaboration.

This repository aims to provide a structured collection of representative foundation models and QA datasets relevant to autonomous driving. We hope it can serve as a useful resource for researchers and newcomers interested in this emerging research area.

### 📚 Read the Full Survey Paper

📄 **[Read the Full Survey Paper (PDF)](./paper.pdf)**

### 📌 Highlights

This survey presents a unified QA-centric perspective on large foundation models for autonomous driving, with the following highlights:

1. **Systematic Taxonomy of QA Tasks:** We categorize QA tasks in autonomous driving across perception, prediction, decision-making, planning, human-AI interaction, multi-agent coordination, and counterfactual and safety-critical reasoning.
2. **Large Foundation Models for Driving QA:** We review how different foundation models support QA-related tasks through cross-modal alignment, causal reasoning, and instruction following.
3. **Datasets and Benchmarks:** We summarize representative QA datasets, annotation strategies, evaluation metrics, and benchmarking protocols.
4. **Challenges and Future Directions:** We identify open challenges related to multimodal reasoning, prompt sensitivity, real-time deployment, data scarcity, and system-level verifiability, and discuss promising research directions.

**Keywords:** Autonomous Driving, Question Answering, Large Foundation Models, Large Language Models, Vision-Language Models, Multimodal Large Language Models

---

## 📌 Framework

The survey is organized around the relationship between large foundation models and question answering in autonomous driving.

It covers the evolution of QA in autonomous driving, the integration of foundation models into driving systems, a systematic taxonomy of driving-related QA tasks, representative datasets and benchmarks, existing challenges, and future research directions.

The overall organization of the paper is illustrated below.

![Organization of the Survey](./framework.png)

*Note: Place the survey organization figure in the repository root directory as `framework.png`, or update the image path accordingly.*

---

## 🔗 Repository Structure

The repository contains two main sections, organized according to the foundation model roadmap and the QA dataset table presented in the survey.

1. **[Roadmap of Large Foundation Models](./ROADMAP/README.md)**

   A collection of representative foundation models and milestone papers, organized into seven categories:

   - Large Language Models (LLMs)
   - Vision-Language Models (VLMs)
   - Multimodal Large Language Models (MLLMs)
   - Foundation Models for Autonomous Driving
   - World Models
   - Vision-Language-Action (VLA) Models
   - Multi-Agent Systems

2. **[QA Datasets and Benchmarks](./datasets/datasets_benchmarks.md)**

   A collection of datasets and benchmarks for question answering in autonomous driving, including representative papers, data modalities, QA task categories, dataset statistics, and available resources.

---

## 🗂️ Project Organization

```text
Autonomous-Driving-LFM-QA/
│
├── README.md
├── paper.pdf
├── framework.png
│
├── ROADMAP/
│   ├── README.md
│   └── roadmap.png
│
├── datasets/
│   └── datasets_benchmarks.md
│
├── LICENSE
└── CITATION.cff
```

---

## 🎯 Scope of This Repository

This repository focuses on the intersection of question answering, large foundation models, and autonomous driving. It aims to:

- Organize representative foundation models and their milestone publications.
- Summarize the development of different model families relevant to autonomous driving.
- Collect and categorize QA datasets and benchmarks for autonomous driving.
- Provide convenient access to relevant papers and publicly available resources.
- Facilitate further research on explainable, interactive, and trustworthy autonomous driving systems.

## 🤝 Contributions

We welcome contributions from the research community! If you find relevant foundation models, QA datasets, benchmarks, or related resources that should be included, feel free to open an issue or submit a pull request.

Suggestions for correcting existing entries and improving the organization of this repository are also welcome.

## 📖 Citation

If you find this repository or the associated survey useful in your research, please consider citing our paper:

```bibtex
@article{your_bibtex_key,
  title={Large Foundation Models for Question Answering in Autonomous Driving: A Review},
  author={Author Names},
  journal={Journal Name},
  year={Year}
}
```

*Please replace the placeholder information with the final publication details.*

## ⭐ Acknowledgement

We thank all researchers and institutions whose contributions have advanced question answering, large foundation models, and autonomous driving research. This repository is intended to facilitate knowledge sharing and encourage further research in this emerging area.
