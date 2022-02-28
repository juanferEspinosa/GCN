# GCN
Practical experimentation of Graph Convolutional Neural Networks based on the study "Semi-Supervised Classification with Graph Convolutional Networks" by Kipf, et al ([1](https://arxiv.org/abs/1609.02907))

GCNs perform convolutions by making use of both the signal and the graph structure by taking into account the adjacency matrix. It also normalize the latter by using the so called "Re-normalization trick". The formula is: A = D^(-1/2)AD^(-1/2) with A also considering its self loops.

- GCN-sequential is based on the work of [Jackie Loong](https://github.com/dragen1860).
- K-GCN performs an augmentation of the GCN process to a degree K.




