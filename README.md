# EDA-of-Medical-Cost-Insurance-data---Kaggle
This project is exploratory data analysis of Medical Cost Personal Dataset acquired from Kaggle. The libraries involved to perform the analysis are - python's pandas, numpy, seaborn, matplotlib, missingno.
Below are the steps summarizing the whole project :
1. Basic EDA : Shape of the dataframe(1338, 7), Statistical Analysis using describe function, columns in the dataset, memory used by the data set(73.3 + KB), Scatter plot and correlation matrix to look for correlation.
2. Missing Values : Library used missingno - generated matrix to look for missing values, isnull() method to cross check the presence of outliers in the data.
3. Duplicate values : Locations 195 and 581 have duplicate values, used .duplicated() method on the data frame. 
4. Detecting Outliers : Scatter and boxplot to spot the outliers in the data(columns age, bmi and charges have outlier values).
5.Data analysis : Formed visualizations based upon questions -    
  a. Mean value of children covered under insurance based on gender    
  b. Average charges incurred by each age group(line plot).    
  c. Mean body mass index based upon age(line plot)    
  d. Are charges incurred different for smoker and non-smoker.(bar plot)   
  e. People from which region incurred more medical costs.(bar plot)
  f.  Which region has more number of people enrolling for the insurance scheme(bar plot)    
  g. Were there more number of smokers who enrolled for insurance(bar plot)   
  h. What is the gender of the people who generally smoke(bar plot)    
