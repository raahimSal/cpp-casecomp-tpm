# cpp-casecomp-tpm
Factor investing portion of the CPP Investments intern case comp. 

Objcetive was to find a way to quantify factor exposures to a Brazilian stock. 

Since the company was a consumer retail company, the notebook uses Brazil's top exports as a way to gauge the health of the company. 
This was calculated using a multi-variate linear regression using various exports of Brazil onto the stock's daily returns. 

The next objective was to create a mean-variance optimized portfolio with the stock. This was done using cvxpy. 
