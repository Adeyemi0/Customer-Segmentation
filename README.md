## Project Overview
In this project, I analyzed various demographic variables such as age, gender, location, and socioeconomic factors. Based on the insights gained from the analysis, personalized marketing strategies, tailored product recommendations, and targeted customer experiences will be developed for each segment. The effectiveness of these strategies will be evaluated by measuring customer satisfaction, retention rates, and revenue generated from each segment. The insights gained from this research will empower businesses to better understand their customers, refine their marketing approaches, and ultimately drive sustainable growth and success in the e-commerce industry.

### PROBLEM STATEMENT
The company aims to enhance its marketing efforts by dividing its customer base into distinct segments based on demographic information. The following challenges have been identified:
1. Inefficient targeting: The company lacks a clear understanding of its diverse customer base, resulting in ineffective marketing efforts and inefficient allocation of resources.
2. Limited personalization: The company struggles to provide personalized experiences and tailored recommendations due to a lack of customer segmentation insights.
3. Customer retention issues: The company faces challenges in retaining customers and fostering long-term relationships due to a lack of targeted engagement strategies for different customer segments.

### THE COMPANY'S GOALS
To address the aforementioned challenges, the company has set the following goals:
1. Improved marketing effectiveness: The company aims to enhance its marketing efforts by implementing robust customer segmentation strategies, allowing for precise targeting and personalized messaging.
2. Enhanced customer experiences: The company seeks to deliver personalized experiences to its customers by leveraging customer segmentation insights, resulting in increased customer satisfaction and loyalty.
3. Increased customer retention: The company strives to develop targeted engagement strategies for different customer segments to improve customer retention rates and build long-lasting relationships.

### DETAILS ABOUT THE DATASET
![](https://github.com/Adeyemi0/Customer-Segmentation/blob/main/Images/datase.png)

### CUSTOMER SEGMENTATION PROCESS
The first step in performing customer segmentation is feature selection, where demographic features that are most relevant to the segmentation goals are chosen.
The selected features for this project are:

#### 1. Age/Yearly Income
Age or yearly income can provide insights into the customer's financial situation and purchasing power. It can be useful for segmenting customers based on their spending habits or affordability.

#### 2. Gender
Gender can be relevant for segmentation, especially if there are gender-specific preferences or behaviors related to the products or services offered by the e-commerce store.

#### 3. Marital Status
Marital status can be relevant for segmentation, particularly if the e-commerce store offers products or services that cater to specific marital status categories, such as wedding-related items or family-oriented products.

#### 4. Total Children
The number of children a customer has can be valuable for segmentation, especially for products or services targeted at families or parents.

#### 5. Education
Education level can provide insights into the customer's background, interests, and preferences. It can be relevant for segmenting customers based on their educational attainment or educational needs related to the store's offerings.

#### 6. Occupation
Occupation can be relevant for segmentation, as different occupations may have specific needs or preferences related to the products or services offered by the e-commerce store.

#### 7. Home Ownership
Homeownership status can be relevant, especially if the e-commerce store offers products or services related to home improvement, décor, or maintenance.

The second step in customer segmentation is data normalization, where selected features are normalized to ensure they are on a similar scale. This step is crucial as it prevents features with larger ranges from dominating the clustering process. In this project, standardization is used as the normalization technique. After normalization, the K-Means clustering is employed to perform segmentation. However, before clustering, the number of clusters is determined by the elbow method. The elbow joint method involves iterating over a range of cluster numbers and computing the sum of squared distances (WCSS) within each cluster. The plot of the WCSS values against the number of clusters is used to identify the “elbow point”, indicating the optimal number of clusters. In this case, the value 4 was chosen as the optimal number of clusters. Take a look at the diagram below:

![](https://github.com/Adeyemi0/Customer-Segmentation/blob/main/Images/kmeans.png)

### INSIGHTS FROM CUSTOMER SEGMENTATION
Here are the insights obtained for each segment:
#### Segment 0:
•	Yearly income distribution: The majority of customers in Segment 0 fall into the income range of $30K-$50K, followed by $50K-$70K. There is a smaller proportion of customers in the higher income ranges ($110K-$150K and $150K+).
•	Education distribution: Customers in Segment 0 have a relatively higher proportion of High School and Partial College education levels compared to other segments. The proportion of customers with a Bachelor's Degree is also significant.
•	Occupation distribution: The most common occupation in Segment 0 is Professional, followed by Skilled Manual and Manual. The proportion of customers in Clerical occupations is relatively lower.
•	Homeownership status: The number of homeowners is higher than non-homeowners in Segment 0.
•	Gender distribution: Segment 0 has a higher number of male customers compared to females.
•	Average age and total children: The average age of customers in Segment 0 is approximately 32, and they tend to have an average of 2 children.

![](https://github.com/Adeyemi0/Customer-Segmentation/blob/main/Images/segment%200.png)

#### Segment 1:
•	Yearly income distribution: Customers in Segment 1 have a significantly higher proportion in the income range of $70K-$90K. There are no customers with incomes above $150K in this segment.
•	Education distribution: The majority of customers in Segment 1 have a High School Degree. The proportion of customers with a Graduate Degree is very low.
•	Occupation distribution: Manual occupations have the highest representation in Segment 1, followed by Management and Skilled Manual.
•	Homeownership status: The number of homeowners is higher than non-homeowners in Segment 1.
•	Gender distribution: Segment 1 has a higher number of female customers compared to males.
•	Average age and total children: The average age of customers in Segment 1 is approximately 32, and they tend to have an average of 3 children.

![](https://github.com/Adeyemi0/Customer-Segmentation/blob/main/Images/segment%201.png)

#### Segment 2:
•	Yearly income distribution: Customers in Segment 2 have a relatively balanced income distribution across various ranges, with a slightly higher proportion in the $110K-$150K range.
•	Education distribution: The majority of customers in Segment 2 have either a High School Degree or a Bachelor's Degree.
•	Occupation distribution: Professional occupations have the highest representation in Segment 2, followed by Management and Skilled Manual.
•	Homeownership status: The number of homeowners is higher than non-homeowners in Segment 2.
•	Gender distribution: Segment 2 has a higher number of female customers compared to males.
•	Average age and total children: The average age of customers in Segment 2 is approximately 33, and they tend to have an average of 3 children.

![]()
