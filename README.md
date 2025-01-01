# Marketing-Campaign
Predict Customer Personality to boost marketing campaign by using Machine Learning
## 📂 **Stage 0 : Problem Statement**
Understanding customer behavior deeply is crucial for creating more targeted marketing approaches. By considering various factors in customer interactions, companies can deliver more relevant and personalized experiences, enhancing customer satisfaction and driving overall sales growth. This approach ensures that every product or service offered aligns with customer needs, fostering loyalty and maintaining long-term relationships.

One effective method for analyzing customer characteristics and behavior is clustering. This technique allows companies to group customers into segments with specific similarities, enabling them to develop more tailored and relevant marketing strategies for each group. With more targeted strategies, companies can enhance customer experiences, build stronger relationships, and ultimately gain a competitive edge in the market.

<br>

### Goal
The clustering approach is currently used to analyze customer characteristics and behavior, enabling deeper insights and the delivery of more personalized services. This method facilitates more targeted marketing decisions and enhances sales performance.

### Objectives
1. Develop a Machine Learning clustering model to segment customers based on key characteristics such as shopping habits, preferences, and interactions with the platform.
2. Provide insights to help businesses target more potential customer groups to increase transactions and loyalty.
3. Deliver recommendations for more personalized and effective marketing strategies based on clustering results.
<br>

---

## 📂 **Stage 1 : Data Preparation**
### Data Understanding & Assesment
The dataset consists of 2,240 rows and 30 features. Data understanding and assessment were conducted to ensure the data is ready for analysis and meets analytical requirements. The following steps were performed:
- Checking for missing values in the data
- Identifying duplicate records
- Detecting outliers
- Verifying data types and value consistency
  
<br>
<p align="center">
<img src="https://github.com/user-attachments/assets/f177d31b-4b4d-4db8-b2fc-b2202bbd0355"
 alt="DataMarketingCampaign">
</p>
<br>


## 📂 **Stage 2 : Exploratory Data Analysis**

<p align="center">
<img src="https://github.com/user-attachments/assets/85a0c50f-4b3f-41c9-b9b0-86bfc4da3225"
 alt="BivariateAnalysis">
</p>
<br>
<p>Income and total spending positively correlate with purchase conversion.
Higher income and spending increase the likelihood of purchases.
High-spending customers tend to have better conversion rates, indicating loyalty and higher buying potential. Targeting high-income customers with premium offers is effective.
Lifestyle may influence conversion more than age.
</p>

## 📂 **Stage 3 : Data Preprocessing**
### Feature Encoding
<p align="center">
<img src="https://github.com/user-attachments/assets/18dcec76-2e1a-4e39-a0ec-a150d76b42ed"
 alt="FeatureEncoding">
</p>
<br>
Feature encoding was performed on the education feature.

## 📂 **Stage 4 : Data Modeling**
<p align="center">
<img src="https://github.com/user-attachments/assets/62d86847-cfde-431b-adc7-c3b1dda7674f"
 alt="ElbowMethod">
</p>
<br>

The graph represents the results of the Elbow Method, preceded by PCA to reduce data dimensions while retaining information for optimal model performance.

The graph indicates that the optimal number of clusters is 4, as the decrease in variance becomes insignificant after the 4th cluster, meaning additional clusters do not provide valuable new information.

## 📂 **Stage 5 : Conclusion and Recommendation**
<p align="center">
<img src="https://github.com/user-attachments/assets/f6c92b9d-a96a-4484-8be8-3ec985f6f275)"
alt="UserCluster">
</p>
<br>

1. Cluster 0: Low Spender
Strategy:
Offer special discounts and loyalty programs to encourage transactions. Provide budget-friendly products.
Use email marketing or personalized messages with age-relevant offers (>55 years).
Recommendation: Increase marketing frequency to drive transactions.

2. Cluster 1: Risk of Churn
Strategy:
Provide exclusive offers such as discounts or savings programs (e.g., free shipping) for the next transaction within a limited time.
Run re-engagement campaigns with engaging content across platforms.
Recommendation: Create more personalized re-engagement campaigns with attractive offers to reduce churn risk.

3. Cluster 2: High Spender
Strategy:
Offer loyalty programs with exclusive access to premium products.
Use upselling and cross-selling offers (premium or complementary products) to increase purchase value.
Launch personalized campaigns with engaging user experiences.
Recommendation: Focus on maintaining loyalty through exclusive benefits and relevant offers.

4. Cluster 3: Mid Spender
Strategy:
Provide incentives to increase transaction frequency, such as loyalty programs (membership discounts).
Ensure product offerings and promotions are highly relevant to customer interests.
Offer value bundles to encourage more transactions.
Introduce premium products to boost transaction value.
Recommendation: Increase transaction frequency with special incentives, value bundles, and personalized marketing.
