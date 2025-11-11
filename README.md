# Sampling Methods - Interactive Tutorial
This Jupyter Notebook is an interactive tutorial on Sampling Methods, based on Chapter 11 of Bishop’s "Pattern Recognition and Machine Learning", covering both the theory and practical implementation of: 

- Inverse Transform Sampling
- Rejection Sampling
- Adaptive Rejection Sampling
- Importance Sampling
- Sampling-Importance-Resampling
- Metropolis-Hastings       



## Setup
The following libraries are required to correctly run all code cells:
- numpy  
- matplotlib  
- scipy  
- ipywidgets  
- IPhyton
- arspy  # installed manually

  

### Note on ARSpy

As it is quite dated, the ARSpy library can't be installed via `pip` due to compatibility issues. To make the ARS section work, please follow these steps:

1. Manually download the library from [PyPI](https://pypi.org/project/ARSpy/)
2. Extract the contents and navigate to the sub-folder `arspy`
3. Copy it directly into the same directory as this Jupyter Notebook (be careful to copy it as it is and not nested inside of other folders)



Vuoi che ti aggiunga subito dopo anche una piccola sezione “Tested environment” con Python version, OS e Jupyter? Sarebbe utile per completezza del README.
