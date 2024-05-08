# Iron-purity
Introduction:
- This ML project aims to use Regression to determine the purity of iron.
- The dataset pertains to a flotation plant utilized for concentrating iron ore, a common process in mining plants. The goal is to forecast the percentage of Silica in the final product, which is the concentrate of iron ore and its impurity (Silica percentage). Despite the Silica percentage being measured (last column), it's a lab measurement, taking at least an hour for process engineers to obtain. Thus, the aim is to predict the impurity amount in the process.

Model Training:
- Machine Learning models are developed to forecast iron purity.
- The initial examination includes reviewing rows, summarizing columns, basic statistics, data types, and managing missing values.
- Data preparation and cleaning involve addressing missing values and potential transformations.
- The Exploratory Data Analysis (EDA) section examines independent variables and their impact on the Silica concentrate percentage.
- Scaling is performed using MinMaxScaler, and the data is split into train and test sets using train_test_split.
- Model Training: Regression algorithm, Linear Regressor is employed.
- The model is trained using the test dataset and output is predicted.
- Model Evaluation: Mean squared error, mean absolute error, and Root mean squared error are computed.
- Model Prediction: Predicting the Silica percentage by providing new input values.

Conclusion:
- Industrial Automation: Integrating ML models for iron purity detection into industrial processes can enhance automation and reduce human error, potentially boosting manufacturing efficiency.
- Real-time Monitoring: ML models facilitate real-time monitoring of iron purity during production, enabling quick adjustments, minimizing defective products, and optimizing resource utilization.
