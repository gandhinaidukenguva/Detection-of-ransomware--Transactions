
# Ransomware-Transactions-Detection

### Problem Statement:
To determine whether the bitcoin transaction is a ransomware attack or not, use a categorization model. 

### Dataset:
The dataset is provided by UCI. It has  2,916,697 records with 10 features like the bitcoin transaction address and date. 
Each row represents a transaction. The target is the label of the transaction: Is it a ransom transaction or not?<br><br>

#### Full data
It can be accessed from here: [Full data](https://archive.ics.uci.edu/ml/datasets/BitcoinHeistRansomwareAddressDataset)

#### Best model data:
The data is too big to upload in github, but you can [download it from here](https://drive.google.com/file/d/160KSNgXVwATn1EBSE1MwM5v44_DM8Pai/view?usp=sharing).

### Model Score:
#### Data:
Undersampled (with TomekLinks and EditedNearestNeighbours) and unbalanced, scaled with min-max<br>
#### Model:
AdaBoosting with XGB, GBT and GNB
#### Scoring:
![CM](https://raw.githubusercontent.com/SDAIA-T5-Projects/Ransomware-Transactions-Detection/main/Photo/CM.png)
![AUC](https://raw.githubusercontent.com/SDAIA-T5-Projects/Ransomware-Transactions-Detection/main/Photo/AUC.png)

Accuracy   =  0.9120<br>
Precision  =  0.898 <br>
Recall        =  0.9321 <br>
F-Score       =  0.9138<br>
AUC           = 0.972








