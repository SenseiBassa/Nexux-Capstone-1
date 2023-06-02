# Nexux-Capstone-1
# Nexus Bank Introduction
Welcome to Nexus Bank! are a financial institution deeply committed to delivering exceptional banking services to their valued clients. Their primary mission is to build enduring relationships with their customers by offering tailored financial solutions that align with their individual needs and goals.

At Nexus Bank, they strongly believe that every individual, regardless of age, profession, or income level, deserves access to world-class financial products and services. That's why they provide a diverse range of banking solutions designed to accommodate an customer's unique lifestyle. Whether they're looking for term deposits, personal loans, or mortgage financing, Nexux Bank have their customers covered.

Their dedicated team of experienced banking professionals is fully devoted to providing their customers with the highest level of service, transparency, and honesty. They also prioritize their financial well-being and strive to exceed their expectations in every interaction.

# Problem Overview
Welcome to the Nexus Bank Problem Overview! In our pursuit of acquiring deposits, Nexus Bank has conducted various campaigns. However, during our recent board meeting, the directors expressed dissatisfaction with our current situation and emphasized the need to optimize our operations.

To address this challenge, the Director of Nexus Bank has reached out to me, a Data Scientist, as they believe in harnessing the power of data to gain valuable insights and enhance our efficiency. My primary objective is to identify patterns and trends in customer behavior, specifically examining how demographic factors like age and education influence customers' attitudes towards defaulting. 

# Aim
We aim to anticipate future customer behavior and assess the likelihood of deposits from our customers.

In addition, we strive to evaluate the effectiveness of our campaigns and develop targeted marketing strategies to reach specific customer segments. By analyzing customer behaviors, loan trends, and the impact of our marketing campaigns, Nexus Bank aims to optimize operations, mitigate risks associated with loan defaults, and improve customer deposits.

Join me in this endeavor as I delve into the power of data analysis to drive enhancements at Nexus Bank. Together, we can make informed decisions that will improve our campaigns, minimize risks, and enhance customer satisfaction.


# Stages of the process

# Import necessary libraries
![Importing Necessary Libararies]("C:\Users\Uncle Baby\Desktop\Gondolin\10Alytics\Capstone project 1\screenshots of project\1.1 Importing necessary libraries.PNG")


 # 1. Data Cleaning
 ![2](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/a47f7bab-5d50-44ca-8f25-6dc4a60786cb)

 # 2. Data Cleaning and Pre-Processing
 ![3](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/39e93128-5de3-4341-bf15-d8422cdb8ba6)

 # 3 Exploratory Data Analysis
 
 # 3.1 Univariate Analysis
 ![4](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/a4a222f5-2ac3-409f-8c9d-7e5dad85d6d9)

 # 3.2 Bivariate Analysis
 ![5](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/b65c7d41-e83a-4316-a6c7-e75b58c1a6ca)

# Training of the Model
![6](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/ba380dd7-6ccf-4351-9fe3-767e0ccfd7f0)

![7](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/ca5dff5b-5b3c-42f3-8c47-d8f92d1b1de9)

![8](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/63a321c3-ee69-4331-92c1-222febef2e8a)


# Drawn Insights
Insights drawn based on the provided narrations observed:

The bank's customer base is primarily composed of adults and old adults, with the aged group having the lowest representation. The largest percentage of customers who did not make a deposit belongs to the adult and old adult age groups. Customers contacted via cellular communication had a higher success rate compared to other contact modes. There is no clear distinction in the distribution of customers contacted through different platforms to determine their influence on deposit behavior. Customers contacted through cellular and telephone communication in the previous campaign have a higher probability of making deposits. Customers contacted via cellular communication exhibited a higher percentage of deposit behavior. A significant portion of the bank's customer base comprises blue-collar workers, followed by management, technicians, and administrative staff. The job categories with the highest default rates are blue-collar, management, technician, and entrepreneur. Entrepreneurs had the highest percentage of defaults, while students had the lowest default rate among all job types. Customers with unknown job types, self-employed individuals, housemaids, and students had a 100% default rate and were given loans. Additionally, over 90% of customers who were given loans did not make deposits. Among customers who did not make a deposit, a majority of them were given housing loans. Conversely, among customers who made a deposit, only a small percentage were given loans. A higher percentage of customers were given loans without making a deposit compared to those who made a deposit and were given loans. From the chart, it can be observed that a small percentage of customers who received housing loans ended up defaulting. Only a small percentage of customers made deposits at the bank. A certain percentage of customers were given both housing and personal loans, while a larger percentage received only housing loans, only personal loans, or no loans at all. A small percentage of customers who did not make a deposit were still given loans. The chart suggests a higher likelihood of default among customers who did not make a deposit. There was a higher number of customers reached out to in the month of May. The boxplot analysis indicates that customers contacted for specific durations have a higher probability of making deposits. The chart shows a difference in dispersion between customers who made deposits and those who did not, with some customers clustered around the mean. On average, customers needed to be contacted more times in the new campaign compared to the previous campaign to make a deposit. The average number of contacts for a successful promotion was found to be lower when the campaign feature had 1.7 contacts. The similarity between the test score and train score suggests no overfitting in the features used in the machine learning model. The confusion matrix of the logistic regression correctly predicted a significant number of customers who did not make deposits, but had some incorrect predictions for customers who made deposits and customers who did not make deposits.

# Recommendations

The bank should consider reducing or stopping loans given to customers who do not make deposits. Bank executives should utilize the procedures used in the previous campaign to increase customer retention and deposits. The bank should focus on reaching out to customers more through cellular and telephone communication.

In point of fact, it will help a great deal if addtional data columns are added. Namely; The date of the last deposit made by the customer, Requirements for loan approval, Types of accounts held by customers, Collateral required for loan approval and Number of times each customer has received and defaulted on loans.


