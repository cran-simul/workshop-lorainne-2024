# LoRAINNe'24: workshop on LOw-Rank Approximations and their Interactions with Neural NEtworks

**Location**: IDMC (Institut des Sciences du Digital), Nancy, France.  [How to get there](https://www.openstreetmap.org/directions?engine=fossgis_osrm_foot&route=48.68979%2C6.17514%3B48.69743%2C6.17170#map=16/48.69352/6.17392)

**Date**: 26 and 27 November, 2024.

## About the Workshop
This workshop will explore low-rank matrix and tensor decompositions/approximations and their interactions with neural networks and machine learning at large. The workshop will cover theoretical foundations as well as practical applications, with the main goal to connect researchers working in these fields. This workshop is also a closing event for the ANR LeaFleT project (project ANR-19-CE23-0021).

## Schedule
We will start at 13h-14h on 26 November and should finish on the 27th in the afternoon. Stay tuned for the detailed schedule of talks!

## Registration
Registration is free but mandatory (the capacity is limited), by 21 November at the latest. [Click here to register!](https://forms.gle/cp7v3FCfH1QnJh8F6). 

## Confirmed speakers
- [André de Almeida](https://professors.gtel.ufc.br/andre/) (Federal University of Ceara, Fortaleza)
- [Christophe Cerisara](https://members.loria.fr/CCerisara/) (CNRS-LORIA, Nancy)
- [Jérémy Cohen](https://jeremy-e-cohen.jimdofree.com) (CNRS-CREATIS, Lyon)
- [Julia Gusak](https://juliagusak.github.io) (INRIA Bordeaux)
- [Mariya Ishteva](https://www.kuleuven.be/wieiswie/en/person/00050783) (Katholieke Universiteit Leuven)
- [Bernard Mourrain](https://www-sop.inria.fr/members/Bernard.Mourrain/) (INRIA Sophia-Antipolis)
- [Carolin Penke](https://www.fz-juelich.de/profile/penke_c) (Jülich Supercomputing Centre)
- [Mark Sandler](https://www.seresearch.qmul.ac.uk/cmai/people/msandler/) (Queen Mary University of London)
- [Romain Serizel](https://members.loria.fr/RSerizel/) (LORIA, Nancy)
- [Francesco Tudisco](https://ftudisco.gitlab.io/) (University of Edinburgh)
- [Yang Qi](https://sites.google.com/view/yangqi) (INRIA Saclay – Île-de-France)
- [Yassine Zniyed](https://yzniyed.blogspot.com/p/about-me.html) (University of Toulon)


### Tentative schedule:


| **Date**       | **Time**         | **Session**                             |
|----------------|------------------|-----------------------------------------|
| **Tue 26 Nov** |                  | **(Day 1)**                             |
|                | 13:15-13:45      | Registration                            |
|                | 13:45-14:00      | Opening remarks                         |
|                | 14:00-15:00      | [André de Almeida](#andré-de-almeida)   |
|                | 15:00-15:30      | Mariya Ishteva                          |
|                | 15:30-16:00      | Coffee break                            |
|                | 16:00-17:00      | Francesco Tudisco                       |
|                | 17:00-17:30      | Yang Qi                                 |
|                | 17:30-19:00      | Cocktail + poster session               |
| **Wed 27 Nov** |                  | **(Day 2)**                             |
|                | 09:00-10:00      | Bernard Mourrain                        |
|                | 10:00-10:30      | Jérémy Cohen                            |
|                | 10:30-11:00      | Coffee break                            |
|                | 11:00-12:00      | Julia Gusak                             |
|                | 12:00-12:30      | Yassine Zniyed                          |
|                | 12:30-14:00      | Lunch break                             |
|                | 14:00-14:45      | Christophe Cerisara                     |
|                | 14:45-15:15      | Carolin Penke                           |
|                | 15:15-15:45      | Coffee break                            |
|                | 15:45-16:15      | Mark Sandler                            |
|                | 16:15-16:45      | Romain Serizel                          |
|                | 16:45-17:00      | Farewell                                |

## Oral presentations

### André de Almeida
*Overview of tensor decompositions and some applications to wireless communications*

### Christophe Cerisara
*Study of a few properties of LLM pruning*

### Jérémy Cohen
*Implicit Regularization in Regularized (Nonnegative) Low-Rank Approximations* 

**Abstract:**
Regularized nonnegative low-rank approximations such as sparse Nonnegative Matrix Factorization or Sparse Nonnegative Tucker Decomposition are an important branch of dimensionality reduction models with enhanced interpretability. However, from a practical perspective, the choice of regularizers and regularization coefficients is often challenging because of the multifactor nature of these models and the lack of theory to back these choices. The work presented aims at improving upon these issues. By studying a more general model called the Homogeneous Regularized Scale-Invariant, we prove that the scale- invariance inherent to low-rank approximation models causes an implicit regularization with unexpected effects. This observation enables to better understand the effect of regularization functions in low-rank approximation models, to guide the choice of the regularization hyperparameters, and to design balancing strategies to enhance the convergence speed of dedicated optimization algorithms. We showcase our contributions on sparse Nonnegative Matrix Factorization, ridge-regularized Canonical Polyadic decomposition and sparse Nonnegative Tucker Decomposition.

### Mariya Ishteva
*Decoupling multivariate functions using tensors*


### Bernard Mourrain
*Low rank approximation of moment matrices and tensors*

### Carolin Penke
*Efficient Computation of Low-Rank Representations to Reduce Memory Requirements in LLM Training*

**Abstract:**
The OpenGPT-X project represents one of Europe's pioneering publicly funded efforts in the domain of large language models (LLMs), covering the entire lifecycle from pre-training foundational models to fine-tuning and practical application development.  To maximize the efficiency of training on High Performance Computing (HPC) resources, strategies aimed at reducing computational and memory demands are being explored. A promising avenue exploits the low-rank structure of gradients, as done in the LoRA or GaLore frameworks, the latter of which relies on the computation of dominant low-rank subspaces during training. The randomized range finder algorithm provides a more efficient alternative to computing a full singular value decomposition (SVD). We introduce a novel variant of the range finder, based on the blocked Householder QR decomposition, optimized for modern GPU accelerators.



### Mark Sandler
*Artificial Neuroscience: metrology and engineering for Deep Learning using Linear Algebra*

**Abstract:**
Our new, UK-funded project (which shares a title with this presentation) sets out to establish a new, holistic approach to the understanding and engineering of Artificial Neural Networks. Called Artificial Neuroscience it draws inspiration from natural neuroscience, borrowing and re-imagining its established scientific method and practice, mixing that with mathematics, signal processing and eventually, systems engineering, to Engineer Better AI. 
 
The motivation for this shift in viewpoint comes from an observation that the metric-driven approach to AI research and discovery, which relies strongly on the availability of data, GPUs and electricity is leading to potentially unsafe, inefficient and uninterpretable AI: this belief is widely shared though by no means ubiquitous. We believe that a new way of working, built upon formalisms from an appropriate set of disciplines, will change how AI is done.
 
The presentation will explore further the parallels between AI and neuroscience and will use existing literature to show how several aspects of this viewpoint on the research landscape are already being explored in several labs. It will include a glimpse of our own latest results (submitted to ICLR 2025) that explores how training in low-rank domains can improve learning and reduce the demand for data.

### Romain Serizel
*Monitoring Environmental Impact of AI Systems: why and how?*

**Abstract:**
With the increasingly complex models used in machine learning and the large amount of data needed to train these models, machine learning based solutions can have a large environmental impact. Even if a few hundred experiments are sometimes needed to train a working model, the cost of the training phase represents only 10% to 20% of the total CO2 emissions of the related machine learning usage (the rest lying in the inference phase). Yet, as machine learning researchers the largest part of our energy consumption lays in the training phase. Comparing the energy consumption of system trained on different site can be a complex task and the relation between the system performance and its energy footprint can be uneasy to interpret. In this presentation we will study the energy consumption measurement under various configurations to assess the aspects that can potentially affect the measure of the energy consumption.

### Francesco Tudisco
*Exploiting Low-Rank Geometry in Deep Learning*

**Abstract:** As models and datasets grow, modern AI faces significant challenges related to timing, costs, energy consumption, and accessibility. To address these, there has been a surge of interest in network compression and parameter-efficient fine-tuning (PEFT) techniques to reduce computational overhead while maintaining model performance. In terms of compression, the majority of the existing methods focus on post-training pruning to reduce inference costs. However, an important subset tackles the reduction of training overhead, with layer factorization emerging as a key approach both for training and fine-tuning. In fact, recent empirical and theoretical findings indicate that deep networks exhibit an implicit low-rank bias, suggesting the existence of highly effective low-rank subnetworks. In this talk, I will present our recent work on analyzing and leveraging this low-rank bias for efficient model compression and fine-tuning. By exploiting the Riemannian geometry of low-rank spaces, we propose a geometry-aware variant of stochastic gradient descent that trains small, factorized layers while dynamically adjusting their rank. We provide theoretical guarantees on convergence and approximation, alongside experimental results demonstrating competitive performance across various state-of-the-art network architectures both in terms of pre-training and fine-tuning. 

Based on:
Geometry-aware training of factorized layers in tensor Tucker format
Emanuele Zangrando, Steffen Schotthöfer, Jonas Kusch, Gianluca Ceruti, Francesco Tudisco
Advances in Neural Information Processing Systems (NeurIPS), 2024
 
Robust low-rank training via approximate orthonormal constraints
Dayana Savostianova, Emanuele Zangrando, Gianluca Ceruti, Francesco Tudisco
Advances in Neural Information Processing Systems (NeurIPS), 2023
 
Low-rank lottery tickets: finding efficient low-rank neural networks via matrix differential equations
Steffen Schotthöfer, Emanuele Zangrando, Jonas Kusch, Gianluca Ceruti, Francesco Tudisco
Advances in Neural Information Processing Systems (NeurIPS), 2022
 


### Yang Qi
*The statistical limits of multi-spiked random tensor models*

**Abstract:** Numerous problems in signal processing, machine learning, and data analysis are based on the low-rank tensor model, a.k.a. the multi-spiked tensor model, where we would like to recover the hidden low-rank structure from a noisy observed tensor data. Though several algorithms have been proposed for low-rank approximations, little is known about the corresponding performance analyses and statistical limits. In this talk, we will focus on the statistical performance of the local methods designed for low-rank approximations. More precisely, thanks to the nature of local optimization methods used to find the maximum likelihood estimator of the multi-spiked Gaussian tensor model, we propose to study the phase transition phenomenon for finding critical points of the corresponding optimization problem, i.e., those points defined by the KKT conditions. In particular, we obtain a threshold above which the detection of critical points is possible. Moreover, we characterize the limiting alignments between the maximum-likelihood estimators and the ground truth signals. With the help of these results, we achieve a new estimator by modifying the classical maximum likelihood estimator.

### Yassine Zniyed
*Network compression using tensor decompositions and pruning*


## Poster session 
The full list of posters will be announced shortly.

### Joppe De Jonghe (KU Leuven, Belgium)
*Multilayer Tensor-based Neural Network Compression with Flexible Activation Functions*

**Abstract:** The nonlinear activation functions used in deep neural networks are typically fixed simple functions, leading to a large number of neurons and hidden layers. To reduce the number of parameters, pruning or compression techniques are often considered. Alternatively, flexible activation functions can be considered but learning them during the training process is not straightforward.
In this paper, we develop a compression methodology that decomposes a given pre-trained model into a decoupled representation that has the structure of a (multiple-layer) neural network with flexible activation functions. 
The multi-layer function structure is linked to a ParaTuck-$L$ tensor decomposition by considering the first-order derivative information.
To reduce the approximation error on the initial function (and not only of its derivatives),
the multi-layer decoupling method ultimately reduces to solving a coupled matrix-tensor factorization problem. 
We propose two alternating least squares-based algorithms for computing the (constrained) decomposition, including tailored strategies for the order of updates, updating the regularization parameter, and
properly handling the bias terms in the case of analytic activation functions.
The proposed methodology is illustrated on both synthetic and neural network examples. 

### Faustine Faccin (CRAN/LORIA/NOVIGA, Nancy)
*ECG-based Deep Convolutional Recurrent Network with Attention Mechanism for Sleep Apnea Detection*

**Abstract:** Sleep apnea syndrome (SAS) is a nocturnal respiratory disorder that can be associated with long-term cardiovascular complications. Alternative screening solutions are currently being developed to overcome the limitations of reference in-lab polysomnography. As the respiratory signal can be reconstructed from the electrocardiogram (ECG), the latter is all the more interesting as its recording is easy and non-invasive for the patient. The application of deep learning algorithms using ECGs has proved effective in classifying sleep-related pathological events.
In this work, we propose a novel hybrid architecture to detect apneic episodes using single-lead ECGs. Following a preprocessing step, morphological and temporal components of interest are extracted through convolutional and recurrent blocks, respectively. Additional mechanisms are further integrated to enhance the classification. Models were trained and validated on a dataset derived from STAGES and Apnea-ECG databases. Influence of patient phenotype on classification was estimated by comparing the performance between several groups of patients with different clinical information.
Overall, a model we have developed performs competitively with the best current methods by accurately classifying patients to different degrees of severity with average sensitivity, specificity and accuracy of 93.38%, 75.46% and 86.66%, respectively.

### Arthur Lebeurrier (ENS Lyon)
*Hierarchical Matrix Approximation for Accelerated Regularized Optimal Transport*

**Abstract:** Optimal Transport (OT) is a mathematical framework for determining the most efficient way to move one distribution of mass to another while minimizing a certain cost. Despite its broad applications, ranging in machine learning, its computational complexity remains a bottleneck for large datasets. The Sinkhorn algorithm, a state-of-the-art method for regularized OT, suffers from a quadratic complexity, $O(n^2)$, due to repeated matrix-vector multiplications.
This work introduces a hierarchical approximation algorithm inspired by the Barnes-Hut method and partitioning trees, such as the k-d tree. Our method decomposes the kernel matrix into low-rank and dense blocks, optimizing the computational cost to $O(n\log n)$ while ensuring controlled approximation errors. The hierarchical approach leverages spatial relationships between data points to approximate interactions efficiently, balancing computational efficiency and accuracy.
We validate our method theoretically and experimentally, showcasing significant computational gains in synthetic benchmarks and classification tasks. These results highlight the potential of our hierarchical approximation framework to extend OT applications to high-dimensional, large-scale datasets while maintaining performance in practical machine learning scenarios.



### Rima Khouja (Huawei, Paris)
*Quasi-Orthogonal Tensor-Based Modulation for Unsourced Massive Random Access*

**Abstract:** We introduce an improved tensor-based modulation for unsourced massive random access that support more users. In this modulation scheme, transmitted symbols are modulated as rank one tensors.  One of the sub-constellation is designed as an optimized quasi-orthogonal constellation. This allows to consider an iterative decoding process over the elements of this sub-constellation, by coupling tensor decomposition and projection on the elements of the sub-constellation.

### Fabio Matti (EPFL, Switzerland)
*Randomized trace estimation for parameter-dependent matrices applied to neural network optimization*

**Abstract:** Randomized trace estimators are a family of well established techniques for approximating traces of large matrices which are only accessed through matrix-vector products. These methods have been studied in detail for constant matrices $\boldsymbol{B}$. We analyze three of these methods, the Girard-Hutchinson, Nyström, and Nyström++ estimators, when they are applied to parameter-dependent matrices $\boldsymbol{B}(t)$ which continuously depend on a real parameter $t \in [a, b]$. Instead of applying a separate estimator to each value of the parameter $t_1, t_2, \dots$ in which the trace is approximated, we reuse the same random vectors to construct a single estimator which approximates the trace in all values of the parameter $t$ simultaneously. This makes the methods scale favorably in terms of the number of parameter values at which the estimate is evaluated and allows us to derive error bounds for each of the methods which closely match existing results for constant matrices. Subsequently, we show that these estimators can be used to efficiently approximate the spectral density, i.e. the distribution of the eigenvalues of the Hessian matrix of a neural network, which reflects the geometry of the loss landscape around the iterates from an optimization process.

### Irina Proskurina (ERIC, Université de Lyon)
*Combating Biased Outcomes of Low-Rank Adaptation of Large Models*

**Abstract:** Low-Rank Adaptation (LoRA) helps avoid full-scale fine-tuning of large language models, paving the way for lower training costs. However, training only a subset of weights can lead to biased outcomes, such as an increased probability of toxic speech generation, particularly in multilingual contexts. Models fine-tuned with LoRA also exhibit lower fairness in classification tasks, especially with respect to subgroup accuracy, compared to full-scale training. 
These issues are exacerbated when fine-tuning models with QLoRA, which involves quantizing the weights in conjunction with LoRA. We question how to mitigate these effects arising from using QLoRA while preserving the weight size reduction achieved through quantization for efficiency. 
Our aim is to develop subgroup-fairness-aware regularization approaches to address the problem of biased outcomes.

### Konstantin Usevich (CRAN-CNRS, Nancy)
*A lifting approach to ParaTuck-2 tensor decompositions*

**Abstract:** The ParaTuck-2 decomposition (PT2D) of third-order tensor is a two-layer generalization of the well-known canonical polyadic decomposition (CPD). While being more flexible than the CPD, the PT2D also possesses similar uniqueness properties.
In this paper, we show than under the best known uniqueness conditions, the exact PT2D can be computed by an algebraic algorithm (i.e., can the PT2D problems can be reduced to computing nullspaces and eigenvalues of certain matrices).
We do so by lifting the slices of the tensor to higher-dimensional space, which also allows for refining the existing uniqueness conditions. The algorithms are developed for general PT2D and its symmetric version (DEDICOM), which leads to an algebraic algorithm for another generalization of the CPD, the PARAFAC2 decomposition. Our methods are also applicable in the approximation scenario, as shown by the numerical experiments.


## Contact Us

Organization committee: 
 - Ricardo Borsoi
 - Marianne Clausel
 - Sebastian Miron
 - Konstantin Usevich
 - group [SiMul @ CRAN](https://cran-simul.github.io/).

You can email the organizers at: [firstname.lastname@univ-lorraine.fr](firstname.lastname@univ-lorraine.fr)

---

&copy; 2024 Workshop LoRaINNe
