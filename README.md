# Clustering


### The Data: State Legislative Professionalism

For the *second* "applied" part of the project, I will perform the three main clustering techniques (hierarchical, k-means, and Gaussian mixture models) on the Bowen and Greene state legislative professionalism data. In these data, there are four key features of interest, which record raw values for every state legislature in the U.S. from 1974-2010: 

  * Total session length 
  * Regular session length
  * Legislators' salaries
  * Expenditures per legislator

See the codebook for more details on these feature and the full set. 

### Performing k-Means By Hand

In this first part of the project, my goal is to gain a deeper conceptual understanding of the iterative process of k-means, which operates by initializing random cluster assignments, then updates cluster centroids, then cluster assignments, and so on, until convergence, which is defined by no furtehr changes to cluster configurations (i.e., optimal clusters definined by minimum sums of squares *within* clusters, and maximum sums of squares *between* clusters. 

In short, then, by answering each of the following questions, I will be performing k-means clustering "by hand" to see and demonstrate this iterative process. My simulated data includes `n = 6` observations and `p = 2` features, and should set the number of clusters, `k`, equal to two (i.e., you are hunting for 2 clusters within these data).

### Clustering State Legislative Professionalism

In the second part of this project, I will discuss the structure of these data, fit the three main clustering techniques (hierarchical, k-means, and Gaussian mixture models) on the Bowen and Greene state legislative professionalism data, and apply `r clValid` to compare three algorithms.
Next, I will discuss the validation output in more details

