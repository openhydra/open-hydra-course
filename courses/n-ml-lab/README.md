# 一、机器学习n个经典实验课程简介
机器学习n个经典实验聚焦于机器学习对应的相关课程实验。本课程基于BaseML设计，选择机器学习中最为经典的算法和数据集，以实验的方式呈现。课程涉及了线性回归（LinearRegression）、多项式回归（Polynomial）、随机森林（RandomForest）、支持向量机（SVM）、决策树（CART）、朴素贝叶斯（NaiveBayes）、K最近邻（KNN）、多层感知机（MLP）、Kmeans和Birch等。
实验涉及到的数据集，除来自经典数据集（如汽车燃油、波士顿房价、鸢尾花等）外，大部分属于自行制作。实验涉及的代码可以通过浦育平台（OpenInnoLab）、Mo平台访问和运行。
本课程由AI课程众筹计划团队开发，涉及的文档、代码、演示文稿、数据集等全部采用CC-BY协议开源。AI课程众筹计划全称为中小学开源AI课程众筹计划，由谢作如名师工作室和温州科技高级中学发起的公益活动。活动关注以机器学习、深度学习为核心的新一代AI技术，以“开源”的方式分享各种面向真实问题解决的项目式学习课程，期望能形成一系列具备复制价值的中小学AI课程库。

# 二、编写人员

规划：谢作如

编写：陆雅楠、林淼焱、陈恩慈、邱奕盛、魏静洁

审稿：王怡婷、刘正云、张敬云

# 三、课程目录

## 前言 机器学习基础知识

  - 机器学习的概念
  - 机器学习的基本流程
  - 机器学习的训练工具

## 第一部分 回归任务

### 1-1 [线性回归和温度转换探究](01-part/01-lab/线性回归和温度转换探究教案.ipynb)

编写：魏静洁

数据集：温度转换

实验1：摄氏温度转华氏温度

实验2：华氏温度转摄氏温度

结论：通过线性回归算法训练模型，我们能够准确地将摄氏温度转换为华氏温度，验证了摄氏温度和华氏温度之间存在线性关系。

openinnolab项目链接：https://www.openinnolab.org.cn/pjlab/project?id=668baf67be41a80a6ba1d6a4&backpath=/pjlab/projects/list#public
资源：文档、数据集、代码、PPT、微视频（可选）

### 1-2 多项式回归和汽车燃油效率预测

编写：陆雅楠

数据集：汽车燃油效率

实验1：使用全部特征训练多项式回归模型

实验2：基于特征选择的多项式回归模型训练

结论：通过分别使用全部特征和选择部分特征进行实验，验证了多项式回归算法在汽车燃油效率评估中的适用性。同时验证了通过有效特征的选择，可以提高模型预测的准确度。

openinnolab项目链接：https://www.openinnolab.org.cn/pjlab/project?id=66948d4b6eedcd184861d3dc&backpath=/pjedu/userprofile?slideKey=project

### 1-3 随机森林和波士顿房价

编写：陈恩慈

数据集：波士顿房价

实验1：使用随机森林算法训练模型

实验2：修改参数优化模型

结论：在实验一中，我们使用随机森林算法对波士顿房价数据集进行了训练。实验结果表明，随机森林模型能够有效地捕捉波士顿房价数据中的特征与价格之间的关系，从而实现对房价的预测。
在实验二中，我们对随机森林模型的决策树数量进行了调整，以优化模型性能。通过比较不同决策树数量下的模型性能，我们发现决策树数量的增加可以提升模型的预测精度，但过大的决策树数量可能导致过拟合。因此，我们需要在预测精度与过拟合之间找到一个平衡点。

openinnolab项目链接：https://www.openinnolab.org.cn/pjlab/project?id=66967e8c6eedcd1848777aa3&sc=64b33e20aac6f67c8236f417#public

### 1-4 支持向量机和鲍鱼年龄预测

编写：陈恩慈

数据集：鲍鱼年龄数据集

实验1：使用向量机算法训练模型

实验2：修改参数优化模型准确性

结论：通过使用支持向量机 (SVM) 算法训练鲍鱼年龄模型，我们验证了该方法在预测鲍鱼年龄方面的具有一定的有效性。通过调整 SVM 模型的参数，如 C、gamma 和 kernel，我们发现这些参数对模型的性能有一定影响。通过比较不同参数设置下的模型性能，我们确定了最佳的参数组合，这进一步提升了模型的预测精度。

openinnolab项目链接：https://www.openinnolab.org.cn/pjlab/project?id=66af37231232f3376a117382&sc=64b33e20aac6f67c8236f417#public

## 第二部分 分类任务

