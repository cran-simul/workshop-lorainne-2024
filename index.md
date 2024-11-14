# LoRAINNe'24: workshop on LOw-Rank Approximations and their Interactions with Neural NEtworks

**Location**: IDMC (Institut des Sciences du Digital), Nancy, France.  [How to get there](https://www.openstreetmap.org/directions?engine=fossgis_osrm_foot&route=48.68979%2C6.17514%3B48.69743%2C6.17170#map=16/48.69352/6.17392)

**Date**: 26 and 27 November, 2024.

## About the Workshop
This workshop will explore low-rank matrix and tensor decompositions/approximations and their interactions with neural networks and machine learning at large. The workshop will cover theoretical foundations as well as practical applications, with the main goal to connect researchers working in these fields. This workshop is also a closing event for the ANR LeaFleT project (project ANR-19-CE23-0021).

## Schedule
We will start at 13h-14h on 26 November and should finish on the 27th in the afternoon. Stay tuned for the detailed schedule of talks!

## Registration
Registration is free but mandatory (the capacity is limited), by 11 November at the latest. [Click here to register!](https://forms.gle/cp7v3FCfH1QnJh8F6). 

## Confirmed speakers
- [André de Almeida](https://professors.gtel.ufc.br/andre/) (Federal University of Ceara, Fortaleza)
- [Christophe Cerisara](https://members.loria.fr/CCerisara/) (CNRS-LORIA, Nancy)
- [Jérémy Cohen](https://jeremy-e-cohen.jimdofree.com) (CNRS-CREATIS, Lyon)
- [Julia Gusak](https://juliagusak.github.io) (INRIA Bordeaux)
- Mariya Ishteva (Katholieke Universiteit Leuven)
- [Bernard Mourrain](https://www-sop.inria.fr/members/Bernard.Mourrain/) (INRIA Sophia-Antipolis)
- [Carolin Penke](https://www.fz-juelich.de/profile/penke_c) (Jülich Supercomputing Centre)
- [Mark Sandler](https://www.seresearch.qmul.ac.uk/cmai/people/msandler/) (Queen Mary University of London)
- [Francesco Tudisco](https://ftudisco.gitlab.io/) (University of Edinburgh)
- [Yang Qi](https://sites.google.com/view/yangqi) (INRIA Saclay – Île-de-France)
- [Yassine Zniyed](https://yzniyed.blogspot.com/p/about-me.html) (University of Toulon)


### Tentative schedule:


| **Date**       | **Time**         | **Session**                             |
|----------------|------------------|-----------------------------------------|
| **Tue 26 Nov** |                  | **(Day 1)**                             |
|                | 13:45-14:00      | Registration                            |
|                | 14:00-14:15      | Opening remarks                         |
|                | 14:15-15:15      | André de Almeida                        |
|                | 15:15-15:45      | Mariya Ishteva                          |
|                | 15:45-16:15      | Coffee break                            |
|                | 16:15-17:15      | Francesco Tudisco                       |
|                | 17:15-17:30      | Spotlight posters                       |
|                | 17:30-19:00      | Cocktail + posters                      |
| **Wed 26 Nov** |                  | **(Day 2)**                             |
|                | 09:00-09:30      | Welcome coffee, registration            |
|                | 09:30-10:30      | Bernard Mourrain                        |
|                | 10:30-11:00      | Jeremy Cohen                            |
|                | 11:00-11:30      | Coffee break                            |
|                | 11:30-12:30      | Julia Gusak                             |
|                | 12:30-14:00      | Lunch break                             |
|                | 14:00-15:00      | Christophe Cerisara                     |
|                | 15:00-15:30      | Invited talk                            |
|                | 15:30-16:00      | Invited talk                            |
|                | 16:00-17:00      | Farewell break                          |

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

### Yang Qi
*On the multi-spiked random tensor model*

### Yassine Zniyed
*Network compression using tensor decompositions and pruning*


## Poster session 
The full list of posters will be announced shortly.

### Joppe De Jonghe (KU Leuven, Belgium)
Tensor-based Neural Network Compression with Flexible Activation Functions*

**Abstract:** TBD

### Rima Khouja (Huawei, Paris)
**Abstract:** We introduce an improved tensor-based modulation for unsourced massive random access that support more users. In this modulation scheme, transmitted symbols are modulated as rank one tensors.  One of the sub-constellation is designed as an optimized quasi-orthogonal constellation. This allows to consider an iterative decoding process over the elements of this sub-constellation, by coupling tensor decomposition and projection on the elements of the sub-constellation.

### Fabio Matti (EPFL, Switzerland)
*Randomized trace estimation for parameter-dependent matrices applied to neural network optimization*

**Abstract:** Randomized trace estimators are a family of well established techniques for approximating traces of large matrices which are only accessed through matrix-vector products. These methods have been studied in detail for constant matrices $\boldsymbol{B}$. We analyze three of these methods, the Girard-Hutchinson, Nyström, and Nyström++ estimators, when they are applied to parameter-dependent matrices $\boldsymbol{B}(t)$ which continuously depend on a real parameter $t \in [a, b]$. Instead of applying a separate estimator to each value of the parameter $t_1, t_2, \dots$ in which the trace is approximated, we reuse the same random vectors to construct a single estimator which approximates the trace in all values of the parameter $t$ simultaneously. This makes the methods scale favorably in terms of the number of parameter values at which the estimate is evaluated and allows us to derive error bounds for each of the methods which closely match existing results for constant matrices. Subsequently, we show that these estimators can be used to efficiently approximate the spectral density, i.e. the distribution of the eigenvalues of the Hessian matrix of a neural network, which reflects the geometry of the loss landscape around the iterates from an optimization process.


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
