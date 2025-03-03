The research team creates a file where all stocks across the world are ranked/scored on the relevant "factors".

This code uses that file and selects Indian equities. It then creates the combined factor score.

We introduce a sector and market cap contraint and remove illiquid securities.

We also patch the existing portfolio and the benchmark portfolio.

Based on all the constraints and the new scores, we create a recommended portfolio.

We patch this into one master file which has information about all stocks in India.

This output files becomes the base to rebalance the portfolio and to generate analytics about the current / proposed and benchmark portfolio.

I have not uploaded any input files due to confidentialtiy. 
