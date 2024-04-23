# DeepTGIN
A Protein Ligand Affinity Prediction Model based on Transformer and GIN

Environment  
python==3.8  
torch==1.9.0  
torch_geometric==2.0.1  
torch_cluster==1.5.9  
torch_scatter==2.0.8  
torch_sparse==0.6.12  
rdkit==2023.3.3  
## Data
We use PDBBind2020 as our dataset，http://pdbbind.org.cn/
The code for data preprocessing is [create_data.py](create_data.py)
## Train
If you want to train the model, run python [main.py](main.py)
## Cite
If our work is helpful to you, we encourage you to cite our paper:
