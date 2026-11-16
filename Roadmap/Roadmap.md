# Roadmap of Large Foundation Models

This roadmap presents the development of representative large foundation models and related architectures, organized into five categories: **Large Language Models (LLMs), Vision-Language Models (VLMs), Multimodal Large Language Models (MLLMs), Diffusion Models (DMs), and World Models (WMs)**.

The selected models are arranged chronologically within each category to illustrate the evolution of different model families and their representative milestones. This roadmap provides the model-development background for understanding the foundation models discussed in the survey *Large Foundation Models for Question Answering in Autonomous Driving: A Review*.

## 1. Large Language Models (LLMs)

Large Language Models focus on learning general-purpose language representations and generation capabilities. Their development has progressed from early pre-trained language models to increasingly large and capable models with strong language understanding, reasoning, and instruction-following abilities.

| Model | Representative Paper | Year | Venue | Citation Key |
|---|---|---|---|---|
| GPT-1 | Improving Language Understanding by Generative Pre-training | 2018 | arXiv (2018) | `radford2018improving` |
| GPT-2 | Language Models are Unsupervised Multitask Learners | 2019 | arXiv (2019) | `radford2019language` |
| BERT | BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding | 2019.06 | NAACL-HLT (2019) | `devlin2019bert` |
| XLNet | XLNet: Generalized Autoregressive Pretraining for Language Understanding | 2019.06 | NeurIPS (2019) | `yang2019xlnet` |
| RoBERTa | RoBERTa: A Robustly Optimized BERT Pretraining Approach | 2019.07.26 | arXiv (2019) | `liu2019roberta` |
| T5 | Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer | 2019.10.23 | JMLR (2020) | `raffel2020exploring` |
| GPT-3 | Language Models are Few-Shot Learners | 2020.05.28 | NeurIPS (2020) | `brown2020language` |
| Gopher | Scaling Language Models: Methods, Analysis & Insights from Training Gopher | 2021.11.08 | arXiv (2021) | `rae2021scaling` |
| Chinchilla | Training Compute-Optimal Large Language Models | 2022.03.29 | arXiv (2022) | `hoffmann2022training` |
| OPT | OPT: Open Pre-trained Transformer Language Models | 2022.05.02 | arXiv (2022) | `zhang2022opt` |
| UL2 | UL2: Unifying Language Learning Paradigms | 2022.05.10 | arXiv (2022) | `tay2022ul2` |
| BLOOM | BLOOM: A 176B-parameter Open-access Multilingual Language Model | 2022.11.09 | arXiv (2022) | `workshop2022bloom` |
| LLaMA | LLaMA: Open and Efficient Foundation Language Models | 2023.02.27 | arXiv (2023) | `touvron2023llama` |
| PaLM | PaLM: Scaling Language Modeling with Pathways | 2023.10.11 | arXiv (2022) | `chowdhery2023palm` |

## 2. Vision-Language Models (VLMs)

Vision-Language Models establish connections between visual information and natural language. They learn joint visual and linguistic representations, providing important foundations for cross-modal understanding and vision-language tasks.

| Model | Representative Paper | Year | Venue | Citation Key |
|---|---|---|---|---|
| ViLBERT | ViLBERT: Pretraining Task-Agnostic Visiolinguistic Representations for Vision-and-Language Tasks | 2019.08 | NeurIPS (2019) | `lu2019vilbert` |
| VisualBERT | VisualBERT: A Simple and Performant Baseline for Vision and Language | 2019.08.09 | arXiv (2019) | — |
| LXMERT | LXMERT: Learning Cross-Modality Encoder Representations from Transformers | 2019.08.20 | EMNLP-IJCNLP (2019) | `tan2019lxmert` |
| VL-BERT | VL-BERT: Pre-training of Generic V+L Representations | 2019.08.22 | ICLR (2020) | `su2019vl` |
| UNITER | UNITER: UNiversal Image-TExt Representation Learning | 2020.09.24 | ECCV (2020) | `chen2020uniter` |
| CLIP | Learning Transferable Visual Models From Natural Language Supervision | 2021.02.26 | ICML (2021) | `radford2021learning` |
| BLIP | BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation | 2022.02.15 | ICML (2022) | `li2022blip` |
| Flamingo | Flamingo: A Visual Language Model for Few-Shot Learning | 2022.04.29 | NeurIPS (2022) | `alayrac2022flamingo` |
| BLIP-2 | BLIP-2: Bootstrapping Language-Image Pretraining with Frozen Image Encoders and Large Language Models | 2023.01.30 | ICML (2023) | `li2023blip2` |

## 3. Multimodal Large Language Models (MLLMs)

Multimodal Large Language Models extend language models with the ability to process and reason over multiple modalities, particularly visual and textual information. By integrating visual encoders, modality alignment mechanisms, and language models, MLLMs enable more flexible multimodal interaction and understanding.

| Model | Representative Paper | Year | Venue | Citation Key |
|---|---|---|---|---|
| Kosmos-1 | Language Is Not All You Need: Aligning Perception with Language Models | 2023.02.27 | arXiv (2023) | `huang2023language` |
| InstructBLIP | InstructBLIP: Towards General-Purpose Vision-Language Models with Instruction Tuning | 2023.03.11 | NeurIPS (2023) | `dai2023instructblip` |
| GPT-4V | GPT-4 Technical Report | 2023.03.15 | Technical Report / arXiv (2023) | `achiam2023gpt` |
| LLaVA | Visual Instruction Tuning | 2023.04.17 | NeurIPS (2023) | `liu2023visual` |
| MiniGPT-4 | MiniGPT-4: Enhancing Vision-Language Understanding with GPT-4-level Capabilities | 2023.04.20 | arXiv (2023) | `zhu2023minigpt` |
| mPLUG-Owl | mPLUG-Owl: Modularization Empowers Large Language Models with Multimodality | 2023.04.27 | arXiv (2023) | `ye2023mplug` |
| Shikra | Shikra: Unleashing Multimodal LLM's Referential Dialogue Magic | 2023.06.27 | arXiv (2023) | `chen2023shikra` |
| OpenFlamingo | OpenFlamingo: An Open-Source Framework for Training Large Autoregressive Vision-Language Models | 2023.08.02 | arXiv (2023) | `awadalla2023openflamingo` |

## 4. Diffusion Models (DMs)

Diffusion Models learn data distributions through iterative denoising processes. They have demonstrated strong generative capabilities and have also been explored for planning and behavior synthesis, offering alternative approaches to generative modeling and decision-making.

| Model | Representative Paper | Year | Venue | Citation Key |
|---|---|---|---|---|
| DDPM | Denoising Diffusion Probabilistic Models | 2020.06.19 | NeurIPS (2020) | `ho2020denoising` |
| DDIM | Denoising Diffusion Implicit Models | 2020.10.06 | ICLR (2021) | `song2020denoising` |
| Improved DDPM | Improved Denoising Diffusion Probabilistic Models | 2021.02.18 | ICML (2021) | `nichol2021improved` |
| Latent Diffusion (LDM) | High-Resolution Image Synthesis with Latent Diffusion Models | 2021.12.20 | CVPR (2022) | `rombach2022high` |
| Planning with Diffusion | Planning with Diffusion for Flexible Behavior Synthesis | 2022.05.20 | ICLR (2022) | `janner2022planning` |
| Imagen | Phot
