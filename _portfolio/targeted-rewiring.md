---
title: "Targeted Network Rewiring Algorithms"
permalink: /portfolio/targeted-rewiring
excerpt: 'Three targeted network rewiring algorithms in Julia I coded'
date: 2025-07-23
paperurl: 'https://github.com/chuecadelc/Targeted_network_rewiring_alg'

---
The repository includes three different network rewiring algorithms I coded that target distinct structural network properties of social networks: assortativity (degree correlations), (local) clustering coefficient and mean geodesic (average path length). The goal was to be able to independently change a single property and observe the effect on the rest of the structural properties. This in turn allowed us to determine which (if any) properties were independent from each other and within what ranges these properties could be manipulated. These algorithms were applied to the degree sequences of seven empirical social networks with different relationship types. Their sizes ranged between 101 to 610 nodes. The average degree was between 3.7 and 43 and edge density ranging from 0.006 and 0.148. 
Using the Configuration Model network generator (reproduced by me from Molloy and Reed (1995) A critical point for random graphs with a given degree sequence. Random Structures & Algorithms 6(2–3):161–80.), ten random network instances for each degree sequence were artificially generated. Then, ten repetitions per network and each rewiring algirthm were run producing 2,100 rewiring experiments.

These algorithms were used in the following publication: Chueca Del Cerro, C. and Badham, J. (2026) The importance of structure: using targeted rewiring to explore social networks property interdependencies, PLOS One,21(3): e0336496 [https://doi.org/10.1371/journal.pone.0336496](https://doi.org/10.1371/journal.pone.0336496) Moreover, the previous version of this work was presented at the International Social Network Analysis Conference (Paris 2024).

This was joint work where I led the design, implementation and debugging of the algorithms in Julia. For more details about author contributions, please read the statement on the paper.

[Access the GitHub repo here](https://github.com/chuecadelc/Targeted_network_rewiring_alg)
