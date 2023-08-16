# Graph-UNet_project
An implementation of the paper https://arxiv.org/pdf/1905.05178.pdf

This paper simply describes the application of the UNet model to Graph Neural Networks (GNNs).
We chose the PROTEINS dataset, which will be automatically downloaded (if not already present in the directory) 
when running the code.

The general structure of the model is the following:

![image](https://github.com/camillaiorio/Graph-UNet_project/assets/73958694/8842056d-cee6-4c22-ba33-f96ac88f4236)

## How to run 
- $ pip install -r requirements.txt
- run all the cells of the Jupyter notebook _Graph_UNets_paper_implementation.ipynb_
- (Optional) Make other experiments by changing parameters by looking at the experiments folder

In any case, look at _experiments.pdf_ to look at the results of the experiments that we have already performed.
