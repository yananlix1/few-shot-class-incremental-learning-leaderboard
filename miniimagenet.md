# miniImageNet Leaderboard (5-way 5-shot)

We mainly report two important metrics: (1) AVG: the average top-1 accuracies across all sessions, and (2) PD: the performance drop between the first and last session. 

|Method|Venue|Year|Backbone|AVG|PD|Base|Last|Code|
|------|------|------|------|------|------|------|------|------|
[LRT](https://arxiv.org/pdf/2501.05862)|TPAMI|2024|ResNet50-CLIP|75.94|24.83|90.17|65.34|[Pytorch](https://github.com/iCVTEAM/LRT)
[FineFMPL](https://www.ijcai.org/proceedings/2024/0144.pdf)|IJCAI|2024|ViT-B/16-CLIP|93.36|4.8|96.0|91.2| [Pytorch](https://github.com/PKU-ICST-MIPL/FineFMPL_IJCAI2024)
[PriViLege](https://openaccess.thecvf.com/content/CVPR2024/papers/Park_Pre-trained_Vision_and_Language_Transformers_Are_Few-Shot_Incremental_Learners_CVPR_2024_paper.pdf)|CVPR|2024|ViT-B/16-ImageNet21K|95.27|2.58|96.68|94.10|[Pytorch](https://github.com/KU-VGI/PriViLege)
[ASP](https://arxiv.org/pdf/2403.09857)|ECCV|2024|ViT-B/16-ImageNet1K|--|--|--|--|[Pytorch](https://github.com/DawnLIU35/FSCIL-ASP)
[GKEAL](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhuang_GKEAL_Gaussian_Kernel_Embedded_Analytic_Learning_for_Few-Shot_Class_Incremental_CVPR_2023_paper.pdf)|CVPR|2023|ResNet18|60.48|22.28|73.59|51.31|[Pytorch](https://github.com/ZHUANGHP/Analytic-continual-learning)
[BiDistFSCIL](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_Few-Shot_Class-Incremental_Learning_via_Class-Aware_Bilateral_Distillation_CVPR_2023_paper.pdf)|CVPR|2023|ResNet18|62.06|21.26|74.65|53.39|[Pytorch](https://github.com/LinglanZhao/BiDistFSCIL)
[NC-FSCIL](https://arxiv.org/pdf/2302.03004)|ICLR|2023|ResNet12|67.82|25.71|84.02|58.31|[Pytorch](https://github.com/NeuralCollapseApplications/FSCIL)
[TEEN](https://openreview.net/pdf?id=8NAxGDdf7H)|NeurIPS|2023|ResNet18|61.44|21.45|73.53|52.08|[Pytorch](https://github.com/wangkiw/TEEN)
[SAVC](https://openaccess.thecvf.com/content/CVPR2023/papers/Song_Learning_With_Fantasy_Semantic-Aware_Virtual_Contrastive_Constraint_for_Few-Shot_Class-Incremental_CVPR_2023_paper.pdf)|CVPR|2023|ResNet18|67.05|24.01|81.12|57.11|[Pytorch](https://github.com/zysong0113/SAVC)
[WaRP](https://openreview.net/pdf?id=kPLzOfPfA2l)|ICLR|2023|ResNet18|59.69|22.34|72.99|50.65|[Pytorch](https://github.com/EdwinKim3069/WaRP-CIFSL)
[C-FSCIL](https://arxiv.org/pdf/2203.16588)|CVPR|2022|ResNet12|61.61|24.99|76.40|51.41|[Pytorch](https://github.com/IBM/constrained-FSCIL)
[MetaFSCIL](https://openaccess.thecvf.com/content/CVPR2022/papers/Chi_MetaFSCIL_A_Meta-Learning_Approach_for_Few-Shot_Class_Incremental_Learning_CVPR_2022_paper.pdf)|CVPR|2022|ResNet18|58.85|22.85|72.04|49.19|Pytorch
[FSIL-GAN](https://dl.acm.org/doi/pdf/10.1145/3503161.3548160)|ACMMM|2022|ResNet18-ImageNet|56.40|23.73|69.87|46.14|Pytorch
[LIMIT](https://arxiv.org/pdf/2203.17030)|TPAMI|2022|ResNet18|50.09|23.13|72.32|49.49|[Pytorch](https://github.com/LAMDA-CL/TPAMI-Limit)
[FACT](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhou_Forward_Compatible_Few-Shot_Class-Incremental_Learning_CVPR_2022_paper.pdf)|CVPR|2022|ResNet18|60.70|22.07|72.56|50.49|[Pytorch](https://github.com/LAMDA-CL/CVPR22-Fact)
[SPPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhu_Self-Promoted_Prototype_Refinement_for_Few-Shot_Class-Incremental_Learning_CVPR_2021_paper.pdf)|CVPR|2021|ResNet18|52.76|19.53|61.45|41.92|[Pytorch](https://github.com/zhukaii/SPPR)
[F2M](https://openreview.net/pdf?id=ALvt7nXa2q)|NeurIPS|2021|ResNet18|54.89|22.63|67.28|44.65|[Pytorch](https://github.com/moukamisama/F2M)
[FSLL](https://arxiv.org/pdf/2103.00991)|AAAI|2021|ResNet18|----|----|----|----|Pytorch
[ERL](https://ojs.aaai.org/index.php/AAAI/article/view/16213)|AAAI|2021|ResNet18|----|----|----|----|Pytorch
[CEC](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Few-Shot_Incremental_Learning_With_Continually_Evolved_Classifiers_CVPR_2021_paper.pdf)|CVPR|2021|ResNet18|57.75|24.37|72.00|47.63|[Pytorch](https://github.com/icoz69/CEC-CVPR2021)|
|[TOPIC](https://openaccess.thecvf.com/content_CVPR_2020/papers/Tao_Few-Shot_Class-Incremental_Learning_CVPR_2020_paper.pdf)|CVPR|2020|ResNet18|39.64|36.89|61.31|24.42|[Pytorch](https://github.com/xyutao/fscil)|
