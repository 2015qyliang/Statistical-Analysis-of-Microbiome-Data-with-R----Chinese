# 第五章：微生物组数据的效力与样本量大小

本章内容简介：

- 5.1 假设检验与效力分析
- 5.2 基于T-检验差异的测试的效力分析
- 5.3 基于ANOVA检验多组间(>2)差异测试的效力分析
- 5.4 组间比较分类学数据的效力分析
- 5.5 基于Dirichlet多项式模型比较组间所有分类信息的频率
- 5.6 本章小结

## 5.1 假设检验与效力分析

### 5.1.1 假设检验

#### 5.1.1.1 统计分析的要素

#### 5.1.1.2 检验统计假设的步骤

#### 5.1.1.3 微生物组数据的假设检验

### 5.1.2 效力分析与样本量计算

#### 5.1.2.1 效力分析和样本量计算的重要性

#### 5.1.2.2 效力分析

## 5.2 基于T-检验差异的测试的效力分析

### 5.2.1 连续结果的效力公示

### 5.2.2 ALS研究中的多样性数据

### 5.2.3 使用power.t.test()计算Power和样本Size

## 5.3 基于ANOVA检验多组间(>2)差异测试的效力分析

### 5.3.1 one-way ANOVA的基本概念

### 5.3.2 使用pwr.avova.test()计算Power和样本Size

## 5.4 组间比较分类学数据的效力分析

### 5.4.1 比较比例的假设和基本Power、样本Size公式

### 5.4.2 使用power.prop.test()进行效力分析

### 5.4.3 使用卡方检验和Fisher检验进行效力分析

#### 5.4.3.1 进行比较比例的卡方检验的理论概念

#### 5.4.3.2 使用pwr.chisq.test()实现效力分析

#### 5.4.3.3 使用power.fisher.test()和power.exact.test()实现效力分析

## 5.5 基于Dirichlet多项式模型比较组间所有分类信息的频率

### 5.5.1 多元假设检验和Dirichlet多项式模型

### 5.5.2 使用Dirichlet多项式模型计算Power和样本Size

### 5.5.3 使用HMP包计算Power和Size

#### 5.5.3.1 准备HMP包计算使用的数据集

#### 5.5.3.2 使用分类学组成数据计算Power和Size

#### 5.5.3.3 使用秩丰度分布数据计算Power和Size

### 5.5.4 使用HMP包计算effect size

## 5.6 本章小结

## 参考文献

- Boyu, Ren, Sergio, Bacallado, et al. 2017. Bayesian nonparametric ordination for the analysis of microbial communities. arXiv:1601.05156 [stat.ME].
- Cohen, J. 1988. Statistical power analysis for the behavioral sciences. Hillsdale, New Jersey: Lawrence Erlbaum Associates.
- Costea, P.I., G. Zeller, et al. 2017. Towards standards for human fecal sample processing in metagenomic studies. Nat Biotech. Advance online publication.
- Graham, J.W., P.E. Cumsille, et al. 2003. Methods for handling missing data. Handbook of Psychology, vol. 2, ed. J.A. Schinka and W.F. Velicer, 87–114. New York: Wiley.
- Hart, M.M., A. Kristin, et al. 2015. Navigating the labyrinth: A guide to sequence-based, community ecology of arbuscular mycorrhizal fungi. New Phytologist 207 (1): 235–247.
- Holmes I, Harris K, et al. 2012 Dirichlet multinomial mixtures: Generative models for microbial metagenomics. PLoS One 7: e30126.
- Kelly, B.J., R. Gross, et al. 2015. Power and sample-size estimation for microbiome studies using pairwise distances and PERMANOVA. Bioinformatics 31 (15): 2461–2468.
- Koehler, K.J., and J.R. Wilson. 1986. Chi-square tests for comparing vectors of proportions for several cluster samples. Communications in Statistics—Theory and Methods 15 (10): 2977– 2990.
- La Rosa, P.S., J.P. Brooks, et al. 2012. Hypothesis testing and power calculations for taxonomic-based human microbiome data. PLoS ONE 7 (12): e52078.
- La Rosa, P.S., Y. Zhou, et al. 2015. Hypothesis testing of metagenomic data. In Metagenomics for microbiology, ed. J. Izard and M.C. Rivera, 81–96. Waltham, MA, USA: Academic Press.
- Mattiello, F., B. Verbist, et al. 2016. A web application for sample size and power calculation in case-control microbiome studies. Bioinformatics 32 (13): 2038–2040.
- Neal, S., Grantham, Brian J. Reich, et al. (2017). MIMIX: A Bayesian mixed-effects model for microbiome data from designed experiments. arXiv:1703.07747 [stat.ME].
- Tvedebrink, T. 2010. Overdispersion in allelic counts and h-correction in forensic genetics. Theoretical Population Biology 78 (3): 200–210.
- Wu, G.D., J. Chen, et al. (2011). Linking long-term dietary patterns with gut microbial enterotypes. Science 334.
- Zhang, Y.-G., S. Wu, et al. 2017. Target intestinal microbiota to alleviate disease progression in amyotrophic lateral sclerosis. Clinical Therapeutics 39 (2): 322–336.
- Zhernakova, A., A. Kurilshikov, et al. 2016. Population-based metagenomics analysis reveals markers for gut microbiome composition and diversity. Science 352 (6285): 565–569.
