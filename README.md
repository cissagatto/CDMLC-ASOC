# CDMLC
Repository for the paper "Community Detection for Multi-Label Classification" published in the journal "Applied Soft Computing"

Previous work in wich this on is based and extended [repository](https://github.com/cissagatto/Bracis2023)

## SOURCE CODE

*Step 1: Pre-processing*
- [Code](https://github.com/cissagatto/CrossValidationMultiLabel) to create the 10-Fold Cross Validation for each dataset. You can download our data splits [here](https://drive.google.com/drive/folders/16t1rRptgULrM20IFItC_HlPJrmFZbIzH?usp=sharing). 

*Step 2: Modeling Label Correlations*
- [SimilaritiesMultiLabel](https://github.com/cissagatto/SimilaritiesMultiLabel) to compute similarities measures
- [GraphMultiLabel](https://github.com/cissagatto/GraphMultiLabel) to build the label co-occurrence graphs.

*Step 3: Applying Communities Detection Methods*
- [GeneratePartitionsCommunities](https://github.com/cissagatto/Generate-Partitions-Communities) to generate partitions from the communities.

*Steps 4, 5, and 6: Build, validate, chose, and test hybrid partitions*
- [Code](https://github.com/cissagatto/TcpKnnH) for Sparsification with KNN + Hierarchical Methods 
- [Code](https://github.com/cissagatto/TcpKnnNh) for Sparsification with KNN + Non Hierarchical Methods
- [Code](https://github.com/cissagatto/TcpTrH) for Sparsification with Threshold + Hierarchical Methods
- [Code](https://github.com/cissagatto/TcpTrNh) for Sparsification with Threshold + Non Hierarchical Methods

*Code for Global, Local, and Random Partitions*
- [Global](https://github.com/cissagatto/GlobalPartitions)
- [Local](https://github.com/cissagatto/LocalPartitions)
- [Generate Random Graphs](https://github.com/cissagatto/GenerateRandomCommunities)
- [Test Random Graph + Hierarchical Methods](https://github.com/cissagatto/TcpRandomH)
- [Test Random Graph + Non Hierarchical Methods](https://github.com/cissagatto/TcpRandomNh)
