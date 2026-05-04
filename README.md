**Manifold-Driven-Plasticity**
Replication and extension of Feulner et al. 2020, exploring how RNN connectivity structure shapes neural manifolds and motor learning dynamics Replication of Feulner et al. 2020.
### **Theoretical Foundation**
This project builds on the concept of "Within-Manifold" vs. "Outside-Manifold" learning established by **Sadtler et al. (2014)**.

**Key Investigation Areas:**

Q1-Q2: Training dynamics, loss curves, and the impact of connection density on performance.

Q3-Q4: Connectivity sparsity and the role of network graph properties.

Q5-Q6: Influence of task complexity on manifolds and decoder-only learning dynamics.

Q7-Q9: Advanced extensions into manifold realignment and co-evolutionary representations.

**Project Overview** This project investigates how Recurrent Neural Networks (RNNs) develop internal representations to solve complex motor tasks. By characterizing the population geometry of neural manifolds, we aim to understand the co-evolution of neural structure and functional output. This work is a foundational step toward the NeuroRecovery framework, designed to optimize Brain-Computer Interfaces (BCIs) for clinical motor rehabilitation. Key Research Aims

**Manifold Characterization:** Systematically quantifying the intrinsic dimensionality and curvature of neural representations during learning.
Task Complexity: Analyzing how increasing the number of motor targets influences the linear separability of neural states.
Decoder Plasticity: Comparing fixed vs. adaptive feedforward decoders to evaluate recovery efficiency in post-injury simulations.
Technical Implementation

**Model:** Recurrent Neural Networks (RNNs) trained on multi-target reaching tasks.
Dimensionality Reduction: Utilizing Isomap, PCA, and UMAP to visualize manifold structure.
Representational Analysis: Implementing Representational Dissimilarity Matrices (RDMs) to quantify state-space organization.
Visualizations The repository includes scripts to generate:

**Target-Specific Manifolds:** 3D Isomap projections showing neural separability.
Learning Dynamics: MSE curves comparing plastic vs. fixed decoder architectures.
Curvature Evolution: Tracking the "smoothing" of manifolds over training epochs.
Clinical Application: NeuroRecovery Grounding motor rehabilitation in neural manifold geometry allows for the development of adaptive neuroprosthetics that "realign" with the user's changing neural signatures post-stroke or injury.
