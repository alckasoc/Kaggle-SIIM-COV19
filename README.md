# Kaggle-SIIM-COVID19


## Table of Contents:  
- [Pipeline Architecture](https://github.com/alckasoc/Kaggle-SIIM-COVID19/blob/main/README.md#pipeline-architecture)
- [Dependencies](https://github.com/alckasoc/Kaggle-SIIM-COVID19/blob/main/README.md#dependencies)


# Pipeline Architecture

For this competition our pipeline can be separated into multiple parts:

- [wandb.ai](https://wandb.ai/site) for logging, metrics, error analysis, and model tracking.
- [GitHub](https://github.com/) for storing the raw code from our Kaggle Notebooks.
- [Kaggle](https://www.kaggle.com/) for sharing, collaborating, and experimenting with code. 


## Dependencies

* The original dataset from this competition is located [here](https://www.kaggle.com/c/siim-covid19-detection/data).
* The Python libraries used are located in [requirements.txt](https://github.com/alckasoc/Kaggle-SIIM-COVID19/blob/main/requirements.txt).
* The input files from all our Kaggle Notebooks will be located in the privately shared Kaggle Notebooks.
* Working/intermediate files such as model weights or history scores will be kept in the src folder in this repo.

