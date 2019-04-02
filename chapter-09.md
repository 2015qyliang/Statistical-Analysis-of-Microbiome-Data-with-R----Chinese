# 第九章：多元变量群落数据分析

本章内容简介：

- 9.1 Hypothesis Testing Among Groups Using Permutational Multivariate Analysis of Variance (PERMANOVA)
- 9.2 Hypothesis Tests Among Group-Differences Using Mantel Test (MANTEL)
- 9.3 Hypothesis Tests Among-Group Differences Using ANOSIM
- 9.4 Hypothesis Tests of Multi-response Permutation Procedures (MRPP)
- 9.5 Compare Microbiome Communities Using the GUniFrac Package
- 9.6 本章小结与讨论

## 9.1 Hypothesis Testing Among Groups Using Permutational Multivariate Analysis of Variance (PERMANOVA)

### 9.1.1 Introduction of PERMANOVA

### 9.1.2 Implementing PERMANOVA Using Vegan Package

### 9.1.3 Implementing Pairwise Permutational MANOVA Using RVAideMemoire Package

### 9.1.4 Test Group Homogeneities Using the Function betadisper()

## 9.2 Hypothesis Tests Among Group-Differences Using Mantel Test (MANTEL)

### 9.2.1 Introduction of Mantel and Partial Mantel Tests for Dissimilarity Matrices

### 9.2.2 Illustrating Mantel Test Using Vegan Package

#### 9.2.2.1 Test the Correlation of Two Community Distance Matrices

#### 9.2.2.2 Test the Correlation of a Community Matrix and a Design Matrix

#### 9.2.2.3 Partial Mantel Test the Correlation of Two Distance Matrices Controlling the Third Matrix

## 9.3 Hypothesis Tests Among-Group Differences Using ANOSIM

### 9.3.1 Introduction of Analysis of Similarity (ANOSIM)

### 9.3.2 Illustrating Analysis of Similarity (ANOSIM) Using Vegan Package

## 9.4 Hypothesis Tests of Multi-response Permutation Procedures (MRPP)

### 9.4.1 Introduction of MRPP

### 9.4.2 Illustrating MRPP Using Vegan Package

## 9.5 Compare Microbiome Communities Using the GUniFrac Package

### 9.5.1 Introduction to UniFrac, Weighted UniFrac and Generalized UniFrac Distance Metrics

### 9.5.2 Breast Milk Data Set

### 9.5.3 Comparing Microbiome Communities Using the GUniFrac Package

## 9.6 本章小结与讨论

## 参考文献

