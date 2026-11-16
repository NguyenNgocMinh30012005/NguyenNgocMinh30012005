# Nguyen Ngoc Minh

DSAI @ HUST · Computer vision · Generative models · Robot learning

I build personal projects and research experiments in machine learning, with an
emphasis on runnable code, reproducible evaluation, and documented limitations.
This page is a directory of my public work, including course projects and forks.

[Email](mailto:nguyenngocminh2005bn@gmail.com) · Vietnam

## Projects to explore

| Project | What it contains | Scope |
|---|---|---|
| [T2I Search Experiments](https://github.com/NguyenNgocMinh30012005/t2i-search-experiments) | Config-driven orchestration for paired Classical Search BFS and Soft VASR text-to-image experiments on TPU/BF16. | Experiment harness; model weights and raw results are external. |
| [LangVWM-RL](https://github.com/NguyenNgocMinh30012005/LangVWM-RL) | Language-conditioned visual world models, action chunks, and candidate reranking. | CPU-friendly prototype in a synthetic 2D tabletop environment. |
| [Sparse-View 3D Reconstruction](https://github.com/NguyenNgocMinh30012005/Computer_vision_2025.2) | MV-DUSt3R+ reconstruction, source-depth correction, and predicted-depth experiments. | Course research project; validated RGB-D reference and experimental estimated-depth track. |
| [Virtual Try-On Experiments](https://github.com/NguyenNgocMinh30012005/Project_Phase2) | Four ComfyUI-based try-on pipelines with masks, LoRA, local inpainting, and comparison grids. | GPU experiment suite; quality depends on masks, crops, and garment type. |
| [Plant Disease Classification](https://github.com/NguyenNgocMinh30012005/DeepLearningProject2025.1) | Stable Diffusion + LoRA synthetic data and ResNet classifier evaluation. | Course project comparing real, synthetic, and mixed training data. |
| [Customer Churn Dashboard](https://github.com/NguyenNgocMinh30012005/DataVis_2025.2) | Power BI dashboards and a Random Forest pipeline for churn analysis. | Course project; includes evaluation metrics and class-imbalance limitations. |

## Related robot-learning experiments

These repositories explore related ideas with different world-model interfaces.

| Project | Main idea | Environment |
|---|---|---|
| [DreamACT](https://github.com/NguyenNgocMinh30012005/DreamACT) | ACT-lite behavior cloning with a scalar progress/risk model for action reranking. | CPU-friendly 2D PushT-lite. |
| [DreamJEPA](https://github.com/NguyenNgocMinh30012005/DreamJEPA) | JEPA-style latent prediction with a progress head for action reranking. | CPU-friendly 2D PushT-lite with state observations. |

These are small research prototypes. Their READMEs describe the implemented
interfaces and limitations; they do not establish real-robot performance.

## Coursework and system design

| Repository | Contents |
|---|---|
| [AIMS / Java OOP](https://github.com/NguyenNgocMinh30012005/IT3100E.744516.20241.20235533.NguyenNgocMinh) | Java media-store domain model, cart/store workflows, GUI exercises, and UML artifacts. |
| [AI-Assisted CPU Scheduling](https://github.com/NguyenNgocMinh30012005/OperatingSystem2024.2) | XGBoost and PPO scheduling experiments; fork of [nhthai23-05/OperatingSystem2024.2](https://github.com/nhthai23-05/OperatingSystem2024.2). |
| [Ecopark Bicycle Parking Design](https://github.com/NguyenNgocMinh30012005/Project_System_Design) | Draft business analysis, requirements, use cases, and traceability documents; fork of [KietLe2504/Project_System_Design](https://github.com/KietLe2504/Project_System_Design). |

## Reproductions and upstream references

| Repository | Purpose | Upstream |
|---|---|---|
| [arc-modulo](https://github.com/NguyenNgocMinh30012005/arc-modulo) | Diffusion test-time alignment reproduction kit for Null-TTA, DAS, FK Steering, and FK Correctors. | [sontungkieu/arc-modulo](https://github.com/sontungkieu/arc-modulo) |
| [flow-to-better](https://github.com/NguyenNgocMinh30012005/flow-to-better) | Offline preference-based reinforcement learning reference implementation. | [Zzl35/flow-to-better](https://github.com/Zzl35/flow-to-better) |

Both are forks. Please refer to the upstream projects, citations, and repository
history for authorship and the original implementations.

## Early-stage work

- [Image Generation](https://github.com/NguyenNgocMinh30012005/Image_Generation)
  currently contains a placeholder README; implementation and usage instructions
  have not been published.

## Using or contributing to a project

Start with the individual repository's README for setup, data/model requirements,
evaluation commands, and known limitations. Check its license and upstream terms
before reuse; licensing is not yet standardized across these repositories.

For questions, reproducibility reports, or focused improvements, use the relevant
repository's Issues or pull requests where enabled. Include the command, environment,
and observed behavior when reporting a problem. For a fork, check the upstream
project's contribution instructions first.
