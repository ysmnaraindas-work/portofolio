**Overview**

Predicting beauty product ratings using Sephora skincare review data.

---

**Background**

In the highly competitive beauty industry, customer satisfaction and product popularity often correlate strongly with product ratings. Analyzing and predicting these ratings provide valuable insights for both manufacturers and customers.

The dataset from Sephora skincare reviews offers a comprehensive view of factors influencing product ratings. This project focuses on leveraging these factors to build a predictive model, enabling better understanding of what drives customer satisfaction. Insights can inform product development, marketing strategies, and customer purchasing decisions.

---

**Objective**

The primary goal is to predict product ratings using machine learning models and explore the relationship between key features and ratings. The analysis addresses:
- Key factors influencing product ratings (e.g., price, active ingredients, categories).
- Correlation between price and popularity.
- Insights into how brand and category affect ratings.

---

**Problem Statement**

Understanding and predicting product ratings pose challenges due to:
1. Complexity of customer preferences.
2. Multiple influencing factors, such as price, active ingredients, and brand reputation.
3. Need to analyze large datasets to identify trends and patterns.
4. Developing an interpretable and accurate model to predict ratings effectively.

---

**Available Data**

The analysis uses the "Sephora Skincare Review Dataset," which includes the following key attributes:
- **Product Information:** `brand_name`, `primary_category`, `secondary_category`, `tertiary_category`, `price`, `active_ingredients`.
- **Customer Feedback:** `rating`, `review_text`, `helpfulness`.
- **Other Features:** `online_only`, `new`, `popularity`.

---

**Steps Overview**

1. **Exploratory Data Analysis (EDA)**
   - Descriptive statistics for key features.
   - Visualization of relationships, e.g., price vs. rating, brand vs. rating.
   - Analysis of missing values and data distribution.

2. **Feature Engineering**
   - Encoding categorical variables (e.g., `brand_name`, `primary_category`).
   - Text processing for `review_text` using NLP techniques.
   - Creating interaction terms, e.g., `price * popularity`.

3. **Data Splitting**
   - Splitting the dataset into training and test sets (e.g., 80-20 split).
   - Stratified sampling to maintain rating distribution across splits.

4. **Model Development**
   - Initial models: Linear Regression, Random Forest, XGBoost.
   - Hyperparameter tuning for optimal performance.
   - Evaluation metrics: RMSE, MAE, R².

5. **Insights and Recommendations**
   - Key drivers of high ratings.
   - Suggested price points for maximizing customer satisfaction.
   - Categories with the highest potential for rating improvement.

6. **Dashboard Creation**
   - Interactive visualizations to display key findings.
   - Graphs for feature importance and model predictions.
   - Filters for category, brand, and price range analysis.

---

**Conclusion**

This project delivers actionable insights into customer preferences and predicts product ratings with high accuracy. By identifying the main factors influencing ratings, stakeholders can optimize product offerings and marketing strategies. Future work may include:
- Incorporating real-time review data for dynamic analysis.
- Expanding the scope to include more product categories and regions.

The final deliverable includes a well-documented codebase, a predictive model, and an interactive dashboard showcasing the analysis results.

