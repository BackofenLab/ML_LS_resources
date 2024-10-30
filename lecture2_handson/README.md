## Step 1: Create the necessary environment

`conda create --name gene_disease python==3.10`

`conda activate gene_disease`

`pip install jupyterlab==4.2.4`

`pip install pandas==2.1.1`

`pip install scikit-learn==1.5.1`

`pip install torch==2.4.0 torchvision==0.19.0 torchaudio==2.4.0 --index-url https://download.pytorch.org/whl/cu121`

`pip install torch-scatter torch-sparse  torch-cluster torch-spline-conv -f https://pytorch-geometric.com/whl/torch-2.4.0+cu121.html`

`pip install torch-geometric==2.6.1`


## Step 2: Run Jupyter lab

`jupyter lab`

