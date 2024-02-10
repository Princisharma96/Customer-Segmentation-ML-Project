Online Retail Data Analysis

Abstract

Retail businesses engage in selling products or services to customers for personal consumption. They operate through various channels including in-store, online, and over the phone, with a focus on customer satisfaction and profitability. This is supported by strategic pillars such as marketing, management, finance, and operations. Customer segmentation, the process of dividing customers into groups with similar characteristics, is crucial for efficient marketing. It can be based on transactions, demographics, geography, and psychographics, helping businesses expand markets, target production, enhance competitiveness, and increase customer satisfaction. This project reviews transaction history from an online business using association algorithms and K-means clustering to identify frequently purchased items and customer segments, recommending advertising strategies to boost revenue and maintain customer satisfaction.

Introduction

Business and Data Mining Goals
Retailers aim to enhance marketability and understand customer purchase practices, especially in e-commerce. Classifying customers by purchase behavior aids in crafting effective marketing strategies to improve revenue, understand customer habits, target marketing efforts, and identify customer segments for strategic management.

Business Goals
Improve organizational profits by identifying customer buying behaviors to predict future patterns.
Recommend marketing strategies to enhance purchasing behaviors across categories.
Data Mining Goals
Segment customers based on various factors and correlate them based on variables.
Identify outliers, clean the dataset, and develop models to predict future customer buying patterns.
Data Description and Data Preparation

The dataset, sourced from Kaggle for an e-commerce store covering 2010-2011, contains approximately 500,000 data rows from 4000 customers across 37 countries, with categorical and numerical variables. New columns were added for Total Revenue, Canceled Quantity, Canceled Cost, and Return Customer to aid in analysis and model building. Data preprocessing involved filling missing values and creating new predictive columns using Excel.

Exploratory Data Analysis and Data Visualization

Exploratory Data Analysis (EDA) revealed buying patterns, outliers, trends, and relationships among variables. Analysis showed the UK/Europe as the largest customer base, with the UK leading in bulk orders. Customer-based quantity analysis indicated a need to focus on frequent consumers for consistent revenue. Further, analysis of average sales, revenue collection by country, quarterly sales, and monthly sales highlighted key trends and informed the choice of association analysis for customer segmentation.

Data Mining Solutions

K-Means Clustering
K-means clustering segmented customers into groups based on purchasing history using RFM analysis (Recency, Frequency, Monetary Value). Preprocessing checked for K-means assumptions, and the Elbow method helped determine the optimal number of clusters. Three clusters were identified, characterized by their buying patterns and customer attributes, leading to actionable insights for targeted marketing.

Association Rules
The Apriori algorithm was applied to identify relationships between purchased items, generating frequent item sets and establishing strong association rules based on confidence and lift ratio metrics. This analysis suggested targeted product recommendations to enhance cross-selling opportunities.

Recommendation

Marketing strategies tailored to bronze, silver, and gold customer segments can leverage these insights for targeted promotions, loyalty programs, and personalized offers to increase sales and customer engagement.

Conclusion

The project's analysis, based on association rules and clustering, provides a foundation for improving revenue and customer satisfaction in online retail. Ongoing model updates and incorporation of additional data, such as customer feedback, can enhance the understanding of customer behavior and refine marketing strategies. Future models should adapt to current data trends and incorporate broader customer behavior indicators for comprehensive analysis.
