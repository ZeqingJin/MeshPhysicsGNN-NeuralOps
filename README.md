# MeshPhysicsGNN-NeuralOps

In this paper, we developed graph neural network (GNN) models with enhanced generalizability derived from the distinct GNN architecture and neural operator technique. As a proof of concept, we employ our GNN models to predict finite element (FE) simulation results for three-dimensional solid mechanics problems with varying boundary conditions. Results show that our GNN model achieves accurate and robust performance in predicting the stress and deformation profiles of structures compared with FE simulations. Furthermore, the neural operator embedded GNN approach enables learning and predicting various solid mechanics problems in a generalizable fashion, making it a promising approach for surrogate modeling.

<img src="Fig2.tif" width="500"/>

Instructions:

1. Please either clone the full repo to your local desktop or download the whole repo and upload to Google drive "MyDrive" folder, running on Google Colab (recommended).

2. The code in "data_preprocessing" folder converts the csv results from FEM to .pt file for training.(You may skip this step if just want to run the GNN model)

3. The code in "main" folder runs the conventional GNN model. 

4. The code in "NeuralOps" folder includes the modified GNN model with neural operator (mesh reconstruction) method. 

References:

[1] [Learning Mesh-Based Flow Simulations on Graph Networks](https://medium.com/stanford-cs224w/learning-mesh-based-flow-simulations-on-graph-networks-44983679cf2d)

[2] [Learning Mesh-Based Simulation with Graph Networks](https://arxiv.org/abs/2010.03409)

[3] [Neural Operator: Learning Maps Between Function Spaces](http://tensorlab.cms.caltech.edu/users/anima/pubs/GraphPDE_Journal.pdf)
