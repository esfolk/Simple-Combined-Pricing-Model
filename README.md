# Simple-Combined-Pricing-Model

Binomial Tree Trigeorgis Model for American Options
This repository contains an implementation of the Binomial Tree Trigeorgis model for pricing American options. The primary focus was on refactoring and improving the original code to achieve accurate option pricing and to calculate the Greeks.

## Overview:
The project began with a review of an initial implementation of the Binomial Tree Trigeorgis model. During the review, several key features of Object-Oriented Programming (OOP) were identified, including classes, methods, and inheritance.

## Key Enhancements:
Refactored Code:

Adopted an OOP approach to structure the code, making it modular and more maintainable.
Introduced abstract base class Option and derived classes EuropeanOption and AmericanOption to handle specific option types.
Enumerations (OptionType, OptionModel, OptionExerciseType) were introduced for better code clarity and to prevent magic strings.
Implemented Pricing Models:

Black Scholes: Used for European options.
Binomial Tree Trigeorgis: Used for American options.
Monte Carlo: Used for both European and American options.
Greeks Calculation:

Added functionality to compute the Greeks (Delta, Gamma, Theta, Vega, Rho) for the option, providing insights into the option's sensitivity to various factors.

## Example Computations:

The code includes example computations for both call and put options, demonstrating the accurate pricing and Greeks computation for the options using the aforementioned models.

## Future Work:
- Extend the code to handle more exotic types of options.
- Implement more sophisticated models for option pricing.
- Optimize the code for performance, especially for larger binomial trees and Monte Carlo simulations.
