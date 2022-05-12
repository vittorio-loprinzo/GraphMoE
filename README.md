# GraphMoE
Generative model for random graph distributions.

Paper available at:
https://arxiv.org/abs/2204.07634

GraphMoE is designed to learn a random graph distribution from a sample of graphs from that distribution. Afterwards, it can be used to generate synthetic data.

The main file, graph_learner_release, contains a class of neural networks, built with Pytorch, designed to do all of the heavy lifting in the problem. 
There are also some data files required to do the learning, as well as several publically available datasets.
Sources for the datasets can be found in the paper above.
