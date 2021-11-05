# AI-Updates

# Imagenet papers summarized

**CoAtNet: Marrying Convolution and Attention for All Data Sizes | 2021**

- Algorithm: CoAtNet-7
- CoAtNets (pronounced “coat” nets), a family of hybrid models built from two key insights: (1) depthwise Convolution and self-Attention can be naturally unified via simple relative attention and (2) vertically stacking convolution layers and attention layers in a principled way is surprisingly effective in improving generalization, capacity and efficiency.
- Link: https://arxiv.org/pdf/2106.04803v2.pdf

**Scaling Vision Transformers | 2021**

- Algorithm: ViT-G/
- A ViT model with two billion parameters is successfully trained, which attains a new state-of-the-art on ImageNet of 90.45% top-1 accuracy and performs well on few-shot learning.
- Link: https://arxiv.org/pdf/2106.04560v1.pdf

**Scaling Vision with Sparse Mixture of Experts | 2021**

- Algorithm: ViT-MoE-15B
- This work presents a Vision MoE (V-MoE), a sparse version of the Vision Transformer that is scalable and competitive with the largest dense networks, and proposes an extension to the routing algorithm that can prioritize subsets of each input across the entire batch, leading to adaptive per-image compute.
- Link: https://arxiv.org/pdf/2106.05974v1.pdf

**Meta Pseudo Labels | 2020**

- Algorithm: Meta Pseudo Labels
- This work proposes an efficient meta-learning algorithm, which encourages the teacher to adjust the target distributions of training examples in the manner that improves the learning of the main network.
- Link: https://arxiv.org/pdf/2003.10580v4.pdf

**High-Performance Large-Scale Image Recognition Without Normalization | 2021**

- Algorithm: NFNet-F4+
- An adaptive gradient clipping technique is developed which overcomes instabilities in batch normalization, and a significantly improved class of Normalizer-Free ResNets is designed which attain significantly better performance when finetuning on ImageNet.
- Link: https://arxiv.org/pdf/2102.06171v1.pdf

**TokenLearner: What Can 8 Learned Tokens Do for Images and Videos? | 2021**

- Algorithm: TokenLearner
- A novel visual representation learning which relies on a handful of adaptively learned tokens, and which is applicable to both image and video understanding tasks, which accomplishes competitive results at significantly reduced compute amount.
- Link: https://arxiv.org/pdf/2106.11297v2.pdf

**Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision | 2021**

- Algorithm: ALIGN (EfficientNet-L2)
- A simple dual-encoder architecture learns to align visual and language representations of the image and text pairs using a contrastive loss, and it is shown that the scale of the corpus can make up for its noise and leads to state-of-the-art representations even with such a simple learning scheme.
- Link: https://arxiv.org/pdf/2102.05918v2.pdf

**Sharpness-Aware Minimization for Efficiently Improving Generalization | 2020**

- Algorithm: EfficientNet-L2-475
- This work introduces a novel, effective procedure for simultaneously minimizing loss value and loss sharpness, Sharpness-Aware Minimization (SAM), which improves model generalization across a variety of benchmark datasets and models, yielding novel state-of-the-art performance for several.
- Link: https://arxiv.org/pdf/2010.01412v3.pdf

**BEiT: BERT Pre-Training of Image Transformers | 2021**

- Algorithm: BEiT-L
- A self-supervised vision representation model BEIT, which stands for Bidirectional Encoder representation from Image Transformers, is introduced and Experimental results on image classification and semantic segmentation show that the model achieves competitive results with previous pre-training methods.
- Link: https://arxiv.org/pdf/2106.08254v1.pdf

**Fixing the train-test resolution discrepancy: FixEfficientNet | 2020**

- Algorithm: FixEfficientNet-L2
- This strategy is advantageously combined with recent training recipes from the literature and significantly outperforms the initial architecture with the same number of parameters, and establishes the new state of the art for ImageNet with a single crop.
- Link: https://arxiv.org/pdf/2003.08237v5.pdf

**MLP-Mixer: An all-MLP Architecture for Vision | 2021**

- Algorithm: Mixer-H
- It is shown that while convolutions and attention are both sufficient for good performance, neither of them are necessary, and MLP-Mixer, an architecture based exclusively on multi-layer perceptrons (MLPs), attains competitive scores on image classification benchmarks.
- Link: https://arxiv.org/pdf/2105.01601v4.pdf

**An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale | 2020**

- Algorithm: ViT-L
- Vision Transformer (ViT) attains excellent results compared to state-of-the-art convolutional networks while requiring substantially fewer computational resources to train.
- Link: https://arxiv.org/pdf/2010.11929v2.pdf

**CvT: Introducing Convolutions to Vision Transformers | 2021**

- Algorithm: CvT-W24
- A new architecture, named Convolutional vision Transformer (CvT), is presented, that improves Vision Trans transformer (ViT) in performance and efficiency by introducing convolutions into ViT to yield the best of both designs.
- Link: https://arxiv.org/pdf/2103.15808v1.pdf

**CSWin Transformer: A General Vision Transformer Backbone with Cross-Shaped Windows | 2021**

- Algorithm: CSWin-L
- The Cross-Shaped Window self-attention mechanism for computing self-Attention in the horizontal and vertical stripes in parallel that form a cross-shaped window is developed, with each stripe obtained by splitting the input feature into stripes of equal width.
- Link: https://arxiv.org/pdf/2107.00652v2.pdf

