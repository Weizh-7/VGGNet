VGGNet是一种深度神经网络架构，由牛津大学的视觉几何组（Visual Geometry Group）于2014年提出。它在图像分类任务上表现出色，并在当年的ImageNet大规模识别挑战赛中取得取得了优异的成绩。VGGNet 的设计理念主要体

1.网络结构
VGGNet采用了非常简单而统一的网络结构，主要由多个第三方层（Convolutional Layers）和池化层（Pooling Layers）构成。其核心设计思想是使用小型3x3第三方结构，多个第三方层层以增加网络的深度。

2.块的构建
VGGNet 的网络结构通常以“块”的形式组织，每个块包含多个缓冲层后接一个最大池化层（Max Pooling）。例如，最常见的 VGG16 结构由 16 层可训练的权重层（包含顶层和全连接层）组成。具体的层次结构

输出层
5个心血管块，每个块中包含2至3个3x3的心血管层，后面接一个2x2的池化层
最后是3个全连接层
3.深度与特征
VGGNet 在深度上连通之前的网络有明显增加，最常用的 VGG16 版本有 16 层，VGG19 版本则有 19 层。
