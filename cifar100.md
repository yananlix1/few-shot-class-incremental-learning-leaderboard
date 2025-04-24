# CIFAR100 Leaderboard (5-way 5-shot)

We mainly report two important metrics: (1) AVG: the average top-1 accuracies across all sessions, and (2) PD: the performance drop between the first and last session. 

|Method|Venue|Year|Backbone|AVG|PD|Base|Last|Code|
|------|------|------|------|------|------|------|------|------|
[LIMIT](https://arxiv.org/pdf/2203.17030)|TPAMI|2022|ResNet20|61.84|22.58|73.81|51.23|[Pytorch](https://github.com/LAMDA-CL/TPAMI-Limit)
[FACT](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhou_Forward_Compatible_Few-Shot_Class-Incremental_Learning_CVPR_2022_paper.pdf)|CVPR|2022|ResNet20|62.24|22.50|74.60|52.10|[Pytorch](https://github.com/LAMDA-CL/CVPR22-Fact)
[FSLL](https://arxiv.org/pdf/2103.00991)|AAAI|2021|ResNet18|----|----|----|----|Pytorch
[ERL](https://ojs.aaai.org/index.php/AAAI/article/view/16213)|AAAI|2021|ResNet20|59.29|25.39|73.62|48023|Pytorch
[CEC](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Few-Shot_Incremental_Learning_With_Continually_Evolved_Classifiers_CVPR_2021_paper.pdf)|CVPR|2021|ResNet20|59.53|23.93|73.07|49.14|[Pytorch](https://github.com/icoz69/CEC-CVPR2021)|
|[TOPIC](https://openaccess.thecvf.com/content_CVPR_2020/papers/Tao_Few-Shot_Class-Incremental_Learning_CVPR_2020_paper.pdf)|CVPR|2020|ResNet18|42.62|34.73|64.10|29.37|[Pytorch](https://github.com/xyutao/fscil)|
