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
>	Yearly income distribution: The majority of customers in Segment 0 fall into the income range of $30K-$50K, followed by $50K-$70K. There is a smaller proportion of customers in the higher income ranges ($110K-$150K and $150K+).
>	Education distribution: Customers in Segment 0 have a relatively higher proportion of High School and Partial College education levels compared to other segments. The proportion of customers with a Bachelor's Degree is also significant.
>	Occupation distribution: The most common occupation in Segment 0 is Professional, followed by Skilled Manual and Manual. The proportion of customers in Clerical occupations is relatively lower.
>	Homeownership status: The number of homeowners is higher than non-homeowners in Segment 0.
>	Gender distribution: Segment 0 has a higher number of male customers compared to females.
>	Average age and total children: The average age of customers in Segment 0 is approximately 32, and they tend to have an average of 2 children.

![](https://github.com/Adeyemi0/Customer-Segmentation/blob/main/Images/segment%200.png)

#### Segment 1:
>	Yearly income distribution: Customers in Segment 1 have a significantly higher proportion in the income range of $70K-$90K. There are no customers with incomes above $150K in this segment.
>	Education distribution: The majority of customers in Segment 1 have a High School Degree. The proportion of customers with a Graduate Degree is very low.
>	Occupation distribution: Manual occupations have the highest representation in Segment 1, followed by Management and Skilled Manual.
>	Homeownership status: The number of homeowners is higher than non-homeowners in Segment 1.
>	Gender distribution: Segment 1 has a higher number of female customers compared to males.
>	Average age and total children: The average age of customers in Segment 1 is approximately 32, and they tend to have an average of 3 children.

![](https://github.com/Adeyemi0/Customer-Segmentation/blob/main/Images/segment%201.png)

#### Segment 2:
>	Yearly income distribution: Customers in Segment 2 have a relatively balanced income distribution across various ranges, with a slightly higher proportion in the $110K-$150K range.
>	Education distribution: The majority of customers in Segment 2 have either a High School Degree or a Bachelor's Degree.
>	Occupation distribution: Professional occupations have the highest representation in Segment 2, followed by Management and Skilled Manual.
>	Homeownership status: The number of homeowners is higher than non-homeowners in Segment 2.
>	Gender distribution: Segment 2 has a higher number of female customers compared to males.
>	Average age and total children: The average age of customers in Segment 2 is approximately 33, and they tend to have an average of 3 children.

![](https://github.com/Adeyemi0/Customer-Segmentation/blob/main/Images/segment%202.png)

#### Segment 3:
>	Yearly income distribution: Customers in Segment 3 have a relatively balanced income distribution across various ranges, with a slightly higher proportion in the $110K-$130K range.
>	Education distribution: The majority of customers in Segment 3 have either a High School Degree or a Bachelor's Degree.
>	Occupation distribution: Professional occupations have the highest representation in Segment 3, followed by Management and Skilled Manual.
>	Homeownership status: The number of homeowners is higher than non-homeowners in Segment 3.
>	Gender distribution: Segment 3 has a higher number of female customers compared to males.
>	Average age and total children: The average age of customers in Segment 3 is approximately 32, and they tend to have an average of 3 children.

![](https://github.com/Adeyemi0/Customer-Segmentation/blob/main/Images/segment%203.png)

### CUSTOMER PERSONA
Creating customer personas is crucial for any business as it helps you understand your target audience at a deeper level. By developing detailed customer personas, you can gain valuable insights into your customers' preferences, behaviors, and needs. Here are the four personas based on the above insights:


#### 1.	Segment 0: Young Professionals
Name: Emily Thompson
Age: 28
Income: $35,000 per year
Education: Bachelor's Degree
Occupation: Professional
Homeownership: Non-homeowner
Gender: Female
Total Children: 1
#### Persona Description:
Emily Thompson is a driven and ambitious young professional in her late 20s. She has recently completed her Bachelor's Degree and works in a professional role. With a moderate income, she is focused on building her career and establishing financial stability. Emily values convenience, affordability, and quality. She enjoys socializing, exploring new trends, and staying updated with the latest technology. As a non-homeowner, she is looking for flexible housing options that align with her current lifestyle. Emily is open to opportunities for personal growth and is interested in educational programs that can enhance her skills and advance her career.

#### 2.	Segment 1: Middle-Income Families
Name: Mark and Sarah Johnson
Age: Mark (35), Sarah (33)
Income: $80,000 per year
Education: High School Degree (Mark), Bachelor's Degree (Sarah)
Occupation: Manual (Mark), Skilled Manual (Sarah)
Homeownership: Homeowner
Gender: Male (Mark), Female (Sarah)
Total Children: 3
#### Persona Description:
Mark and Sarah Johnson are a hardworking couple in their early 30s, raising a family with three children. Mark has completed high school and works in a manual occupation, while Sarah has a Bachelor's Degree and works in a skilled manual occupation. They prioritize stability, family well-being, and financial security. As homeowners, they value products and services that cater to their family's needs. Mark and Sarah seek value for money and appreciate brands that offer reliability, durability, and affordability. They are interested in educational resources that can support their children's development and future opportunities.

#### 3.	Segment 2: Educated Achievers
Name: David Miller
Age: 32
Income: $120,000 per year
Education: Graduate Degree
Occupation: Professional
Homeownership: Homeowner
Gender: Male
Total Children: 3
##### Persona Description:
David Miller is a highly educated individual in his early 30s, holding a Graduate Degree. He has a successful career as a professional and earns a substantial income. David values continuous learning, personal growth, and intellectual stimulation. He seeks products and services that align with his sophisticated taste and appreciate brands that offer exclusivity and quality. As a homeowner, David is interested in home improvement and innovative technologies that can enhance his living experience. He invests in his children's education and extracurricular activities to support their well-rounded development

#### 4. Segment 3: Affluent Females
Name: Elizabeth Anderson
Age: 35
Income: $140,000 per year
Education: High School Degree
Occupation: Management
Homeownership: Homeowner
Gender: Female
Total Children: 3
#### Persona Description:
Elizabeth Anderson is a successful and affluent female in her mid-30s. Despite not having a higher education degree, she has achieved career success in a management position and earns a high income. Elizabeth values luxury, elegance, and personalized experiences. She seeks high-end products and services that reflect her sophisticated lifestyle. As a homeowner, she appreciates brands that offer exclusive home décor, fine dining, and premium travel experiences. Elizabeth prioritizes her children's education and extracurricular activities, investing in their future and providing them with a comfortable lifestyle.

### RECOMMENDATIONS
#### 1.	Segment 0: Young Professionals
>	Target this segment with affordable and trendy products that align with their income range (10K-30K) and education level (bachelor’s Degree).
>	Offer convenience, fast shipping, and seamless online shopping experiences to cater to their busy lifestyles.
>	Leverage social media platforms and influencer marketing to reach and engage with this tech-savvy segment.
>	Provide options for flexible payment plans or installment options to accommodate their budget.

#### 2.	Segment 1: Middle-Income Families
>	Focus on offering value-for-money products and services that cater to the needs of families.
>	Provide discounts, bundle deals, and loyalty programs to incentivize repeat purchases.
>	Highlight family-oriented features, durability, and practicality in product descriptions and marketing materials.
>	Offer educational resources, parenting tips, and family-focused content to establish a connection with this segment.

#### 3.	Segment 2: Educated Achievers
>	Target this segment with higher-end products and services that align with their income range (130K-150K) and education level (Graduate Degree).
>	Emphasize quality, exclusivity, and personalized experiences to resonate with their aspirations.
>	Implement a recommendation engine that suggests sophisticated and relevant products based on their browsing history and purchase behavior.
>	Provide educational and professional development resources to support their continuous learning and growth

#### 4.	Segment 3: Affluent Females
>	Offer luxury products, premium services, and personalized shopping experiences to cater to the preferences of this segment.
>	Implement a visually appealing and user-friendly website design that reflects elegance and sophistication.
>	Curate a selection of high-end brands and exclusive collections to attract this segment.
>	Leverage customer reviews and testimonials from similar affluent females to build trust and credibility.
>	Provide exceptional customer service and personalization options to enhance the shopping experience.

### GENERAL RECOMMENDATIONS FOR ALL SEGMENTS
>	Optimize the mobile shopping experience to cater to the increasing trend of mobile shopping across all segments.
>	Offer secure and seamless checkout processes to build trust and reduce cart abandonment rates.
>	Implement a robust customer support system with various channels to address inquiries and resolve issues promptly.
>	Leverage social proof and user-generated content to build brand trust and encourage customer engagement.
>	Continuously analyze customer data to identify emerging trends, refine marketing strategies, and identify new market opportunities.
>	By tailoring your marketing, product offerings, and customer experiences to each segment's unique characteristics and preferences, you can effectively attract and engage customers, enhance their satisfaction, and drive sales for your e-commerce business


