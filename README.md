The regression model was created, trained on the car dataset, and used for predicting car prices. Car price prediction is vital in the automotive industry, enabling various stakeholders to make informed decisions. For manufacturers, it helps in setting competitive prices for new vehicles. Buyers can use price predictions to negotiate better deals, while insurance companies rely on accurate predictions for premium calculations. Furthermore, car price prediction assists in market analysis and forecasting future trends.

The dataset used for this assignment consisted of car features, such as make, model, year, mileage, fuel type, transmission type, number of cylinders, and others. The target variable of interest was the price of the car. The assignment's objective was to predict car prices using machine learning algorithms accurately.

Task 1: Data Preprocessing:
To clean and preprocess the dataset, several steps were involved. These steps included handling missing values, categorical encoding to convert categorical variables into numerical representations, and feature scaling to ensure all features were on a similar scale. In our dataset, we had no null values but had some duplicated rows, which we removed. We have encoded the categorical columns for easy prediction by the regression models.

Task 2: Feature Selection and Engineering:
The process of selecting relevant features for the prediction task was explained. Additionally, feature engineering techniques were employed to enhance the model's performance. These techniques could involve creating new features, transforming existing ones, or combining them to capture additional information. We did not make any new features, but we removed the owner column from the dataset as it had to predict car prices using machine learning algorithms accurately least correlate with the target variable (price) and had the least importance in prediction.

Task 3: Algorithms:
At least two machine learning algorithms were introduced for car price prediction. We used  Random Forest, Gradient Boosting, and other regression algorithms. Each algorithm was briefly explained, highlighting its suitability for the task. Techniques like hyperparameter tuning and cross-validation were discussed for optimizing the models.

Task 4: Training, Evaluation & Selection:
The dataset was split into training and testing sets. The two algorithms were trained on the training set, and their performance was evaluated using mean squared error and R-squared. The results of both algorithms were compared and analyzed to identify the model that performed better in predicting car prices.
