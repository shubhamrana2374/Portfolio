### ITEC657 DATA SCIENCE

### Name : Shubham Rana

### Student ID : 45812713

## This is the portfolio submissions for this semester. Various portfolio's includes different scenario's on which analysis is required.

### Portfolio 1: This portfolio includes the analysis of dataset taken from the social website for cyclists 🚴 such as `Strava` and `GoldenCheetah` . These two websites are well known in the sports industry and have plenty of data recorded of their users during their rides. We have plenty of analysis using these two datasets listed below :

 a) Reading both csv files , converting their date column to similar type and joined them to collect common rows with data.

 b) Distributions of the various variables have been visualise to depict whether they are `bi-modal` ,`right skewed`, `left skewed` or `normally distributed`.

 c) Correlation has been plotted using the package of python to understand the relationship between various variables and come up with a conclusion that whether they are positively correlated or negatively correlated.

 d) Plotting plethora of scatter plot and box plots to understand the spread and distribution of the variables.
 
 e) There a part in the analysis which leads to conclusion that some factore(variables) leads to more kudos/likes 👍.
 
 For more detailed analysis on the cycling data , please refer to the __`Portfolio.ipynb`__ file in the repository.

## Portfolio 2: Data driven prediction models of energy use of appliances 🔌 in a low energy house. This portfolio has one complete dataset which has the complete energy data. The analysis covered in this portfolio has listed below:

a) Reading the csv file, change data column type for the analysis.

b) Line graphs, histogram and boxplots are used to depict the usage of appliances across all the appliances. It includes depicting the outliers in the dataset.

c) Numerous pairplots have been created to depict the `Appliances` variable relation with other variables.

d) Usage of the appliances have been illustrated weekly as well using the heatmaps.

e) We have developed a linear model as well, it comes with high MSE value (which is not good for a model). We used RFE as well to make our predictions better but still it gives high MSE value. We conclude that significant number of variables have direct impact on the model.

## Portfolio 3: Clustering Visualisation. This porfolio involves implementation of the Kmeans algorithm.

a) Generate random cluster centres (function defined : **gen_random_centres**) and assiging each centre with color green, blue, yellow and cyan respectively and their edge color is red.Centres are genrate by using the formula : (**np.random.randn(k,c)*std + mean** .

b) Visualise the clustering results in each iteration(4) by applying the k means algorithm.

c) To search for clusters, eucledian distance has been used and functions have been customized in the notebook for the same. 
    euc_dist : to calculate eucledian distance
    cluster_search : to find new clusters based on distance.
    centres_search : to find new centres.
    
 d) Iteration has been repeated for five times and in the fourth and fifth iteration there is no significant change so we stop our kmeans alogrithm on 5th iteration only.
