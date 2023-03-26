# Credit_Risk_Prediction

**In this dataset, each entry represents a person who takes a credit by a bank. Each person is classified as good or bad credit risks according to the set of attributes. The link to the original dataset can be found below.**


It is almost impossible to understand the original dataset due to its complicated system of categories and symbols. Thus, I wrote a small Python script to convert it into a readable CSV file. Several columns are simply ignored, because in my opinion either they are not important or their descriptions are obscure. The selected attributes are:

    - Age (numeric)
    - Sex (text: male, female)
    - Job (numeric: 0 - unskilled and non-resident, 1 - unskilled and resident, 2 - skilled, 3 - highly skilled)
    - Housing (text: own, rent, or free)
    - Saving accounts (text - little, moderate, quite rich, rich)
    - Checking account (numeric, in DM - Deutsch Mark)
    - Credit amount (numeric, in DM)
    - Duration (numeric, in month)
    - Purpose (text: car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, vacation/others)
    
    
    
### KMeans:
35.87 seems to be the mean duration and 6911.78 seems to be the mean credit amount of the cluster 1 where we have the riskiest bunch of customers

![alt text](https://github.com/Kensaroven/Credit_Risk_Prediction/blob/main/Kmeans.png?raw=true)

![alt text](https://github.com/Kensaroven/Credit_Risk_Prediction/blob/main/Kmenas%20scatter.png?raw=true)


### Hierarchial:
41.01 seems to be the mean duration and 8507.35 seems to be the mean credit amount of the cluster 1 where we have the riskiest bunch of customers

![alt text](https://github.com/Kensaroven/Credit_Risk_Prediction/blob/main/Hierarchial%20Linkage.png?raw=true)

![alt text](https://github.com/Kensaroven/Credit_Risk_Prediction/blob/main/Hierarchial%20scatter.png?raw=true)


### DBSCAN:
27.66 seems to be the mean duration and 5599.62 seems to be the mean credit amount of the cluster -1 where we have the riskiest bunch of customers

![alt text](https://github.com/Kensaroven/Credit_Risk_Prediction/blob/main/DBscan.png?raw=true)

![alt text](https://github.com/Kensaroven/Credit_Risk_Prediction/blob/main/dbscan%20hierarchial.png?raw=true)
