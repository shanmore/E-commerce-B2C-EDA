# E-commerce-B2C-EDA

**Target :**

Analyze user behavior across different page categories, engagement time, and other features. Gain insights into factors influencing purchase decisions and identify areas for optimization. Formulate some hypotheses on the dataset and check if they are correct.

**Shopping dataset:**

1. Preprocessing of data as required
2. Univariate Analysis: Plot histograms or box plots for each numerical feature to identify outliers and distribution shapes.
3. Correlation Analysis: Calculate correlations between numerical features to identify potential relationships.
4. Visualizations: Use scatter plots, pair plots, or heatmaps to visualize relationships between numerical features.
5. Class Distribution: Check the distribution of the target variable ('Revenue') to understand class balance.
6. Summarize page views, durations, and bounce/exit rates for each page category.
7. Analyze SpecialDay distribution and its correlation with Revenue.
8. Generate a binary feature indicating whether the user visited all three page categories.
9. Explore PageValues distribution and its relationship with TrafficType, VisitorType, and Region.
10. Investigate user session lengths and their impact on conversion rates.
11. Group users based on VisitorType, OperatingSystems, and Region to identify potential differences in behavior and conversion rates.
12. Segment users based on TrafficType and analyze their engagement patterns and purchase probability.

**Campaign Dataset**

1. EDA on various features and columns.
2. Feature engineering for the required analysis.
3. Remove extreme values if required.

**Hypothesis testing:**
1. Is income of customers dependent on their education
2. Do higher income people spend more (take in account spending in all categories together)
3. Do couples spend more or less money on wine than people living alone (set 'Married','Together':'In couple' and 'Divorced','Single','Absurd','Widow','YOLO':'Alone')
4. Are people with lower income are more attracted towards campaign or simply put accept more campaigns. ( create two income brackets one below median , other above median income and create a column which tells if they have ever accepted any campaign)
