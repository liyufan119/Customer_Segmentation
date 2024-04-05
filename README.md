## Customer Segmentation and purchase Behavior Analysis 

**The customer segmentation analysis of Oltis retail store utilizing KMeans clustering identified 6  reveals distinct clusters with unique demographic and behavioral characteristics. I outline actionable insights and targeted marketing strategies to enhance customer engagement and drive revenue growth.The analysis follows this workflow:**

### Data Importation and Cleaning
The analysis begins with the importation of two datasets: `marketing_data.csv` which has the main customer data, and `marketing_data_dictionary.csv` that serves as a reference for understanding the data attributes. Preliminary data cleaning is performed to ensure data quality and usability. This includes handling missing values, correcting data types, and removing outliers where necessary.

### Exploratory Data Analysis (EDA)
An extensive EDA is conducted to understand the dataset's structure, content, and relationships:
- **Distribution Analysis:** I examine the distribution of key variables to understand the demographics of our customer base, such as age, income, and family size.
- <img width="400" alt="distribution_age" src="https://github.com/liyufan119/Customer_Segmentation/assets/71167199/8add610b-55a8-4bc5-918a-04dc9a3e3c23">
- <img width="400" alt="distribution_income" src="https://github.com/liyufan119/Customer_Segmentation/assets/71167199/3530bd7e-13dc-48b0-8708-3f4a0070f291">
<img width="400" alt="distribution_marital" src="https://github.com/liyufan119/Customer_Segmentation/assets/71167199/90cef683-9dc1-4c4e-9cf8-677100896c49">
<img width="400" alt="disrribution_education" src="https://github.com/liyufan119/Customer_Segmentation/assets/71167199/ee11f336-4891-4636-b41b-962e9ac2b442">



- **Correlation Analysis:** I explore the relationships betIen different variables to identify potential correlations that could influence purchase behaviors.

### Customer Segmentation
One of the core components of this analysis is segmenting customers to identify distinct groups based on their purchasing behaviors. This involves:
- **Feature Selection:** Identifying which features are most relevant to purchasing behavior.
- **KMeans Clustering:** Applying KMeans clustering algorithm to segment the customer base into distinct groups. The number of clusters is determined based on the Elbow method, ensuring optimal segmentation.

### Analysis of Purchase Behaviors
With customer segments identified, I delve into analyzing the purchasing patterns within each segment:
- **Segment Profiling:** Each customer segment is profiled based on their demographic information and purchasing behaviors, providing a clear picture of each segment's characteristics.
- **Purchasing Patterns:** I examine the purchasing patterns within each segment, focusing on product categories, spending habits, and responsiveness to marketing campaigns.

### Visualization of Findings
Throughout the analysis, visualizations play a crucial role in conveying insights:
- **Demographic Distributions:** Histograms and bar charts are used to visualize the distribution of demographic variables.
- **Cluster Visualization:** Cluster distributions are visualized using scatter plots, highlighting the segmentation within the customer base.
- **Purchasing Trends:** Heatmaps and line charts are employed to showcase purchasing trends over time and across different segments.
Purchase trend among different groups


### Insights and Recommendations
The culmination of the analysis is a set of actionable insights and recommendations tailored to each customer segment. These insights are aimed at helping businesses tailor their marketing strategies to meet the unique needs and preferences of each segment, enhancing customer engagement and optimizing marketing efforts.
    - **Targeted Marketing**: For Cluster 1 (Affluent Wine Enthusiasts), focus on premium wine offerings and personalized marketing strategies to maintain their high engagement levels.
    - **Engagement Strategies:** Develop targeted campaigns for Cluster 3 (Upper Middle-aged Heavy Spenders) to promote meat products and in-store experiences, leveraging their heavy spending behavior.
    - **Segment-specific Promotions:** Tailor promotions for Cluster 2 (Young Frugal Shoppers) to attract them towards higher-value purchases while considering their budget-conscious approach.
    - **Customer Retention:** Implement strategies to retain customers in Cluster 4 (Elderly Conservative Shoppers) by offering value-driven promotions and products aligned with their conservative spending habits.
    - **Segmented Offerings:** Develop diverse product offerings and promotions that appeal to the balanced spending behavior of customers in Cluster 0 (Middle-aged Moderate Spenders) and Cluster 5 (Middle-aged Balanced Spenders).

**Continuous Analysis:** Regularly update customer segmentation models based on changing trends and customer preferences to ensure effective targeting and marketing strategies.

## Conclusion
This detailed analysis of customer purchase behaviors leverages data science techniques to uncover insights that can drive strategic business decisions. By understanding the underlying patterns in customer data, businesses can better align their offerings with customer needs, ultimately leading to improved customer satisfaction and loyalty.


