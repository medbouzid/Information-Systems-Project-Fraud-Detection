# Information-Systems-Project-Fraud-Detection

The Mini Project-Fraud Detection involves the exploration and cleaning of data related to clients and their consumption patterns, with the ultimate goal of detecting fraudulent activities. The project utilizes Python and several libraries for data manipulation and analysis.

## Project Workflow
### Data Import and Exploration:

Import necessary libraries, including NumPy, Pandas, Seaborn, and Matplotlib.
Load client and consumption data from CSV files.

### Client Data Cleaning:

Inspect and clean the client dataset.
Drop unnecessary columns.
Convert specific columns to appropriate data types.
Handle missing values.


### Feature Engineering:

Create a new "Consomation" column based on the consumption indexes.
Generate ratios for different consumption levels.
Create a correlation matrix to analyze feature relationships.

### New Merge (After Cleaning):

Merge the cleaned consumption and client datasets.

### First Approach (Quarterly Analysis):

Divide observations into four groups corresponding to quarters.
Perform statistical operations on each group, calculating mean, standard deviation, min, max, variance, and median.
Drop unnecessary columns and duplicates.
Feed the data into anomaly detection models (Isolation Forest, Local Outlier Factor, DBSCAN) for each quarter.

### Second Approach (Full Data Analysis):

Repeat the statistical operations on the entire dataset.
Bring additional data from other CSV files.
Shuffle the data and drop duplicates.
Feed the data into anomaly detection models (Isolation Forest, Local Outlier Factor, DBSCAN).

### Model Evaluation:

Evaluate the performance of anomaly detection models using confusion matrices, F1-score, and AUC.
Deep Learning Approach:

### Utilize an AutoEncoder model for anomaly detection.
Train the model on the standardized data.
Visualize the anomaly scores and determine the optimal threshold for classification.
Evaluate the model's performance using confusion matrix, F1-score, and AUC.
Conclusion:

### Summarize the findings and observations from the anomaly detection models.
Reflect on the strengths and limitations of the models used.
Discuss potential improvements or alternative approaches for fraud detection.


Overall, the project demonstrates a comprehensive exploration of data cleaning, feature engineering, and anomaly detection techniques for fraud detection in client consumption patterns.
