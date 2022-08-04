# Analysis-of-World-Bank-international-Debt-using-Basic-sql
Here is a mini project where i analyze international debt data collected by The World Banksome using some basic SQL queries codes i learnt from datacamp's (Introduction to sql). The dataset contains 2357 rows of information about the amount of debt (in USD) owed by developing countries across several categories.

Before we start analysing our dataset, i did a quick preview to see what is contained in the dataset and familarise myself with the data. It contains 2357 rows and 5 columns

## Step 1: Asking Questions
We are going to find the answers to questions like:
What is the total amount of debt that is owed by the countries listed in the dataset?
Which country owns the maximum amount of debt and what does that amount look like?
What is the average amount of debt owed by countries across different debt indicators?
-------------------------------------------------------------------

Step 2: Analysing our dataset to come up with meaningful insights by responding to the questions above
1. Let's find the distinct countries involved as there are repetitions in the country names because a country is most likely to have debt in more than one debt indicator. We are going to extract the number of unique countries present in the table to perform our statistical analyses holistically.



We can see there are a total of 124 countries present on the table. 
2. Extracting the unique debt indicators in the table. The indicator_name briefly specifies the purpose of taking the debt. Also, there is another column called indicator_code which symbolizes the category of these debts. These debt indicators will help us to understand the areas in which a country can possibly be indebted to.


Here, we have 25 distinct debt indicators (i.e. category of debts)
3. Totaling the amount of debt owed by the countries. The total amount of debt (in USD) that is owed by the different countries will give us a sense of how the overall economy of the entire world is holding up.
