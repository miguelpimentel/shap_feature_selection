

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

The dependencies could be installed using pip, the file with dependecies is presented in root folder, requirements.txt.


### Donwload the Datasets

The data set is available at:

* 

### Update Paths

You have to set the correct path for each dataset.

* 

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