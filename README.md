<h3>Data Visualization Network Assignment<h3>

<h1>Data Relation:<h1>
A network consists of numerous one-to-one and/or one-to-many relations within the same data set. The graph consists of vertices (or nodes), and connections between vertices, called edges. The edges can be directed (indicating the edge only goes one way) or un-directed. Sometimes edges are marked with weights, to indicate their strength. Think of this as a road connecting two cities, the weight could be the number of lanes on the road. This is a very complex data type due to the potential for one-to-many relations.

<h1>English Language Description:<h1>
Networks are sets of relations between nodes. A node might be a person, and edge would denote a friendship. Or an node could be a product, and an edge indicate that two products are purchased simultaneously, like beer and sausages. Perhaps more accessibly, networks include towns (vertices) and roads between them (edges), or airports (nodes) and flights between them (edges). Evaluation of these relations for predictive purposes is an open research problem and useful for a addressing questions ranging from marketing to radicalization of terrorists.

<h1>Example Data Sources:<h1>
Sometimes smaller is easier in this assignment, try this site. Beware the last link - those are some monstrous, but fascinating data sets.

<h1>Example Hypotheses:<h1>
Networks often have a highly connected node that, if removed, would result in several disjoint networks. 
There are many more nodes of low connectivity that of high connectivity. 
More highly connected networks tend to be older.
The capacity or weight of edges increases with the size of nodes.
Hub cities in transportation networks tend to centrally located.
The top ten products sell more units that all the rest combined.

<h1>Implementation Tips:<h1>
As has been the case with other assignments, you are strongly encouraged to leverage what you've done in the past to reveal the data used here. Consider a network that exists on a map. Produce a histogram of the number of count of vertices vs. edges per vertex. Plot the network both abstractly using Vega or D3, as well as on a map. Note there is a software package called "Gephi" that does some interesting network analysis, and isn't especially hard to use. Consider applying it to some reductions or analysis of networks before working on you assignment.
