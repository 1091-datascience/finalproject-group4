# [GroupID] Title of your final project

### Groups
* 賴玠忠, 109753101
* 林彥賓, 109753111
* 簡筑節, 109753146
* 鄭宇軒, 108753121

### Goal
Create a model to predict the quality of red wine

### Demo 
You should provide an example commend to reproduce your result
```R
Rscript code/your_script.R --input data/training --output results/performance.tsv
```
* any on-line visualization

## Folder organization and its related information

### docs
* Your presentation, 1091_datascience_FP_group4.pptx, by **Jan. 12**
* Any related document for the final project
  * papers
  * software user guide

### data

* Source
  * Red Wine Quality
  * [Red Wine Quality Kaggle](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009)
* Input format
  * One .csv file.
  * Attribute Information
    * `fixed acidity` - most acids involved with wine or fixed or nonvolatile (do not evaporate readily);
    * `volatile acidity` - the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste;  
    * `citric acid` - found in small quantities, citric acid can add 'freshness' and flavor to wines;  
    * `residual sugar` - the amount of sugar remaining after fermentation stops, it's rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet;  
    * `chlorides` - the amount of salt in the wine;  
    * `free sulfur dioxide` - the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine;  
    * `total sulfur dioxide` - amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine;  
    * `density` - the density of water is close to that of water depending on the percent alcohol and sugar content;  
    * `pH` - describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale;  
    * `sulphates` - a wine additive which can contribute to sulfur dioxide gas (S02) levels, wich acts as an antimicrobial and antioxidant
    * `alcohol` - the percent alcohol content of the wine;
    The output feature is:  
    * `quality` - output variable (based on sensory data, score between 0 and 10);
* Any preprocessing?
  * Handle missing data
  * Scale value

### code

* Which method do you use?
  * randomForest
  * xgboost
  * CART
* What is a null model for comparison?
* How do your perform evaluation? ie. Cross-validation, or extra separated data
  * Cross-validation
  * accuracy
  * AUC

### results

* Which metric do you use 
  * precision, recall, R-square
* Is your improvement significant?
* What is the challenge part of your project?

## References
* Code/implementation which you include/reference (__You should indicate in your presentation if you use code for others. Otherwise, cheating will result in 0 score for final project.__)
* Packages you use
* Related publications


