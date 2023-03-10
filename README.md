# Alphabet_Soup_Deep_Learning
Module 21 Challenge

For this assignment I trained and optomized a series of models attempting to predict the success of applicants. 

Before tackling the models, I cleaned up the data. I made a bunch of dummy columns. I created an 'other' category comprised of all the smaller values. I dropped the EIN and NAME Columns. 

For the models, I started with a Linear Regression and an XGBoost to get a performance baseline. After those models I tried a few configurations of Neural Networks. 
The most successful model was the last one I tried, where I used a different activation function. The difference was small but clear. 
