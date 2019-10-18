### ITEC657 DATA SCIENCE

### Name : Shubham Rana

### Student ID : 45812713

## This is the portfolio submissions for this semester. Various portfolio's includes different scenario's on which analysis is required.

## Portfolio 1:

1. First scenario includes anaysis on cycling and it has below parts :

 a) join two data frames which have rows have data.

 b) check for distribution , skewness is there or not ?

 c) correlation between various columns.

 d) analysis on difference between various categories of rides.

## Portfolio 2:

**Data driven prediction models of energy use of appliances in a low energy house.**

Various comparions are depicted in the notebook across all the variables. 

1) Two line graphs depicted the appliances usage across the all data.

Data is then splitted into training and testing data to fit in into regression model.

2) Histogram and box plot depicts the nature of the distribution which is right skewed and has many outliers which states many values are out of the range in the data.

3) Correlation is calculated across different variable and highlight the negative vaues between them.

4) Heatmaps depicts the usage for four different months and color coding is different for each month.

5) Linear model has been developed , it predicts value nearly correctly. MSE comes out 17.590 and R2 is 0.0002 for the model developed.

## Portfolio 3:

**Clustering Visualisation**

1) Generate random cluster centres (function defined : **gen_random_centres**) and assiging each centre with color green, blue, yellow and cyan respectively and their edge color is red.Centres are genrate by using the formula : (**np.random.randn(k,c)*std + mean** .

2) Visualise the clustering results in each iteration(4) by applying the k means algorithm.

3) To search for clusters, eucledian distance has been used and functions have been customized in the notebook for the same. 
    euc_dist : to calculate eucledian distance
    cluster_search : to find new clusters based on distance.
    centres_search : to find new centres.
    
 4) Iteration has been repeated for five times and in the fourth and fifth iteration there is no significant change so we stop our kmeans alogrithm on 5th iteration only.
