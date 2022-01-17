# titanic_survival_prediction
Using the Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic), I applied machine learning algorithms with Scikit-Learn to predict survival, using Seaborn for data visualization. 
- data: contains cleaned and split data
- models: contains models fit for selection and final models fit over all data
- submissions: contains submissions from each model
- [titanic.ipynb](https://github.com/KevinyWu/titanic_survival_prediction/blob/main/titanic.ipynb): contains full pipeline
  - Exploration of categorical and continuous features
  - Creation of new features
  - Cleaning, capping, transforming, and scaling data
  - Feature selection
  - Training and validating models using 5-fold cross-validation
    - Logistic regression
    - Support vector machine
    - Multilayer perceptron
    - Random Forest
    - Gradient Boosting
  - Model selection
  - Final training, submission, and results
- [best_model.ipynb](https://github.com/KevinyWu/titanic_survival_prediction/blob/main/best_model.ipynb): streamlined notebook that tunes and improves upon random forest, the best model from titanic.ipynb
  - see models/best_model.pkl for model
  - see submissions/best_submission.csv for submission

The random forest model scored top 2% of 13400 submissions.
