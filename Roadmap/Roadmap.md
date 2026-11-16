# Roadmap of Large Foundation Models

This roadmap presents the development of representative large foundation models and related architectures, organized into five categories: **Large Language Models (LLMs), Vision-Language Models (VLMs), Multimodal Large Language Models (MLLMs), Diffusion Models (DMs), and World Models (WMs)**.

The selected models are arranged chronologically within each category to illustrate the evolution of different model families and their representative milestones. This roadmap provides the model-development background for understanding the foundation models discussed in the survey *Large Foundation Models for Question Answering in Autonomous Driving: A Review*.

## 1. Large Language Models (LLMs)

Large Language Models focus on learning general-purpose language representations and generation capabilities. Their development has progressed from early pre-trained language models to increasingly large and capable models with strong language understanding, reasoning, and instruction-following abilities.

| Model | Representative Paper | Year | Citation Key |
|---|---|---|---|
| GPT-1 | [Improving Language Understanding by Generative Pre-training](https://scholar.google.com/scholar?q=Improving+Language+Understanding+by+Generative+Pre-training) | 2018 | `radford2018improving` |
| GPT-2 | [Language Models are Unsupervised Multitask Learners](https://scholar.google.com/scholar?q=Language+Models+are+Unsupervised+Multitask+Learners) | 2019 | `radford2019language` |
| BERT | [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://scholar.google.com/scholar?q=BERT+Pre-training+of+Deep+Bidirectional+Transformers) | 2019.06 | `devlin2019bert` |
| XLNet | [XLNet: Generalized Autoregressive Pretraining for Language Understanding](https://scholar.google.com/scholar?q=XLNet+Generalized+Autoregressive+Pretraining) | 2019.06 | `yang2019xlnet` |
| RoBERTa | [RoBERTa: A Robustly Optimized BERT Pretraining Approach](https://scholar.google.com/scholar?q=RoBERTa+A+Robustly+Optimized+BERT+Pretraining+Approach) | 2019.07.26 | `liu2019roberta` |
| T5 | [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://scholar.google.com/scholar?q=Exploring+the+Limits+of+Transfer+Learning+with+a+Unified+Text-to-Text+Transformer) | 2019.10.23 | `raffel2020exploring` |
| GPT-3 | [Language Models are Few-Shot Learners](https://scholar.google.com/scholar?q=Language+Models+are+Few-Shot+Learners) | 2020.05.28 | `brown2020language` |
| Gopher | [Scaling Language Models: Methods, Analysis & Insights from Training Gopher](https://scholar.google.com/scholar?q=Scaling+Language+Models+Methods+Analysis+Insights+Gopher) | 2021.11.08 | `rae2021scaling` |
| Chinchilla | [Training Compute-Optimal Large Language Models](https://scholar.google.com/scholar?q=Training+Compute-Optimal+Large+Language+Models) | 2022.03.29 | `hoffmann2022training` |
| OPT | [OPT: Open Pre-trained Transformer Language Models](https://scholar.google.com/scholar?q=OPT+Open+Pre-trained+Transformer+Language+Models) | 2022.05.02 | `zhang2022opt` |
| UL2 | [UL2: Unifying Language Learning Paradigms](https://scholar.google.com/scholar?q=UL2+Unifying+Language+Learning+Paradigms) | 2022.05.10 | `tay2022ul2` |
| BLOOM | [BLOOM: A 176B-parameter Open-access Multilingual Language Model](https://scholar.google.com/scholar?q=BLOOM+A+176B-parameter+Open-access+Multilingual+Language+Model) | 2022.11.09 | `workshop2022bloom` |
| LLaMA | [LLaMA: Open and Efficient Foundation Language Models](https://scholar.google.com/scholar?q=LLaMA+Open+and+Efficient+Foundation+Language+Models) | 2023.02.27 | `touvron2023llama` |
| PaLM | [PaLM: Scaling Language Modeling with Pathways](https://scholar.google.com/scholar?q=PaLM+Scaling+Language+Modeling+with+Pathways) | 2023.10.11 | `chowdhery2023palm` |

## 2. Vision-Language Models (VLMs)

Vision-Language Models establish connections between visual information and natural language. They learn joint visual and linguistic representations, providing important foundations for cross-modal understanding and vision-language tasks.

| Model | Representative Paper | Year | Citation Key |
|---|---|---|---|
| ViLBERT | [ViLBERT: Pretraining Task-Agnostic Visiolinguistic Representations for Vision-and-Language Tasks](https://scholar.google.com/scholar?q=ViLBERT+Pretraining+Task-Agnostic+Visiolinguistic+Representations) | 2019.08 | `lu2019vilbert` |
| VisualBERT | [VisualBERT: A Simple and Performant Baseline for Vision and Language](https://scholar.google.com/scholar?q=VisualBERT+A+Simple+and+Performant+Baseline+for+Vision+and+Language) | 2019.08.09 | — |
| LXMERT | [LXMERT: Learning Cross-Modality Encoder Representations from Transformers](https://scholar.google.com/scholar?q=LXMERT+Learning+Cross-Modality+Encoder+Representations) | 2019.08.20 | `tan2019lxmert` |
| VL-BERT | [VL-BERT: Pre-training of Generic V+L Representations](https://scholar.google.com/scholar?q=VL-BERT+Pre-training+of+Generic+V%2BL+Representations) | 2019.08.22 | `su2019vl` |
| UNITER | [UNITER: UNiversal Image-TExt Representation Learning](https://scholar.google.com/scholar?q=UNITER+UNiversal+Image-TExt+Representation+Learning) | 2020.09.24 | `chen2020uniter` |
| CLIP | [Learning Transferable Visual Models From Natural Language Supervision](https://scholar.google.com/scholar?q=Learning+Transferable+Visual+Models+From+Natural+Language+Supervision) | 2021.02.26 | `radford2021learning` |
| BLIP | [BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation](https://scholar.google.com/scholar?q=BLIP+Bootstrapping+Language-Image+Pre-training) | 2022.02.15 | `li2022blip` |
| Flamingo | [Flamingo: A Visual Language Model for Few-Shot Learning](https://scholar.google.com/scholar?q=Flamingo+A+Visual+Language+Model+for+Few-Shot+Learning) | 2022.04.29 | `alayrac2022flamingo` |
| BLIP-2 | [BLIP-2: Bootstrapping Language-Image Pretraining with Frozen Image Encoders and Large Language Models](https://scholar.google.com/scholar?q=BLIP-2+Bootstrapping+Language-Image+Pretraining) | 2023.01.30 | `li2023blip2` |

## 3. Multimodal Large Language Models (MLLMs)

Multimodal Large Language Models extend language models with the ability to process and reason over multiple modalities, particularly visual and textual information. By integrating visual encoders, modality alignment mechanisms, and language models, MLLMs enable more flexible multimodal interaction and understanding.

| Model | Representative Paper | Year | Citation Key |
|---|---|---|---|
| Kosmos-1 | [Language Is Not All You Need: Aligning Perception with Language Models](https://scholar.google.com/scholar?q=Language+Is+Not+All+You+Need+Aligning+Perception+with+Language+Models) | 2023.02.27 | `huang2023language` |
| InstructBLIP | [InstructBLIP: Towards General-Purpose Vision-Language Models with Instruction Tuning](https://scholar.google.com/scholar?q=InstructBLIP+Towards+General-Purpose+Vision-Language+Models) | 2023.03.11 | `dai2023instructblip` |
| GPT-4V | [GPT-4 Technical Report](https://scholar.google.com/scholar?q=GPT-4+Technical+Report) | 2023.03.15 | `achiam2023gpt` |
| LLaVA | [Visual Instruction Tuning](https://scholar.google.com/scholar?q=Visual+Instruction+Tuning) | 2023.04.17 | `liu2023visual` |
| MiniGPT-4 | [MiniGPT-4: Enhancing Vision-Language Understanding with GPT-4-level Capabilities](https://scholar.google.com/scholar?q=MiniGPT-4+Enhancing+Vision-Language+Understanding) | 2023.04.20 | `zhu2023minigpt` |
| mPLUG-Owl | [mPLUG-Owl: Modularization Empowers Large Language Models with Multimodality](https://scholar.google.com/scholar?q=mPLUG-Owl+Modularization+Empowers+Large+Language+Models) | 2023.04.27 | `ye2023mplug` |
| Shikra | [Shikra: Unleashing Multimodal LLM's Referential Dialogue Magic](https://scholar.google.com/scholar?q=Shikra+Unleashing+Multimodal+LLM+Referential+Dialogue+Magic) | 2023.06.27 | `chen2023shikra` |
| OpenFlamingo | [OpenFlamingo: An Open-Source Framework for Training Large Autoregressive Vision-Language Models](https://scholar.google.com/scholar?q=OpenFlamingo+An+Open-Source+Framework+for+Training+Large+Autoregressive+Vision-Language+Models) | 2023.08.02 | `awadalla2023openflamingo` |

## 4. Diffusion Models (DMs)

Diffusion Models learn data distributions through iterative denoising processes. They have demonstrated strong generative capabilities and have also been explored for planning and behavior synthesis, offering alternative approaches to generative modeling and decision-making.

| Model | Representative Paper | Year | Citation Key |
|---|---|---|---|
| DDPM | [Denoising Diffusion Probabilistic Models](https://scholar.google.com/scholar?q=Denoising+Diffusion+Probabilistic+Models) | 2020.06.19 | `ho2020denoising` |
| DDIM | [Denoising Diffusion Implicit Models](https://scholar.google.com/scholar?q=Denoising+Diffusion+Implicit+Models) | 2020.10.06 | `song2020denoising` |
| Improved DDPM | [Improved Denoising Diffusion Probabilistic Models](https://scholar.google.com/scholar?q=Improved+Denoising+Diffusion+Probabilistic+Models) | 2021.02.18 | `nichol2021improved` |
| Latent Diffusion (LDM) | [High-Resolution Image Synthesis with Latent Diffusion Models](https://scholar.google.com/scholar?q=High-Resolution+Image+Synthesis+with+Latent+Diffusion+Models) | 2021.12.20 | `rombach2022high` |
| Planning with Diffusion | [Planning with Diffusion for Flexible Behavior Synthesis](https://scholar.google.com/scholar?q=Planning+with+Diffusion+for+Flexible+Behavior+Synthesis) | 2022.05.20 | `janner2022planning` |
| Imagen | [Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding](https://scholar.google.com/scholar?q=Photorealistic+Text-to-Image+Diffusion+Models+with+Deep+Language+Understanding) | 2022.05.23 | `saharia2022photorealistic` |
| Classifier-Free Guidance | [Classifier-Free Diffusion Guidance](https://scholar.google.com/scholar?q=Classifier-Free+Diffusion+Guidance) | 2022.07.26 | `ho2022classifier` |

## 5. World Models (WMs)

World Models learn representations of environments and their dynamics, enabling agents to predict future states and support planning through learned models or latent imagination. They provide an important research direction for model-based decision-making and intelligent autonomous systems.

| Model | Representative Paper | Year | Citation Key |
|---|---|---|---|
| MuZero | [Mastering Atari, Go, Chess and Shogi by Planning with a Learned Model](https://scholar.google.com/scholar?q=Mastering+Atari+Go+Chess+and+Shogi+by+Planning+with+a+Learned+Model) | 2019.11.19 | `schrittwieser2020mastering` |
| Dreamer | [Dream to Control: Learning Behaviors by Latent Imagination](https://scholar.google.com/scholar?q=Dream+to+Control+Learning+Behaviors+by+Latent+Imagination) | 2019.12.03 | `hafner2019dream` |
| World Model as a Graph | [World Model as a Graph: Learning Latent Landmarks for Planning](https://scholar.google.com/scholar?q=World+Model+as+a+Graph+Learning+Latent+Landmarks+for+Planning) | 2020.11.25 | `zhang2021world` |
| DayDreamer | [DayDreamer: World Models for Physical Robot Learning](https://scholar.google.com/scholar?q=DayDreamer+World+Models+for+Physical+Robot+Learning) | 2022.06.28 | `wu2023daydreamer` |
| DreamerV3 | [Mastering Diverse Domains through World Models](https://scholar.google.com/scholar?q=Mastering+Diverse+Domains+through+World+Models) | 2023.01.10 | `hafner2023mastering` |
| UniZero | [UniZero: Generalized and Efficient Planning with Scalable Latent World Models](https://scholar.google.com/scholar?q=UniZero+Generalized+and+Efficient+Planning+with+Scalable+Latent+World+Models) | 2024.06.15 | `pu2024unizero` |
| WorldGPT | [WorldGPT: Empowering LLM as Multimodal World Model](https://scholar.google.com/scholar?q=WorldGPT+Empowering+LLM+as+Multimodal+World+Model) | 2024.10.28 | `ge2024worldgpt` |
| Interpreting MuZero | [Interpreting the Learned Model in MuZero Planning](https://scholar.google.com/scholar?q=Interpreting+the+Learned+Model+in+MuZero+Planning) | 2024.11.07 | `guei2024interpreting` |

## Scope and Notes

- The five categories reflect the `type` classification in the current model-paper collection.
- The listed papers represent selected milestones and examples, rather than an exhaustive list of all models in each category.
- The roadmap focuses on model families and their development. It is complementary to the survey's autonomous-driving QA task taxonomy and the dataset and benchmark collection.
- The citation keys are provided for reference and can be used to connect the roadmap entries with the corresponding bibliography.

