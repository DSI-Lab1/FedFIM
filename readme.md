# FLFIM
This repo hosts the code for paper "Privacy-preserving federated mining of frequent itemsets", Information Sciences, Chen, Yao and Gan, Wensheng and Wu, Yongdong and Philip, S Yu, 2023.

## Requirements
Python programming language.

## Running the program
python main.py --dataset=mushrooms --k=0.35 --xi=0.01 --epsilon=5 --num_participants=8416

## Introduction
FedFIM is a federated learning framework for frequent itemset mining. FedFIM collects the noisy responses sent by participants, which are used by the server to reconstruct the noisy dataset. After that, the noisy dataset is applied to the non-Apriori algorithm to mine frequent patterns. In addition, FedFIM incorporates a differential privacy-preserving mechanism into federated learning, which addresses the need for federated modeling and protects data privacy.

## Dataset
The Movielens dataset is used in FedFPM and provided at GitHub (https://github.com/HuskyW/FFPA). The other datasets are available at SPMF website (https://www.philippe-fournier-viger.com/spmf/index.php?link=datasets.php).
Firstly, download dataset D from the website above. 
Then, obtain the pickle file by executing program Preprocess.py.

## Citation 
If this article or code useful for your project, please refer to
```
@article{chen2023privacy,
  title={Privacy-preserving federated mining of frequent itemsets},
  author={Chen, Yao and Gan, Wensheng and Wu, Yongdong and Philip, S Yu},
  journal={Information Sciences},
  volume={625},
  pages={504--520},
  year={2023},
  publisher={Elsevier}
}
```

## Notes
If there are any questions, please contact us (Email: csyaochen@gmail.com).