# 计算广告论文、学习资料、业界分享
在这里分享我工作中实现或者阅读过的计算广告相关论文、学习资料和业界分享。作为自己工作的整理和总结，也希望能为计算广告相关行业的技术同学带来便利。所有资料均来自于互联网，如有侵权，请联系[王喆](http://wangzhe.website/about/)

**下面将列出所有的资料目录，以及我对每篇文章的简要介绍** <br>如有任何问题，欢迎对计算广告感兴趣的同学与我讨论，我的联系方式如下：
* email: wzhe06@163.com
* 知乎私信: [王喆的知乎](https://www.zhihu.com/people/wang-zhe-58)
* 主页留言: [王喆的主页](http://wangzhe.website/about/)

## 目录
### Allocation
广告流量的分配问题
* [Ad Serving Using a Compact Allocation Plan](https://github.com/wzhe06/Ad-papers/blob/master/Allocation/Ad%20Serving%20Using%20a%20Compact%20Allocation%20Plan.pdf)雅虎的一篇比较经典的流量分配的文章，文中的HWM和DUAL算法都比较实用
* [An Efficient Algorithm for Allocation of Guaranteed Display Advertising](https://github.com/wzhe06/Ad-papers/blob/master/Allocation/An%20Efficient%20Algorithm%20for%20Allocation%20of%20Guaranteed%20Display%20Advertising.pdf)同样是雅虎的流量分配文章，跟上一篇文章同时发布，介绍SHALE流量分配算法
### Bidding Strategy
计算广告中广告定价，RTB过程中广告出价策略的相关问题
* [Combining Powers of Two Predictors in Optimizing Real-Time Bidding Strategy under Constrained Budget](https://github.com/wzhe06/Ad-papers/blob/master/Bidding%20Strategy/Combining%20Powers%20of%20Two%20Predictors%20in%20Optimizing%20Real-Time%20Bidding%20Strategy%20under%20Constrained%20Budget.pdf) 国立台湾大学的文章，介绍一种基于流量选择的计算广告竞价方法，有别于传统的CTR CPC的方法，我在实践中尝试过该方法，非常有效
* [Real-Time Bidding Algorithms for Performance-Based Display Ad Allocation](https://github.com/wzhe06/Ad-papers/blob/master/Bidding%20Strategy/Real-Time%20Bidding%20Algorithms%20for%20Performance-Based%20Display%20Ad%20Allocation.pdf)微软的一篇基于PID反馈控制的与效果相关的竞价算法
* [Research Frontier of Real-Time Bidding based Display Advertising](https://github.com/wzhe06/Ad-papers/blob/master/Bidding%20Strategy/Research%20Frontier%20of%20Real-Time%20Bidding%20based%20Display%20Advertising.pdf)张伟楠博士的一篇介绍竞价算法的ppt，可以非常清晰的了解该问题的主要方法
### Budget Control
广告系统中Pacing，预算控制，以及怎么把预算控制与其他模块相结合的问题
* [Budget Pacing for Targeted Online Advertisements at LinkedIn](https://github.com/wzhe06/Ad-papers/blob/master/Budget%20Control/Budget%20Pacing%20for%20Targeted%20Online%20Advertisements%20at%20LinkedIn.pdf)
* [PID控制原理与控制算法](https://github.com/wzhe06/Ad-papers/blob/master/Budget%20Control/PID%E6%8E%A7%E5%88%B6%E5%8E%9F%E7%90%86%E4%B8%8E%E6%8E%A7%E5%88%B6%E7%AE%97%E6%B3%95.doc)
* [PID控制经典培训教程](https://github.com/wzhe06/Ad-papers/blob/master/Budget%20Control/PID%E6%8E%A7%E5%88%B6%E7%BB%8F%E5%85%B8%E5%9F%B9%E8%AE%AD%E6%95%99%E7%A8%8B.pdf)
* [Real Time Bid Optimization with Smooth Budget Delivery in Online Advertising](https://github.com/wzhe06/Ad-papers/blob/master/Budget%20Control/Real%20Time%20Bid%20Optimization%20with%20Smooth%20Budget%20Delivery%20in%20Online%20Advertising.pdf)
* [Smart Pacing for Effective Online Ad Campaign Optimization](https://github.com/wzhe06/Ad-papers/blob/master/Budget%20Control/Smart%20Pacing%20for%20Effective%20Online%20Ad%20Campaign%20Optimization.pdf)

### CTR Prediction
CTR预估模型相关问题
* [Ad Click Prediction a View from the Trenches.pdf](https://github.com/wzhe06/Ad-papers/blob/master/CTR%20Prediction/Ad%20Click%20Prediction%20a%20View%20from%20the%20Trenches.pdf)
* [Adaptive Targeting for Online Advertisement.pdf](https://github.com/wzhe06/Ad-papers/blob/master/CTR%20Prediction/Adaptive%20Targeting%20for%20Online%20Advertisement.pdf)
* [Logistic Regression in Rare Events Data.pdf](https://github.com/wzhe06/Ad-papers/blob/master/CTR%20Prediction/Logistic%20Regression%20in%20Rare%20Events%20Data.pdf)
* [Practical Lessons from Predicting Clicks on Ads at Facebook.pdf](https://github.com/wzhe06/Ad-papers/blob/master/CTR%20Prediction/Practical%20Lessons%20from%20Predicting%20Clicks%20on%20Ads%20at%20Facebook.pdf)
* [The Problem of Modeling Rare Events in ML-based Logistic Regression.pdf](https://github.com/wzhe06/Ad-papers/blob/master/CTR%20Prediction/The%20Problem%20of%20Modeling%20Rare%20Events%20in%20ML-based%20Logistic%20Regression.pdf)

### Computational Advertising Architect
广告系统的架构问题
* [Display Advertising with Real-Time Bidding (RTB) and Behavioural Targeting.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Computational%20Advertising%20Architect/Display%20Advertising%20with%20Real-Time%20Bidding%20(RTB)%20and%20Behavioural%20Targeting.pdf)
* [大数据下的广告排序技术及实践.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Computational%20Advertising%20Architect/%E5%A4%A7%E6%95%B0%E6%8D%AE%E4%B8%8B%E7%9A%84%E5%B9%BF%E5%91%8A%E6%8E%92%E5%BA%8F%E6%8A%80%E6%9C%AF%E5%8F%8A%E5%AE%9E%E8%B7%B5.pdf)
* [美团机器学习 吃喝玩乐中的算法问题.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Computational%20Advertising%20Architect/%E7%BE%8E%E5%9B%A2%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%20%E5%90%83%E5%96%9D%E7%8E%A9%E4%B9%90%E4%B8%AD%E7%9A%84%E7%AE%97%E6%B3%95%E9%97%AE%E9%A2%98.pdf)

### Computer Vision
计算机视觉相关文章（跟广告创意优化有相关性，喜欢该方向的可以读一读）
* [Distinctive Image Features from Scale-Invariant Keypoints.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Computer%20Vision/Distinctive%20Image%20Features%20from%20Scale-Invariant%20Keypoints.pdf)

### Explore and Exploit
探索和利用问题，计算广告中非常经典的问题， 也是容易被大家忽视的问题，其实所有的广告系统都面临如何解决新广告主冷启动的问题，以及在效果不好的情况下如何探索新的优质流量的问题，希望该目录下的几篇文章能搞帮助到你。
* [A Contextual-Bandit Approach to Personalized News Article Recommendation(LinUCB).pdf](https://github.com/wzhe06/Ad-papers/blob/master/Explore%20and%20Exploit/A%20Contextual-Bandit%20Approach%20to%20Personalized%20News%20Article%20Recommendation(LinUCB).pdf)
* [An Empirical Evaluation of Thompson Sampling.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Explore%20and%20Exploit/An%20Empirical%20Evaluation%20of%20Thompson%20Sampling.pdf)
* [Analysis of Thompson Sampling for the Multi-armed Bandit Problem.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Explore%20and%20Exploit/Analysis%20of%20Thompson%20Sampling%20for%20the%20Multi-armed%20Bandit%20Problem.pdf)
* [Finite-time Analysis of the Multiarmed Bandit Problem.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Explore%20and%20Exploit/Finite-time%20Analysis%20of%20the%20Multiarmed%20Bandit%20Problem.pdf)
* [Thompson Sampling PPT.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Explore%20and%20Exploit/Thompson%20Sampling%20PPT.pdf)
* [UCT算法.doc](https://github.com/wzhe06/Ad-papers/blob/master/Explore%20and%20Exploit/UCT%E7%AE%97%E6%B3%95.doc)
* [基于UCT的围棋引擎的研究与实现.doc](https://github.com/wzhe06/Ad-papers/blob/master/Explore%20and%20Exploit/%E5%9F%BA%E4%BA%8EUCT%E7%9A%84%E5%9B%B4%E6%A3%8B%E5%BC%95%E6%93%8E%E7%9A%84%E7%A0%94%E7%A9%B6%E4%B8%8E%E5%AE%9E%E7%8E%B0.doc)
* [对抗搜索、多臂老虎机问题、UCB算法.ppt](https://github.com/wzhe06/Ad-papers/blob/master/Explore%20and%20Exploit/%E5%AF%B9%E6%8A%97%E6%90%9C%E7%B4%A2%E3%80%81%E5%A4%9A%E8%87%82%E8%80%81%E8%99%8E%E6%9C%BA%E9%97%AE%E9%A2%98%E3%80%81UCB%E7%AE%97%E6%B3%95.ppt)

### Factorization Machines
FM因子分解机模型的相关paper，在计算广告领域非常实用的模型
* [FM PPT by CMU.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Factorization%20Machines/FM%20PPT%20by%20CMU.pdf)
* [Factorization Machines Rendle2010.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Factorization%20Machines/Factorization%20Machines%20Rendle2010.pdf)
* [Fast Context-aware Recommendations with Factorization Machines.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Factorization%20Machines/Fast%20Context-aware%20Recommendations%20with%20Factorization%20Machines.pdf)
* [Scaling Factorization Machines to Relational Data.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Factorization%20Machines/Scaling%20Factorization%20Machines%20to%20Relational%20Data.pdf)
* [fastFM- A Library for Factorization Machines.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Factorization%20Machines/fastFM-%20A%20Library%20for%20Factorization%20Machines.pdf)
* [libfm-1.42.manual.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Factorization%20Machines/libfm-1.42.manual.pdf)

### Google Three Papers 
Google三大篇，HDFS，MapReduce，BigTable，奠定大数据基础架构的三篇文章，应该读一读
* [Bigtable A Distributed Storage System for Structured Data.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Google%20Three%20Papers/Bigtable%20A%20Distributed%20Storage%20System%20for%20Structured%20Data.pdf)
* [MapReduce Simplified Data Processing on Large Clusters.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Google%20Three%20Papers/MapReduce%20Simplified%20Data%20Processing%20on%20Large%20Clusters.pdf)
* [The Google File System.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Google%20Three%20Papers/The%20Google%20File%20System.pdf)

### Machine Learning Tutorial 
机器学习方面一些非常实用的学习资料
* [Deep Learning Tutorial.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Machine%20Learning%20Tutorial/Deep%20Learning%20Tutorial.pdf)
* [Rules of Machine Learning- Best Practices for ML Engineering.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Machine%20Learning%20Tutorial/Rules%20of%20Machine%20Learning-%20Best%20Practices%20for%20ML%20Engineering.pdf)
* [关联规则基本算法及其应用.doc](https://github.com/wzhe06/Ad-papers/blob/master/Machine%20Learning%20Tutorial/%E5%85%B3%E8%81%94%E8%A7%84%E5%88%99%E5%9F%BA%E6%9C%AC%E7%AE%97%E6%B3%95%E5%8F%8A%E5%85%B6%E5%BA%94%E7%94%A8.doc)
* [各种回归的概念学习.doc](https://github.com/wzhe06/Ad-papers/blob/master/Machine%20Learning%20Tutorial/%E5%90%84%E7%A7%8D%E5%9B%9E%E5%BD%92%E7%9A%84%E6%A6%82%E5%BF%B5%E5%AD%A6%E4%B9%A0.doc)
* [广义线性模型.ppt](https://github.com/wzhe06/Ad-papers/blob/master/Machine%20Learning%20Tutorial/%E5%B9%BF%E4%B9%89%E7%BA%BF%E6%80%A7%E6%A8%A1%E5%9E%8B.ppt)
* [机器学习总图.jpg](https://github.com/wzhe06/Ad-papers/blob/master/Machine%20Learning%20Tutorial/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E6%80%BB%E5%9B%BE.jpg)
* [贝叶斯统计学(PPT).pdf](https://github.com/wzhe06/Ad-papers/blob/master/Machine%20Learning%20Tutorial/%E8%B4%9D%E5%8F%B6%E6%96%AF%E7%BB%9F%E8%AE%A1%E5%AD%A6(PPT).pdf)

### Optimization Method 
Online Optimization，Parallel SGD，FTRL等优化方法，很实用的一些文章
* [A Survey on Algorithms of the Regularized Convex Optimization Problem.pptx](https://github.com/wzhe06/Ad-papers/blob/master/Optimization%20Method/A%20Survey%20on%20Algorithms%20of%20the%20Regularized%20Convex%20Optimization%20Problem.pptx)
* [Follow-the-Regularized-Leader and Mirror Descent- Equivalence Theorems and L1 Regularization.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Optimization%20Method/Follow-the-Regularized-Leader%20and%20Mirror%20Descent-%20Equivalence%20Theorems%20and%20L1%20Regularization.pdf)
* [Hogwild A Lock-Free Approach to Parallelizing Stochastic Gradient Descent.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Optimization%20Method/Hogwild%20A%20Lock-Free%20Approach%20to%20Parallelizing%20Stochastic%20Gradient%20Descent.pdf)
* [Parallelized Stochastic Gradient Descent.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Optimization%20Method/Parallelized%20Stochastic%20Gradient%20Descent.pdf)
* [在线最优化求解(Online Optimization)-冯扬.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Optimization%20Method/%E5%9C%A8%E7%BA%BF%E6%9C%80%E4%BC%98%E5%8C%96%E6%B1%82%E8%A7%A3(Online%20Optimization)-%E5%86%AF%E6%89%AC.pdf)
* [非线性规划.doc](https://github.com/wzhe06/Ad-papers/blob/master/Optimization%20Method/%E9%9D%9E%E7%BA%BF%E6%80%A7%E8%A7%84%E5%88%92.doc)

### Recommendation
推荐系统相关文章，研究不多，欢迎补充
* [基于BPR-MF算法的推荐系统设计.docx](https://github.com/wzhe06/Ad-papers/blob/master/Recommendation/%E5%9F%BA%E4%BA%8EBPR-MF%E7%AE%97%E6%B3%95%E7%9A%84%E6%8E%A8%E8%8D%90%E7%B3%BB%E7%BB%9F%E8%AE%BE%E8%AE%A1.docx)
* [微博推荐策略平台Eros.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Recommendation/%E5%BE%AE%E5%8D%9A%E6%8E%A8%E8%8D%90%E7%AD%96%E7%95%A5%E5%B9%B3%E5%8F%B0Eros.pdf)

### Topic Model
话题模型相关文章，PLSA，LDA，进行广告Context特征提取，创意优化肯定会用到Topic Model
* [Dirichlet Distribution, Dirichlet Process and Dirichlet Process Mixture(PPT).pdf](https://github.com/wzhe06/Ad-papers/blob/master/Topic%20Model/Dirichlet%20Distribution%2C%20Dirichlet%20Process%20and%20Dirichlet%20Process%20Mixture(PPT).pdf)
* [LDA数学八卦.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Topic%20Model/LDA%E6%95%B0%E5%AD%A6%E5%85%AB%E5%8D%A6.pdf)
* [Parameter estimation for text analysis.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Topic%20Model/Parameter%20estimation%20for%20text%20analysis.pdf)
* [概率语言模型及其变形系列.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Topic%20Model/%E6%A6%82%E7%8E%87%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E5%8F%8A%E5%85%B6%E5%8F%98%E5%BD%A2%E7%B3%BB%E5%88%97.pdf)
* [理解共轭先验.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Topic%20Model/%E7%90%86%E8%A7%A3%E5%85%B1%E8%BD%AD%E5%85%88%E9%AA%8C.pdf)

### Transfer Learning
迁移学习相关文章，计算广告中经常遇到新广告冷启动的问题，利用迁移学习能较好解决该问题
* [A Survey on Transfer Learning.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Transfer%20Learning/A%20Survey%20on%20Transfer%20Learning.pdf)
* [Scalable Hands-Free Transfer Learning for Online Advertising.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Transfer%20Learning/Scalable%20Hands-Free%20Transfer%20Learning%20for%20Online%20Advertising.pdf)

### Tree Model 
树模型和基于树模型的boosting模型，树模型的效果在大部分问题上非常好，在CTR，CVR模型以及特征工程方面的应用非常广，值得深入研究
* [Classification and Regression Trees.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Tree%20Model/Classification%20and%20Regression%20Trees.pdf)
* [Classification and Regression Trees.ppt](https://github.com/wzhe06/Ad-papers/blob/master/Tree%20Model/Classification%20and%20Regression%20Trees.ppt)
* [Greedy Function Approximation A Gradient Boosting Machine.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Tree%20Model/Greedy%20Function%20Approximation%20A%20Gradient%20Boosting%20Machine.pdf)
* [Introduction to Boosted Trees.pdf](https://github.com/wzhe06/Ad-papers/blob/master/Tree%20Model/Introduction%20to%20Boosted%20Trees.pdf)
