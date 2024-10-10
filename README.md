## Table of Contents
1. [Project Overview](#project-overview)
2. [Problem Statement](#problem-statement)
3. [The Company's Goals](#the-companys-goals)
4. [Details About the Dataset](#details-about-the-dataset)
5. [Customer Segmentation Process](#customer-segmentation-process)
   - [Step 1: Feature Selection](#step-1-feature-selection)
   - [Step 2: Data Normalization](#step-2-data-normalization)
6. [Insights from Customer Segmentation](#insights-from-customer-segmentation)
   - [Segment 0](#segment-0)
   - [Segment 1](#segment-1)
   - [Segment 2](#segment-2)
   - [Segment 3](#segment-3)
7. [Customer Persona](#customer-persona)
   - [Segment 0: Young Professionals](#segment-0-young-professionals)
   - [Segment 1: Middle-Income Families](#segment-1-middle-income-families)
   - [Segment 2: Educated Achievers](#segment-2-educated-achievers)
   - [Segment 3: Affluent Females](#segment-3-affluent-females)

## Project Overview
In this project, I used K-Means Clustering to analyze customer demographic variables, like their age, gender, where they live, and how much money they earn. Leveraging the derived insights, I crafted individualized marketing strategies for each group of customers, suggested products they might like, and arranged their shopping experiences to suit their needs better

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
#### Step 1: FEATURE SELECTION
The first step in performing customer segmentation is feature selection, where demographic features that are most relevant to the segmentation goals are chosen.
The selected features for this project are:

#### 1. Age/Yearly Income
Age or yearly income can provide insights into the customer's financial situation and purchasing power. It can be useful for segmenting customers based on their spending habits or affordability.

#### 2. Gender
Gender is relevant due to the potential presence of gender-specific preferences or behaviors associated with the products offered by the e-commerce store.

#### 3. Marital Status
Marital status is particularly significant because the e-commerce store can offer products tailored to specific marital status categories, such as wedding-related items or family-oriented products.

#### 4. Total Children
The number of children a customer has is valuable because products can be targeted at families or parents.

#### 5. Education
Education level can provide insights into the customer's background, interests, and preferences. It can be relevant for segmenting customers based on their educational attainment or educational needs related to the store's offerings.

#### 6. Occupation
Occupation can be relevant for segmentation, as different occupations may have specific needs or preferences related to the products or services offered by the e-commerce store.

#### 7. Home Ownership
Homeownership status is particularly relevant, especially when the e-commerce store offers or intends to offer products related to home improvement, decor, or maintenance

#### Step 2: DATA NORMALIZATION
The second step in customer segmentation is data normalization, where selected features are normalized to ensure they are on a similar scale. This step is crucial as it prevents features with larger ranges from dominating the clustering process. In this project, standardization is used as the normalization technique. After normalization, the K-Means clustering is employed to perform segmentation. However, before clustering, the number of clusters is determined by the elbow method. The elbow joint method involves iterating over a range of cluster numbers and computing the sum of squared distances (WCSS) within each cluster. The plot of the WCSS values against the number of clusters is used to identify the “elbow point”, indicating the optimal number of clusters. In this case, the value 4 was chosen as the optimal number of clusters. Take a look at the diagram below:

![](https://github.com/Adeyemi0/Customer-Segmentation/blob/main/Images/kmeans.png)

### INSIGHTS FROM CUSTOMER SEGMENTATION
Here are the insights obtained for each segment:
#### Segment 0:
*	Yearly income distribution: The majority of customers in Segment 0 fall into the income range of $30K-$50K, followed by $50K-$70K. There is a smaller proportion of customers in the higher income ranges ($110K-$150K and $150K+).
*	Education distribution: Customers in Segment 0 have a relatively higher proportion of High School and Partial College education levels compared to other segments. The proportion of customers with a Bachelor's Degree is also significant.
*	Occupation distribution: The most common occupation in Segment 0 is Professional, followed by Skilled Manual and Manual. The proportion of customers in Clerical occupations is relatively lower.
*	Homeownership status: The number of homeowners is higher than non-homeowners in Segment 0.
*	Gender distribution: Segment 0 has a higher number of male customers compared to females.
*	Average age and total children: The average age of customers in Segment 0 is approximately 32, and they tend to have an average of 2 children.

![](https://github.com/Adeyemi0/Customer-Segmentation/blob/main/Images/segment%200.png)

#### Segment 1:
*	Yearly income distribution: Customers in Segment 1 have a significantly higher proportion in the income range of $70K-$90K. There are no customers with incomes above $150K in this segment.
*	Education distribution: The majority of customers in Segment 1 have a High School Degree. The proportion of customers with a Graduate Degree is very low.
*	Occupation distribution: Manual occupations have the highest representation in Segment 1, followed by Management and Skilled Manual.
*	Homeownership status: The number of homeowners is higher than non-homeowners in Segment 1.
*	Gender distribution: Segment 1 has a higher number of female customers compared to males.
*	Average age and total children: The average age of customers in Segment 1 is approximately 32, and they tend to have an average of 3 children.

![](https://github.com/Adeyemi0/Customer-Segmentation/blob/main/Images/segment%201.png)

#### Segment 2:
*	Yearly income distribution: Customers in Segment 2 have a relatively balanced income distribution across various ranges, with a slightly higher proportion in the $110K-$150K range.
*	Education distribution: The majority of customers in Segment 2 have either a High School Degree or a Bachelor's Degree.
*	Occupation distribution: Professional occupations have the highest representation in Segment 2, followed by Management and Skilled Manual.
*	Homeownership status: The number of homeowners is higher than non-homeowners in Segment 2.
*	Gender distribution: Segment 2 has a higher number of female customers compared to males.
*	Average age and total children: The average age of customers in Segment 2 is approximately 33, and they tend to have an average of 3 children.

![](https://github.com/Adeyemi0/Customer-Segmentation/blob/main/Images/segment%202.png)

#### Segment 3:
*	Yearly income distribution: Customers in Segment 3 have a relatively balanced income distribution across various ranges, with a slightly higher proportion in the $110K-$130K range.
*	Education distribution: The majority of customers in Segment 3 have either a High School Degree or a Bachelor's Degree.
*	Occupation distribution: Professional occupations have the highest representation in Segment 3, followed by Management and Skilled Manual.
*	Homeownership status: The number of homeowners is higher than non-homeowners in Segment 3.
*	Gender distribution: Segment 3 has a higher number of female customers compared to males.
*	Average age and total children: The average age of customers in Segment 3 is approximately 32, and they tend to have an average of 3 children.

![](https://github.com/Adeyemi0/Customer-Segmentation/blob/main/Images/segment%203.png)

### CUSTOMER PERSONA
Creating customer personas is crucial for any business as it helps you understand your target audience at a deeper level. By developing detailed customer personas, you can gain valuable insights into your customers' preferences, behaviors, and needs. Here are the four personas based on the above insights:


#### 1.	Segment 0: Young Professionals
* Name: Emily Thompson
* Age: 28
* Income: $35,000 per year
* Education: Bachelor's Degree
* Occupation: Professional
* Homeownership: Non-homeowner
* Gender: Female
* Total Children: 1
##### Background:
Emily is a 28-year-old young professional with a bachelor's degree. She is driven, career-focused, and values personal growth. Despite having a moderate income, Emily is ambitious and works in a professional role, aiming to advance her career. She is currently a non-homeowner, possibly due to her focus on career development and mobility. As a female with one child, she may be managing a work-life balance and looking for convenient, time-saving solutions.
##### Shopping Preferences: 
Emily is likely to be tech-savvy and prefers online shopping for convenience. She may be interested in products and services that help her save time, improve her work-life balance, or enhance her career. Special deals, promotions, or products designed for young professionals may appeal to her.
##### Marketing Approach: 
To engage with Emily, the e-commerce store should focus on offering time-saving solutions, career-related products, and promotions that resonate with young professionals. Tailored email campaigns, loyalty programs, or product bundles that suit her lifestyle can be effective in capturing her interest.

##### 2.	Segment 1: Middle-Income Families
* Name: Mark and Sarah Johnson
* Age: Mark (35), Sarah (33)
* Income: $80,000 per year
* Education: High School Degree (Mark), Bachelor's Degree (Sarah)
* Occupation: Manual (Mark), Skilled Manual (Sarah)
* Homeownership: Homeowner
* Gender: Male (Mark), Female (Sarah)
* Total Children: 3
##### Background: 
Mark and Sarah are a married couple in their mid-thirties, both working to support their family. Mark has a high school degree and works in a manual labor job, while Sarah holds a bachelor's degree and is employed in a skilled manual occupation. As homeowners with three children, their lives are likely centered around family, and they may be looking for products and services that cater to their family's needs.
##### Shopping Preferences: 
Mark and Sarah may prioritize affordability and value when shopping. They might be interested in products that make their daily lives more convenient and family-friendly. Home improvement, child-related products, and family-oriented deals and promotions could resonate with them.
##### Marketing Approach: 
To connect with Mark and Sarah, the e-commerce store should focus on offering family-oriented products and promotions that align with their budget-conscious approach. Tailored email campaigns, loyalty programs, and product bundles that cater to family needs could capture their attention. Additionally, providing customer support and information that helps with family-related decision-making can enhance their shopping experience.

#### 3.	Segment 2: Educated Achievers
* Name: David Miller
* Age: 32
* Income: $120,000 per year
* Education: Graduate Degree
* Occupation: Professional
* Homeownership: Homeowner
* Gender: Male
* Total Children: 3
##### Background:
David is a 32-year-old professional with a graduate degree. He is ambitious and well-educated, holding a high-paying job that reflects his dedication to his career. As a homeowner with three children, he likely values family life, convenience, and work-life balance. His higher income and education level suggest that he may be more discerning and selective in his purchasing decisions.
##### Shopping Preferences: 
David may prioritize quality and convenience when shopping. He might be interested in products and services that save him time and enhance his family's well-being. He may also appreciate luxury or premium options in various product categories.
##### Marketing Approach: 
To engage with David, the e-commerce store should focus on offering high-quality, time-saving products, and services that enhance his family's lifestyle. Personalized recommendations, loyalty programs, and premium product options can be effective in attracting his attention. Customer reviews and testimonials can also play a crucial role in his purchasing decisions, given his discerning nature.

##### 4. Segment 3: Affluent Females
* Name: Elizabeth Anderson
* Age: 35
* Income: $140,000 per year
* Education: High School Degree
* Occupation: Management
* Homeownership: Homeowner
* Gender: Female
* Total Children: 3
##### Background: 
Elizabeth is a 35-year-old professional with a high school degree who has achieved success in a management role, earning a substantial income. As a homeowner and a mother of three children, she likely values a balance between her demanding career and family life. Despite her education level, she has managed to excel in her profession, demonstrating her determination and leadership abilities.
##### Shopping Preferences: 
Elizabeth may prioritize time-saving solutions and convenience in her shopping choices. Given her higher income, she might appreciate premium or luxury options for both personal and family-related products and services. She is likely to value efficiency and quality.
##### Marketing Approach: 
To engage with Elizabeth, the e-commerce store should focus on offering high-quality, time-saving products and services that cater to her busy lifestyle. Tailored recommendations, loyalty programs, and premium product options can be effective in capturing her interest. Highlighting product quality, convenience, and the potential for enhancing work-life balance can resonate with her.
