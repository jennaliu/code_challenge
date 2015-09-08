Print out the top 10 most frequent words in the EDRM Enron v2 dataset

Instruction:
1. Download the dataset (http://trec-legal.umiacs.umd.edu/corpora/trec/legal10/edrmv2txt-v2.tar.bz2)
2. Install nltk (http://www.nltk.org/)
3. Write a script to calcuate the top 10 most frequent words
4. Write another script that speeds up the calculation on a multi-core system using threading, multiprocessing or celery

Requirements:
1. For this challenge, you are required to use nltk to split raw text into words, the way to use it is as follows
    from nltk import word_tokenize
    words = word_tokenize(raw_doc)
2. The scripts have to be executable on a Linux(Ubuntu) system

Please send the result along with your scripts and the time took to run each script
