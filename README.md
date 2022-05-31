# PFL-MQ

个性化联邦学习+模型量化

## 解决问题

在PS架构下，模型训练时间长、通信开销大以及同步屏障的问题，提高在non-IID数据分布上的训练精度。 （固定时间，不同non-IID程度下能够达到多少的精度；固定通信开销，不同non-IID程度下能够达到多少的精度；每一轮的等待时间；指定精度，需要的通信开销。）

## 方法

通过动态确定每一轮的量化比的方法降低等待时间，缓解同步屏障。同时根据数据分布和量化比确定模型聚合的权重。


## 20220531更新

阅读相关论文，已经存在不少关于这个想法的论文，只不过别人没有使用个性化的方法。我的改进太少
