# Variance
# Language: Python
# Input: CSV (weights)
# Output: TXT (variance in weights across rows)

PluMA plugin to compute variance.  The plugin takes as input a CSV
file with rows representing samples and columns holding the datasets,
with entry (i, j) the value of dataset j in sample i.  The plugin
computes the variance of each dataset as a textfile with two columns:
the name of the dataset and its variance.
