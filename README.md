# Optimising roundtrips based on cost, time and CO2 emission

This Python notebook shows how a roundtrip through several cities can be optimised in terms of cost, travelling time and CO2 emissions. In the literature this problem is called a three-objective travelling salesman problem (TSP). Moreover, this problem is extended by two different modes of travel, i.e. bus and flight. The traveller can choose between a slow but eco-friendly bus ride or a fast but 'eco-unfriendly' fligh to get from A to B.

To solve this multi-objective optimisation problem evolutionary algorithms are the state of the art methods. In this case, the NSGA-II by Deb (2002) is used which is implemented in the Platypus framework. In the end, the cheapest, the fastest, and the greenest routes are plotted on a world map.
