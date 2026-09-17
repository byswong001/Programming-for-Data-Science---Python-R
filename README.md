# Statistical Computing: MCMC & Flight Analytics

## Overview

This project applies **statistical computing and programming techniques using Python and R** across two analytical problems.

The first component focuses on **Markov Chain Monte Carlo (MCMC) simulation**, while the second analyses US commercial flight data to investigate flight delays and diversions.

## Part 1 — Markov Chain Monte Carlo

### Objectives

* Simulate random samples from probability distributions.
* Implement the Metropolis-Hastings algorithm.
* Apply the Random Walk Metropolis algorithm.
* Assess the convergence of the generated Markov chains.

### Methodology

The Metropolis-Hastings algorithm was implemented using a **Random Walk Metropolis** approach to generate samples from a target probability distribution.

The generated chains were evaluated using the **R-hat convergence diagnostic** to assess whether the simulation had sufficiently converged.

## Part 2 — US Flight Analytics

The second component uses commercial flight data containing flight arrival and departure information from **1987 to 2008**.

### Objectives

* Identify the best days and times to minimise flight delays.
* Investigate changes in flight delays over time.
* Examine whether older aircraft experience greater delays.
* Model the probability of flight diversions.

### Methodology

Exploratory and statistical analysis was conducted across variables including:

* Year
* Month
* Day of week
* Scheduled departure time
* Scheduled arrival time
* Actual departure and arrival times
* Aircraft characteristics
* Flight delays
* Flight diversions

A **logistic regression model** was developed using available flight attributes to estimate the probability of a flight being diverted.

## Key Skills Demonstrated

* Statistical programming
* Monte Carlo simulation
* Markov Chain Monte Carlo
* Metropolis-Hastings
* Random Walk Metropolis
* Convergence diagnostics
* Exploratory data analysis
* Logistic regression
* Feature selection
* Data visualisation

## Tools & Technologies

* Python
* R
* Statistical Modelling
* Data Analysis
* Data Visualisation
