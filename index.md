---
layout: default
title: Advanced GNN
---

# About

This course is a continuation of [Network Science](https://netspractice.github.io/ml-on-graphs/) course at [BigData Academy MADE](https://data.mail.ru/) by [VK](https://vk.company/). It covers the recent problems in the field of Graph Neural Networks and their applications.

# Team

{% include image-row.html url1="assets/imgs/ilya.jpg" description1="Ilya Makarov" link1="#" url2="assets/imgs/vitalii.jpeg" description2="Vitalii Pozdnyakov" link2="#" url3="assets/imgs/mitya.jpg" description3="Dmitrii Kiselev" link3="#" %}


# Schedule

## Lecture 1. Self-supervised learning and attention-based models on graphs

[Lecture slides](assets/lectures/MADE_GNN_Lecture_1__2021_.pdf) / [Seminar notebook](https://github.com/netspractice/advanced_gnn/blob/main/lab_ssl_on_graphs/lab.ipynb) / [Homework](https://github.com/netspractice/advanced_gnn/blob/main/assignment_contrastive_learning/assignment.ipynb)

Unified framework and mathematical formulation of graph self-supervised learning. Taxonomy of graph self-supervised learning: generation-based methods, auxiliary methods, contrast-based methods. Taxonomy of self-supervised training schemes: pre-training and fine-tuning, joint learning, unsupervised representation learning. Modelling graph-structured data using Transformers.

## Lecture 2. Subgraph-level embeddings and Deep Sets

[Lecture slides](assets/lectures/MADE_GNN_Lecture_2__2021_.pdf) / [Seminar notebook](https://github.com/netspractice/advanced_gnn/blob/main/lab_subgraph_emb/lab.ipynb)

Set pooling approaches. Graph coarsening approaches. Graph neural networks for graph classification. Kernel machines and spectral methods. DeepSets, invariant and equivariant models.

## Lecture 3. Graph neural networks at scale, efficient models and scaling techniques

[Lecture slides](assets/lectures/MADE_GNN_Lecture_3__2021_.pdf) / [Seminar notebook](https://github.com/netspractice/advanced_gnn/blob/main/lab_scalable_gnn/lab.ipynb)

Simple graph convolution. Linearization and logistic regression for interpretation and learning on large datasets. The "neighbor explosion" problem. Graph sampling based on inductive learning methods. Normalization and sampling algorithms for variance reduction.

## Lecture 4. Compression and Knowledge distillation for GNNs

[Lecture slides](assets/lectures/MADE_GNN_Lecture_4__2021_.pdf) / [Seminar notebook](https://github.com/netspractice/advanced_gnn/tree/main/lab_knowledge_distillation/lab.ipynb)

Quantization techniques for GNNs: degree-based, noise-based, graph-level. Knowledge distillation methods. Self-distillation. Binary GNNs. Federated learning and hardware acceleration.

## Lecture 5. Deep Generative Graph Models

[Lecture slides](assets/lectures/MADE_GNN_Lecture_5__2021_.pdf) / [Seminar notebook](https://github.com/netspractice/advanced_gnn/blob/main/lab_deep_generation/lab.ipynb) / [Homework](https://github.com/netspractice/advanced_gnn/blob/main/assignment_recurrent_generation/assignment.ipynb)

Recap on generative techniques. Problems of transferring to the graph domain. Unconditional generation techniques: adjacency matrix generation, edge-list generation, graph-motifs, node or edge sequences generation. Conditional generative methods: conditions on sequences or semantic context, conditions on graphs (modification based, embedding based). Graph generation applications.


## Lecture 6. Interpretable explanations for graph neural networks

[Lecture slides](assets/lectures/MADE_GNN_Lecture_6__2021_.pdf) / [Seminar notebook](https://github.com/netspractice/advanced_gnn/blob/main/lab_explainable_gnn/lab.ipynb)

Explanation methods for GNN classification. Gradient-based methods, perturbations, decomposition, surrogates. Generative models for interpretability.


## Lecture 7. Recommender systems based on graph neural networks

[Lecture slides](assets/lectures/MADE_GNN_Lecture_7__2021_.pdf) / [Seminar notebook](https://github.com/netspractice/advanced_gnn/blob/main/lab_recsys/lab.ipynb) / [Homework](https://github.com/netspractice/advanced_gnn/blob/main/assignment_recsys/assignment.ipynb)

Recap on recommender systems. Approaches to state RecSys problem as an issue on graphs: link prediction over user-item interaction graph, similarity information preserving with item-item graph, knowledge graph lookup and completion. Review of industrial examples: GraphSAGE at Uber Eats, PinnerSAGE at Pinterest.

## Lecture 8. Temporal graph embeddings

[Lecture slides](assets/lectures/MADE_GNN_Lecture_8__2021_.pdf) / [Seminar notebook](https://github.com/netspractice/advanced_gnn/blob/main/lab_temporal_gnn/lab.ipynb)

Taxonomy of dynamic graphs. Types of network evolution. Temporal motifs. Common tasks on dynamic graphs. GNNs for snapshot-based graphs. GNNs for continuous dynamic graphs. Generalizations of given methods.

## Lecture 9. Query embeddings for knowledge graphs

[Lecture slides](assets/lectures/MADE_GNN_Lecture_9__2021_.pdf) / [Seminar notebook](https://github.com/netspractice/advanced_gnn/blob/main/lab_multihop/lab.ipynb) / [Homework](https://github.com/netspractice/advanced_gnn/blob/main/assignment_multihop/assignment.ipynb)

Knowledge Graphs recap: entity, relations, representations. Formulation of knowledge graph query answering problem. Representation of queries with classical logic. Embedding of a query. Embedding of disjunction and negation.


## Lecture 10. Combinatorial optimization using graph neural networks

[Lecture slides](assets/lectures/MADE_GNN_Lecture_10__2021_.pdf) / [Seminar notebook](https://github.com/netspractice/advanced_gnn/blob/main/lab_combinatorial_opt/lab.ipynb)

Review of general optimization frameworks: integer linear programming, satisfiability problem, constrained problems. Finding feasible solutions with GNN. Proving optimality with GNN. Algorithmic reasoning. Limitations and future directions.

## Lecture 11. Applications of graph neural networks

Lecture slides TBA Seminar notebook TBA

Material design. Biology and medicine: molecular design, protein-protein networks, drug-target repurposing, side-effects prediction, medical knowledge graphs problems. Physics: complex system modelling.


# Programming environment

1. Python, iPython Notebooks (e.g. Anaconda distribution)
2. Python libraries: NetworkX, pytorch, pyG and dgl

# Resources

* [CS224W: Machine Learning with Graphs](https://snap.stanford.edu/class/cs224w-2020/). Jure Leskovec. Stanford, 2020-2021.
* [SNAP Project](http://snap.stanford.edu/)
* [PyG](https://pytorch-geometric.readthedocs.io/en/latest/) & [PyG Temporal](https://pytorch-geometric-temporal.readthedocs.io/en/latest/)
* [DGL](https://dgl.ai)
* [Network Science](http://networksciencebook.com), Albert-Laszlo Barabasi, Cambridge University Press, 2016. 
* [Network Science](http://leonidzhukov.net/hse/2021/networks/) course by Leonid E. Zhukov
