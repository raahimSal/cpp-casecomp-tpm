# CPP Investments Intern Case Competition
Factor investing portion of the CPP Investments intern case comp. 

Objcetive was to find a way to quantify factor exposures to a Brazilian stock. 

Since the company was a consumer retail company, the notebook uses Brazil's top exports as a way to gauge the health of the company. 
This was calculated using a multi-variate linear regression using various exports of Brazil onto the stock's daily returns. 

The next objective was to create a mean-variance optimized portfolio with the stock. This was done using cvxpy. 

Here is the portfolio v.s. the stock we are trying to minimize the risk of.

![port vs comp](https://github.com/raahimSal/cpp-casecomp-tpm/blob/master/Portfolio_vs_company.png)

As can be observed the variance of the portfolio is much lower than the variance of the individual stock, and we can diversify the risk this way. 

![const](https://github.com/raahimSal/cpp-casecomp-tpm/blob/master/ind_performance.png)