**Swin Transformer: Hierarchical Vision Transformer using Shifted Windows | 2021**

- Algorithm: Swin-L
- A new vision Transformer is presented that capably serves as a general-purpose backbone for computer vision and has the flexibility to model at various scales and has linear computational complexity with respect to image size.
- Link: https://arxiv.org/pdf/2103.14030v2.pdf

**VOLO: Vision Outlooker for Visual Recognition | 2021**

- Algorithm: VOLO-D5
- A novel outlook attention is introduced and presented, termed Vision Outlooker (VOLO), which efficiently encodes finer-level features and contexts into tokens, which is shown to be critically beneficial to recognition performance but largely ignored by the self-attention.
- Link: https://arxiv.org/pdf/2106.13112v2.pdf

**EfficientNetV2: Smaller Models and Faster Training | 2021**

- Algorithm: EfficientNetV2-L
- An improved method of progressive learning, which adaptively adjusts regularization (e.g., dropout and data augmentation) along with image size is proposed, which significantly outperforms previous models on ImageNet and CIFAR/Cars/Flowers datasets.
- Link: https://arxiv.org/pdf/2104.00298v3.pdf

**Drawing Multiple Augmentation Samples Per Image During Training Efficiently Decreases Test Error | 2021**

- Algorithm: NFNet-F5 - SAM - augmult=16
- It is found that drawing multiple samples per image consistently enhances the test accuracy achieved for both small and large batch training, despite reducing the number of unique training examples in each mini-batch.
- Link: https://arxiv.org/pdf/2105.13343v1.pdf

**Going deeper with Image Transformers | 2021**

- Algorithm: CaiT-M-48-448
- This work builds and optimize deeper transformer networks for image classification and investigates the interplay of architecture and optimization of such dedicated transformers, improving the accuracy of deep transformers.
- Link: https://arxiv.org/pdf/2103.17239v2.pdf

**All Tokens Matter: Token Labeling for Training Better Vision Transformers | 2021**

- Algorithm: LV-ViT-L
- Experiments show that token labeling can clearly and consistently improve the performance of various ViT models across a wide spectrum and improve the generalization capability of the pretrained models on downstream tasks with dense prediction, such as semantic segmentation.
- Link: https://arxiv.org/pdf/2104.10858v3.pdf

**Refiner: Refining Self-attention for Vision Transformers | 2021**

- Algorithm: Refiner-ViT-L
- This work introduces a conceptually simple scheme, called refiner, to directly refine the selfattention maps of ViTs, and explores attention expansion that projects the multi-head attention maps to a higher-dimensional space to promote their diversity.
- Link: https://arxiv.org/pdf/2106.03714v1.pdf

**XCiT: Cross-Covariance Image Transformers | 2021**

- Algorithm: XCiT-L24
- This work proposes a “transposed” version of self-attention that operates across feature channels rather than tokens, where the interactions are based on the cross-covariance matrix between keys and queries, and has linear complexity in the number of tokens, and allows efficient processing of high-resolution images.
- Link: https://arxiv.org/pdf/2106.09681v2.pdf

**Circumventing Outliers of AutoAugment with Knowledge Distillation | 2020**

- Algorithm: KDforAA (EfficientNet-B8)
- It is revealed that AutoAugment may remove part of discriminative information from the training image and so insisting on the ground-truth label is no longer the best option, and knowledge distillation is made use that refers to the output of a teacher model to guide network training.
- Link: https://arxiv.org/pdf/2003.11342v1.pdf

**MaxUp: A Simple Way to Improve Generalization of Neural Network Training | 2020**

- Algorithm: Fix-EfficientNet-B8 (MaxUp + CutMix)
- The idea is to generate a set of augmented data with some random perturbations or transforms and minimize the maximum, or worst case loss over the augmented data, by doing so, to implicitly introduce a smoothness or robustness regularization against the random perturgations, and hence improve the generation performance.
- Link: https://arxiv.org/pdf/2002.09024v1.pdf

**Scaling Local Self-Attention for Parameter Efficient Visual Backbones | 2021**

- Algorithm: HaloNet4
- A new self-attention model family, HaloNets, is developed which reach state-of-the-art accuracies on the parameter-limited setting of the ImageNet classification benchmark, and preliminary transfer learning experiments find that HaloNet models outperform much larger models and have better inference performance.
- Link: https://arxiv.org/pdf/2103.12731v3.pdf

**Training data-efficient image transformers & distillation through attention | 2020**

- Algorithm: DeiT-B 384
- This work produces a competitive convolution-free transformer by training on Imagenet only, and introduces a teacher-student strategy specific to transformers that relies on a distillation token ensuring that the student learns from the teacher through attention.
- Link: https://arxiv.org/pdf/2012.12877v2.pdf

**Semi-Supervised Recognition under a Noisy and Fine-grained Dataset | 2020** 

- Algorithm: ResNet200_vd_26w_4s_ssld
- This work combined generic image recognition and fine-grained image recognition method to solve the problem of identifying similar birds with a very small difference in Simi-Supervised Recognition Challenge-FGVC7
- Link: https://arxiv.org/pdf/2006.10702v1.pdf

