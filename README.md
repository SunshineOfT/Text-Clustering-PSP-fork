# Text-Clustering-PSP
Text Clustering Using K Means

Methodology
We will use a dataset provided by Sklearn to have a replicable corpus. After that, we will use the KMeans algorithm to group the vectors generated by the TF-IDF. We will then use Principal Component Analysis to visualize our groups and bring out common or unusual characteristics of the texts present in our corpus.

Here is what we’ll do

import the dataset
apply preprocessing to our corpus to remove words and symbols which, when converted into numerical format, do not add value to our model
use TF-IDF as a vectorization algorithm
apply KMeans to group our data
apply PCA to reduce the dimensionality of our vectors to 2 for visualization purposes
interpret the data
The Analysis
Our Dataset
For this example we will use Scikit-Learn’s API, sklearn.datasets, which allows us to access a famous dataset for linguistic analysis, the 20newsgroups dataset. A newsgroup is an online user discussion group, such as a forum. Sklearn allows us to access different categories of content. We will use texts that have to do with technology, religion and sport.

![image](https://user-images.githubusercontent.com/90134926/198548756-41ca4211-76e7-40b2-845f-f10364503ecb.png)
