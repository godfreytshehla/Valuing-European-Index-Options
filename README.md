# Valuing-European-Index-Options
Valuation of European Index Options using Numerical Methods

### Payoff Functions
The payoff of an option is the amount received by the holder at expiration. The payoffs for European call and put options are as follows:

#### European Call Option
The payoff of a European call option at expiration $ T $ is given by:

$$
C_T = \max(I_T - K, 0)
$$

where:
- $$ C_T $$ is the payoff of the call option at expiration
- $ I_T $ is the price of the index at expiration
- $ K $ is the strike price

#### European Put Option
The payoff of a European put option at expiration $ T $ is given by:

$$
P_T = \max(K - I_T, 0)
$$

where:
- $ P_T $ is the payoff of the put option at expiration
- $ I_T $ is the price of the index
