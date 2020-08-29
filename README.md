# crypto-prediction
This is the web application for predictions based on my previous repo to source crypto currency prices. 
Using only the historical data link from CMC, the application will fetch historicall data first.
The, data is then preprocessed for machine learning, adding indicator values like, Moving Average, Exponential Moving Avereges, etc.
Afterwards, the backend of the application will use an ensemble machine learning technique on the backend to create three price predictions. 
One using Linear regression, the others two using Lasso and Ridge regression.
The predictions are averaged together, and fed forward through the prediction algorithm. 
This is done for seven days, but can be adjusted to predict more or less. 

[![IMAGE FOR VIDEO](https://i.ytimg.com/vi/0oPGMa4ihvI/hqdefault.jpg?sqp=-oaymwEZCNACELwBSFXyq4qpAwsIARUAAIhCGAFwAQ==&rs=AOn4CLCS_5CLu1NxJ0ELxpHDGQdGx2k2Ug)](https://youtu.be/0oPGMa4ihvI)

The above PREDICTION MODEL is for information purposes only. It is not intended to be investment advice. Seek a duly licensed professional for investment advice.
