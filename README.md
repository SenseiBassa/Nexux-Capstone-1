# Nexux-Capstone-1 Customer Segmentation and Deposit Detection system Case Study
![1st](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/a37c7c56-3d99-49cd-b68b-ca2e876470df)
# Bassa, Joshua Samuel 
# 2nd May,2023
![2nd](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/a1dd7b37-fcf4-4a94-b0ef-84b58243f2f1)
# Nexus Bank Introduction
Nexus Bank is a financial institution that aims to provide exceptional banking services tailored to the specific needs and goals of its clients. They offer a wide range of banking solutions and prioritize delivering high-quality service, transparency, and honesty. However, during a recent board meeting, the directors expressed dissatisfaction with the current state of affairs and recognized the need to optimize operations and improve efficiency.

![3rd](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/dd8af039-845d-436f-a0ac-13ebbbfb7e2b)

# Problem Overview
In her pursuit of acquiring deposits, Nexus Bank has conducted various campaigns. However, during their recent board meeting, the directors expressed dissatisfaction with their current situation and emphasized the need to optimize our operations. To address this challenge, the Director of Nexus Bank reached out to me, as they believe in harnessing the power of data to gain valuable insights and enhance our efficiency. 

![4th](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/ba058d59-60e4-49ea-8be5-97186b334ca8)

# Objectives
My primary objective is to identify patterns and trends in customer behavior, specifically examining how demographic factors like age and education influence customers' attitudes towards defaulting. 

# Aim
- To anticipate future customer behavior and assess the likelihood of deposits from their customers.
- To optimize operations, mitigate risks associated with loan defaults, and improve customer deposits.
- To evaluate the effectiveness of their campaigns and develop targeted marketing strategies to reach specific customer segments. 
  (by analyzing customer behaviors, loan trends, and the impact of their marketing campaigns).

# Expected Deliverable
Join me in this endeavor as I delve into the power of data analysis to drive enhancements at Nexus Bank. Together, we can make informed decisions that will improve their campaigns, minimize risks, and enhance customer satisfaction.

![5th](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/25131f8b-3d29-4fd8-88ad-121062b96e64)

