# Customer Segmentation Analysis

This repository contains code and data for performing customer segmentation analysis on the Mall Customers dataset. The analysis aims to identify distinct customer segments based on their annual income, spending score, and other attributes.

## Dataset

The dataset used for this analysis is called 'Mall_Customers.csv'. It contains information about customers' demographics and purchasing behavior in a shopping mall. The columns in the dataset include:

- CustomerID: Unique identifier for each customer
- Gender: Gender of the customer (Male/Female)
- Age: Age of the customer
- Annual Income (k$): Annual income of the customer in thousands of dollars
- Spending Score (1-100): Score assigned to the customer based on their spending behavior and purchasing patterns

## Analysis Code

The main code file for the customer segmentation analysis is 'customer_segmentation_analysis.py'. It performs the following steps:

1. Load the dataset using pandas.
2. Preprocess the data by handling missing values, encoding categorical variables, and scaling numerical features if necessary.
3. Perform customer segmentation using a clustering algorithm (K-means in this example).
4. Visualize the results with various plots, including scatter plots, bar plots, violin plots, and more.

## Instructions

To run the customer segmentation analysis:

1. Clone this repository to your local machine.
2. Ensure you have the necessary dependencies installed (pandas, scikit-learn, seaborn, matplotlib).
3. Place the 'Mall_Customers.csv' dataset in the same directory as the code file.
4. Run the 'customer_segmentation_analysis.py' file using Python.

Feel free to modify the code to suit your specific needs or experiment with different clustering algorithms and visualization techniques.

## Results

The analysis results in the identification of distinct customer segments based on their characteristics and behavior. The clusters are labeled with meaningful names, such as 'Low Income, Low Spending' and 'High Income, High Spending', to provide insights into each segment's characteristics.

The analysis visualizes the clusters using scatter plots, bar plots, violin plots, and other visual representations, allowing for a comprehensive understanding of the customer segmentation.

## License

The code and dataset in this repository are available under the [MIT License](LICENSE). You are free to use, modify, and distribute the code and data for both commercial and non-commercial purposes.

Please refer to the [LICENSE](LICENSE) file for more details.

