# Valuing-European-Index-Options
Valuation of European Index Options Using Numerical Methods.

### Payoff Functions
The payoff of an option is the amount received by the option holder at expiration. The payoffs for European call and put options are given below.

#### European Index Option Payoff
The payoff of a European call (put) option at expiration $T$ is given by:

$$
V_T =H_T= \max(\kappa (I_T - K), 0)
$$

where $\kappa=1$ for a call and $\kappa=-1$ for a put,  $V_T$ is the payoff of the option at expiration, and $K$ is the strike price.

For a call option, the option holder hopes for the index price to increase (the market to be bullish) so that they can make a profit. At maturity, they will receive $I_T-K$ if $I_T>K$, and otherwise, they receive a zero amount. And, for a put option, the option holder hopes for the index price to decrease (the market to be bearish) so that they can make a profit. At maturity, they will receive $K-I_T$ if $I_T<K$, and otherwise they receive a zero amount.

Here's a numerical illustration for a call option. Assume that the strike $K=10$. The option holder with receive $I_T-K=2$ if the index price at maturity is $I_T=12$ or receive zero if the index price is $I_T=9$.
