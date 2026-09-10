# D2L 个人练习

这里存放自己的代码和实验；`D:\d2l\chapter_*` 下的官方 Notebook 只作为教材和参考。

## 目录

| 目录 | 内容 |
|---|---|
| `00_preliminaries/` | 张量、线性代数、自动微分基础自测 |
| `01_softmax/` | Softmax、交叉熵与分类训练 |
| `02_mlp/` | 多层感知机、反向传播、正则化 |
| `03_optimization/` | SGD、Momentum、Adam 与对照实验 |
| `04_cnn/` | 卷积、LeNet、ResNet |
| `05_rnn/` | RNN 与序列建模 |
| `06_transformer/` | 注意力、掩码、位置编码与 Transformer |
| `07_detection_segmentation/` | 目标检测与语义分割 |
| `08_self_supervised_multimodal/` | 自监督、CLIP、DINO 等后续内容 |

## 使用规则

- 简单知识点使用一个 Notebook 做短测，不机械抄写官方示例。
- 核心算法使用 `.py` 独立实现；测试写在 `test_*.py`。
- 同一主题持续修改同一组文件，不按每天复制新版本。
- 图表、模型和日志放在该主题的 `results/` 中，需要时再创建。
- 与 CS231n 作业重合的实现直接在作业目录完成，不在这里重复写。

## 文件命名

- 基础自测：`主题_check.ipynb`
- 从零实现：`模型_scratch.py`
- 训练入口：`train.py`
- 自动检查：`test_模型.py`
- 探索和画图：`experiment.ipynb`
