Electrical grids require a balance between electricity supply and demand in order to be stable. Conventional systems achieve this balance through demand-driven electricity production. For future grids with a high share of inflexible (i.e. renewable) energy sources, the concept of demand response is a promising solution. This implies changes in electricity consumption in relation to electricity price changes. 
In this project, I would be working on building a binary classification model to predict if a grid is stable or unstable.

## What's in this dataset❔
This dataset consists of 12 predictive features and 2 dependent variables
#### The 12 predictive features:
- tau 1: Reaction time of each network participant in the Supplier node; a real value within the range 0.5 to 10
- tau 2: Reaction time of each network participant in the Consumer node; a real value within the range 0.5 to 10
- tau 3: Reaction time of each network participant in the Consumer node; a real value within the range 0.5 to 10
- tau 4: Reaction time of each network participant in the Consumer node; a real value within the range 0.5 to 10
- p1: Nominal power produced (positive) or consumed (negative) by each network participant in the Supplier node; a real value within the range -2.0 to -0.5
- p2: Nominal power produced (positive) or consumed (negative) by each network participant in the Consumer node; a real value within the range -2.0 to -0.5
- p3: Nominal power produced (positive) or consumed (negative) by each network participant in the Consumer node; a real value within the range -2.0 to -0.5
- p4: Nominal power produced (positive) or consumed (negative) by each network participant in the Consumer node; a real value within the range -2.0 to -0.5
- g1: Price elasticity coefficient for each network participant in the Supplier node; a real value within the range 0.05 to 1.00
- g2: Price elasticity coefficient for each network participant in the Consumer node; a real value within the range 0.05 to 1.00
- g3: Price elasticity coefficient for each network participant in the Consumer node; a real value within the range 0.05 to 1.00
- g4: Price elasticity coefficient for each network participant in the Consumer node; a real value within the range 0.05 to 1.00
#### The 2 dependent variables:
- stab: the maximum real part of the characteristic differential equation root (if positive, the system is linearly unstable; if negative, linearly stable)
- stabf: a categorical (binary) label ('stable' or 'unstable')

## Tools
- Pandas🐼
- Scikit-learn
