# Credit_Risk_Analysis
Bootcamp Module 17

## Overview
The main porpouse of the analysis is to predict Credit adn Risk for laon approval. Predicting loans is quite a difficlt taks, so we will be creating different machine learing models to get different scenarios and pick the best performing model to hepl us take the best decision possible.

The models we will be using are the following:
- Naive Random Oversampling
- SMOTE Oversampling
- ClusterCentroids Undersampling
- SMOTEENN Combination
- Balanced Random Forest
- Easy Ensemble AdaBoost


## Results
We will display each model and measure them using 3 main metrics (Accuracy, Precision and Recall).
- Naive Random Oversampling
  - Accuracy = 66.13%
  - Precision = 99%
  - Recall = 66%
<img width="967" alt="Captura de Pantalla 2021-10-17 a la(s) 18 57 16" src="https://user-images.githubusercontent.com/85461477/137657777-e6709288-44fe-4bb9-b071-837cf1de981e.png">


- SMOTE Oversampling
  - Accuracy = 64.80%
  - Precision = 99%
  - Recall = 65%
<img width="933" alt="Captura de Pantalla 2021-10-17 a la(s) 18 57 28" src="https://user-images.githubusercontent.com/85461477/137657788-5cb3b4f4-c4bb-49e5-bfb7-d4e1c88b2254.png">


- ClusterCentroids Undersampling
  - Accuracy = 43.50%
  - Precision = 99%
  - Recall = 43%
<img width="849" alt="Captura de Pantalla 2021-10-17 a la(s) 18 57 51" src="https://user-images.githubusercontent.com/85461477/137657811-e120f382-28ba-4632-9241-844f81ca044f.png">


- SMOTEENN Combination
  - Accuracy = 54.02%
  - Precision = 99%
  - Recall = 54%
<img width="804" alt="Captura de Pantalla 2021-10-17 a la(s) 18 58 03" src="https://user-images.githubusercontent.com/85461477/137657832-09f5894b-0ce5-4cbb-8778-1b284692eec4.png">


- Balanced Random Forest
  - Accuracy = 80.16%
  - Precision = 99%
  - Recall = 88%
<img width="825" alt="Captura de Pantalla 2021-10-17 a la(s) 18 58 29" src="https://user-images.githubusercontent.com/85461477/137657843-5dec2a0d-8fda-4f7e-a1d9-092740c0948f.png">


- Easy Ensemble AdaBoost
  - Accuracy = 91.79%
  - Precision = 99%
  - Recall = 94%
<img width="812" alt="Captura de Pantalla 2021-10-17 a la(s) 18 58 50" src="https://user-images.githubusercontent.com/85461477/137657855-466993d2-905f-4a2c-8fd9-e8c2c6398363.png">


## Summary
First, we must classify our models in 2. The first group is where we us Oversampling, Undersampling and the combination. We can see models in there group are not very accurate, ranging from 43% to 66% percent in accuracy. The second group used ensembled classifier to resample their data. The second group is more accurate ranging from 80% to approximatly 92% accuracy. We can see all models have a 99% precision. We can also appreciate the Recall percentage tends to be close to the accuracy percentage in this excercise. I would recomend the AdaBoost model, since it seems to be model with the best stats overall.
