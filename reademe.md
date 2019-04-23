This repo includes the implementation of AdaShift and also the demonstration code that uses AdaShift to training GANs which achieves FID: 15.8800±0.4921 and Inception Score: 8.0367±0.0499 for unsupervised image generation of GANs in CIFAR-10.

The provided implementation of AdaShift (common/optimizer/AdaShift) is further developed version, which extends our discussion in [1], i.e., v_t can be any random variable that keeps the scale of g_t. We use LGANs developed in [2] and MaxGP described in [3]. 

[1] AdaShift: Decorrelation and Convergence of Adaptive Learning Rate Methods https://arxiv.org/abs/1810.00143
]2] Lipschitz Generative Adversarial Nets https://arxiv.org/abs/1902.05687
[3] Towards Efficient and Unbiased Implementation of Lipschitz Continuity in GANs https://arxiv.org/abs/1904.01184
