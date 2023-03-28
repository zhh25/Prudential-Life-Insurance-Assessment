# Prudential-Life-Insurance-Assessment
Developed a multilabel classification model to rank life insurance applications into 8 risk levels

Built 7 XGBoost binary classifiers. Each classifier predicted the probability that the risk level is higher than i, where i in 1 to 7

Chained the 7 binary classifiers in order and trained them together

Classified risk level according to the sum of 7 probabilities. The cutoff boundaries were optimized to maximize the kappa score.
