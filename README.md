# 项目介绍
这个项目用于提取19元GaN HEMT等效电路的元件参数。主要的思想为根据已有的数据进行经验迁移，实现提高效率的目标。不同于传统的PSO启发式算法，这里选用了GPBO，其优势在于概率性建模，效果更好。
## 项目结构

.
├─Experiment 用于存放实验数据及文件
│    ├─exp_optimize 表示优化迭代实验
│    ├─exp_transfer 表示迁移实验
│    ├─flow 演示了流程
│
│
├─Model 用于存放模型文件
│    ├─ dknet 为实现的神经网络核
│    ├─ BO 为贝叶斯优化
│    ├─ psoOptimize 为pso的baseline
│    ├─ Initial... 为初始点设计的方法
│    ├─ Search... 为搜索空间设计
│    ├─....
│
│
├─Simulaiton 为仿真所需的一些文件
## 开发环境
python版本为3.8
## 库信息
待补充...