# instagram_reach
 Predicting the reach of Instagram posts
Pre-requisites:
Jupyter Notebook in Vscode
Github
Vscode 
Python 3+ installed on your system with packages:
Pandas
Plotly
Matplotlib
Numpy
statsmodels
seaborn
sklearn

Dataset:
Instagram-Reach.csv: Contains the the instagram reach per day
Instagram.csv: contains Impressions,From Home,From Hashtags,From Explore,From Other,Saves,Comments,Shares,Likes,Profile Visits,Follows,Caption,Hashtags of all the posts made by the user 

reach_forecast:this does reach forecasting on basis of instagram reach per day using a time series forecasting model called SARIMA (Seasonal Autoregressive Integrated Moving Average) method.

main: this does prediction on the basis of all posts made by the user using supervised machine learning for regression using the PassiveAggressiveRegressor model from scikit-learn library.The model predicts the corresponding 'Impressions' value based on these features: 'Likes', 'Saves', 'Comments', 'Shares', 'Profile Visits', and 'Follows'