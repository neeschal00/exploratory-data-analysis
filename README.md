# Introduction:

This report attempts to elaborate and provide findings based on the
given scenario of the marketing campaign run by the telecommunication
company, the company aims to gain insights into customer responsiveness
to the campaign and evaluate the attributes in the provided dataset. The
goal is to identify the factors that affect subscription plans,
understand customer behavior, and pinpoint the factors that contribute
to higher subscription rates. The following questions have been
formulated:

1\. How are different data attributes correlated with customer
subscriptions?

2\. How can the company modify its strategy to increase subscription
rates?

3\. Are there any noticeable patterns in customer behavior related to
subscriptions?

# Methodology:

## Data Pre-Processing:

Upon loading the data into Pandas with Python, it was observed that the
dataset was not properly formatted. Both the quote value and the
separating characters, which were set as \";\", needed to be specified
for the dataset to be successfully loaded into the dataframe. After the
dataset was loaded into the Pandas dataframe, the presence of double
quotes in the dataset was addressed by cleaning and formatting it. This
was achieved by mapping the headers and the entire dataframe to remove
the double quotes characters. Furthermore, data consistency and an
overview of the dataframe were evaluated, and formatting was applied to
the necessary column, such as \"age.\"

## Univariate Analysis:

The analysis of the individual variables depicts that majority of the
customer's didn't subscribe to the plan and distribution of unique
values for each categorical(i.e. Object data type) was shown through
different bar plots which in return assisted in identifying the coverage
of each unique value for a particular variable. The density plots also
helped identify the distribution of values for a variable where higher
response concentration for specific age groups and month's were
identified.

## Bivariate Analysis:

To analyze the relationships between variables, we conducted an analysis
in which scatter plots were created and examined for any correlations
among the variables. It was observed that the people with "admin" and
"blue-collar" job titles were subscribed and distribution of subscribers
was similar across different age groups, suggesting a negligible
correlation. However, a higher number of subscribers were observed among
individuals with longer durations of contact. Additionally, it was found
that subscribers were more numerous among those who were contacted via
cellular methods rather than telephone.

## Correlation Matrix:

A correlation matrix was constructed to identify potential attributes
affecting the subscription. It was observed that the \'campaign\'
variable, along with the \'number employed\' variable, showed a slight
positive correlation with the subscription. Further analysis may help in
uncovering the relationship in a more comprehensive manner and
identifying additional factors that affect customer responsiveness
behavior.

# Findings:

Data being Improperly formatted was shown in the screenshots and
formatted to load in the Pandas Dataframe also converting the data type
of the column "age".

The overview of the data types in the column along with the duplicated
row count and description of columns with numeric data types are shown
in the screenshots below.

It was observed that the **majority** of the customers **were not
subscribed** to the marketed plan.

Based on the density chart below it can be depicted that the majority of
customers were in the age group 30-40.

Similarly the **distribution** of the value count for variable previous
outcome and campaign is shown with bar plots along with box plot and
density plots.

From the below box plot it can be observed that **outlier's** exist for
the column duration which shows some contact duration **lasted** a lot
**longer**.

According to the Categorical distribution chart below, the majority of
responders consisted of customers with **\'admin\'** and
**\'blue-collar\'** job types, with a notable number of subscribers
belonging to the \'admin\' category and, to a greater extent.

The Subscription Variable was further analyzed with others as a part of
bivariate analysis where relation with duration of contact time was
observed whereas in case of age was negligible.

Here Customer's **contact method** also displayed a differentiating
factor in the subscription.

The below clustered Chart depicts that responders were high in the month
of **"may".**

The **correlation matrix** with the heatmap shows there is high
correlation of number employed and euribor 3 month rate.

There's a slight positive correlation observed for the subscription with
attributes such as duration, campaign, employee variation rate and
number employed.

# Conclusion:

From the given dataset initial insights were uncovered based on
different analyses in relation to customer's responsiveness to the
marketing campaigns. Notably, observations regarding job type, contact
method and campaign might play a piviotal role in customer's
subscription behavior. Finally, those initial observations upon further
analysis and evaluation may help uncover them and justify while also
identifying the additional factors affecting the behavior.
