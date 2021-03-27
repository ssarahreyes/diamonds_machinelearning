
### :arrow_right: **Diamond Price Predition** 
In this project I have analyzed the data of more than 40.000 diamonds and have used different machine learning models in order to predict the price of other diamonds.

![Image](https://cisp.cachefly.net/assets/articles/images/resized/0000891341_resized_diamonds1022.jpg)



### :white_check_mark: **Status**
Ironhack Data Analytics Project Module 3: Diamond Price Predition.



### :computer: **Technology stack**
In this project it is been used Python, Pandas, Seaborn and Plotly to make an exploratory process of the data and to draw some explanatory plots and different machine learning models in order to achieve the minimum RMSE:
- Linear Regression.
- Random Forest.
- Decision Tree Regressor
- KNeighbors Regressor
- XGB Regressor
- LGBM Regressor
- Extra Trees Regressor


### :zap: **EDA Results**
After doing the data exploratory process in Jupyter Notebook, our main conclusions are:
- Carat is the most relevant characteristic of a diamond's price.
- Fair is the cut form that have diamonds with higher carat. This is the reason that even being the worst cut form, have a higher average price.
- Premium cut form together with I and J colors, are the most expensive diamonds although this colors are two of the lowest quality. This is because of the carat weight of I and J diamonds.
- As for Clarity, I1 and SI2 have two of the lowest clarity qualities but, as there a lot I and J color diamonds, the price is higher.
- Also, J and I are the colors with biggest diamonds.



### :rocket: **Machine Learning Prediction Results**
For predicting the price, the best model appears to be XGB Regressor with a RMSE of a 532 aprox. (calculated using cross validation).

Also I have used the Pipeline process in order to do the preprocessing data and try different machine learning models at the same time. The result appears to be the same, XGB Regressor is the best model.


### :wrench: Technology Stack
- Python==3.8.5
- pandas==1.1.3
- seaborn==0.11.0
- numpy==1.19.2
- scipy==1.5.4
- 
[...]


### :file_folder: Folder structure
```
└── project
    ├── .gitignore
    ├── README.md
    ├── notebooks
    │   ├── diamonds_pipeline.ipynb
    │   ├── diamonds_differentmodels.ipynb
    └── data
```



### :love_letter: Contact info
Doubts? Advice? Drop me a line! :smirk:
