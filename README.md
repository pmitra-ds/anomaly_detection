# anomaly_detection with credit card data
In this project we dive into anomaly or fraud detection with the  kaggle credit card dataset (source:). The datafile contains 26 features including amount of money spent for each user, a timing information of the trasaction and many other sensitive user information which are presented in an abstract way via PCA trasformation to protect privacy isssues. One point to stress here is that, the dataset is highly imbalanced, with the ratio of fraud to valid data about 0.17%, this makes the classification problem extremely challenging.

Before jumping into building models, first let's have a look at the data, where the amount of money spent is plotted against all the other features for the two classes. It appears that there is no visible correlation between amount and transaction time, but other parameters like V10,V12,V13 seem to have very clear separation between the two classes.  
![Example Figure](example.gif) 
