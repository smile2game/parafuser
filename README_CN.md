# 🚀扩散模型的并行推理与训练

本仓库旨在回顾扩散模型（包括 UNet 和 Transformer 主干）的并行推理与训练，结合我自定义的方法和其他开源库进行对比分析。

我已经测试了所有开源的扩散模型并行推理与训练方法，并在下文列出，并在实验部分对它们的性能进行了对比实验。

在这些基础上，我开发了自己的并行化解决方案，并扩展支持了更多的模型。

## 结构
```bash
.
├── docs
├── examples #不仅包含我自定义的方法，还包括 distrifuser、xdit、megatron-lm（张量并行）、deepspeed（ulysses）、Ring attention 等示例
├── experiments # 各种方法的性能对比实验
├── infer 
├── scripts #快速启动的bash脚本
├── thirdparty
└── train
