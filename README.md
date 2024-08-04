# Bayesian-Forecaster-for-Asset-Payoffs

I create a Bayesian Asset Pricing Forecaster by exploiting the methodology from **Kacperczyk, M., van Nieuwerburgh, S., & Veldkamp, L. (2016). A Rational Theory of Mutual Funds’ Attention Allocation. Econometrica, 84(2), 571–626. https://doi.org/10.3982/ecta11412.**

The model in this repository uses sample prior beliefs about signals containing information about the variance of an asset X's payoff in a business cycle. In the first instance, the model uses the priors to update posteriors beliefs about signals containing information about the same asset X's payoff in the future when there is no regime switching and use the signals to calculate the probability density function (pdf) of the future expected payoff.

In the second instance, the model uses the priors to update posteriors beliefs about signals containing information about the same asset X's payoff in the future when there is regime switching (shifts in business cycles) and use the signals to calculate the probability density function (pdf) of the future expected payoff in (a) Expansionary Phase and (b) Recession. 

As expected, the **model correctly predicts the expected payoff of asset X to be slightly higher in recessions** (confirming the results of Kacperczyk, van Nieuwerburgh, & Veldkamp (2016)) due to greater attention allocation during more uncertainty in the financial markets. Since **investors allocate more attention to the signals about variance during recessions**, they are better able to **choose the asset that pays a higher payoff** in their portfolio, thereby enabling **efficient diversifiation**. 

