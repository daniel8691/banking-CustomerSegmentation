# banking-CustomerSegmentation

### Data Cleaning
* Replaced null values with the mean for the features: Minimum payments and Credit Limit
* Dropped Customer ID column as it doesn'thelp with the analysis

### Machine Learning
* Normalized data using StandardScaler
* Find the best k value by testing clusters numbers from 2 to 20 and graphing (elbow test)
* Fit data into the Kmeans model to determine cluster numbers for each datapoint

### Visualized the features of each clusters
![alt text](https://github.com/daniel8691/banking-CustomerSegmentation/blob/master/cluster_analysis_SS/pic1.jpg)
![alt text](https://github.com/daniel8691/banking-CustomerSegmentation/blob/master/cluster_analysis_SS/pic2.jpg)
![alt text](https://github.com/daniel8691/banking-CustomerSegmentation/blob/master/cluster_analysis_SS/pic3.jpg)
![alt text](https://github.com/daniel8691/banking-CustomerSegmentation/blob/master/cluster_analysis_SS/pic4.jpg)
![alt text](https://github.com/daniel8691/banking-CustomerSegmentation/blob/master/cluster_analysis_SS/pic5.jpg)
![alt text](https://github.com/daniel8691/banking-CustomerSegmentation/blob/master/cluster_analysis_SS/pic6.jpg)

### Findings

Transactors: Customers who pay the least amount of interest charges and careful with their money
* Cluster 4
* Cluster 0 - Low purchase frequency, low credit limit, around average % full payment

Revolvers: customers who use their CC as a loan. this group is the most lucrative sector for the bank since they pay 20%+ interest.
* cluster 3, 5 both have very low minimum payment percentage

New Customers:
* cluster 7: moderate blanace, moderate balance frequency, low credit limit

VIP/Prime: customers with high credit limit/% full payments, targeted to increase their credit limit/spending
* cluster 4: highest credit limit and purchases among the clusters with the highest % full payments
* cluster 6: high credit limit and higher than average % full payments


Clients tend to stay with the company for long periods of time with the average tenure at 11.27 years