**Multiscale Vision Transformers | 2021**

- Algorithm: MViT-B-24
- This fundamental architectural prior for modeling the dense nature of visual signals for a variety of video recognition tasks where it outperforms concurrent vision transformers that rely on large scale external pre-training and are 5-10× more costly in computation and parameters is evaluated.
- Link: https://arxiv.org/pdf/2104.11227v1.pdf

**Bottleneck Transformers for Visual Recognition | 2021**

- Algorithm: BoTNet T7
- BoTNet is presented, a conceptually simple yet powerful backbone architecture that incorporates self-attention for multiple computer vision tasks including image classification, object detection and instance segmentation, and a simple adaptation of the BoTNet design for image classification is presented.
- Link: https://arxiv.org/pdf/2101.11605v2.pdf

**ResNeSt: Split-Attention Networks | 2020**

- Algorithm: ResNeSt-269
- A simple and modular Split-Attention block that enables attention across feature-map groups ResNet-style is presented that preserves the overall ResNet structure to be used in downstream tasks straightforwardly without introducing additional computational costs.
- Link: https://arxiv.org/pdf/2004.08955v2.pdf

**Revisiting ResNets: Improved Training and Scaling Strategies | 2021**

- Algorithm: ResNet-RS-50
- It is found that training and scaling strategies may matter more than architectural changes, and further, that the resulting ResNets match recent state-of-the-art models.
- Link: https://arxiv.org/pdf/2103.07579v1.pdf

**ResMLP: Feedforward networks for image classification with data-efficient training | 2021**

- Algorithm: ResMLP-B24
- ResMLP is a simple residual network that alternates a linear layer in which image patches interact, independently and identically across channels, and a two-layer feed-forward network in which channels interact independently per patch.
- Link: https://arxiv.org/pdf/2105.03404v2.pdf

**TResNet: High Performance GPU-Dedicated Architecture | 2020**

- Algorithm: TResNet-XL
- A series of architecture modifications are introduced that aim to boost neural networks’ accuracy, while retaining their GPU training and inference efficiency, and a new family of GPU-dedicated models, called TResNet, which achieves better accuracy and efficiency than previous ConvNets1.
- Link: https://arxiv.org/pdf/2003.13630v3.pdf

**LambdaNetworks: Modeling Long-Range Interactions Without Attention | 2021**

- Algorithm: LambdaResNet200
- The resulting neural network architectures, LambdaNetworks, significantly outperform their convolutional and attentional counterparts on ImageNet classification, COCO object detection and instance segmentation, while being more computationally efficient.
- Link: https://arxiv.org/pdf/2102.08602v1.pdf

**Compounding the Performance Improvements of Assembled Techniques in a Convolutional Neural Network | 2020**

- Algorithm: Assemble-ResNet152
- Detailed experiments to validate that carefully assembling these techniques and applying them to basic CNN models can improve the accuracy and robustness of the models while minimizing the loss of throughput showed that the improvement to backbone network performance boosted transfer learning performance significantly.
- Link: https://arxiv.org/pdf/2001.06268v2.pdf

**Visual Parser: Representing Part-whole Hierarchies with Transformers | 2021**

- Algorithm: ViP-B
- The Visual Parser (ViP) is presented, that explicitly constructs such a hierarchy with transformers that can achieve very competitive performance on three major tasks e.g. classification, detection and instance segmentation.
- Link: https://arxiv.org/pdf/2107.05790v1.pdf

**Conformer: Local Features Coupling Global Representations for Visual Recognition | 2021**

- Algorithm: Conformer-B
- Experiments show that Conformer, under the comparable parameter complexity, outperforms the visual transformer (DeiT-B) by 2.3% on ImageNet and on MSCOCO, it outperforms ResNet-101 by 3.7% and 3.6% mAPs for object detection and instance segmentation, respectively, demonstrating the great potential to be a general backbone network.
- Link: https://arxiv.org/pdf/2105.03889v1.pdf

**Rethinking Spatial Dimensions of Vision Transformers | 2021**

- Algorithm: PiT-B
- A novel Pooling-based Vision Transformer (PiT) is proposed, which achieves the improved model capability and generalization performance against ViT and outperforms the baseline on several tasks such as image classification, object detection and robustness evaluation
- Link: https://arxiv.org/pdf/2103.16302v2.pdf

**Transformer in Transformer | 2021**

- Algorithm: TNT-B
- It is pointed out that the attention inside these local patches are also essential for building visual transformers with high performance and a new architecture, namely, Transformer iN Transformer (TNT), is explored
- Link: https://arxiv.org/pdf/2103.00112v3.pdf

**DynamicViT: Efficient Vision Transformers with Dynamic Token Sparsification | 2021**

- Algorithm: DynamicViT-LV-M
- A dynamic token sparsification framework to prune redundant tokens progressively and dynamically based on the input and an attention masking strategy to differentiably prune a token by blocking its interactions with other tokens is proposed.
- Link: https://arxiv.org/pdf/2106.02034v2.pdf

**PVTv2: Improved Baselines with Pyramid Vision Transformer | 2021**

- Algorithm: PVTv2-B4
- This work presents new baselines by improving the original Pyramid Vision Transformer (abbreviated as PVTv1) by adding three designs, including (1) overlapping patch embedding, (2) convolutional feedforward networks, and (3) linear complexity attention layers.
- Link: https://arxiv.org/pdf/2106.13797v4.pdf

