Vasicek Model¶ The Vasicek model, named after economist Oldřich Vašíček, is a stochastic model widely employed in finance to describe the evolution of interest rates over time. Introduced in 1977, the model assumes that interest rates exhibit mean reversion, meaning they tend to move towards a long-term average or equilibrium level.

𝑑𝑟(𝑡) =  𝐾(𝜃−𝑟𝑡)Δ𝑡+𝜎𝑑𝑤𝑡    (1)

where:

r(t) is the short-term interest rate at time
κ is the mean reversion strength
θ is the long-run mean or the equilibrium interest rate
σ is the volatility
dW(t) is a Wiener process (Brownian motion)
