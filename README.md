## [Interpreting CNN knowledge via an Explanatory Graph](https://arxiv.org/pdf/1708.01785.pdf)
`Quanshi Zhang, Ruiming Cao, Feng Shi, Ying Nian Wu, Song-Chun Zhu`
> This paper learns a graphical model, namely an explanatory graph, which reveals the knowledge hierarchy hidden inside a pre-trained CNN. Considering that each filter in a conv-layer of a pre-trained CNN usually represents a mixture of object parts, we propose a simple yet efficient method to automatically disentangles different part patterns from each filter, and construct an explanatory graph. Each graph node represents a part pattern, and graph edges encode co-activation relationships and spatial relationships between patterns. We learn the explanatory graph for a pre-trained CNN in an unsupervised manner, i.e., without a need of annotating object parts. Experiments show that each graph node consistently represents the same object part among different images. We transfer part patterns in the explanatory graph to part localization, and our method greatly outperforms other approaches.

## [Interpretable Convolutional Neural Networks](https://arxiv.org/pdf/1710.00935.pdf)
`Quanshi Zhang, Ying Nian Wu, Song-Chun Zhu`
> This paper proposes a method to modify traditional convolutional neural networks (CNNs) into interpretable CNNs, in order to clarify knowledge representations in high conv-layers of CNNs. In an interpretable CNN, each filter in a high conv-layer represents a certain object part. We do not need any annotations of object parts or textures to supervise the learning process. Instead, the interpretable CNN automatically assigns each filter in a high conv-layer with an object part during the learning process. Our method can be applied to different types of CNNs with different structures. The clear knowledge representation in an interpretable CNN can help people understand the logics inside a CNN, i.e., based on which patterns the CNN makes the decision. Experiments showed that filters in an interpretable CNN were more semantically meaningful than those in traditional CNNs.

## [Interpretation of Neural Networks is Fragile](https://arxiv.org/pdf/1710.10547.pdf)
`Amirata Ghorbani, Abubakar Abid, James Zou` from Stanford
> In order for machine learning to be deployed and trusted in many applications, it is crucial to be able to reliably explain why the machine learning algorithm makes certain predictions. For example, if an algorithm classifies a given pathology image to be a malignant tumor, then the doctor may need to know which parts of the image led the algorithm to this classification. How to interpret black-box predictors is thus an important and active area of research. A fundamental question is: how much can we trust the interpretation itself? In this paper, we show that interpretation of deep learning predictions is extremely fragile in the following sense: two perceptively indistinguishable inputs with the same predicted label can be assigned very different interpretations. We systematically characterize the fragility of several widely-used feature-importance interpretation methods (saliency maps, relevance propagation, and DeepLIFT) on ImageNet and CIFAR-10. Our experiments show that even small random perturbation can change the feature importance and new systematic perturbations can lead to dramatically different interpretations without changing the label. We extend these results to show that interpretations based on exemplars (e.g. influence functions) are similarly fragile. Our analysis of the geometry of the Hessian matrix gives insight on why fragility could be a fundamental challenge to the current interpretation approaches.