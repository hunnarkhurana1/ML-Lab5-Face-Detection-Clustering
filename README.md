Answers:
1. What are the common distance metrics used in distance-based classification algorithms?
Common distance metrics include Euclidean (L2), Manhattan (L1), Minkowski (Lp), and Chebyshev
(L∞). In high-dimensional or text-like data, cosine distance is also widely used. For binary or categorical
features, Hamming distance is common, and for correlated features, Mahalanobis distance can be useful.
2. What are some real-world applications of distance-based classification algorithms?
They are used in face recognition and image retrieval, recommendation systems (finding similar
users/items), document and spam classification, medical diagnosis (nearest patient cases), anomaly/fraud
detection, and customer segmentation based on behavioral similarity.
3. Explain various distance metrics.
Euclidean measures straight-line distance and works well when features are scaled and continuous.
Manhattan sums absolute differences and can be more robust in higher dimensions. Minkowski is a
general form that becomes Manhattan when p=1 and Euclidean when p=2. Chebyshev uses the maximum
coordinate difference, so it reflects the worst-case feature difference. Cosine distance compares the angle
between vectors, so it focuses on direction rather than magnitude.
4. What is the role of cross validation in model performance?
Cross-validation estimates how well the model will generalize to unseen data by testing it on multiple
train-validation splits. It reduces the risk of overfitting to one split and is the standard way to tune
hyperparameters (like K in KNN) based on reliable performance estimates.
5. Explain variance and bias in terms of KNN?
With a small K, KNN has low bias but high variance: it fits local noise and can change a lot with small
data changes. With a large K, variance drops but bias increases: predictions become smoother and may
ignore real local structure. Choosing K via cross-validation balances this trade-off for the best
generalization.
