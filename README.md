# SC1015 Mini Project: Stroke Prediction
## Overview
Welcome to our SC1015 Mini Project on Stroke Prediction! In this repository, we explore an insightful dataset related to stroke prediction. Our primary goal is to develop a predictive model that accurately identifies individuals at risk of experiencing a stroke based on various demographic, lifestyle, and health-related factors provided in the dataset.

## About
According to the World Health Organization (WHO), stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths. Additionally, from 1990 to 2019, there has been a 70% increase in stroke incidence, 43% increase in deaths due to stroke, and 10% increase in stroke prevalence.

## Problem Definition
- How can we develop a predictive model that effectively identifies individuals at risk of experiencing a stroke by analyzing a dataset containing demographic, lifestyle, and health-related factors?
- Which machine learning model would best predict the likelihood of stroke occurrence in individuals?

## Repository Contents
1. [Data_Cleaning.ipynb](#Data_Cleaning.ipynb)
2. [Data_Modeling.ipynb](#Data_Modeling.ipynb)
3. [Exploratory_Data_Analysis.ipynb](#Exploratory_Data_Analysis.ipynb)
4. [LICENSE](#LICENSE)
5. [README.md](#README.md)
6. [cleaned_data.csv](#cleaned_data.csv)
   - This is our dataset after data cleaning.
7. [healthcare-dataset-stroke-data.csv](#healthcare-dataset-stroke-data.csv)
   - This is the original uncleaned dataset.

## File Description
For detailed walkthrough, please view the source code in the following order:
1. [Data Cleaning](#Data_Cleaning.ipynb)
2. [Exploratory Data Analysis](#Exploratory_Data_Analysis.ipynb)
3. [Data Modeling](#Data_Modeling.ipynb)

## Installation Instructions
### Models Used
1. Gaussian Naive Bayes
2. K-Nearest Neighbour
3. eXtreme Gradient Boosting
4. Bernoulli Naive Bayes
5. Decision Tree

### Libraries and Packages
1. numpy
2. pandas
3. seaborn
4. matplotlib.pyplot
5. scikit-learn
6. imbalanced-learn
   - Requires installation by using pip, the Python package manager, and entering `pip install imbalanced-learn`

## Takeaways from the project
- Handling imbalanced datasets using data resampling methods and imbalanced-learn package
- Collaborating using GitHub
- Understanding metrics on Precision, Recall, F1 Score, Accuracy Score
- Understanding the Metric Trap and Data Leakage
- Learnt about new models and their use cases


## Key Takeaways from the Project
- **Handling Imbalanced Datasets**: Explored various data resampling methods, such as oversampling and undersampling, to address class imbalance issues and improve model performance. Leveraged the `imbalanced-learn` package to implement these techniques effectively.

- **Effective Collaboration with GitHub**: Utilized Git and GitHub for version control, collaboration, and project management.

- **Understanding Performance Metrics**: Gained insights into key performance metrics such as Precision, Recall, F1 Score, and Accuracy Score. Explored their interpretation and significance in evaluating model performance.

- **Avoiding the Metric Trap and Data Leakage**: Recognized the importance of avoiding common pitfalls such as the Metric Trap and Data Leakage, which can lead to misleading results and overestimation of model performance. Implemented strategies to mitigate these risks effectively.

- **Exploring New Models and Use Cases**: Explored a range of machine learning models and their use cases, gaining valuable insights into their strengths, weaknesses, and practical applications.

## Contributors
- **[@DylanTYX](https://github.com/DylanTYX)**: Data Preparation, Exploratory Data Analysis, Data Resampling, Data Modelling
- **[@KiongLu](https://github.com/KiongLu)**: Exploratory Data Analysis, Data Resampling, Data Modelling

School of Computer Science and Engineering  
Nanyang Technological University

## References
- B, H. N. (2020). Confusion Matrix, Accuracy, Precision, Recall, F1 Score. Retrieved from [Medium](https://medium.com/analytics-vidhya/confusion-matrix-accuracy-precision-recall-f1-score-ade299cf63cd)
- Fedesoriano. (2021). Stroke Prediction Dataset. Retrieved from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
- World Stroke Day 2022. (n.d.). Retrieved from [World Health Organization](https://www.who.int/srilanka/news/detail/29-10-2022-world-stroke-day-2022#:~:text=From%201990%20to%202019%2C%20there,Adjusted%20Life%20Years%20(DALY).)

## License
Copyright (c) 2024 Tan Yi Xiang, Dylan and Yong Kiong Lu.

Unless otherwise specified, this project (all of the files in this repository) is licensed under the [MIT License](LICENSE).
