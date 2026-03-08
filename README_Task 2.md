This project predicts emerging consumer trends in the FMCG industry using a hybrid machine learning approach that combines unsupervised learning and supervised learning. Workflow of the Model

Data Collection The dataset containing FMCG sales or consumer behavior data is uploaded and loaded using Pandas for analysis.
Data Preprocessing Missing values are removed and only numerical features are selected. The data is standardized using StandardScaler to ensure that all variables are on the same scale.
Unsupervised Learning – K-Means Clustering The K-Means algorithm is applied to identify hidden consumer segments based on purchasing behavior. Each data point is assigned to a cluster representing a specific consumer pattern.
Hybrid Feature Integration The cluster labels obtained from K-Means are added back to the dataset as a new feature. This allows the prediction model to incorporate consumer segmentation information.
Supervised Learning – Random Forest The dataset is split into training and testing sets. A Random Forest Regression model is trained to predict future trends or sales patterns.
Model Evaluation Model performance is evaluated using: R² Score (prediction accuracy) Mean Squared Error (MSE)
Visualization Graphs are generated to visualize: Consumer clusters Actual vs predicted values Feature importance influencing trend prediction Outcome The hybrid model helps FMCG companies detect emerging consumer trends early, enabling better: product development marketing strategies inventory planning
