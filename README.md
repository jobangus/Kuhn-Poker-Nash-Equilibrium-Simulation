# Kuhn-Poker-Nash-Equilibrium-Simulation
Genetically evolve each players strategies to converge to nash equilbrium.

# Final Project on a class about Computational Modelling and Simulation.
I am deeply interested in turn-based games where players can employ varying optimal strategy. I decided to investigate whether players could learn optimal strategies using genetic algorithms in a simplified poker game (Kuhn Poker). My report shows my findings. tldr; it does not necessarily converge to the theoretical equilibrium, but the mean value does. The reason for the lack of convergence is due to the coevolutionary property: player 1 would adapt to player 2's strategy and vice versa, creating a cycle of varying probability distributions in their strategy set. Nevertheless, I learned a lot on genetic algorithms and identified the Red Queen Effect in my simulation. In the future, I would like to explore simulating strategies in other turn-based games like Pokemon. 
