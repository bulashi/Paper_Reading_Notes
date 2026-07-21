# 中文论文阅读笔记

记录大语言模型、多模态大模型幻觉缓解与视觉 Transformer 相关论文的中文阅读笔记，持续更新。

## 论文索引

| 论文 | 核心创新点 | 中文笔记 | 原论文 |
| --- | --- | --- | --- |
| AIR: Adaptive Visual Reinforcements | 先用原型压缩视觉 token，再以最优传输度量选择并强化与当前隐藏状态一致的图像 patch。 | [PDF](./AIR_2602.24041_zh_CN.pdf) | [2602.24041](https://arxiv.org/abs/2602.24041) |
| ART: Attention Replacement Technique | 发现浅层均匀注意力会削弱关键信息聚焦，并以局部注意力替换它，无需额外训练。 | [PDF](./ART_zh_CN.pdf) | [2604.06393](https://arxiv.org/abs/2604.06393) |
| CIPHER | 用扩散模型构造反事实图像，提取视觉诱导幻觉的低秩子空间，并在推理时投影移除该成分。 | [PDF](./CIPHER_zh_CN.pdf) | [2603.10470](https://arxiv.org/abs/2603.10470) |
| Causal Route Gating (CRG) | 通过因果干预拆分并量化注意力头中的视觉/文本路由，只对视觉证据被语言先验压制的冲突头门控抑制文本路由。 | [PDF](./CRG_2605.24024_zh_CN.pdf) | [2605.24024](https://arxiv.org/abs/2605.24024) |
| GuarantRAG | 分离参数化推理与检索证据：Contrastive DPO 生成 Refer-Answer，再以 token 级联合解码融合两者。 | [PDF](./GUARANTRAG_zh_CN.pdf) | [2604.08046](https://arxiv.org/abs/2604.08046) |
| HAVAE: Hijacking-Aware Visual Attention Enhancement | 以固定劫持词锚定位惰性视觉 token，再筛选抗劫持关键头并选择性增强其对显著视觉内容的关注，无需训练。 | [PDF](./HAVAE_2605.10622_zh_CN.pdf) | [2605.10622](https://arxiv.org/abs/2605.10622) |
| HIRE | 动态定位含幻觉的中间表征，并进行 token 级编辑，以单次推理替代重训练或双路解码。 | [PDF](./HIRE_zh_CN.pdf) | [2603.29405](https://arxiv.org/abs/2603.29405) |
| HulluEdit | 将隐藏状态正交分解为视觉证据、冲突先验和不确定性子空间，只抑制先验中的幻觉成分。 | [PDF](./HulluEdit_2602.22727_zh_CN.pdf) | [2602.22727](https://arxiv.org/abs/2602.22727) |
| Vision Transformer | 将图像切分为 patch 序列并直接输入纯 Transformer；大规模预训练后迁移到视觉任务。 | [PDF](./ViT_2010.11929_zh_CN.pdf) | [2010.11929](https://arxiv.org/abs/2010.11929) |
| Attention Is All You Need | 以多头自注意力构建完全去除循环与卷积的 Transformer 编解码器，实现并行序列建模。 | [PDF](./attention_is_all_you_need.pdf) | [1706.03762](https://arxiv.org/abs/1706.03762) |

## 说明

创新点依据论文原文摘要与方法描述概括；笔记仅用于个人学习与学术交流，论文版权归原作者及出版方所有。
