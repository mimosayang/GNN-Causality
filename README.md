# Causality
关于Causality各种研究的阅读笔记

转：[Causality 基础概念汇总](https://zhuanlan.zhihu.com/p/269625734)

[D分离方法](https://www.bilibili.com/video/BV1xF411K7aa?p=5&vd_source=7f04b7eac11d48d62aada37d93c07804)

[寻找领域不变量：从生成模型到因果表征](https://zhuanlan.zhihu.com/p/568100850)

[无监督的视觉常识特征学习——因果关系上的一点探索（CVPR 2020）](https://zhuanlan.zhihu.com/p/111306353)

[深度神经网络中的因果推理](https://zhuanlan.zhihu.com/p/425331915)


经典论文Causal effect inference with deep latent-variable models（还没看）

### Causal Inference for NNs

$\bullet$ Estimate causal effects

Fundamental approach:blocking backdoor paths ...

1. CVPR2020 [Visual commonsense r-cnn.](https://arxiv.org/abs/2002.12204)Tan Wang, Jianqiang Huang, Hanwang Zhang, and Qianru Sun. Visual commonsense r-cnn. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 10760–10770, 2020a.
2. ArXiv [Devlbert: Learning deconfounded visio-linguistic representations](https://dl.acm.org/doi/10.1145/3394171.3413518)Shengyu Zhang, Tan Jiang, Tan Wang, Kun Kuang, Zhou Zhao, Jianke Zhu, Jin Yu, Hongxia Yang, and Fei Wu. Devlbert: Learning deconfounded visio-linguistic representations. In ACM International Conference on Multimedia, pp. 4373–4382, 2020b.
3. CVPR2022 [Causality inspired representation learning for domain generalization](https://arxiv.org/abs/2203.14237)Fangrui Lv, Jian Liang, Shuang Li, Bin Zang, Chi Harold Liu, Ziteng Wang, and Di Liu. Causality inspired representation learning for domain generalization. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 8046–8056, 2022.

$\bullet$ In CV

[因果推断：因果表征学习的CV落地](https://zhuanlan.zhihu.com/p/400043237)

Frontdoor adjustment:
1. Arxiv [Causal Unsupervised Semantic Segmentation](https://arxiv.org/abs/2310.07379)
  Junho Kim and Byung-Kwan Lee and Yong Man Ro. Causal Unsupervised Semantic Segmentation

Backdoor adjustment:
1. NeurIPS2020 [Long-Tailed Classification by Keeping the Good and Removing the Bad Momentum Causal Effect](https://arxiv.org/abs/2009.12991)Kaihua Tang, Jianqiang Huang, and Hanwang Zhang. Long-tailed classification by keeping the good and removing the bad momentum causal effect. Advances in Neural Information Processing Systems, 33:1513–1524, 2020a.
2. NeurIPS2020 oral [Causal Intervention for Weakly-Supervised Semantic Segmentation](https://arxiv.org/abs/2009.12547)Dong Zhang, Hanwang Zhang, Jinhui Tang, Xian-Sheng Hua, and Qianru Sun. Causal intervention for weakly-supervised semantic segmentation. Advances in Neural Information Processing Systems, 33:655–666, 2020a.
3. NeurIPS2020 [Interventional Few-Shot Learning](https://arxiv.org/abs/2009.13000)Zhongqi Yue, Hanwang Zhang, Qianru Sun, and Xian-Sheng Hua. Interventional few-shot learning. Advances in Neural Information Processing Systems, 33:2734–2746, 2020.
4. CVPR2022 [Show, Deconfound and Tell: Image Captioning with Causal Inference](https://ieeexplore.ieee.org/document/9880383)Bing Liu, Dong Wang, Xu Yang, Yong Zhou, Rui Yao, Zhiwen Shao, and Jiaqi Zhao. Show, deconfound and tell: Image captioning with causal inference. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 18041–18050, 2022.

Mediation analysis:
1. CVPR2020 [Unbiased scene graph generation from biased training](https://arxiv.org/abs/2002.11949)Kaihua Tang, Yulei Niu, Jianqiang Huang, Jiaxin Shi, and Hanwang Zhang. Unbiased scene graph generation from biased training. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 3716–3725, 2020b.
2. CVPR2021 [Counter- factual vqa: A cause-effect look at language bias](https://arxiv.org/abs/2006.04315)Yulei Niu, Kaihua Tang, Hanwang Zhang, Zhiwu Lu, Xian-Sheng Hua, and Ji-Rong Wen. Counter- factual vqa: A cause-effect look at language bias. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 12700–12710, 2021.

Generating counterfactual:
1. ArXiv [Towards Causal VQA: Revealing and Reducing Spurious Correlations by Invariant and Covariant Semantic Editing](https://arxiv.org/abs/1912.07538)Vedika Agarwal, Rakshith Shetty, and Mario Fritz. Towards causal vqa: Revealing and reducing spurious correlations by invariant and covariant semantic editing. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 9690–9698, 2020.
2. CVPR2021 [Counterfactual zero- shot and open-set visual recognition](https://arxiv.org/abs/2103.00887)Zhongqi Yue, Tan Wang, Qianru Sun, Xian-Sheng Hua, and Hanwang Zhang. Counterfactual zero- shot and open-set visual recognition. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 15404–15414, 2021.
3. CVPR2022 [Out-of-distribution generalization with causal invariant transformations](https://arxiv.org/abs/2203.11528)Ruoyu Wang, Mingyang Yi, Zhitang Chen, and Shengyu Zhu. Out-of-distribution generalization with causal invariant transformations. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 375–385, 2022.
4. KDD2023[Counterfactual Learning on Heterogeneous Graphs with Greedy Perturbation](https://dl.acm.org/doi/abs/10.1145/3580305.3599289)


sophisticated theories:
1. CVPR2023 [Demystifying causal features on adversarial examples and causal inoculation for robust network by adversarial instrumental variable regression](https://arxiv.org/abs/2303.01052)Junho Kim, Byung-Kwan Lee, and Yong Man Ro. Demystifying causal features on adversarial examples and causal inoculation for robust network by adversarial instrumental variable regression. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 12302–12312, 2023b.
2. ICCV2023 [Mitigating adversarial vulnerability through causal parameter estimation by adversarial double machine learning](https://arxiv.org/abs/2307.07250)Byung-Kwan Lee, Junho Kim, and Yong Man Ro. Mitigating adversarial vulnerability through causal parameter estimation by adversarial double machine learning. In Proceedings of the IEEE/CVF International Conference on Computer Vision, pp. 4499–4509, October 2023.

### Transfer learning
1.Survey [Transferability in Deep Learning: A Survey](https://arxiv.org/abs/2201.05867)


### Domain adaption

### Few shot 
"Few-shot"是一个机器学习的术语，主要用于描述一种特殊的学习情况，即模型只需要少量的训练样本（例子）就能很好地学习和理解新的概念或任务。

这种学习方式的灵感来自人类的学习能力。例如，小孩子只需要看几次橙色的物体，就能理解“橙色”这个概念，而不需要看成千上万的橙色物体。这种学习方式在机器学习中非常有用，特别是在训练样本稀缺的情况下。

在实践中，few-shot learning通常涉及到预训练和微调两个阶段。在预训练阶段，模型在大量的数据上进行训练，以学习一般的知识和模式。然后，在微调阶段，模型使用少量的新样本进行训练，以适应新的任务或概念。

例如，一个已经在大量猫和狗的图片上训练过的图像识别模型，可能只需要几张斑马的图片，就能学会识别斑马。这就是few-shot learning的一个例子。
1. NeurIPS2020 [Interventional Few-Shot Learning](https://arxiv.org/abs/2009.13000)


### Causal Reinforcememt Leanring
ICML2020 [Causal Reinforcement Learning tutorial](https://crl.causalai.net/#overview)

对应[知乎](https://zhuanlan.zhihu.com/p/363339023)链接

Survey [A Survey on Causal Reinforcement Learning](https://arxiv.org/abs/2302.05209)


