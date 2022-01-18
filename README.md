# DFL-PiDA
Prediction of Piwi-interacting RNA-Disease Association based on Deep Feature Learning
# Data description
Benchmark dataset: contains 7939 known associations between 4796 piRNAs and 28 diseases from manually curated experiments. The positive samples are derived from piRDisease v1.0 (http://www.piwirna2disease.org/index.php), containing 5002 association pairs between 4350 piRNAs and 21 diseases, the negative samples containing the same 5002 association pairs, which were randomly selected from all the 86348 (4350\*21-5002) unidentified piRNA-disease association pairs.


Disease_semantic_information: The disease semantic information is derived from the Medical Subject Headings (MeSH) database (https://www.nlm.nih.gov/).


piRBase_hsa_piRNA_Sequence: The piRNA IDs and sequence information is derived from the piRBase v2.0 (http://www.regulatoryrna.org/database/piRNA/index.html).


Five-fold data partitions: Random array for dividing the training dataset into 5 random copies.


Five-fold prediction results: The prediction results under five-fold cross-validation. The first column of the \*.csv file represents the original labels and the second column represents the predicted labels. The first column of the \*Prob.csv file represents the original labels and the second column represents the predicted scores. The numbers 0 to 4 correspond to the 1 to 5 fold data for the 5-fold cross validation.
# Requirements
DFL-PiDA is tested to work under:


Python 3.6


Tensorflow 1.1.4


numpy 1.14.0


sklearn 0.19.0
# Cite this (BibTex)
@INPROCEEDINGS{9669793,  author={Ji, Boya and Luo, Jiawei and Pan, Liangrui and Xie, Xiaolan and Peng, Shaoliang},  booktitle={2021 IEEE International Conference on Bioinformatics and Biomedicine (BIBM)},   title={DFL-PiDA: Prediction of Piwi-interacting RNA-Disease Associations based on Deep Feature Learning},   year={2021},  volume={},  number={},  pages={406-411},  doi={10.1109/BIBM52615.2021.9669793}}

# Contacts
If you have any questions or comments, please feel free to email: byj@hnu.edu.cn.
