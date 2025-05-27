# Bias-Mitigation


```
- Contributions are highly welcome, and feel free to submit a pull request or contact me.
```
## Contents


## Papers

### Survey
### Fairness (Human Bias)
Constructing Fair Latent Space for Intersection of Fairness and Explainability AAAI 2025 [paper](https://ojs.aaai.org/index.php/AAAI/article/view/32436)

FairCoT: Enhancing Fairness in Text-to-Image Generation via Chain of Thought Reasoning with Multimodal Large Language Models Submited to ICLR 2025 [paper](https://openreview.net/forum?id=WGWoRZb0pT)

FairRAG: Fair Human Generation via Fair Retrieval Augmentation CVPR 2024 [paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Shrestha_FairRAG_Fair_Human_Generation_via_Fair_Retrieval_Augmentation_CVPR_2024_paper.pdf)

Unified Concept Editing in Diffusion Models WACV 2024 [paper](https://arxiv.org/pdf/2308.14761)

VersusDebias: Universal Zero-Shot Debiasing for Text-to-Image Models via SLM-Based Prompt Engineering and Generative Adversary arXiv 2024 [paper](https://arxiv.org/pdf/2407.19524)

Easily Accessible Text-to-Image Generation Amplifies Demographic Stereotypes at Large Scale FAccT 2023 [paper](https://arxiv.org/pdf/2211.03759)

Instructing Text-to-Image Generation Models on Fairness arXiv 2023 [paper](https://arxiv.org/pdf/2302.10893)

### Domain/Dataset
## 🧩 Comparison of Syn2Real and Real2Real Domain Adaptation

| Aspect               | (Synthetic → Real)                                                                 | (Real → Real)                                                                 |
|----------------------|---------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| **Data Source**      | Rendered images from simulators or 3D models (e.g., ShapeNet, GTA5)                         | Real-world images captured under varying conditions (e.g., different cities, devices)   |
| **Typical Datasets** | Syn2Real, GTA5 → Cityscapes, Virtual KITTI → KITTI                                          | Cityscapes → ACDC, Office-31, VisDA-C                                             |
| **Bias Types**  | - **Style Bias**: Synthetic images often lack realistic textures and noise<br>- **Lighting Bias**: Differences in illumination between synthetic and real images<br>- **Background Bias**: Simplified or unrealistic backgrounds in synthetic data | - **Device Bias**: Variations causesd by cameras or sensors<br>- **Environmental Bias**: Changes in weather, time (Low-light: illuminations, sensor's noise), or location<br>- **Background Bias**: Diverse real-world backgrounds affecting object appearance |


### Learning Bias
### Measurement Bias



