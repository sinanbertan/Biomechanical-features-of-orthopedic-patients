
# Biomechanical-features-of-orthopedic-patients
- This repository contains the code and data for a project on Orthopedic Patients Classification. The project uses the column_2C_weka.csv dataset, which can be downloaded from Kaggle:https://www.kaggle.com/datasets/uciml/biomechanical-features-of-orthopedic-patients
## Data Content



Column_2C_weka.csv (file with two class labels)
* the categories Disk Hernia and Spondylolisthesis were merged into a single category labelled as 'abnormal'. Thus, the second task consists in classifying patients as belonging to one out of two categories: Normal (100 patients) or Abnormal (210 patients).
## Installation
The following tools were used for this analysis:

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Sklearn
- xgboost
- lightgbm
- catboost


- To run this project, you will need to have Python 3 installed on your machine. You can install the required libraries by running the following command:


- pip install pandas matplotlib seaborn numpy plotly Sklearn xgboost catboost lightgbm

    
## Usage 
- To run the analysis, simply execute the notebook. The script will generate several visualizations that help illustrate analysis of data.
## Roadmap

The analysis includes the following tasks:

- Data loading and cleaning
- Exploratory data analysis
- data visualization
- outlier detection 
- building model
- tuning model
- feature importance


The analysis includes visualizations using Matplotlib, Plotly and Seaborn.

## Contributing

- Contributions to this project are welcome. If you notice any errors or have ideas for additional analyses, please feel free to open an issue or submit a pull request.


## Conclusion 
* In This Project, I built a model of Orthopedic Patients classification with Lightgbm algorithm after evaluating lots of classification algorithms. I have explored lots of insights by visualizing the dataset and I got precise result from model classification. According to my model, The accuracy  score is 
% 84.92.