webcraping project on cars24 website (used cars)
Importing Required libraries copy the URL of the website 
check for status code which will give you 200 its good to go for scraping 
then we extract data from the website the data is not in order to perform necessary actions to get useful insights 
so we have to clean the data using regex Functions and also want to drop unwanted columns
after cleaning data finally check for the Data frame   
df.isnull().sum()---this will give the information about the total null values in the data set in my dataset there are no null values 
df.info()---this will give you the data types in the dataset 
my entire dataset is clean and we can perform visualization 
visualization mainly based on three categories univarient,bivarient, multivarient analysis
based on my dataset i perform visualization an get necessary insights from that 