**Aggregating Nested Transformers | 2021**

- Algorithm: Transformer local-attention
- Beyond image classification, the idea of nesting basic local transformers on non-overlapping image blocks and aggregating them in a hierarchical manner is extended to image generation and shows NesT leads to a strong decoder that is 8× faster than previous transformer based generators.
- Link: https://arxiv.org/pdf/2105.12723v2.pdf

**Twins: Revisiting the Design of Spatial Attention in Vision Transformers | 2021**

- Algorithm: Twins-SVT-L
- This work revisits the design of the spatial attention and demonstrates that a carefully devised yet simple spatial attention mechanism performs favorably against the state-of-the-art schemes
- Link: https://arxiv.org/pdf/2104.13840v4.pdf

**ResT: An Efficient Transformer for Visual Recognition | 2021**

- Algorithm: ResT-Large
- Experimental results show that the proposed ResT can outperform the recently state-of-the-art backbones by a large margin, demonstrating the potential of ResT as strong backbones.
- Link: https://arxiv.org/pdf/2105.13677v5.pdf

**ViTAE: Vision Transformer Advanced by Exploring Intrinsic Inductive Bias | 2021**

- Algorithm: ViTAE-B-Stage
- Experiments on ImageNet as well as downstream tasks prove the superiority of ViTAE over the baseline transformer and concurrent works, which has the intrinsic locality IB and is able to learn local features and global dependencies collaboratively.
- Link: https://arxiv.org/pdf/2106.03348v2.pdf

**Sparse MLP for Image Recognition: Is Self-Attention Really Necessary? | 2021**

- Algorithm: sMLPNet-B
- An attention-free network called sMLPNet is built based on the existing MLP-based vision models, replacing the MLP module in the token-mixing step with a novel sparse MLP (sMLP) module that significantly reduces the number of model parameters and computational complexity.
- Link: https://arxiv.org/pdf/2109.05422v1.pdf

**Incorporating Convolution Designs into Visual Transformers | 2021**

- Algorithm: CeiT-S
- A new Convolution-enhanced image Transformer (CeiT) is proposed which combines the advantages of CNNs in extracting lowlevel features, strengthening locality, and theadvantages of Transformers in establishing long-range dependencies.
- Link: https://arxiv.org/pdf/2103.11816v2.pdf

**Multi-Scale Vision Longformer: A New Vision Transformer for High-Resolution Image Encoding | 2021**

- Algorithm: ViL-Medium-D
- A comprehensive empirical study shows that the new ViT significantly outperforms several strong baselines, including the existing ViT models and their ResNet counterparts, and the Pyramid Vision Transformer from a concurrent work, on a range of vision tasks, including image classification, object detection, and segmentation.
- Link: https://arxiv.org/pdf/2103.15358v2.pdf

**Tokens-to-Token ViT: Training Vision Transformers from Scratch on ImageNet | 2021**

- Algorithm: T2T-ViT-14|384
- A new TokensTo-Token Vision Transformers (T2T-ViT), which introduces an efficient backbone with a deep-narrow structure for vision transformers motivated by CNN architecture design after extensive study and reduces the parameter counts and MACs of vanilla ViT by 200%, while achieving more than 2.5% improvement when trained from scratch on ImageNet.
- Link: https://arxiv.org/pdf/2101.11986v2.pdf

**CycleMLP: A MLP-like Architecture for Dense Prediction | 2021

- Algorithm: CycleMLP-B5
- CycleMLP aims to provide a competitive baseline on object detection, instance segmentation, and semantic segmentation for MLP models, and expands the MLPlike models’ applicability, making them a versatile backbone for dense prediction tasks
- Link: https://arxiv.org/pdf/2107.10224v1.pdf

**DeepViT: Towards Deeper Vision Transformer | 2021**

- Algorithm: DeepVit-L* (DeiT training recipe)
- This paper proposes a simple yet effective method, named Re-attention, to re-generate the attention maps to increase their diversity at different layers with negligible computation and memory cost and makes it feasible to train deeper ViTs with consistent performance improvements via minor modification to existing ViT models.
- Link: https://arxiv.org/pdf/2103.11886v4.pdf

**Global Filter Networks for Image Classification | 2021**

- Algorithm: GFNet-H-B
- The Global Filter Network is presented, a conceptually simple yet computationally efficient architecture that learns long-term spatial dependencies in the frequency domain with log-linear complexity and can be a very competitive alternative to transformer-style models and CNNs in efficiency, generalization ability and robustness.
- Link: https://arxiv.org/pdf/2107.00645v2.pdf

**CrossViT: Cross-Attention Multi-Scale Vision Transformer for Image Classification | 2021**

- Algorithm: CrossViT-18+
- A dual-branch transformer to combine image patches of different sizes to produce stronger image features and a simple yet effective token fusion module based on cross attention, which uses a single token for each branch as a query to exchange information with other branches.
- Link: https://arxiv.org/pdf/2103.14899v2.pdf

**Knowledge distillation: A good teacher is patient and consistent | 2021**

- Algorithm: FunMatch - T384+224 (ResNet-50)
- It is demonstrated that, when performed correctly, knowledge distillation can be a powerful tool for reducing the size of large models without compromising their performance.
- Link: https://arxiv.org/pdf/2106.05237v1.pdf

