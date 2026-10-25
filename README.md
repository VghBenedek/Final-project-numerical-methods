# Final-project-numerical-methods

VII. Dynamics on Networks: Kuramoto Synchronization and SIR Epidemics

Developers: Benedek Végh(VghBenedek), Zilly Huma Rao(Huma755)

In this project we study how things change over time on a network. A network is a set of nodes connected by links, for example people in a social network.

We look at two classic processes:

- Kuramoto model: every node is an oscillator with its own frequency. The links pull the oscillators toward each other, and if the coupling is strong enough they start to move in sync. We measure this with the order parameter r(t).
- SIR epidemic model: every node is susceptible, infected or recovered. The infection spreads along the links and infected nodes recover after some time.

Both are systems of differential equations, so we solve them numerically.