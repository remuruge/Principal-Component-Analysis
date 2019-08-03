# Principal-Component-Analysis
ML - Use PCA for dimension reduction 

The purpose of the case study is to classify a given silhouette as one of four different types of
vehicle, using a set of features extracted from the silhouette. The vehicle may be viewed from
one of many different angles.
Four &quot;Corgie&quot; model vehicles were used for the experiment: a double decker bus, Cheverolet
van, Saab 9000 and an Opel Manta 400 cars. This particular combination of vehicles was chosen
with the expectation that the bus, van and either one of the cars would be readily distinguishable,
but it would be more difficult to distinguish between the cars.
The purpose is to classify a given silhouette as one of three types of vehicle, using a set of
features extracted from the silhouette. The vehicle may be viewed from one of many different
angles.
 
1. Data preprocessing - Understand the data and treat missing values (Use box plot), outliers.

2. Understanding the attributes - Find relationship between different attributes (Independent variables) and choose carefully which all attributes have to be part of the analysis and why

3. Use PCA from scikit learn and elbow plot to find the reduced number of dimensions (which covers more than 95% of the variance)

TO DO : Use Support Vector machines and use grid search (try C values - 0.01, 0.05, 0.5, 1 and kernal=linear, rbf) and find out the best hyper parameters and do cross validation to find the accuracy.
