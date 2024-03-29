# Data Science Challenge @ Interdisciplinary Workshop on Machine Learning for Cryptology (ML4Crypto 2022)

This Data Science Challenge is a part of an interdisciplinary workshop on "Machine Learning for Cryptology" (ML4Crypto 2022) to be held during December 15-16, 2022 at Indian Statistical Institute, Kolkata. The webpage for the workshop is: https://www.isical.ac.in/~caiml/ml4crypto2022

The said Data Science Challenge is about performing distinguishing attack on some popular symmetric-key block based ciphers with machine learning. The challenge deals with a relatively easier version of the problem. The distinguishing attack is posed as a multi-class classification (supervised learning) problem. The participants are welcome to employ any sort of classification approach, be it classical machine learning, deep learning, or others.

A large set of plaintexts is taken from a benchmark dataset. These plaintexts are converted into ciphertexts and cropped to the same length. There are three columns in the dataset. The first column denotes the ID of the ciphertext. The second column comprises either the ciphertexts generated by applying some ciphers or random text. The ciphertexts / random texts are given in hexadecimal representation. Each ciphertext / random text has a length of 1000 hexadecimal characters. The third column consists of the labels (0, 1, 2 and 3), which denote the ciphertext type.

The dataset is segregated into two parts - training and test. The training dataset comprises 80,000 ciphertexts. The training dataset includes the labels. The test dataset comprises 20,000 ciphertexts without any labels. The labels of the test dataset are to be predicted. The submitted trained models will be applied on the test dataset by the organizers.

The performance metric for the multi-class classification on the test dataset will be the accuracy score.
