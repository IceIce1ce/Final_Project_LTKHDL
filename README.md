# Final Project: House Price Analysis
In this project, we conduct two parts of data analysis, including descriptive analysis and predictive analysis. On the main part, we perform descriptive analysis on the [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) to get more intutition about the tendency of the house using on house market of Ames, Iowa from 2006-2010 throughout 79 collected features and 1460 records. Moreover, we also experiment with the predictive analysis on this dataset detail reported in **expand section** and the results are potential (125 on Kaggle competition).

Our main works are conducted on **House_Prices.ipynb**, detail about the dataset are shown in **data_description.txt**. On the descriptive parts, we utilize the **train.csv** to analyze the house sold price and others. Next, we would also predict the house price from the abovementioned features on **test.csv**, then save the result into **submission.csv**.
	
## Project Planning
You could access our project planing by click to the [Project_Planing.html](https://github.com/IceIce1ce/Final_Project_LTKHDL/blob/main/Project_Planning.html).

## Environment
Project is created with:
* min_ds-env: last updated on Sep 25, 2021
* mlxtend library version: 0.19.0
* lightgbm library version: 3.3.1
* xgboost library version: 1.5.1
	
## Setup
Activate the **min_ds-env** environment before launching to Jupyter Notebook. Install the requirements before runing the **House_Prices.ipynb**

```
pip install mlxtend==0.19.0
pip install lightgbm==3.3.1
pip install xgboost==1.5.1
```
## Descriptive Analysis
In this section, we would  analyze our observations to answer some meaningful questions belows:
- **Question 1:** How does the house prices and real-estate market changes in each year?
- **Question 2:** What are the popular neghborhoods?
- **Question 3:** How does the house purpose changes from 2006 to 2010?
- **Question 4:** How is the price of a house affected by its age?

## Predictive Analysis
We conduct house price prediction on **test.csv** and submit the result to [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) Competition.

**Kaggle score**:   0.11741

**Rank**:        125

## References
[1] Dean De Cock. (2016&asp; 08). House Prices - Advanced Regression Techniques. Kaggle. Retrieved January 01, 2022 from https://www.kaggle.com/c/house-prices-advanced-regression-techniques.

[2] ProgramerSought team. Python machine learning combat: master these four feature selection methods to improve model prediction performance. ProgramerSought. Retrieved January 05, 2022 from https://programmersought.com/article/16587300186/

[3] Ying Geng(June 7, 2020).House Price Analysis of Ames, Iowa (2006–2010). Medium. Retrieved January 07, 2022 from https://medium.com/@ying.geng5/house-price-analysis-of-ames-iowa-2006-2010-266e307f836f

## About Us
Our project includes two contributors:
- Tran Xuan Loc - 18127131 - 18127131@student.hcmus.edu.vn
- Tran Dai Chi - 18127070 - 18127070@student.hcmus.edu.vn
