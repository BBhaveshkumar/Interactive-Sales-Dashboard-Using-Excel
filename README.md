Interactive-Sales-Dashboard-Using-Excel
The objective was to create an annual sales report of a Super Store for last year. So that, the owner can understand their customers and grow more sales in the next year.

We had to create a dashboard to provide the following KPI's as per the demand:

1)Compare Sales and Orders using a single chart
2)Which month got the highest sales and orders?
3)Who purchased more- Men or Women?
4)What are the different order status?
5)List top 5 states contributing to the sales.
6)Relation between Age and Gender based on numbers of orders.
7)Which channel is contribnuting to maximum sales?
8)Highest selling category?

After understanding the objective and the problem statement, we went forward to our first step i.e. Data Cleaning. For data cleaning, we followed the following steps:

1) Removing Duplicates: We had to remove duplicates so that they don't cause any error in the calculations or the result outcomes. The easist but less reliable way to remove duplicates is to select all data and click remove duplicates. Or the other way is to apply filters and check for duplicate values and delete them.

2) Removing Null Values: The null values has to be removed for the same reason as stated above that they should not cause any error in the Pivot Table calculations. To do so, we apply the filters, select rows with blank values and delete them.

3) Setting datatype: Setting the correct datatype is a must. For example, the age column datatype must be a number. It cannot be text and so on for other columns as well.

4) Correcting Row Values: In the gender column, in certain rows Men were showed as 'M' and in others as 'Men' and same for women. So, we need to make them equal to process the data. Either we should indicate Men as 'M' or 'Men' only.

Various other data cleaning steps can be applied as per your requirement. Now moving on to the Data Preparation/Processing part, the necessary steps are:

1) Grouping Data: We can group the data to simplify the category. Suppose, if we need check orders by age, our data has a age range between 12 to 51. We might need to check sales for each age, which in turn is a tedious and useless task. Instead, we can classify them as teenager, adult and senior.

2) Modifying Data: To get monthwise sales, we can extract month from the date column and create a new month column next to it to track sales by month.

3) Establishing Relationship between Columns:
