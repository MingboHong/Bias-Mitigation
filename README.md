# Bias-Mitigation


```
- Contributions are highly welcome, and feel free to submit a pull request or contact me.
```
## Contents


## Papers

### Survey
### Fairness (Human Bias)
| Title                                                                                                                | Venue       | Paper                                                                                                                     | Code | Note                   |
|----------------------------------------------------------------------------------------------------------------------|------------------------|----------------------------------------------------------------------------------------------------------------------------------|------|------------------------|
| Constructing Fair Latent Space for Intersection of Fairness and Explainability                                      | AAAI 2025              | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32436)                                                                 | —    |  |
| FairCoT: Enhancing Fairness in Text-to-Image Generation via Chain of Thought Reasoning with Multimodal LLMs         | ICLR 2025 (Submitted)  | [Paper](https://openreview.net/forum?id=WGWoRZb0pT)                                                                             | —    |      |
| FairRAG: Fair Human Generation via Fair Retrieval Augmentation                                                      | CVPR 2024              | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Shrestha_FairRAG_Fair_Human_Generation_via_Fair_Retrieval_Augmentation_CVPR_2024_paper.pdf) | —    |           |
| Unified Concept Editing in Diffusion Models                                                                         | WACV 2024              | [Paper](https://arxiv.org/pdf/2308.14761)                                                                                       |[Code](https://github.com/rohitgandikota/unified-concept-editing)    |    |
| VersusDebias: Universal Zero-Shot Debiasing for Text-to-Image Models via SLM-Based Prompt Engineering and Adversary | arXiv 2024             | [Paper](https://arxiv.org/pdf/2407.19524)                                                                                       |[Code](https://github.com/versusdebias/versusdebias)    |             |
| Easily Accessible Text-to-Image Generation Amplifies Demographic Stereotypes at Large Scale                         | FAccT 2023             | [Paper](https://arxiv.org/pdf/2211.03759)                                                                                       | [Data](https://github.com/vinid/text-to-image-bias)    |         |
| Instructing Text-to-Image Generation Models on Fairness                                                             | arXiv 2023             | [Paper](https://arxiv.org/pdf/2302.10893)                                                                                       | [Code](http://github.com/ml-research/Fair-Diffusion)    |        |



### Domain

### Domain Adaptation
| Title                                                                                                                | Venue       | Paper                                                                                                                      | Code | Note                   |
|-----------------------------------------------------|------------------------|---------------------------------------------|------|------------------------|
| CAT: Exploiting Inter-Class Dynamics for Domain Adaptive Object Detection                          | CVPR 2024              | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Kennerley_CAT_Exploiting_Inter-Class_Dynamics_for_Domain_Adaptive_Object_Detection_CVPR_2024_paper.pdf)                                                                 | [Code](https://github.com/w1oves/Rein)    |  |
| Parameter Efficient Self-Supervised Geospatial Domain Adaptation  | CVPR 2024   | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Scheibenreif_Parameter_Efficient_Self-Supervised_Geospatial_Domain_Adaptation_CVPR_2024_paper.pdf)                                                                             | [Code](https://github.com/HSG-AIML/GDA)    |   GeoAI   |
| Open-Set Domain Adaptation for Semantic Segmentation  | CVPR 2024   | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Choe_Open-Set_Domain_Adaptation_for_Semantic_Segmentation_CVPR_2024_paper.pdf)      |[Code](https://github.com/HSG-AIML/GDA)
| Stable Neighbor Denoising for Source-free Domain Adaptive Segmentation  | CVPR 2024   | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhao_Stable_Neighbor_Denoising_for_Source-free_Domain_Adaptive_Segmentation_CVPR_2024_paper.pdf)      |[Code](https://github.com/DZhaoXd/SND)
| Boosting Object Detection with Zero-Shot Day-Night Domain Adaptation  | CVPR 2024   | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Du_Boosting_Object_Detection_with_Zero-Shot_Day-Night_Domain_Adaptation_CVPR_2024_paper.pdf)      |[Code](https://github.com/ZPDu/DAI-Net)
| UPRE: Zero-Shot Domain Adaptation for Object Detection via Unified Prompt and Representation Enhancement  | ICCV 2025   | [Paper](https://arxiv.org/pdf/2507.00721)      |Code












#### 🧩 Comparison of Syn2Real and Real2Real Domain Adaptation

| Aspect               | (Synthetic → Real)                                                                 | (Real → Real)                                                                 |
|----------------------|---------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| **Data Source**      | Rendered images from simulators or 3D models (e.g., ShapeNet, GTA5)                         | Real-world images captured under varying conditions (e.g., different cities, devices)   |
| **Typical Datasets** | Syn2Real, GTA5 → Cityscapes, Virtual KITTI → KITTI                                          | Cityscapes → ACDC, Office-31, VisDA-C                                             |
| **Bias Types**  | - **Style Bias**: Synthetic images often lack realistic textures and noise<br>- **Lighting Bias**: Differences in illumination between synthetic and real images<br>- **Background Bias**: Simplified or unrealistic backgrounds in synthetic data | - **Style Bias**: textures <br> - **Device Bias**: Variations causesd by cameras or sensors<br>- **Environmental Bias**: Changes in weather, time (Low-light: illuminations, sensor's noise), or location<br> |



### Domain Generalization
| Title                                                                                                                | Venue       | Paper                                                                                                                      | Code | Note                   |
|-----------------------------------------------------|------------------------|---------------------------------------------|------|------------------------|
| Stronger, Fewer, & Superior: Harnessing Vision Foundation Models for Domain Generalized Semantic Segmentation                          | CVPR 2024              | [Paper](https://arxiv.org/pdf/2312.04265v5)                                                                 | [Code](https://github.com/w1oves/Rein)    |  |
| SoRA: Singular Value Decomposed Low-Rank Adaptation for Domain Generalizable Representation Learning  | CVPR 2025 (Highlight)  | [Paper](https://arxiv.org/pdf/2412.04077v1)                                                                             | [Code](https://github.com/ysj9909/SoMA)    |      |
| A Simple Recipe for Language-guided Domain Generalized Segmentation  | CVPR 2024   | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Fahes_A_Simple_Recipe_for_Language-guided_Domain_Generalized_Segmentation_CVPR_2024_paper.pdf)      |[Code](https://astra-vision.github.io/FAMix/)
| Collaborating Foundation Models for Domain Generalized Semantic Segmentation  | CVPR 2024   | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Benigmim_Collaborating_Foundation_Models_for_Domain_Generalized_Semantic_Segmentation_CVPR_2024_paper.pdf)     |[Code](https://github.com/yasserben/CLOUDS)
| Unified Language-driven Zero-shot Domain Adaptation  | CVPR 2024   | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Yang_Unified_Language-driven_Zero-shot_Domain_Adaptation_CVPR_2024_paper.pdf)      |[Code](https://senqiaoyang.com/project/ulda/)
| Unbiased Faster R-CNN for Single-source Domain Generalized Object Detection  | CVPR 2024   | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_Unbiased_Faster_R-CNN_for_Single-source_Domain_Generalized_Object_Detection_CVPR_2024_paper.pdf)      |



#### Counting
| Title                                                                                                                | Venue       | Paper                                                                                                                      | Code | Note                   |
|-----------------------------------------------------|------------------------|---------------------------------------------|------|------------------------|
| Single Domain Generalization for Crowd Counting  | CVPR 2024   | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Peng_Single_Domain_Generalization_for_Crowd_Counting_CVPR_2024_paper.pdf)      |[Code](https://github.com/Shimmer93/MPCount)

#### ReID
| Title                                                                                                                | Venue       | Paper                                                                                                                      | Code | Note                   |
|-----------------------------------------------------|------------------------|---------------------------------------------|------|------------------------|
| Day-Night Cross-domain Vehicle Re-identification  | CVPR 2024   | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_Day-Night_Cross-domain_Vehicle_Re-identification_CVPR_2024_paper.pdf)      |[Code](https://github.com/chenjingong/DN-ReID)
### Learning Bias
| Title                                                                                                                | Venue       | Paper                                                                                                                      | Code | Note                   |
|-----------------------------------------------------|------------------------|---------------------------------------------|------|------------------------|
| Shortcut Learning in Deep Neural Networks  | Nature Machine Intelligence   | [Paper](https://arxiv.org/pdf/2004.07780)                                                                             | [Code](https://github.com/rgeirhos/shortcut-perspective)    |      |
| Invariant Risk Minimization  | arXiv   | [Paper](https://arxiv.org/pdf/1907.02893)                                                                             | [Code](https://github.com/facebookresearch/InvariantRiskMinimization)    |      |
| An Empirical Study of Invariant Risk Minimization on Deep Models  | ICML2021 workshop   | [Paper](https://www.gatsby.ucl.ac.uk/~balaji/udl2021/accepted-papers/UDL2021-paper-044.pdf)                                                                             | |      |
| Sparse Invariant Risk Minimization  | ICML2022   | [Paper](https://proceedings.mlr.press/v162/zhou22e/zhou22e.pdf)                                                                             |     |  Invariant Risk Minimization  |
| Bayesian Invariant Risk Minimization | CVPR 2022  | [Paper](https://proceedings.mlr.press/v162/zhou22d/zhou22d.pdf)                                                                             | [Code](https://github.com/x-zho14/)    |  Invariant Risk Minimization  |
| ZIN: When and How to Learn Invariance Without Environment Partition? | NeurIPS 2022  | [Paper](https://openreview.net/forum?id=pUPFRSxfACD)                                                                             | [Code](https://github.com/linyongver/ZIN_official)    |  Invariant Risk Minimization  |

### Measurement Bias
| Title                                                                                                                | Venue       | Paper                                                                                                                      | Code | Note                   |
|-----------------------------------------------------|------------------------|---------------------------------------------|------|------------------------|
| Learning from Noisy Labels with Deep Neural Networks: A Survey  | IEEE TNNLS   | [Paper](https://arxiv.org/pdf/2004.07780)                                                                             |     |   See this [Repo](https://github.com/songhwanjun/Awesome-Noisy-Labels)  |


