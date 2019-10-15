<<<<<<< HEAD
# 陆思奇 201934729
# <center>实验报告  </center>

## 一、    实验内容

​        利用[K-Means](https://scikit-learn.org/stable/modules/clustering.html#k-means)、[Affinity propagation](https://scikit-learn.org/stable/modules/clustering.html#affinity-propagation)、[Mean-shift](https://scikit-learn.org/stable/modules/clustering.html#mean-shift)、[Spectral clustering](https://scikit-learn.org/stable/modules/clustering.html#spectral-clustering)、[Ward hierarchical clustering](https://scikit-learn.org/stable/modules/clustering.html#hierarchical-clustering)、[Agglomerative clustering](https://scikit-learn.org/stable/modules/clustering.html#hierarchical-clustering)、[DBSCAN](https://scikit-learn.org/stable/modules/clustering.html#dbscan)、[Gaussian mixtures](https://scikit-learn.org/stable/modules/mixture.html#mixture)八种聚类算法在load_digits、fetch_20newsgroups两个数据集上的聚类效果。

## 二、    实验目的

（1）了解常用聚类算法原理。

（2）掌握利用多种聚类算法对数据集进行分析。

## 三、    实验步骤

### （1）  使用工具：

​        jupyter notebook 

### （2）  实现过程：

​        加载数据集、数据集降维（使用sklearn内的TfidfVectorizer 将文本转化为tf-idf向量形式表示）、选择聚类算法、参数调整、结果输出。

## 四、    结论

​      使用DBSCAN时，当聚类有不同的密度时，它的性能不像其他聚类算法那样好，因为密度变化时，距离阈值和识别临近点的设置会随着聚类而变化。K-means算法在数据集大时结果容易局部最优；需要预先设定K值，对最先的K个点选取很敏感。
