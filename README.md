# Credit_Risk_Analysis

## Overiew of Project

This project aimed to to use machine learning to assess credit data. I used various methods to create a model that predicts credit risk from an exisiting dataset.

I utilized RandomOversampling, SMOTE, RandomUndersampling, Randon Forst Classifier, and Easy Ensemble Classifier to create the different models.

The following report will display the returns of the models and discuss which would be the most accurate for determining credit risk.

## Results

1. ###### RandomOversampler
    - Balanced Accuracy Score

    ![Credit ROS BAS](https://user-images.githubusercontent.com/85756203/139594487-6a7da687-2337-4834-bf85-65abe3546fb2.png)
    - Precision & Recall

    ![Credit ROS PR](https://user-images.githubusercontent.com/85756203/139594497-cab26ced-59a3-488a-be9a-50766edee790.png)
    
2. ###### SMOTE Oversampling
    - Balanced Accuracy Score
    
    ![SMOTE BAS](https://user-images.githubusercontent.com/85756203/139594578-77c22575-6e5c-4b62-b15f-84962dbbbe9d.png)
    
    - Precision & Recall
     
    ![SMOTE PR](https://user-images.githubusercontent.com/85756203/139594581-241e6b08-1042-4132-b5b5-16b0dbb29670.png)

3. ##### RandomUndersampler
    - Balanced Accuracy Score
    
    ![UND BAS](https://user-images.githubusercontent.com/85756203/139594657-eccbc473-1bfa-44d0-b191-ac8f5dd1e577.png)

    - Precision & Recall

    ![UND PR](https://user-images.githubusercontent.com/85756203/139594661-95afc351-ed80-4b67-9d8b-40141c981fb0.png)

4. ###### SMOTEEN
    - Balanced Accuracy Score

    ![SMOTEEN BAS](https://user-images.githubusercontent.com/85756203/139594706-e930e7fc-ab87-455f-836a-9567b1d4b019.png)

    - Precision & Recall

    ![SMOTEEN PR](https://user-images.githubusercontent.com/85756203/139594709-3945861d-f74c-4405-9be4-b3fc4362a932.png)

5. ##### Random Forest Classifier
    - Balanced Accuracy Score

    ![RFC BAS](https://user-images.githubusercontent.com/85756203/139594900-3f820772-ae77-4cd3-a47d-76c5060f0a3d.png)

    - Precision & Recall

    ![RFC PR](https://user-images.githubusercontent.com/85756203/139594905-e6ce0725-b0ca-47f0-9375-3b62e520cd89.png)

6. ##### Easy Ensemble Classifier
    - Balanced Accuracy Score
    
    ![EEC BAS](https://user-images.githubusercontent.com/85756203/139594860-de06e92f-81a3-4d77-9790-b13fb86a930d.png)

    - Precision & Recall
    
    ![EEC PR](https://user-images.githubusercontent.com/85756203/139594865-28caf59d-6a45-49c7-8c38-48be59c92fc3.png)

## Summary

The classification reports for all the models show a few similarities between them. All the models have high average-precision scores.

We start to see the disparities between the models when we look at the balanced accuracy scores and the recall scores of the models.

The Random Forest Classifier and EasyEnsambleClassifier both had strong recall scores.

The model I recommend to be used to determine credit risk is the EasyEnsembleClassifier. This model produced an accuracy score of 0.93, the highest score of all the models—combined with a precision score of 0.99 and a recall score of 0.94, the EasyEnsembleClassifier model has produced the best results. 
