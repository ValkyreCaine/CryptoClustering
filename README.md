# CryptoClustering

Welcome to my first crack at machine learning! 

This project works through clustering with tracking market changes in regards to crypto-currency. 
The main code walks through loading the data with pandas, scaling, modeling inertia, and clustering with SkLearn. Data is visualized with hvplot in line and scatter formats. 

The analysis answers the following questions:

**Question:** What is the best value for `k`?

**Answer:** Inertia is decreasing to begin to plateau at k=4, this is the most significant drop observed and inertia continues to dwindle minimally after k=7. The best value for k in this given scenario k would be k=4 since it represents a trade off between cluster sizes and simplicity as inertia doesn't continue decreasing by a large enough margin to warrant more clusters later. 


**Question:** What is the total explained variance of the three principal components?

* **Answer:** The total explained variance comes out to 0.89503166 or 89%.


**Question:** What is the best value for `k` when using the PCA data?

* **Answer:** The PCA data supports the K value of 4 as that is the sharpest change.


 **Question:** Does it differ from the best k value found using the original data?

  * **Answer:** No, both data points support a k value of 4 and mirror the same dwindling pattern after 7.
 

 **Question:** After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

  * **Answer:** Using PCA results in a more condensed area of clusters while also highlighting outliers despite having the same amount of clusters in the original data. This can also mean that some nuanced information in the original dataset was lost in the transformation to PCA. Overall PCA is the preferred method in this analysis as it is structured more clearly and displays less noise giving a more abstract comparison.
 
All code is writen by me with the class resources and troublshooting from the class AI tool. 
Thank you!
