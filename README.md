<h1 align="center"> 🚀 awesome-awesome-Semi-supervised-clustering </h1>

<p align="center">
  <img src="https://awesome.re/badge.svg">
  <a href="https://github.com/Wintersdragon/awesome-awesome-Semi-supervised-clustering">
    <img src="https://img.shields.io/badge/Awesome-AwesomeML-orange">
  </a>

  <a href="https://github.com/Wintersdragon/awesome-awesome-Semi-supervised-clustering/stargazers">
    <img src="https://img.shields.io/github/stars/Wintersdragon/awesome-awesome-Semi-supervised-clustering.svg">
  </a>

  <a href="https://github.com/Wintersdragon/awesome-awesome-Semi-supervised-clustering/network/members">
    <img src="https://img.shields.io/github/forks/Wintersdragon/awesome-awesome-Semi-supervised-clustering.svg">
  </a>

  <a href="https://github.com/Wintersdragon/awesome-awesome-Semi-supervised-clustering/issues">
    <img src="https://img.shields.io/github/issues/Wintersdragon/awesome-awesome-machine-learning">
  </a>

  <a href="https://github.com/Wintersdragon/awesome-awesome-Semi-supervised-clustering/LICENSE">
    <img src="https://img.shields.io/github/license/Wintersdragon/awesome-awesome-machine-learning">
  </a>

---

### 半监督学习

半监督学习是一种机器学习方法，它结合了有标签数据和无标签数据来构建模型。在半监督学习中，我们通常只有一小部分有标签的样本数据，而大多数数据都没有标签。与监督学习不同，半监督学习的目标是使用少量的标记样本来训练一个分类器，并在未标记的样本上进行推断。

半监督学习的主要思想是利用未标记数据的分布信息和特征之间的关系来提高模型的性能。这种方法通常被用于那些难以获取大量标记数据的应用中，例如图像、音频和文本领域等。

半监督学习通常可以分为一下几类，它们的优缺点如下表格（秦悦 等, 计算机科学 2019）：

  ![image](https://github.com/Wintersdragon/awesome-awesome-Semi-supervised-clustering/blob/main/2.png)

### 半监督聚类

传统无监督聚类算法在划分数据时并不需要任何数据属性，但在实际应用中，存在少量带有独立类标签或成对约束的监督信息的数据样本，学者们致力于将这些为数不多的监督信息运用于聚类，以得到更优的聚类结果，从而提出了半监督聚类。

![image](https://github.com/Wintersdragon/awesome-awesome-Semi-supervised-clustering/blob/main/1.png)

### 半监督聚类算法的分类

一般情况下，按照学习场景的不同，半监督学习可以划分为 3 类：

- **基于约束的方法**：这种方法使用人工标记的样本来限制聚类结果，例如，必须将某些样本聚为一类或不同类。基于约束的方法包括Cop K-Means等。
- **基于距离的半监督聚类算法**：这类算法的特点是在对数据进行预处理的过程中，对样本之间的相似性度量进行变换，从而得到一个新的测量函数，使得相关联的正约束样本之间更加相近而负样本则更加相反。
- **基于约束和距离相结合的半监督聚类算法**：这类算法是将前两种方法相结合而得到的一种新的算法，可以获得更好的聚类效果。

### 部分半监督聚类算法及开源代码

  - [**[List] Deep Clustering**](https://github.com/zhoushengisnoob/DeepClustering) ![](https://img.shields.io/github/stars/zhoushengisnoob/DeepClustering?style=social)
    - 深度聚类：方法和实现

  - [**[List] Awesome Community Detection Research Papers**](https://github.com/benedekrozemberczki/awesome-community-detection) ![](https://img.shields.io/github/stars/benedekrozemberczki/awesome-community-detection?style=social)
    - 社区检测论文集。
  - [**[List] Awesome Multi-view Clustering**](https://github.com/wangsiwei2010/awesome-multi-view-clustering) ![](https://img.shields.io/github/stars/wangsiwei2010/awesome-multi-view-clustering?style=social)
    - 最新（SOTA），新颖的多视图聚类方法（论文，代码和数据集）的集合。
  - [**[List] Awesome-Deep-Graph-Clustering**](https://github.com/yueliu1999/Awesome-Deep-Graph-Clustering) ![](https://img.shields.io/github/stars/yueliu1999/Awesome-Deep-Graph-Clustering?style=social)
    - 最先进的（SOTA），新颖的深度图聚类方法（论文，代码和数据集）的集合。
    - 
  - [**[List] The COP-Kmeans algorithm**](https://github.com/Behrouz-Babaki/COP-Kmeans) ![](https://github.com/Behrouz-Babaki/COP-Kmeans)
    - Cop-Kmeans算法是一种基于约束的半监督聚类算法

  - [**[Library] faiss**](https://github.com/facebookresearch/faiss) ![](https://img.shields.io/github/stars/facebookresearch/faiss?style=social)
      - 用于高效相似性搜索和密集向量聚类的库。
  - [**[Library] hdbscan**](https://github.com/scikit-learn-contrib/hdbscan) ![](https://img.shields.io/github/stars/scikit-learn-contrib/hdbscan?style=social)
      - HDBSCAN 群集的高性能实现。
  - [**[Code Collection] time-series-classification-and-clustering**](https://github.com/alexminnaar/time-series-classification-and-clustering) **[⚠️Inactive]** ![](https://img.shields.io/github/stars/alexminnaar/time-series-classification-and-clustering?style=social)
      - 用 Python 编写的时间序列分类和聚类代码。


