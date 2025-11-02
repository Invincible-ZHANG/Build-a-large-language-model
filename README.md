# Build a Large Language Model — From Scratch

> 入门项目：从零实现一个迷你版 LLM 的关键部件（分词、数据集、嵌入与位置编码等）。  
> 代码与讲解尽量简洁，便于快速上手与迭代。

本仓库是我基于《从零构建大模型（Build a Large Language Model from Scratch）》的动手项目。
目标：**从分词、数据集、嵌入、位置编码、注意力、Transformer Block 到训练与推理**，用尽量少的依赖把每个模块实现清楚，并能在小数据上完成端到端训练与采样。

> 说明：实现以教学可读性为优先，工程优化（高性能、分布式、混合精度等）后续逐步加入。


## 目录结构
├── ch2_tokenization.ipynb # 第2章：分词与数据加载（含练习）
├── main.py # 运行脚本（可逐步扩展为训练入口）
├── the-verdict.txt # 示例文本（数据源）
├── README.md
└── .gitignore


## 更新日志
* 11.1 学完了数据预处理

