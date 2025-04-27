# CIFAR100 Leaderboard (5-way 5-shot)

We mainly report two important metrics: (1) AVG: the average top-1 accuracies across all sessions, and (2) PD: the performance drop between the first and last session. 

|Method|Venue|Year|Backbone|AVG|PD|Base|Last|Code|
|------|------|------|------|------|------|------|------|------|
[FineFMPL](https://www.ijcai.org/proceedings/2024/0144.pdf)|IJCAI|2024|ViT-B/16-CLIP|84.24|9.3|89.9|80.6 | [Pytorch](https://github.com/PKU-ICST-MIPL/FineFMPL_IJCAI2024)
[PriViLege](https://openaccess.thecvf.com/content/CVPR2024/papers/Park_Pre-trained_Vision_and_Language_Transformers_Are_Few-Shot_Incremental_Learners_CVPR_2024_paper.pdf)|CVPR|2024|ViT-B/16-ImageNet21K|88.08|4.82|90.88|86.06|[Pytorch](https://github.com/KU-VGI/PriViLege)
[ASP](https://arxiv.org/pdf/2403.09857)|ECCV|2024|ViT-B/16-ImageNet1K|89.0|5.5|92.2|86.7|[Pytorch](https://github.com/DawnLIU35/FSCIL-ASP)
[GKEAL](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhuang_GKEAL_Gaussian_Kernel_Embedded_Analytic_Learning_for_Few-Shot_Class_Incremental_CVPR_2023_paper.pdf)|CVPR|2023|ResNet20|61.35|22.61|74.01|51.40|[Pytorch](https://github.com/ZHUANGHP/Analytic-continual-learning)
[BiDistFSCIL](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_Few-Shot_Class-Incremental_Learning_via_Class-Aware_Bilateral_Distillation_CVPR_2023_paper.pdf)|CVPR|2023|ResNet18|66.55|22.89|79.45|56.56|[Pytorch](https://github.com/LinglanZhao/BiDistFSCIL)
[NC-FSCIL](https://arxiv.org/pdf/2302.03004)|ICLR|2023|ResNet12|67.50|26.41|82.52|56.11|[Pytorch](https://github.com/NeuralCollapseApplications/FSCIL)
[TEEN](https://openreview.net/pdf?id=8NAxGDdf7H)|NeurIPS|2023|ResNet18|63.10|22.28|74.92|52.64|[Pytorch](https://github.com/wangkiw/TEEN)
[SAVC](https://openaccess.thecvf.com/content/CVPR2023/papers/Song_Learning_With_Fantasy_Semantic-Aware_Virtual_Contrastive_Constraint_for_Few-Shot_Class-Incremental_CVPR_2023_paper.pdf)|CVPR|2023|ResNet20|63.63|25.65|78.77|53.12|[Pytorch](https://github.com/zysong0113/SAVC)
[WaRP](https://openreview.net/pdf?id=kPLzOfPfA2l)|ICLR|2023|ResNet20|65.82|25.57|80.31|54.74|[Pytorch](https://github.com/EdwinKim3069/WaRP-CIFSL)
[C-FSCIL](https://arxiv.org/pdf/2203.16588)|CVPR|2022|ResNet12|61.84|27.27|77.50|50.23|[Pytorch](https://github.com/IBM/constrained-FSCIL)
[MetaFSCIL](https://openaccess.thecvf.com/content/CVPR2022/papers/Chi_MetaFSCIL_A_Meta-Learning_Approach_for_Few-Shot_Class_Incremental_Learning_CVPR_2022_paper.pdf)|CVPR|2022|ResNet20|60.79|24.53|74.50|49.97|Pytorch
[FSIL-GAN](https://dl.acm.org/doi/pdf/10.1145/3503161.3548160)|ACMMM|2022|ResNet18-ImageNet|55.30|23.53|70.14|46.61|Pytorch
[LIMIT](https://arxiv.org/pdf/2203.17030)|TPAMI|2022|ResNet20|61.84|22.58|73.81|51.23|[Pytorch](https://github.com/LAMDA-CL/TPAMI-Limit)
[FACT](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhou_Forward_Compatible_Few-Shot_Class-Incremental_Learning_CVPR_2022_paper.pdf)|CVPR|2022|ResNet20|62.24|22.50|74.60|52.10|[Pytorch](https://github.com/LAMDA-CL/CVPR22-Fact)
[SPPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhu_Self-Promoted_Prototype_Refinement_for_Few-Shot_Class-Incremental_Learning_CVPR_2021_paper.pdf)|CVPR|2021|ResNet18|54.36|20.65|63.97|43.32|[Pytorch](https://github.com/zhukaii/SPPR)
[F2M](https://openreview.net/pdf?id=ALvt7nXa2q)|NeurIPS|2021|ResNet18|53.65|20.04|64.71|44.67|[Pytorch](https://github.com/moukamisama/F2M)
[FSLL](https://arxiv.org/pdf/2103.00991)|AAAI|2021|ResNet18|----|----|----|----|Pytorch
[ERL](https://ojs.aaai.org/index.php/AAAI/article/view/16213)|AAAI|2021|ResNet20|59.29|25.39|73.62|48023|Pytorch
[CEC](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Few-Shot_Incremental_Learning_With_Continually_Evolved_Classifiers_CVPR_2021_paper.pdf)|CVPR|2021|ResNet20|59.53|23.93|73.07|49.14|[Pytorch](https://github.com/icoz69/CEC-CVPR2021)|
|[TOPIC](https://openaccess.thecvf.com/content_CVPR_2020/papers/Tao_Few-Shot_Class-Incremental_Learning_CVPR_2020_paper.pdf)|CVPR|2020|ResNet18|42.62|34.73|64.10|29.37|[Pytorch](https://github.com/xyutao/fscil)|
