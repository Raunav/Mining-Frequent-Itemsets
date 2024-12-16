# Mining Frequent Itemsets using Apriori and PCY Algorithms
## Project Description
This project involves implementing and applying the **Apriori** and **PCY algorithms** to identify frequent itemsets in the **Kaggle Groceries Dataset**. The primary goal is to perform **market basket analysis** by exploring customer purchasing behaviors and generating association rules using specific thresholds for support and confidence. Additionally, a performance comparison between the Apriori and PCY algorithms is conducted.

## Objectives

1. **Apriori Algorithm Implementation**
   - Mine frequent itemsets with a minimum support threshold of 0.12%.
   - Generate association rules with a confidence threshold of 6.0%.
   - Evaluate the rules using metrics such as support, confidence, and lift.
   
2. **PCY Algorithm Implementation**
   - Mine frequent itemsets with similar thresholds for comparison.
   - Analyze the performance differences between Apriori and PCY algorithms.

3. **Insights and Metrics**
   - Explore the significance of support, confidence, and lift in association rule mining.
   - Understand the utility of these rules in market basket analysis for actionable insights.

## Dataset

The **Kaggle Groceries Dataset** contains:
- Customer IDs
- Dates of purchase
- Item descriptions

The dataset helps uncover purchasing patterns for applications in recommendation systems, inventory management, and marketing.

## Key Results

- **Frequent Itemsets:** Discovered using the Apriori algorithm with specified thresholds.
- **Association Rules:** Evaluated based on support, confidence, and lift metrics.
- **Performance Analysis:** Compared runtime and efficiency of Apriori and PCY algorithms.

## Tools and Libraries Used

- **Python** for implementation
- **NumPy** and **Pandas** for data manipulation
- **Matplotlib** and **Seaborn** for data visualization
- **MLxtend** for association rule mining

## Bonus: Performance Comparison

Implemented the **PCY algorithm** and compared it with Apriori for efficiency and scalability with the given dataset and thresholds.

## How to Run

1. Clone this repository.
2. Install the required libraries: `pip install numpy pandas matplotlib seaborn mlxtend`.
3. Load the dataset in the provided script or notebook.
4. Execute the Apriori and PCY implementations.
5. View visualizations and performance metrics.

## Insights from the Analysis

- **Support, Confidence, and Lift:** These metrics provide a structured way to measure the strength of rules derived from the dataset.
- **Market Basket Analysis:** Helps businesses understand customer behavior and create targeted recommendations and promotions.
- **Algorithm Performance:** PCY offers an efficient alternative for handling larger datasets with lower memory requirements.

## References

- Kaggle Groceries Dataset
- Market Basket Analysis and Association Rule Mining
- Apriori Algorithm and PCY Algorithm Theoretical Insights

---
**Author:** Raunav Sharma  
**Date:** November 12, 2023

