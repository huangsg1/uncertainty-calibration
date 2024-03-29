# Uncertainty Calibration（预估校准技术）
> Calibration techniques are increasingly applied in the fields of computation advertising，medical diagnosis and meteorological forecasting etc. This is a collection of research and application papers of (uncertainty) calibration techniques. These works are summarized from the public website. If any authors do not want their paper to be listed here, please feel free to contact me（email:hsg01993@gmail.com, Wechat:coder_hh）.

## 1. Papers
### Post-hoc Calibrator（后处理方法）
#### Parametric Method（参数化方法）
- **Platt scaling**: [Probabilistic outputs for support vector machines and comparisons to regularized likelihood methods](https://home.cs.colorado.edu/~mozer/Teaching/syllabi/6622/papers/Platt1999.pdf)[J]. by Platt J.  Advances in large margin classifiers, 1999.
- **Temperature scaling**: [On calibration of modern neural networks](http://proceedings.mlr.press/v70/guo17a.html). by Chuan Guo et al. ICML, 2017. 
- **Beta calibration**: [A well-founded and easily implemented improvement on logistic calibration for binary classifiers](http://proceedings.mlr.press/v54/kull17a.html). by Meelis Kull et al. In Artificial Intelligence and Statistics, 2017.
- **Attended temperature scaling**: [Attended temperature scaling: a practical approach for calibrating deep neural networks](https://arxiv.org/abs/1810.11586). by AzadehSadatMozafari et al. arXiv , 2018.
- **Dirichlet scaling**: [Obtaining well-calibrated multiclass probabilities with Dirichlet calibration](https://arxiv.org/abs/1910.12656). by Meelis Kull et al. arXiv, 2019.



#### Non-parametric Method（非参数化方法）
- **Hisogram Binning**: [Obtaining calibrated probability estimates from decision trees and naive bayesian classifiers](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.29.3039&rep=rep1&type=pdf). by Bianca Zadrozny et al. ICML, 2001.
- **Isotonic Regression**: [Transforming classifier scores into accurate multiclass probability estimates](https://dl.acm.org/doi/abs/10.1145/775047.775151). by Bianca Zadrozny et al. KDD, 2002.
- **Bayesian Binning**: [Obtaining well calibrated probabilities using bayesian binning](https://ojs.aaai.org/index.php/AAAI/article/view/9602). by MahdiPakdamanNaeini et al. AAAI, 2015.
- [Distribution-free calibration guarantees for histogram binning without sample splitting](https://arxiv.org/pdf/2105.04656.pdf) by Chirag Gupta et al. ICML, 2021.


#### Hybrid Method（参数&非参数混合方法）
- **Scaling-binning**:[Verified Uncertainty Calibration](https://arxiv.org/abs/1909.10155). by Ananya Kumar et al. NeurIPS, 2020.
- **Mix-n-Match**:[Ensemble and Compositional Methods for Uncertainty Calibration in Deep Learning](http://proceedings.mlr.press/v119/zhang20k.html). by Jize Zhang et al. ICML 2020.
- **SIR**:[Calibrating User Response Predictions in Online Advertising](http://link.zhihu.com/?target=https%3A//www.semanticscholar.org/paper/Calibrating-User-Response-Predictions-in-Online-Deng-Wang/678d93dba3003dc30fcfa2e29c93b009834dcd0a). by Chao Deng et al. PKKDD, 2020. **(Our work)**
- **MBCT**:[Tree-Based Feature-Aware Binning for Individual Uncertainty Calibration](https://arxiv.org/abs/2202.04348). by Siguang Huang et al. WWW, 2022. **(Our work)**

### Calibrated Predictor（与模型直接结合的方法）
- Field-aware Calibration: [A Simple and Empirically Strong Method for Reliable Probabilistic Predictions](https://dl.acm.org/doi/abs/10.1145/3366423.3380154). by Feiyang Pan et al. WWW 2020 (Tencent).
- [Posterior Probability Matters: Doubly-Adaptive Calibration for Neural Predictions in Online Advertising](https://arxiv.org/abs/2205.07295). by Penghui Wei et al. SIGIR 2022. (Alibaba)
  - [中文链接](https://zhuanlan.zhihu.com/p/520272718)
- [Joint Optimization of Ranking and Calibration with Contextualized Hybrid Model](https://arxiv.org/pdf/2208.06164.pdf). by Xiang-Rong Sheng et al. KDD 2023. (Alibaba)
  - [中文链接](https://zhuanlan.zhihu.com/p/638414676)    

### Calibration Theory（校准理论分析）
- [Binary Classifier Calibration: Non-parametric approach](https://arxiv.org/abs/1401.3390). by Mahdi Pakdaman Naeini et al. arXiv 2014.
- [Verified Uncertainty Calibration](https://arxiv.org/abs/1909.10155). by Ananya Kumar et al. NeurIPS, 2020.
- [Distribution-free binary classification: prediction sets, confidence intervals and calibration](https://arxiv.org/abs/2006.10564). by Chirag Gupta et al. NeurIPS, 2020.
- [Ensemble and Compositional Methods for Uncertainty Calibration in Deep Learning](http://proceedings.mlr.press/v119/zhang20k.html). by Jize Zhang et al. ICML 2020.
- [Individual Calibration with Randomized Forecasting](http://proceedings.mlr.press/v119/zhao20e.html). by Shengjia Zhao et al. ICML, 2020.
- [Post-hoc Calibration of Neural Networks](https://arxiv.org/abs/2006.12807). by Amir Rahimi et al. arXiv 2020.(Google)
- [Non-Parametric Calibration for Classification](http://proceedings.mlr.press/v108/wenger20a.html). by Jonathan Wenger et al. AISTATS 2020.
- [Don’t Just Blame Over-parametrization for Over-confidence: Theoretical Analysis of Calibration in Binary Classification](https://arxiv.org/pdf/2102.07856.pdf) by Yu Bai et al. ICML, 2021.
- [Distribution-free calibration guarantees for histogram binning without sample splitting](https://arxiv.org/pdf/2105.04656.pdf) by Chirag Gupta et al. ICML, 2021.
- [Meta-Cal: Well-controlled Post-hoc Calibration by Ranking](https://arxiv.org/pdf/2105.04290.pdf) by Xingchen Ma et al. ICML, 2021.

## 2. Applications（校准应用）
### Advertising
- Field-aware Calibration: [A Simple and Empirically Strong Method for Reliable Probabilistic Predictions](https://dl.acm.org/doi/abs/10.1145/3366423.3380154). by Feiyang Pan et al. WWW 2020 (Tencent).
- [Calibrating User Response Predictions in Online Advertising](http://link.zhihu.com/?target=https%3A//www.semanticscholar.org/paper/Calibrating-User-Response-Predictions-in-Online-Deng-Wang/678d93dba3003dc30fcfa2e29c93b009834dcd0a). by Chao Deng et al. PKKDD, 2020 (Alibaba).
- **MBCT**:[Tree-Based Feature-Aware Binning for Individual Uncertainty Calibration](https://arxiv.org/abs/2202.04348). by Siguang Huang et al. WWW, 2022. (Alibaba)
### 

## 3. Calibration Metrics（评价方法）
- [Mitigating bias in calibration error estimation](https://arxiv.org/abs/2012.08668) by Rebecca Roelofs et al. arXiv 2020.(Google)
- [Measuring Calibration in Deep Learning](https://openaccess.thecvf.com/content_CVPRW_2019/papers/Uncertainty%20and%20Robustness%20in%20Deep%20Visual%20Learning/Nixon_Measuring_Calibration_in_Deep_Learning_CVPRW_2019_paper.pdf) by Jeremy Nixon et al. arXiv 2020.(Google)
- [Calibration of Neural Networks using Splines](https://arxiv.org/abs/2006.12800) by Kartik Gupta et al. arXiv 2020.(Google)

## 4. Datasets and Benchmarking（公开数据集）
- [Alibaba Group's Dataset for Feature-Aware Calibration](https://github.com/huangsg1/Tree-Based-Feature-Aware-Binning-for-Individual-Uncertainty-Calibration) by Siguang Huang. 2022
- [Alibaba Pctr Calibration Dataset](https://tianchi.aliyun.com/dataset/dataDetail?dataId=40792) by Chao Deng. 2019
- [Alibaba Pcvr Calibration Dataset](https://tianchi.aliyun.com/dataset/dataDetail?dataId=40796) by Chao Deng. 2019

## 5. Other Links
- Research Track
  - ICML: Trustworthy Machine Learning (accountability, causality, fairness, privacy, robustness, etc.)

 
---
## 6. 中文材料
- [阿里巴巴展示广告校准技术演进之路](https://zhuanlan.zhihu.com/p/398235467)
- [MBCT：基于树模型的特征可感知的个性化校准方法](https://zhuanlan.zhihu.com/p/516779767)
- [AdaCalib: 后验引导的特征自适应预估校准](https://zhuanlan.zhihu.com/p/520272718)
- [贝叶斯分层校准](https://zhuanlan.zhihu.com/p/614214235)
- [算法实践_专栏](https://www.zhihu.com/column/c_1514240377606926336)
