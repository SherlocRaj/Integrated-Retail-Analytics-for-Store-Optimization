# **Project Name** - Integrated Retail Analytics for Store Optimization

##### **Project Type** - Unsupervised / Regression / EDA
##### **BY: RAJ SHEKHAR**

# **Project Summary -**

This project presents a comprehensive, data-driven framework to address critical operational challenges faced by a retail organization, including inaccurate demand forecasting, inefficient inventory management, and untargeted marketing strategies. By leveraging a rich dataset comprising sales transactions, store attributes, and external economic factors, this analysis successfully develops an integrated solution that combines exploratory data analysis, advanced feature engineering, supervised machine learning for forecasting, and unsupervised learning for strategic segmentation.

The project began with a thorough data wrangling phase, where three distinct datasets—sales, features, and stores—were meticulously cleaned, merged, and prepared for analysis. A key insight from this initial phase was the interpretation of missing `MarkDown` data, which was correctly identified not as an error but as an indicator of no promotional activity and consequently imputed with zero. Other missing economic data points were handled using median imputation to maintain data integrity.

An extensive Exploratory Data Analysis (EDA) phase, involving over fifteen visualizations, uncovered several crucial business insights. We confirmed strong seasonal sales patterns with significant peaks during the Thanksgiving and Christmas holidays, a clear performance hierarchy where Type 'A' stores consistently outperformed Types 'B' and 'C', and a statistically significant positive correlation between a store's size and its sales volume. A particularly powerful discovery was that the highest sales weeks were not driven by heavy markdowns, suggesting that promotions should be used surgically during off-peak seasons rather than during periods of high organic demand. These visual findings were then rigorously validated through formal hypothesis testing using t-tests, ANOVA, and Pearson correlation tests.

To build a robust forecasting model, a sophisticated feature engineering process was undertaken. New features were created to capture complex patterns, including sales lags and rolling averages to represent recent performance momentum, and sine/cosine transformations to effectively model the cyclical nature of weekly and monthly seasonality.

Three distinct machine learning models—Random Forest, XGBoost, and Ridge Regression—were implemented to forecast weekly sales. Using a time-series-aware cross-validation strategy, each model was rigorously evaluated and tuned. The **Tuned Random Forest Regressor** was selected as the final model, demonstrating superior performance by achieving an **R-squared value exceeding 0.96**. This high level of accuracy establishes the model as a reliable tool for short-term inventory and operational planning.

Beyond forecasting, the project implemented unsupervised learning to provide deeper strategic insights. **K-Means Clustering** was used to successfully segment the 45 stores into four distinct clusters based on their sales patterns, size, and promotional activity, enabling the development of personalized marketing and operational strategies. Furthermore, an **anomaly detection** system was developed using time-series decomposition to automatically flag weeks with unusual sales for further investigation.

In conclusion, this project successfully translates complex historical data into a powerful, forward-looking strategic asset. It delivers not just a predictive model, but a complete analytical framework that empowers the retail organization to optimize inventory, personalize marketing, and make more intelligent, data-driven decisions to enhance overall performance and profitability.

