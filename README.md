# Customer-Insights-Analysis
In-depth exploratory data analysis on a shopper dataset for a store in the luxury industry (store's exact name is unknown). <br>
Link to the original dataset: https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis
<hr>
<h3>Results</h3>
An example of my "|" formatting: <br>
[Income, Children | Fruit_Spending] <br>
Above, I'm referring to the correlations between Income and Fruit_Spending AND Children and Fruit_Spending. Anything on the side with 1 column is correlated with all of the columns on the other side.<hr>

1. The strongest correlation between any 2 different columns is between Luxury_Spending and income. This should come as no surprise. Furthermore, there is a very strong similarity in the correlation between [Luxury_Spending | NumWebPurchases, NumStorePurchase] and [Income | NumWebPurchases, NumStorePurchases]. However, upon another inspection of the correlation heatmap, [Luxury_Spenders | NumWebPurchases] have a slightly stronger correlation compared to [Income | NumWebPurchases].

2. Correlation between [Income | Fruit_Spending, Luxury_Spending] (more so for Luxury_Spending).

3. There is a moderate correlation between people who come into our store and who shop on our website. The key word here is moderate.

4. Moderate correlation between [Luxury_Spending | Total_Campaigns_Accepted]. Given the almost identical correlation between [Meat_Spending, Luxury_Spending | Income], but the greater correlation between [Total_Campaigns_Accepted | Luxury_Spending], this implies that Luxury_Spenders have less impulse control toward our *campaigns* specifically.

5. [Meat_Spending | NumCatalogPurchases] is a notable correlation. [Children | NumCatalogPurchases] is as well, but this correlation is negative. [Meat_Spending | Children] is also another notable negative correlation.

6. If we look at Children and Income, we can see that there is a pretty clear negative correlation between children and income. The interesting thing is that the difference between the median between having 0 children and 1 child is ~25000!
   
7. The correlation between the different types of spending is clearly high. This is due to income, although there are other factors at play, especially with Fruit_Spending.
   
8. The columns of Birth_Year, Enrollment_Date, Education, and Marital_Status surprisingly had little to no correlations with other columns.

<hr>
<h3>Applications of this EDA</h3>
The patterns found in the results above as well as the graphs in the notebook provide valuable insights for luxury retail marketers.
