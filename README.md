## FedMax and FedMed: Federated aggregation techniques with adaptime momentum estimation

In this peoject, I introduced two novel federated aggregation techniques: Federated maximum and federated median and compare their perfomnace with federated averaging (FedAvg). 

## Dataset 
A well-known dermatoscopic image dataset: [HAM10000](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T) is used as experiment data.

## Folder description
- client_1 (HAM-data-owner1)
  - This client has total 2800 sample of seven class ( 400 per class)
- client_2 (HAM10000-data-owner2)
   - This client has total 2100 sample of seven classes ( 300 per class)
      - 0/
        - image_1.png
        - image_2.png
        - ...
      - 1/
      - ...
    - test/
      - 0/
        - image_1.png
        - image_2.png
        - ...
      - 1/
      - ...
  - models/
    - best_mlp_model.pt
    - best_cnn_model.pt
  - notebooks/
    - data_exploration.ipynb
    - model_training.ipynb
    - model_evaluation.ipynb
  - src/
    - data.py
    - models.py
    - train.py
    - evaluate.py
