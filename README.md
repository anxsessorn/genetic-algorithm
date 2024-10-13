Genetic algorithm for an optimization task where I am comparing different parameters across three functions (Easom, Ackley, and Three-Hump Camel), including:

Crossover: One-point (OT), two-point (DT)
Mutation rates: 0.001 (M1), 0.05 (M2), 0.01 (M3)
Parent selection: Inbreeding (ID), Outbreeding (AD), Panmixia (PM), Selective breeding (SE)
Population formation: Normal selection (ZV), Displacement selection (VV), Elite selection (EV)
Stopping criteria: Fixed iterations (KI), Distance between individuals (VCH), Distance between average fitness values (VF)

The idea is to:
1. Compare performance with different combinations of these parameters (using tables).
2. Plot graphs showing the minimum function value vs. population number, testing mutation rates, crossover types, parent selection, and population formation.
