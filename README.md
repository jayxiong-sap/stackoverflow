### Table of contents
1. [Motivation](#motivation)
2. [Libraries used](#library)
3. [File Descriptions](#files)
4. [Summary of the analysis](#summary)

## 1. Motivation <a name="motivation"></a>

This is a project about introduction to data science.  The purpose is to practice data wrangling, data visualization on findings from the dataset, machine learning model creation, prediction by using the model. In addition, the project also wants the data scientist to communicate the techniques used, and interesting insights I found via a blog.  

## 2. Libraries used <a name="library"></a>

The following Python libraries are used in this project, 
- numpy
- pandas
- matplotlib
- seaborn
- sklearn (ColumnTransformer, OneHotEncoder, train_test_split, LinearRegression, metrics)

## 3. Files Descriptions <a name="files"></a>

- README.md
  The readme file of the project, introducing the motivation of the project, the libraries used, files included and a summary of the analysis results
  
- z_airbnb_data_analysis.ipynb
  The jupyter notebook that has all the code and their documentation
  
- listings.csv
  The dataset used for analysis, and the dataset is Seattle's Airbnb property listing data
  
## 4. Summary of the analysis <a name="summary"></a>
  I believe property types, number of bedrooms, neighbourhood groups, rating socres are correlated to each other in some way.  
  
  - 1 bedroom is the highest number of availalbe bedroom type, across all types of properties
  - Most property types have high rating scores (between 90 and 100). Apartment has the widest range of review score ratings. House has the second widest
    range of review score ratings. 
  - Townhouse and Bungalw appear to be among the highest rated property types. Townhouses are highly rated at neighbourhoods areas like Beacon Hill,
    Capitol Hill, Cascade and Queen Anne. Bungalows are highly rated at neighbourhood areas like Ballard and Queen Anne
  - Other than "Other neighborhoods", the Capitol Hill and Downtown neighbourhood groups have the highest number of properties

  Finally, I believe the above features will impact price too, so I used them to predict the price. 
