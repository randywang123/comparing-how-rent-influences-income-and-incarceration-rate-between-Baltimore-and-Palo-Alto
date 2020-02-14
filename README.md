# Mini Project 1: Comparing how rent influences income and incarceration rate between Baltimore and Palo Alto

# Summary of the project 

The project shows the relationship between average household income and incarceration rate in both Baltimore and Palo Alto, and further normalizes the income with the median rent at each place to figure out whether the rent is a big factor in this relationship. The result from data analysis shows that there is a negative relationship between Average household income and incarceration rate which means when the average household income is high, the average incarceration rate will be low. Also, median rent can make the relationship more obvious by substracting extra amount of money form the income. This can be really useful in determining whether the government should issue social welfare in certain areas to reduce the crime and violence. Moreover, this project can be used to decide whether a household would have to lead an economical way of life (has net income < 10000 USD), which can be an indication of a low income family. After people have certain ideas of what the result is like, they can continue to work on how much social walfare should be invested on the development of certain areas when more data is available. 

# Step-by-Step Analysis 

## Data Selection 

- It takes some time to figure out how Opportunity Atlas works. The preset counties and tracts are not quite useful because it will give the result of the entire United States, which is not what reqired for this project. Then, I decided to use the "Just what is on the screen" to get the 210 records of data for Baltimore and 45 records of data for Palo Alto. Moreover, then for the neighborhood information, we need to get the corresponding neighborhood data by scrolling down to the very end of the page and select what we really need for the project. 

## Data Preprocessing 
- We removed empty columns and clean all empty cells in order to make sure that we won't have problems when running the program. If there are some issues like something doesn't work, please email me at zwang191 @ jhu .edu 

## Data Analysis

- Read the document online about all the data collected by tracts and use the specific rows or columns to do the operation. In this case, we used several pivotTables to get the relationship, VLOOKUP to get the median rent from other files, do the if statement to check if the net income after paying the rent can make the household poor or not. 

# Data Visualization 

- ![image1](./image/bii.png)
- ![image2](./image/bri.png)
- ![image3](./image/brent.png)
- ![image4](./image/pii.png)
- ![image5](./image/pri.png)
- ![image6](./image/prent.png)

