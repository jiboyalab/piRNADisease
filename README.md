# DFL-PiDA
Deep Feature Learning for Piwi-interacting RNA-Disease Association Prediction via Convolutional Denoising Autoencoder Neural Network
# Data description
benchmark dataset: contains 7939 known associations between 4796 piRNAs and 28 diseases from manually curated experiments. The positive samples are derived from piRDisease v1.0 (http://www.piwirna2disease.org/index.php), containing 5002 association pairs between 4350 piRNAs and 21 diseases, the negative samples containing the same 5002 association pairs, which were randomly selected from all the 86348 (4350\*21-5002) unidentified piRNA-disease association pairs.
disease_semantic_information: The disease semantic information is derived from the Medical Subject Headings (MeSH) database (https://www.nlm.nih.gov/).
piRBase_hsapiRNA_Sequence: The piRNA IDs and sequence information is derived from the piRBase v2.0 (http://www.regulatoryrna.org/database/piRNA/index.html).
five-fold data partitions: 
five-fold prediction results:
# Requirements
DFL-PiDA is tested to work under:
Python 3.6
Tensorflow 1.1.4
tflearn
numpy 1.14.0
sklearn 0.19.0
# Contacts
If you have any questions or comments, please feel free to email: byj@hnu.edu.cn.