**Escaping the Big Data Paradigm with Compact Transformers | 2021**

- Algorithm: CCT-14/7x2 | 384
- This paper shows for the first time that with the right size and tokenization, transformers can perform head-to-head with state-of-the-art CNNs on small datasets, and democratizes transformers by making them accessible to those equipped with basic computing resources and/or dealing with important small datasets.
- Link: https://arxiv.org/pdf/2104.05704v3.pdf

**Container: Context Aggregation Network | 2021**

- Algorithm: Container
- The CONTAINER (CONText AggregatIon NEtwoRk), a general-purpose building block for multi-head context aggregation that can exploit long-range interactions a la Transformers while still exploiting the inductive bias of the local convolution operation leading to faster convergence speeds, is presented.
- Link: https://arxiv.org/pdf/2106.01401v2.pdf

**Harmonic Convolutional Networks based on Discrete Cosine Transform | 2020**

- Algorithm: Harm-SE-RNX-101 64x4d (320x320, Mean-Max Pooling)
- This paper proposes to revert to learning combinations of preset spectral filters by switching to CNNs with harmonic blocks and relies on the use of the Discrete Cosine Transform filters which have excellent energy compaction properties and are widely used for image compression.
- Link: https://arxiv.org/pdf/2001.06570v2.pdf

**Towards Robust Vision Transformer | 2021**

- Algorithm: RVT-B*
- This work proposes Robust Vision Transformer (RVT), which is a new vision transformer and has superior performance with strong robustness, and proposes two new plug-and-play techniques called positionaware attention scaling and patch-wise augmentation to augment the RVT, which is abbreviate as RVT∗
- Link: https://arxiv.org/pdf/2105.07926v3.pdf

**ConViT: Improving Vision Transformers with Soft Convolutional Inductive Biases | 2021**

- Algorithm: ConViT-B+
- GPSA is introduced, a form of positional self-attention which can be equipped with a "soft" convolutional inductive bias and outperforms the DeiT on ImageNet, while offering a much improved sample efficiency.
- Link: https://arxiv.org/pdf/2103.10697v2.pdf

**LeViT: a Vision Transformer in ConvNet's Clothing for Faster Inference | 2021**

- Algorithm: LeViT-384
- This work designs a family of image classification architectures that optimize the trade-off between accuracy and efficiency in a high-speed regime, and proposes - -LeVIT: a hybrid neural network for fast inference image classification.
-Link: https://arxiv.org/pdf/2104.01136v2.pdf

**Rethinking and Improving Relative Position Encoding for Vision Transformer | 2021**

- Algorithm: DeiT-B with iRPE-K
- New relative position encoding methods dedicated to 2D images, called image RPE (iRPE), are proposed, which consider directional relative distance modeling as well as the interactions between queries and relative position embeddings in self-attention mechanism.
- Link: https://arxiv.org/pdf/2107.14222v1.pdf

**ResNet strikes back: An improved training procedure in timm | 2021**

- Algorithm: ResNet-152 (A2 + reg)
- This paper re-evaluate the performance of the vanilla ResNet-50 when trained with a procedure that integrates such advances, and shares competitive training settings and pre-trained models in the timm open-source library, with the hope that they will serve as better baselines for future work.
- Link: https://arxiv.org/pdf/2110.00476v1.pdf

**AutoFormer: Searching Transformers for Visual Recognition | 2021**

- Algorithm: AutoFormer-base
- This work proposes a new one-shot architecture search framework, namely AutoFormer, dedicated to vision transformer search, which surpass the recent state-of-the-arts such as ViT and DeiT and achieves top-1 accuracy on ImageNet.
- Link: https://arxiv.org/pdf/2107.00651v1.pdf

**GLiT: Neural Architecture Search for Global and Local Image Transformer | 2021**

- Algorithm: GLiT-Bases
- This work introduces the first Neural Architecture Search (NAS) method to find a better transformer architecture for image recognition and introduces a locality module that models the local correlations in images explicitly with fewer computational cost.
- Link: https://arxiv.org/pdf/2107.02960v3.pdf

**BossNAS: Exploring Hybrid CNN-transformers with Block-wisely Self-supervised Neural Architecture Search | 2021**

- Algorithm: BossNet-T1+
- This work presents Block-wisely Self-supervised Neural Architecture Search (BossNAS), an unsupervised NAS method that addresses the problem of inaccurate architecture rating caused by large weight-sharing space and biased supervision in previous methods.
- Link: https://arxiv.org/pdf/2103.12424v3.pdf

**Evo-ViT: Slow-Fast Token Evolution for Dynamic Vision Transformer | 2021**

- Algorithm: Evo-LeViT-384*
- Evo-ViT, a self-motivated slow-fast token evolution method for vision transformers, which dynamically identify uninformative tokens for each instance and trim down both the training and inference complexity while maintaining complete spatial structure and information flow.
- Link: https://arxiv.org/pdf/2108.01390v4.pdf

**Differentiable Model Compression via Pseudo Quantization Noise | 2021**

- Algorithm: DIFFQ
- DIFFQ is a differentiable method for model compression for quantizing model parameters without gradient approximations (e.g., Straight Through Estimator) and outperforms stateof-the-art quantization techniques on several benchmarks and architectures for image classification, language modeling, and audio source separation.
- Link: https://arxiv.org/pdf/2104.09987v2.pdf

