Word life Expectancy Analysis by EDA in SQL 

1. Create database, table worldlifeexpectancy following the script sql file i provided.
   
2. Connection Notebook on Azure Data Studio to MySQL database

3. Data Cleaning

a. **Handling Missing Values**:
   
   - Identify missing values in the dataset.
     
   - Decide on strategies to handle missing values.

b. **Data Consistency**:
   
   - Check for and correct inconsistencies in categorical columns like `Country` and `Status`.


c. **Removing Duplicates**:**
   
   - Identify and remove duplicate rows if any.

d. **Outlier Detection and Treatment**:
   
 -  Identify and treat outliers in columns like `Lifeexpectancy`, `AdultMortality`, and `GDP`.
   
 - Decide on strategies to handle outlier (eg. avg)
   
4. EDA

-  Basic Descriptive Stastistics

-  Query for comparation the average lifeexpectancy between the percentage rate of Developing and Developed countries

-   Query for calculating the correlation between Lifeexpectancy and AdultMortality

-   Impact of GDP, Finding the average Lifeexpectancy of countries grouped by GDP ranges (low gdp, high gdp)
