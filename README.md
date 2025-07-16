#European Options Pricing

In my other repository of "Forecasting Future Stock Prices", we have rather intuitional methods of forecasting future prices using historical simulation. However, as discussed, there are many limitations to those methods. Hence, we explore these more advanced models, namely Black-Scholes model, Laplace Transform and Monte Carlo Simulation. 
The parameters in all models can be changed accordingly as desired. 

As for the main reasons why one would prefer each method are as follows:

1. Black-Scholes
   It provides a closed-form solutions for options pricing under log-normal returns and accounts for time decay, interest rate and strike prices. It is a fairly fast and accurate way to price European options in liquid markets. However, it does come with limitations as well, where it assumes constant volatility and normal returns which may underestimate tails.

2. Laplace Transform 
   It handles complex distribution, such as jumpy and heavy tails using moment-generating functions and it is used for special options when the Black-Scholes method fails. It is mainly used when one is pricing path-dependent options with jump diffusion. However, it has its limitations too, where it is mathemtically uqite complex and is limited to certain distribution types.

3. Monte Carlo Simulation
   It is the most flexible model where it can model any return distirbution, be it Student's t-distribution or GARCH and it is also forward-looking where it simulates paths with volatility and drift, and handles path dependency such as in Asian Options. It is usually use for complex derivatives, stress testing and multi-asset portfolios. However, once again, it has its limitations as well, where it is computationally expensive.

All the above limitations mentioned are hence the reason why one would tap into risk management and look into other factors such as Value-at_Risk (VaR) and Expected Shortfall (ES) which will be under another repository in my account (soon). 