**Parametric Contrastive Learning | 2021**

- Algorithm: ResNet-200
- This paper introduces a set of parametric class-wise learnable centers to rebalance from an optimization perspective and demonstrates that PaCo can adaptively enhance the intensity of pushing samples of the same class close as more samples are pulled together with their corresponding centers and benefit hard example learning
- Link: https://arxiv.org/pdf/2107.12028v2.pdf

**Beyond Self-attention: External Attention using Two Linear Layers for Visual Tasks | 2021**

- Algorithm: T2T-ViT-14
- A novel attention mechanism, based on two external, small, learnable, shared memories, which can be implemented easily by simply using two cascaded linear layers and two normalization layers is proposed, which conveniently replaces self-attention in existing popular architectures.
- Link: https://arxiv.org/pdf/2105.02358v2.pdf

**Pay Attention to MLPs | 2021**

- Algorithm: gMLP-B
- This work proposes a simple attention-free network architecture, gMLP, based solely on MLPs with gating, and shows that it can perform as well as Transformers in key language and vision applications and can scale as much as Transformers over increased data and compute.
- Link: https://arxiv.org/pdf/2105.08050v2.pdf

**Visformer: The Vision-friendly Transformer | 2021**

- Algorithm: Visformer-S
- A new architecture named Visformer is proposed, which is abbreviated from the ‘Vision-friendly Transformer’, which outperforms both the Transformer-based and convolution-based models in terms of ImageNet classification accuracy, and the advantage becomes more significant when the model complexity is lower or the training set is smaller.
- Link: https://arxiv.org/pdf/2104.12533v4.pdf

**Collaboration of Experts: Achieving 80% Top-1 Accuracy on ImageNet with 100M FLOPs | 2021**

- Algorithm: CoE-Large 214 MFLOPs
- This paper proposes a Collaboration of Experts (CoE) framework to pool together the expertise of multiple networks towards a common aim, and proposes three modules to impel each model to play its role, namely weight generation module (WGM), labelgeneration module (LGM) and variance calculation module (VCM)
- Link: https://arxiv.org/pdf/2107.03815v1.pdf

**Pyramidal Convolution: Rethinking Convolutional Neural Networks for Visual Recognition | 2020**

- Algorithm: PyConvResNet-101
- Different architectures based on PyConv are presented for four main tasks on visual recognition: image classification, video action classification/recognition, object detection and semantic image segmentation/parsing, showing significant improvements over all these core tasks in comparison with the baselines.
- Link: https://arxiv.org/pdf/2006.11538v1.pdf

**Shape-Texture Debiased Neural Network Training | 2020**

- Algorithm: ResNeXt-101 (Debiased+CutMix)
- A simple algorithm for shape-texture debiased learning that improves model performance on several image recognition benchmarks and adversarial robustness and is compatible to other advanced data augmentation strategies, e.g., Mixup and CutMix.
- Link: https://arxiv.org/pdf/2010.05981v2.pdf

**When Vision Transformers Outperform ResNets without Pre-training or Strong Data Augmentations | 2021**

- Algorithm: ResNet-152x2-SAM
- The aim is to improve the models’ data efficiency at training and generalization at inference, and substantially improve the accuracy and robustness of ViTs and MLP-Mixers on various tasks spanning supervised, adversarial, contrastive, and transfer learning.
- Link: https://arxiv.org/pdf/2106.01548v2.pdf

**Centroid Transformers: Learning to Abstract with Attention | 2021**

- Algorithm: CentroidViT-S (arXiv, 2021-02)
Centroid attention is proposed, a generalization of self-attention that maps N inputs to M outputs (M ≤ N ), such that the key information in the inputs are summarized in the smaller number of outputs (called centroids).
- Link: https://arxiv.org/pdf/2102.08606v2.pdf

**Supervised Contrastive Learning | 2020**

- Algorithm: ResNet-200 (Supervised Contrastive)
- A novel training methodology that consistently outperforms cross entropy on supervised learning tasks across different architectures and data augmentations is proposed, and the batch contrastive loss is modified, which has recently been shown to be very effective at learning powerful representations in the self-supervised setting.
- Link: https://arxiv.org/pdf/2004.11362v5.pdf

**LocalViT: Bringing Locality to Vision Transformers | 2021**

- Algorithm: LocalViT-S
- This work adds locality to vision transformers by introducing depth-wise convolution into the feed-forward network and successfully applies the same locality mechanism to 4 visiontransformers, which shows the generalization of the locality concept.
- Link: https://arxiv.org/pdf/2104.05707v1.pdf

**MEAL V2: Boosting Vanilla ResNet-50 to 80%+ Top-1 Accuracy on ImageNet without Tricks | 2020**

- Algorithm: ResNet-50 + MEAL V2
- This is the first work that is able to boost vanilla ResNet-50 to surpass 80% on ImageNet without architecture modification or additional training data, and can be regarded as a new strong baseline on Res net-50 using knowledge distillation.
- Link: https://arxiv.org/pdf/2009.08453v2.pdf

**Neural Architecture Transfer | 2020**

