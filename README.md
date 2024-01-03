## Data Science Intern  
**CODSOFT** | *15 December 2023 to 15 January 2024*

# Project Highlights:
## Titanic Survival Prediction Project

## Overview
The Titanic Survival Prediction project aimed to predict passenger survival rates aboard the Titanic using machine learning algorithms. Leveraging the Titanic dataset encompassing passenger information, the project delved into exploratory data analysis (EDA), feature engineering, model training, and evaluation.

## Key Steps and Achievements
1. **Data Exploration and Analysis:** Conducted in-depth exploration of passenger attributes such as age, gender, ticket class, fare, and cabin details. Utilized statistical summaries and visualizations to understand relationships and trends within the dataset.
2. **Preprocessing and Feature Engineering:** Processed the dataset by handling missing values, scaling numerical features, and encoding categorical variables for modeling purposes.
3. **Model Building and Evaluation:** Employed three classification algorithms - Logistic Regression, K Nearest Neighbors (KNN), and Support Vector Classifier (SVC) - to predict survival outcomes. Assessed model performance using precision, recall, F1-score, and accuracy metrics.
4. **Model Deployment and Persistence:** Saved the best-performing KNN model and established functionality to load the model for predictions.
5. **Prediction App Development:** Created a prediction interface using Streamlit, enabling users to input passenger information and receive survival predictions based on the trained model.

## Performance and Insights
- **Model Performance:** The K Nearest Neighbors (KNN) algorithm emerged as the top-performing model with an accuracy of 83%, showcasing balanced precision and recall for both survivor and non-survivor classes.
- **Insights:** The model demonstrated effectiveness in predicting survival likelihood, providing insights into passenger survival probabilities based on their attributes.

## Future Improvements
- Enhance the prediction app's interface and user experience.
- Explore additional feature engineering techniques for improved model performance.
- Consider ensemble methods or fine-tuning hyperparameters to further enhance model accuracy.

