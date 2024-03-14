<div align="center">

# 🍿**InternLM2_Horowag**🍿

🍏**专门为 2024 书生·浦语挑战赛 (春季赛) 准备的 Repo - 收录了赫萝相关的微调模型**🍎
</div>

![alt text](image/img-1.png)

## 🌠**基本介绍**

**`Horowag_7b` 是由书生·浦语的 `InternLM2-Chat-7b` 经过微调得到的角色扮演聊天系列机器人。具体目标是将《狼与香辛料》中贤狼赫萝的形象带入大语言模型，实现带入感较高的角色扮演行为。针对技术细节，`Horowag_7b` 使用了书生·浦语开源的 `Xtuner` 进行低成本微调训练，在训练条件较差的条件下，赋予模型高质量的自然语言处理能力。硬件方面，我采用了 `(1/2) A100` 支持训练，显存约 `40G` 左右，如果参数调节合理，显存可控制在 `16G`以下。**

![alt text](image/img-2.jpg)
---

<div align="center">

| 版本号 | 模型相关解释 |
|:-------:|:-------:|
| **Horowag_7b** | **InternLM2-Chat-7b 微调后的基础赫萝对话模型** |
| **Horowag_7b_Craft** | **优化数据增强方法 + Langchain 辅助模型输出** |
| **Horowag_Mini** | **InternLM2-Chat-1_8b 微调后的轻量级赫萝对话模型** |
| **Chatty_Horo_Voich** | **InternLM2-Chat-7b 微调 + Assistant Model + VITS** |
| **-- 亟待后续 --** | **--** |

</div>

---
![alt text](image/img-3.jpg)

**除去基本的 `Horowag_7b` 链条，为了能够丰富语言模型角色扮演的模式和手段，我还推出了 `Horowag_7b_Craft`、`Horowag_Mini` 和 `Chatty_Horo_Voich`**