- Algorithm: NAT-M4
- Experimental evaluation indicates that, across diverse image classification tasks and computational objectives, NAT is an appreciably more effective alternative to conventional transfer learning of fine-tuning weights of an existing network architecture learned on standard datasets.
- Link: https://arxiv.org/pdf/2005.05859v2.pdf

**AutoDropout: Learning Dropout Patterns to Regularize Deep Networks | 2021**

- Algorithm: ResNet-50+AutoDropout+RandAugment
- This work proposes AutoDropout, which automates the process of designing dropout patterns, and shows that this method works well for both image recognition on CIFAR-10 and ImageNet, as well as language modeling on Penn Treebank and WikiText-2.
- Link: https://arxiv.org/pdf/2101.01761v1.pdf

**Attentional Feature Fusion | 2020**

- Algorithm: iAFF-ResNeXt-50-32x4d
- This work proposes a multiscale channel attention module, which addresses issues that arise when fusing features given at different scales, and demonstrates that the initial integration of feature maps can become a bottleneck and that this issue can be alleviated by adding another level of attention.
- Link: https://arxiv.org/pdf/2009.14082v2.pdf

**ConvMLP: Hierarchical Convolutional MLPs for Vision | 2021**

- Algorithm: ConvMLP-L
ConvMLP is proposed: a hierarchical Convolutional MLP for visual recognition, which is a light-weight, stage-wise, co-design of convolution layers, and MLPs.
- Link: https://arxiv.org/pdf/2109.04454v2.pdf

**Go Wider Instead of Deeper | 2021**

- Algorithm: WideNet-H
- This paper proposes a framework to deploy trainable parameters efficiently, by going wider instead of deeper, which plays the role to transform various semantic representations, which makes the model more parameter-efficient and effective.
- Link: https://arxiv.org/pdf/2107.11817v3.pdf

**Designing Network Design Spaces | 2020**

- Algorithm: RegNetY-8.0GF
- The RegNet design space provides simple and fast networks that work well across a wide range of flop regimes, and outperform the popular EfficientNet models while being up to 5x faster on GPUs.
- Link: https://arxiv.org/pdf/2003.13678v1.pdf

**Grafit: Learning fine-grained image representations with coarse labels | 2020**

- Algorithm: Grafit (ResNet-50)
- This paper tackles the problem of learning a finer representation than the one provided by training labels, which enables fine-grained category retrieval of images in a collection annotated with coarse labels only and significantly improves the accuracy of category-level retrieval methods.
- Link: https://arxiv.org/pdf/2011.12982v1.pdf

**Model Rubik's Cube: Twisting Resolution, Depth and Width for TinyNets | 2020**

- Algorithm: TinyNet (GhostNet)
- A tiny formula for downsizing neural architectures through a series of smaller models derived from the EfficientNet-B0 with the FLOPs constraint is summarized, observing that resolution and depth are more important than width for tiny networks.
- Link: https://arxiv.org/pdf/2010.14819v2.pdf

**Involution: Inverting the Inherence of Convolution for Visual Recognition | 2021**

- Algorithm: RedNet-152
- The proposed involution operator could be leveraged as fundamental bricks to build the new generation of neural networks for visual recognition, powering different deep learning models on several prevalent benchmarks, including ImageNet classification, COCO detection and segmentation, together with Cityscapes segmentation.
- Link: https://arxiv.org/pdf/2103.06255v2.pdf

**Self-Knowledge Distillation with Progressive Refinement of Targets | 2020**

- Algorithm: PS-KD (ResNet-152 + CutMix)
- A simple yet effective regularization method named Progressive self-knowledge distillation (PS-KD), which progressively distills a model's own knowledge to soften hard targets (i.e., one-hot vectors) during training, which can be interpreted within a framework of knowledge distillation as a student becomes a teacher itself.
- Link: https://arxiv.org/pdf/2006.12000v3.pdf

**Multiscale Deep Equilibrium Models | 2020**

- Algorithm: Multiscale DEQ (MDEQ-XL)
- In both settings, MDEQs are able to match or exceed the performance of recent competitive computer vision models: the first time such performance and scale have been achieved by an implicit deep learning approach.
- Link: https://arxiv.org/pdf/2006.08656v2.pdf

**Puzzle Mix: Exploiting Saliency and Local Statistics for Optimal Mixup | 2020**

- Algorithm: ResNet-50
- The experiments show Puzzle Mix achieves the state of the art generalization and the adversarial robustness results compared to other mixup methods on CIFAR-100, Tiny-ImageNet, and ImageNet datasets.
- Link: https://arxiv.org/pdf/2009.06962v2.pdf

**RepMLP: Re-parameterizing Convolutions into Fully-connected Layers for Image Recognition | 2021**

- Algorithm: RepMLP-Res50
- A structural re-parameterization technique that adds local prior into an FC to make it powerful for image recognition, and highlights that combining the global representational capacity and positional perception of FC with the local prior of convolution can improve the performance of neural network with faster speed on both the tasks with translation invariance and those with aligned images and positional patterns.
- Link: https://arxiv.org/pdf/2105.01883v2.pdf

**Scalable Vision Transformers with Hierarchical Pooling | 2021**

- Algorithm: HVT-S-1
- A Hierarchical Visual Transformer (HVT) is proposed which progressively pools visual tokens to shrink the sequence length and hence reduces the computational cost, analogous to the feature maps downsampling in Convolutional Neural Networks (CNNs).
- Link: https://arxiv.org/pdf/2103.10619v2.pdf

