# Uncertainty Calibration
Calibration techniques are increasingly applied in the fields of computation advertising，medical diagnosis and meteorological forecasting etc. This is a collection of research and application papers of (uncertainty) calibration techniques. These works are summarized from the public website. If any authors do not want their paper to be listed here, please feel free to contact me（siguang.hsg@alibaba-inc.com）.

## Papers
### Parametric Method
- **Platt scaling**: [Probabilistic outputs for support vector machines and comparisons to regularized likelihood methods](https://home.cs.colorado.edu/~mozer/Teaching/syllabi/6622/papers/Platt1999.pdf)[J]. by Platt J.  Advances in large margin classifiers, 1999.
- **Temperature scaling**: [On calibration of modern neural networks](http://proceedings.mlr.press/v70/guo17a.html). by Chuan Guo et al. ICML, 2017. 
- **Attended temperature scaling**: [Attended temperature scaling: a practical approach for calibrating deep neural networks](https://arxiv.org/abs/1810.11586). by AzadehSadatMozafari et al. arXiv , 2018.
- **Dirichlet scaling**: [Obtaining well-calibrated multiclass probabilities with Dirichlet calibration](https://arxiv.org/abs/1910.12656). by Meelis Kull et al. arXiv, 2019.
- **Beta calibration**: [A well-founded and easily implemented improvement on logistic calibration for binary classifiers](http://proceedings.mlr.press/v54/kull17a.html). by Meelis Kull et al. In Artificial Intelligence and Statistics, 2017.


### Non-parametric Method
- **Hisogram Binning**: [Obtaining calibrated probability estimates from decision trees and naive bayesian classifiers](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.29.3039&rep=rep1&type=pdf). by Bianca Zadrozny et al. ICML, 2001.
- **Bayesian Binning**: [Obtaining well calibrated probabilities using bayesian binning](https://ojs.aaai.org/index.php/AAAI/article/view/9602). by MahdiPakdamanNaeini et al. AAAI, 2015.

- **Isotonic Regression**: [Transforming classifier scores into accurate multiclass probability estimates](https://dl.acm.org/doi/abs/10.1145/775047.775151). by Bianca Zadrozny et al. KDD, 2002.


### Semi-parametric Method
- **Scaling-binning**:[Verified Uncertainty Calibration](https://arxiv.org/abs/1909.10155). by Ananya Kumar et al. NeurIPS, 2020.
- **Mix-n-Match**:[Ensemble and Compositional Methods for Uncertainty Calibration in Deep Learning](http://proceedings.mlr.press/v119/zhang20k.html). by Jize Zhang et al. ICML 2020.
- **SIR**:[Calibrating User Response Predictions in Online Advertising](). by Chao Deng et al. PKKDD, 2020.

### Calibration Theory
- [Binary Classifier Calibration: Non-parametric approach](https://arxiv.org/abs/1401.3390). by Mahdi Pakdaman Naeini et al. arXiv 2014.
- [Verified Uncertainty Calibration](https://arxiv.org/abs/1909.10155). by Ananya Kumar et al. NeurIPS, 2020.
- [Distribution-free binary classification: prediction sets, confidence intervals and calibration](https://arxiv.org/abs/2006.10564). by Chirag Gupta et al. NeurIPS, 2020.
- [Ensemble and Compositional Methods for Uncertainty Calibration in Deep Learning](http://proceedings.mlr.press/v119/zhang20k.html). by Jize Zhang et al. ICML 2020.
- [Individual Calibration with Randomized Forecasting](http://proceedings.mlr.press/v119/zhao20e.html). by Shengjia Zhao et al. ICML, 2020.
- [Post-hoc Calibration of Neural Networks](https://arxiv.org/abs/2006.12807). by Amir Rahimi et al. arXiv 2020.(Google)
- [Non-Parametric Calibration for Classification](http://proceedings.mlr.press/v108/wenger20a.html). by Jonathan Wenger et al. AISTATS 2020.

### Applications
#### Advertising
- Field-aware Calibration: [A Simple and Empirically Strong Method for Reliable Probabilistic Predictions](https://dl.acm.org/doi/abs/10.1145/3366423.3380154). by Feiyang Pan et al. WWW 2020 (Tencent).
- [Calibrating User Response Predictions in Online Advertising](). by Chao Deng et al. PKKDD, 2020 (Alibaba).

### Calibration Metrics
- [Mitigating bias in calibration error estimation](https://arxiv.org/abs/2012.08668) by Rebecca Roelofs et al. arXiv 2020.(Google)
- [Measuring Calibration in Deep Learning](https://openaccess.thecvf.com/content_CVPRW_2019/papers/Uncertainty%20and%20Robustness%20in%20Deep%20Visual%20Learning/Nixon_Measuring_Calibration_in_Deep_Learning_CVPRW_2019_paper.pdf) by Jeremy Nixon et al. arXiv 2020.(Google)
- [Calibration of Neural Networks using Splines](https://arxiv.org/abs/2006.12800) by Kartik Gupta et al. arXiv 2020.(Google)

## Datasets and Benchmarking
- [Alibaba Pctr Calibration Data Set](https://tianchi.aliyun.com/dataset/dataDetail?dataId=40792) by Chao Deng. 2019
- [Alibaba Pcvr Calibration Data Set](https://tianchi.aliyun.com/dataset/dataDetail?dataId=40796) by Chao Deng. 2019

## Other Links
- Research Track
  - ICML: Trustworthy Machine Learning (accountability, causality, fairness, privacy, robustness, etc.)
    - [ICML 2021 Accepted List](https://icml.cc/Conferences/2021/AcceptedPapersInitial) 
