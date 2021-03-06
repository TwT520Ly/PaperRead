Paper: https://www.biorxiv.org/content/biorxiv/early/2018/11/04/461525.full.pdf

## 摘要 ##

ANNs是目前表达灵长类生物大脑腹侧视觉流的最精准模型。利用ANN驱动的图像合成模型来近似图像作用于灵长类生物的视网膜之后的V4-神经元的活动状态。该方式已经实现对V4-神经元群的整体控制。从而表明通过ANN模型的内部特征嵌入方式可以从神经元级别设置大脑的神经元状态。

## 正文 ##

之前的工作表明了视觉诱导ANNs模型内部表征方式的逻辑与视觉诱导大脑腹侧视觉流的表征方式是类似的，主要体现在中层次的V4神经元群和高级别的IT神经元群，表明了模型与大脑的近似性。但是存在两个问题，第一，model-to-brain逻辑是感觉上可行的，但是没有真正的实验测试；第二，先前的证明中所采样的图像不具有更强的泛化性能。

因此第一步实验测试ANNs是否存在一个潜在表达能力从而实现对大脑神经元的控制，第二步实验测试对新的图像数据的泛化能力。（模型中的神经元的活动模式与灵长类生物的视觉皮层响应相同图像数据时有着相似的活动模式，从而在验证该理论之后，进一步验证是否可以利用模型对动物视觉皮层的活动模型进行预测并实现控制）

选用一个固定了一组参数的模型来生成实验图像（控制器图像），当将该图像作用于实验者视网膜时，通过两个实验设定尝试控制在视觉皮层V4区域的选定神经元的活动，设定（1）合成图像对单个神经元的最大拉伸速率超过自然情况下的速率；设定（2）为神经元群的状态控制，合成图像可以独立的控制神经元群中的每一个神经元。

通过实验建立从V4到ANNs模型的映射，model-to-brain的映射预测精度作为仿大脑模型对大脑的近似逼真程度，

**伸展测试: 最大化每一个V4区神经元结点的活动响应**
     

