# Valuing-European-Index-Options
Valuation of European Index Options Using Numerical Methods

### Payoff Functions
The payoff of an option is the amount received by the holder at expiration. The payoffs for European call and put options are as follows:

#### European Index Option Payoff
The payoff of a European call (put) option at expiration $T$ is given by:

$$
V_T = \max(\kappa (I_T - K), 0)
$$

where $\kappa=1$ is a call and $\kappa=1$ is a put,  $V_T$ is the payoff of the option at expiration, and $K$ is the strike price
