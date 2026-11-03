# Model Assumptions

This document describes the assumptions used in the Honkai: Star Rail probability analysis.

## 1. Character Event Warp

- Base 5-star probability: 0.6%.
- Consolidated 5-star probability: 1.6% (official game information).
- Hard pity: 90 pulls.
- Soft pity begins at pull 74 in this simplified model.

## 2. Soft Pity Approximation

The project uses the following simplified probabilities:

- Pulls 1–73: 0.6%.
- Pulls 74–89: 32.4%.
- Pull 90: 100%.

This is a modelling assumption, not the exact official probability curve.

## 3. Featured Character Guarantee

- A 5-star character has a 50% chance of being featured.
- Losing the 50/50 guarantees the featured character at the next 5-star.
- The guarantee carries over between Character Event Warp banners.

## 4. 4-Star Mechanics

The simulation uses a simplified 4-star guarantee after 10 pulls without a 4-star-or-higher result.

A 5-star result also satisfies this guarantee.

## 5. Simulation

Monte Carlo simulations are used to estimate probabilities by simulating many independent players.

The theoretical and simulated results are compared to evaluate the implementation.

## 6. Limitations

The simplified soft-pity curve and 4-star mechanics do not reproduce every detail of the actual game system. Results are therefore estimates based on the assumptions above.
