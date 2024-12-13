# 灾难性遗忘
灾难性遗忘/干扰(catcastrophic forgetting/interference)：在连续学习多个任务的过程中，，学习新知识的过程会遗忘旧知识，从而导致模型性能在旧任务中急剧下降
## 原因：
传统模型假设数据分布是固定或平稳的，训练样本iid分布，模型训练过程见到的数据可以反复学习，但是当数据变为数据流时，训练数据的分布是非平稳的，新知识会干扰旧知识，甚至覆盖
## 缓解方法
- 冻结重要权重
- 持续性学习，可以缓解灾难性遗忘的机器学习方法，包括正则化方法/记忆回放reply-based/参数孤立等
-- 记忆回放：基于样本：训练新任务的时候混一些旧任务的数据样本；基于特征：存储量化后的特征图，训练新任务的时候从记忆库重构出记忆和新数据一起训练
#对抗生成网络GAN的loss理解
[loss公式](