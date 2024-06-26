# CryptoAssetsAnalytics
Analyzing Ethereum Smart Contracts by fintuning CodeBert on it to detect vurnabilities

## Data

https://huggingface.co/datasets/mwritescode/slither-audited-smart-contracts

## Training
For training the TU Wien Jupyter Hub Servers where used with GPU support. You need 40GB of RAM to train these models.

QLoRA was used for traning: https://github.com/artidoro/qlora

## Model

https://github.com/microsoft/CodeBERT


In the Notebook, data and model checkpoints are made. Thats why the disk requirement is so high.

Here you can see the usage of the last run
![image](https://github.com/DennisToma/CryptoAssetsAnalytics/assets/92679395/0dbb2e2d-89cb-4a99-b420-372158e3d018)
