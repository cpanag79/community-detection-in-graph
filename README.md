# Community detection in graph

Community Detection in Graph Using Synthetic Coordinates

Matlab Code: https://www.mathworks.com/matlabcentral/fileexchange/46360-community-detection-in-graph

This is an implementation of Community Detection Using Synthetic Coordinates
and the synthetic datasets used in [1].

More details can be found in www.csd.uoc.gr/~cpanag
and in https://sites.google.com/site/netdilab/

You can use them only for non-commercial purposes.
If you use them, please cite [1]. The code of .java files
is written by H. Papadakis.

You can download the synthetic datasets used in [1] from
https://pithos.okeanos.grnet.gr/public/SVGXVpIoHy4NN1wIUM1966
or https://sites.google.com/site/netdilab
or https://sites.google.com/site/costaspanagiotakis

The .jar file can be downloaded from https://dl.dropboxusercontent.com/u/11081708/sccd.rar
or can be created by compliling the .java files.

[1]. H. Papadakis, C. Panagiotakis and P. Fragopoulou,
Distributed Community Detection in a Complex World Using Synthetic Coordinates, Journal of
Statistical Mechanics, 2014

runSSCD.m: function that calls the SCCD.jar.
testSCCD.m: script that tests runSSCD
USAGE: [COMM,L] = runSSCD('pareto-graph_1000_5_30_0.75.txt')
where pareto-graph_1000_5_30_0.75.txt is the graph file that represents the graph edges.
See comments on .m files for more details.

output file: coms.txt: Each line holds the ids of all nodes of a community separated by space

In this work, we propose an algorithm that ﬁnds the
entire community structure of a network, based on local interactions between
neighboring nodes and on an unsupervised distributed hierarchical clustering
algorithm. The novelty of the proposed approach, named SCCD (to stand for
Synthetic Coordinate Community Detection), is the fact that the algorithm is based on the use of Vivaldi synthetic network coordinates computed by a distributed algorithm.
