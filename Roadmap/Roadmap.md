# Roadmap of Large Foundation Models

This roadmap presents the development of representative large foundation models and related architectures, organized into five categories: **Large Language Models (LLMs), Vision-Language Models (VLMs), Multimodal Large Language Models (MLLMs), Diffusion Models (DMs), and World Models (WMs)**.

The selected models are arranged chronologically within each category to illustrate the evolution of different model families and their representative milestones. This roadmap provides the model-development background for understanding the foundation models discussed in the survey *Large Foundation Models for Question Answering in Autonomous Driving: A Review*.

## 1. Large Language Models (LLMs)

Large Language Models focus on learning general-purpose language representations and generation capabilities. Their development has progressed from early pre-trained language models to increasingly large and capable models with strong language understanding, reasoning, and instruction-following abilities.

| Model | Representative Paper | Venue | Citation Key |
|---|---|---|---|
| GPT-1 | Improving Language Understanding by Generative Pre-training | arXiv (2018) | `radford2018improving` |
| GPT-2 | Language Models are Unsupervised Multitask Learners | arXiv (2019) | `radford2019language` |
| BERT | BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding | NAACL-HLT (2019) | `devlin2019bert` |
| XLNet | XLNet: Generalized Autoregressive Pretraining for Language Understanding | NeurIPS (2019) | `yang2019xlnet` |
| RoBERTa | RoBERTa: A Robustly Optimized BERT Pretraining Approach | arXiv (2019) | `liu2019roberta` |
| T5 | Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer | JMLR (2020) | `raffel2020exploring` |
| GPT-3 | Language Models are Few-Shot Learners | NeurIPS (2020) | `brown2020language` |
| Gopher | Scaling Language Models: Methods, Analysis & Insights from Training Gopher | arXiv (2021) | `rae2021scaling` |
| Chinchilla | Training Compute-Optimal Large Language Models | arXiv (2022) | `hoffmann2022training` |
| OPT | OPT: Open Pre-trained Transformer Language Models | arXiv (2022) | `zhang2022opt` |
| UL2 | UL2: Unifying Language Learning Paradigms | arXiv (2022) | `tay2022ul2` |
| BLOOM | BLOOM: A 176B-parameter Open-access Multilingual Language Model | arXiv (2022) | `workshop2022bloom` |
| LLaMA | LLaMA: Open and Efficient Foundation Language Models | arXiv (2023) | `touvron2023llama` |
| PaLM | PaLM: Scaling Language Modeling with Pathways | arXiv (2022) | `chowdhery2023palm` |

## 2. Vision-Language Models (VLMs)

Vision-Language Models establish connections between visual information and natural language. They learn joint visual and linguistic representations, providing important foundations for cross-modal understanding and vision-language tasks.

| Model | Representative Paper | Venue | Citation Key |
|---|---|---|---|
| ViLBERT | ViLBERT: Pretraining Task-Agnostic Visiolinguistic Representations for Vision-and-Language Tasks | NeurIPS (2019) | `lu2019vilbert` |
| VisualBERT | VisualBERT: A Simple and Performant Baseline for Vision and Language | arXiv (2019) | — |
| LXMERT | LXMERT: Learning Cross-Modality Encoder Representations from Transformers | EMNLP-IJCNLP (2019) | `tan2019lxmert` |
| VL-BERT | VL-BERT: Pre-training of Generic V+L Representations | ICLR (2020) | `su2019vl` |
| UNITER | UNITER: UNiversal Image-TExt Representation Learning | ECCV (2020) | `chen2020uniter` |
| CLIP | Learning Transferable Visual Models From Natural Language Supervision | ICML (2021) | `radford2021learning` |
| BLIP | BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation | ICML (2022) | `li2022blip` |
| Flamingo | Flamingo: A Visual Language Model for Few-Shot Learning | NeurIPS (2022) | `alayrac2022flamingo` |
| BLIP-2 | BLIP-2: Bootstrapping Language-Image Pretraining with Frozen Image Encoders and Large Language Models | ICML (2023) | `li2023blip2` |

## 3. Multimodal Large Language Models (MLLMs)

Multimodal Large Language Models extend language models with the ability to process and reason over multiple modalities, particularly visual and textual information. By integrating visual encoders, modality alignment mechanisms, and language models, MLLMs enable more flexible multimodal interaction and understanding.