## Project Resources
- **Dataset Link:** [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **GitHub Repository:** [Titanic Survival Prediction Repo](https://github.com/IBakare/CODSOFT-/tree/main/Titanic%20Survival%20Prediction)

## Conclusion
The Titanic Survival Prediction project successfully constructed a predictive model capable of estimating passenger survival rates. Through comprehensive analysis and modeling, the project offered insights into factors influencing survival outcomes aboard the Titanic.

## Movie Genre Classification Project

## Overview
The Movie Genre Classification project aimed to predict movie genres based on various features such as release year, duration, director, and actors. Utilizing IMDb India movie data, the project involved data exploration, preprocessing, feature engineering, model training, and evaluation to predict movie genres accurately.

## Key Steps and Achievements
1. **Data Collection and Preparation:** Accessed IMDb India movie dataset via Kaggle API, encompassing movie details like release year, duration, genres, ratings, director, and cast information.
2. **Exploratory Data Analysis (EDA):** Conducted extensive EDA to understand the distribution and relationships among features, visualizing movie ratings, genre frequencies, and other relevant trends.
3. **Data Cleaning and Preprocessing:** Addressed missing values in columns like 'Year', 'Duration', 'Rating', 'Votes', 'Director', 'Actor 1', 'Actor 2', and 'Actor 3'. Applied transformations, such as encoding categorical variables and handling missing data.
4. **Feature Engineering:** Utilized one-hot encoding for genre categories, label encoding for categorical variables, and feature extraction from 'Duration' and 'Year' columns.
5. **Model Building and Selection:** Explored various regression models (Random Forest, Gradient Boosting, Decision Tree) using hyperparameter tuning via RandomizedSearchCV for predicting movie ratings.

## Performance and Insights
- **Model Evaluation:** Identified the best-performing models with their respective hyperparameters:
    - Random Forest: n_estimators=300, min_samples_split=5, min_samples_leaf=4, max_depth=20
    - Gradient Boosting: n_estimators=200, min_samples_split=2, min_samples_leaf=4, max_depth=5, learning_rate=0.1
    - Decision Tree: min_samples_split=10, min_samples_leaf=4, max_depth=10
- **Insights:** Discovered that the movie's release year, duration, and the cast (director, actors) play crucial roles in predicting movie genres. Higher accuracy was achieved by ensemble methods.

## Future Improvements
- Experiment with additional feature engineering techniques, like text analysis for director or actor names.
- Explore ensemble methods or advanced deep learning models for enhanced accuracy in genre prediction.
- Develop a user-friendly interface for genre prediction, leveraging the trained model.

## Project Resources
- **Dataset:** [IMDb India Movies Dataset](https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies)
- **GitHub Repository:** [Movie Genre Classification Repo](https://github.com/IBakare/CODSOFT-/tree/main/Movie%20Rating%20Prediction)

## Conclusion
The Movie Genre Classification project successfully built predictive models to identify movie genres based on various movie attributes. Through comprehensive analysis and modeling, the project provided insights into the crucial factors influencing movie genre predictions in the IMDb India movie dataset.

## Iris Flower Classification Project

## Overview
The Iris Flower Classification project focuses on building a machine learning model to classify iris flowers into different species based on their sepal and petal measurements. The project involves data exploration, preprocessing, model training using the K-Nearest Neighbors (KNN) algorithm, and evaluation of the model's performance.

### Libraries and Tools Used
- Python libraries:
  - NumPy, Pandas, Seaborn, Matplotlib
  - Scikit-learn: ColumnTransformer, SimpleImputer, StandardScaler, OneHotEncoder, MinMaxScaler, LabelEncoder, Pipeline, KNeighborsClassifier, SVC, RandomForestRegressor, GradientBoostingRegressor, DecisionTreeRegressor
- Kaggle API for dataset retrieval
- Joblib for model persistence

### Data Exploration and Preprocessing
- Imported the Iris dataset from Kaggle, comprising measurements of sepal length, sepal width, petal length, petal width, and corresponding species (setosa, versicolor, virginica).
- Explored dataset shape, columns, data types, summary statistics, and missing values.
- Utilized Seaborn for visualizations, including pair plots, box plots, and violin plots to understand data distributions and relationships among features.

### Model Training and Evaluation
- Defined features (sepal length, sepal width, petal length, petal width) and target variable (species) for classification.
- Split the dataset into training and testing sets.
- Trained a KNN classifier using the training data and evaluated its performance on the test set.
- Generated a detailed classification report showcasing precision, recall, F1-score, and accuracy for each class (setosa, versicolor, virginica).

### Model Performance and Analysis
- The KNN model achieved outstanding performance metrics:
  - Perfect precision, recall, F1-score (1.00) for all classes on the test set.
  - 100% accuracy, indicating flawless predictions on the test data.
- Implications suggest the model accurately distinguished between the iris species based on provided features.

### Model Persistence and Deployment
- Saved the trained KNN model using Joblib for future use.
- Demonstrated model deployment by loading the saved model and making predictions on new data samples.
- Exported predictions to a CSV file for further analysis or usage.

## Future Steps and Improvements
- Explore cross-validation techniques to validate model generalization.
- Experiment with other algorithms or ensemble methods to compare performance.
- Enhance documentation and code comments for better understanding and maintainability.

## Project Files and Resources
- [Iris Dataset Link](https://www.kaggle.com/datasets/arshid/iris-flower-dataset)
- [GitHub Repository](https://github.com/IBakare/CODSOFT-/tree/main/Iris%20Flower%20Classification)

## Conclusion
The Iris Flower Classification project successfully built a KNN-based model demonstrating exceptional accuracy in classifying iris flowers into species. The model effectively learned patterns from the provided features, showcasing strong potential for accurate predictions.


#### Sales Prediction Using Python
- Implemented machine learning techniques to forecast future sales, considering various factors like advertising expenditure and audience segmentation.
- Utilized Python to analyze and interpret data, optimizing advertising strategies for maximizing sales potential.
- Employed regression models to predict product purchases and support business decision-making.
- [Dataset Link](https://www.kaggle.com/code/ashydv/sales-prediction-simple-linear-regression/input)
- [GitHub Repo](https://github.com/IBakare/CODSOFT-/tree/main/Sales%20Prediction)

#### Credit Card Fraud Detection
- Developed a fraud detection model using classification algorithms to identify fraudulent credit card transactions.
- Processed and normalized transaction data while addressing class imbalance issues.
- Evaluated model performance using precision, recall, and F1-score metrics.
- Investigated oversampling and undersampling techniques for enhanced results.
- [Dataset Link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- [GitHub Repo](https://github.com/IBakare/CODSOFT-/tree/main/Credit%20Card%20Fraud%20Detection)

