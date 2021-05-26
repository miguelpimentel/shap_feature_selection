

# Feature Selection Using SHAP: An Explainable AI Approach

## Overview

The experiments were developed from python notebooks. For each experiment, a notebook was created for each of the used models, that is, for the Cancer Breast dataset, four python notebooks were created, one for each model. The same process was introduced in the Credit Card Dataset.

When running each notebook the results are saved in the result folder for each of the experiments. A CSV file is created with the result of the metrics for each scenario of the experiment (number of features), and the charts are created for each of the metrics.

For each experiment, there is a notebook with the objective of gathering the results obtained for each model and creating reports and charts about the experiment as a whole.

Last but not least important, for any questions, read the README.md file and feel free to open an issue.

## Article

The thesis and presentation is presented inside the docs foldes. 

## Install

### Clone the repository

```bash
git clone https://github.com/miguelpimentel/shap_feature_selection.git
```

### Install dependecies 

#### Mini conda

Install the mini conda to create an enviroment, it's a nice solution to handle different versions of libraries and packages:

* [Miniconda](https://docs.conda.io/en/latest/miniconda.html)

#### Install jupyter 

```bash
conda install -y jupyter
```

### Create enviroment

Add the code below to an xai.yml file. This add the required packages and versions to each library.

```
name: xai
 
dependencies:
    - python=3.9
    - pip>=19.0
    - jupyter
    - scikit-learn
    - scipy
    - pandas
    - pandas-datareader
    - matplotlib
    - pillow
    - tqdm
    - requests
    - h5py
    - pyyaml
    - flask
    - boto3
    - pip:
        - lime
        - shap

```

The following command create an enviroment with the mentioned packages and libraries

conda env create -f xai.yml -n xai

#### Use Enviroment

```bash
conda activate xai
```

#### Add Enviroment to notebook 

```bash
conda install nb_conda
```

```bash
python -m ipykernel install --user --name xai --display-name "XAI - Python Enviroment"
```

### Donwload the Datasets

The datasets are available at:

*  [Dataset](https://drive.google.com/drive/folders/1yWUv0vK79ahxmHUuFKORJSyOwq_tiX54?usp=sharing

### Update Paths

You have to set the correct path for each dataset, that means:

* Add de creditcard.csv file inside the folder credit_card_fraud/dataset/

* Add de data-te.csv file inside the folder cancer_breast/dataset/.


## Run 

 You can run using using jupyter notebook by the following command inside the project root folder:

 ```bash
jupyter notebook </Experiment>
 ```

E.g:

 ```bash
jupyter notebook cancer_breast/cancer-breast-catboost.ipynb
 ```

## Authors

Miguel Pimentel