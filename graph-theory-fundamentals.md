# Graph Theory Fundamentals

## Graph
Notation: G = (V, E)

Where G is the graph, V represents the set of vertices and E represents the set of edges.

## Simple Graph
A simple graph has no loops or multiple edges.

![](assets/simple.png){width=250px}
![](assets/not-simple.png){width=250px}

## Neighborhood
A set of all vertices adjacent to a vertex.

Using the simple graph above:

N(b) = {a, d, c}

N(a) = {b}

\newpage

## Degree
Cardinality (count) of a neighborhood.

Using the simple graph shown earlier:

deg(b) = |N(b)| = 3

deg(a) = 1

## Handshaking Theorem
The sum of the degrees of a graph is equal to twice the the number of edges.

Using the simple graph shown earlier:

$$
2 |E| = \sum_{v \in V} deg(v)
$$
$$
2 \times 3 = deg(a) +  deg(b) + deg(c) + deg(d)
$$
$$
2 \times 3 = 1 + 3 + 1 + 1
$$

\newpage

## Complete Graph
Contains exactly one edge between every pair of different vertices.

Notation: $K_n$ where n is the number of vertices.

![](assets/k1.png){width=250px}
![](assets/k2.png){width=250px}
![](assets/k3.png){width=250px}
![](assets/k4.png){width=250px}
