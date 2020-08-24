# Optimising roundtrips based on cost, time and CO2 emission

## Motivation
Imagine you want to do a Eurotrip (like in the infamous [US movie from 2004](https://www.imdb.com/title/tt0356150/)). You are starting from Amsterdam and on your list are: Berlin, Brussels, Copenhagen, Lisbon, London, Madrid, Paris, Prague, Rome, Vienna, Warsaw. In the end you have to come back to Amsterdam. To plan your roundtrip you want to find the route which minimises cost, travelling time and CO2 emissions.

The aim of this project is to stimulate consumers torwards greener travel options. Instead of flying everywhere consider taking the train or bus.

## Methodology
In the literature this problem is called a three-objective travelling salesman problem (TSP). Moreover, this problem is extended by two different modes of travel, i.e. bus and flight. You can choose between a slow but eco-friendly bus ride or a fast but 'eco-unfriendly' fligh to get from A to B.

To solve this multi-objective optimisation problem evolutionary algorithms are the state of the art methods. In this case, the NSGA-II by Deb (2002) is used which is implemented in the Platypus framework. In the end, the cheapest, the fastest, and the greenest routes are plotted on a world map.

- [To the Code](https://github.com/grafkevin/multiobjective_route_optimisation/blob/master/%23%23%23%20Three-objective%20TSP%20with%2012%20cities%20solved%20with%20NSGA-II.ipynb)

![Alt text](3obj_map_green2.png?raw=true "Title")