- Anderson, M.J. 2001. A new method for non-parametric multivariate analysis of variance. Austral Ecology 26: 32–46.
- Anderson, M.J., T.O. Crist, et al. 2011. Navigating the multiple meanings of beta diversity: A roadmap for the practicing ecologist. Ecology Letters 14 (1): 19–28.
- Benjamini, Y., and Y. Hochberg. 1995. Controlling the false discovery rate: A practical and powerful approach to multiple testing. Journal of the Royal Statistical Society Series B 57: 289–300.
- Benjamini, Y., and D. Yekutieli. 2001. The control of the false discovery rate in multiple testing under dependency. Annals of Statistics 29: 1165–1188.
- Bonferroni, C.E. 1936. Teoria statistica delle classi e calcolo delle probabilitàby. Pubblicazioni del R Istituto Superiore di Scienze Economiche e Commerciali di Firenze 8: 3–62 Key: citeulike:1778138.
- Carcer, D.A., S.E. Denman, et al. 2011. Evaluation of subsampling-based normalization strategies for tagged high-throughput sequencing data sets from gut microbiomes. Applied and Environment Microbiology 77 (24): 8795–8798.
- Chang, Q., Y. Luan, et al. 2011. Variance adjusted weighted UniFrac: A powerful beta diversity measure for comparing communities based on phylogeny. BMC Bioinformatics 12 (1): 118.
- Chen, J. 2012. GUniFrac: Generalized UniFrac distances. R package version 1.0. https://CRAN.R- project.org/package=GUniFrac.
- Chen, J., K. Bittinger, et al. 2012. Associating microbiome composition with environmental covariates using generalized UniFrac distances. Bioinformatics 28 (16): 2106–2113.
- Clarke, K.R. 1993. Non-parametric multivariate analysis of changes in community structure. Australian Journal of Ecology 18: 117–143.
- Hochberg, Y. 1988. A sharper Bonferroni procedure for multiple tests of signiﬁcance. Biometrika 75: 800–803.
- Holm, S. 1979. A simple sequentially rejective multiple test procedure. Scandinavian Journal of Statistics 6: 65–70.
- Hommel, G. 1988. A stagewise rejective multiple test procedure based on a modiﬁed Bonferroni test. Biometrika 75: 383–386.
- Jin, D., S. Wu, et al. 2015. Lack of Vitamin D receptor causes dysbiosis and changes the functions of the murine intestinal microbiome. Clinical Therapeutics 37 (5): 996–1009, e1007.
- Laliberte, E. 2008. Analyzing or explaining beta diversity? comment. Ecology 89 (11): 3232–3237.
- Legendre, P. 2007. Studying beta diversity: Ecological variation partitioning by multiple regression and canonical analysis. Journal of Plant Ecology 1 (1): 3–8.
- Legendre, P., and L. Legendre. 2012. Numerical ecology. Amsterdam: Elsevier Science BV. Legendre, P., and M.J. Fortin. 1989. Spatial pattern and ecological analysis. Vegetatio 80 (2):107–138.
- Legendre, P., D. Borcard, et al. 2005. Analyzing beta diversity: Partitioning the spatial variation of community composition data. Ecological Monographs 75 (4): 435–450.
- Legendre, P., D. Borcard, et al. 2008. Analyzing or explaining beta diversity? comment. Ecology 89 (11): 3238–3244.
- Linnenbrink, M., J. Wang, et al. 2013. The role of biogeography in shaping diversity of the intestinal microbiota in house mice. Molecular Ecology 22 (7): 1904–1916.
- Lozupone, C., and R. Knight. 2005. UniFrac: A new phylogenetic method for comparing microbial communities. Applied and Environmental Microbiology 71 (12): 8228–8235.
- Lozupone, C.A., M. Hamady, et al. 2007. Quantitative and qualitative beta diversity measures lead to different insights into factors that structure microbial communities. Applied and Environment Microbiology 73 (5): 1576–1585.
- Mantel, N. 1967. The detection of disease clustering and a generalized regression approach.
- Cancer Research 27: 209–220.
- Mantel, N., and R.S. Valand. 1970. A technique of nonparametric multivariate analysis.
- Biometrics 26 (3): 547–558.
- McArdle, B.H., and M.J. Anderson. 2001. Fitting multivariate models to community data: A comment on distance-based redundancy analysis. Ecology 82 (1): 290–297.
- Mielke, P.W. 1984. Meteorological applications of permutation techniques based on distance functions. In Handbook of statistics, vol. 4, ed. P.R. Krishnaiah and P.K. Sen, 813–830. Amsterdam, North-Holland: Elsevier Science Publishers.
- Mielke Jr., P.W. 1991. The application of multivariate permutation methods based on distance functions in the earth sciences. Earth-Science Reviews 31: 55–71.
- Oksanen, J., F. Guillaume Blanchet, et al. 2016. Vegan: Community ecology package. R package version 2.4-1. http://CRAN.R-project.org/package=vegan.
- Pélissier, R., P. Couteron, et al. 2008. Analyzing or explaining beta diversity? comment. Ecology 89 (11): 3227–3232.
- Smouse, P.E., J.C. Long, et al. 1986. Multiple regression and correlation extensions of the mantel test of matrix correspondence. Systematic Zoology 35 (4): 627–632.
- Tuomisto, H., and K. Ruokolainen. 2006. Analyzing or explaining beta diversity? Understanding the targets of different methods of analysis. Ecology 87: 2697–2708.
- Tuomisto, H., and K. Ruokolainen. 2008. Analyzing or explaining beta diversity: Reply. Ecology 89: 3244–3256.
- Urbaniak, C., M. Angelini, et al. 2016. Human milk microbiota proﬁles in relation to birthing method, gestation and infant gender. Microbiome 4 (1): 1.
- Wang, J., L.B. Thingholm, et al. 2016. Genome-wide association analysis identiﬁes variation in vitamin D receptor and other host factors influencing the gut microbiota. Nature Genetics 48 (11): 1396–1406.
- Warton, D.I., S.T. Wright, et al. 2012. Distance-based multivariate analyses confound location and dispersion effects. Methods in Ecology and Evolution 3 (1): 89–101.
- Wong, R.G., J.R. Wu, et al. 2016. Expanding the UniFrac toolbox. PLoS ONE 11 (9): e0161196.
