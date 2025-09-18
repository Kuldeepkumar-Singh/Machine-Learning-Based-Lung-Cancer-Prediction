# Machine-Learning-Based-Lung-Cancer-Prediction

## TITLE

Machine Learning-Based Prediction of Lung Cancer Risk Using Demographic, Environmental, Lifestyle, and Health Factors.

## Objective
To identify which feature groups and machine learning models provide the most reliable predictions of lung cancer risk, and to evaluate the potential of ML in supporting early detection and prevention strategies.

## Project Overview

This project applies multiple machine learning algorithms (Logistic Regression, Support Vector Machine, Decision Tree, and Random Forest) to predict lung cancer risk using demographic, environmental, lifestyle, and health-related features.

The workflow includes:
1. Data Preprocessing & Exploration
2. Feature Grouping (Demographic, Environmental, Lifestyle, Health, All Combined)
3. Feature Data Visualization
4. Model Training & Hyperparameter Tuning
5. Performance Evaluation using Accuracy, Precision, Recall, and F1-score
6. Results Visualization
7. Conclusion

## Conclusion
In this project, multiple machine learning models were applied to demographic, environmental, lifestyle, health-related features and all combined features to predict lung cancer risk. The results demonstrated that model performance varied depending on the feature group used:
Demographic features alone yielded relatively low predictive power with Decision Tree and Random Forest slightly outperforming Logistic Regression and SVM.
Environmental and Lifestyle features provided much stronger predictive ability, with SVM, Decision Tree, and Random Forest achieving accuracies close to 0.90-0.97.
Health-related features achieved the highest performance, with all models reaching perfect classification scores, suggesting strong predictive potential but also the possibility of overfitting.
When all feature groups were combined, performance was further enhanced, with Random Forest and SVM delivering near-perfect results (accuracy >= 0.99).
Overall, the study highlights that incorporating a broad spectrum of risk factors—particularly health, lifestyle, and environmental features improves accuracy compared to demographic data alone.

## License
This project is licensed under the **MIT License** - see the [LICENSE.md](LICENSE.md) file for details.



