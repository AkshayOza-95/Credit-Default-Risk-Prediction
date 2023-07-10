# Credit Default Risk Prediction

# Purpose and Problem Domain

As the power of consumption increases, people tend to spend more now and borrow against future income. Relative to the bank loans, personal loans have shorter approval procedure and lower application standards. Since the first P2P (peer-to-peer) web lending platform, ZOPA, was established in 2005, the personal loan industry has grown rapidly throughout the world. Outstanding personal loan debt triples from 49 billion dollars in 2010 to 156 billion dollars, as of Q3 2019.

Nevertheless, the prosperity of the personal loan market brings a serious credit default problem. Delinquency rates (60 days or more past due) for personal loans is currently 3.3%, which is higher than mortgages (1.5% delinquency rate), auto loans (1.4%), and credit cards (1.8%). The main reason lies in lending platforms that relax the loan audit conditions and ignore the potential risks, in order to enhance their market competitiveness and get more benefits. Usually, personal loans are unsecured. Once the clients default, the loans will become bad debts for the lending platform and could never be taken back, which may cause great economic losses for the investors and the lending platform. Therefore, how to better control the economic risk caused by the customer loan default is the key to the stable development of the loan platform and the credit industry. 

For our project, we limit the domain within an international non-bank financial institution called Home Credit, a company founded in 1997 and has provided more than 131 million loans for people worldwide. Our goal is to predict how capable each applicant is of repaying a loan based on clients' current loan applications to Home Credit and their previous lending activities(eg. credit card balance, POS (point of sales) and cash loans, installments payments). We develop a series of credit scoring models which classify personal loan applications into default and nondefault groups, and also pick out the most important factors related to credit default from hundreds of columns in the datasets.

# Definition of Task, Performance, Experience & Value
The **Task** for our project is to predict whether a client has payment difficulties(1 for having difficulties and 0 otherwise). If he/she had late payment on at least one of the installments of the loan in our sample, we will regard he/she as having payment difficulties and thus the lending company should not issue a loan to that applicant.

To evaluate the **Performance**, we will use recall to avoid an applicant who actually defaults being predicted as not default by our models. It is important because the landing platform will have a benefit lost when lending money to those applicant. Also, we plot Precision-Recall Curve for different thresholds.

Our model will learn from the **Experience** of loan applicants' information at application time, their previous loans and payments in Home Credit, credit card loans in Home Credit and other lending activities reported to Credit Bureau.

The **Value** we would be adding through our project is increased efficiency and accuracy through which financial institutions can evaluate a loan application and examine the risk of whether a loan applicant is likely to default or not. This will save financial institutions a significant amount of money that they might lose otherwise while lending a loan to someone who might face difficulties in repayment

# Data
The data we will be using for our project is the [https://www.kaggle.com/c/home-credit-default-risk/overview] (Home Credit Default Risk Data). It was provided by the Home Credit Group as a part of the Kaggle Competition.




