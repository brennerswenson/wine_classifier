# Wine Grape Variety Classifier

# POST ON MEDIUM REGARDING FINDINGS
- https://medium.com/@brenner.swenson/predicting-expensive-wine-grape-varieties-65d92287b38d

### A random forest classifer which uses data from Kaggle.com 
- (https://www.kaggle.com/zynicide/wine-reviews)


### Motivations for projects
- I've always loved wine and wanted to know which characteristics are the most important in determining the grape variety in a classifier model. Also I wanted to know the general descriptive statistics with aggregate functions.

### Libraries used: 
- pandas 
- numpy 
- matplotlib 
- seaborn 
- scikitlearn

## Files in repository:
- wine.html: html representation of Jupyter Notebook
- wine.ipynb: Jupyter Notebook used for analysis
- winemag-data-130k-v2.csv: data
- winemag-data-130k-v2.json: data
- winemag-data_first150k.csv: data

## Summary of analysis findings:
- Contrary to my preconceptions, France is not the highest contributor to the expensive wine market
- `Tinta de Toro` grapes produce the most expensive wine
- France's price variance is much higher than any other country
- The US produces the most expensive wines
- `price` and `points` are the most important features when classifying a wine's grape variety
