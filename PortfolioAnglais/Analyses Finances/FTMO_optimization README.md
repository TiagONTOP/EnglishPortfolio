# README

The `FTMOLeverageOptimazation` module is a Python class designed to optimize financial leverage as part of the FTMO (Funding for Serious Traders) test. The FTMO test is a trading challenge that, if passed successfully, allows traders to manage a funded trading account.

The `FTMOLeverageOptimazation` class contains several methods to simulate trading scenarios, calculate the probabilities of passing the FTMO test, and optimize financial leverage to maximize these probabilities.

Here is a description of the main methods of the class:

- `__init__(self, sigma, mu, n_sim, S0)`: The constructor of the class. It initializes the model parameters, including volatility (`sigma`), expected return (`mu`), the number of simulations to perform (`n_sim`), and the initial price of the asset (`S0`).

- `get_gbms(self, time_in_month, leverage)`: This method generates geometric Brownian motion trajectories, which are used to simulate price variations of the asset. The `time_in_month` parameter specifies the duration of the simulation in months, and `leverage` is the financial leverage used.

- `get_probas(self, leverage, time_in_month, target, dd_max)`: This method calculates the probability of passing the FTMO test based on the financial leverage, the test duration, the return target, and the maximum allowable drawdown.

- `objective(self, leverage, time_in_month, target, dd_max)`: This method is the objective function that is minimized when optimizing financial leverage. It returns the negation of the probability of passing the FTMO test.

- `optimize_leverage(self)`: This method performs the optimization of financial leverage. It uses Powell's minimization method to find the leverage that maximizes the probability of passing the FTMO test.

After executing the `optimize_leverage` method, the `first_best_leverage`, `first_best_proba`, `second_best_leverage`, `second_best_proba`, and `total_proba` attributes of the `FTMOLeverageOptimazation` object contain the best leverage for the first and second months of the test, the corresponding success probabilities, and the total probability of passing the test, respectively.