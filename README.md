# PFA: Pattern fusion analysis

This is a backup repository of matlab package for pattern fusion analysis (PFA).

Motivation: Integrating different omics profiles is a challenging task, which provides a comprehensive way to understand complex diseases in a multi-view manner. One key for such an integration is to extract intrinsic patterns in concordance with data structures, so as to discover consistent information across various data types even with noise pollution. Thus, we proposed a novel framework called 'pattern fusion analysis' (PFA), which performs automated information alignment and bias correction, to fuse local sample-patterns (e.g. from each data type) into a global sample-pattern corresponding to phenotypes (e.g. across most data types). In particular, PFA can identify significant sample-patterns from different omics profiles by optimally adjusting the effects of each data type to the patterns, thereby alleviating the problems to process different platforms and different reliability levels of heterogeneous data.

Results: To validate the effectiveness of our method, we first tested PFA on various synthetic datasets, and found that PFA can not only capture the intrinsic sample clustering structures from the multi-omics data in contrast to the state-of-the-art methods, such as iClusterPlus, SNF and moCluster, but also provide an automatic weight-scheme to measure the corresponding contributions by data types or even samples. In addition, the computational results show that PFA can reveal shared and complementary sample-patterns across data types with distinct signal-to-noise ratios in Cancer Cell Line Encyclopedia (CCLE) datasets, and outperforms over other works at identifying clinically distinct cancer subtypes in The Cancer Genome Atlas (TCGA) datasets.

# Reference:
Shi Q, Zhang C, Peng M, Yu X, Zeng T, Liu J, Chen L. Pattern fusion analysis by adaptive alignment of multiple heterogeneous omics data. Bioinformatics. 2017 Sep 1;33(17):2706-2714. doi: 10.1093/bioinformatics/btx176. PMID: 28520848.

Code issues can contact: Chuanchao Zhang (chuanchaozhang@ucas.ac.cn, chaozhangchuan@163.com); or Tao Zeng (zengtao@sibs.ac.cn, zeng_tao@gzlab.ac.cn)
