---
layout: default
title: Shenzhen--Nagoya Workshop on Quantum Science 2023
---

Shenzhen--Nagoya Workshop on Quantum Science 2023
================

Date and venue
----------------
5--8 Sep. 2023, Hybrid (in-person and Zoom)

509 Mathematics Bldg. Nagoya University [access](https://www.math.nagoya-u.ac.jp/en/direction/nagoya.html)

Registration
----------------
[Link to Microsoft Forms](https://forms.office.com/r/PMMAiL9Z3T)

Organizing committee
----------------
* Masahito Hayashi (Chair, CUHK-SZ, IQA, and Nagoya Univ.)
* An-Si Bai (SUSTech)
* Hiroaki Kanno (Nagoya Univ.)
* Shintarou Yanagida (Nagoya Univ.)
* Ryuhei Mori (Nagoya Univ.)

<ShenzhenNagoya2023@gmail.com>

KouShare/YouTube live streaming
----------------

Talks will be streamed on KouShare and YouTube.

Program
----------------

### 5 Sep.

| CST (UTC+8)    | JST (UTC+9)    | Speaker             | Title |
|---------------:|---------------:|:--------------------|-------|
| 09:25 -- 09:30 | 10:25 -- 10:30 |                     | Opening |
| 09:30 -- 10:10 | 10:30 -- 11:10 | François Le Gall    | |
| 10:20 -- 10:40 | 11:20 -- 11:40 | Ansis Rosmanis      | [Quantum computation and simulation, algorithms and complexity](#rosmanis) |
| 10:50 -- 11:30 | 11:50 -- 12:30 | Benyou Wang         | |
| 13:30 -- 14:10 | 14:30 -- 15:10 | Harumichi Nishimura | [More Distributed Quantum Merlin-Arthur Protocols: Improvement and Extension](#nishimura) |
| 14:20 -- 14:40 | 15:20 -- 15:40 | Qisheng Wang        | [Quantum Lower Bounds by Sample-to-Query Lifting](#qwang) |
| 14:50 -- 15:10 | 15:50 -- 16:10 | Geng Liu            | |
| 15:20 -- 16:00 | 16:20 -- 17:00 | Kohtaro Kato        | [Exact and Local Compression of Quantum Bipartite States](#kato) |

### 6 Sep.

| CST (UTC+8)    | JST (UTC+9)    | Speaker             | Title |
|---------------:|---------------:|:--------------------|-------|
| 09:30 -- 10:10 | 10:30 -- 11:10 | Liang Kong          | [A morphism between two QFTs](#kong) |
| 10:20 -- 10:40 | 11:20 -- 11:40 | Yusuke Nishinaka    | |
| 10:50 -- 11:10 | 11:50 -- 12:10 | Jiaheng Zhao        | [Center functors and condensation theory](#zhao) |
| 13:30 -- 14:10 | 14:30 -- 15:10 | Shinichiroh Matuso  | |
| 14:20 -- 14:40 | 15:20 -- 15:40 | Hao Xu              | |
| 14:50 -- 15:10 | 15:50 -- 16:10 | Ryo Hayami          | [dg symplectic geoemetry and (higher) Poisson vertex algebras](#hayami) |

### 7 Sep.

| CST (UTC+8)    | JST (UTC+9)    | Speaker             | Title |
|---------------:|---------------:|:--------------------|-------|
| 09:30 -- 10:10 | 10:30 -- 11:10 | Francesco Buscemi   | [Measurement sharpness and incompatibility as quantum resources](#buscemi) |
| 10:20 -- 10:40 | 11:20 -- 11:40 | Shintaro Minagawa   | |
| 10:50 -- 11:30 | 11:50 -- 12:30 | Masahito Hayashi    | [Tight Cramér-Rao type bounds for multiparameter quantum metrology through conic programming](#hayashi) |
| 13:30 -- 14:10 | 14:30 -- 15:10 | Haidong Yuan        | |
| 14:20 -- 14:40 | 15:20 -- 15:40 | Hayato Arai         | [Derivation of Standard Quantum Theory via State Discrimination](#arai) |
| 14:50 -- 15:10 | 15:50 -- 16:10 | Baichu Yu           | |
| 15:20 -- 16:00 | 16:20 -- 17:00 | Ryuhei Mori         | |

### 8 Sep.

| CST (UTC+8)    | JST (UTC+9)    | Speaker             | Title |
|---------------:|---------------:|:--------------------|-------|
| 09:30 -- 10:10 | 10:30 -- 11:10 | Shintarou Yanagida  | [Quick introduction to chiral quantization](#yanagida) |
| 10:20 -- 10:40 | 11:20 -- 11:40 | An-Si Bai           | |
| 10:50 -- 11:10 | 11:50 -- 12:10 | Shun Wakatsuki      | |
| 13:30 -- 14:10 | 14:30 -- 15:10 | Qin Li              | |
| 14:20 -- 14:40 | 15:20 -- 15:40 | Masamune Hattori    | |
| 14:50 -- 15:10 | 15:50 -- 16:10 |                     | Closing |


Abstracts
----------------

### Ansis Rosmanis (Nagoya University) {#rosmanis}

Title :
Quantum computation and simulation, algorithms and complexity

Abstract :
We consider quantum search algorithms that have access to a noisy oracle that, for every oracle call, with probability $$p>0$$ completely depolarizes the query registers, while otherwise working properly. Previous results had not ruled out quantum $$O(\sqrt{n})$$-query algorithms in this setting, even for constant $$p$$. We show that for all $$p$$ in $$[1/\sqrt{n}, 1-\Omega(1)]$$, the quantum noisy-query complexity of the unstructured search is $$\Omega(np)$$, which is tight up to logarithmic factors. The same bound holds for the dephasing noise and even when, for every oracle call, the algorithm is provided with a flag indicating whether the noise has occurred.

### Harumichi Nishimura (Nagoya University) {#nishimura}

Title:
More Distributed Quantum Merlin-Arthur Protocols: Improvement and Extension

Abstract:
Quantum Merlin-Arthur (QMA) is a quantum analogue of  the complexity
class NP, that is, the class of Yes-No problems such that any Yes
instance can be verified by a party called the verifier (or Arthur) with
the help of a quantum message (a.k.a quantum witness) from a party
called the prover (or Merlin).  In 2021, Fraigniaud et al. introduced a
distributed version of QMA protocols (dQMA protocols) where there are
multiple verifiers who consists of a network. They gave an efficient
dQMA protocols for the equality problem that ask whether all the input
strings owned by a subset of the verifiers are the same. In this talk, I
first present the formulation of dQMA protocols and revisit the protocol
by Fraigniuad et al. After that, I present improvements of the protocol
in several aspects, and also provide the dQMA protocols for more
extended problems.

### Qisheng Wang (Nagoya University) {#qwang}

Title: Quantum Lower Bounds by Sample-to-Query Lifting

Abstract:
The polynomial method by Beals, Buhrman, Cleve, Mosca, and de Wolf (FOCS
1998) and the adversary method by Ambainis (STOC 2000) have been shown
powerful in proving quantum query lower bounds for a wide variety of
problems. In this paper, we propose an arguably new method for proving
quantum query lower bounds by a quantum sample-to-query lifting theorem,
which is from an information theory perspective. Using this method, we
obtain the following new results:
1. A quadratic relation between quantum sample and query complexities
regarding quantum property testing, which is optimal and saturated by
quantum state discrimination.
2. A matching lower bound $$\Omega(\beta)$$ for quantum Gibbs sampling at inverse
temperature $$\beta$$, showing that the quantum Gibbs sampler by Gilyén, Su,
Low, and Wiebe (STOC 2019) is optimal.
3. A new lower bound $$\Omega(1/\sqrt{\Delta})$$ for the entanglement entropy problem with
gap $$\Delta$$, which was recently studied by She and Yuen (ITCS 2023).
In addition, we also provide unified proofs for some known lower bounds
that have been proven previously via different techniques, including
those for phase/amplitude estimation and Hamiltonian simulation.

### Kohtaro Kato (Nagoya University) {#kato}

Title: Exact and Local Compression of Quantum Bipartite States

Abstract: Quantum data compression is one of the most fundamental quantum information processing. We study an exact local compression of a quantum bipartite state; that is, exact and noiseless one-shot quantum data compression of general mixed state sources without side information or entanglement assistance. We provide a formula for computing the minimal achievable compression dimensions, provided as a minimization of the Schmidt rank of a particular pure state constructed from that state. We will then discuss a possible application to tensor-network states.

### Liang Kong (Southern University of Science and Technology) {#kong}

Title: A morphism between two QFTs

Abstract: A morphism between two mathematical objects of the same type (e.g. groups, algebras, representations, categories, etc.), which preserves the defining structures of the objects, is one of the most important notions in mathematics. However, how to define such a morphism between two QFT's (or quantum phases) had never been considered in physics until [arXiv:1502.01690](https://arxiv.org/abs/1502.01690). This notion is getting more and more important in the study of QFTs especially after the rise of generalized high symmetries in recent years. In this talk, I will give a review of this notion and discuss some of its applications in mathematics and physics.

### Jiaheng Zhao (Chinese Academy of Sciences) {#zhao}

Title: Center functors and condensation theory

Abstract:
The notion of center plays a key role in the study of topological order. In this talk I will introduce the center functor in the context of seperable n-categories. Then I will talk about some generalizations and applications in condensation theory.

### Ryo Hayami (Nagoya University) {#hayami}

Title:dg symplectic geoemetry and (higher) Poisson vertex algebras

Abstract: One-to-one correspondence between Courant-Dorfman algebras and
Poisson vertex algebras can be seen as an algebraic generalization of
the relation between generalized tangent bundles and Alekseev-Strobl
currents. In terms of dg symplectic geometry, Alekseev-Strobl currents
are 1-dimensional BFV(Batalin-Fradkin-Vilkovisky) currents whose target
datum are degree 2 dg symplectic manifolds(Courant algebroids). In this
talk, I will introduce a higher version of the one-to-one
correspondence, which is an algebraic generalization of
$$(n-1)$$-dimensional BFV currents whose target datum are degree n dg
symplectic manifolds. Moreover, noncommutative analogue of the
correspondence (dg bisymplectic geometry and (higher) double Poisson
vertex algebras) will be discussed. This talk is partly based on
[arxiv:2302.11420](https://arxiv.org/abs/2302.11420).

### Francesco Buscemi (Nagoya University) {#buscemi}

Title: Measurement sharpness and incompatibility as quantum resources

Abstract: In this talk I will discuss two aspects of quantum measurements, namely sharpness and incompatibility, from a resource-theoretic perspective. Our construction settles a debate in the literature and fills some gaps in the mathematical and conceptual foundations of quantum theory.

References:
* F.B., E. Chitambar, W. Zhou; PRL 124, 120401 (2020)
* F.B., K. Kobayashi, S. Minagawa, A. Tosini, P. Perinotti; Quantum 7, 1035 (2023)
* F.B., K. Kobayashi, S. Minagawa; [arXiv:2303.07737](https://arxiv.org/abs/2303.07737)


### Masahito Hayashi (CUHK-SZ, IQA, and Nagoya Univ.) {#hayashi}

Title: Tight Cramér-Rao type bounds for multiparameter quantum metrology through conic programming

Abstract:
In the quest to unlock the maximum potential of quantum sensors, it is of paramount importance to have practical measurement strategies that can estimate incompatible parameters with best precisions possible. However, it is still not known how to find practical measurements with optimal precisions, even for uncorrelated measurements over probe states. Here, we give a concrete way to find uncorrelated measurement strategies with optimal precisions. We solve this fundamental problem by introducing a framework of conic programming that unifies the theory of precision bounds for multiparameter estimates for uncorrelated and correlated measurement strategies under a common umbrella. Namely, we give precision bounds that arise from linear programs on various cones defined on a tensor product space of matrices, including a particular cone of separable matrices. Subsequently, our theory allows us to develop an efficient algorithm that calculates both upper and lower bounds for the ultimate precision bound for uncorrelated measurement strategies, where these bounds can be tight. In particular, the uncorrelated measurement strategy that arises from our theory saturates the upper bound to the ultimate precision bound. Also, we show numerically that there is a strict gap between the previous efficiently computable bounds and the ultimate precision bound.

Link to arXiv paper: [arXiv:2209.05218](https://arxiv.org/abs/2209.05218)
It will appear in Quantum.

### Hayato Arai (Nagoya University) {#arai}

Title:
Derivation of Standard Quantum Theory via State Discrimination

Abstract:
It is a key issue to characterize the model of standard quantum theory
out of general models by an operational condition. The framework of
General Probabilistic Theories (GPTs) is a new information theoretical
approach to single out standard quantum theory. It is known that
traditional properties, for example, Bell-CHSH inequality are not
sufficient to single out standard quantum theory among possible models
in GPTs. As a more precise property, we focus on the bound of the
performance for an information task called state discrimination in
general models. We give an equivalent condition for outperforming the
minimum discrimination error probability under the standard quantum
theory, which is given by the trace norm. Besides, by applying the
equivalent condition, we derive standard quantum theory out of classes
of general models under a condition.

### Shintarou Yanagida (Nagoya University) {#yanagida}

Title: Quick introduction to chiral quantization

Abstract: The notion of chiral quantization is a relatively new notion of quantization in pure mathematics,
appearing in the recent development of the theory of vertex algebras,
a mathematical formulation of two-dimensional chiral conformal field theory.

It involves attaching to a given Poisson manifold (the phase space of a classical mechanical system)
a sheaf of vertex algebras whose 0th associated graded part recovers the
original structure sheaf with Poisson structure.
I will give a short introduction to this topic.
 
Link
----------------

* [SUSTech-Nagoya 2022](https://www.math.nagoya-u.ac.jp/~yanagida/SUSTech-Nagoya2022.html)
* [SUSTech-Nagoya 2021](https://www.math.nagoya-u.ac.jp/~yanagida/SUSTech-Nagoya2021.html)

