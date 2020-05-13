# COVID-19-X-ray-IEEE-LATAM
This repository provides all code of the experiments of the paper "Classifying COVID-19 positive X-ray using deep learning models", which was submitted to IEEE Latin America Transactions (IEEE-LATAM).

## The project
In this repository, we classify two types of binary classification:
* COVID-19 vs Healthy
* COVID-19 vs Viral pneumonia

We also make a multiclass classification:
* COVID-19 vs Viral pneumonia vs Healthy

## Dataset
Thanks to Tawsifur Rahman et al. [1], which have developed the dataset. The dataset contains data of patients that contains the three mentioned classes above. 

## Environment configuration
* Conda version: https://repo.continuum.io/miniconda/Miniconda3-4.5.1-Linux-x86_64.sh
* Make sure you have installed the conda environment
	* Clone repository
	* In the repository folder create the environment `conda env create -f covid.yml`
	* List the environment `conda info --envs`
	* Activate the new created environment `conda activate env_name`

## Executing the code
* When you activate the environment, navigate into the "code" folder
* Run the jupyter notebook `python -m notebook`
* With the jupyter notebook open the `main.ipynb`
* The code has instructions of how to execute in its comments

## The paper results
The paper results can be found at https://docs.google.com/spreadsheets/d/1xBRx6-rHy__1FjaBbd1KzKGlwoyckLjrB7SMz_yMzSA/edit#gid=0
These results are corresponding to each step of the cross validation experiments (average and std are also provided). 

## References
[1] COVID-19 RADIOGRAPHY DATABASE (Winner of the COVID-19 Dataset Award). Kaggle. https://www.kaggle.com/tawsifurrahman/covid19-radiography-database
