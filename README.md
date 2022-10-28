# Parameter estimation using residual neural network
----
### In this work, we represent a practical approach capable of estimating any stochastic process, whether its likelihood function comes from an unknown distribution or the model relys on simulation-based approaches for data generation.
### The architecture used in this work is as follows: 
<!-- ![Image](https://github.com/hodaVS/Parameter-estimation-using-residual-neural-network/blob/main/ResNet.png =250x250) -->
<img src="https://github.com/hodaVS/Parameter-estimation-using-residual-neural-network/blob/main/ResNet.png" width="500" height="900">

---
## DataSets

> We utilized our model on four specific models. Data sets for the [Toy Examples](https://github.com/hodaVS/Parameter-estimation-using-residual-neural-network/tree/main/Toy%20examples) are available [here](https://heidata.uni-heidelberg.de/dataset.xhtml?persistentId=doi%3A10.11588%2Fdata%2FUVOWT0&version=DRAFT), or you can use [MVN](https://github.com/hodaVS/Parameter-estimation-using-residual-neural-network/tree/main/Toy%20examples/Multivariate%20normal/multivariate%20normal%20data) and [MR](https://github.com/hodaVS/Parameter-estimation-using-residual-neural-network/tree/main/Toy%20examples/Multiple%20regression/multiple%20regression%20data). (Stefan et al., [2020](https://doi.org/10.1111/bmsp.12159))

> Data sets provided for Drift-Diffusion and Collapsing Drift-Diffusion were based on a data-simulation mechanism, and the codes are available [here](https://github.com/hodaVS/Parameter-estimation-using-residual-neural-network/blob/main/Drift-Difusison%20models/DDM/Data_Generation/DataSet/Data_generation-.ipynb) and [here](https://github.com/hodaVS/Parameter-estimation-using-residual-neural-network/tree/main/Drift-Difusison%20models/Collapsing%20DDM/Data_Generation/CB_DataSet), respectively.
---

## Required packages 
For training:
  1. `tensorflow 2.x`
  2. `pandas & numpy & matplotlib`
  3. `sklearn`
 
 For data generation:
  1. `numpy`
  2. `scipy`
  3. `multiprocessing`
  4. `functools` 
  
  number 3 and 4 is needed when using [multi threaded](https://github.com/hodaVS/Parameter-estimation-using-residual-neural-network/blob/main/Drift-Difusison%20models/Collapsing%20DDM/Data_Generation/CB_DataSet/Data_generation-Collapsing-Multi_threaded.ipynb)
  
  
---

## Trained model (To Do)

> To run inference from the SavedModels click on [ [MVN]() , [MR]() , [DDM](https://github.com/hodaVS/Parameter-estimation-using-residual-neural-network/blob/main/trained%20moedels/Resnet_DDM.h5) , [C-DDM]() ]

