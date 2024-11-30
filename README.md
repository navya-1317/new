#Project overview:
We will visualize a dataset of daily temperatures to observe seasonal patterns and trends.

#Steps:
Import required libraries.
Load the dataset (example: "daily-minimum-temperatures.csv").
Process and clean the data.
Plot the data using Matplotlib and Seaborn.
Add analysis insights like rolling averages or trends.




#EXPLANATION:
Dataset:

 We use a publicly available dataset on daily minimum temperatures in Melbourne, Australia (1981–1990).
 The dataset contains two columns: Date and Temp.

#Data Loading:

 pandas is used to load the data, parse the Date column as a datetime object, and set it as the index.
 Exploratory Data Analysis (EDA):

head() displays the first few rows of the dataset.
info() provides data types and missing values.
describe() gives summary statistics.
#Visualization:

 The original time series data is plotted using Matplotlib.
 Rolling averages (7-day and 30-day) are calculated to observe short-term and long-term trends.
 Seasonal boxplots using Seaborn reveal temperature distribution across months.



#Moving Averages:

 Rolling averages smooth the data to highlight trends and reduce noise.


#Seasonality:

 Boxplots demonstrate monthly variations, showing how temperatures vary throughout the year.
