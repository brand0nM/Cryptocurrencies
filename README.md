# Cryptocurrencies
## Overview
An investment bank wants to offer a cryptocurrency portfolio, but they need to know how to group and classify each investment. We've been hired to create an unsupervised model that auto generates clusters based on the data's "important features;" These models are seen as flexible since they can use an entire dataset and ignore pairing inputs/outputs. Unsupervised learners are primarily used in determining non-linear clustering rather than predicting a classification.

### Purpose
Preprocess the data; convert categorical variables to booleans and normalize with StandardScaler. Then fit the KMeans model of varying cluster sizes to plot an elbow curve and determine an ideal amount of clusters. Use this number to predict and visualize how each principle component affects its categorization.

## Analysis
### Dendrogram
Dendrograms can help determine the number of clusters; however, no obvious patterns have emerged- and understandably so for this dataset.<br/><br />
<img width="790" alt="Screen Shot 2022-07-29 at 11 05 41 AM" src="https://user-images.githubusercontent.com/79609464/181809532-bd268bbe-eeba-4d50-8f80-672e8fa0b166.png">

#### Elbow Curve
A cluster size 4 was chosen based on this elbow curve <br /><br/>
<img width="663" alt="Screen Shot 2022-07-29 at 11 05 26 AM" src="https://user-images.githubusercontent.com/79609464/181809641-bcf9c7d3-ad31-430f-a7e7-bd5576743c35.png">

### Results
#### 3-D Plot
<img width="685" alt="Screen Shot 2022-07-29 at 11 04 49 AM" src="https://user-images.githubusercontent.com/79609464/181809748-347077f9-aeed-45b4-bd61-fbf75d2479fc.png">

#### 2-D Plot
<img width="667" alt="Screen Shot 2022-07-29 at 11 05 07 AM" src="https://user-images.githubusercontent.com/79609464/181809771-3c13a975-2f61-4b7b-b336-9460e9f8096c.png">

## Summary
We've successfully processed the Crypto data for machine learning, clustering each coin into 4 groups with an unsupervised model
