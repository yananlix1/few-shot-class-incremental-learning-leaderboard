# miniImageNet Leaderboard (5-way 5-shot)

We mainly report two important metrics: (1) AVG: the average top-1 accuracies across all sessions, and (2) PD: the performance drop between the first and last session. 

|Method|Venue|Year|Backbone|AVG|PD|Base|Last|Code|
|------|------|------|------|------|------|------|------|------|
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
