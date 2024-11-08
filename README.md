# Option Pricing

Welcome to the **Option Pricing** repository! This project delves into numerical methods for financial mathematics, with a strong emphasis on option pricing. Our primary focus is on implementation and numerical analysis, covering key methods and models such as stochastic differential equations, the Black-Scholes model, and the multilevel Monte Carlo method.

## Contents

This repository includes a collection of Jupyter notebooks that introduce and explore various methods in option pricing:

- **[Brownian Motion and Euler-Maruyama](notebooks/Brownian_motion_and_Euler-Maruyama.ipynb)**  
  Understand the foundations of the Wiener process, geometric Brownian motion, and the Euler-Maruyama method for solving stochastic differential equations.

- **[Strong and Weak Convergence](notebooks/Strong_and_weak_convergence.ipynb)**  
  Validate the strong and weak convergence orders for both the Euler-Maruyama and Milstein methods.

- **[Monte Carlo European Option Pricing](notebooks/Monte_Carlo_European_Option.ipynb)**  
  Apply Monte Carlo methods to price European options and explore the primary sources of error in the process.

- **[Multilevel Monte Carlo Method](notebooks/Multilevel_Monte_Carlo.ipynb)**  
  An in-depth look at the Multilevel Monte Carlo method, replicating results from [Michael B. Giles' paper](https://ora.ox.ac.uk/objects/uuid:d9d28973-94aa-4179-962a-28bcfa8d8f00/download_file?safe_filename=2007OMI06.pdf&file_format=application%2Fpdf&type_of_work=Working+paper) on path simulation.

- **[European Basket Call Option with MLMC](notebooks/European_Basket_Option.ipynb)**  
  Price a European basket call option using the Multilevel Monte Carlo method, leveraging historical data from major tech companies.

- **[European Capped Symmetric Power Call](notebooks/European_Capped_Symmetric_Power_Call.ipynb)**  
  Explore pricing techniques for a European capped symmetric power call, utilizing appropriate discretization and finite difference methods.

---

These notebooks are designed to be practical and accessible, providing insights into both theoretical concepts and their real-world applications. Whether you're a student, researcher, or finance professional, this repository will serve as a valuable resource in your study of option pricing.
