**Mobile Price Prediction using Machine Learning**
**Overview**
This project aims to predict mobile phone prices based on key features like battery power, RAM, ratings, and camera specifications. Using Linear Regression and K-Nearest Neighbors (KNN) Regression, we analyze the relationships between these features and price. The dataset is cleaned, explored through visualizations, and then used to train the models. Finally, we evaluate their performance using standard metrics to determine which model gives the most accurate predictions.

**Dataset Features**
The dataset includes important specifications that influence mobile phone pricing:

Battery Power – The phone’s battery capacity

RAM – The amount of memory (in MB)

Ratings – User ratings for the phone

Mobile Size – The screen size of the phone

Selfi Cam – Megapixels of the front camera

Primary Cam – Megapixels of the rear camera

Price – The actual price of the phone (target variable)

**Technologies Used**
Python for data processing and modeling

Pandas & NumPy for handling and analyzing data

Scikit-Learn for training machine learning models

Seaborn & Matplotlib for data visualization

**How It Works**
Load and preprocess the dataset – Handle missing values and standardize features.

Explore the data – Use visualizations to understand the relationships between features.

**Train two machine learning models:**

Linear Regression

K-Nearest Neighbors (KNN) Regression

Evaluate the models using key metrics like:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score (used to calculate accuracy as a percentage)

Compare performance – Determine which model provides the best price predictions.

**Model Accuracy**
Linear Regression Accuracy: 40%

KNN Regression Accuracy: 67.6%

**Running the Project**
To run the model on your own system:
Install the necessary libraries:

pip install pandas numpy scikit-learn matplotlib seaborn
**Run the script:**

python mobile_price_prediction.py

**Conclusion**
This project helps in understanding how different mobile features contribute to pricing and evaluates which machine learning model performs best for price prediction. It provides insights that could be useful for smartphone manufacturers, retailers, and consumers looking for price estimations based on specifications.

**License**
This project is open-source and available for learning, modification, and improvement.
