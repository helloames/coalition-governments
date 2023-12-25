# coalition-governments
I modeled and predicted the proportion of cabinet ministries each party gains from being part of a winning coalition government. Each row of the csv file represents an observation/data point of a party (from European parliamentary democracies and ministries), and the data show the rewards parties gain from forming a winning coalition government. This project was my solution to the data problem from the final exam of POLISCI 189FS: Introduction to Machine Learning and Computational Models in the Social Sciences, taught by Professor Scott de Marchi at Duke University. Data set contained parties from 1986 to 2011.

**Accuracy of final model:** train R2 of 1.0, test R2 of 0.8895608931555545, train MSE of 0.0, and test MSE of 0.005653300880198345

Final model (decision tree) was overfit on training set, and my future plans for this data: 1) exploring whether or not it’s possible to get rid of interaction terms in a polynomial regression in sklearn and 2) implementing a k-fold cross validation to search for an alpha value to create a non-overfit decision tree.

**modeling.ipynb** - my code and models (networks, decision trees, polynomial regressions, XGBoost).

**class_final_proportion.csv** - the data set. cabinet_proportion is the DV; all other columns are IVs.

**model-interpretations.pdf** - write-up and interpretation of models.


**Citations (for the source of the data), courtesy of Professor de Marchi:**

Government formation as logrolling in high-dimensional issue spaces (Scott de Marchi and Michael Laver). 2020. Journal of Politics.

Government Formation in the Shadow of an Uncertain Future Election (Scott de Marchi, Michael Laver, and Georg Vanberg). Forthcoming. In Edward Elgar Handbook of Coalition Politics.
