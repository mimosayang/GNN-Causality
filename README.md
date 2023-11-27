# Causality
关于Causality各种研究的阅读笔记

转：[Causality 基础概念汇总](https://zhuanlan.zhihu.com/p/269625734)
[D分离方法](https://www.bilibili.com/video/BV1xF411K7aa?p=5&vd_source=7f04b7eac11d48d62aada37d93c07804)

### Causal Inference for NNs

$\bullet$ Estimate causal effects

fundamental approach:blocking backdoor paths ...

1. CVPR2020 [Visual commonsense r-cnn.](https://arxiv.org/abs/2002.12204)Tan Wang, Jianqiang Huang, Hanwang Zhang, and Qianru Sun. Visual commonsense r-cnn. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 10760–10770, 2020a.
2. Shengyu Zhang, Tan Jiang, Tan Wang, Kun Kuang, Zhou Zhao, Jianke Zhu, Jin Yu, Hongxia Yang, and Fei Wu. Devlbert: Learning deconfounded visio-linguistic representations. In ACM International Conference on Multimedia, pp. 4373–4382, 2020b.
3. CVPR2022 [Causality inspired representation learning for domain generalization](https://arxiv.org/abs/2203.14237)Fangrui Lv, Jian Liang, Shuang Li, Bin Zang, Chi Harold Liu, Ziteng Wang, and Di Liu. Causality inspired representation learning for domain generalization. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 8046–8056, 2022.

$\bullet$ In CV
frontdoor adjustment:
1. Arxiv [Causal Unsupervised Semantic Segmentation](https://arxiv.org/abs/2310.07379)
  Junho Kim and Byung-Kwan Lee and Yong Man Ro. Causal Unsupervised Semantic Segmentation

backdoor adjustment:
1. NeurIPS2020 [Long-Tailed Classification by Keeping the Good and Removing the Bad Momentum Causal Effect](https://arxiv.org/abs/2009.12991)Kaihua Tang, Jianqiang Huang, and Hanwang Zhang. Long-tailed classification by keeping the good and removing the bad momentum causal effect. Advances in Neural Information Processing Systems, 33:1513–1524, 2020a.
2. Dong Zhang, Hanwang Zhang, Jinhui Tang, Xian-Sheng Hua, and Qianru Sun. Causal intervention for weakly-supervised semantic segmentation. Advances in Neural Information Processing Systems, 33:655–666, 2020a.
3. Zhongqi Yue, Hanwang Zhang, Qianru Sun, and Xian-Sheng Hua. Interventional few-shot learning. Advances in Neural Information Processing Systems, 33:2734–2746, 2020.
4. Bing Liu, Dong Wang, Xu Yang, Yong Zhou, Rui Yao, Zhiwen Shao, and Jiaqi Zhao. Show, deconfound and tell: Image captioning with causal inference. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 18041–18050, 2022.

mediation analysis:
1. Kaihua Tang, Yulei Niu, Jianqiang Huang, Jiaxin Shi, and Hanwang Zhang. Unbiased scene graph generation from biased training. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 3716–3725, 2020b.
2. Yulei Niu, Kaihua Tang, Hanwang Zhang, Zhiwu Lu, Xian-Sheng Hua, and Ji-Rong Wen. Counter- factual vqa: A cause-effect look at language bias. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 12700–12710, 2021.

generating counterfactual augmentations for randomized treatment assignments:
1. Vedika Agarwal, Rakshith Shetty, and Mario Fritz. Towards causal vqa: Revealing and reducing spurious correlations by invariant and covariant semantic editing. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 9690–9698, 2020.
2. Zhongqi Yue, Tan Wang, Qianru Sun, Xian-Sheng Hua, and Hanwang Zhang. Counterfactual zero- shot and open-set visual recognition. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 15404–15414, 2021.
3. Ruoyu Wang, Mingyang Yi, Zhitang Chen, and Shengyu Zhu. Out-of-distribution generalization with causal invariant transformations. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 375–385, 2022.

sophisticated theories:
1. Junho Kim, Byung-Kwan Lee, and Yong Man Ro. Demystifying causal features on adversarial examples and causal inoculation for robust network by adversarial instrumental variable regression. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 12302–12312, 2023b.
2. Byung-Kwan Lee, Junho Kim, and Yong Man Ro. Mitigating adversarial vulnerability through causal parameter estimation by adversarial double machine learning. In Proceedings of the IEEE/CVF International Conference on Computer Vision, pp. 4499–4509, October 2023.

### Transfer learning
1.Survey [Transferability in Deep Learning: A Survey](https://arxiv.org/abs/2201.05867)


### Domain adaption
1. 
