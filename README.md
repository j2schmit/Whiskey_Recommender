# Whiskey_Recommender
An exploration of a whiskey dataset ( https://www.mathstat.strath.ac.uk/outreach/nessie/nessie_whisky.html) from the University of Strathclyde in Glasgow Scotland, which contains a profile of 86 single malt Scotch whiskies.

 A series of multivariate analysis (aka unsupervised learning) methods have been applied with the goal of identifying groups of whiskies. Then a recommender system is developed, based off of the groupings and other dimensionality reduction techniques. The findings indicate that there are 4 clear groups. Furthermore, the groupings do not seem to indicate that region (i.e. Highlands, Islay, Speyside, etc) is highly correlated with the groups, but there is definitely some correlation.
 
 The file whiskey.ipynb shows the entire process from exploratory data anaysis to final model selection and refinement. A series of unsupervised clustering algorithms were used, in addition to PCA and NMF. THe final model consisted of the Non-negative Matrix Factorization (NMF), where the parameters were tuned using information from the previously applied clustering algorithms. 
 
 The file whiskey_recommender.ipynb consists of a recommender system built as a python script, which takes as input one of the 86 single-malt distillers, and outputs 3 other similar choices, as well as the flavor profile and geographical mapping of all four distilleries.