# Deployment process stages
Below are a list of stages employed in ensuring the project was a success.
# Import necessary libraries
Below were the necessary lbraries that were utilized for the sake of this project:
![1](![1 1 Importing necessary libraries](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/8e1e7488-810f-44ef-aaae-f0c2c8d5fbdb)

# 1. Data Cleaning and Pre-Processing
Data cleaning is essential for improving data quality, ensuring accurate analysis, enabling efficient decision-making, and meeting compliance requirements. It is a critical step in the data preparation process that contributes to reliable and meaningful insights from data analysis. Data cleaning helps enhance the quality of data by identifying and rectifying various issues, such as missing values, outliers, duplicate records, and formatting errors. Clean data reduces the risk of making incorrect conclusions or decisions based on flawed information. During this process, thorough care was taken in the process. The data was cleaned, outliers were removed and te data was made squeky clean and readable for easy access. Below are screenshots from the data cleaning:
 ![1 Data Cleaning](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/c2afccaa-c32b-4a7c-8e93-7dd48b5c7e0a)
 ![3](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/39e93128-5de3-4341-bf15-d8422cdb8ba6)
 # 1.1 Identifying the outliers
 This stages is important because it gives insights moving forward into what data type or structure is dealt with.
 ![2 Identifying the outliers](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/bf8faf22-4608-4485-8849-1dc83a195fd6)
 ![2](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/a47f7bab-5d50-44ca-8f25-6dc4a60786cb)
 # 1.2 Removing the outliers
 Data removal is also a crucial stage, oftentitmes, some data scientists do not bother removing it them, since they make little to no difference.
 ![3 Removing outliers](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/018cf4d4-55d4-42dc-b02e-1e485eec8f4c)
 ![4 Removing outliers](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/070e790b-634f-48d6-ba94-d0c8ea0ad195)
  
  # 2 Exploratory Data Analysis
  Exploratory Data Analysis (EDA) is a crucial step in the machine learning pipeline that involves analyzing and understanding the characteristics and patterns within a dataset. It helps to gain insights, identify relationships, and detect anomalies or patterns that may be useful for building predictive models. 
 ![5 EDA](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/d77549b8-e477-4f88-a518-0fb9f19e32e4)
 Below are charts generated during the course of this stage:
 # Chart showing the count of the age bracket of customers
 ![6 Chart showing the count of the age bracket of customers](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/790a737b-d136-4884-bb9b-6f95018d7914)
  ![4](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/a4a222f5-2ac3-409f-8c9d-7e5dad85d6d9)
  # Percentage of those that made deposit
  ![7 percentage of those that made deposit](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/c2799683-b9d9-4c81-a498-38fbb211dc7d)
  # Chart showing the mode of contact
  ![8 Chart showing the mode of contact](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/22cf173f-5946-4529-803c-e6fa078df320)
  # Showing outcome by mode of contact
  ![9 showing outcome by mode of contact](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/5d1a76a0-1a6e-4e4d-bf2f-0770ac31e664)
  # Chart showing the job type of customers
  ![10 Chart showing the job type of customers](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/562796de-4a92-4d4c-a9be-6928819ff552)
  # Customers that took both personal and Housing Loans
  ![11 Customers that took both personal and Housing Loans](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/18ddc64a-3579-4492-a8b1-f3c4206be099)
  # Types of customers that default
  ![12 Types of customers that default](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/3dadfdb5-1e59-43bd-b377-3471352396f2)
  # Month customers were last reached out to
  ![13 Month customers were last reached out to](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/aa5e2519-2638-4d40-99f5-db44b5c063bd)
  # Duration of deposit
  ![14 Duration of deposit](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/0412627c-3eab-489b-a6e2-eda88dbd72b2)

  # Feature Engineering
  Feature engineering is the process of creating new features or transforming existing features in a dataset to enhance the performance and interpretability of machine learning models. It involves extracting relevant information from the raw data and representing it in a way that captures important patterns or relationships. Below is a screenshot of that stage:
  ![15 Feature Engineering](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/1085fdf5-8c3c-4a38-8a28-df5b438ce10e)

  # Machine Learning
  Machine learning algorithms are designed to learn patterns and relationships from input data. They analyze and process large amounts of data to discover underlying patterns, trends, or structures that can be used to make predictions or decisions. This is what we did in this stage.
  ![16 Machine Learning](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/581b4d5b-2523-4712-be36-8e107c504e15)
  ![17 Machine learning 2](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/cf247655-1a3f-408c-8ccd-4ea2bb29ac7b)
  
 # Model Building
 Model building in machine learning involves the process of selecting and training a predictive model that can make accurate predictions or decisions based on the input data. Data preprocessing ensures that the data is in a suitable format for training the model. The training set is used to train the model, the validation set is used to fine-tune and optimize model parameters, and the test set is used to evaluate the final performance of the model on unseen data. In this stage, we tried to understand the model and deployed the most suitable model. Below was utilized for the sake of the project.
 ![18 Model Building](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/55e6abda-5a5a-4ff6-8656-34d757336ac0)
 # Confusion Matrix
 ![19 Confusion Matrix](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/88b317e5-e3be-4625-9170-bfc13fa70361)
 ![20 Confusion Matrix](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/0b771070-df66-4994-8bd4-f8f5deb3bb68)
 
 # Normalization
 Normalization is a data preprocessing technique that is commonly used in machine learning to scale and standardize features or variables. It involves transforming the data to a common scale or range to eliminate the influence of differing magnitudes and units.  Normalization ensures that all features or variables are on a similar scale, preventing certain features from dominating the learning process simply because of their larger values. By scaling features, we give equal importance to each feature during model training. Find below some pictoral representations.
 ![21 Normalization](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/fa646fb2-ff75-4c44-8b55-65b22618b282)
 ![22 Score lists](https://github.com/SenseiBassa/Nexux-Capstone-1/assets/98027992/2cfcc0f6-a061-4595-a425-4f448bd190a6)

# Drawn Insights
Insights drawn based on the provided narrations observed:
The bank's customer base is primarily composed of adults and old adults, with the aged group having the lowest representation. The largest percentage of customers who did not make a deposit belongs to the adult and old adult age groups. Customers contacted via cellular communication had a higher success rate compared to other contact modes. There is no clear distinction in the distribution of customers contacted through different platforms to determine their influence on deposit behavior. Customers contacted through cellular and telephone communication in the previous campaign have a higher probability of making deposits. Customers contacted via cellular communication exhibited a higher percentage of deposit behavior. A significant portion of the bank's customer base comprises blue-collar workers, followed by management, technicians, and administrative staff. The job categories with the highest default rates are blue-collar, management, technician, and entrepreneur. Entrepreneurs had the highest percentage of defaults, while students had the lowest default rate among all job types. Customers with unknown job types, self-employed individuals, housemaids, and students had a 100% default rate and were given loans. Additionally, over 90% of customers who were given loans did not make deposits. Among customers who did not make a deposit, a majority of them were given housing loans. Conversely, among customers who made a deposit, only a small percentage were given loans. A higher percentage of customers were given loans without making a deposit compared to those who made a deposit and were given loans. From the chart, it can be observed that a small percentage of customers who received housing loans ended up defaulting. Only a small percentage of customers made deposits at the bank. A certain percentage of customers were given both housing and personal loans, while a larger percentage received only housing loans, only personal loans, or no loans at all. A small percentage of customers who did not make a deposit were still given loans. The chart suggests a higher likelihood of default among customers who did not make a deposit. There was a higher number of customers reached out to in the month of May. The boxplot analysis indicates that customers contacted for specific durations have a higher probability of making deposits. The chart shows a difference in dispersion between customers who made deposits and those who did not, with some customers clustered around the mean. On average, customers needed to be contacted more times in the new campaign compared to the previous campaign to make a deposit. The average number of contacts for a successful promotion was found to be lower when the campaign feature had 1.7 contacts. The similarity between the test score and train score suggests no overfitting in the features used in the machine learning model. The confusion matrix of the logistic regression correctly predicted a significant number of customers who did not make deposits, but had some incorrect predictions for customers who made deposits and customers who did not make deposits.

# Recommendations
The bank should consider reducing or stopping loans given to customers who do not make deposits. Bank executives should utilize the procedures used in the previous campaign to increase customer retention and deposits. The bank should focus on reaching out to customers more through cellular and telephone communication.
In point of fact, it will help a great deal if addtional data columns are added. Namely; The date of the last deposit made by the customer, Requirements for loan approval, Types of accounts held by customers, Collateral required for loan approval and Number of times each customer has received and defaulted on loans.
