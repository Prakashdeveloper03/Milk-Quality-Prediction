# Milk Quality Prediction

![python 3.11.2](https://img.shields.io/badge/Python-3.11.2-blue.svg)
![html](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![numpy](https://img.shields.io/badge/Numpy-777BB4?logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/Pandas-2C2D72?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/Scikit_learn-0078D4?logo=scikit-learn&logoColor=white)
![fastapi](https://img.shields.io/badge/Fastapi-109989?logo=FASTAPI&logoColor=white)
![jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?logo=Jupyter&logoColor=white)
![terminal](https://img.shields.io/badge/Windows%20Terminal-4D4D4D?logo=windows%20terminal&logoColor=white)
![vscode](https://img.shields.io/badge/Visual_Studio_Code-0078D4?logo=visual%20studio%20code&logoColor=white)

Milk Quality Predictor App used to predict nothing but the quality grade of the milk based on certain input parameters created using python's scikit-learn, fastapi, numpy and joblib packages.

## Dataset Description

The datasets consist of several predictor (independent) variables and one target (dependent) variable, Grade. This Data is already preprocessed where there are no null values and Probably there will no imbalance in Dataset.

The data contains the following columns:

| Feature Name  | Feature Description                                                                                           |
| ------------- | ------------------------------------------------------------------------------------------------------------- |
| pH            | This Column defines PH values of the milk which ranges from 3 to 9.5 max : 6.25 to 6.90                       |
| Temprature    | This Column defines Temprature of the milk which ranges from 34'C to 90'C max : 34'C to 45.20'C               |
| Taste         | This Column defines Taste of the milk which is categorical data 0 (Bad) or 1 (Good) max : 1 (Good)            |
| Odor          | This Column defines Odor of the milk which is categorical data 0 (Bad) or 1 (Good) max : 0 (Bad)              |
| Fat           | This Column defines Odor of the milk which is categorical data 0 (Low) or 1 (High) max : 1 (High)             |
| Turbidity     | This Column defines Turbidity of the milk which is categorical data 0 (Low) or 1 (High) max : 1 (High)        |
| Colour        | This Column defines Colour of the milk which ranges from 240 to 255 max : 255                                 |
| Grade         | This Column defines Grade (Target) of the milk which is categorical data Where Low (Bad) or Medium (Moderate) |
| Outcome Taste | Class variable (0 or 1) 268 of 768 are 1, the others are 0                                                    |
