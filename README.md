# Analysis-of-World-Bank-international-Debt-using-Basic-sql
Here is a mini project where i analyze international debt data collected by The World Banksome using some basic SQL queries codes i learnt from datacamp's (Introduction to sql). The dataset contains 2357 rows of information about the amount of debt (in USD) owed by developing countries across several categories.
Here is a ![Link](https://github.com/MariamAdekanye/Analysis-of-World-Bank-international-Debt-using-Basic-sql/blob/main/international_debt.sql) to the dataset

Before we start analysing our dataset, i did a quick preview to see what is contained in the dataset and familarise myself with the data. It contains 2357 rows and 5 columns
![Image 1](https://github.com/MariamAdekanye/Analysis-of-World-Bank-international-Debt-using-Basic-sql/blob/main/image1.png)

## Step 1: Asking Questions
We are going to find the answers to questions like:

* What is the total amount of debt that is owed by the countries listed in the dataset?
* Which country owns the maximum amount of debt and what does that amount look like?
* What is the average amount of debt owed by countries across different debt indicators?
* Finding out the most common indicator in which the countries owe their debt.
* What is themaximum debt owed by the countries?

------------------------------------------------------------------

Step 2: Analysing our dataset to come up with meaningful insights by responding to the questions above

1. Let’s find the distinct countries involved as there are repetitions in the country names because a country is most likely to have debt in more than one debt indicator. We are going to extract the number of unique countries present in the table to perform our statistical analyses holistically.
![Image 2](https://github.com/MariamAdekanye/Analysis-of-World-Bank-international-Debt-using-Basic-sql/blob/main/2022-08-04%20(4).png)


We can see there are a total of 124 countries present on the table.
---------------------------------------------------------------------

2. Extracting the unique debt indicators in the table. The indicator_name briefly specifies the purpose of taking the debt. Also, there is another column called indicator_code which symbolizes the category of these debts. These debt indicators will help us to understand the areas in which a country can possibly be indebted to.
![Image 3](https://github.com/MariamAdekanye/Analysis-of-World-Bank-international-Debt-using-Basic-sql/blob/main/2022-08-04%20(6).png)

Here, we have 25 distinct debt indicators (i.e. category of debts)
------------------------------------------------------------------------

3. Totaling the amount of debt owed by the countries. The total amount of debt (in USD) that is owed by the different countries will give us a sense of how the overall economy of the entire world is holding up.
![Image 4](https://github.com/MariamAdekanye/Analysis-of-World-Bank-international-Debt-using-Basic-sql/blob/main/2022-08-04%20(8).png)



We have a total of 3,079,734.49 debt owed.
------------------------------------------------------------


4. Finding out the country owing the highest debt. This debt is the sum of different debts owed by a country across several categories.
![Image 5](https://github.com/MariamAdekanye/Analysis-of-World-Bank-international-Debt-using-Basic-sql/blob/main/2022-08-04%20(10).png)

China has the highest debt owed.
------------------------------------------------------------------------


5. Determining the average amount of debt owed across the categories. This will give us a better sense of the distribution of the amount of debt across different indicators.
![Image 6](https://github.com/MariamAdekanye/Analysis-of-World-Bank-international-Debt-using-Basic-sql/blob/main/2022-08-04%20(14).png)

The indicator DT.AMT.DLXF.CD tops the chart of average debt. This category includes repayment of long term debts.

An interesting observation in the above finding is that there is a huge difference in the amounts of the indicators after the second one. This indicates that the first two indicators might be the most severe categories in which the countries owe their debts.

We can investigate this a bit more so as to find out which country owes the highest amount of debt in the category of long term debts (DT.AMT,DLXF.CD). Since not all the countries suffer from the same kind of economic disturbances, this finding will allow us to understand that particular country's economic condition a bit more specifically.
-----------------------------------------------------------------------


6. Finding out the country with the highest amount of principal repayments.
![Image 7](https://github.com/MariamAdekanye/Analysis-of-World-Bank-international-Debt-using-Basic-sql/blob/main/2022-08-04%20(16).png)

China has the highest amount of debt in the long-term debt (DT.AMT.DLXF.CD) category.
----------------------------------------------------------------------------------------


7. Finding out the most common indicator in which the countries owe their debt.
![Image 8](https://github.com/MariamAdekanye/Analysis-of-World-Bank-international-Debt-using-Basic-sql/blob/main/2022-08-04%20(18).png)
------------------------------------------------------------

8. Finding out the maximum amount of debt that each country has. With this, we will be in a position to identify the other plausible economic issues a country might be going through.
![Image 9](https://github.com/MariamAdekanye/Analysis-of-World-Bank-international-Debt-using-Basic-sql/blob/main/2022-08-04%20(20).png)

That’s all for this analysis.

Thank you.


