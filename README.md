## E-commerce Sales Transaction Analysis and Frequent Itemset Mining with PySpark

This Colab notebook provides an in-depth analysis of a UK-based e-commerce sales transaction dataset using both Pandas and PySpark. The analysis covers sales trends, popular products, customer behavior, and profitable customer segments. Additionally, the notebook utilizes the FP-Growth algorithm in PySpark to discover frequent itemsets within customer transactions, revealing potential product associations.

**Key Features:**

* **Data Cleaning and Preprocessing:** Handles missing values, duplicates, and data type conversions to prepare the dataset for analysis.
* **Exploratory Data Analysis:**
    * Analyzes sales trends over time, identifying peak seasons and potential anomalies.
    * Determines the most frequently purchased products and visualizes the results.
    * Investigates customer purchase behavior, calculating average products per transaction.
    * Identifies the most profitable customer segments based on country and individual purchase history.
    * Examines product cancellation rates to understand potential areas for improvement.
* **Frequent Itemset Mining with PySpark:**
    * Leverages the power of PySpark to efficiently process and analyze large datasets.
    * Implements the FP-Growth algorithm to uncover frequent itemsets, revealing potential product associations.
    * Provides insights into customer purchase patterns, which can inform marketing strategies and product recommendations.
* **Cluster Deployment:** Demonstrates the execution of the FP-Growth analysis on a Spark cluster for enhanced scalability and performance.

**Insights and Recommendations:**

The analysis provides actionable insights into the e-commerce business, including:

* Understanding sales trends and seasonality for inventory planning and marketing campaigns.
* Identifying popular products for stock optimization and potential promotions.
* Analyzing customer purchase behavior to personalize offers and recommendations.
* Targeting specific customer segments for increased profitability.
* Addressing product cancellation issues to improve customer satisfaction and reduce lost sales.

**Instructions:**

1. Open the Colab notebook.
2. Upload the provided dataset "Sales Transaction v.4a.csv" to your Google Drive.
3. Execute the code cells sequentially to perform the analysis.

**Note:** The notebook includes code for running the FP-Growth analysis on a Spark cluster. This section requires a configured Spark environment.

**Visualizations:**

The notebook utilizes various visualization libraries like Plotly and Seaborn to present the findings in an easy-to-understand manner, including line charts, bar graphs, and pie charts.
