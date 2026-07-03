# ML From Scratch

Ten classical machine learning algorithms implemented using only NumPy — no Scikit-learn.

## Why

Libraries like Scikit-learn hide the math behind a `.fit()` call. Implementing each algorithm by hand forces an understanding of what's actually happening — the gradient, the loss function, the update rule — not just how to call a function.

## Algorithms implemented

- Linear Regression (gradient descent and the normal equation)
- Logistic Regression (sigmoid, binary cross-entropy)
- Decision Tree (information gain, ID3)
- K-Means Clustering (k-means++ initialization)
- PCA (via eigenvectors of the covariance matrix)
- Random Forest (bootstrap aggregating)
- Naive Bayes (text classification)
- K-Nearest Neighbors (multiple distance metrics)
- Ridge and Lasso Regression (L2/L1 regularization)
- Linear SVM (simplified primal form)

## Structure

Each algorithm has its own file with the implementation and a README section explaining the math derivation alongside the code.

## Author

Salik Hussain — github.com/salikhussain71-code

## License

MIT
```