### 2-1 决策树和出行预测

编写：陆雅楠

数据集：出行预测

实验1：搭建决策树算法训练出行预测模型

实验2：通过参数调整探究模型效果

结论：通过搭建决策树算法训练一个出行预测模型，通过实验验证，决策树算法能够有效地分类和预测不同的出行模式。

链接：https://www.openinnolab.org.cn/pjlab/project?id=669492846eedcd1848928dbd&sc=62f34141bf4f550f3e926e0e#public

### 2-2 朴素贝叶斯和天气预报

编写：魏静洁

数据集：某地区天气预报

实验1：用朴素贝叶斯算法搭建并训练天气预报模型

实验2：通过特征选择探究模型效果

链接：https://www.openinnolab.org.cn/pjlab/project?id=641a6dae9aa34d67d15b5214&backpath=/pjlab/projects/list#public

结论：通过使用全部数据和部分数据进行实验，验证朴素贝叶斯算法在天气预报模型中的适用性，并且通过特征选择，对数据有更深入的理解。

### 2-3 K最近邻和果物分类

编写：林淼焱

数据集：包含不同种类的柑橘类水果的果物数据集(来自kaggle网站) https://www.kaggle.com/datasets/joshmcadams/oranges-vs-grapefruit

openinnolab项目链接：https://www.openinnolab.org.cn/pjlab/project?id=6695c480d2c4e3576330a8b7&backpath=/pjlab/projects/list

实验1：用KNN算法训练一个果物数据分类模型。

实验2：通过参数调整训练一个更好的分类模型。

结论：使用K最近邻分类算法训练模型后，我们可以准确地对数值数据进行分类。通过实验2，我们发现KNN算法在果物数据集上的表现可以通过调整参数进行优化。选择合适的k值和权重处理对于模型的准确性至关重要。

### 2-4 支持向量机和手势分类

编写：魏静洁

数据集：手势分类数据集（自行采集）

openinnolab项目链接：https://www.openinnolab.org.cn/pjlab/project?id=66a1b1de8034227b8af1bac1&backpath=/pjedu/userprofile?slideKey=project

实验1：使用支持向量机进行手势分类

实验2：使用不同核函数构建SVM模型

结论：通过实验，验证了支持向量机算法在手势分类模型中的性能，并且通过使用不同核函数构建SVM模型，对支持向量机算法以及模型构建有更深入的理解。

### 2-5 多层感知机和鸢尾花分类

编写：魏静洁

数据集：鸢尾花数据集

openinnolab项目链接：https://www.openinnolab.org.cn/pjlab/project?id=66ac572a1232f3376ab890e3&backpath=/pjedu/userprofile?slideKey=project

实验1：使用多层感知机搭建并训练鸢尾花分类模型

实验2：通过参数调整探究模型效果

结论：通过实验，验证了多层感知机在鸢尾花分类模型中的性能，并且通过调整参数提升模型效果，对多层感知机模型有了更深入的理解。

## 第三部分 聚类任务
#### 3-1 Kmeans聚类和场馆分布

编写：林淼焱

数据集：温州市城市书房地理位置（来自温州市公共数据开放平台）

实验1：Kmeans算法探究-模型的训练与推理

实验2：Kmeans算法应用-区域场馆分布与优化

结论：算法结合可视化的图表，可以找出数值数据中无法发现的数据规律，并指导城市规划和公共资源分配等实际活动。

项目地址：https://www.openinnolab.org.cn/pjlab/project?id=6694d307be41a80a6b4bf699&backpath=/pjedu/userprofile?slideKey=project

参考文档：网购用户的画像分析https://www.openinnolab.org.cn/pjlab/project?id=6530d31fe036f8568ac9a824&backpath=/pjlab/projects/list#public

### 3-2 Birch算法和操场人群分布实验

编写：邱奕盛

数据集：操场人群分布数据集

实验一：使用Birch算法划分操场的人群分布

实验二：观察层次聚类的边界

结论：
- 通过实验一，我们发现Birch算法可以一定程度上满足人群划分的预期。但是在圆形环绕分布的数据上表现不佳。Birch算法的优点是可以适应簇间样本数量不均衡的情况，缺点是对圆形的数据适用性较差。
- 通过实验二，我们观察到了Birch划分的边界，验证了Birch算法的层次聚类过程，每个簇是由更小的簇合并而来的。

openinnolab项目链接：https://www.openinnolab.org.cn/pjlab/project?id=66b48e743d983e6b4ebdc32e&backpath=/pjedu/userprofile?slideKey=project#public

附录：

1. 借助EasyTrain不写代码生成训练代码
2. 从模型训练到应用部署