<h1 align="center"> Credit cards customer predictions </h1>

<h1 align="Left"> Case  🗂️ </h1> 
<br>

In order to enhance my machine learning skills, I have been working on various projects. The dataset you will see below has been obtained from the Kaggle platform. Its context is as follows:

      A manager at the bank is disturbed with more and more customers leaving their credit card services. They would really appreciate 
      if one could predict for them who is gonna get churned so they can proactively go to the customer to provide them better services 
      and turn customers' decisions in the opposite direction.
            
      I got this dataset from a website with the URL as https://leaps.analyttica.com/home. I have been using this for a while to get 
      datasets and accordingly work on them to produce fruitful results. The site explains how to solve a particular business problem.
            
      Now, this dataset consists of 10,000 customers mentioning their age, salary, marital_status, credit card limit, credit card, 
      etc. There are nearly 18 features.
            
      We have only 16.07% of customers who have churned.

<br>



<h1 align="Left"> Goal 🎯 </h1> 
<br>
 
 - Make an EDA to check our data.

 - Predict churning customers.
<br>





</head>
<body>
    <h1>Data Dictionary</h1>
    <table>
        <tr>
            <th>Column</th>
            <th>Description</th>
        </tr>
        <tr>
            <td>CLIENTNUM</td>
            <td>Client number. Unique identifier for the customer holding the account</td>
        </tr>
        <tr>
            <td>Attrition_Flag</td>
            <td>Internal event (customer activity) variable - if the account is closed then 1 else 0</td>
        </tr>
        <tr>
            <td>Customer_Age</td>
            <td>Demographic variable - Customer's Age in Years</td>
        </tr>
        <tr>
            <td>Gender</td>
            <td>Demographic variable - M=Male, F=Female</td>
        </tr>
        <tr>
            <td>Dependent_count</td>
            <td>Demographic variable - Number of dependents</td>
        </tr>
        <tr>
            <td>Education_Level</td>
            <td>Demographic variable - Educational Qualification of the account holder (example: high school, college graduate, etc.)</td>
        </tr>
        <tr>
            <td>Marital_Status</td>
            <td>Demographic variable - Married, Single, Divorced, Unknown</td>
        </tr>
        <tr>
            <td>Income_Category</td>
            <td>Demographic variable - Annual Income Category of the account holder (< $40K, $40K - 60K, $60K - $80K, $80K-$120K, >$120K)</td>
        </tr>
        <tr>
            <td>Card_Category</td>
            <td>Product Variable - Type of Card (Blue, Silver, Gold, Platinum)</td>
        </tr>
        <tr>
            <td>Months_on_book</td>
            <td>Period of relationship with bank</td>
        </tr>
        <tr>
            <td>Total_Relationship_count</td>
            <td>Total no. of products held by the customer</td>
        </tr>
        <tr>
            <td>Months_Inactive_12_mon</td>
            <td>No. of months inactive in the last 12 months</td>
        </tr>
        <tr>
            <td>Contacts_Count_12_mon</td>
            <td>No. of Contacts in the last 12 months</td>
        </tr>
        <tr>
            <td>Credit_Limit</td>
            <td>Credit Limit on the Credit Card</td>
        </tr>
        <tr>
            <td>Total_Revolving_Bal</td>
            <td>Total Revolving Balance on the Credit Card</td>
        </tr>
        <tr>
            <td>Avg_Open_To_Buy</td>
            <td>Open to Buy Credit Line (Average of last 12 months)</td>
        </tr>
        <tr>
            <td>Total_Amt_Chng_Q4_Q1</td>
            <td>Change in Transaction Amount (Q4 over Q1)</td>
        </tr>
        <tr>
            <td>Total_Trans_Amt</td>
            <td>Total Transaction Amount (Last 12 months)</td>
        </tr>
        <tr>
            <td>Total_Trans_Ct</td>
            <td>Total Transaction Count (Last 12 months)</td>
        </tr>
        <tr>
            <td>Total_Ct_Chng_Q4_Q1</td>
            <td>Change in Transaction Count (Q4 over Q1)</td>
        </tr>
        <tr>
            <td>Avg_Utilization_Ratio</td>
            <td>Average Card Utilization Ratio</td>
        </tr>
        <tr>
            <td>Naive_Bayes_Classifier_attribution</td>
            <td>Naive Bayes</td>
        </tr>
        <tr>
            <td>Naive_Bayes_Classifier_attribution</td>
            <td>Naive Bayes</td>
        </tr>
    </table>



