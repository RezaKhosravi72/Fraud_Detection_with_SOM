# Self-Organizing Map for Fraud Detection

## Project Overview:

The **"Self-Organizing Map for Fraud Detection" project** utilizes a Self-Organizing Map (SOM) to identify potential instances of fraud in credit card applications. The SOM is a type of artificial neural network that excels at capturing patterns in high-dimensional data, making it well-suited for detecting outliers in a dataset.

## Key Steps and Components:

1. **Data Import and Preprocessing:**
- The project begins by importing customer data from credit card applications.
- The dataset is preprocessed, including feature scaling using MinMaxScaler, which scales the features to a specific range (0 to 1).
2. **Training the SOM:**
- A MiniSom package is utilized to create and train the Self-Organizing Map.
- The SOM is initialized with specific dimensions (10x10) and input length.
- Weights are randomly initialized.**
- The SOM is trained using random data for a specified number of iterations.
3. **Visualizing the Results:**
- To visualize the SOM's output, we use **the distance map** to create a visual representation.
- The visualization highlights regions of the map with different colors.
- Actual data points are plotted on the map, with markers distinguishing between fraudulent and non-fraudulent applications.
4. **Finding the Frauds:**
- The SOM is employed to map and cluster data.
- Potential fraudulent applications are identified based on their proximity to specific clusters on the SOM.
5. **Printing Fraudulent Client IDs:**
- The project concludes by printing the IDs of customers associated with potential fraudulent applications.


## Conclusion:

The **"Self-Organizing Map for Fraud Detection"** project offers a practical application of machine learning and SOMs for fraud detection, which can be crucial for financial institutions. This project demonstrates the ability to uncover patterns and identify outliers within a dataset, which is a fundamental skill in data analysis and fraud prevention.
