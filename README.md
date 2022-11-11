# Data Science Challenge @ Interdsciplinary Workshop on Machine Learning for Cryptology (ML4Crypto 2022)

This Data Science Challenge is about performing distinguishing attack on some popular symmetric-key block based ciphers with machine learning. The distinguishing attack is imposed as a multi-class classification (supervised) learning problem.

The sources of the data are summaries of news articles converted into ciphertexts. The data is seggregated into two parts - training and testing. The training data comprises 80,000 ciphertexts generated either randomly or by applying one of the ciphers DES, AES and Blowfish. The labels (0, 1, 2 and 3) in the training data denotes the source type. The test data comprises 20,000 ciphertexts without any labels. The labels of the test data are to be predicted.
