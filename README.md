# Telco-Customer-Churn-Analysis
Findings:

Telco faces the problem of customer churn. This time, analyze the data and try to provide recommendations related to the problem faced.
"Churn" refers to the loss of customers, typically due to dissatisfaction with a service or product.

CUSTOMER CHURN:
26% of Telco customers are churning, resulting in a devastating $3.6 million revenue loss.
Competitor and Poor Attitude from employees are the largest cause of customer churn. This analysis will help us
understand why customers are leaving and develop targeted strategies to win them back

![newplot (6)](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/d54a19a7-a0fa-4d6c-8637-00f5696fe63e)

![newplot (7)](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/06e04cfe-aed0-40d4-90b9-401e6549aa38)


SERVICES AND CUSTOMER CHURN:
From the chart, I observe that customers who subscribe to internet Services tend to be more likely to churn compared to those who do not, The result of Cramer’s V (0.228 indicates that there is a weak to moderate association between the variables. Although it's weak, t will conduct further analysis to understand the cell he conditions.

![newplot (8)](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/f7e74110-d6b3-4c65-bcc9-60384c6bd71f)
![newplot (9)](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/f1f255a7-d366-4533-96bb-308675dac207)
![newplot (10)](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/66d159e2-db54-404f-bd3b-c84c0ef8d625)

INTERNET DEVICES RATING
supporting the idea that the internet services of this company are problematic, the Fiber Optic product received the largest percentage of low ratings, suggesting that many customers rare not particularly pleased with it.

![newplot (11)](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/6951eabc-e515-442b-bd63-bb002e9496ab)


PHONE SERVICES RATING
in contrast, Phone Service users tend to give higher ratings.

![newplot (12)](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/d7cadeff-6922-4ccd-bf9b-d9da87902fc2)


INTERNET SERVICE OPTIONS
This matrix reveals Cramer V statistics between 0.07 and 0.17, indicating a small to moderato relationship between Internet Service options and Customer Churn, While the relationship exists, its strength suggests that other factors may be more influential in explaining customer churn

![newplot (13)](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/db02c36c-c901-4171-af45-c48d296139f5)


OFFERINGS
The second-largest reason customers become churned is because the competitor made better offers. Customers who a ho are offered "E” tend to churn. Therefore, this offering strategy needs to be changed.

![image](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/dc85d312-72d7-41cf-ab23-9e13485ff3b8)

![newplot](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/1de93049-ed66-43d0-b0de-81aaaf3f6c3f)

CONTRACTS
Moreover, we also need to modify our contract strategy, Customers who take a 'Month-to-Month' contract have a 50% chance of churning.

![image](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/8a12b74b-5057-473b-b21d-276458d05e7b)

![newplot (1)](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/d06aa810-d473-4c06-8771-3d3a3021cdb9)

CUSTOMER CHURN AREA
Los Angeles, San Diego, and San Francisco are areas with the highest level of Customer Churn. We need to be aware of the presence of of competitors in these areas.

![newplot (2)](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/528813c1-0c80-4b7b-bae6-f4320da6e2c2)

Machine Learning
I built a Machine Learning model to predict customer churn, with the goal of identifying customers who are likely to leave.

MODEL EVALUATION
The algorithm I use is CatBoost; my model predicts customer churn with relatively high score.
In the case of Customer churn, False Negatives are more dangerous than False Positives because False Negatives can
have significant consequences, including financial losses, negative customer experiences, and reputational harm.

![newplot (3)](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/16465ea7-6cf0-4d48-9bcb-7fa52fd0de4e)

![newplot (4)](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/89722b0d-961f-448b-8388-06f06833579b)

BUSINESS SIMULATION
Using the Machine Learning model, Telco can reduce approximately $70,100 from the potential revenue loss of $577,427 due to customer churn.

![newplot (5)](https://github.com/khorkina/Telco-Customer-Churn-Analysis/assets/166530415/10f8948a-b155-4f70-ac61-ebf20913ce1a)

Addressing Competitors and Employee Attitude:

Competitors:
Enhance Product/Service Quality 
-Conduct regular customer feedback sessions, 
-Invest in R&D for innovation and improvement. 
-Benchmark against competitors.

Competitive Pricing Strategies
-Analyze competitor pricing.
-Offer competitive pricing options or value added services. 
-Implement Loyalty programs and discounts for long-term customers

Unique Selling Proposition (USP)
-Identity and communicate your USP clearly 
-Highlight unique and better aspect of your product/service.

Poor Attitude from Employees:
Employee Training and Development 
-Implement regular training programs, 
-Provide continuous learning opportunities.

Employee Engagement and Motivation
-Foster a positive work environment 
-Recognize and reward good performance, 
-Conduct regular employee satisfaction surveys

Improve Communication and Feedback Channels 
-Establish clear communication channels. 
-Create a system for anonymous feedback. 

Hiring and Onboarding
-Hire individuals with a positive attitude 
-Implement a comprehensive onboarding process

Addressing Bad Offering and Contract Strategy:

Bad Offering:
Conduct Market Research
-Perform market analysis to understand customer needs and preferences.
-Identify gaps in current offerings and areas tor improvement.

Improve Customer Communication 
-Clearly communicate the benefits and unique features of your offerings 
-Use multiple channels (social media, email, website) for consistent messaging.

Competitive Pricing Analysis
-Research competitor pricing strategies. 
-Adjust prices to reflect the value provided while remaining competitive

Contract Strategy:
Focus on Customer Needs
-Tailor contracts to meet the specific needs and preferences of different customer segment. -Introduce customizable contract options to provide greater customer choice.

Value-Added Benefits
-Include additional perks or benefits in contracts to increate perceived value, 
-Offer incentives for long-term commitments, such as discounts or exclusive services.

Conclusion:
Customer churn refers to the phenomenon where customers discontinue their subscription to a service: It is a critical metric for businesses, especially those with a subscription-based model, as it directly impact revenue and growth
To tackle customer churn, Telco need to developing superior products and services to match or surpass competitors, building a positive and proactive customer service culture, designing customer friendly and flexible contracts, and continuously refining predictive models
Moving forward, Telco have to focus on customer-centric strategies to enhance loyalty and retention, stay adaptable to market changes and customer needs











