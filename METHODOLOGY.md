# Project Methodology

## 1. Research Approach

This project combines theoretical probability calculations and Monte Carlo simulations to analyse the Character Event Warp system in Honkai: Star Rail.

## 2. Theoretical Analysis

The probability of receiving at least one 5-star character over multiple pulls is calculated using:

P(at least one 5-star) = 1 - P(no 5-star)

For different pull probabilities, this becomes:

P(X >= 1) = 1 - ∏(1 - pᵢ)

where pᵢ represents the probability of receiving a 5-star on pull i.

## 3. Monte Carlo Simulation

The simulation models many independent players. Each simulated pull checks:

- The current 5-star pity count.
- The probability of receiving a 5-star.
- The featured character 50/50.
- The featured character guarantee.
- The 4-star-or-higher guarantee.

## 4. Scenario Comparison

Three saving scenarios are compared:

- Free-to-play (F2P).
- Monthly Pass.
- Monthly Pass + Battle Pass.

The number of available pulls is used to calculate and simulate the probability of obtaining at least one 5-star character.

## 5. Validation

The theoretical probabilities are compared with the Monte Carlo results. Small differences are expected because simulation results are random.

## 6. Interpretation

The results demonstrate how pity mechanics and guarantees influence the probability of obtaining rare characters. The conclusions remain subject to the modelling limitations documented in `MODEL_ASSUMPTIONS.md`.
