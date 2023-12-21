# Bank-Loan-Modelling
<b>Project Title: Marketing Campaign for Banking Products</b>

<b>This project is a part of Internship Studio Machine Learning (Training + Internship)</b>

<b>Data Description:</b> <br>
The file Bank.xls contains data on 5000 customers. The data include customer
demographic information (age, income, etc.), the customer's relationship with the bank
(mortgage, securities account, etc.), and the customer response to the last personal
loan campaign (Personal Loan).

Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was
offered to them in the earlier campaign.

<b>Data:</b> https://www.kaggle.com/itsmesunil/bank-loan-modelling/download

<b>Context:</b><br>
The bank has a growing customer base. The bank wants to increase borrowers (asset
customers) base to bring in more loan business and earn more through the interest on
loans. So , the bank wants to convert the liability based customers to personal loan
customers. (while retaining them as depositors). A campaign that the bank ran last year
for liability customers showed a healthy conversion rate of over 9% success. The
department wants you to build a model that will help them identify the potential
customers who have a higher probability of purchasing the loan. This will increase the
success ratio while at the same time reduce the cost of the campaign.

<b>Attribute Information:</b><br>
● ID: Customer ID<br>
● Age: Customer's age in completed years<br>
● Experience: #years of professional experience<br>
● Income: Annual income of the customer ($000)<br>
● ZIP Code: Home Address ZIP code.<br>
● Family: Family size of the customer<br>
● CCAvg: Avg. spending on credit cards per month ($000)<br>
● Education: Education Level. 1: Undergrad; 2: Graduate; 3:
Advanced/Professional<br>
● Mortgage: Value of house mortgage if any. ($000)<br>
● Personal Loan: Did this customer accept the personal loan offered in the last
campaign?<br>
● Securities Account: Does the customer have a securities account with the bank?<br>
● CD Account: Does the customer have a certificate of deposit (CD) account with
the bank?<br>
● Online: Does the customer use internet banking facilities?<br>
● Credit card: Does the customer use a credit card issued by the bank?<br>

<b>Objectives:</b>

1. Analyze and Predict Customer Behavior: Use data from the previous campaign to analyze and build a machine learning model to predict the likelihood of a customer accepting a personal loan in future campaigns.

2. Optimize Marketing Campaign: Based on the analysis, the goal is to optimize the marketing campaign to increase the acceptance rate of personal loans, thereby increasing profit for the bank.

- Reduce Marketing Costs: Find ways to reduce costs for the campaign by targeting more accurately those customers likely to accept a loan, instead of inefficiently approaching a large number of customers.
-In-Depth Understanding of Customers: Derive in-depth insights from data about factors influencing customers' loan decisions, such as income, financial history, banking service usage behavior, etc.

3. Propose Specific Strategies: Based on the analysis results, propose specific strategies for the bank's marketing and product departments to deploy more effective campaigns in the future.

<b>Result:</b>

The dataset contains information on 5000 customers, including demographic data, the relationship with the bank, and feedback on personal loan requests from the previous campaign, but only 9.6% of customers accepted the personal loan. We conducted data analysis to understand the reasons behind this low acceptance rate. Here are some key points from our analysis:
- The age for accepting a personal loan ranges from 26 to 65.
- Customers with over 42 years of experience tend not to accept personal loans.

There is a clear trend that higher income increases the likelihood of accepting a personal loan, specifically more than 2.19 times compared to customers with lower income.
Educational background also plays a crucial role, especially for customers with higher education levels (Graduate, Advanced/Professional).

We employed the K-means algorithm as an unsupervised machine learning model to cluster customers into more optimized groups. By applying the Elbow method and Silhouette Score to attributes such as 'Age,' 'Income,' 'CCAvg,' 'Education,' we determined the optimal number of clusters (e.g., k=2). We observed a significant distinction between the two clusters, particularly in the first cluster, where the acceptance rate for personal loans increased to 53%, a substantial increase from the initial rate of 9.6%. This result highlights the effectiveness of clustering in identifying customer groups with a tendency to accept personal loans, providing valuable information for shaping business strategy and financial advice.
The most suitable age for accepting personal loans falls within the range of 26 to 65, with an income of $60,000 per year and higher education after undergraduate studies.

We deployed predictive models such as Logistic Regression, Random Forest Classifier, Decision Tree Classifier, and Naive Bayes to assist the bank in building a more effective campaign for converting debt customers into loan customers. The results showed that the Random Forest Classifier achieved the best performance.

<b>Steps and tasks:</b>
1. Import data, Exlore the data
2. Data Processing
3. Analyzing the relationship between variables
4. Analyzing the reasons, among these 5000 customers, only 480 (9.6%) accepted the personal loan offer.
5. Customer Segmentation
6. Use models to predict customers accepting personal loans
7. Conclusion
