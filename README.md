# Sales Analysis with Pandas
A set of real life data science tasks completed using Pandas library

### Task overview

The dataset considered for the sales analysis include thousands of electronics store purchase information broken down month wise.

Python Pandas and Matplotlib is used to analyze and answer different buisness questions

For analysis purpose the csv files with monthly data are concatenated into single file (pd.concat)

### Data Cleaning

The dataset containig all months data required some bit of cleaning before the analysis

* Rows with NaN values were removed 
* Removing certain rows based on condition
* Converting the data type of column into appropriate type (to_numeric, to_datetime etc.)

### Data exploration

In this section the dataset is manipulated and analysed inorder to find answers to some important buisness questions like:

* How much amount was earned each month and what is the best month of sales?
* City with most sales
* Best time to display ads as per the purchase trend of customers
* Best products that could be bundeled together
* Product with maximum sale and reason for this trend

### Visualizations

Below are some of the visualization created using matplotlib

![monthly sales](https://user-images.githubusercontent.com/37290809/191277878-c7b63381-b5ce-41a6-b114-94a58d8f3b9e.png)

An interesting plot which includes a bar graph overlayed with a line graph. This visualization gives a correlation between a product's quantity sold and price. These type of visualization helps to bring out meanginful perception and helps business decision makers take data driven decisions and insights to imporve the business.

![quantity and price](https://user-images.githubusercontent.com/37290809/191277885-d29130c7-2d9f-4759-9910-bcde14e0bc1f.png)


![time and sales](https://user-images.githubusercontent.com/37290809/191277889-9c241353-6092-4a53-9533-a16a8e0d518b.png)
