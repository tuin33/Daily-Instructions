# 日常跑实验的一些tips
**数据集：** 数据版本、transform（数据增强、transform）

**optimizer + scheduler：** SGD+milestone或者Adam+warm up  注意param一定要包含要训练的所有参数

**模型load：** 检查是否都load进去了

**target：** 标签平滑

**training：** GPU数量、batchsize大小、学习率lr这三最好同步调

**其他：** layer_normalization、tanh