**Deep Polynomial Neural Networks | 2020**

- Algorithm: Prodpoly
- It is empirically demonstrated that $\Pi$-Nets have better representation power than standard DCNNs and they even produce good results without the use of non-linear activation functions in a large battery of tasks and signals, i.e., images, graphs, and audio.
- Link: https://arxiv.org/pdf/2006.13026v2.pdf

**GreedyNAS: Towards Fast One-Shot NAS with Greedy Supernet | 2020**

- Algorithm: GreedyNAS-A
- This paper proposes a multi-path sampling strategy with rejection, and greedily filter the weak paths to ease the burden of supernet by encouraging it to focus more on evaluation of those potentially-good ones, which are identified using a surrogate portion of validation data.
- Link: https://arxiv.org/pdf/2003.11236v1.pdf

**Contextual Classification Using Self-Supervised Auxiliary Models for Deep Neural Networks | 2021**

- Algorithm: SSAL-Resnet50
- Self-Supervised Autogenous Learning is introduced and it is shown that SSAL models outperform similar state-of-the-art methods focused on contextual loss functions, auxiliary branches and hierarchical priors.
- Link: https://arxiv.org/pdf/2101.03057v1.pdf

**Learning Visual Representations for Transfer Learning by Suppressing Texture | 2020**

- Algorithm: Perona Malik (Perona and Malik, 1990)
- This paper proposes to use classic methods based on anisotropic diffusion to augment training using images with suppressed texture to address problems of self-supervised learning and suggests that this approach helps in learning better representations that better transfer.
- Link: https://arxiv.org/pdf/2011.01901v2.pdf

**X-volution: On the unification of convolution and self-attention | 2021**

- Algorithm: ResNet-50
- This work theoretically derive a global self-attention approximation scheme, which approximates self-Attention via the convolution operation on transformed features, and establishes a multi-branch elementary module composed of both convolution and self-ATTention operation, capable of unifying both local and non-local feature interaction
- Link: https://arxiv.org/pdf/2106.02253v2.pdf

**MUXConv: Information Multiplexing in Convolutional Neural Networks | 2020**

- Algorithm: MUXNet-l
- MUXConv is a layer that is designed to increase the flow of information by progressively multiplexing channel and spatial information in the network, while mitigating computational complexity, and is integrated within an efficient multi-objective evolutionary algorithm to search for the optimal model hyper-parameters.
- Link: https://arxiv.org/pdf/2003.13880v2.pdf

**Perceiver: General Perception with Iterative Attention | 2021**

- Algorithm: Perceiver
- This paper introduces the Perceiver – a model that builds upon Transformers and hence makes few architectural assumptions about the relationship between its inputs, but that also scales to hundreds of thousands of inputs, like ConvNets.
- Link: https://arxiv.org/pdf/2103.03206v2.pdf

**A Large Batch Optimizer Reality Check: Traditional, Generic Optimizers Suffice Across Batch Sizes | 2021**

- Algorithm: ResNet-50 MLPerf v0.7 - 2512 steps
- It is demonstrated that standard optimization algorithms such as Nesterov momentum and Adam can match or exceed the results of LARS and LAMB at large batch sizes and shed light on the difficulties of comparing optimizers for neural network training more generally.
- Link: https://arxiv.org/pdf/2102.06356v3.pdf

**Semi-Supervised Learning of Visual Features by Non-Parametrically Predicting View Assignments with Support Samples | 2021**

- Algorithm: PAWS (ResNet-50, 10% labels)
- Despite the simplicity of the approach, PAWS outperforms other semi-supervised methods across architectures, setting a new state-of-the-art for a ResNet-50 on ImageNet trained with either 10% or 1% of the labels, reaching 75% and 66.5% top-1 respectively.
- Link: https://arxiv.org/pdf/2104.13963v3.pdf

**Do You Even Need Attention? A Stack of Feed-Forward Layers Does Surprisingly Well on ImageNet | 2021**

- Algorithm: FF
- This short report replaces the attention layer in a vision transformer with a feed-forward layer applied over the patch dimension, and results indicate that aspects of vision transformers other than attention, such as the patch embedding, may be more responsible for their strong performance than previously thought.
- Link: https://arxiv.org/pdf/2105.02723v1.pdf

**torchdistill: A Modular, Configuration-Driven Framework for Knowledge Distillation | 2020**

- Algorithm: ResNet-18 (PAD-L2 w/ ResNet-34 teacher)
- An open-source framework built on PyTorch and dedicated for knowledge distillation studies is presented, designed to enable users to design experiments by a declarative PyYAML configuration file, and helps researchers complete the recently proposed ML Code Completeness Checklist.
- Link: https://arxiv.org/pdf/2011.12913v2.pdf

**Correlated Input-Dependent Label Noise in Large-Scale Image Classification | 2021**

- Algorithm: Heteroscedastic (InceptionResNet-v2)
- This work places a multivariate Normal distributed latent variable on the final hidden layer of a neural network classifier, and demonstrates that the learned covariance structure captures known sources of label noise between semantically similar and co-occurring classes.
- Link: https://arxiv.org/pdf/2105.10305v1.pdf
