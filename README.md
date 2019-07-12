Classifying the perfect match 

This project is a try to explore what makes two peopel a match based on online profile using the eHarmonry matchings dataset. 



DATA: 
This data set was provided by eHarmony, Inc. Dataset can be downloaded here:
https://bmcfee.github.io/data/eharmony.html

The data consists of pairs of individuals, which either matched (positive example) or did not (negative example). The data is partitioned into two subsets corresponding to two equal-length segments of time. The data is stored in CSV files, organized as follows.

EH-*-data.csv.gz
Each row describes an individual. The first column is an identification number for that individual, and all subsequent columns contain the (numeric) feature values.
EH-*-labels.csv.gz
Each row describes a pairwise interaction. The first column indicates whether the interaction is positive (1) or negative (0). The second and third columns contain identification numbers for the corresponding individuals.

NOTE:
To protect the privacy of users, all features have been obfuscated and normalized. I cannot provide names for the features.

More details about the dataset can be found in this paper: 
McFee, B. and Lanckriet, G.R.G. (2010). Metric learning to rank. Twenty-seventh International Conference on Machine Learning (ICML).
The source code for this paper can be found in Github: 
https://github.com/bmcfee/mlr