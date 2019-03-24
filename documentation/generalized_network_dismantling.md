[![](https://raw.githubusercontent.com/wdbm/InfoPeace/master/media/InfoPeace_home.png)](https://github.com/wdbm/InfoPeace/blob/master/README.md)

# Generalized network dismantling

[*Generalized Network Dismantling*](https://arxiv.org/abs/1801.01357) suggests ideas that disrupt information networks. While the current generations of [adversarial examples](https://arxiv.org/abs/1607.02533) in the context of machine learning might not be applicable to individual humans, might they be applicable to networks of humans? How would generalized network dismantling techniques in social media be implemented, observed or even combated?

There are many tools available in this context ranging from ethical to unethical. One class of tool is counter-disinformation. Another class of tool is deplatforming/vertex attenuation.

## Scale-free networks

The degree of a vertex in a graph or network is the number of connections it has to other vertices, and the degree distribution is the probability distribution of these degrees over the whole network. A scale-free network is a network that has a degree distribution that follows a power law, at least asymptotically. Examples of scale-free networks might be the scientific paper citation network, or the [webgraph](https://en.wikipedia.org/wiki/Webgraph) of the World Wide Web, or social networks.

Scale-free networks are more robust to random attacks than random network structures but are *more vulnerable* to targeted attacks. Finding the set of influential vertices (the minimal set of vertices the removal of which results in the network fragmented into subnetworks of subcritical size) is called the network dismantling problem. It is an NP-hard problem. The paper [*Generalized Network Dismantling*](https://arxiv.org/abs/1801.01357) attempts to address the question of how to select the set of vertices which, when removed/deactivated/attenuated can stop the spread of (dis)information. The paper posits the idea of the cost of removing a vertex, a non-negative real number, which might be defined by a function of vertex centrality characteristics, such as degree, page-rank, betweenness or other characteristics not suitable for description in a simple graph object.

## Activation maximization, and the psychology of thinking networks

Could [activation maximization](https://arxiv.org/abs/1605.09304) provide hints at what social network patterns correspond to resonating with the limbic systems of the vertices of [self-isolating groups](https://www.media.mit.edu/videos/sm-electome-2017-01-31)?

Are there analogies to psychiatric disorders for information networks implemented with humans as vertices, or other thinking networks that are homomorphic? In a social graph, might there be observable a kind of schizophrenia that might indicate that the network is modelling noise or disinformation, or perhaps a kind of autism that might indicate more accurate modelling of information? [1]

- [1] [*When the world becomes 'too real': a Bayesian explanation of autistic perception*](https://doi.org/10.1016/j.tics.2012.08.009) -- Elizabeth Pellicano, David Burr (2012)
