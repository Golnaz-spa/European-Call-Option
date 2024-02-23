# European Call Option Pricing with Binomial Lattice

This project demonstrates the valuation of European call options using the Binomial Lattice method, a popular numerical method in financial engineering for pricing options. The valuation is performed across various strike prices to analyze the option's value sensitivity to changes in the strike price. The project utilizes Python for implementing the Binomial Lattice model and visualizing the results.

## Project Overview

- **Objective**: To price European call options using the Binomial Lattice method and to visualize how the option's value changes with different strike prices.
- **Methodology**: The Binomial Lattice model creates a discrete-time lattice to model the possible paths that the underlying asset price can take until the option's expiration. The option value is calculated by stepping back through the lattice from expiration to the present.
- **Visualization**: The relationship between various strike prices and the option values is plotted to provide insights into the option's sensitivity to the strike price.

## Key Components

- **Binomial Lattice Model**: A financial model that calculates the option value by simulating the underlying asset price's possible future paths.
- **European Call Option**: A type of option contract that gives the holder the right, but not the obligation, to buy the underlying asset at a specified price (strike price) before or at the expiration date.
- **Strike Price Sensitivity Analysis**: Examines how the value of the European call option changes as the strike price is varied.

## Implementation

1. **Environment Setup**: Ensure Python along with `numpy`, `matplotlib`, and `seaborn` libraries are installed for numerical operations and data visualization.
2. **Binomial Tree Parameters**:
   - Initial stock price (S0), strike price (K), time to maturity (T), risk-free interest rate (r), number of steps (N), up-factor (u), and down-factor (d).
3. **Option Pricing Function**: A Python function `binomial_tree` is defined to calculate the European call option price using given parameters.
4. **Visualization**: Using `matplotlib`, the relationship between strike prices and option values is plotted to illustrate sensitivity.

## Usage

To run the project:
- Define the parameters for the Binomial Lattice model.
- Execute the `binomial_tree` function across a range of strike prices.
- Use the plotting functionality to visualize the option price sensitivity to the strike price.

## Conclusion

This project illustrates the application of the Binomial Lattice method to price European call options and analyze the impact of varying strike prices on the option's value. The visualization provides valuable insights into the option pricing behavior, which is crucial for financial analysts and practitioners in the field of derivatives trading and risk management.
