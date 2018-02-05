# Introduction
This is the source code of our AAAI 2018 paper "Unsupervised Generative Adversarial Cross-modal Hashing", Please cite the following paper if you use our code.

Jian Zhang, Yuxin Peng, and Mingkuan Yuan, "Unsupervised Generative Adversarial Cross-modal Hashing", 32th AAAI Conference on Artificial Intelligence (AAAI), New Orleans, Louisiana, USA, Feb. 2–7, 2018. [[arXiv]](https://arxiv.org/abs/1712.00358)

# Usage
For NUSWIDE dataset:

1. Generate KNN graph by the codes under KNN directory: python knn_nus_cross5.py
2. Pretrain the model by using the code under pretrain directory: python train_16.py
3. Train the model by using the code under UGACH-nus: python train_16.py
4. Generate hash codes for query and database samples: python test_16.py

MIRFlickr dataset is similar to the NUSWIDE dataset.

For more information, please refer to our [AAAI paper](https://arxiv.org/abs/1712.00358).

Welcome to our [Laboratory Homepage](http://www.icst.pku.edu.cn/mipl) for more information about our papers, source codes, and datasets.
