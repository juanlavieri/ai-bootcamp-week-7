# Correlation Conquerors

In this activity, you’ll have an opportunity to use SciPy to compare factors across Scikit-learn's wine recognition dataset.

The wine recognition dataset includes "the results of a chemical analysis of wines grown in the same region in Italy by three different cultivators." Measurements of different constituents are taken for three types of wine.

**Note:** This dataset contains a typo ("flavanoid") that we have retained in the code to minimize confusion.

## Instructions

1. Open the starter notebook from the unsolved folder.

2. Execute the starter code to import the wine recognition dataset from Scikit-learn.

3. Using the dataset, plot the factors flavonoids and malic acid against each other on a scatter plot. Is this relationship positively correlated, negatively correlated, or not correlated? How strong is the correlation?

4. Calculate the Pearson's correlation coefficient for  malic acid versus flavonoids. Compare the correlation coefficient to the following strength of correlation table. Was your prediction correct?

    ![correlation strength table.](Images/correlation_table.png)

5. Plot the factors color intensity versus alcohol on a scatter plot. Is this relationship positively correlated, negatively correlated, or not correlated? How strong is the correlation?

6. Calculate the Pearson's correlation coefficient for alcohol versus color intensity. Compare the correlation coefficient to the Strength of Correlation table. Was your prediction correct?

## Bonus

* Review the [Pandas documentation](https://pandas.pydata.org/pandas-docs/stable/) to find how to generate a correlation matrix. This matrix will contain the Pearson correlation coefficient for all pairs of factors in the DataFrame.

* Generate the correlation matrix, and try to find the pair of factors with the strongest positive and negative correlations.

## Reference

[Scikit-learn’s wine dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_wine.html#sklearn.datasets.load_wine) originally sourced from https://archive.ics.uci.edu/ml/datasets/wine

- - -

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
