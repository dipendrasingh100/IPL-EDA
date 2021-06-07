# IPL EDA
Indian Premier League(IPL) is a professional Twenty20 cricket league in India contested during March or April and May of every year by eight teams representing eight different cities in India. 
The league was founded by the Board of Control for Cricket in India(BCCI) in 2008. 
I got the Dataset from https://www.kaggle.com/ramjidoolla/ipl-data-set. I also provided the datsets I have used in my analysis in this repo. By using this Dataset I want to analyze that which team won the most IPL matches, in which city most matches were played and the batsman who hitted the most sixes in IPL ...etc. 
Python libraries that I use in the notebook are

- Numpy- to perform faster Numerical operations
- Pandas - Provide many functions and makes it simple to work with data
- Matplotlib and seaborn - for Visualization

## Import Datasets Into Notebook
To import the datset into our notebook I used read_csv() function of Pandas to read(import) a csv file and do operations on it. This method takes many usefull arguments which we can use as per our need.
We can read a csv file not only locally but from URL also. To know more about it go to the documentation.

## Data Preperation and Cleaning
For this first of all we have to find 
- missing data(Rows and Columns have missing or nan values)
- unneccessary data - Duplicates and the data which are not usefull for our analysis.
- Inconsistent data - Formats and type.  
I used some techniques to deal with those data in my notebook.

## Visualization
In Notebook I tried to keep things easy to understand by visualizing answers of respective questions.
Some plots that I have used are 
- Histogram - To represent the frequency distribution of numerical data.
- Bar plot - a bar graph makes it easy to compare sets of data between different groups.
- Pie chart - It is best to use when we are trying to compare parts of a whole.  
there are more charts that i didn't use in my work like scatter plot, lineplot,boxplot...etc.

## Thank You
If you like my work then leave a star.
