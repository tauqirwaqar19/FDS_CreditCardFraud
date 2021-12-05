# Dataset Description 

The dataset for this project can be taken from [here](https://www.kaggle.com/mlg-ulb/creditcardfraud)

The dataset used for this project was obtained from kaggle.
The dataset covers credit card transactions completed by European cardholders dated September 2013.In this dataset, we have **492** frauds out of **284,807** transactions that occurred during a span of two days. The dataset is heavily skewed, with the positive class (fraudulent transactions) comprising only 0.172 percent of all transactions.

The dataset only has numerical input variables that have undergone a **Principal component analysis** (PCA) transformation. It is not possible to obtain the original features of the data and further background information about the data period since bank data is highly confidential and restricted. The major components derived with PCA are features V1, V2,... V28; the only features not modified with PCA are 'Time' and 'Amount.' The seconds lapsed amongst each transaction and the very first transaction in the database are stored in the feature 'Time.'
The transaction Amount is expressed by the feature 'Amount,' which can be utilized for illustration-reliant cost-sensitive learning. The target variable is called 'Class,' and it has a value of 1 whenever there is fraudulent transaction  and 0 if it is a normal transaction.

Google Doc for the same is available [here](https://docs.google.com/document/d/1eido7n7AkYn8oKyo0qj1pjeiorpUMpefBzz58AeZ0b0/edit#heading=h.rfzdwltk9jq3)
