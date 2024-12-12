# 近年方法对比
- DepthFL : Depthwise Federated Learning for Heterogeneous Clients  
主要内容：针对不同客户端资源分配不均匀，对局部模型进行自蒸馏操作  
- FedFA: Federated Feature Augmentation  
主要内容：通过特征增强的策略解决客户端特征偏移的问题  
- Personalized Federated Learning with Feature Alignment and Classifier Collaboration  
研究问题：数据异质性  
提出方法：FedPAC 特征对齐和分类器协助  
  -- 特征对齐采用全局特征质心来正则化本地特征提取器，减少不同客户端之间的表示多样性，促进全局聚合。  
  -- 分类器协作则通过对相似客户端的分类器进行加权平均，鼓励相似客户端之间的协作，避免无关客户端的负面迁移  
- FedSpeed: Larger Local Interval, Less Communication Round, and Higher Generalization Accuracy  
研究问题：数据分布异质性和局部过拟合导致的客户端漂移问题  
提出方法：局部更新时引入一个偏差项，减轻局部数据和全局数据分布的不一致性  
- FedAvg，FedProx，FedCM，FedAdam，SCAFFOLD，FedDyn，FedADMM  
# 聚类方法对比  
- K-means方法  
- DBSCAN(Density-Based Spatial Clustering of Applications with Noise)  
- 高斯混合模型（GMM）的最大期望（EM）聚类  
# 实验参考论文
