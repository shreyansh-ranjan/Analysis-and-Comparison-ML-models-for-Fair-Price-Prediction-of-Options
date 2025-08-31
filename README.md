# Analysis-and-Comparison-ML-models-for-Fair-Price-Prediction-of-Options-
This project explores the the usability of MLP(Multi Layer Perceptron) and other ML models in finding the "fair" price of a options price. The options in this project are synthetically created and replicate the NIFTY option chain (specifically European call options).
So, here we have used 6 variables for finding price of any option. They are: 
1. S: Spot price
2. K: Strike price
3. T: Time to maturity (in years)
4. r: Risk-free interest rate (decimal, e.g., 0.03)
5. sigma: Volatility (decimal)
6. option_type: "call" samilarly we can do it for "put" options also......

We have generated the synthetic data using **Geometic Browninon motion** (sorry if the spelling is wrong. I am terrible at them). We have used **Monte Carlo Simulation** to find the ground truth for training the data.

**This is just venilla project we shall be increasing the complexity of the models and will incorporate the time series data in the next phase of the project. The project will strictly focus on Indian option market.**
