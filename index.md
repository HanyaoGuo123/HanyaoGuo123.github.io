---
layout: default
---

# 算法与模型的区别

## 算法（Algorithm）

* 算法是一个明确的、有序的、有限的步骤集合
* 是用于解决特定问题或执行一个特定的任务

算法每一步骤是清晰无歧义的，且步骤的顺序是固定的，不能无期限的运行，经过一定步骤后自动结束，每次运算时按照相同的’pipeline‘去挖掘处理数据。总而言之，**<mark>算法就是对于获得的海量数据，你是按照什么方法去分析处理，获取信息的。这个方法就是“算法”</mark>**。

举例：排序算法（Sorting algorithm）和动态规划算法（Dynamic Programming Algorithm）

![Local Image](./assets/img/example1.jpg)

排序算法是为了完成排序任务的明确方法步骤

## 模型（Model）

* 模型是在训练数据上运行机器学习算法后保存的“东西“
* 模型表示用于预测的”规则“

人工智能领域的“**模型**”是指基于已有数据集，运行机器学习算法，所得到的**输出**。可以简单理解为，**<mark>就是通过算法，我们学到的规则</mark>**。

举例：线性回归（Linear Regression）与逻辑回归（Logistic Regression）

![Local Image](/assets/img/example2.jpg)

## <mark>总结</mark>

**模型 = 数据 + 算法**



# Bioinformatics学习计划

## 模块一：NGS基础知识与实践

1. 熟悉常用NGS技术原理：RNA-seq，ChIP-seq，scRNA-seq等
2. 优化自己之前搭建的NGS raw data上游pipeline，并理解每一步的**作用和数学原理**
3. 优化之前自己搭建的常用NGS下游pipeline，例Differential Expression  Analysis、GO/KEGG enrichment，着重学习不太熟悉的ChIP-seq和ATAC-seq的motif analysis
4. 进阶：利用网络资源自学空间转录组分析方法，搭建自己的pipeline

## 模块二：编程基础

1. ~~对R已经较为熟练，继续做巩固练习~~
2. 主要进一步学习**Linux的基础操作**，尤其是shell语法，学习编写bash脚本进行文件处理<font color=red>（薄弱，重点学习）</font>
3. 主要加强对**Python**学习和掌握，主要学习**Scanpy**，利用Scanpy分析处理单细胞数据

## 模块三：机器学习/深度学习基础

1. 首先要学习机器学习和深度学习流程的搭建（在github中如何规范存储机器学习和深度学习的文件？规范格式是怎样的？）
2. 了解基础概念：如什么是**损失函数**，什么是**激活函数**，他们都有怎么样的作用
3. 学习常用机器学习算法：线性回归、逻辑回归、RandomForest和SVM等，了解数学原理，并学会用Python对示例数据编写脚本，**学会在github建一个自己的ML project**
4. 进阶：了解机器学习和深度学习在生物学前沿分析中的应用，思考和自己课题有关的内容和设计

