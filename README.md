# Dynamic time series clustering via volatility change-points

A method for clustering time series based on a statistical model in which volatility shifts at unobserved change-points.
Clustering is performed using a probability metric evaluated between posterior distributions of the most recent change-point associated with each series. This implies series are grouped together at a given time if there is evidence the
most recent shifts in their respective volatilities were coincident or closely timed. The clustering method is dynamic, in that groupings may be updated in an online manner as data arrive. Numerical results are given analyzing daily returns of constituents of the S\&P 500.

[Get the arXiv posting here](xxx), including a review of the literature on financial time series clustering, mathematical derivations and discussion of results.

[For best rendering of formuale view the Jupyter notebook here...](https://nbviewer.jupyter.org/github/nckwhiteley/volatility-change-points/blob/master/clustering%20via%20volatility%20change%20points.ipynb)



