# multiCriteriaDimReduction
Multi-Criteria Dimensionality Reduction

This repo contains the codes of the paper Multi-Criteria Dimensionality Reduction with Applications to Fairness.

The .py files contain helper methods for:
- preprocessing the data
- standard PCA and calculating several utility criteria of fairness
- solving SDP
- using mutiplicative weight update method for some types of objective functions
- other helper methods

Each of the Jupyter notebooks shows how to apply one of the PCA strategy (fair SDP-based PCA vs standard PCA) to each of the dataset (Credit and Income data). The MW notebook implements MW (multiplicative weight update) instead of using SDP solver for the fair SDP-based PCA.

To use, we recommend opening one of the Jupyter notebook and run the notebook. You can check the format of the data and see an example usage, and apply to your own datasets. For more details of usage, each method (MW, fair SDP-based PCA, std_PCA, etc.) has documentation of usage in corresponding .py files, including what to expect as an input and output.
