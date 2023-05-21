# supermarketsales
The following project was realized to evaluate sales in a supermarket, because the growth of supermarkets in most populated cities are increasing and market competitions are also high. The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data.

So, a Python code was built, using Jupyter Notebook, to analyze further the data, where it was necessary to use external Python packages such as Pandas, Numpy, Matplotlib, Seaborn etc. to conduct univariate analysis, bivariate analysis, correlation analysis and identify and handle duplicate/missing data.

The data was retrieved from: https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales

The main objective involved analyze the database with information about the supermarket sales to know how the data is distributed and to get some insights from it about the different branches, customers ratings, gross income, etc.

As a starting point, it was necessary to import the Python libraries that were going to be used in the notebook.

![python libraries](https://github.com/KenethRojas/supermarketsales/assets/131609936/0eada42f-6ab8-4d18-8461-b9afd337fb3b)

Then, the data was visualized using the library called Pandas to analyze the distribution, quantity of records, the class of each attribute and to get a summary of each characteristic within the table. Therefore, once the data was checked, the analyzed was made.

First, the univariate analysis focused on evaluating the distribution of the customer rating; where, as shown in the graphic below, the customer rating has a uniform distribution; and the sales number per branch, where it could be seen that sales don’t differ by much between branches.

![customer rating distribution](https://github.com/KenethRojas/supermarketsales/assets/131609936/7a989f86-dc89-4421-b5cd-24671b6df401)

Second, the bivariate analysis focused on assessing the relationship between the gross income customer rating, branches and genders; and analyzing the variation of the gross income during time, where it could be seen that on 02/15/2019 there was a peak on sales.

![gross income - customer rating relationship](https://github.com/KenethRojas/supermarketsales/assets/131609936/8b1034c5-08ef-406f-8dee-1e4cb7d06c4a)

Next, it was necessary to handle with duplicated data by dropping them and with missing data using heatmap to visualize it and replacing them with “NA” values.

Finally, a correlation analysis was made to visualize the relation that each variable had with each other and draw conclusions.

![correlation analysis heatmap](https://github.com/KenethRojas/supermarketsales/assets/131609936/37c8d6f6-8c33-4cbe-9a54-1427fcb6192c)

As a result, the insights obtained from all this project were the following. For the univariate analysis, as the customer rating has a uniform distribution, it can be inferred that none of the values within this attribute has a bigger probability of happening than the others. Also, for sales per branch, it can be deduced that the location doesn’t really make a difference in terms of quantity of transactions. For the bivariate analysis, as seen in the graphic, it can be inferred that there is no influence between the customer rating and how much money they spend. Also, as there is not much variation between gross income and branches/gender, it can be interpreted as these variables doesn’t really affect how much money customers spend. Additionally, for the variation through the days, despite having a peak on sales on 02/15/2019, there was not really a trend for the sales regarding to the date. Finally, for the correlation analysis, as seen in the heatmap graphic, customers rating has no relation with any other of the attributes, so it can be inferred that no variable at all influence in the overall shopping experience.
