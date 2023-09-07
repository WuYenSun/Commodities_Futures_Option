# Commodities_Futures_Option

This repository showcases the implementation of four distinct commodity futures option pricing models:
- Bachelier (1900) Model
- Black (1976) Model
- Heston (1993) Model
- Quadratic Normal Model (Bouchouev, 2023)

We have diligently implemented each of these models using at least two different methods to ensure the accuracy and reliability of our implementations.
![option_price](https://github.com/WuYenSun/Commodities_Futures_Option/blob/main/option_price.png)

Additionally, we provide a mapping of the option prices computed from these four models to two important domains of implied volatility: Implied Black Volatility (IBV) and Implied Normal Volatility (INV).

![IBV](https://github.com/WuYenSun/Commodities_Futures_Option/blob/main/ibv.png)
![INV](https://github.com/WuYenSun/Commodities_Futures_Option/blob/main/inv.png)

It's worth noting that both the Heston and Quadratic Normal models have the capability to produce the volatility smirk or smile commonly observed in real-world markets. This feature enhances their ability to capture market dynamics. 
One intriguing observation is that the IBV for the WTI (West Texas Intermediate) market exhibits negative skewness. 
This observation implies that the dynamics of the underlying futures price are closer to the arithmetic Brownian motion specified in Bachelier (1900) than the geometric Brownian motion specified in Black (1976).