| Model | Representative Paper | Venue | Citation Key |
|---|---|---|---|
| Kosmos-1 | Language Is Not All You Need: Aligning Perception with Language Models | arXiv (2023) | `huang2023language` |
| InstructBLIP | InstructBLIP: Towards General-Purpose Vision-Language Models with Instruction Tuning | NeurIPS (2023) | `dai2023instructblip` |
| GPT-4V | GPT-4 Technical Report | Technical Report / arXiv (2023) | `achiam2023gpt` |
| LLaVA | Visual Instruction Tuning | NeurIPS (2023) | `liu2023visual` |
| MiniGPT-4 | MiniGPT-4: Enhancing Vision-Language Understanding with GPT-4-level Capabilities | arXiv (2023) | `zhu2023minigpt` |
| mPLUG-Owl | mPLUG-Owl: Modularization Empowers Large Language Models with Multimodality | arXiv (2023) | `ye2023mplug` |
| Shikra | Shikra: Unleashing Multimodal LLM's Referential Dialogue Magic | arXiv (2023) | `chen2023shikra` |
| OpenFlamingo | OpenFlamingo: An Open-Source Framework for Training Large Autoregressive Vision-Language Models | arXiv (2023) | `awadalla2023openflamingo` |

## 4. Diffusion Models (DMs)

Diffusion Models learn data distributions through iterative denoising processes. They have demonstrated strong generative capabilities and have also been explored for planning and behavior synthesis, offering alternative approaches to generative modeling and decision-making.

| Model | Representative Paper | Venue | Citation Key |
|---|---|---|---|
| DDPM | Denoising Diffusion Probabilistic Models | NeurIPS (2020) | `ho2020denoising` |
| DDIM | Denoising Diffusion Implicit Models | ICLR (2021) | `song2020denoising` |
| Improved DDPM | Improved Denoising Diffusion Probabilistic Models | ICML (2021) | `nichol2021improved` |
| Latent Diffusion (LDM) | High-Resolution Image Synthesis with Latent Diffusion Models | CVPR (2022) | `rombach2022high` |
| Planning with Diffusion | Planning with Diffusion for Flexible Behavior Synthesis | ICLR (2022) | `janner2022planning` |
| Imagen | Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding | arXiv (2022) | `saharia2022photorealistic` |
| Classifier-Free Guidance | Classifier-Free Diffusion Guidance | NeurIPS (2021) | `ho2022classifier` |

## 5. World Models (WMs)

World Models learn representations of environments and their dynamics, enabling agents to predict future states and support planning through learned models or latent imagination. They provide an important research direction for model-based decision-making and intelligent autonomous systems.

| Model | Representative Paper | Venue | Citation Key |
|---|---|---|---|
| MuZero | Mastering Atari, Go, Chess and Shogi by Planning with a Learned Model | Nature (2020) | `schrittwieser2020mastering` |
| Dreamer | Dream to Control: Learning Behaviors by Latent Imagination | ICLR (2020) | `hafner2019dream` |
| World Model as a Graph | World Model as a Graph: Learning Latent Landmarks for Planning | ICML (2021) | `zhang2021world` |
| DayDreamer | DayDreamer: World Models for Physical Robot Learning | CoRL (2022) | `wu2023daydreamer` |
| DreamerV3 | Mastering Diverse Domains through World Models | Nature (2025) / arXiv (2023) | `hafner2023mastering` |
| UniZero | UniZero: Generalized and Efficient Planning with Scalable Latent World Models | TMLR (2025) | `pu2024unizero` |
| WorldGPT | WorldGPT: Empowering LLM as Multimodal World Model | arXiv (2024) | `ge2024worldgpt` |
| Interpreting MuZero | Interpreting the Learned Model in MuZero Planning | arXiv (2024) | `guei2024interpreting` |

## Notes

- The five categories follow the `type` classification in the current model-paper collection.
- The listed papers represent selected milestones and examples, rather than an exhaustive list of all models in each category.
- The publication venue and year are presented together in the `Venue` column.
- For papers without a confirmed formal conference or journal publication, arXiv is used as the source.
- The roadmap focuses on model families and their development. It is complementary to the survey's autonomous-driving QA task taxonomy and the dataset and benchmark collection.
- Citation keys are provided for reference and can be used to connect the roadmap entries with the corresponding bibliography.

