# Datasets and Benchmarks

## Overview

This section provides a collection of representative datasets and benchmarks for question answering (QA) in autonomous driving.

These datasets cover a variety of tasks, including visual question answering, counterfactual reasoning, scene understanding, spatial reasoning, perception, prediction, and planning. They involve different data sources and modalities, such as real-world driving videos, camera images, LiDAR point clouds, textual descriptions, and trajectories.

The table summarizes their publication information, supported modalities, QA tasks, dataset scales, and available links to original papers, official project repositories, and dataset websites.

## Dataset Comparison

| Dataset / Paper | Year / Venue | Modalities | QA Tasks | Scale | Link |
|---|---|---|---|---|---|
| SUTD-TrafficQA: A Question Answering Benchmark and an Efficient Network for Video Reasoning | 2021 / CVPR | V, T | VQA, CQA, P2 | 10,080 videos, 62,535 QA pairs | [https://openaccess.thecvf.com/content/CVPR2021/html/Xu_SUTD-TrafficQA_A_Question_Answering_Benchmark_and_an_Efficient_Network_for_CVPR_2021_paper.html](https://openaccess.thecvf.com/content/CVPR2021/html/Xu_SUTD-TrafficQA_A_Question_Answering_Benchmark_and_an_Efficient_Network_for_CVPR_2021_paper.html) <br> [https://github.com/SUTDCV/SUTD-TrafficQA](https://github.com/SUTDCV/SUTD-TrafficQA) |
| DRAMA: Joint Risk Localization and Captioning in Driving | 2023 / WACV | V, T | VQA, Visual Reasoning | 17,785 driving scenarios | [https://openaccess.thecvf.com/content/WACV2023/html/Malla_DRAMA_Joint_Risk_Localization_and_Captioning_in_Driving_WACV_2023_paper.html](https://openaccess.thecvf.com/content/WACV2023/html/Malla_DRAMA_Joint_Risk_Localization_and_Captioning_in_Driving_WACV_2023_paper.html) <br> [https://usa.honda-ri.com/drama](https://usa.honda-ri.com/drama) |
| DriveLM: Driving with Graph Visual Question Answering | 2024 / ECCV | I, T, Tra. | GVQA, P1, P2, P3 | 4,871 frames, 443K QA pairs | [https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/6870_ECCV_2024_paper.php](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/6870_ECCV_2024_paper.php) <br> [https://github.com/OpenDriveLab/DriveLM](https://github.com/OpenDriveLab/DriveLM) |
| LingoQA: Video Question Answering for Autonomous Driving | 2024 / ECCV | V, T | VQA, SU | 28K scenarios, 419.9K QA pairs | [https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/9911_ECCV_2024_paper.php](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/9911_ECCV_2024_paper.php) <br> [https://github.com/wayveai/LingoQA](https://github.com/wayveai/LingoQA) |
| NuScenes-QA: A Multi-Modal Visual Question Answering Benchmark for Autonomous Driving Scenario | 2024 / AAAI | I, L, T | VQA | 34,149 scenes, 460K QA pairs | [https://ojs.aaai.org/index.php/AAAI/article/view/28253](https://ojs.aaai.org/index.php/AAAI/article/view/28253) <br> [https://github.com/qiantianwen/NuScenes-QA](https://github.com/qiantianwen/NuScenes-QA) |
| NuScenes-MQA: Integrated Evaluation of Captions and QA for Autonomous Driving Datasets Using Markup Annotations | 2024 / WACV Workshops | I, T | VQA, Caption QA, Reasoning | 34,149 scenes, 1.5M QA pairs | [https://arxiv.org/abs/2312.06352](https://arxiv.org/abs/2312.06352) <br> [https://github.com/turingmotors/NuScenes-MQA](https://github.com/turingmotors/NuScenes-MQA) |
| VLAAD: Vision and Language Assistant for Autonomous Driving | 2024 / WACV Workshops | V, T | QA, Caption, Reasoning | 11K videos, 64K instruction pairs | [https://openaccess.thecvf.com/content/WACV2024W/LLVM-AD/html/Park_VLAAD_Vision_and_Language_Assistant_for_Autonomous_Driving_WACVW_2024_paper.html](https://openaccess.thecvf.com/content/WACV2024W/LLVM-AD/html/Park_VLAAD_Vision_and_Language_Assistant_for_Autonomous_Driving_WACVW_2024_paper.html) <br> [https://github.com/sungyeonparkk/vision-assistant-for-driving](https://github.com/sungyeonparkk/vision-assistant-for-driving) |
| Driving with LLMs: Fusing Object-Level Vector Modality for Explainable Autonomous Driving | 2024 / ICRA | I, T | VQA, P1, P2 | 160K QA pairs, 10K scenarios | [https://ieeexplore.ieee.org/document/10611018/](https://ieeexplore.ieee.org/document/10611018/) |
| MAPLM: A Real-World Large-Scale Vision-Language Benchmark for Map and Traffic Scene Understanding | 2024 / CVPR | I, L, M, T | Caption, VQA | 2M frames, 161.6K QA pairs | [https://openaccess.thecvf.com/content/CVPR2024/html/Cao_MAPLM_A_Real-World_Large-Scale_Vision-Language_Benchmark_for_Map_and_Traffic_Scene_Understanding_CVPR_2024_paper.html](https://openaccess.thecvf.com/content/CVPR2024/html/Cao_MAPLM_A_Real-World_Large-Scale_Vision-Language_Benchmark_for_Map_and_Traffic_Scene_Understanding_CVPR_2024_paper.html) <br> [https://github.com/LLVM-AD/MAPLM](https://github.com/LLVM-AD/MAPLM) |
| DRIVEVLM: The Convergence of Autonomous Driving and Large Vision-Language Models | 2024 / arXiv | I, T, Tra. | SU, P3 | 1,000 video clips | [https://arxiv.org/abs/2402.12289](https://arxiv.org/abs/2402.12289) |
| DriveMLLM: A Benchmark for Spatial Understanding with Multimodal Large Language Models in Autonomous Driving | 2024 / arXiv | I, T | Spatial QA, VQA | 880 images, 8 spatial QA tasks | [https://arxiv.org/abs/2411.13112](https://arxiv.org/abs/2411.13112) <br> [https://github.com/XiandaGuo/Drive-MLLM](https://github.com/XiandaGuo/Drive-MLLM) |
| TOKEN | 2024 / arXiv | V, M, T | VQA, P3 QA | 150K P1 QAs | [https://scholar.google.com/scholar?q=TOKEN+autonomous+driving+150K+P1+QA](https://scholar.google.com/scholar?q=TOKEN+autonomous+driving+150K+P1+QA) |
| OmniDrive: A Holistic Vision-Language Dataset for Autonomous Driving with Counterfactual Reasoning | 2025 / CVPR | I, T, Tra. | CQA, P1, P3, Reasoning | Based on nuScenes | [https://openaccess.thecvf.com/content/CVPR2025/html/Wang_OmniDrive_A_Holistic_Vision-Language_Dataset_for_Autonomous_Driving_with_Counterfactual_CVPR_2025_paper.html](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_OmniDrive_A_Holistic_Vision-Language_Dataset_for_Autonomous_Driving_with_Counterfactual_CVPR_2025_paper.html) <br> [https://github.com/NVlabs/OmniDrive](https://github.com/NVlabs/OmniDrive) |
| Holistic Autonomous Driving Understanding by Bird's-Eye-View Injected Multi-Modal Large Models | 2024 / CVPR | I, T, Tra. | Caption, P3, CQA | 850 videos, 91.4K QA pairs | [https://openaccess.thecvf.com/content/CVPR2024/html/Ding_Holistic_Autonomous_Driving_Understanding_by_Birds-Eye-View_Injected_Multi-Modal_Large_Models_CVPR_2024_paper.html](https://openaccess.thecvf.com/content/CVPR2024/html/Ding_Holistic_Autonomous_Driving_Understanding_by_Birds-Eye-View_Injected_Multi-Modal_Large_Models_CVPR_2024_paper.html) <br> [https://github.com/xmed-lab/NuInstruct](https://github.com/xmed-lab/NuInstruct) |
| AutoDrive-QA: Automated Generation of Multiple-Choice Questions for Autonomous Driving Datasets Using Large Vision-Language Models | 2025 / arXiv | I, L, T, V | VQA, P1, P2, P3 | 5,125 MCQs | [https://arxiv.org/abs/2503.15778](https://arxiv.org/abs/2503.15778) |
| NuPlanQA: A Large-Scale Dataset and Benchmark for Multi-View Driving Scene Understanding in Multi-Modal Large Language Models | 2025 / ICCV | I, T | VQA, Reasoning, P1, Action | 1M trajectories / QA pairs | [https://openaccess.thecvf.com/content/ICCV2025/html/Park_NuPlanQA_A_Large-Scale_Dataset_and_Benchmark_for_Multi-View_Driving_Scene_ICCV_2025_paper.html](https://openaccess.thecvf.com/content/ICCV2025/html/Park_NuPlanQA_A_Large-Scale_Dataset_and_Benchmark_for_Multi-View_Driving_Scene_ICCV_2025_paper.html) |
| V2V-QA | 2025 / arXiv | L, T | VQA, Reasoning, P3 QA | 48K frames, 1.45M QA pairs | [https://scholar.google.com/scholar?q=V2V-QA+autonomous+driving+1.45M+QA+pairs](https://scholar.google.com/scholar?q=V2V-QA+autonomous+driving+1.45M+QA+pairs) |
| DriveLMM-o1 | 2025 / arXiv | I, L, T | VQA, P1, P2, P3, Reasoning | 1,962 scenes, 18,507 QA pairs | [https://scholar.google.com/scholar?q=DriveLMM-o1+autonomous+driving](https://scholar.google.com/scholar?q=DriveLMM-o1+autonomous+driving) |
| nuScenes-SpatialQA | 2025 / arXiv | I, L, T | Spatial Understanding QA, Reasoning QA | 3.5M QA pairs | [https://taco-group.github.io/NuScenes-SpatialQA/](https://taco-group.github.io/NuScenes-SpatialQA/) |
| Box-Qaymo | 2025 / arXiv | I, T | VQA, Reasoning | 101 scenes, 20,779 QA pairs | [https://scholar.google.com/scholar?q=Box-Qaymo+autonomous+driving](https://scholar.google.com/scholar?q=Box-Qaymo+autonomous+driving) |

## Notes

### Modalities

- **I** = RGB Image
- **V** = Video
- **T** = Text
- **L** = LiDAR
- **M** = HD Map
- **Tra.** = Trajectory

### QA Tasks

- **VQA** = Visual Question Answering
- **CQA** = Counterfactual Question Answering
- **Caption** = Scene/Image Captioning
- **Reasoning** = Causal, spatial, or temporal reasoning
- **SU** = Spatial Understanding
- **QA** = General Question Answering
- **P1** = Perception-level QA
- **P2** = Prediction-focused QA
- **P3** = Planning and behavior QA
- **GVQA** = Graph-based Visual Question Answering

### Dataset Statistics

- **MCQ** = Multiple-choice Questions
- **Evaluation QA** = QA pairs used for evaluation
- **Training QA** = QA pairs used for training

### Links and Availability

- The URLs in the final column link to the corresponding paper, official project repository, or dataset website.
- Google Scholar search links are used for entries whose official publication pages have not yet been verified.
- A dash (—) indicates that an additional public resource link has not yet been added. It does not necessarily mean that the dataset is unavailable.

## Contributions

We welcome contributions, corrections, and suggestions. If you find missing datasets, incorrect publication information, or additional official resources, please feel free to open an issue or submit a pull request.
