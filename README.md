# Car Price Prediction of Old Used Cars

## Justification for Choosing the Project
In today's world, car ownership is prevalent, but there are risks associated with selling used cars, such as fraudulent activities where cars are bought at low prices and sold at significantly higher prices, resulting in losses for sellers. To address this issue, we developed a website to provide users with accurate valuation of their cars, thus mitigating fraudulent activities and ensuring fair transactions. Our machine learning model is based on the Random Forest Classification algorithm.

## Methodology

### Step 1: Data Cleansing
- Removed rows with NULL values from the dataset.

### Step 2: Correlation Analysis
- Utilized heat map graph from Seaborn to identify correlations among features.
- Found that selling price and present price have the highest correlation.

### Step 3: Model Fitting
- Implemented the Random Forest algorithm to train the model on the dataset.

### Step 4: Hyperparameter Tuning
- Utilized Randomized Search CV to find the best combination of hyperparameters for optimal model performance.

### Step 5: Evaluation Metrics
- Calculated Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) to evaluate model performance.
- Achieved an accuracy of 84%.

## Conclusion
Through our project, we aim to provide users with a reliable tool to accurately predict the price of old used cars, thereby facilitating fair transactions and minimizing the risk of fraudulent activities in the used car market.


![image](https://github.com/RithikSuthan/Car-Price-Prediction/assets/72434153/2b137db5-97ae-4e06-b7e5-82de2258a640)
