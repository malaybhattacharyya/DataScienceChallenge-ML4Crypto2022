# Data Science Challenge @ Interdisciplinary Workshop on Machine Learning for Cryptology (ML4Crypto 2022)

This Data Science Challenge is about performing distinguishing attack on some popular symmetric-key block based ciphers with machine learning. The distinguishing attack is imposed as a multi-class classification (supervised learning) problem. The participants are welcome to employ any sort of classification approach, be it classical machine learning, deep learning, or others.

The sources of the data are summaries of news articles. These articles (plaintexts) are converted into ciphertexts. There are three columns in the dataset. The first column denotes the ID of the ciphertext. The second column comprises the actual ciphertexts generated either randomly or by applying one of the ciphers DES, AES and Blowfish. The ciphertexts are created in CBC mode and are given in hexadecimal representation. Each ciphertext has a length of 1000 hexadecimal characters. The third column consists of the labels (0, 1, 2 and 3), which denote the ciphertext type.

The data is segregated into two parts - training and testing. The training data comprises 80,000 ciphertexts. The training data includes the labels. The test data comprises 20,000 ciphertexts without any labels. The labels of the test data are to be predicted.

The performance metric for the multi-classification on the test data will be F1-score.
