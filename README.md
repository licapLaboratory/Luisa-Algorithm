# Luisa-Algorithm
LUISA - An algorithm for Feature Selection based on the causality relation.

Non-casual feature selection methods may incur errors regarding feature relevance because they use one selection criteria, which can lead to spurious correlations. The current causality methods of feature selection consider only the features that compose the Markov Blanket of one target variable (class) as relevant. That may lead to disregarding relevant features.

We present a new algorithm, LUISA, based on the causality relationship. This algorithm expands the Markov Blanket to include indirect ancestors for a specific target variable or class. We test the algorithm in several synthetic and real databases. After LUISA performed the feature selection, the reduced real databases were submitted to the classifiers Random Forest and Naive Bayes to evaluate their accuracy, considering the complete database and other feature selection methods.

The results show that LUISA selected the relevant features in the synthetic data sets and fewer features than other feature selection methods. In addition, the classifiers showed promising results when using the reduced data set compared to the complete data set and with different feature selection methods.
