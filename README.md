# CDMLC
Repository for the paper "Community Detection for Multi-Label Classification" published in the journal "Applied Soft Computing"

Please, for now, check this [repository](https://github.com/cissagatto/Bracis2023)

## SOURCE CODE

*Step 1: Pre-processing*
- [Code](https://github.com/cissagatto/CrossValidationMultiLabel) to create the 10-Fold Cross Validation for each dataset. You can download our data splits [here](https://drive.google.com/drive/folders/16t1rRptgULrM20IFItC_HlPJrmFZbIzH?usp=sharing). 

*Step 2: Modeling Label Correlations*
- [SimilaritiesMultiLabel](https://github.com/cissagatto/SimilaritiesMultiLabel) to compute similarities measures {OR [https://github.com/cissagatto/MultiLabelSimilaritiesMeasures];}
- [GraphMultiLabel](https://github.com/cissagatto/GraphMultiLabel) to build the label co-occurrence graphs.

*Step 3: Applying Communities Detection Methods*
- [GeneratePartitionsCommunities](https://github.com/cissagatto/Generate-Partitions-Communities) to generate partitions from the communities.

*Steps 4, 5, and 6: Build, validate, chose, and test hybrid partitions*
- [Code](https://github.com/cissagatto/TCP-KNN-H-Clus) for Sparsification with KNN + Hierarchical Methods 
- [Code](https://github.com/cissagatto/TCP-KNN-NH-Clus) for Sparsification with KNN + Non Hierarchical Methods
- [Code](https://github.com/cissagatto/TCP-TR-H-Clus) for Sparsification with Threshold + Hierarchical Methods
- [Code](https://github.com/cissagatto/TCP-TR-NH-Clus) for Sparsification with Threshold + Non Hierarchical Methods

*Code for Global, Local, and Random Partitions*
- [Global](https://github.com/cissagatto/Global-Partitions)
- [Local](https://github.com/cissagatto/Local-Partitions)
- [Generate Random Graphs](https://github.com/cissagatto/Generate-Random-Communities)
- [Test Random Graph + Hierarchical Methods](https://github.com/cissagatto/TCP-Random-H-Clus)
- [Test Random Graph + Non Hierarchical Methods](https://github.com/cissagatto/TCP-Random-NH-Clus)
