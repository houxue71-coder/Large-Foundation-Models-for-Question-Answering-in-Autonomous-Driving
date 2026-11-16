# Roadmap of Large Foundation Models

This roadmap presents the development of representative large foundation models and related architectures, organized into five categories: **Large Language Models (LLMs), Vision-Language Models (VLMs), Multimodal Large Language Models (MLLMs), Diffusion Models (DMs), and World Models (WMs)**.

The selected models are arranged chronologically within each category to illustrate the evolution of different model families and their representative milestones. This roadmap provides the model-development background for understanding the foundation models discussed in the survey *Large Foundation Models for Question Answering in Autonomous Driving: A Review*.

## 1. Large Language Models (LLMs)

Large Language Models focus on learning general-purpose language representations and generation capabilities. Their development has progressed from early pre-trained language models to increasingly large and capable models with strong language understanding, reasoning, and instruction-following abilities.

| Model | Representative Paper | Venue | Paper Link |
|---|---|---|---|
| GPT-1 | [Improving Language Understanding by Generative Pre-training](https://arxiv.org/abs/1810.04805) | arXiv (2018) | [Paper](https://arxiv.org/abs/1810.04805) |
| GPT-2 | [Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) | OpenAI Technical Report (2019) | [Paper](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) |
| BERT | [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://aclanthology.org/N19-1423/) | NAACL-HLT (2019) | [Paper](https://aclanthology.org/N19-1423/) |
| XLNet | [XLNet: Generalized Autoregressive Pretraining for Language Understanding](https://arxiv.org/abs/1906.08237) | NeurIPS (2019) | [Paper](https://arxiv.org/abs/1906.08237) |
| RoBERTa | [RoBERTa: A Robustly Optimized BERT Pretraining Approach](https://arxiv.org/abs/1907.11692) | arXiv (2019) | [Paper](https://arxiv.org/abs/1907.11692) |
| T5 | [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://jmlr.org/papers/v21/20-074.html) | JMLR (2020) | [Paper](https://jmlr.org/papers/v21/20-074.html) |
| GPT-3 | [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165) | NeurIPS (2020) | [Paper](https://arxiv.org/abs/2005.14165) |
| Gopher | [Scaling Language Models: Methods, Analysis & Insights from Training Gopher](https://arxiv.org/abs/2112.11446) | arXiv (2021) | [Paper](https://arxiv.org/abs/2112.11446) |
| Chinchilla | [Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556) | arXiv (2022) | [Paper](https://arxiv.org/abs/2203.15556) |
| OPT | [OPT: Open Pre-trained Transformer Language Models](https://arxiv.org/abs/2205.01068) | arXiv (2022) | [Paper](https://arxiv.org/abs/2205.01068) |
| UL2 | [UL2: Unifying Language Learning Paradigms](https://arxiv.org/abs/2205.05131) | arXiv (2022) | [Paper](https://arxiv.org/abs/2205.05131) |
| BLOOM | [BLOOM: A 176B-parameter Open-access Multilingual Language Model](https://arxiv.org/abs/2211.05100) | arXiv (2022) | [Paper](https://arxiv.org/abs/2211.05100) |
| LLaMA | [LLaMA: Open and Efficient Foundation Language Models](https://arxiv.org/abs/2302.13971) | arXiv (2023) | [Paper](https://arxiv.org/abs/2302.13971) |
| PaLM | [PaLM: Scaling Language Modeling with Pathways](https://arxiv.org/abs/2204.02311) | arXiv (2022) | [Paper](https://arxiv.org/abs/2204.02311) |

## 2. Vision-Language Models (VLMs)

Vision-Language Models establish connections between visual information and natural language. They learn joint visual and linguistic representations, providing important foundations for cross-modal understanding and vision-language tasks.

| Model | Representative Paper | Venue | Paper Link |
|---|---|---|---|
| ViLBERT | [ViLBERT: Pretraining Task-Agnostic Visiolinguistic Representations for Vision-and-Language Tasks](https://arxiv.org/abs/1908.02265) | NeurIPS (2019) | [Paper](https://arxiv.org/abs/1908.02265) |
| VisualBERT | [VisualBERT: A Simple and Performant Baseline for Vision and Language](https://arxiv.org/abs/1908.03557) | arXiv (2019) | [Paper](https://arxiv.org/abs/1908.03557) |
| LXMERT | [LXMERT: Learning Cross-Modality Encoder Representations from Transformers](https://arxiv.org/abs/1908.07490) | EMNLP-IJCNLP (2019) | [Paper](https://arxiv.org/abs/1908.07490) |
| VL-BERT | [VL-BERT: Pre-training of Generic V+L Representations](https://arxiv.org/abs/1908.08530) | ICLR (2020) | [Paper](https://arxiv.org/abs/1908.08530) |
| UNITER | [UNITER: UNiversal Image-TExt Representation Learning](https://arxiv.org/abs/1909.11740) | ECCV (2020) | [Paper](https://arxiv.org/abs/1909.11740) |
| CLIP | [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020) | ICML (2021) | [Paper](https://arxiv.org/abs/2103.00020) |
| BLIP | [BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation](https://arxiv.org/abs/2201.12086) | ICML (2022) | [Paper](https://arxiv.org/abs/2201.12086) |
| Flamingo | [Flamingo: A Visual Language Model for Few-Shot Learning](https://arxiv.org/abs/2204.14198) | NeurIPS (2022) | [Paper](https://arxiv.org/abs/2204.14198) |
| BLIP-2 | [BLIP-2: Bootstrapping Language-Image Pretraining with Frozen Image Encoders and Large Language Models](https://arxiv.org/abs/2301.12597) | ICML (2023) | [Paper](https://arxiv.org/abs/2301.12597) |

## 3. Multimodal Large Language Models (MLLMs)

Multimodal Large Language Models extend language models with the ability to process and reason over multiple modalities, particularly visual and textual information. By integrating visual encoders, modality alignment mechanisms, and language models, MLLMs enable more flexible multimodal interaction and understanding.

| Model | Representative Paper | Venue | Paper Link |
|---|---|---|---|
| Kosmos-1 | [Language Is Not All You Need: Aligning Perception with Language Models](https://arxiv.org/abs/2302.14045) | arXiv (2023) | [Paper](https://arxiv.org/abs/2302.14045) |
| InstructBLIP | [InstructBLIP: Towards General-Purpose Vision-Language Models with Instruction Tuning](https://arxiv.org/abs/2305.06500) | NeurIPS (2023) | [Paper](https://arxiv.org/abs/2305.06500) |
| GPT-4V | [GPT-4 Technical Report](https://arxiv.org/abs/2303.08774) | Technical Report / arXiv (2023) | [Paper](https://arxiv.org/abs/2303.08774) |
| LLaVA | [Visual Instruction Tuning](https://arxiv.org/abs/2304.08485) | NeurIPS (2023) | [Paper](https://arxiv.org/abs/2304.08485) |
| MiniGPT-4 | [MiniGPT-4: Enhancing Vision-Language Understanding with GPT-4-level Capabilities](https://arxiv.org/abs/2304.10592) | arXiv (2023) | [Paper](https://arxiv.org/abs/2304.10592) |
| mPLUG-Owl | [mPLUG-Owl: Modularization Empowers Large Language Models with Multimodality](https://arxiv.org/abs/2304.14178) | arXiv (2023) | [Paper](https://arxiv.org/abs/2304.14178) |
| Shikra | [Shikra: Unleashing Multimodal LLM's Referential Dialogue Magic](https://arxiv.org/abs/2306.15195) | arXiv (2023) | [Paper](https://arxiv.org/abs/2306.15195) |
| OpenFlamingo | [OpenFlamingo: An Open-Source Framework for Training Large Autoregressive Vision-Language Models](https://arxiv.org/abs/2308.01390) | arXiv (2023) | [Paper](https://arxiv.org/abs/2308.01390) |

## 4. Diffusion Models (DMs)

Diffusion Models learn data distributions through iterative denoising processes. They have demonstrated strong generative capabilities and have also been explored for planning and behavior synthesis, offering alternative approaches to generative modeling and decision-making.

| Model | Representative Paper | Venue | Paper Link |
|---|---|---|---|
| DDPM | [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239) | NeurIPS (2020) | [Paper](https://arxiv.org/abs/2006.11239) |
| DDIM | [Denoising Diffusion Implicit Models](https://arxiv.org/abs/2010.02502) | ICLR (2021) | [Paper](https://arxiv.org/abs/2010.02502) |
| Improved DDPM | [Improved Denoising Diffusion Probabilistic Models](https://proceedings.mlr.press/v139/nichol21a.html) | ICML (2021) | [Paper](https://proceedings.mlr.press/v139/nichol21a.html) |
| Latent Diffusion (LDM) | [High-Resolution Image Synthesis with Latent Diffusion Models](https://openaccess.thecvf.com/content/CVPR2022/html/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.html) | CVPR (2022) | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.html) |
| Planning with Diffusion | [Planning with Diffusion for Flexible Behavior Synthesis](https://arxiv.org/abs/2205.09991) | ICLR (2022) | [Paper](https://arxiv.org/abs/2205.09991) |
| Imagen | [Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding](https://arxiv.org/abs/2205.11487) | arXiv (2022) | [Paper](https://arxiv.org/abs/2205.11487) |
| Classifier-Free Guidance | [Classifier-Free Diffusion Guidance](https://arxiv.org/abs/2207.12598) | arXiv (2022) | [Paper](https://arxiv.org/abs/2207.12598) |

## 5. World Models (WMs)

World Models learn representations of environments and their dynamics, enabling agents to predict future states and support planning through learned models or latent imagination. They provide an important research direction for model-based decision-making and intelligent autonomous systems.

| Model | Representative Paper | Venue | Paper Link |
|---|---|---|---|
| MuZero | [Mastering Atari, Go, Chess and Shogi by Planning with a Learned Model](https://www.nature.com/articles/s41586-020-03051-4) | Nature (2020) | [Paper](https://www.nature.com/articles/s41586-020-03051-4) |
| Dreamer | [Dream to Control: Learning Behaviors by Latent Imagination](https://arxiv.org/abs/1912.01603) | ICLR (2020) | [Paper](https://arxiv.org/abs/1912.01603) |
| World Model as a Graph | [World Model as a Graph: Learning Latent Landmarks for Planning](https://proceedings.mlr.press/v139/zhang21x.html) | ICML (2021) | [Paper](https://proceedings.mlr.press/v139/zhang21x.html) |
| DayDreamer | [DayDreamer: World Models for Physical Robot Learning](https://proceedings.mlr.press/v205/wu23c.html) | CoRL (2022) | [Paper](https://proceedings.mlr.press/v205/wu23c.html) |
| DreamerV3 | [Mastering Diverse Domains through World Models](https://arxiv.org/abs/2301.04104) | Nature (2025) / arXiv (2023) | [Paper](https://arxiv.org/abs/2301.04104) |
| UniZero | [UniZero: Generalized and Efficient Planning with Scalable Latent World Models](https://arxiv.org/abs/2406.10667) | TMLR (2025) | [Paper](https://arxiv.org/abs/2406.10667) |
| WorldGPT | [WorldGPT: Empowering LLM as Multimodal World Model](https://doi.org/10.1145/3664647.3681488) | ACM Multimedia (2024) | [Paper](https://doi.org/10.1145/3664647.3681488) |
| Interpreting MuZero | [Interpreting the Learned Model in MuZero Planning](https://arxiv.org/abs/2411.04580) | arXiv (2024) | [Paper](https://arxiv.org/abs/2411.04580) |

## Notes

- The five categories follow the `type` classification in the current model-paper collection.
- The listed papers represent selected milestones and examples, rather than an exhaustive list of all models in each category.
- The publication venue and year are presented together in the `Venue` column.
- For papers without a confirmed formal conference or journal publication, arXiv or the corresponding technical report is used as the source.
- Each paper title and its corresponding link direct readers to the original paper or official publication page whenever available.
- The roadmap focuses on model families and their development. It is complementary to the survey's autonomous-driving QA task taxonomy and the dataset and benchmark collection.

