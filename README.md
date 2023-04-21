## FedMax and FedMed: Federated aggregation techniques with adaptive moment estimation

In this peoject, I introduced two novel federated aggregation techniques: Federated maximum and federated median and compare their perfomnace with federated averaging (FedAvg). 

## Dataset 
A well-known dermatoscopic image dataset: [HAM10000](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T) is used as experiment data.

## Library and framework
PySyft==0.7.0 for creating remote workers and PyTorch for deep learning implementation.

## Folder description
- client_1 (HAM-data-owner1)
  - This client has total 2800 sample of seven class ( 400 per class)
- client_2 (HAM10000-data-owner2)
   - This client has total 2100 sample of seven classes ( 300 per class)
- server-side (HAM-data-scientist)
   - Global model (LeNet): design and make a copy of the global model for two clients, send the copy to the clients for training the model using their local data, and    implement aggregation for global model updates.
- data-analysis (course project)
   - Data balancing, creating two different subsets for two clients.
      
