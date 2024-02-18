# Medical-Insurance-Cost-Prediction

Skip to main content
Medical Insurance Cost Prediction.ipynb
Medical Insurance Cost Prediction.ipynbC_Notebook unstarred
All changes saved
Files
..
Drop files to upload them to session storage.
Disk
81.40 GB available
This directory includes a few sample datasets to get you started.

california_housing_data*.csv is California housing data from the 1990 US Census; more information is available at: https://developers.google.com/machine-learning/crash-course/california-housing-data-description

mnist_*.csv is a small sample of the MNIST database, which is described at: http://yann.lecun.com/exdb/mnist/

anscombe.json contains a copy of Anscombe's quartet; it was originally described in

Anscombe, F. J. (1973). 'Graphs in Statistical Analysis'. American Statistician. 27 (1): 17-21. JSTOR 2682899.

and our copy was prepared by the vega_datasets library.

n: int = ..., Return the last `n` rows. This function returns last `n` rows from the object based on position. It is useful for quickly verifying data, for example, after sorting or appending rows. For negative values of `n`, this function returns all rows except the first `|n|` rows, equivalent to `df[|n|:]`. If n is larger than the number of rows, this function returns all rows. Parameters ---------- n : int, default 5 &nbsp;&nbsp;&nbsp;&nbsp;Number of rows to select. Returns ------- type of caller &nbsp;&nbsp;&nbsp;&nbsp;The last `n` rows of the caller object. See Also -------- DataFrame.head : The first `n` rows of the caller object. Examples -------- ``` >>> df = pd.DataFrame({'animal': ['alligator', 'bee', 'falcon', 'lion', ... 'monkey', 'parrot', 'shark', 'whale', 'zebra']}) >>> df animal 0 alligator 1 bee 2 falcon 3 lion 4 monkey 5 parrot 6 shark 7 whale 8 zebra ``` Viewing the last 5 lines ``` >>> df.tail() animal 4 monkey 5 parrot 6 shark 7 whale 8 zebra ``` Viewing the last `n` lines (three in this case) ``` >>> df.tail(3) animal 6 shark 7 whale 8 zebra ``` For negative values of `n` ``` >>> df.tail(-3) animal 3 lion 4 monkey 5 parrot 6 shark 7 whale 8 zebra ```, hint
Creating a copy…
