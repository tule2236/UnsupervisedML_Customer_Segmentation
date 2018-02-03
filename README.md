# Motivation
Customer segmentation is the task of dividing customers into groups of individuals that are similar aspects relevant to marketing, such as
- Demographics: age, race, religion, gender, education level, income, ethnicity
- Psychographics: social class, personality characteristic, lifestyle
- Behavioral: spending habits, consumption, usage, and desired benefits
- Geography: where they live, and work

The purpose of customer segmentation is targeting specific groups of customers, allowing effective allocation of marketing resources and thus, maximizing cross-and-up-selling opportunities. Marketing materials delivered to customers using customer segmentation tend to be more valued and appreciated by customers as opposed to impersonal brand messaging that doesn’t acknowledge purchase history and customer relationship. 
How to implement customer segmentation results into marketing strategies:
-	Send customers special offers that encourage them to buy more products
-	Improve customer service
-	Assist in customer loyalty and retention

# Data Description
We investigate customer segmentation problem by clustering on ‘Bike Sale’ dataset which including 3 files related to customers, products and orders information. First, we need to merge 3 files together based on their common Customer ID and Product ID. We are interested in deciding the preference of bikes that each customer ‘bike shop’ have. Therefore, we need to process our data into a format with row containing bike shop name and features are the bike model. The hypothesis for our customer trends is that bike shops purchase certain bike models based on features such as bike categories (Mountain or Road) and price tier (high or low). Although we will use bike model to cluster on, the bike model features such as price, category will be used for assessing the preference of the customer clusters. 
# Prerequisites
- [Jupyter Notebook](http://jupyter.org/install)
- [Python](https://www.python.org/downloads/release/python-364/)
# Running the Tests
I have designed many experiments to test the performance of 2 popular unsupervised algorithms which are K-means and Expectation Optimization. I also implemented 3 dimensionality reduction algorithms _ Principle Component Analysis (PCA), Independent Component Analysis (ICA), Random Projection (RP) to explore how dimension size effects the performance of clustering. The result of clustering on “Bike Sale” datasets are stored in [ICA_Cluster_Result](https://github.com/tule2236/Customer_Segmentation/tree/master/ICA_Cluster_Result),[PCA_Cluster_Result](https://github.com/tule2236/Customer_Segmentation/tree/master/PCA_Cluster_Result), [k_means_Result](https://github.com/tule2236/Customer_Segmentation/tree/master/k_Means_Result).

